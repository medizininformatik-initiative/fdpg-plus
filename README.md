# fdpg-plus

This repository is used to:
- Collect issues spanning multiple repositories
- Collect issues from the community

## Our repositories

Overview of the repositories currently maintained by the fdpg-plus project:

| Repository Name                                                                                     | Repository Information | Description                                                              | Language     |
|------------------------------------------------------------------------------------------------------|--------|--------------------------------------------------------------------------|--------------|
| [torch](https://github.com/medizininformatik-initiative/torch)                                      |        | Extracts data from FHIR Server according to CRTDL                        | Java         |
| [fhir-ontology-generator](https://github.com/medizininformatik-initiative/fhir-ontology-generator)  |        | Generate FHIR ontologies                                                 | Java         |
| [dataportal-availibility-updater](https://github.com/medizininformatik-initiative/dataportal-availibility-updater) |        | *No description available*                                               | Python       |
| [feasibility-deploy](https://github.com/medizininformatik-initiative/feasibility-deploy)            |        | Shell scripts for feasibility deployment using docker compose            | Shell        |
| [feasibility-gui](https://github.com/medizininformatik-initiative/feasibility-gui)                  |        | Frontend UI for dataportal                                               | TypeScript   |
| [feasibility-backend](https://github.com/medizininformatik-initiative/feasibility-backend)          | [![Build](https://github.com/medizininformatik-initiative/feasibility-backend/actions/workflows/ci.yml/badge.svg)](https://github.com/medizininformatik-initiative/feasibility-backend/actions/workflows/ci.yml) [![OpenSSF Scorecard](https://api.scorecard.dev/projects/github.com/medizininformatik-initiative/feasibility-backend/badge)](https://scorecard.dev/viewer/?uri=github.com/medizininformatik-initiative/feasibility-backend) [![codecov](https://codecov.io/gh/medizininformatik-initiative/feasibility-backend/graph/badge.svg?token=0E6UPL7I5K)](https://codecov.io/gh/medizininformatik-initiative/feasibility-backend) [![GitHub Release](https://img.shields.io/github/v/release/medizininformatik-initiative/feasibility-backend?sort=semver&display_name=tag&style=flat&logo=github&label=current)]()                   | Backend of the feasibility-gui (dataportal)  | Java         |
| [sq2cql](https://github.com/medizininformatik-initiative/sq2cql)                                    |        | Convert CCDL (before SQ) to CQL                                          | Java         |
| [fhir-data-evaluator](https://github.com/medizininformatik-initiative/fhir-data-evaluator)          |        | Stratify FHIR data of a FHIR Server                                      | Java         |
| [mii-testdata](https://github.com/medizininformatik-initiative/mii-testdata)                        |        | Assorted MII test-data tools and provisioning of testdata                |              |
| [flare](https://github.com/medizininformatik-initiative/flare)                                      |        | Execute a CCDL against FHIR server using FHIR search                     | Java         |
| [mii-process-feasibility](https://github.com/medizininformatik-initiative/mii-process-feasibility)  |        | FDPG+ feasibility process plugins                                        | Java         |
| [fdpg-test-env](https://github.com/medizininformatik-initiative/fdpg-test-env)                      |        | Deployment of development environment for FDPG+                          | Jinja        |
| [kds-report](https://github.com/medizininformatik-initiative/kds-report)                            |        | Creates kds-report and provides it                                       | Python       |
| [dataportal-es-init](https://github.com/medizininformatik-initiative/dataportal-es-init)            |        | Initialises elastic search for the dataportal with ontology              | Shell        |
| [feasibility-monitoring](https://github.com/medizininformatik-initiative/feasibility-monitoring)    |        | Automatic monitoring for the Dataportal                                  | Python       |
| [clinical-resource-transfer-definition-language](https://github.com/medizininformatik-initiative/clinical-resource-transfer-definition-language) |        | CRTDL - formal definition of a data extraction                           |              |
| [kds-report-converter](https://github.com/medizininformatik-initiative/kds-report-converter)        |        | Convert DSF kds report to json formatted kds report                      | Python       |
| [fdpg-ontology-translation](https://github.com/medizininformatik-initiative/fdpg-ontology-translation) |        | Generates translations for ontologies using deepl                        | Python       |
| [Projectathon7-VHF-DataExtraction](https://github.com/medizininformatik-initiative/Projectathon7-VHF-DataExtraction) |        | Data Extraction for Projectathon 7                                       | Python       |
| [clinical-cohort-definition-language](https://github.com/medizininformatik-initiative/clinical-cohort-definition-language) |        | CCDL - formal definition of a cohort/feasibility                         | Python       |
| [fdpg-query-data-validation](https://github.com/medizininformatik-initiative/fdpg-query-data-validation) |        | Validate FDPG FHIR data quality                                          | Python       |
| [fhir-server-examples](https://github.com/medizininformatik-initiative/fhir-server-examples)        |        | Docker & Makefile examples for FHIR servers                              |              |
| [feasibility-auth](https://github.com/medizininformatik-initiative/feasibility-auth)                |        | Keycloak setup for dataportal (dev)                                      |              |
| [fdpg-plus](https://github.com/medizininformatik-initiative/fdpg-plus)                              |        | FDPG+ core repo                                                          |              |
| [fhir-performance-test](https://github.com/medizininformatik-initiative/fhir-performance-test)      |        | Test the paging performance of your FHIR server                          |              |


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


