# CDSS4PCP

Our investigation team develops publicly accessible, reusable, and machine-interpretable clinical decision support system (CDSS) rules by leveraging an upper-level ontology for CDSS. We developed CDSS modules, including the routine CDSS function and functionalities for CDSS rule management and maintenance. We implemented the module in OpenMRS and demonstrated the functionality through CDS rules for CDC-recommended immunization schedules. Our efforts will save duplicate work by multiple stakeholders of CDS rules and establish a critical foundation for achieving interoperability for individuals’ immunization records. Our investigation also aims to enable primary care providers, especially those in small primary care practices, to manage and maintain CDS rules independently, keeping CDS updated, valid, and working to its full potential, thereby benefiting the large population served by such practices. On this page, we share the CDSS rules in multiple formats, including clinical quality language rules (CQL), CDSS modules (common and adaptor for OpenMRS), a CQL rule testing module, and an active learning pipeline that facilitates manual ontology construction and maintenance.




## Projects
### CDSS Modules for OpenMRS and OpenEMR
#### OpenMRS
- [OpenMRS](https://github.com/xjing16/EMR_EHR4CDSSPCP/tree/main/OpenMRS): The code for the OpenMRS adapter module, frontend module and documentation.
- [Documentation for OpenMRS modules](https://github.com/xjing16/EMR_EHR4CDSSPCP/tree/main/OpenMRS/docs/README.md): The documentation for the OpenMRS adapter module and frontend module.

#### OpenEMR
- [OpenEMR](https://github.com/xjing16/EMR_EHR4CDSSPCP/tree/main/OpenEMR): The code for the OpenEMR adapter module.

### Common Module
- [cdss-common](https://github.com/CDSS4PCP/cdss-common): The common component for running CDS on the frontend.
- [CDSS Rule Standards](https://github.com/CDSS4PCP/cdss-common/blob/d79e59d44dbc4c19b25d0281de044b743cdbf0c1/CQL%20Rule%20Standard%20Specification.md): A document outlining the format and expectations for wring new CQL rules.

#### Other
- [cdss-testing-harness](https://github.com/CDSS4PCP/cdss-testing-harness.git): The CQL rule testing framework.
- [CDSS_Rules_Repository](https://github.com/CDSS4PCP/CDSS_Rules_Repository): The collection of CDSS rules taht we have built.
- [rule-modification-service](https://github.com/CDSS4PCP/rule-modification-service): A docker servcie taht allows to inject values into CQL to allow for modifying them.
- [browserfy-cql-exec-vsac](https://github.com/CDSS4PCP/browserfy-cql-exec-vsac): A client-based valueset resolver forked form [cql-exec-vsac](https://github.com/cqframework/cql-exec-vsac).
- Contributed to [cql-execution](https://github.com/cqframework/cql-execution/pull/332) by implementing the `ExpandValueset` operator.

---
### Automatic Identication of CDSS Ontology Entity Candidates
- [NLP_KPIdentify](https://github.com/CDSS4PCP/NLP_KPIdentify): A NLP pipeline for Keyphrase Identification with a Limited Labeled Dataset Using Deep Active Learning and Domain Adaptation.
- AL measurements, strategies, and results [(Full paper)](https://github.com/CDSS4PCP/NLP_KPIdentify/blob/active_learning_files/ActiveLearningStrategiesResults/Active%20Learning%20Strategies_V8_20250808.pdf)
- Hyperparameters tuning 
- Active learning pipelines
- System to incorporate HDE feedback (Front + back) and initiate AL
- AL pipeline results
- AL pipelines performances tracking over time
- Writings

---
See more [here](https://cdss4pcp.com/#/)
