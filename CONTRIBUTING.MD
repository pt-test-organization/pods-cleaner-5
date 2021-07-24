# Contributing guidelines

* The branch should be named `JIRA-1234-Your_description`.
* The PR title has to be in the format:
  **level(scope)**: [JIRA-1234] Human-readable description

  Where `level` is one of:

  * **feat**: A new feature
  * **fix**: A bug fix
  * **docs**: Documentation only changes
  * **style**: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)
  * **refactor**: A code change that neither fixes a bug nor adds a feature
  * **perf**: A code change that improves performance
  * **test**: Adding missing or correcting existing tests
  * **chore**: Changes to the build process or auxiliary tools and libraries such as documentation generation

* Every Pull Request will have to be reviewed by at least one other developer.
* At the end of review, the PR is squashed (use GitHub's <q>Squash and merge</q>) into a single commit in `master`.
  Unless the PR has a `DO NOT MERGE` label, it's expected for the reviewer to squash&merge it.
* The PR branch should be removed from GitHub after merge, to avoid confusion in the future.
{"mode":"full","isActive":false}
