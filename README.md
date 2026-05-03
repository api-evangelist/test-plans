# Test Plans (test-plans)
Structured documentation outlining test objectives, scope, approach, resources, schedule, and deliverables for software testing activities. Test plans define the overall strategy for testing a system or feature, specifying what will be tested, how it will be tested, who will test it, and what constitutes a pass or fail. They are critical for coordinating testing efforts across teams and ensuring comprehensive coverage.

**URL:** [Visit APIs.json URL](https://en.wikipedia.org/wiki/Test_plan)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Documentation, Quality Assurance, Software Development, Test Management, Testing

## Timestamps

- **Created:** 2025
- **Modified:** 2026-05-03

## APIs

### TestRail API
REST API for TestRail test management including test plans, test runs, milestones, and reporting, enabling structured test planning and execution tracking.

**Human URL:** [https://www.testrail.com](https://www.testrail.com)

#### Tags:

 - Test Management, Test Plans, Test Runs, Testing

#### Properties

- [Documentation](https://support.testrail.com/hc/en-us/articles/7077990413588-Introduction-to-the-API)
- [APIReference](https://support.testrail.com/hc/en-us/categories/7076832415124-API-Reference)

### Jira Software API
REST API for Jira Software project management, supporting test plan tracking via epics, sprints, issues, and custom fields integrated with testing workflows.

**Human URL:** [https://developer.atlassian.com/cloud/jira/software/rest/intro/](https://developer.atlassian.com/cloud/jira/software/rest/intro/)

#### Tags:

 - Agile, Jira, Project Management, Test Planning

#### Properties

- [Documentation](https://developer.atlassian.com/cloud/jira/software/rest/intro/)
- [OpenAPI](https://dac-static.atlassian.com/cloud/jira/software/swagger.v3.json)

### Azure DevOps Test Plans API
REST API for Azure DevOps Test Plans service supporting test plan creation, test suites, test case management, test execution, and results reporting.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/azure/devops/testplan/](https://learn.microsoft.com/en-us/rest/api/azure/devops/testplan/)

#### Tags:

 - Azure DevOps, CI/CD, Microsoft, Test Plans

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/azure/devops/testplan/)
- [OpenAPI](https://github.com/MicrosoftDocs/vsts-rest-api-specs)

### qTest API
REST API for qTest test management platform by Tricentis, supporting test plan management, test cycle creation, defect linking, and release-level test planning.

**Human URL:** [https://documentation.tricentis.com/qtestmanager/10.0/en/content/qtestmanager/api/intro.htm](https://documentation.tricentis.com/qtestmanager/10.0/en/content/qtestmanager/api/intro.htm)

#### Tags:

 - Agile Testing, Test Management, Test Plans, Tricentis

#### Properties

- [Documentation](https://documentation.tricentis.com/qtestmanager/10.0/en/content/qtestmanager/api/intro.htm)
- [APIReference](https://api.qasymphony.com/)

### ALM Octane API
REST API for Micro Focus ALM Octane test planning and quality management, supporting test planning, defect management, and release quality tracking.

**Human URL:** [https://admhelp.microfocus.com/octane/en/latest/Online/Content/API/REST_API.htm](https://admhelp.microfocus.com/octane/en/latest/Online/Content/API/REST_API.htm)

#### Tags:

 - ALM, Enterprise Testing, Quality Management, Test Plans

#### Properties

- [Documentation](https://admhelp.microfocus.com/octane/en/latest/Online/Content/API/REST_API.htm)

## Common Properties

- [Documentation](https://en.wikipedia.org/wiki/Test_plan)
- [Documentation](https://www.guru99.com/what-is-test-plan-how-to-write-it.html)

## Features

| Name | Description |
|------|-------------|
| Scope Definition | Define what features, modules, and components are in scope for the testing effort. |
| Resource Allocation | Assign testers, environments, and tools needed to execute the test plan. |
| Risk Assessment | Identify testing risks and mitigation strategies for high-risk areas. |
| Schedule Management | Define testing timelines, milestones, and entry and exit criteria for test phases. |
| Coverage Mapping | Map test cases to requirements ensuring complete coverage of all specifications. |
| Defect Tracking Integration | Link test failures to defect tracking systems for resolution workflow management. |

## Use Cases

| Name | Description |
|------|-------------|
| Release Test Planning | Create a comprehensive test plan for each release cycle defining scope and success criteria. |
| Sprint Test Planning | Plan testing activities within agile sprints aligned to user stories and acceptance criteria. |
| Regulatory Compliance Testing | Use test plans to document testing required for regulatory and compliance certifications. |
| Performance Test Planning | Plan load, stress, and performance test scenarios with target metrics and thresholds. |
| UAT Coordination | Coordinate user acceptance testing with business stakeholders through structured test plans. |

## Integrations

| Name | Description |
|------|-------------|
| Jira | Link test plans to Jira epics and sprints for agile testing coordination. |
| Confluence | Publish test plans to Confluence for team visibility and stakeholder review. |
| Jenkins | Trigger automated test execution from test plans via Jenkins pipeline integration. |
| Slack | Send test plan status updates and milestone notifications to Slack channels. |

## Artifacts

Machine-readable API specifications organized by format.

### JSON Schema

- [Test Plan Schema](json-schema/test-plans-test-plan-schema.json)
- [Test Cycle Schema](json-schema/test-plans-test-cycle-schema.json)
- [Milestone Schema](json-schema/test-plans-milestone-schema.json)

### JSON Structure

- [Test Plan Structure](json-structure/test-plans-test-plan-structure.json)
- [Test Cycle Structure](json-structure/test-plans-test-cycle-structure.json)
- [Milestone Structure](json-structure/test-plans-milestone-structure.json)

### JSON-LD

- [Test Plans Context](json-ld/test-plans-context.jsonld)

### Examples

- [Test Plan Example](examples/test-plans-test-plan-example.json)
- [Test Cycle Example](examples/test-plans-test-cycle-example.json)
- [Milestone Example](examples/test-plans-milestone-example.json)

## Vocabulary

- [Test Plans Vocabulary](vocabulary/test-plans-vocabulary.yml) — Unified taxonomy mapping 3 resources, 8 actions, and 4 personas across test planning domains.

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
