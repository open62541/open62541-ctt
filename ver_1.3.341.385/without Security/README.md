# open62541-ctt
Conformance test configuration for the open62541 project with CTT version 1.3.341.385. The newer version of CTT contains bug fixes. Optional features for testing in previous version are made mandatory.

The configuration matches the `/examples/server_ctt.c` server implementation in the open62541 project.

- open62541 master: Configuration for the conformance units that are supported on the master branch

## Issues

- Security User Name Password (12 test left)
- Subscription Publish Min 02 (1 test left)
 
## Resolved Issues
- View Minimum Continuation Point 01 (1 test)
- View RegisterNodes (2 test)
- View TranslateBrowsePath (1 test)

## Attention!
Only upload the open62541.ctt.xml and open62541.selection.xml files.
The other script definitions are part of the CTT and need to be licensed from the OPC Foundation.

If such files are committed by accident, rewrite the history of the repository to make them inaccessible.
