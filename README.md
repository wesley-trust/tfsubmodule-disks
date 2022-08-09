# tfsubmodule-disks
Terraform submodule for deploying disks and attaching to VMs in Azure, with Terratest Unit/Integration testing via Go, and Regula (OPA) Policy as Code scanning in an Azure DevOps Pipeline
## [CI/CD Pipeline](https://dev.azure.com/wesleytrust/Terraform/_build?definitionId=92)
Select a stage to view in Azure DevOps. *Note that 'Skipped' stages in the last run, will show as "unknown" by design.*
| Pipeline |
| :------: |
|[![Build Status](https://dev.azure.com/wesleytrust/Terraform/_apis/build/status/Modules/Resources/ENV-P%3BREF-latest%3B%20tfsubmodule-disks?repoName=wesley-trust%2Ftfsubmodule-disks&branchName=main)](https://dev.azure.com/wesleytrust/Terraform/_build/latest?definitionId=92&repoName=wesley-trust%2Ftfsubmodule-disks&branchName=main)|
### Testing Stages
| Unit Tests | Integration Tests |
| :--------: | :---------------: |
|    [![Build Status](https://dev.azure.com/wesleytrust/Terraform/_apis/build/status/Modules/Resources/ENV-P%3BREF-latest%3B%20tfsubmodule-disks?repoName=wesley-trust%2Ftfsubmodule-disks&branchName=main&stageName=Unit)](https://dev.azure.com/wesleytrust/Terraform/_build/latest?definitionId=92&repoName=wesley-trust%2Ftfsubmodule-disks&branchName=main)        |          [![Build Status](https://dev.azure.com/wesleytrust/Terraform/_apis/build/status/Modules/Resources/ENV-P%3BREF-latest%3B%20tfsubmodule-disks?repoName=wesley-trust%2Ftfsubmodule-disks&branchName=main&stageName=Integration)](https://dev.azure.com/wesleytrust/Terraform/_build/latest?definitionId=92&repoName=wesley-trust%2Ftfsubmodule-disks&branchName=main)        |