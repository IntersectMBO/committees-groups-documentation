# Contributing to the xxxx Committee documentation

## Table of Contents

- [Contributing to the xxxx Committee documentation](#contributing-to-the-xxxx-committee-documentation)
  - [Table of Contents](#table-of-contents)
  - [Code of Conduct](#code-of-conduct)
  - [Roles and Responsibilities](#roles-and-responsibilities)
  - [I Want To Contribute](#i-want-to-contribute)
    - [Setup](#setup)
    - [Make changes](#make-changes)
  - [Working Conventions](#working-conventions)
    - [Pull Requests](#pull-requests)
    - [Branch Naming](#branch-naming)
    - [Commit Messages](#commit-messages)
      - [Rationale](#rationale)

## Code of Conduct

This project and everyone participating in it is governed by the [Code of Conduct](./CODE-OF-CONDUCT.md).
By participating, you are expected to uphold this code.

## Roles and Responsibilities

We maintain a [CODEOWNERS file](./CODEOWNERS) which provides information who should review a contributing PR.
Note that you might need to get approvals from all code owners (even though GitHub doesn't give a way to enforce it).

## I Want To Contribute

### Setup

1. **Fork the repository:**
   - Navigate to  https://github.com/xxxx/xxxx-committee-documentation
   - Press the `Fork` button and make a fork of the repository.

2. **Clone the fork:**
   - Open a terminal on your computer.
   - Navigate to the directory where you want to store the project.
   - Run the following command to clone the repository:
     ```shell
     git clone https://github.com/xxxx/xxxx-committee-documentation.git
     ```

3. **Navigate to the Project Directory:**
   - After cloning, change into the project's root directory:
     ```shell
     cd xxxx-committee-documentation
     ```

### Make changes

1. **Make a branch for your changes:**
   - It is good practice to make a branch per set of changes being made
   - In the project directory, open terminal and execute the follow command
     ```shell
     git checkout -b add-my-new-thing
     ```

2. **Make your and push your changes:**
   - Make your changes to the files.
   - Then push these changes to your branch, using a informative commit message.
     ```shell
     git add .
     git commit -m "I am adding my new thing"
     git push
     ```

3. **Make a pull request:**
   - You can now make a pull request from your branch to the base repo.


## Working Conventions

### Pull Requests

Thank you for contributing your changes by opening a pull requests!

To get something merged we usually require:
- Follow the Pull Request template
- Description of the changes - if your commit messages are great, this is less important
- Quality of changes is ensured - through new or updated automated tests
- Change is related to an issue, feature (idea) or bug report - ideally discussed beforehand
- Well-scoped - we prefer multiple PRs, rather than a big one

Please reuse the branch naming for the pull request naming.

### Branch Naming

- When creating your branches please create informative names.
- Using prefixes such as `feat/`, `fix/`, `chore/`, `docs/` for branch names are a good start.
- Using the related issue number after the prefix is required.

Examples:
- `feat/123-added-ability-for-dreps-to-change-drep-id`
- `fix/312-fixed-drep-ids-being-reversed`
- `chore/567-bumped-cardano-node-version-to-9`
- `docs/88-tweak-contributing-pr-template-codeowners`

### Commit Messages

Please make informative commit messages!
It makes it much easier to work out why things are the way they are when you’re debugging things later.

A commit message is communication, so as usual, put yourself in the position of the reader: what does a reviewer, or someone reading the commit message later need to do their job?
Write it down!
It is even better to include this information in the code itself, but sometimes it doesn’t belong there (e.g. ticket info).

Also, include any relevant meta-information, such as issue numbers.
If a commit completely addresses a issue, you can put that in the headline if you want, but it’s fine to just put it in the body.

Here are seven rules for great git commit messages:
1. Separate subject from body with a blank line
2. Limit the subject line to 50 characters (soft limit)
3. Capitalize the subject line
4. Do not end the subject line with a period
5. Use the imperative mood in the subject line and suffix with ticket number if applicable
6. Wrap the body at 72 characters (hard limit)
7. Use the body to explain what and why vs. how

There is plenty to say on this topic, but broadly the guidelines in [this post](https://cbea.ms/git-commit/) are good.

#### Rationale

Git commit messages are our only source of why something was changed the way it was changed.
So we better make the readable, concise and detailed (when required).
