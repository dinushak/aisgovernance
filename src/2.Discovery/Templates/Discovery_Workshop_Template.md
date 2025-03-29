# Discovery Workshop Data Collection Template

## Project Information
- **Project Name**: 
- **Project Manager**: 
- **Date**: 
- **Participants**: 

## Integration Overview
- **Integration Name**: 
- **Description**: 
- **Business Objective**: 
- **Stakeholders**: 

## Current State of Integration
- **Source System Name**: 
- **Source System Owner**: 
- **Current Data Format**: (e.g., JSON, XML, CSV)
- **Current Integration Protocol**: (e.g., SFTP, API)
- **Current Connection Details**: (e.g., API endpoint, database connection string)
- **Current Authentication Method**: (e.g., OAuth, API Key, Basic Auth)
- **Current Data Flow**: (e.g., how data is currently transferred)
- **Current Challenges**: (e.g., issues with data quality, latency)

## Integration Requirements
- **Frequency**: (e.g., real-time, batch, scheduled)
- **Volume**: (e.g., number of records per integration)
- **Latency**: (e.g., acceptable delay in data transfer)
- **Error Handling**: 
  - **Transient Errors**: (e.g., retry logic)
  - **Permanent Errors**: (e.g., error notifications)
- **Logging & Monitoring**: (e.g., logging levels, monitoring tools)
- **Secrets Management**: (e.g., key vaults, secure storage)
- **Security Considerations**: 
  - **Encryption**: (e.g., data at rest, data in transit)
  - **Access Controls**: (e.g., role-based access)
- **Notifications**: (e.g., alerts, emails)
- **Scalability**: (e.g., scaling strategies)
- **High Availability**: (e.g., redundancy, failover mechanisms)
- **Disaster Recovery**: (e.g., backup strategies, recovery plans)
- **Governance**: (e.g., policies, procedures)
- **Compliance**: (e.g., regulatory requirements)
- **Privacy**: (e.g., data protection measures)
- **Costing**: (e.g., budget considerations)

## Existing and Supported Infrastructure
### Infrastructure
- **Existing State of Azure Tenant**: 
  - **Landing Zones**: (e.g., How subscriptions are organized)
  - **Resource Groups & Resources**: (e.g., How resources are organized)
  - **Type of Subscriptions**: (e.g., PAYG, EA)

- **On-Premises Connectivity**: (e.g., ExpressRoute, VPN)
- **Email/Notification Approach**: (e.g., SMTP server, notification services)
- **Logging & Monitoring**: (e.g., existing logging frameworks, SIEM systems)
- **Internet Connectivity**: 
  - **Firewalls**: (e.g., firewall rules, configurations)
  - **Network Controls**: (e.g., network segmentation, access controls)
- **Existing DevOps Infrastructure**: (e.g., Corporate Azure DevOps)
- **Availability of Environments**: (e.g., Dev, Test, UAT, Production)

### Policies & Procedures
- **Naming Conventions for Resources**: (e.g., existing naming guideline)
- **Service Request/Change Management Process**: (e.g., ITIL processes, ticketing systems)
- **Preferred IaC Frameworks**: (e.g., Bicep, Terraform)

### Vendors
- **Vendor Communication**: 
  - **Frequency**: (e.g., weekly, monthly)
  - **Contacts**: (e.g., vendor contact details, communication channels)
  - **Systems Availability**: (e.g., current access to vendor systems)

## Data Considerations

### Data Mapping and Transformation
- **Source Fields**: 
- **Target Fields**: 
- **Global Transformation Rules**: (e.g., data type conversion, field concatenation)
- **Validation Rules**: (e.g., data format validation, range checks)

### File Type Details
For each file type (e.g., invoice file), gather the following information:
- **File Type Name**: 
- **Purpose**: 
- **Validations**: (e.g., schema validation, business rules)
- **Mapping and Transformations**: (e.g., field mappings, transformation logic)
- **Quality Requirements**: (e.g., data accuracy, completeness)

## Target State of Integration
- **Target System Name**: 
- **Target System Owner**: 
- **Target Data Format**: (e.g., JSON, XML, CSV)
- **Target Integration Protocol**: (e.g., SFTP, API)
- **Target Connection Details**: (e.g., API endpoint, database connection string)
- **Target Authentication Method**: (e.g., OAuth, API Key, Basic Auth)
- **Target Data Flow**: (e.g., how data should be transferred)
- **Expected Improvements**: (e.g., enhanced data quality, reduced latency)

## Azure Integration Services Components
### Logic Apps
- **Workflows**: (e.g., types of workflows, triggers, actions)
- **Connectors**: (e.g., connectors used, custom connectors)
- **Error Handling**: (e.g., retry policies, exception handling)
- **Security**: (e.g., authentication methods, data encryption)

### API Management
- **APIs**: (e.g., number of APIs, endpoints)
- **Policies**: (e.g., rate limiting, caching, transformation)
- **Security**: (e.g., authentication, authorization)
- **Monitoring**: (e.g., metrics, logging)

### Service Bus
- **Messaging**: (e.g., queues, topics, subscriptions)
- **Message Handling**: (e.g., dead-lettering, retry policies)
- **Security**: (e.g., access controls, encryption)

### Event Grid
- **Events**: (e.g., event sources, event handlers)
- **Subscriptions**: (e.g., event subscriptions, filters)
- **Security**: (e.g., authentication, authorization)

### Data Factory
- **Pipelines**: (e.g., data pipelines, activities)
- **Data Integration**: (e.g., ETL/ELT processes, data transformation)
- **Monitoring**: (e.g., pipeline runs, error handling)
- **Security**: (e.g., data encryption, access controls)

## Metrics for Successful Integration
- **Success Criteria**: (e.g., data transfer completion, accuracy)
- **Performance Metrics**: (e.g., processing time, throughput)
- **Error Metrics**: (e.g., error rates, types of errors)
- **User Satisfaction Metrics**: (e.g., stakeholder feedback)

## Additional Notes
- **Assumptions**: 
- **Constraints**: 
- **Risks and Mitigation**: 
- **Open Questions**: 

---