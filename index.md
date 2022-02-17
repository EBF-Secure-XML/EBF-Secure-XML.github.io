---
title: Secure Instrument Link
---
# Secure Instrument Link
Secure Instrument Link is a secure mechanism to integrate analytical instruments with LIMS and ELN software.

It specifies an XML-based format for data exchange between LIMS/ELN software and LC-MS instruments. The project originates in regulated bioanalysis, but is open to other areas as well. [Learn more about the history](history).

Secure Instrument Link offers a secure exchange mechanism 
for two main interactions:
* Worklist submission (LIMS to instrument)
* Result reporting (Instrument to LIMS)

The exchange is secured through [digital signatures](signatures).

### Documentation and examples
See the [Github repository](https://github.com/EBF-Secure-XML/examples) for documentation and example files.

### Future improvements
The project team sees the following opportunities
for future expansion of this format:

#### Plate reader and ligand binding assay support
Currently, we only support LC-MS instruments.
Support for microplate readers and ligand binding assays 
is under consideration, since they play a 
significant role in the bioanalysis domain.

#### File-less exchange
Today, this format is file-based. In the future, a 
file-less mechanism (such as [SiLA](https://sila-standard.com) or web services) could be added.

