# GitHub API Data We are Interested in (First Pass)

### Activity

| Data                        | GitHub API                                                | GHTorrent                      |
| --------------------------- | --------------------------------------------------------- | ------------------------------ |
| Events                      | https://developer.github.com/v3/activity/events/          | events (MongoDB only)          |
| Notifications               | https://developer.github.com/v3/activity/notifications/   |                                |
| Starring                    | https://developer.github.com/v3/activity/starring/        | watchers                       |
| Watching                    | https://developer.github.com/v3/activity/watching/        | events (MongoDB only)          |

### Issues

| Data                        | GitHub API                                                | GHTorrent                      |
| --------------------------- | --------------------------------------------------------- | ------------------------------ |
| Issues                      | https://developer.github.com/v3/issues/                   | issues                         |
| Comments                    | https://developer.github.com/v3/issues/comments/          | issue_comments                 |
| Assignees                   | https://developer.github.com/v3/issues/assignees/         | issues                         |
| Events                      | https://developer.github.com/v3/issues/events/            | issue_events                   |
| Labels                      | https://developer.github.com/v3/issues/labels/            | issue_labels                   |
| Reactions                   | https://developer.github.com/v3/issues/labels/            | issue_labels                   |

### Pull Requests

| Data                        | GitHub API                                                | GHTorrent                      |
| --------------------------- | --------------------------------------------------------- | ------------------------------ |
| Pull Requests               | http://developer.github.com/v3/pulls/                     | pull_requests                  |
| Pull Requests Comments      | http://developer.github.com/v3/pulls/comments/            | pull_requests_comments         |

### Repositories

| Data                        | GitHub API                                                | GHTorrent                      |
| --------------------------- | --------------------------------------------------------- | ------------------------------ |
| Repositories                | https://developer.github.com/v3/repos/                    | projects                       |
| Releases                    | https://developer.github.com/v3/repos/releases/           | events                         |
| Commits                     | https://developer.github.com/v3/repos/commits/            | commits                        |
| Commit Comments             | https://developer.github.com/v3/repos/comments/           | commit_comments                |
| References                  | https://developer.github.com/v3/repos/commits/            | commits                        |
| Collaborators               | https://developer.github.com/v3/repos/collaborators/      | repo_collaborators             |
| Forks                       | https://developer.github.com/v3/repos/forks/              | forks, projects                |
| Merging                     | https://developer.github.com/v3/repos/merging/            | pull_request_history           |
| Traffic                     | https://developer.github.com/v3/repos/traffic/            |                                |
| Pages                       | https://developer.github.com/v3/repos/pages/              |                                |
| Statistics                  | https://developer.github.com/v3/repos/statistics/         |                                |

### Users

| Data                        | GitHub API                                                | GHTorrent                      |
| --------------------------- | --------------------------------------------------------- | ------------------------------ |
| Users                       | https://developer.github.com/v3/users/                    | users                          |
| Followers                   | https://developer.github.com/v3/repos/releases/           | events                         |
