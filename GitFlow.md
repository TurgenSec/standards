# GitFlow

- Git Basics: https://rogerdudler.github.io/git-guide/
- When shit hits the fan: https://ohshitgit.com/
- GitHub PR: https://guides.github.com/activities/hello-world/#pr

We will be practising a mini version of [Git Flow](https://datasift.github.io/gitflow/IntroducingGitFlow.html).

The current version is to enhance developer velocity. Once we have proper customers and releases, we will move to the full GitFlow model.

## Developer GitFlow Guide

- All work by developers should happen in their own branch, which was created from master.
- For all completed work, raise a Pull Request(PR) to the master/main branch and tag your Github Team (eg: @TurgenSec/datashadow, @TurgenSec/saas, etc ) in the description. This ensures everyone in the team is aware of the discussions.
- Keep your PRs short. It's easier to review small chunks than a big fat PR with a thousand lines.
- All team members should go through Open PRs, review the code and give suggestions if any. You should make it a habit to review and comment on your own PR. After all, you know your code best and will catch any issues easier.
- You should NEVER merge your own PR. It will be merged after all comments are resolved.
- Two ways to resolve a comment.
  - Small code fixes/suggestion can be merged directly
  - Do not resolve a comment without any explanation if you are not implementing the comment. Leave an explanation on why the comment is not valid and wait for the commenter to resolve it or reply. 

## Commit Messages

- Follow https://www.conventionalcommits.org/en/v1.0.0/ when possible
- Avoid non descriptive messages like 'Update', 'Test', etc.

## Releases

- master/main will be the Branch being released to Production.

