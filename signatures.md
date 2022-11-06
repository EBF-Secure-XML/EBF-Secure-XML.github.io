[Benefits](benefits) | [Digital Signatures](signatures)  | [History](history) | [Publications](publications) | [Contributors](contributors) 

## Digital Signatures

In SOFT Instrument Link, both worklist and result 
records can be digitally signed to improve security and 
traceability. The signature mechanism is based on the [XML DSIG Specification](https://www.w3.org/TR/xmldsig-core2/), 
as defined by the [World Wide Web Consortium (W3C) Signature Working Group](https://www.w3.org/Signature/).

Any AnIML document can be covered with one or more 
signatures. By building on XML DSIG, off-the-shelf tools
for creating and verifying signatures are widely available.

W3C XML DSIG provides several valuable characteristics:
* Attributability – you can tell who made a signature
* Tamper-evidence – you can tell if data has changed since signing
* Multi-signature support – multiple people and/or systems can sign a data set (approval workflows)
* Automated validation – before accepting a file, instrument or LIMS can confirm its provenance
* Integrates with enterprise PKI – some organizations already have certificate management infrastructures
* Stored in XML – easy to read and write, broad developer experience
* Royalty free, widely implemented – free libraries for Java, .net, …