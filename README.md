# Private Recipes Manager

![Forked Repository](https://img.shields.io/badge/status-fork-blue)
![GitHub License](https://img.shields.io/github/license/madcat34/private-recipes-manager?color=red)

## 🔄 About this fork

> [!IMPORTANT]
> This project is an **independant fork** of the original **[symfony-tools/recipes-checker](https://github.com/symfony-tools/recipes-checker)** tool,
> redesigned to meet specific needs not covered by the original project: **managing private recipes**.

### 🎯 Purpose of the fork

While `symfony-tools/recipes-checker` is exclusively dedicated to validating public Symfony recipes
([symfony/recipes](https://github.com/symfony/recipes) and [symfony/recipes-contrib](https://github.com/symfony/recipes-contrib)),
**this fork aims to create a generic tool** for managing **private recipes** in **enterprise environments**.

### ✨ Key differences from the original project

| Aspect                 | Original project              | This fork                                                   |
|------------------------|-------------------------------|-------------------------------------------------------------|
| **Scope**              | Symfony public recipes only   | Private enterprise recipes                                  |
| **CI/CD platforms**    | GitHub Actions only           | GitHub, GitLab (SaaS + self-hosted), BitBucket              |
| **Package registries** | Public Packagist only         | Packagist, Satis, JFrog Artifactory, GitLab/GitHub Packages |
| **Authentication**     | Not applicable (public)       | Auth for private registries                                 |
| **Configuration**      | Hardcoded for symfony/recipes | A `.json` file customisable per project                     |
| **Licence validation** | Enforced (MIT)                | Can be enabled/disabled as needed                           |
| **Distribution**       | Composer package only         | Composer package, PHAR, Docker                              |

### 🚀 Use cases

This fork is particularly suitable if you:

- Develop **private bundles** for your organization
- Host your packages on **private registries** (Satis, Artifactory, etc.)
- Use **self-hosted GitLab** or **BitBucket** for your CI/CD
- Need **customizable validation workflows** for your recipes
- Want **validation rules specific** to your business context

### 📋 Project status

This project is undergoing a complete overhaul.

### 🤝 Relationship with the original project

This fork **does not compete** with the original project. The two projects have complementary objectives:

- **symfony-tools/recipes-checker**: Maintaining the quality of public Symfony recipes (official and contributed)
- **This fork**: Managing private recipes within companies

No upstream merge is planned at the moment, as the architectures differ fundamentally (public vs. private).
---

## 📜 Licence and credits

This project retains the [AGPL v3 license](LICENSE) of the original project.

## 🙏 Acknowledgments

A huge thank you to **Fabien Potencier** and the team at [`symfony-tools/recipes-checker`](https://github.com/symfony-tools/recipes-checker)
for creating the solid foundation on which this fork is based.

---

**© 2025 MadCat34 | Licensed under [AGPL v3](LICENSE)**
