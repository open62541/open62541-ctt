# open62541-ctt
Conformance test configuration for the open62541 project.

The configuration matches the `/examples/server_ctt.c` server implementation in the open62541 project.
The following CTT projects are tracked here:

- open62541 master: Configuration for the conformance units that are supported on the master branch
- open62541 embedded: Configuration for the Embedded UA Server Profile (work in progress)
- open62541 certify: Configuration that shall be used for Certification of open62541 stack (CTT v1.3.341.389 public beta). The selected profiles and facets are:
	1. Micro Embedded Device Server
	2. Method Server Facet
	3. Security Policy
		- Basic128Rsa15
		- Basic256
		- Basic256Sha256

## Attention!
Only upload the open62541.ctt.xml and open62541.selection.xml files.
The other script definitions are part of the CTT and need to be licensed from the OPC Foundation.

If such files are committed by accident, rewrite the history of the repository to make them inaccessible.
