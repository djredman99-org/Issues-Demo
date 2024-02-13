[![CodeQL](https://github.com/djredman99-org/Issues-Demo/actions/workflows/codeql.yml/badge.svg)](https://github.com/djredman99-org/Issues-Demo/actions/workflows/codeql.yml)

# Issues-Demo

## Demonstrates how to use Issues to trigger automations

1. Add a new Issue and select the "Create Repo" Issue Template
2. Add your repo name to the form and create the issue

This will create a new repo, add a topic to the repo, and close the issue.

What this needs in place is:

1. An [Issue Template](https://github.com/djredman99-org/Issues-Demo/blob/main/.github/ISSUE_TEMPLATE/create_repo.yml) in a .github/ISSUE_TEMPLATE folder of the repo
2. A [workflow](https://github.com/djredman99-org/Issues-Demo/blob/main/.github/workflows/issueop.yml) that triggers on an issue being opened

Both of these items can be seen in this repo

## Demonstrates the ability to create issue forms

Issue Forms provides a convenient way to guide users through the issue creation process to capture pertinent data.

Additionally, you can prohibit the ability to create non-templated issues through the use of a issue [config](https://github.com/djredman99-org/Issues-Demo/blob/main/.github/ISSUE_TEMPLATE/config.yml) file as well as provide other helpful links/info.
