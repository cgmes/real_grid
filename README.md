# Real Grid

The Real Grid Test Configuration for the ENTSO-E Common Grid Model Exchange Standard (CGMES) Conformity Assessment.

The Real Grid Test Configuration represents a bus-branch model of a real power system.
The test configuration does not include boundary set as the model has no dangling references to external power systems or boundaries.
It includes only useful switches, so the topology can be considered as semi-detailed topology.

## Trig

The "trig" branch of this repository contains the Real Grid Test Configuration in [TriG](https://www.w3.org/TR/trig/) format.
CIM/XML is a domain specific syntax used in the energy sector.
It is based on RDF/XML, but is not compatible.
As a result, it can not be used directly with generic RDF tools and libraries.
TriG is an extension to [TURTLE](https://www.w3.org/TR/turtle/) for representing complete RDF datasets.
TURTLE and TriG are well established syntaxes for RDF and are supported by many tools and libraries.
TriG allows metadata to be associated with named graphs.
This allows separate parts of a CGMES model to be stored in a single text file and avoids the need to use an opaque ZIP archive.

## Note

This is an unofficial source for the Real Grid Test Configuration.
Please refer to [ENTSO-E](https://www.entsoe.eu) for official resources.