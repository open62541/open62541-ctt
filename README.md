# open62541-ctt
Conformance test configuration for the open62541 project.

The configuration matches the `/examples/server_ctt.c` server implementation in the open62541 project.
The following CTT projects are tracked here:

- open62541 master: Configuration for the conformance units that are supported on the master branch
- open62541 embedded: Configuration for the Embedded UA Server Profile (work in progress)
- ver_1.3.441.385: Configuration for newer version of CTT
- public_beta_1.3.341.389: New bug fixed version of CTT. Click [here](https://opcfoundation.org/developer-tools/certification-test-tools/opc-ua-compliance-test-tool-uactt/) to download.

## Attention!
Only upload the open62541.ctt.xml and open62541.selection.xml files.
The other script definitions are part of the CTT and need to be licensed from the OPC Foundation.

If such files are committed by accident, rewrite the history of the repository to make them inaccessible.
