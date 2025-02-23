# Common Workflow Language Website

The main repo for the [CWL Website](https://www.commonwl.org/).

GitHub: https://github.com/common-workflow-language/cwl-website/

## Table of Contents

<!-- MarkdownTOC -->

* [Repositories](#repositories)
* [Getting Started](#getting-started)
* [Contributing](#contributing)
* [Reporting a Vulnerability](#reporting-a-vulnerability)
* [User Gallery Nomination](#user-gallery-nomination)
* [Editing the Main Site](#editing-the-main-site)

<!-- /MarkdownTOC -->

<a id="repositories"></a>
## Repositories

The main website's files are in the `/content/` directory, and built with [Jekyll](https://jekyllrb.com/).

The [CWL Specification](https://github.com/common-workflow-language/cwl-v1.2) and [User Guide](https://github.com/common-workflow-language/user_guide) are hosted separately from this repo, but built via the `/site/` directory and `./website.sh` script found here.

<a id="getting-started"></a>
## Getting Started

For setup and development instructions, see [CWL Website Instructions - Setup & Development](/content/README.md#setup--development)

<a id="contributing"></a>
## Contributing

**Contributing to New Issues:**

1. Create a new [GitHub Issue](https://github.com/common-workflow-language/cwl-website/issues/new/choose)
2. In your terminal, from the `main` branch, create a new local branch by running `git checkout -b branch-name-here`
3. Edit & Commit your changes, mentioning the Issue number in your commit, e.g. `git commit file-names-here -m "Fix XYZ from #99"`
4. Push the changes via `git push origin branch-name-here`
5. Find the branch on the GitHub repo (the url looks like `https://github.com/common-workflow-language/cwl-website/tree/branch-name-here`) and click "Compare and Pull Request"
6. The reviewers will either suggest additional revisions, or approve the pull request.

**Existing Issues:** To contribute to an existing issue and branch: Checkout the existing branch via `git checkout remote-branch-name-here` (don't add the `-b`). Then follow steps 3-6 above.

<a id="reporting-a-vulnerability"></a>
## Reporting a Vulnerability

See the [Security Policy](https://github.com/common-workflow-language/cwl-website/security/policy) page.

<a id="user-gallery-nomination"></a>
## User Gallery Nomination

To suggest a new entry for the CWL User Gallery, create a new Issue, via the: [User Gallery Nomination issue template](https://github.com/common-workflow-language/cwl-website/issues/new?assignees=&labels=user+gallery&template=user-gallery-nomination.md&title=User+Gallery+Nomination%3A+%5Buser%2Fproject+name+here%5D)

<a id="editing-the-main-site"></a>
## Editing the Main Site

Setup Instructions: [CWL Website Instructions - Setup & Development](content/README.md#setup-and-development)

Editing Guidelines: [Editing the CWL Website](content/EDITING.md)

The root directory contains the following important files and directories:

* `/content/` - directory for the **main website**
* `/site/` - directory for the docs. **Not the main site**
* `README.md` - general readme for the repo.
* `website.sh` - script that builds the website (both the main site and the docs)

Note: All edits and updates should be made in `/content/` unless there is a specific reason to do otherwise.
