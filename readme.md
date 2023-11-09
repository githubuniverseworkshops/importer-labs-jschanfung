# Overview
<h1 align="center">Migrate your CI/CD Pipelines  using GitHub Actions Importer</h1>
<h5 align="center">@facilitators</h3>

<p align="center">
  <a href="#mega-prerequisites">Prerequisites</a> •  
  <a href="#books-resources">Resources</a> •
  <a href="#learning-objectives">Learning Objectives</a>
</p>

## Who is this workshop for?

- **Who is this for**: GitHub users that are trying to convert workflows from their current CI/CD system/service to GitHub Actions using GitHub Actions Importer.
- **What you'll learn**: How to plan, forecast, automate the conversion of a users existing CI/CD workflows.
- **What you'll build**: An environment to use GitHub Actions importer to convert your workflows.

## Learning Objectives

In this workshop, you will:

  - Using Github Actions Importer on the command line in codespaces. Setting up the environment for a specific CI/CD service or tool to enable workflow conversion.
  - How to automatically convert CI/CD workflows from existing services/tools to GitHub Actions.
  - How to make custom transformers to convert existing environment variables and runners as well as leveraging marketplace actions.

## :mega: Prerequisites
Before joining the workshop, there are a few items that you will need to install or bring with you.
- GitHub Account

## :books: Resources
- [GitHub Actions Importer Repository and Documenation](https://github.com/github/gh-actions-importer)
- [Actions importer-labs repository](https://github.com/actions/importer-labs)

# GitHub Actions Importer labs

[GitHub Actions Importer](https://docs.github.com/en/actions/migrating-to-github-actions/automating-migration-with-github-actions-importer) helps plan, test, and automate the migration of Azure DevOps, CircleCI, GitLab, Jenkins, and Travis CI pipelines to GitHub Actions. This repository contains learning paths that teach you how to use GitHub Actions Importer and how to approach migrations to Actions.

## Choose your learning path

To get started:

1. Use the `githubuniverseworkshops/importer-labs` repository as a template to [generate](https://github.com/githubuniverseworkshops/importer-labs/generate) a new GitHub repository.
2. Choose where to start. There are currently learning paths for:
   - [Migrating from Azure DevOps to GitHub Actions](/azure_devops/readme.md)
   - [Migrating from CircleCI to GitHub Actions](/circle_ci/readme.md)
   - [Migrating from GitLab to GitHub Actions](/gitlab/readme.md)
   - [Migrating from Jenkins to GitHub Actions](/jenkins/readme.md)
   - [Migrating from Travis CI to GitHub Actions](/travis/readme.md)
3. Each learning path describes how to configure your codespace, bootstrap a CI/CD environment, and troubleshoot GitHub Actions Importer.
