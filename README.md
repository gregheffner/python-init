<div align="center">
    <h1>New Script Setup</h1>

![macOS](https://img.shields.io/badge/mac%20os-000000?style=for-the-badge&logo=macos&logoColor=F0F0F0)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Sublime Text](https://img.shields.io/badge/sublime_text-%23575757.svg?style=for-the-badge&logo=sublime-text&logoColor=important)

</div>

# Cookie Cut

This project contains a Cookiecutter template that helps you create new Python 3.6+ package projects by automatically generating most of the boiler plate content for you.

Cookiecutter is a command-line utility that creates projects from templates. Cookiecutter lets you to easily and quickly bootstrap a new project from a template which allows you to skip all manual setup and common mistakes when starting a new project.

Cookiecutter takes a source directory tree and copies it into your new project. It replaces all the names that it finds surrounded by templating tags {{ and }} with names that it finds in the file cookiecutter.json.

## Getting Started

1. Install Cookiecutter if you don't have it.

```bash
brew install Cookiecutter
```

1. Use Cookiecutter to generate python project using template.

```bash
cookiecutter https://github.com/gregheffner/python-init.git
```

1. Move into the project directory and make a virtual environment.

```bash
cd new-project
mkvenv
```
