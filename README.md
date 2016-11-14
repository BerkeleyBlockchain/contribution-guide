# Blockchain @ Berkeley Contribution Guide

The Blockchain @ Berkeley organization is made up of many students working together on various blockchain related software products. All members of the organization that contribute code must follow these guidelines. These guidelines ensure that the organization produces high quality code with efficient collaboration.

This is a living document and we are open to ways we can improve. Feel free to create a GitHub issue with suggestions or make a pull request with contributions.

This guide should

## Table of contents

1. Source control
  a. GitHub
  b. Commit messages
  c. Master branch
  d. Branches
  e. Getting code into the main branch via pull requests
  f. Avoid merge bubbles by rebasing
  g. Signing commits
2. Code style
3. License for code

## Source control
We exclusively use git for our source control. To learn git, use https://try.github.io/

### GitHub
We use our GitHub organization BerkeleyBitcoin for all our public and private projects. To gain access to the GitHub organization, contact an officer in charge of this. Also know that not all projects are public for everyone to access. Each repository may have a custom list of who has access.

### Commit messages
Commit messages should be detailed and be descriptive and follow a format

- Write commit messages as a sentence
- Capitalize sentences
- Leave the last period off
- Make sure one commit does just one thing
- Use either:
  - Present tense of the commit does
  - A description of what the changes in the code does

Examples:
- Add catching of error in Baz
- Improve support for the Foo library
- Fix off by one error in the Bar loop

### Master branch
Do not commit directly to the master branch. All contributions should be done via pull requests.

The master branch should be a [protected branch](https://help.github.com/articles/about-protected-branches/) (which can be set up by an adminstrator of the GitHub repository). A protected master branch would enforce this master branch.

### Branches
When implementing a new feature, branch off where your feature is going to be merged into (usually the master branch). There are two places where the branch can live:
- On the repository owned by BerkeleyBitcoin. This enables others to also make changes to your branch.
- On your own fork of the repository. Do not do this for private sensitive projects.

### Pull Requests
- To get code into the master branch, use a pull request
- A pull request must go through a code review by a team member different from the submitter of the pull request.
- A pull request can be merged once there is approval by a team member. Approval should come in a form of a comment on the GitHub pull request.
- Do not squash commits. It is helpful to see the commit history

### Signing git commits with GPG
We care about the integrity of our code. We highly suggest contributors set up a GPG key and sign all their git commits with it. We recommend using these resources:

- [Keybase](https://keybase.io/): A user friendly way to get started with GPG: https://keybase.io/
- [How to sign git commits using GPG](https://help.github.com/articles/signing-commits-using-gpg/)
- [How to add a GPG key to your GitHub account](https://help.github.com/articles/adding-a-new-gpg-key-to-your-github-account/)
- [Mac GPG client: Mac GPG Suite](https://gpgtools.org/)
- [Windows GPG client: Gpg4win](https://www.gpg4win.org/)

## Code style
For code style, use what is most idiomatic in language being worked in. If there is disagreement, then default to the organization wide suggestion:

- 2 character wide indents
- Indent using spaces
- Use a style enforcer if possible (e.g. jshint and gofmt)

## License of code
For all our open source projects, we should use the [Apache 2.0 license](https://www.apache.org/licenses/LICENSE-2.0).

## License of this contribution guide

This contribution guide itself is licensed under the Apache 2.0 license. Feel free to fork this and modify for your own use.