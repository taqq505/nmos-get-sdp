nmos-get-sdp
=====
nmos-get-sdp is a software tool for downloading SDP files from nodes compliant with ST 2110 NMOS IS-04.

This tool solely downloads SDP files from IS-04 nodes.
Since it is implemented using only Python's standard modules, setting up the runtime environment is straightforward.
You can download the SDP file of the target node in just three lines of code.
#ST2110 #NMOS

Usage
=====
Clone this repository and then run the following commands:
'''
  $ git clone https://github.com/taqq505/nmos-get-sdp
  $ cd nmos-get-sdp
  $ ./nmos-get-sdp {node_IP} -p {port_no}
'''
  Replace {node_IP} with the IP address of the target node.
You can specify the port number by adding the -p option.

The tool automatically downloads the SDP file from the latest version of IS-04.

License
=======

MIT

