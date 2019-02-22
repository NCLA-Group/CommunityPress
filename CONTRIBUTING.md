# Contributing to CommunityPress

:tada: First and foremost, thank you for taking the time to contribute! :tada:

The following is a set of guidelines for contributing to CommunityPress and it's packages, which are hosted in the [Neutron Creative Organization](https://github.com/Neutron-Creative) on Github. These are guidelines, not rules. Please use discretion, and feel free to propose changes to this document in a pull request.

## Table of Contents

[Code of Conduct](#code-of-conduct)

[Ways to Contribute](#ways-to-contribute)
    * [Reporting Bugs](#reporting-bugs)
        * [Bug Report Guidelines](#bug-report-guidelines)
    * [Suggesting Enhancements](#suggesting-enhancements)
        * [Enhancement Suggestion Guidelines](#enhancement-suggestion-guidelines)
    * [Pull Requests](#pull-requests)

[Style Guides](#style-guides)
    * [Git Commit Messages](#git-commit-messages)

## Code of Conduct
This project and everyone participating in it is governed by the [CommunityPress Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to [support@neutroncreative.com](mailto:support@neutroncreative.com).

## Ways to Contribute

### Reporting Bugs

This section guides you through submitting a bug report for Atom. Following these guidelines helps maintainers and the community understand your report :pencil:, reproduce the behavior :computer: :computer:, and find related reports :mag_right:
    
#### Bug Report Guidelines

Explain the problem and include additional details to help maintainers reproduce the problem:

* **Use a clear and descriptive title** for the issue to identify the problem.
* **Describe the exact steps which reproduce the problem** in as many details as possible.
* **Provide specific examples to demonstrate the steps**. Include links to files or GitHub projects, or copy/pasteable snippets, which you use in those examples. If you're providing snippets in the issue, use [Markdown code blocks](https://help.github.com/articles/markdown-basics/#multiple-lines).
* **Describe the behavior you observed after following the steps** and point out what exactly is the problem with that behavior.
* **Explain which behavior you expected to see instead and why.**
* **Include screenshots and animated GIFs** which show you following the described steps and clearly demonstrate the problem. If you use the keyboard while following the steps, **record the GIF with the [Keybinding Resolver](https://github.com/atom/keybinding-resolver) shown**. You can use [this tool](https://www.cockos.com/licecap/) to record GIFs on macOS and Windows, and [this tool](https://github.com/colinkeenan/silentcast) or [this tool](https://github.com/GNOME/byzanz) on Linux.
* **If the problem wasn't triggered by a specific action**, describe what you were doing before the problem happened and share more information using the guidelines below.

Provide more context by answering these questions:

* **Did the problem start happening recently** (e.g. after updating to a new version of CommunityPress) or was this always a problem?
* If the problem started happening recently, **can you reproduce the problem in an older version of CommunityPress?** What's the most recent version in which the problem doesn't happen?
* **Can you reliably reproduce the issue?** If not, provide details about how often the problem happens and under which conditions it normally happens.

Include details about your configuration and environment:

* **Which version of WordPress are you using?** You can get the exact version by running `wp core version` via wp-cli
* **What's your current CommunityPress Configuration**?
* **Is the WordPress instance self-hosted, or cloud-hosted?** If self-hosted, please list as many details as you can regarding server configuration for debugging purposes. If cloud-hosted, please list your hosting-provider and configuration details for debugging purposes.

### Suggesting Enhancement

This section guides you through submitting a enhancement suggestion for CommunityPress, ranging from out-of-scope functionality to minor improvements to in-scope functionality.

#### Enhancement Suggestion Guidelines
    
* **Use a clear and descriptive title** for the issue to identify the suggestion.
* **Provide a step-by-step description of the suggested enhancement** in as many details as possible.
* **Provide specific examples to demonstrate the steps**. Include copy/pasteable snippets which you use in those examples, as [Markdown code blocks](https://help.github.com/articles/markdown-basics/#multiple-lines).
* **Describe the current behavior** and **explain which behavior you expected to see instead** and why.
* **Include screenshots and animated GIFs** which help you demonstrate the steps or point out the part of Atom which the suggestion is related to. You can use [this tool](https://www.cockos.com/licecap/) to record GIFs on macOS and Windows, and [this tool](https://github.com/colinkeenan/silentcast) or [this tool](https://github.com/GNOME/byzanz) on Linux.
* **Explain why this enhancement would be useful** to most CommunityPress users.
* **List an existing plugin, application, or CMS where this enhancement exists.**

### Pull Requests

The process described here has several goals:

- Maintain the CommunityPress quality standard
- Fix problems that are important to users
- Engage the community in working toward the best possible Atom
- Enable a sustainable system for Atom's maintainers to review contributions

Please follow these steps to have your contribution considered by the maintainers:

1. Follow all instructions in [the template](PULL_REQUEST_TEMPLATE.md)
2. Follow the [styleguides](#style-guides)
3. After you submit your pull request, verify that all [status checks](https://help.github.com/articles/about-status-checks/) that may apply are passing <details><summary>What if the status checks are failing?</summary>If a status check is failing, and you believe that the failure is unrelated to your change, please leave a comment on the pull request explaining why you believe the failure is unrelated. A maintainer will re-run the status check for you. If we conclude that the failure was a false positive, then we will open an issue to track that problem with our status check suite.</details>

While the prerequisites above must be satisfied prior to having your pull request reviewed, the reviewer(s) may ask you to complete additional design work, tests, or other changes before your pull request can be ultimately accepted.

## Styleguides

### Git Commit Messages

* Use the present tense ("Add feature" not "Added feature")
* Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
* Limit the first line to 72 characters or less
* Reference issues and pull requests liberally after the first line
* When only changing documentation, include `[ci skip]` in the commit title
* Consider starting the commit message with an applicable emoji:
    * :crane: `:crane:` when adding enhancements or expanding the project scope
    * :art: `:art:` when improving the format/structure of the code
    * :racehorse: `:racehorse:` when improving performance
    * :memo: `:memo:` when writing docs
    * :bug: `:bug:` when fixing a bug
    * :fire: `:fire:` when removing code or files
    * :green_heart: `:green_heart:` when fixing the CI build
    * :white_check_mark: `:white_check_mark:` when adding tests
    * :lock: `:lock:` when dealing with security
    * :arrow_up: `:arrow_up:` when upgrading dependencies
    * :arrow_down: `:arrow_down:` when downgrading dependencies