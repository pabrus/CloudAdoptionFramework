# Cloud Adoption Framework Migration Landing Zone

The Microsoft Cloud Adoption Framework for Azure (CAF) migration landing zone is a set of infrastructure to help you set up for migrating your first workload and manage your cloud estate in alignment with CAF.

For more information about this architecture and how it is used, see the [deploy a landing zone article](https://docs.microsoft.com/azure/architecture/cloud-adoption/ready/azure-readiness-guide/migration-landing-zone) in the Microsoft Cloud Adoption Framework.

For guidance regarding expansions of this landing zone to meet your environmental requirements and landing zone needs, see [landing zone considerations](https://docs.microsoft.com/azure/architecture/cloud-adoption/ready/considerations/).

## Introduction

The CAF migration landing zone sample deploys foundation infrastructure resources in Azure that can be used by organizations to prepare their subscription for migrating virtual machines in to. It also helps put in place the governance controls necessary to manage their cloud estate. This sample will deploy and enforce resources and templates that will allow an organization to confidently get started with Azure.

## Parameters

- **Organization**: Enter your organization name (e.g. Contoso), must be unique
- **LogDataRetention**: Number of days data will be retained in in Log Analytics
- **KeyVaultObjectId**: User ID to grant permissions to in Key Vault
- **NetworkIPAddressPrefix**: Provide first 2 octets for virtual network (e.g. 10.0)

## Deployment

Use the following link to deploy it to a greenfield subscription:

[![Deploy To Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#blade/Microsoft_Azure_CreateUIDef/CustomDeploymentBlade/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fpabrus%2FCloudAdoptionFramework%2Fpabrus%2Fblueprint_to_armdeploy%2Fready%2Fmigration-landing-zone%2Fmigration-landing-zone.deploy.json/createUIDefinitionUri/https%3A%2F%2Fraw.githubusercontent.com%2Fpabrus%2FCloudAdoptionFramework%2Fpabrus%2Fblueprint_to_armdeploy%2Fready%2Fmigration-landing-zone%2Fmigration-landing-zone.ui.json)
