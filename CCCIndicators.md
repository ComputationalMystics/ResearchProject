# Health Indicators
We roughly categorize health indicators in three categories: code health, community health, and compliance health.

## Comments

**Disclaimer:** We list and describe health indicators. By no means are we evaluating them for suitability. Open source communities have a flurry of different stakeholders and projects with each having s different interpretation of the indicators. For different situations, the indicators will carry different meanings.

**Caution:** The occurrence count is a rough estimate for how often we encounter the indicator. This is not an exact science.

Keep in mind, many projects do not use the GitHub issue tracker.

Keep in mind, different GitHub projects use pull requests to a greater and lesser degree.

[Issue/3](https://github.com/OSSHealth/HealthIndicators/issues/3): Many of the indicators are also informative when tracked over time.

Interviewees often clarify, that contributions are not merely code commits, but also include documentation, issues, and community management.


## Reasons why community health is assessed
*This includes reasons why metrics are considered for other reasons*
This section collects notes on what possible goals might be.

- Track Corporate Engagement (is an organization creating value, are organizational goals met, employee contributions)
- Risk mitigation
- Identify open source projects that need support.
- Identify single points of failure (and hopefully prevent them)
- Assess value generated through community and engagement
- Show that active community management bears desired results. (Measurable outcomes)
- Avoid in-take of an inactive project, because it makes it difficult to maintain and might carry unknown bugs and security issues.


## Broad categories of indicators that we hear often
- Timeliness of maintainers
- Diversity of community, contributions, and in code base
- Distribution of code contributions (beyond project creator)
- Activity level - Responsiveness
- Viability ([Bus Factor](https://github.com/OSSHealth/HealthIndicators/blob/master/community/truckFactor.md) - individual contributors and clustered by employer)
- Maturity
- Ecosystem health (upstream, downstream, and related projects)
- Vanity metrics (might have use in other cases, e.g. stars)
- Aggregate project-tree health (combined health metrics of all linked dependencies)


## Context: Considerations when evaluating health
- Style of project
- Programming language
- Maturity of project (Projects might seem inactive but rather have fulfilled their goal and community remains responsive to bug reports and security issues, just no new features)
- Quality of Ecosystem (metrics of related projects)
- Value driven metrics (not just activity)
- Development of metrics over time
- External users might not be a homogenous group - consider different metrics
- Compare similar projects (manually determine which projects to compare)
- Classifications (based on a set of metrics, which projects 'behave' similar)
- Interrelationships between categories of indicators (maturity might be high while activity low and response rate is up)
- Aggregate from repository, to project, to community, (to company)


## Community Health
Community health contains indicators descriptive of community interactions and behavior.

Name                        | Formula                                                                                                                | Description                                                                                                                                       | Occurance
----------------------------|------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------
**Contributor Diversity**   | Ratio of contributors from a single company over all contributors                                                      | Also described as: Maintainers from different companies. Diversity of contributor affiliation. **This is mentioned frequently**                   | Interviews: 3
**Issue Response Rate**     | Time between a new issue is opened and a maintainer responds                                                           | Also called: bug response rate. The maintainer is believed to not "pile on" but try to solve an issue. **This is mentioned frequently**           | Interviews: 3
**Community Activity**      | Contribution Frequency                                                                                                 | (Contribution = commit, issue, comment, ...)                                                                                                      | Interviews: 3<br/>[Issue/1](https://github.com/OSSHealth/HealthIndicators/issues/1)
**Contributor Breadth**     | Ratio of non-core committers (drive-by committers)                                                                     | Can indicate openess to outsiders                                                                                                                 | Interviews: 2
**Contribution Diversity**  | Ratio of code committed by contributos other than original project initiator                                           | Contributions are going up beyond the core team                                                                                                   | Interviews: 1
**Contribution Acceptance** | Ratio of contributions accepted vs. closed without acceptance                                                          |                                                                                                                                                   | [Issue/1](https://github.com/OSSHealth/HealthIndicators/issues/1)
**Bus Factor**              | see: [community/truckFactor.md](https://github.com/OSSHealth/HealthIndicators/blob/master/community/truckFactor.md)    | The number of developers it would need to lose to destroy its progress. Alternatively: Number of companies that would have to stop support.       | [Issue/1](https://github.com/OSSHealth/HealthIndicators/issues/1)<br/> Literature
Contibutors                 | Number of contributors                                                                                                 |                                                                                                                                                   | Interviews: 2 <br/> [Issue/1](https://github.com/OSSHealth/HealthIndicators/issues/1)
Contributor Activity        |                                                                                                                        | Activity level of individual contributos                                                                                                          | [Issue/1](https://github.com/OSSHealth/HealthIndicators/issues/1)
Distribution of Work        |                                                                                                                        | How much _recent_ activity is distributed?                                                                                                        | [Issue/1](https://github.com/OSSHealth/HealthIndicators/issues/1)
Contribution Age            | Time since last contribution                                                                                           | Gives a sense of how active the community is. (Contribution = commit, issue, comment, ...)                                                        | Interviews: 1
Forks                       | Number of forks                                                                                                        |                                                                                                                                                   | Interviews: 2
Stars                       | Number of stars                                                                                                        | (Code ?)                                                                                                                                          | Interviews: 2
Watchers                    | Number of watchers                                                                                                     | (Code ?)                                                                                                                                          | Interviews: 2
Issues Open                 | Number of open issues                                                                                                  |                                                                                                                                                   | [Issue/1](https://github.com/OSSHealth/HealthIndicators/issues/1)
Issues sbumitted/closed     | Issues submitted vs. issues closed                                                                                     | [Example](http://repocheck.com/#https%3A%2F%2Fgithub.com%2Ftwbs%2Fbootstrap)                                                                      | Interviews: 2
Issue Comments              | Number of Comments per Issue                                                                                           |                                                                                                                                                   | [Issue/3](https://github.com/OSSHealth/HealthIndicators/issues/3)
Time to Contributor         | Time to becoming a contributor                                                                                         |                                                                                                                                                   | Interviews: 1 <br/>[Issue/1](https://github.com/OSSHealth/HealthIndicators/issues/1)
Path to Leadership          | A communicated path from lurker to contributor to maintainer. (or. track members: time from user to maintainer/leader) | Rational: If active contributors are not included in leadership decisions they might lose interest and leave. (Focus on least likely contributor) | Interviews: 2 <br /> LFOSLS
Blogposts                   | Number of blogposts that mention the project                                                                           |                                                                                                                                                   | LFOSLS
YouTube Videos              | Number of Youtube videos that mention or specifically deal with the project (e.g. tutorials)                           |                                                                                                                                                   | LFOSLS
Job Postings                | Number of job postings that mention the project as a preferred or required skill                                       |                                                                                                                                                   | LFOSLS
Downloads                   | Number of downloads                                                                                                    | ! *beware:* downloads might be skewed by builders                                                                                                 | LFOSLS
Reopened issues             | Rate of issues closed but discussion continues or issues that were closed and re-opened                                |                                                                                                                                                   | LFOSLS
Release Velocity            | Time between releases                                                                                                  | Regular releases are a reliability metric                                                                                                         | LFOSLS
Release Maturity            | Ratio of major and minor releases                                                                                      |                                                                                                                                                   | LFOSLS
Decision Distribution       | Central vs. distributed decision making                                                                                | Governance model, scalability of community                                                                                                        | LFOSLS
Transparency                | Number of comments per issue                                                                                           | Discussion is occuring openly - could also indicate level of agreement                                                                            | LFOSLS
Roadmap                     | Existence and quality of roadmap                                                                                       | Best Practice: community engagement and scalability (might not be automatically computable)                                                       |
Gatherings                  | Number of face-to-face/in-person meetings per year                                                                     | Resets contentious issues; Resolve tensions; Avoid longstanding grudges                                                                           | LFOSLS
Role Definitions            | Existence and quality of role definitions                                                                              | Governance related. Relates to "Path do Leadership"                                                                                               | LFOSLS
Rewards                     |                                                                                                                        | Rewards, shout-outs, recognition, and mentions in pull-requests or change logs - might improve contribution levels                                | LFOSLS
Retrospectives              | Existence of after release meetings                                                                                    | Collect lessons learned, improve processes, recognize contributors                                                                                | LFOSLS
Onion Layers                | Distance between onion model layers (users, contributors, committers, and steering committee)                          | Rule of thumb: factor of 10x between layers. (Node.js keynote)                                                                                    | LFOSLS
Release Note Completeness   | Number of functionality changes and bug fixes represented in release notes vs. release.                                | Good for users, also shows diligence of community                                                                                                 | LFOSLS
Unity                       |                                                                                                                        | Rivalry or unity of community (sentiment analysis?)                                                                                               | LFOSLS
Use of Acronym              | Frequency of acronyms used                                                                                             | Specialized language can be a barrier for new contributors.                                                                                       | LFOSLS
Language Bias               |                                                                                                                        | Diversity metric: Biase against gender, ethnicity, ... in use of language (maybe use sentiment analysis)                                          | LFOSLS
Commit Bias                 |                                                                                                                        | Diversity metric: acceptance rate (and time to acceptance) differences per gender, ethnicity, etc...                                              | LFOSLS
Stack Overflow              | Several metrics: # of questions asked, response rate, number of responding people that have verified solutions         |                                                                                                                                                   | LFOSLS
Non-Source Contributions    |                                                                                                                        | Track contributions like running tests in test environment, writing blog posts, producing videos, giving talks, etc...                            | LFOSLS
Maturity Label              | Community assigned label                                                                                               | Some communities label projects as incubator, mature, (or something)                                                                              | LFOSLS


## Code Health

Code health contains indicators descriptive of a code base and its quality.

Name                              | Formula                                                 | Description                                                                                                                                                                                        | Occurance
----------------------------------|---------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------
Pull Request made/closed          | Pull requests made vs. pull requests closed             | [Example](http://repocheck.com/#https%3A%2F%2Fgithub.com%2Ftwbs%2Fbootstrap) <br/>Encompasses number of pull requests rejected ([Issue/1](https://github.com/OSSHealth/HealthIndicators/issues/1)) | Interviews: 3
Pull Requests Open                | Number of open pull requests                            | Might be more telling than total pull requests                                                                                                                                                     | Interviews: 1<br/>[Issue/1](https://github.com/OSSHealth/HealthIndicators/issues/1)
Pull Request Comments             | Number of comments per pull request                     |                                                                                                                                                                                                    | Inteviews: 1
Pull Request Discussion Diversity | Number of different people discussing each pull request |                                                                                                                                                                                                    | Interviews: 1
Update Rate                       | Number of updates over period x                         |                                                                                                                                                                                                    | [Issue/1](https://github.com/OSSHealth/HealthIndicators/issues/1)
Update Regularity                 |                                                         | How consistently and frequently are updates provided.                                                                                                                                              | Interviews: 1 <br/>[Issue/1](https://github.com/OSSHealth/HealthIndicators/issues/1)
Update Age                        | Time since last update                                  |                                                                                                                                                                                                    | Interviews: 1 <br/>[Issue/1](https://github.com/OSSHealth/HealthIndicators/issues/1)
Repository Size                   |                                                         | Overall size of the repository or number of commits                                                                                                                                                | [Issue/1](https://github.com/OSSHealth/HealthIndicators/issues/1)
Bugs after Release                | Number of bugs reported after a release                 |                                                                                                                                                                                                    | LFOSLS


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
License Coverage      | Number of files with a file notice (copyright notice + license notice)                             |                                                                                |
