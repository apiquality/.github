# Changelog

### v2.23 Devportal [2025-01-15]
- New better developer portal configuration.
- Automatic executions for Newman with global organization configuration
- Add api and environment to emails sended by platform
- New release for apiquality visual api editor with redocly and spectral validations
- New feture to create and update api templates direcly in the platform
- Get better life cycle in Apigee
-> One step to apply company configuration ange workflow generation.
-> Configure the target url in a form
- Get better life cycle in Kong in one step
-> Load the template configuration in initializer
-> Reconfigure services directly to deploy in one-click whitin repository modification
- Get better life cycle in Wso2.
-> New capacity to
-> New field to add as property the repository url
- Get better life cycle in IBM.
- The new deploy maintenance the subscription
-> New IBM prouduct template

### v2.22-Dashboard api scoring [2025-12-30]
- Merge the initializer and apigee templater for apigee
- New redesign for api dashboard rating
- New ife cycle for api templates, api manager templates, opportunities, style guides
- Redesign kong and IBM life cycle
- New documentation section
- Bugs and small features

### v2.21-New quick wins in life cycle IBM, Kong and Apigee [2025-12-18]
- New quick-wins for kong life cycle
- New feature to edit yaml configuration
- New field to configure in deployment
- New quick-wins for online editor
- Add swagger editor validations
- Add redocly and spectral online lines
- New quick-wins for apigee life cycle
- Configure credentials in the environment configuration
- Templates apigee selection in init stage
- Add basepath and target for apigee
- New quick-wins for IBM life cycle
- Add the ibm extension
- Configure openapi2postman in environments
- New quick-wins usability
- New stages in Azure
- Kong initializer
- Kong deployer
- Kong validator

### v2.20-life cycle kong [2025-12-05]
- Life cycle for Kong
- Mocks security
- New parameter to execute stress tests
- New file field to opportunities to add excel opportunities
- Add portman as postman collection generator
- New quick-wins for wso2 life cycle

### v2.19-Apigee Templater [2025-11-25]
- Integrate Apigee X Templater into the lifecycle
- Improvement in the Zap Proxy stage
- New functionality to display the type of API supported by each stage
- New Status View of SaaS Components
- New steps in Azure
- New steps on Github
- New steps in Bitbucket
- Downloading the Newman report
- Self provisionning
- Statistics
- Model Editing
- Allow the download of the Apigee configuration template
- The names of the test generator properties are modified.
- Improvements and bugs

### v2.18-Apihub release [2025-08-25]

- Import from API Hub
- Security Test History
- New Functionality for Tested and Untested Endpoints
- SonarQube (10.8) and Microcks (1.12) Update

### v2.17-MCP ]2025-08-29]
- Creates the new MCP for APIquality

### v2.16 Zap Proxy [2025-08-04]

- APi Security tests with Zap Proxy
- The length of the HOST_URL path in Postman has been extended because 100 characters might be too short.
- The ability to upload multiple models at once is now supported.
- The api-design-collaborator role is now also allowed in models.
- All server options for the openapi-generator have been added (previously, there were only the 5 main ones).
- The node version of the stages has been updated.
- The tags that are added to the application, not those from the OpenAPI, have been included in the deployment with WSO2.
- When logging out for organizations with their own login, the logout will now redirect to their custom login screen.
- When a validation for opportunities is requested for organizations with a custom login, the email must redirect to their own login and not the standard one. For example: https://app.apiquality.io/
- Information on the Tyk stages has been added.
- Improved performance on the API viewing screen.
- Bugs
- It has been validated that the API name is not lost when switching from one step to another within the opportunities section.

### v2.15 TyK, Github and api change log [2025-07-15]

- Life of cycle with pre-configured stages in TyK
- APi Change Log with visual interface
- New version of sonar with more 10 rules news
- New list for models in dashboard screen
- New capacity to generate stress tests using k6
- New stages in Github

### v2.14 Stress tests release (2025-06-16)
- New life of cycle for stress tests (generator, executor)
- New direct import apis from wso2
- New stages with openapigenerator

### v2.13 Models release
- New life of cycle about models
- New audit screen for models
- New refresh button to refresh stages states

### v2.12 Apigee release
- Apigee stages (initializer, synchronizer, deploy)
- Get information for deployment in wso2 (apps, subscribers...)
- New feature of refresh steps for custom stages

### v2.11 Mulesoft integration (2025-04-24)
(2025-04-24)

- Create easy deploy for Mulesoft APIs
- Massive import users
- New field in context / opportunities API (instructions, calculated field, calculated text field, calculated editable field, fixed, organization properties)
- New funcionality to create namespaces and properties in organization level

### v2.10 Github release
[2025-04-10]

- Github integration
- Life of cycle for opportunities / context API (with approval)
- New rules in spectral
- Default config for newman execution
- Add supports for markdown in online editor
- Integration with JAPI - Mapping visual archetype microservices generator

### v2.9 Sequencial stages execution
[2025-03-24]

- Tyk as new API Manager
- Create manual and automatic executions
- New spectral rules

### v2.8 Api Properties
[2025-02-27]

- Order environments to control uploads between environments
- New filter to opportunities / context apis
- New simple paths designer in the opportunities screen
- Redesign the api environment screen adding properties tab and audit tab. This properties can be used in pipelines.
- New api security definition rating in the ratings screen
- New options to create tests (minimal tests, validate output schema, host pattern and new tests for anyOf, oneOf)


### v2.7 (February)
- Display of the APi file
- Configuration parameter of the online validator with spectral
- Newman's execution history
- New API download option in api display screen
- New quality testing step after deployments
- New sonarapi-rules implemented

### v2.6 (January 2025)
- Online editor with online validator with spectral and redocly
- Displaying the domain in the display screen of an API
- Paginate the list of APIs
- Editing Api manager templates
- Rule implementation with spectral
- New post-deployment test section
- Fixes
-- Fixed an issue where the organisation setup tutorial had to be skipped several times.
-- Fixed the issue where the screen was greyed out after adding users to an environment.
-- Fixed the issue where notifications from all of the user’s organisations appeared in the notifications icon.
-- Fixed the bug that prevented the display in several wso2 gateways and only displayed in the default one.

### v2.5 (2024-12-13)
- Improve the IA APis using api template
- Add properties to domain
- Deploy in Wso2 with a graphical mode
- Add  success and wrong properties to openapi2postman
- Reconfigure the screens for linking third parties components.
- New spectral rules implementation (OAR076) and get better configuration

## [2.3] - 2024-11-14

- Create APIs using IA
- Add followers to APIs and domains to get notifications
- Move APis between domains
- Add retrocompatibiliy stage

## [2.2] - 2024-10-30

- Create spectral file with sonarapi rules
- Create contract tests in postman with on click
- View the mocks in apiquality
- Create environment profiles with different cycle of APIOps

## [2.1] - 2024-10-04
- Deploy in Wso2 with api.yaml
- Add automatically the mock server in to the openapi
- Create blocked stages in de deployment
- Securize mock requests in microcks
- Create a styles guide assistant to create a new style guide
- Generate resolved openapi with external references in json and yaml format
- Generate the openapi documentation in the apiquality tool
- Add domain to opportunities
- New linter (redocly) in the apiops process

## [2.0] - 2024-09-19
- Get information stages directly from APIquality
- Show the historical executions
- Allow change the openapi file
- Define global branches
- Generate unified openapi including external refs
- Adds the user name in commits
- Login with SAML
