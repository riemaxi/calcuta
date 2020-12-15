# Project calcuta

This is the world's largest calculus engine

Every node (dust) is identified by the name of the function it implements, the domain area of expertise, the input, and output arguments.

A calculation is recursely defined as:

- dust
- dust | calculation

A star is a hub where dust can be published so calculation users (molders) can use itin order to create calculations.

Stars can be clustered by domains of expertise and other criteria.

A dust is stateless and can be implemented by any device with a host address.

Here is an example of a dust:

name: math/algebra/string/sum/x_y.z
host: http://46.30.213.202
description: concat two strings
author: crue4crue

usage host/math/algebra/string/sum/world

with response:
1\nhello\nworld

or http standard error:
0\n5xx
