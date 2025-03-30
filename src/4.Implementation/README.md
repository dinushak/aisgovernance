# Implementation 🚀

Welcome to the **Implementation** section of the Azure Integration Services (AIS) Project Governance Toolkit. This section contains resources and templates to help you effectively implement and deploy your AIS projects.

## Contents

- **Landing Zone Implementation**: Guidelines and resources for setting up an AIS landing zone.
- **Deployment**: Step-by-step instructions for deploying AIS components using Infrastructure as Code (IaC) with Bicep or Terraform, including DevOps repositories and pipelines.
- **Development**: Resources for developing AIS components such as Azure Functions, Logic Apps, APIM policies, and ADF pipelines.
- **Testing**: Resources for conducting thorough testing of AIS components.

## Resources

### Landing Zone Implementation
Set up an AIS landing zone to provide a well-managed environment for your integration workloads. Use these guidelines and resources to establish a robust and scalable landing zone.

[AIS Landing Zone Accelerator](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/app-platform/integration-services/landing-zone-accelerator)

[Identity & Access Management Considerations](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/app-platform/integration-services/identity-and-access-management)

[Network Topology & Connectivity Considerations](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/app-platform/integration-services/network-topology-and-connectivity)

[Security Considerations](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/scenarios/app-platform/integration-services/security)

### Deployment
Use these guides to deploy AIS components such as Logic Apps, Azure Functions, Service Bus, API Management, and Event Grid using IaC tools like Bicep or Terraform. This section also covers setting up DevOps repositories and pipelines.

[AIS Bicep Quickstart](https://github.com/ronaldbosma/azure-integration-services-quickstart)

#### Sample Repository Structure

/pipelines
  ├── azure-pipelines.yml
  ├── parameters
  │   ├── dev.parameters.json
  │   ├── test.parameters.json
  │   └── prod.parameters.json
  ├── bicep
  │   ├── main.bicep
  │   └── modules
  │       ├── logicapp.bicep
  │       ├── function.bicep
  │       ├── servicebus.bicep
  │       ├── apim.bicep
  │       └── eventgrid.bicep


### Development
Develop AIS components such as Azure Functions, Logic Apps, APIM policies, and ADF pipelines using these resources. These guides and templates will help you create and manage your integration solutions effectively.

[Azure Functions Development Guide](https://learn.microsoft.com/en-us/azure/azure-functions/functions-reference?tabs=blob&pivots=programming-language-csharp)

[Azure Logic Apps Development Guide](https://learn.microsoft.com/en-us/azure/azure-functions/functions-reference?tabs=blob&pivots=programming-language-csharphttps://learn.microsoft.com/en-us/azure/logic-apps/)

[APIM Policy Reference](https://docs.azure.cn/en-us/api-management/api-management-policies)

[ADF Pipeline Reference](https://learn.microsoft.com/en-us/azure/data-factory/concepts-pipelines-activities?tabs=data-factory)

### Testing
Conduct thorough testing of AIS components to ensure they meet the required standards and function as expected. Use these resources to plan and execute your testing strategy.

[Test Plan Template](Templates/Test_Plan_Template.md)
Test Cases Template
Test Data Template