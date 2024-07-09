<h1 align="center">📋 copier-quasar-meta</h1>
<p align="center">
  <i><a href="https://github.com/copier-org/copier">Copier</a> meta template for <a href="https://github.com/quasarframework/quasar">quasar</a> projects.</i>
</p>


<!-- Place https://shields.io/ badges here -->
[![GitHub repo stars](https://img.shields.io/github/stars/worldworm/copier-quasar-meta)](https://github.com/worldworm/copier-quasar-meta)
[![License](https://img.shields.io/badge/license-MIT-green?logo=opensourceinitiative&logoColor=fff)](https://github.com/worldworm/copier-quasar-meta/blob/main/LICENSE)
[![GitHub last commit (main)](https://img.shields.io/github/last-commit/worldworm/copier-quasar-meta/main)](https://github.com/worldworm/copier-quasar-meta/commits/main/)
[![GitHub release](https://img.shields.io/github/v/release/worldworm/copier-quasar-meta)](https://github.com/worldworm/copier-quasar-meta/releases/latest)
[![GitHub commits since latest release](https://img.shields.io/github/commits-since/worldworm/copier-quasar-meta/latest/main)](https://github.com/worldworm/copier-quasar-meta/releases/latest)
[![Copier supported version](https://img.shields.io/badge/Copier-v9-blue)](https://github.com/copier-org/copier)


## Features
- 📦 [Quasar](https://github.com/quasarframework/quasar) setup
- 🔁 Continuous integration (CI) pipelines for Github Actions and GitLab CI/CD
- 🐳 Docker support with build and publish pipelines
- 🪝 [pre-commit](https://github.com/pre-commit/pre-commit) hooks
- 🔍 [ESLint](https://github.com/eslint/eslint) code linter
- 🆚 [VSCode](https://github.com/microsoft/vscode) configuration


## Requirements
First install copier:<br>
([from the official installation documentation](https://copier.readthedocs.io/en/stable/#installation))
```bash
pip install copier
```


## Usage
> [!NOTE]
> This is a [meta template](https://github.com/worldworm/copier-showcase/blob/main/types/meta.md) that cannot be used directly to create a project.
> The template resulting from this meta template can be used for this purpose: [copier-quasar](https://github.com/worldworm/copier-quasar)


Make sure the requirements are met, then:
```bash
copier copy "https://github.com/worldworm/copier-quasar-meta.git" .
```

### Update
To update a template after creating a project, run:
```bash
copier update -a .project/.copier-answers.quasar-meta.yml .
```


## Explore more Copier templates
In addition to this template, there are a number of other Copier templates available. For an overview of all available templates, visit the [Templates Showcase repository](https://github.com/worldworm/copier-showcase).

---
<p align="center">
  <i>© <a href="https://github.com/worldworm">worldworm</a> 2023-2024</i>
  <br><i>Licensed under <a href="https://github.com/worldworm/copier-quasar-meta/blob/main/LICENSE">MIT</a></i>
</p>
