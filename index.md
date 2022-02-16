---
title: Secure Instrument Link
---
# Secure Instrument Link
This project describes a secure XML-based format
for data exchange between LIMS/ELN software and LC-MS
instruments. The project originates in regulated
bioanalysis, but is open to other areas as well. 

Secure Instrument Link offers a secure exchange mechanism 
for two main interactions:
* Worklist submission (LIMS to instrument)
* Result reporting (Instrument to LIMS)

### Documentation and examples
See the [Github repository](https://github.com/EBF-Secure-XML/examples) for documentation and example files.

### Future improvements
The project team sees the following opportunities
for future expansion of this format:

#### Plate reader support
Currently, only LC-MS instruments are supported. We should
add support for plate-based assays, since they play a 
significant role in the bioanalysis domain.

#### File-less exchange
Today, this format is file-based. In the future, a file-less
mechanism (such as [SiLA](https://sila-standard.com) or web services) could be considered.

