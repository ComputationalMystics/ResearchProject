# Title: Compare Repositories

## Description
The user provides two URLs for different GitHub repositories that she wants to
compare the metrics for. The software returns side-by-side
[metrics](https://wiki.linuxfoundation.org/oss-health-metrics/metrics)
that indicate the health and sustainability of both of the repositories.

## Triggers (What prompts the use case to start?)
1. A user seeks to compare the health and sustainability metrics of two open
   source communities (repositories).

## Actors (Who is involved?)
1. User

## Preconditions (This includes things like “data loaded”. Or, project is flagged as “of interest”; etc.)
1. User provides two URLs to two different GitHub repositories

## Main Success Scenario
1. All metrics that can be computed from the provided repositories are displayed
   side-by-side or in a graphical manner that allows easy comparison.

## Alternate Success Scenarios
1. N/A

## Failed End Condition
1. A provided URL points to a non-existent GitHub repository, metrics cannot
   be calculated, and an error message explaining the condition is shown to user.

## Extensions
1. N/A

## Steps of Execution (Requirements)
1. The use enters and submits the URL to a GitHub repository.
2. Metrics computed from the provided repository are displayed.

## Dependent Use Cases
1. [View Metrics](view-metrics.md)

## A use case diagram, following the UML Standard for expressing use cases.
![use case diagram](./diagram/CompareRepositories.png)
