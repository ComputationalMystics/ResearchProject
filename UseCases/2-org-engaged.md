# Title: 2-org-engaged

## Background
Organizations that engage with open source communities or use open source
software want to evaluate the value and long-term sustainability of this
engagement. Depending on the context, organizations may want
to assess the engagement level of its employees in the community, identify
early warn signals about deteriorating community health, or the emergence of
risk factors over time.

## Description
The user (employee) provides a URL to a GitHub repository for a community that
they want to evaluate. The software returns
[metrics](https://wiki.linuxfoundation.org/oss-health-metrics/metrics)
that indicate the health and sustainability of the repository.

## Triggers (What prompts the use case to start?)
1. A user (employee) seeks to assess the value of engaging with an open source
   community and the long-term sustainability to justify continued engagement
   with the community.
2. A participating organization seeks to get metrics on an open source solution to determine if they want to continue to use it

## Actors (Who is involved?)
1. Managers
2. Participating organizations
3. Employees

## Preconditions (This includes things like “data loaded”. Or, project is flagged as “of interest”; etc.)
1. GitHub repository exists and enough data exists to compute metrics
2. User provides URL to a GitHub repository
3. User has access to view metrics of the repository
4. If wanted, the user provides the name of an employee to see their metrics specificially

## Main Success Scenario
1. All metrics that can be computed from the provided repository are displayed.

## Alternate Success Scenarios
1. Metrics are provided for a specific employee to show engagement level

## Failed End Condition
1. The provided URL points to a non-existent GitHub repository, metrics cannot
   be calculated, and an error message explaining the condition is shown to user.
2. The given repository does not have enough data for metrics to be computed.
3. The user does not have access to view the metrics on that repository.

## Extensions
1. Compare metrics between repositories.

## Steps of Execution (Requirements)
1. The user enters and submits the URL to a GitHub repository.
2. Metrics computed from the provided repository are displayed.

## Dependent Use Cases
1. [View Metrics](view-metrics.md)

## A use case diagram, following the UML Standard for expressing use cases.
![use case diagram](./diagram/ViewMetrics.png)
