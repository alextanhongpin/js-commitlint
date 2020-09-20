# Setup commitlint

This repo demonstrates the usage of commitlint and how the examples for commit messages.

## Commit type

The types available are based on the [angular convention](https://github.com/angular/angular/blob/22b96b9/CONTRIBUTING.md#-commit-message-guidelines).

- build: Changes that affect the build system or external dependencies, e.g. build: add loki snapshot testing
- ci: Changes to our CI configuration files and scripts, e.g. ci: modify Github Actions to execute integration testing
- docs: Documentation only changes, e.g. docs: document quickstart
- feat: A new feature, equivalent to _minor_ in SemVer e.g. feat(appointment): add api for Appointment
- fix: A bug fix, equivalent to _patch_ in SemVer, e.g. fix(appointment): invalid reference to non-existing variable
- perf: A code change that improves performance, e.g. perf(sort): use quicksort for sorting numbers
- refactor: A code change that neither fixes a bug nor adds a feature, e.g. refactor(appointment): simplify conditional when checking if the appointment has been assigned
- style: Changes that do not affect the meaning of the code, e.g. style: run lint against code
- test: Adding missing tests or correcting existing tests, e.g. test(appointment): add integration test

References:
https://github.com/conventional-changelog/commitlint
