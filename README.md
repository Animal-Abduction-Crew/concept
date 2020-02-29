# AAR - Software concept

[![GitHub Workflow Status (branch)](https://img.shields.io/github/workflow/status/Animal-Abduction-Crew/concept/CI/master)](https://github.com/Animal-Abduction-Crew/concept/actions) [![GitHub](https://img.shields.io/github/license/Animal-Abduction-Crew/concept)](https://github.com/Animal-Abduction-Crew/concept/blob/master/LICENSE)

## Read the concept

You can find the latest version of the concept as PDF file in [the release section of this repository](https://github.com/Animal-Abduction-Crew/concept/releases).

## Contribute

### Setup

1. Install [docker](https://docs.docker.com/get-started/#download-and-install-docker-desktop) and [docker-compose](https://docs.docker.com/compose/install/).
2. Pull the image specified in `.devcontainer.json` (e.g. `docker pull skyfrk/udhbwvst:4.5.2`).
3. Install [VSCode](https://code.visualstudio.com/).
4. Install the [VSCode Remote Development Extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack).
5. Clone this repository `git clone https://github.com/Animal-Abduction-Crew/concept.git`.
6. Open the cloned folder in VSCode and then reopen it in the development container.

### Build

Open the command palette and run `LaTeX Workshop: Build LaTeX Project`.

### Add a section

1. Create a feature branch (e.g. `git checkout -b feature/yolo_section`).
2. Write some lines! If you want to add an image add it in the `src/content/assets` folder.
3. Commit and push your changes to GitHub.
4. Submit a new [pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests) to merge your changes to the `master` branch.
5. Repeat!