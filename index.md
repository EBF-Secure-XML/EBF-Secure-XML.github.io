---
title: Secure LC-MS Instrument Connectivity
---
# Secure LC-MS Instrument Connectivity
This project describes a secure XML-based format
for data exchange between LIMS/ELN software and LC-MS
instruments in the domain of bioanalysis.

The goal is to provide a secure exchange mechanism for two main interactions:
* Worklist submission (LIMS to instrument)
* Result reporting (Instrument to LIMS)

### Documentation and examples
See the [Github repository](https://github.com/EBF-Secure-XML/examples) for documentation and example files.

### Future improvements
The project team sees the following opportunities for future
expansion of this format:

#### Plate reader support
Currently, only LC-MS instruments are supported. We should
add support for plate-based assays, since they play a significant
role in the bioanalysis domain.

#### File-less exchange
Today, this format is file-based. In the future, a file-less
mechanism (such as SiLA or web services) could be considered.

