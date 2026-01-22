\# STRATIFYHF Heart Failure Ontology (SHFO)



This repository contains the \*\*STRATIFYHF Heart Failure Ontology (SHFO)\*\*, a schema-level OWL ontology

designed to support semantic harmonization of multimodal data for \*\*heart failure diagnosis and risk stratification\*\*.



SHFO provides a unified semantic framework that integrates:

\- conventional clinical measurements,

\- laboratory and imaging-related variables,

\- patient-reported outcomes,

\- mobile application data,

\- and continuous wearable-derived physiological signals.



The ontology was developed within the STRATIFYHF project and is grounded in a clinician-defined

reference data model to ensure clinical relevance and interoperability.



---



\## Version



\*\*Current version:\*\* 1.0.0  

This is the \*\*initial public release\*\* of the ontology.



Version 1.0.0 represents a stable, citable release corresponding to the ontology described

in the associated scientific publication.



---



\## Scope and Design Principles



SHFO is a \*\*schema-level ontology\*\* intended for:

\- semantic harmonization,

\- standardized data representation,

\- validation of heterogeneous heart failure data sources.



The ontology does \*\*not\*\* include instance-level data or object properties.

Instead, it focuses on:

\- class definitions,

\- data properties,

\- value constraints,

\- and mappings to established clinical terminologies.



This design supports interoperability, scalability, and integration with

clinical decision support systems and AI-based analytics pipelines.



---



\## Interoperability and Standards Alignment



SHFO aligns with established clinical and technical standards, including:

\- SNOMED CT (clinical concepts),

\- LOINC (observations and measurements),

\- UCUM (units of measure),

\- and FHIR-compatible modeling patterns.



Where no suitable external terminology exists (e.g., for mobile app–specific

or wearable-derived constructs), STRATIFYHF-specific identifiers are introduced

to preserve semantic completeness and extensibility.



---



\## Ontology IRI Policy



The ontology currently uses a \*\*provisional namespace and IRIs\*\* that serve as stable identifiers

for development, dissemination, and citation purposes.



These IRIs are \*\*not guaranteed to resolve\*\* to web resources.

They may be updated in future releases if a permanent hosting domain is established.



The \*\*canonical and authoritative source\*\* of the ontology is this Git repository.



---



\## Files



\- `Ontology.ttl` — STRATIFYHF Heart Failure Ontology (OWL/Turtle syntax)



---



\## Citation



If you use or reference this ontology, please cite:



\*\*STRATIFYHF Heart Failure Ontology (SHFO), version 1.0.0\*\*  

Available at: https://github.com/DBoucharas/STRATIFYHF



The ontology is described in the following publication:



Boucharas et al., \*Semantic Harmonization of Wearable and Clinical Data for Heart Failure Diagnosis \& Risk Stratification\*, 2025.



---



\## License



This ontology is licensed under the \*\*Creative Commons Attribution 4.0 International (CC BY 4.0)\*\* license.



You are free to:

\- Share — copy and redistribute the material in any medium or format

\- Adapt — remix, transform, and build upon the material for any purpose



Under the following terms:

\- Attribution — appropriate credit must be given to the authors and the STRATIFYHF project.



License text: https://creativecommons.org/licenses/by/4.0/

