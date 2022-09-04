# Visual Subnet Tools

This repository is originally forked from https://github.com/davidc/subnets.

Additions and changes are detailed below.

---
## 🆕 Visual Fn::Cidr tool (NEW)

[https://kyhau.github.io/visual-subnet-tools/fncidr.html](https://kyhau.github.io/visual-subnet-tools/fncidr.html)

This tool calculates and shows the potential outputs of the AWS CloudFormation's intrinsic function [`Fn::Cidr`](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/intrinsic-function-reference-cidr.html) (or `!Cidr`), which returns an array of CIDR address blocks.

This tool takes the same input as `!Cidr [ ipBlock, count, cidrBits ]`.

See also this blog post https://blog.james.rcpt.to/2018/03/16/aws-vpcs-calculating-subnets-in-cloudformation/.

---
## 🚀 Visual subnet calculator (modified version of davidc/subnets)
[https://kyhau.github.io/visual-subnet-tools/subnets.html](https://kyhau.github.io/visual-subnet-tools/subnets.html)

### Run with docker

```
cd <project folder>
docker build . -t subnets
docker run -d -p 5001:80 --name subnets subnets
```
