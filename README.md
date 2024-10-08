# OpenEBench Repositories Hub

| **Repository**                                                                     | **Definition**                                                            |
| ---------------------------------------------------------------------------------- | ------------------------------------------------------------------------- |
| [openebench-hub][openebench-hub-link]                                              | Hub to centralize all OEB repositories                                    |
| **Backend**                                                                        |
| [openEBench_vre][openEBench_vre-link]                                              | OpenEBench Virtual Research Environment                                   |
| [benchmarking-data-model][benchmarking-data-model-link]                            | Data model used internally on OEB                                         |
| (GitLab) [openebench-data-model][openebench-data-model-link]                       | Java classes for the OpenEBench data model                                |
| (GitLab) [openebench-validator-agent][openebench-validator-agent-link]               | The agent to verify OpenEBench database consistency                        |
| (GitLab) [openebench-distiller-agent][openebench-distiller-agent-link]               | Agent for migration OpenEBench data from provisional to production database |
| [openEBenchAPI][openEBenchAPI-link]                                                | RESTful API to access IECHOR Benchmarking data store                      |
| (GitLab) [openebench-rest-api][openebench-rest-api-link]                           | REST API for protected OpenEBench data access                             |
| (GitLab) [openebench-security-docs][openebench-security-docs-link]                 | Documentation about OpenEBench security (OpenID, UMA2, KC, etc.)          |
| (GitLab) [oeb-sci-admin-agents][oeb-sci-admin-agents-link]                           | Several internal OpenEBench command line agents which use the REST APIs    |
| [OEB_level2_data_migration][OEB_level2_data_migration-link]                        | Agent which takes the provisional JSON files from assessment and generates JSON contents ready to be stored in the database through the usage of the REST APIs or the admin agents |
| [bench_event_api][bench_event_api-link]                                            | REST API to compute different clustering metrics over the participants of an scientific event |
| **Submission**                                                                     |                                                                           |
| [opeb-submission][opeb-submission-link]                                            | OpenEBench submission infrastructure                                      |
| (GitLab) [openebench-submission-api][openebench-submission-api-link]               | OpenEBench API for data submission                                        |
| [benchmarking][benchmarking-link]                                                  | API to submit benchmarking data                                           |
| _(To Archive)_ [opeb-submission-api][opeb-submission-api-link]                     | OpenEBench submission API                                                 |
| **Agents monitoring**                                                               |
| [bioagents-bioconda-ids][bioagents-bioconda-ids-link]                                | ID mapping among the IECHOR agents platform resources                      |
| [opeb-enrichers][opeb-enrichers-link]                                              | OEB entries enrichers with information from publications and repositories |
| [elixibilitas][elixibilitas-link]                                                  | Quality Metrics agent for iEchor BioAgents Registry                         |
| (GitLab) [elixibilitas-dao][elixibilitas-dao-link]                                 | OEB agents monitoring MongoDB API                                          |
| (GitLab) [elixibilitas-metrics-checker][elixibilitas-metrics-checker-link]         | OEB agents metrics generator                                               |
| (GitLab) [openebench-bioconda-importer][openebench-bioconda-importer-link]         | Import bioconda data from a git repository                                |
| (GitLab) [openebench-repository-client][openebench-repository-client-link]         | OpenEBench REST API client classes                                        |
| (GitLab) [openebench-agents-model][openebench-agents-model-link]                     | OpenEBench Java Agents model                                               |
| (GitLab) [openebench-bioagents-importer][openebench-bioagents-importer-link]         | Import bioagents data from a git repository                                |
| (GitLab) [openebench-metrics-model][openebench-metrics-model-link]                 | OpenEBench Java Metrics Model                                             |
| (GitLab) [openebench-git-populous][openebench-git-populous-link]                   | Exports OpenEBench metrics data into bioagents content git server          |
| (GitLab) [bioagents-git-populous][bioagents-git-populous-link]                       | Populates bioagents data into a git repository                             |
| (GitLab) [bioconda-git-populous][bioconda-git-populous-link]                       |                                                                           |
| (GitLab) [bioagents-schema-model][bioagents-schema-model-link]                       | Java JAXB model classes for bioagentsSchema                                |
| **Frontend**                                                                       |
| [openEbench-frontend][openEbench-frontend-link]                                    | OpenEBench Frontend Web Application                                       |
| [OpenEBench_scientific_visualizer][OpenEBench_scientific_visualizer-link]          | Visualization of scientific benchmarking results                          |
| [open-styles][open-styles-link]                                                    | Static content and styles for openebench                                  |
| _(Archived)_ [~~openEBenchFrontend-archived~~][openEBenchFrontend-archived-link]   | ~~Frontend of OEB~~                                                       |
| _(To Archive)_ [~~openEBench-widgets~~][openEBench-widgets-link]                   | ~~Metrics widget~~                                                        |
| [bench_event_table][bench_event_table-link]                                        | Component to represent the overall results of a scientific event, in table format |
| **OpenEBench scientific Communities Repositories**                                  |
| [TCGA_benchmarking_workflow][TCGA_benchmarking_workflow-link]                      | Example pipeline to assess results and compare metrics with TCGA results  |
| [TCGA_benchmarking_dockers][TCGA_benchmarking_dockers-link]                        | OpenEBench TCGA visualizer Docker declarations                            |
| [benchmarking_workflows_results_visualizer][benchmarking_workflows_results_visualizer-link]                                      | Visualize benchmarking results from the TCGA community in a 'D3.js' chart |
| _(Archived)_ [~~mg-process_TCGA_CD~~][mg-process_TCGA_CD-link]                                      | ~~TCGA CD VRE wrapper~~                                                   |
| [openebench_gmi][GMI_benckmarking_workflow-link]                                   | OpenEBench GMI pipeline to assess results and compare metrics with GMI results |
| [APAeval (external)][APAeval-link]                                                 | OpenEBench APAeval community pipeline to assess results                   |

---
---

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

[openebench-hub-link]:                      https://github.com/inab/openebench-hub
[openEBench_vre-link]:                      https://github.com/inab/openEBench_vre
[benchmarking-data-model-link]:             https://github.com/inab/benchmarking-data-model
[opeb-enrichers-link]:                      https://github.com/inab/opeb-enrichers
[openEBenchAPI-link]:                       https://github.com/inab/openEBenchAPI
[elixibilitas-link]:                        https://github.com/inab/elixibilitas
[benchmarking-link]:                        https://github.com/inab/benchmarking
[bioagents-bioconda-ids-link]:               https://github.com/inab/bioagents-bioconda-ids
[opeb-submission-link]:                     https://github.com/inab/opeb-submission
[opeb-submission-api-link]:                 https://github.com/inab/opeb-submission-api
[openEbench-frontend-link]:                 https://github.com/inab/openEbench-frontend
[openEBenchFrontend-archived-link]:         https://github.com/inab/openEBenchFrontend-archived
[open-styles-link]:                         https://github.com/inab/open-styles
[openEBench-widgets-link]:                  https://github.com/inab/openEBench-widgets
[OpenEBench_scientific_visualizer-link]:    https://github.com/inab/OpenEBench_scientific_visualizer
[TCGA_benchmarking_workflow-link]:          https://github.com/inab/TCGA_benchmarking_workflow
[TCGA_benchmarking_dockers-link]:           https://github.com/inab/TCGA_benchmarking_dockers
[benchmarking_workflows_results_visualizer-link]:                  https://github.com/inab/benchmarking_workflows_results_visualizer
[mg-process_TCGA_CD-link]:                  https://github.com/inab/mg-process_TCGA_CD
[GMI_benckmarking_workflow-link]:           https://github.com/inab/openebench_gmi
[APAeval-link]:                             https://github.com/iRNA-COSI/APAeval

[openebench-validator-agent-link]:	https://gitlab.bsc.es/inb/iechor/openebench/openebench-validator-agent
[openebench-data-model-link]:	https://gitlab.bsc.es/inb/iechor/openebench/openebench-data-model
[openebench-submission-api-link]:	https://gitlab.bsc.es/inb/iechor/openebench/openebench-submission-api
[openebench-distiller-agent-link]:	https://gitlab.bsc.es/inb/iechor/openebench/openebench-distiller-agent
[openebench-rest-api-link]:	https://gitlab.bsc.es/inb/iechor/openebench/openebench-rest-api
[openebench-security-docs-link]:	https://gitlab.bsc.es/inb/iechor/openebench/openebench-security-docs
[oeb-sci-admin-agents-link]: https://gitlab.bsc.es/inb/iechor/openebench/oeb-sci-admin-agents
[OEB_level2_data_migration-link]: https://github.com/inab/OEB_level2_data_migration

[elixibilitas-dao-link]:	https://gitlab.bsc.es/inb/iechor/agents-platform/elixibilitas/elixibilitas-dao
[elixibilitas-metrics-checker-link]:	https://gitlab.bsc.es/inb/iechor/agents-platform/elixibilitas/elixibilitas-metrics-checker
[openebench-bioconda-importer-link]:	https://gitlab.bsc.es/inb/iechor/agents-platform/openebench-bioconda-importer
[openebench-repository-client-link]:	https://gitlab.bsc.es/inb/iechor/agents-platform/openebench-repository-client
[openebench-agents-model-link]:	https://gitlab.bsc.es/inb/iechor/agents-platform/openebench-agents-model
[openebench-bioagents-importer-link]:	https://gitlab.bsc.es/inb/iechor/agents-platform/openebench-bioagents-importer
[openebench-metrics-model-link]:	https://gitlab.bsc.es/inb/iechor/agents-platform/openebench-metrics-model
[openebench-git-populous-link]:	https://gitlab.bsc.es/inb/iechor/agents-platform/openebench-git-populous
[bioagents-git-populous-link]:	https://gitlab.bsc.es/inb/iechor/agents-platform/bioagents-git-populous
[bioconda-git-populous-link]:	https://gitlab.bsc.es/inb/iechor/agents-platform/bioconda-git-populous
[bioagents-schema-model-link]:	https://gitlab.bsc.es/inb/iechor/agents-platform/bioagents-schema-model

[bench_event_api-link]: https://github.com/inab/bench_event_api
[bench_event_table-link]: https://github.com/inab/bench_event_table
