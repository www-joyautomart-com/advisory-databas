## Contributing

[fork]: https://github.com/github/advisory-database/fork
[pr]: https://github.com/github/advisory-database/compare
[schema]: https://ossf.github.io/osv-schema/
[code-of-conduct]: CODE_OF_CONDUCT.md

Hi there! We're thrilled that you'd like to contribute to this project. Your help is essential for keeping it great.

Contributions to this project are [released](https://help.github.com/articles/github-terms-of-service/#6-contributions-under-repository-license) to the public under the [project's open source license](LICENSE.md).

Please note that this project is released with a [Contributor Code of Conduct][code-of-conduct]. By participating in this project you agree to abide by its terms.

## What this repository is for

`github/advisory-database` is the public repository for GitHub Advisory Database records. Contributions here help improve the quality, clarity, and completeness of advisory data so that developers, ecosystems, and security tools can consume consistent vulnerability metadata.

Examples of helpful contributions include:

- Correcting affected package or ecosystem information
- Fixing version ranges
- Adding or improving references
- Correcting CWEs, CVSS data, or other advisory metadata
- Updating existing advisories to better reflect already-public information

## What this repository is _not_ for

This repository is **not** the right place for:

- Reporting a **new vulnerability** that has not yet been disclosed appropriately
- Publishing **proof-of-concept exploit code**
- Coordinating disclosure with a maintainer or vendor
- Escalating a case where a maintainer or vendor is unresponsive
- Privately sharing sensitive details that are not yet public

This repository exists to **curate and publish advisory records**, not to serve as an intake or coordination channel for newly discovered vulnerabilities.

If you need to report a vulnerability to a project maintainer, please use GitHub's guidance on [privately reporting a security vulnerability](https://docs.github.com/code-security/how-tos/report-and-fix-vulnerabilities/privately-reporting-a-security-vulnerability), which also includes instructions for repositories that do not have private vulnerability reporting enabled.

If your contribution includes sensitive or not-yet-public details, **do not open a public pull request or issue here**.

## Before you submit a contribution

Please make sure that:

- The advisory you are updating already exists in this repository, or the vulnerability is already appropriate for a public advisory record
- The information you're adding is based on public, referenceable sources
- Your change follows the OSSF [OSV schema][schema]
- Your pull request updates only **one advisory per PR**

If you want to improve multiple advisories, please submit them as separate pull requests.

## Submitting an advisory improvement

0. [Fork][fork] and clone the repository
0. Create a new branch: `git checkout -b my-name-GHSA-ID`
0. Make your change to the advisory file
0. Push to your fork and [submit a pull request][pr]
0. Pat yourself on the back and wait for your pull request to be reviewed and merged

Here are a few things you can do that will increase the likelihood of your pull request being accepted:

- Follow the OSSF [OSV schema][schema]
- Change one advisory per pull request
- Include links to public references that support your proposed changes
- Keep your changes focused and avoid unrelated formatting edits

## Common reasons we may not be able to accept a contribution

Sometimes we'll need to close or redirect a contribution. Common reasons include:

- The pull request is attempting to disclose a **new vulnerability** rather than improve an advisory record
- The pull request includes **sensitive, private, or not-yet-public information**
- The change is not supported by public references
- The pull request includes changes to multiple advisories
- The contribution is better handled through a private disclosure or maintainer coordination workflow

In these cases, we may ask you to use a more appropriate reporting path instead.

## Stale advisory improvements

Sometimes our curation team may need more information or clarification about your contribution. They will respond directly to your pull request with comments and questions. Once they have this information, they can continue reviewing your changes.

If we don't hear back after a period of time, we may close the pull request. Closing a pull request does **not** mean your contribution is unwelcome, it usually just means we need more information than was provided, or that we couldn't complete review in its current state.

You're always welcome to return with updated information and open a new pull request.

## Resources

- [GitHub Advisory Databaste](https://github.com/advisories)
- [Docs on Editing security advisories in the GitHub Advisory Database](https://docs.github.com/code-security/how-tos/report-and-fix-vulnerabilities/fix-reported-vulnerabilities/editing-security-advisories-in-the-github-advisory-database)
- [How to Contribute to Open Source](https://opensource.guide/how-to-contribute/)
- [Using Pull Requests](https://help.github.com/articles/about-pull-requests/)
- [GitHub Help](https://help.github.com)
- [Privately reporting a security vulnerability](https://docs.github.com/code-security/how-tos/report-and-fix-vulnerabilities/privately-reporting-a-security-vulnerability)
- [About coordinated disclosure of security vulnerabilities](https://docs.github.com/code-security/concepts/vulnerability-reporting-and-management/about-coordinated-disclosure-of-security-vulnerabilities)
