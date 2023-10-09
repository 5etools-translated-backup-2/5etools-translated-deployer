# Purpose

The single purpose of the repository is to serve as a template to create a language specific deployment repo for the [5etoolstranslated](https://github.com/5etoolstranslated/5etoolstranslated.github.io) repository

# Deploy another website in another lang on Github Pages

First check if is not already done by myself or someone else.

- Use this template repo to create a repository named: `$lang`
- In the repo Settings > Secrets and variables > Actions
   -  Add a secret `PERSONAL_TOKEN` with the personal token for `5etooltranslated`
   -  Add a variable `DEPLOYMENT_LANGUAGE` with the main lang wanted for the content site
- In the repo Settins > Pages check that the source is Github Actions
- Wait or run the deploy workflow