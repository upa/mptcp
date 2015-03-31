Direct Code Execution [![Build Status](https://travis-ci.org/direct-code-execution/net-next-sim.png)](https://travis-ci.org/direct-code-execution/net-next-sim)
===============================


http://www.nsnam.org/overview/projects/direct-code-execution/


how to use mptcp on ns-3-dce with various topologies.

1. git clone https://github.com/upa/mptcp.git
2. cd mptcp
3. make defconfig ARCH=sim
4. make library ARCH=sim
5. make testbin -C arch/sim/test
  * compile ns-3-dce. many packages are required.
  * if use it with iplb, see https://github.com/upa/iplb/tree/master/benchmark
  * and copy tcpgen compiled with DCE=yes option in flowgen, or use iperf.
