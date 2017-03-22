# Title: Compare Repositories

## Description
The user provides two URLs for different GitHub repositories that they want to
compare the metrics for. The software returns side-by-side
[metrics](https://wiki.linuxfoundation.org/oss-health-metrics/metrics)
that indicate the health and sustainability of both of the repositories.

## Triggers (What prompts the use case to start?)
1. A user seeks to compare the health and sustainability metrics of two open
   source communities (repositories).

## Actors (Who is involved?)
1. User

## Preconditions (This includes things like “data loaded”. Or, project is flagged as “of interest”; etc.)
1. GitHub repositories exists and have enough data to compute metrics
2. User provides two URLs to two different GitHub repositories
3. User has access to view metrics of the repositories

## Main Success Scenario
1. All metrics that can be computed from the provided repositories are displayed
   side-by-side or in a graphical manner that allows easy comparison.

## Alternate Success Scenarios
1. N/A

## Failed End Condition
1. A provided URL points to a non-existent GitHub repository, metrics cannot
   be calculated, and an error message explaining the condition is shown to user.
2. At least one of given repository does not have enough data for metrics to be computed.
3. The user does not have access to view the metrics on both repositories.


## Extensions
1. N/A

## Steps of Execution (Requirements)
1. The user enters and submits the URLs to two GitHub repositories.
2. Metrics computed from the provided repository are displayed.

## Dependent Use Cases
1. [View Metrics](view-metrics.md)

## A use case diagram, following the UML Standard for expressing use cases.
![use case diagram](./diagram/CompareRepositories.png)
