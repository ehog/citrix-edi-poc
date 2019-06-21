# citrix-edi-poc
Contains all of the projects necessary for the EDI PoC for Citrix

## Project list
1. Test Scenario 0
 Read an EDI X12.850 (Purchase Order) file from a repository, validate the X12
structure and send the message out via AS2, sending the message encrypted.
2. Test Scenario 1
 Receive a batch of EDI X12.850 (Purchase Order) over an AS2 connection,
decompose the POs into single items, convert the POs into an XML format and
write them out to a repository.
3. Test Scenario 2
 Read an XML containing Invoice data from a repository, convert the XML to an
EDI X12.810 structure, lookup the partner in a database to determine the
desired sending transport and route the message to the appropriate outbound
channel.
