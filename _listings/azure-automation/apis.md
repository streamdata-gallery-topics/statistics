---
name: Azure Automation
x-slug: azure-automation
description: Automate all of those frequent, time-consuming, and error-prone cloud
  management tasks. Azure Automation helps you focus on work that adds business value.
  By reducing errors and boosting efficiency, it also helps to lower your operational
  costs.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-automation-save-time.png
x-kinRank: "10"
x-alexaRank: ""
tags: Statistics
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/statistics/master/_listings/azure-automation/apis.md
specificationVersion: "0.14"
apis:
- name: Azure Automation API Statistics List By Automation Account
  x-api-slug: azure-automation-api
  description: Retrieve the statistics for the account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-automation-save-time.png
  humanURL: https://azure.microsoft.com/en-us/services/automation/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Automation/automationAccounts/{automationAccountName}/statistics
  tags: Statistics, List, Automation, Account
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/statistics/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftautomationautomationaccountsautomationaccountnamestatistics-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/statistics/master/_listings/azure-automation/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftautomationautomationaccountsautomationaccountnamestatistics-get-openapi.md
- name: Azure Automation API
  x-api-slug: azure-automation-api
  description: Automate all of those frequent, time-consuming, and error-prone cloud
    management tasks. Azure Automation helps you focus on work that adds business
    value. By reducing errors and boosting efficiency, it also helps to lower your
    operational costs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-automation-save-time.png
  humanURL: https://azure.microsoft.com/en-us/services/automation/
  baseURL: ://management.azure.com//
  tags: Statistics
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/statistics/master/_listings/azure-automation/openapi.md
x-common:
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/automation/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/automation/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/automation/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/automation/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---