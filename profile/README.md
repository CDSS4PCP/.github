# CDSS4PCP

Our investigation will develop publicly accessible, reusable, upper-level clinical decision support (CDS) ontology and machine-interpretable CDS rules for CDC-recommended immunization schedules, which will save duplicate effort by multiple stakeholders of CDS rules and build a critical foundation for achieving interoperability for individuals’ immunization records. Our investigation also aims to enable primary care providers, especially in small primary care practices, to manage and maintain CDS rules independently to keep CDS updated, useful, and working to its full potential and to benefit the large population served by such practices.






## Projects
### CDSS Modules for OpenMRS and OpenEMR
#### OpenMRS
- [OpenMRS](https://github.com/xjing16/EMR_EHR4CDSSPCP/tree/main/OpenMRS): The code for the OpenMRS adapter module, frontend module and documentation.
- [Documentation for OpenMRS modules ](https://github.com/xjing16/EMR_EHR4CDSSPCP/tree/main/OpenMRS/docs/README.md): The documentation for the OpenMRS adapter module and frontend module.

#### OpenEMR
- [OpenEMR](https://github.com/xjing16/EMR_EHR4CDSSPCP/tree/main/OpenEMR): The code for the OpenEMR adapter module.

### Common Module
- [Common Module](https://github.com/xjing16/EMR_EHR4CDSSPCP/tree/main/Common): The common component for running CDS on the frontend.
- [CDSS Rule Standards](#): A document outlining the format and expectations for wring new CQL rules.

#### Other
- [cdss-testing-harness](https://github.com/DrSmCraft/cdss-testing-harness.git): The CQL rule testing framework.
- [CDSS_Rules_Repository](https://github.com/CDSS4PCP/CDSS_Rules_Repository): The collection of CDSS rules taht we have built.
- [rule-modification-service](https://github.com/DrSmCraft/rule-modification-service): A docker servcie taht allows to inject values into CQL to allow for modifying them.
- [browserfy-cql-exec-vsac](https://github.com/DrSmCraft/browserfy-cql-exec-vsac): A client-based valueset resolver forked form [cql-exec-vsac](https://github.com/cqframework/cql-exec-vsac).
- Contributed to [cql-execution](https://github.com/cqframework/cql-execution/pull/332) by implementing the `ExpandValueset` operator.

---
### Automatic Identication of CDSS Ontology Entity Candidates
- [NLP_KPIdentify](https://github.com/CDSS4PCP/NLP_KPIdentify): A NLP pipeline for Keyphrase Identification with a Limited Labeled Dataset Using Deep Active Learning and Domain Adaptation.

---
See more [here](https://cdss4pcp.com/#/)
