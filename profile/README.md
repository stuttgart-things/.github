<div align="center">
  <p>
    <img src="sthings-city.png" alt="sthings" width="450" />
  </p>
  <p>
    <strong>[sˈθɪŋz]</strong>- using modularity to speed up parallel builds
  </p>
</div>

# stuttgart-things 🍿
microservice development, configuration/infrastructure as code & creation of clis based on surveys.

# PAGES :earth_africa:

|                     Name | Description                                                                                      |  URL  |                                     
| -----------------------: | :----------------------------------------------------------------------------------------------- | :----------------------------------------------------- |
| [docs-repo](https://github.com/stuttgart-things/docs)  | documentation in code snippets | [![Button Component](https://readme-components.vercel.app/api?component=button&text=ClickHere)]([https://github.com/harish-sethuraman/readme-components]([https://stuttgart-things.github.io/stuttgart-things/](https://stuttgart-things.github.io/docs/)))  | 
| [stuttgart-things-repo](https://github.com/stuttgart-things/stuttgart-things) | used for configuration code like gitops configuration, ansible playbooks, Dockerfiles or helm charts | [![Button Component](https://readme-components.vercel.app/api?component=button&text=ClickHere)]([https://github.com/harish-sethuraman/readme-components](https://stuttgart-things.github.io/stuttgart-things/)) | 

# Active Development :computer:

## /ANSIBLE COLLECTIONS

|                     Name | Description                                                                                      | Releases                                               |
| -----------------------: | :----------------------------------------------------------------------------------------------- | :----------------------------------------------------- |
| **[sthings.base_os][sthings.base_os]** | |  | 


## /TERRAFORM MODULES

|                     Name | Description                                                                                      |  Releases  |                                     
| -----------------------: | :----------------------------------------------------------------------------------------------- | :----------------------------------------------------- |
| **[vault-base-setup][vault-base-setup]** | base setup configuration of hashicorp vault | **[vault-base-setup-releases]**  | 
| **[s3-minio-config][s3-minio-config]** | base setup configuration of minio s3 | **[s3-minio-config-releases]** | 
| **[flux2-cluster-bootstrap][flux2-cluster-bootstrap]** | bootstrapping kubernetes clusters w/ flux2 | **[flux2-cluster-bootstrap-releases]**  | 
| **[vsphere-vm][vsphere-vm]** | building vsphere vms (based on an existing vcenter templates)| **[vsphere-vm-releases]** | 
| **[proxmox-vm][proxmox-vm]** | building proxmox vms from existing templates | **[proxmox-vm-releases]** | 
| **[aws-ec2-vm][aws-ec2-vm]** | terraform module for creating ec2 vm instances | **[aws-ec2-vm]** | 

## /ROOT-REPOSITORY

|                     Name | Description                                                                                      |  Releases  |                                     
| -----------------------: | :----------------------------------------------------------------------------------------------- | :----------------------------------------------------- |
| **[stuttgart-things][stuttgart-things]** | flux2/argo-cd applications; packer configuration, helm charts, ansible code or Dockerfiles  | **[stuttgart-things-releases]**  | 
| **[tekton-base][tekton-base]** | helm chart for deploying tekton pipelines  | **[tekton-base-release]** | 
| **[flux-infra][flux-infra]** | kubernetes infrastructure service/applications deployment configuration for flux2  | | 
| **[flux-apps][flux-apps]** | kubernetes service/application deployments configuration for flux2  | | 

## /GOLANG-PROJECTS

|                     Name | Description                                                                                      | Releases                                               |
| -----------------------: | :----------------------------------------------------------------------------------------------- | :----------------------------------------------------- |
| **[machineShop][machineShop]** | git based CLI interface for managing configuration as code | **[machineShop-releases]** |
| **[machineShop-operator][machineShop-operator]** | manage the lifecycle of terraform resources w/ custom resources on k8s | **[machineShop-operator-releases]** |
| **[stageTime-server][stageTime-server]** | gRPC Server for validating & producing revisionRuns (a collection of tekton pipelineRuns/stages) | **[stageTime-server-releases]** |
| **[stageTime-creator][stageTime-creator]** | dynamic rendering and creation of k8s manifests/resources polled from redis streams/json| **[stageTime-creator-releases]** |

## /GOLANG-MODULES

|                     Name | Description                                                                                      | Releases                                               |
| -----------------------: | :----------------------------------------------------------------------------------------------- | :----------------------------------------------------- |
| **[sthingsBase][sthingsBase]** | module providing basic golang functions | **[sthingsBase-releases]** |
| **[sthingsCli][sthingsCli]** | module providing golang functions/building blocks for the use in command line interfaces | **[sthingsCli-releases]** |

## /ANSIBLE ROLES

|                     Name | Description                                                                                      | Releases                                               |
| -----------------------: | :----------------------------------------------------------------------------------------------- | :----------------------------------------------------- |
| **[download-install-binary][download-install-binary]** | download and install binary files | **[download-install-binary-releases]** |
| **[deploy-configure-rke][deploy-configure-rke]** | deploy rancher kubernetes engine + configuration in version 1/2 on linux based systems | **[deploy-configure-rke-releases]** |
| **[manage-filesystem][manage-filesystem]** | manage LVM and resize Linux FS - handle repartitioning with filesystem resizing support | **[manage-filesystem-releases]** |

[stuttgart-things]: https://github.com/stuttgart-things/stuttgart-things
[stuttgart-things-releases]: https://github.com/stuttgart-things/stuttgart-things/releases
[tekton-base]: https://github.com/stuttgart-things/stuttgart-things/tree/tekton-base-v0.50.14/charts/tekton-base
[tekton-base-release]: https://github.com/stuttgart-things/stuttgart-things/releases/tag/tekton-base-v0.50.14
[flux-infra]: https://github.com/stuttgart-things/stuttgart-things/tree/main/infra
[flux-apps]: https://github.com/stuttgart-things/stuttgart-things/tree/main/apps

[vault-base-setup]: https://github.com/stuttgart-things/vault-base-setup
[vault-base-setup-releases]: https://github.com/stuttgart-things/vault-base-setup/releases
[s3-minio-config]: https://github.com/stuttgart-things/s3-minio-config
[s3-minio-config-releases]: https://github.com/stuttgart-things/s3-minio-config/releases
[flux2-cluster-bootstrap]: https://github.com/stuttgart-things/flux2-cluster-bootstrap
[flux2-cluster-bootstrap-releases]: https://github.com/stuttgart-things/flux2-cluster-bootstrap/releases
[vsphere-vm]: https://github.com/stuttgart-things/vsphere-vm
[vsphere-vm-releases]: https://github.com/stuttgart-things/vsphere-vm/releases
[proxmox-vm]: https://github.com/stuttgart-things/proxmox-vm
[proxmox-vm-releases]: https://github.com/stuttgart-things/proxmox-vm/releases

[s3-minio-config]: https://github.com/stuttgart-things/s3-minio-config
[flux2-cluster-bootstrap]: https://github.com/stuttgart-things/flux2-cluster-bootstrap
[proxmox-vm]: https://github.com/stuttgart-things/proxmox-vm
[vsphere-vm]: https://github.com/stuttgart-things/vsphere-vm
[aws-ec2-vm]: https://github.com/stuttgart-things/aws-ec2-vm

[machineShop]: https://github.com/stuttgart-things/machineShop
[machineShop-operator]: https://github.com/stuttgart-things/machineShop-operator
[machineShop-releases]: https://github.com/stuttgart-things/machineShop/releases
[machineShop-operator-releases]: https://console.cloud.google.com/gcr/images/stuttgart-things/eu/machine-shop-operator
[sthingsBase]: https://github.com/stuttgart-things/sthingsBase
[sthingsBase-releases]: https://github.com/stuttgart-things/sthingsBase/tags
[sthingsCli]: https://github.com/stuttgart-things/sthingsCli
[sthingsCli-releases]: https://github.com/stuttgart-things/sthingsCli/tags
[stageTime-server]: https://github.com/stuttgart-things/stageTime-server
[stageTime-server-releases]: https://github.com/stuttgart-things/stageTime-server/releases
[stageTime-creator]: https://github.com/stuttgart-things/stageTime-creator
[stageTime-creator-releases]: https://github.com/stuttgart-things/stageTime-creator/releases
[deploy-configure-rke]: https://github.com/stuttgart-things/deploy-configure-rke
[deploy-configure-rke-releases]: https://github.com/stuttgart-things/deploy-configure-rke/tags
[download-install-binary]: https://github.com/stuttgart-things/download-install-binary
[download-install-binary-releases]: https://github.com/stuttgart-things/download-install-binary/tags
[manage-filesystem]: https://github.com/stuttgart-things/manage-filesystem
[manage-filesystem-releases]: https://github.com/stuttgart-things/manage-filesystem/tags

[DOCS]: https://stuttgart-things.github.io/docs/
[docs-repo]: https://github.com/stuttgart-things/docs

<div align="center">
  <p>
    <img src="sthings-city.png" alt="sthings" width="450" />
  </p>
</div>



<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
