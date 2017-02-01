# Health Indicators
We roughly categorize health indicators in three categories: code health, community health, and compliance health.

## Comments

**Disclaimer:** We list and describe health indicators. By no means are we evaluating them for suitability. Open source communities have a flurry of different stakeholders and projects with each having different interpretation of the indicators. For different situations, the indicators will carry different meanings.

**Caution:** The Occurrance count is a rough estimate for how often we encounter the indicator. This is not an exact science.

Keep in mind, many projects do not use the GitHub issue tracker.

Keep in mind, different GitHub projects use pull requests to a greater and lesser degree.

[Issue/3](https://github.com/OSSHealth/HealthIndicators/issues/3): Many of the indicators are also informative when tracked over time.

Interviewees often clarify, that contributions are not merely code commits, but also include documentation, issues, and community management.


## Code Health

Code health contains indicators descriptive of a code base and its quality.

Name                              | Formula                                                 | Description                                                                                                                                                                                      | Occurance
----------------------------------|---------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------
Pull Request made/closed          | Pull requests made vs. pull requests closed             | Example: http://repocheck.com/#https%3A%2F%2Fgithub.com%2Ftwbs%2Fbootstrap <br/>Encompasses number of pull requests rejected ([Issue/1](https://github.com/OSSHealth/HealthIndicators/issues/1)) | Interviews: 3
Pull Requests Open                | Number of open pull requests                            | Might be more telling than total pull requests                                                                                                                                                   | Interviews: 1<br/>[Issue/1](https://github.com/OSSHealth/HealthIndicators/issues/1)
Pull Request Comments             | Number of comments per pull request                     |                                                                                                                                                                                                  | Inteviews: 1
Pull Request Discussion Diversity | Number of different people discussing each pull request |                                                                                                                                                                                                  | Interviews: 1
Update Rate                       | Number of updates over period x                         |                                                                                                                                                                                                  | [Issue/1](https://github.com/OSSHealth/HealthIndicators/issues/1)
Update Regularity                 |                                                         | How consistently and frequently are updates provided.                                                                                                                                            | Interviews: 1 <br/>[Issue/1](https://github.com/OSSHealth/HealthIndicators/issues/1)
Update Age                        | Time since last update                                  |                                                                                                                                                                                                  | Interviews: 1 <br/>[Issue/1](https://github.com/OSSHealth/HealthIndicators/issues/1)
Repository Size                   |                                                         | Overall size of the repository or number of commits                                                                                                                                              | [Issue/1](https://github.com/OSSHealth/HealthIndicators/issues/1)


## Community Health

Community health contains indicators descriptive of community interactions and behavior.

Name                    | Formula                                                                      | Description                                                                                                                             | Occurance
------------------------|------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------
Contributor Diversity   | Ratio of contributors from a single company over all contributors            | Also described as: Maintainers from different companies. Diversity of contributor affiliation. **This is mentioned frequently**         | Interviews: 3
Issue Response Rate     | Time between a new issue is opened and a maintainer responds                 | Also called: bug response rate. The maintainer is believed to not "pile on" but try to solve an issue. **This is mentioned frequently** | Interviews: 3
Community Activity      | Contribution Frequency                                                       | (Contribution = commit, issue, comment, ...)                                                                                            | Interviews: 3<br/>[Issue/1](https://github.com/OSSHealth/HealthIndicators/issues/1)
Contributor Breadth     | Ratio of non-core committers (drive-by committers)                           | Can indicate openess to outsiders                                                                                                       | Interviews: 2
Contibutors             | Number of contributors                                                       |                                                                                                                                         | Interviews: 2 <br/> [Issue/1](https://github.com/OSSHealth/HealthIndicators/issues/1)
Contributor Activity    |                                                                              | Activity level of individual contributos                                                                                                | [Issue/1](https://github.com/OSSHealth/HealthIndicators/issues/1)
Contribution Diversity  | Ratio of code committed by contributos other than original project initiator | Contributions are going up beyond the core team                                                                                         | Interviews: 1
Contribution Acceptance | Ratio of contributions accepted vs. closed without acceptance                |                                                                                                                                         | [Issue/1](https://github.com/OSSHealth/HealthIndicators/issues/1)
Distribution of Work    |                                                                              | How much _recent_ activity is distributed?                                                                                              | [Issue/1](https://github.com/OSSHealth/HealthIndicators/issues/1)
Contribution Age        | Time since last contribution                                                 | Gives a sense of how active the community is. (Contribution = commit, issue, comment, ...)                                              | Interviews: 1
Truck Factor            | see: community/truckFactor.md                                                | The number of developers it would need to lose to destroy its progress.                                                                 | [Issue/1](https://github.com/OSSHealth/HealthIndicators/issues/1)<br/> Literature
Forks                   | Number of forks                                                              |                                                                                                                                         | Interviews: 2
Stars                   | Number of stars                                                              | (Code ?)                                                                                                                                | Interviews: 2
Watchers                | Number of watchers                                                           | (Code ?)                                                                                                                                | Interviews: 2
Issues Open             | Number of open issues                                                        |                                                                                                                                         | [Issue/1](https://github.com/OSSHealth/HealthIndicators/issues/1)
Issues sbumitted/closed | Issues submitted vs. issues closed                                           | Example: http://repocheck.com/#https%3A%2F%2Fgithub.com%2Ftwbs%2Fbootstrap                                                              | Interviews: 2
Issue Comments          | Number of Comments per Issue                                                 |                                                                                                                                         | [Issue/3](https://github.com/OSSHealth/HealthIndicators/issues/3)
Time to Contributor     | Time to becoming a contributo                                                |                                                                                                                                         | Interviews: 1 <br/>[Issue/1](https://github.com/OSSHealth/HealthIndicators/issues/1)
Path to Leadership      | A communicated path from lurker to contributor to maintainer                 | Rational: If active contributors are not included in leadership descisions, they might lose interest and leave.                         | Interviews: 2



## Compliance (Risk) Health

Compliance health contains indicators informative of vulnerabilities and license obligations.

Name                  | Formula                                                                                            | Description                                                                    | Occurance
----------------------|----------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------|------------------------------------------------------------------------------------
Test Coverage         | tbd                                                                                                |                                                                                | Interviews: 1
Bug Age               | Age of known bugs in issue tracker                                                                 | Use label for determining bugs?                                                | [Issue/1](https://github.com/OSSHealth/HealthIndicators/issues/1)
Known Vulnerabilities | Number of reported vulnerabilities                                                                 | Could be limited to issue-tracker or extended vulnerabity databases (e.g. CVE) | Interviews: 1<br/>[Issue/1](https://github.com/OSSHealth/HealthIndicators/issues/1)
Dependency Depth      | Number of projects included in code base + number of projects relying on focal project (recursive) | Indicator about centrality in open source Dependency network                   | Interviews: 1
License Declared      | What license does the project declare                                                              |                                                                                | [Issue/1](https://github.com/OSSHealth/HealthIndicators/issues/1)
License Conflict      | Does the project contain incompatible licenses                                                     |                                                                                |
All Licenses          | List of licenses                                                                                   |                                                                                |
License Count         | Number of licenses                                                                                 |                                                                                |


## Goals
To what purpose are indicators used?

This section collects notes on what possible goals might be.

- Avoid in-take of inactive project, because it makes it difficult to maintain and might carry unknown bugs and security issues.
- Identify open source projects that need support.
- Show that active community management bears desired results. (Measurable outcomes)
