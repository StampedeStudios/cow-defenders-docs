# Stampede Studios Documentation
This repository contains the documentation for the Stampede Studios games. It's generated with [Antora](https://antora.org/) and hosted on [GitHub Pages](https://pages.github.com/).

## Pipeline
Whenever a commit is pushed to the `master` branch, or the workflow is manually triggered, the following steps are executed:

1. The `antora-playbook.yml` file is used to generate the documentation using every source defined and the UI defined in the `assets/ui-bundle.zip` file.
2. The generated documentation is pushed to the `gh-pages` branch.
3. The `gh-pages` branch is used to host the documentation on GitHub Pages.
4. The `gh-pages` branch is used to host the documentation on [stampedestudios.github.io](https://stampedestudios.github.io/).

## UI
The documentation UI is based on the [Antora Default UI](https://gitlab.com/antora/antora-ui-default). It's modified to fit the Stampede Studios style.
