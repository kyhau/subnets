# Visual Subnet Tools

This repo is forked from https://github.com/davidc/subnets.

## Addition / Modification

- Visual Fn.Cidr tool (NEW): [https://kyhau.github.io/visual-subnet-tools/fncidr.html](https://kyhau.github.io/visual-subnet-tools/fncidr.html)

- Visual subnet calculator (modified): [https://kyhau.github.io/visual-subnet-tools/subnets.html](https://kyhau.github.io/visual-subnet-tools/subnets.html)


### See also

- https://blog.james.rcpt.to/2018/03/16/aws-vpcs-calculating-subnets-in-cloudformation/


# Run with docker

```
cd <project folder>
docker build . -t subnets
docker run -d -p 5001:80 --name subnets subnets
```
