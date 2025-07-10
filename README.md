# fdpg-plus

This repository is used to:
- Collect issues spanning multiple repositories
- Collect issues from the community

## Our repositories


| Repository Name                               | Description                                                              | Language     | Link                                                                 |
|-----------------------------------------------|--------------------------------------------------------------------------|--------------|----------------------------------------------------------------------|
| torch                                         | Extracts data from FHIR Server according to CRTDL                        | Java         | [Link](https://github.com/medizininformatik-initiative/torch)       |
| fhir-ontology-generator                       | Generate FHIR ontologies                                                 | Java         | [Link](https://github.com/medizininformatik-initiative/fhir-ontology-generator) |
| dataportal-availibility-updater               | *No description available*                                               | Python       | [Link](https://github.com/medizininformatik-initiative/dataportal-availibility-updater) |
| feasibility-deploy                            | Shell scripts for feasibility deployment using docker compose            | Shell        | [Link](https://github.com/medizininformatik-initiative/feasibility-deploy) |
| feasibility-gui                               | Frontend UI for dataportal                                               | TypeScript   | [Link](https://github.com/medizininformatik-initiative/feasibility-gui) |
| feasibility-backend                           | Backend of the feasibility-gui (dataportal)                              | Java         | [Link](https://github.com/medizininformatik-initiative/feasibility-backend) |
| sq2cql                                        | Convert CCDL (before SQ) to CQL                                          | Java         | [Link](https://github.com/medizininformatik-initiative/sq2cql)      |
| fhir-data-evaluator                           | Stratify FHIR data of a FHIR Server                                      | Java         | [Link](https://github.com/medizininformatik-initiative/fhir-data-evaluator) |
| mii-testdata                                  | Assorted MII test-data tools and provisioning of testdata                |              | [Link](https://github.com/medizininformatik-initiative/mii-testdata) |
| flare                                         | Execute a CCDL against FHIR server using FHIR search                     | Java         | [Link](https://github.com/medizininformatik-initiative/flare)       |
| mii-process-feasibility                       | FDPG+ feasibility process plugins                                        | Java         | [Link](https://github.com/medizininformatik-initiative/mii-process-feasibility) |
| fdpg-test-env                                 | Deployment of development environment for FDPG+                          | Jinja        | [Link](https://github.com/medizininformatik-initiative/fdpg-test-env) |
| kds-report                                    | Creates kds-report and provides it                                       | Python       | [Link](https://github.com/medizininformatik-initiative/kds-report)  |
| dataportal-es-init                            | Initialises elastic search for the dataportal with ontology              | Shell        | [Link](https://github.com/medizininformatik-initiative/dataportal-es-init) |
| feasibility-monitoring                        | Automatic monitoring for the Dataportal                                  | Python       | [Link](https://github.com/medizininformatik-initiative/feasibility-monitoring) |
| clinical-resource-transfer-definition-language| CRTDL - formal definition of a data extraction                           |              | [Link](https://github.com/medizininformatik-initiative/clinical-resource-transfer-definition-language) |
| kds-report-converter                          | Convert DSF kds report to json formatted kds report                      | Python       | [Link](https://github.com/medizininformatik-initiative/kds-report-converter) |
| fdpg-ontology-translation                     | Generates translations for ontologies using deepl                        | Python       | [Link](https://github.com/medizininformatik-initiative/fdpg-ontology-translation) |
| Projectathon7-VHF-DataExtraction              | Data Extraction for Projectathon 7                                       | Python       | [Link](https://github.com/medizininformatik-initiative/Projectathon7-VHF-DataExtraction) |
| clinical-cohort-definition-language           | CCDL - formal definition of a cohort/feasibility                         | Python       | [Link](https://github.com/medizininformatik-initiative/clinical-cohort-definition-language) |
| fdpg-query-data-validation                    | Validate FDPG FHIR data quality                                          | Python       | [Link](https://github.com/medizininformatik-initiative/fdpg-query-data-validation) |
| fhir-server-examples                          | Docker & Makefile examples for FHIR servers                              |              | [Link](https://github.com/medizininformatik-initiative/fhir-server-examples) |
| feasibility-auth                              | Keycloak setup for dataportal (dev)                                      |              | [Link](https://github.com/medizininformatik-initiative/feasibility-auth) |
| fdpg-plus                                     | FDPG+ core repo                                                          |              | [Link](https://github.com/medizininformatik-initiative/fdpg-plus)   |
| fhir-performance-test                         | Test the paging performance of your FHIR server                          |              | [Link](https://github.com/medizininformatik-initiative/fhir-performance-test) |


## Community Issues

To create a coherent overview of all issues and how they relate to the release planning we ask the community to mostly use this repository to submit new issues,
unless the person adding an issue is certain which repository the issue belongs to. In this case the person should create the issue directly in the appropriate repository.

### Submitting an Issues

**1. Please ensure that any issue is described as clearly as possible.**

**2. When a new issues is submitted it will first have to be reviewed by one of us.**

**3. We will check the issue and give you feedback or ask additional questions.**

**4.  On Issue acceptance: Creating sub issues or moving issue to appropriate repository**
 - If your issue is accepted and spans multiple repositories we will keep the issue in this repository, create the appropriate sub issues in the respective repositories, link the from the issue here and update the progress of this issue as it goes through our system
 - If your issues is accepted and only concerns one repository we will create an issue in this repository, link this new issue from your created issue and close the issue here.

**5. Issue low priority or out of scope**
- Some issues might be considered within scope but very low priority due to resource constraints, which we would let you know via comment in your issue. In this case you have the option to fork the repository(ies) and implement the feature yourself. We would ask you to let us know if your are planning to implement a feature yourself as we might consider merging it in the main repositories.
- Some issues might be considered out of scope. These issues are issues we would not merge into the main repositories, however you have the option of maintaining a fork of the appropriate repository(ies) with your changes.


