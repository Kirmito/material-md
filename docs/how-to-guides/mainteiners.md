# Maintainers :mag_right:

## Table of Contents

- [Maintainers :mag_right:](#maintainers-mag_right)
  - [Table of Contents](#table-of-contents)
  - [Overview](#overview)
  - [Maintainers List](#maintainers-list)
  - [Workflow for reviewing Pull Requests (PR)](#workflow-for-reviewing-pull-requests-pr)
  - [Merging Pull Requests](#merging-pull-requests)

## Overview

This guide is intended for maintainers, anybody with commit access to one or more Centralized Repo repositories.

The right mix of individuals, teams, and resources can ensure a project’s success. The maintainer's tasks are often unexpected, but they’re just as important to the growing project. The maintainers are contributors who are responsible for driving the vision and managing the organizational aspects of the project.

Maintainers can choose to release new maintenance releases with each new patch, or accumulate patches until a significant number of changes are in place.

## Maintainers List

|         Maintainer             |      GitHub ID       |
| :----------------------------: | :------------------: |
| Juan David Gutierrez Reyes     | david-gutierrez      |
| Carlos Andres Zambrano Barrera | carlos-zambrano      |
| Jorge Ernesto Guevara Cuenca   | jorge-guevara        |
| Jhonnatan Gil Chaves           | jhonnatan-gilchaves  |

## Workflow for reviewing Pull Requests (PR)

We recommend reviewing pull requests directly within GitHub. This allows a public commentary on changes, providing transparency for all users.

A PR without comments is surely a poorly reviewed PR. It's not that mistakes are always made, but surely there are always ideas to discuss. Wealth in the exchange of opinions should flow. A peer-reviewed code will always be better code than code that you alone developed. Even a self-revision is always better than leaving it without any revision, since during development we are usually flawed and some minor detail may have escaped us. This will also help team members who are alone on the project to be able to share their ideas and code and not feel lonely in their solution.

When providing feedback be civil, courteous, and kind. Disagreement is fine, so long as the discourse is carried out politely. If we see a record of uncivil or abusive comments, we will revoke your commit privileges and invite you to leave the project.

During your review, consider the following points:

- Do the changes make sense? If you do not understand what the changes are or what they accomplish, ask the author for clarification. Ask the author to add comments or clarify test case names to make the intentions clear. At times, such clarification will reveal that the author may not be using the code correctly, or is unaware of features that accommodate their needs. If you feel this is the case, work up a code sample that would address the issue for them, and feel free to close the issue once they confirm.
- Does the change have impact? While fixing typos is nice as it adds to the overall quality of the project, merging a typo fix at a time can be a waste of effort. (Merging many typo fixes because somebody reviewed the entire component, however, is useful!).
- Changes in variable names. Ask whether or not the change will make understanding the code easier, or if it could simply a personal preference on the part of the author.
- Formatting changes. Most formatting changes should be generated only by a coding standards checker/fixer — and those will normally be caught by continuous integration.

Essentially: feel free to close issues that do not have impact.

- Is this a new feature? If so:

  - Does the issue contain narrative indicating the need for the feature? If not, ask them to provide that information. Since the issue will be linked in the changelog, this will often be a user's first introduction to it.
  - Is the feature necessary for general use cases? Try and keep the scope of any given component narrow. If a proposed feature does not fit that scope, recommend to the user that they maintain the feature on their own, and close the request.
  - Are new unit tests in place that test all new behaviors introduced? If not, **do not merge** the feature until they are!
  - Is documentation in place for the new feature?. If not **do not merge** the feature until it is!

  This workflow ensures that the author of the patch is responsible for any merge conflicts. Since the author is the one most familiar with the changes they are introducing, they are the party most likely to resolve conflicts correctly.

## Merging Pull Requests

Check which branch the PR was made against, which new features were worked on and check the items before mentioned to approve the PR . In addition as maintainers we can:

- Approve a PR.
- Approve a PR with comments: this will mean that we have left a comment, but that we consider that the PR can be merged without problems, since it has been a comment that when evaluating it the developer will decide whether to solve it or not.
- Wait for an answer from the author: we consider that our question / comment is important for the RP, so we wait for the author to answer us before we can approve this RP. (I insist once again that a PR is not blocking to continue working, since you can create a separate branch and continue with another task while this is resolved.)
- Once feedback starts rolling in be sure to respond to comments that desire a response. Doing so helps everyone keep track of the feedback that has been seen and considered.

Some pull requests are so small, clear, and tidy that they take all but a minute or two to get merged. Others may be larger with loftier goals or creative solutions to complex problems. Of course, there’s quite the variety in between.

Opening every pull request with the goal of getting the most out of both the work and the review itself has made peer review an engaging activity amongst peers and colleagues. We need to incorporate and keep this. We hope these numerals help to find a good rhythm for framing and taking part in these conversations.

:heavy_check_mark: Happy code mainteners !
