# CI/CD

Basics : https://docs.gitlab.com/ee/ci/introduction/

We currently use [GithubActions](https://github.com/features/actions) to run all our test and deployment pipelines.

All projects should have Github Actions defined which do the following:

- Lint (Mandatory on new projects)
- Compile/Typecheck (Based on language)
- Test (At least the basic functionality works)
- Deploy (When merged to master)

Developers should not be deploying code to production.
