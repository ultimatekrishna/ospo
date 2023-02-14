
# Contributing Guidelines

- [Contributing Guidelines](#contributing-guidelines)
  - [Reporting a Security Issue ⚠️](#reporting-a-security-issue-️)
  - [Code of Conduct](#code-of-conduct)
  - [Getting Started](#getting-started)
  - [Getting Help](#getting-help)
  - [Office Hours](#office-hours)
  - [Development Environment Setup](#development-environment-setup)
  - [Pull Request Lifecycle](#pull-request-lifecycle)
  - [Pull Request Checklist](#pull-request-checklist)
  - [Sign your Commits (DCO)](#sign-your-commits-dco)
  - [Learn more](#learn-more)

Thank you so much for your interest in contributing to the OSPO project! 💖

We love external input and try to make the process as easy as possible. The following document describes how to get help and where to start.

## Reporting a Security Issue ⚠️

 Do not report security vulnerabilities through public GitHub issues! Please give us time to fix the issue before disclosing it. See the [security guide](SECURITY.md) on steps to report and disclose in a responsible way.

## Code of Conduct

Help us to make this project open and inclusive. Please read and follow our [Code of Conduct](CODE_OF_CONDUCT.md).

## Getting Started

If you want to contribute, but do not know where to start, here are some ideas:

- Write a blog post
- Answer open source questions on our Github Discussions forum
- Search for issues with the labels *good first issue* or *help wanted*

If you need help to pick a issue that fits your interest do not hesitate to ask on Github Discussions. Once you have found an issue leave a comment that you are working on it to avoid double work.

## Getting Help

The best way to get help is:

- Asking on the issue you are working on
- Create a [draft pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests#draft-pull-requests). You can add questions to specific [code lines](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/reviewing-changes-in-pull-requests/commenting-on-a-pull-request#adding-line-comments-to-a-pull-request) as comments.
- Join the weekly office hours

## Office Hours

TODO

## Development Environment Setup

Please see [Development Guide](DEVELOPMENT.md)

## Pull Request Lifecycle

We follow the [Github Flow](https://docs.github.com/en/get-started/quickstart/github-flow) process

1. Create an issue, if not existing yet, to discuss what you want to implement
2. Fork the repository and create your branch from master
3. Regularly pull changes from origin
4. Push changes to your fork and open a pull request
    - Fill in the required template
    - Add a summary of all major changes in the description
    - [Link](https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue)  the pull request and the issue being resolved
    - Enable the option [allow maintainers edits](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/allowing-changes-to-a-pull-request-branch-created-from-a-fork) for faster merging
    - Apply [suggest changes](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/reviewing-changes-in-pull-requests/incorporating-feedback-in-your-pull-request) from reviewers. You can do so directly in the Github UI or commit changes to your fork
    - Mark each suggested change as [resolved](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/reviewing-changes-in-pull-requests/commenting-on-a-pull-request#resolving-conversations)
    - [Re-request a review](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/reviewing-changes-in-pull-requests/incorporating-feedback-in-your-pull-request#re-requesting-a-review) when you are done with all changes
5. Make sure automated tests do not have errors
    - With errors a PR might be ignored and not receive reviews.
    - If you need a review despite test errors, then mark your PR as draft.

## Pull Request Checklist

<!-- TODO enhance this list-->
- If the layout was changed, please test in different browsers and various form factors

## Sign your Commits (DCO)

For each commit in a pull request you must acknowledge the following terms and conditions:

<!-- Copied from https://developercertificate.org/. License in text below. Do not modify. -->
```code
Developer Certificate of Origin
Version 1.1

Copyright (C) 2004, 2006 The Linux Foundation and its contributors.

Everyone is permitted to copy and distribute verbatim copies of this
license document, but changing it is not allowed.


Developer's Certificate of Origin 1.1

By making a contribution to this project, I certify that:

(a) The contribution was created in whole or in part by me and I
    have the right to submit it under the open source license
    indicated in the file; or

(b) The contribution is based upon previous work that, to the best
    of my knowledge, is covered under an appropriate open source
    license and I have the right under that license to submit that
    work with modifications, whether created in whole or in part
    by me, under the same open source license (unless I am
    permitted to submit under a different license), as indicated
    in the file; or

(c) The contribution was provided directly to me by some other
    person who certified (a), (b) or (c) and I have not modified
    it.

(d) I understand and agree that this project and the contribution
    are public and that a record of the contribution (including all
    personal information I submit with it, including my sign-off) is
    maintained indefinitely and may be redistributed consistent with
    this project or the open source license(s) involved.
```
<!-- DCO end. Do not modify -->

Simplified speaking, you acknowledge that:

1. The commit does not contain code you found on the internet e.g. StackOverflow (because you do not own the copyright)
2. If the code was written during work hours, then you have received an *explicit* allowance by your employer to submit the code (because your employer owns the copyright)
3. The code submitted by you can be used by others under the terms and conditions of the project license
4. Personal data (your name) will be stored in the git history and cannot be removed

The acknowledgement must be done on every commit with a sign-off statement in the commit message. E.g.

```code
Documentation improvements

Signed-off-by: Joe Doe <joe.doe@example.com>
```

You must use your real name. After setting `user.name` and `user.email` in git config, the sign-off process can be automated with `git commit -s`.

If you forget to sign-off commits, than the pull request will be rejected by the DCO check. Please see the DCO Troubleshoot Guide (TODO) how to resolve.

## Learn more

If you would like to learn more about the technologies that we use, check out the resources below:

<!-- TODO Enhance this list -->
- [Git](https://ohshitgit.com/)
- TODO
