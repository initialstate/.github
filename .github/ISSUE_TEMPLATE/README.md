<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://theme.tekcloud.com/prod/github/is-logo-dark-mode.svg" width="250px">
  <source media="(prefers-color-scheme: light)" srcset="https://theme.tekcloud.com/prod/github/is-logo-light-mode.svg" width="250px">
  <img alt="IS Logo" src="https://theme.tekcloud.com/prod/github/is-logo-light-mode.svg" width="250px">
</picture>

# Issue Template Guide
![repo linter workflow](https://github.com/initialstate/best-practice-resources/actions/workflows/is-repo-lint.yml/badge.svg)
> [Link to Github docs](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/configuring-issue-templates-for-your-repository)

A brief explanation of issue templates and how to use them.

## Getting Started

If you want to make your own organization wide template, just create a yaml file in this directory that follows Githubs formatting guidelines. You can also use an [existing issue template](https://github.com/initialstate/.github/blob/master/.github/ISSUE_TEMPLATE/bug_report.yml) as a starting point.

## Usage

Issue templates made here will appear as options when creating an issue on any *public* repository.

## Repository Checklist

The `repo_checklist.yml` template is meant to be used as a way to create checklists on newly created repositories when setting them up. Any new workflows/requirements should be added to that checklist.
