# Contributing to quarto-template

First off, thanks for taking the time to contribute to `quarto-template`!

All types of contributions are encouraged and valued. See the 
[Table of contents](#table-of-contents) for different ways to help and details 
about how this project handles them. Please make sure to read the relevant 
section before making your contribution. It will make it a lot easier for us 
maintainers and smooth out the experience for all involved.



## Table of contents

- [Code of conduct](#code-of-conduct)
- [Style guide](#style-guide)
- [Commit messages](#commit-messages)
- [Asking questions](#asking-questions)
- [Reporting bugs](#reporting-bugs)
- [Requesting features](#requesting-features)
- [Contributing code](#contributing-code)



## Code of conduct

This project is released with a [Contributor Code of Conduct](https://github.com/biodiversitydata/quarto-template/blob/main/CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to <rdev.nc@gmail.com>.



## Style guide

We use the [Tidyverse style guide](https://style.tidyverse.org/) for writing R code. Functions are documented with the [roxygen2](https://roxygen2.r-lib.org/articles/roxygen2.html) syntax. `quarto-template` uses the `lower_snake_case`.



## Commit messages

If you want to contribute by commiting changes, please try to use the [Conventional commits](https://www.conventionalcommits.org/en/v1.0.0/) specification.



## Asking questions

Before you ask a question, it is best to search for existing [Issues](https://github.com/biodiversitydata/quarto-template/issues) that might help you. In case you have found a suitable issue and still need clarification, you can write your question in this issue.

If you then still feel the need to ask a question and need clarification, we recommend the following:

- Open a new [Issue](https://github.com/biodiversitydata/quarto-template/issues/new).
- Use the template [other_issue.md](https://github.com/biodiversitydata/quarto-template/blob/main/.github/ISSUE_TEMPLATE/other_issue.md).
- Provide as much context as you can about what you're running into.
- Provide project and platform versions (paste the output of `sessionInfo()`).

We will then take care of the issue as soon as possible.



## Reporting bugs



### Before submitting a bug report

A good bug report shouldn't leave others needing to chase you up for more  information. Therefore, we ask you to investigate carefully, collect information and describe the issue in detail in your report. Please complete the following steps in advance to help us fix any potential bug as fast as possible.

- Make sure that you are using the latest version of `quarto-template`.
- Determine if your bug is really a bug and not an error on your side.
- To see if other users have experienced (and potentially already solved) the same issue you are having, check if there is not already a bug report existing for your bug or error in the [bug tracker](https://github.com/biodiversitydata/quarto-template/issues?q=label%3Abug).



### How do I submit a bug report?

We use [GitHub Issues](https://github.com/biodiversitydata/quarto-template/issues) to 
track bugs and errors. If you run into an issue with the project:

- Open a new [Issue](https://github.com/biodiversitydata/quarto-template/issues/new).
- Use the template [bug_report.md](https://github.com/biodiversitydata/quarto-template/blob/main/.github/ISSUE_TEMPLATE/bug_report.md).
- Explain the behavior you would expect and the actual behavior.
- Please provide as much context as possible and describe the 
*reproduction steps* that someone else can follow to recreate the issue on 
their own. This usually includes your code with a reproducible example.

We will then take care of the issue as soon as possible.



## Requesting features



### Before requesting a feature

- Make sure that you are using the latest version of `quarto-template`.
- Read the [documentation](https://github.com/biodiversitydata/quarto-template/) and the [wiki](https://github.com/biodiversitydata/quarto-template/wiki) carefully and find out if the functionality is already covered.
- Perform a [search](https://github.com/biodiversitydata/quarto-template/issues) to see if this enhancement has already been suggested. If it has, add a comment to the existing issue instead of opening a new one.



### How do I submit a feature request?

Feature requests are tracked as [GitHub Issues](https://github.com/biodiversitydata/quarto-template/issues).

- Open a new [Issue](https://github.com/biodiversitydata/quarto-template/issues/new).
- Use the template [feature_request.md](https://github.com/biodiversitydata/quarto-template/blob/main/.github/ISSUE_TEMPLATE/feature_request.md).
- Provide a clear and descriptive title for the issue to identify the suggestion.
- Provide a step-by-step description of the suggested enhancement in as many details as possible.
- Explain why this enhancement would be useful to most `quarto-template` users.

We will then take care of the issue as soon as possible.



## Contributing code

We use the [GitHub flow](https://docs.github.com/en/get-started/quickstart/github-flow) to collaborate on this project:


1. [Fork](https://docs.github.com/en/get-started/quickstart/contributing-to-projects) this repository using the GitHub interface.
1. [Clone](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository) your fork using `git clone fork-url` (replace `fork-url` by the URL of your fork). Alternatively, open RStudio IDE and create a New Project from Version Control.
1. Create a new branch w/ `git checkout -b branch-name` (replace `branch-name` by the name of your new branch).
1. Make your contribution.
1. Stage (`git add`) and commit (`git commit`) your changes as often as necessary
1. Push your changes to GitHub w/ `git push origin branch-name`.
3. Submit a [Pull Request](https://docs.github.com/en/get-started/quickstart/contributing-to-projects#making-a-pull-request) on the [original repo](https://github.com/biodiversitydata/quarto-template/compare).

We will then review the PR as soon as possible.


**Thanks for your contribution!**
