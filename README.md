# Private Recipes Manager

![Forked Repository](https://img.shields.io/badge/status-fork-blue)
![GitHub License](https://img.shields.io/github/license/madcat34/private-recipes-manager?color=red)

> [!IMPORTANT]
> This project is a fork of the original **[symfony-tools/recipes-checker](https://github.com/symfony-tools/recipes-checker)** tool.

## Description

Private Recipes Manager is a tool designed to help manage and validate recipes for private bundles.

It extends the capabilities of the original recipes-checker by adding support
for multiple CI/CD platforms and private package registries.

## Key Features

- ✅ Support for GitHub, GitLab, and Bitbucket repositories
- ✅ Integration with private package registries such as :
    - Satis
    - Private Packagist
    - JFrog Artifactory,
    - GitLab Package Registry,
    - GitHub Package Registry
- ✅ Commands for linting and validating recipe manifests

## Differences from Original

This fork removes the support for public and contributed recipes, focusing solely on private recipes management.
It also introduces enhancements for better integration with private registries.

- ✅ Removed official and contributed recipes support

---

## 🙏 Acknowledgments

Special thanks to **Fabien Potencier** and **all contributors** to the original [symfony-tools/recipes-checker](https://github.com/symfony-tools/recipes-checker) project

---

**© 2025 MadCat34 | Licensed under [AGPL v3](LICENSE)**
