[openNetVM][onvm]
==

About
--
openNetVM is a high performance NFV platform based on [DPDK][dpdk] and [Docker][docker] containers.  openNetVM is SDN-enabled, allowing the network controller to provide rules that dictate what network functions need to process each packet flow.

openNetVM is an open source version of the NetVM platform described in our [NSDI 2014 paper][nsdi04], released under the [BSD][license] license. 

You can find information about research projects building on [OpenNetVM][onvm] at the [UCR/GW SDNFV project site][sdnfv]. _Please [let us know](mailto:timwood@gwu.edu) if you use OpenNetVM in your research so we can add your papers to our list._

Installing
--
To install openNetVM, please see the [openNetVM Installation][install] guide for a thorough walkthrough.

Using openNetVM
--
openNetVM can be used in a variety of ways.  To get started with some examples, please see the [Example Uses][examples] guide

Creating NFs
--
The [NF Development][nfs] guide will provide what you need to start create your own NFs.

Dockerize NFs
--
NFs can be run inside docker containers, with the NF being automatically or hand started. For more informations, see our [Docker guide][docker-nf].



[onvm]: http://sdnfv.github.io/onvm/
[sdnfv]: http://sdnfv.github.io/
[license]: LICENSE
[dpdk]: http://dpdk.org
[docker]: https://www.docker.com/
[nsdi04]: http://faculty.cs.gwu.edu/timwood/papers/14-NSDI-netvm.pdf
[install]: docs/Install.md
[examples]: docs/Examples.md
[nfs]: docs/NF_Dev.md
[docker-nf]: docs/Docker.md
