# Contributing to Outboard

First off, thank you for considering contributing to Outboard!
We're excited you're here and appreciate you taking the time to help us build this new PHP framework.
Every contribution, from a typo fix to a new feature, is valuable.

This document provides a set of guidelines for contributing to Outboard and its related packages.
These are mostly guidelines, not strict rules. Use your best judgment, and feel free to propose changes to this document in a pull request.

## Code of Conduct

This project and everyone participating in it is governed by our copy of the [Contributor Covenant Code of Conduct](https://github.com/outboardphp/.github/blob/main/CODE_OF_CONDUCT.md).
By participating, you are expected to uphold this code. Please report unacceptable behavior.

## How Can I Contribute?

There are many ways to contribute to Outboard, and we welcome all of them!

* **Reporting Bugs:** Help us find and squash bugs by submitting detailed issue reports.
* **Suggesting Enhancements:** Have an idea for a new feature or an improvement to an existing one? Let us know!
* **Writing Code:** Help us build the framework by fixing bugs or implementing new features.
* **Improving Documentation:** Good documentation is key. Help us make it clear and comprehensive.
* **Community Support:** Answering questions in our discussion forums helps other users and strengthens the community.

### Have a Question?

If you have a question about using the framework or want to discuss a broader topic, the best place to start is our [GitHub Discussions](https://github.com/orgs/outboardphp/discussions).

## Reporting Bugs and Requesting Features

All bug reports and feature requests should be submitted through [GitHub Issues](https://github.com/outboardphp/outboard/issues).

Before submitting a new issue, please perform a quick search to see if the issue has already been reported.
If it has, you can add a "thumbs up" reaction to the existing issue to show your support or add any new information you have as a comment.

When creating a new issue, please include as much detail as possible. For bug reports, this should include:
* A clear and descriptive title.
* The version of PHP you are using.
* A step-by-step description of how to reproduce the bug.
* Any relevant code snippets.

*Note: We will be creating Issue Templates to streamline this process in the future.*

## Submitting Pull Requests

We use a standard "Fork & Pull Request" workflow for code contributions.

1.  **Fork** the [main repository](https://github.com/outboardphp/outboard) on GitHub.
2.  **Clone** your fork to your local machine: `git clone https://github.com/your-username/outboard.git`
3.  **Create a new branch** for your changes. While we haven't formalized a strict naming convention yet, please use a descriptive name (e.g., `fix/login-bug` or `feature/new-validator`).
    ```bash
    git checkout -b your-branch-name
    ```
4.  **Make your changes** to the codebase.
5.  **Commit** your changes with a clear and descriptive commit message that follows the [Conventional Commits](https://www.conventionalcommits.org/) standard.
    *We may add tooling to support this.*
6.  **Push** your branch to your fork on GitHub: `git push -u origin your-branch-name`
7.  **Open a Pull Request** from your forked repository to the `main` branch of the official Outboard repository. Please provide a detailed description of the changes you have made.

## Development Setup

To get started with development, you will need the following:

* **PHP:** We support PHP versions from 8.4 to the latest stable version.
* **Composer:** We use Composer v2 to manage project dependencies.

After cloning the repository, install the dependencies by running:

```bash
composer install
```
*Note: As the project matures, a list of required PHP extensions will be documented here.*

## Coding Standards

Outboard follows the **PER Coding Style**. We will be using tooling (like PHP-CS-Fixer or PHP_CodeSniffer) to enforce this standard.
Please ensure your contributions adhere to the latest supported version of PER-CS.

## Testing

We use [PhpSpec](https://phpspec.net/) for unit testing our libraries.

While it is not strictly required at this early stage, **we highly recommend that new code submissions are accompanied by tests.**
This helps ensure the stability and reliability of the framework as it grows. As the project matures, this recommendation will likely become a requirement.

*Information regarding integration testing and other testing frameworks will be added here as those decisions are made.* 

## Security Vulnerability Reporting

The security of Outboard is a top priority. If you discover a security vulnerability within the framework, we ask that you report it to us privately.
**Please do not disclose the vulnerability publicly by creating a GitHub issue.**

*This section will be updated with a dedicated security email address once it is established.*

Thank you for helping us make Outboard a great PHP framework!
