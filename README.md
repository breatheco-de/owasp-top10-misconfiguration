<!-- hide -->
# OWASP top 10 - Security Misconfiguration

> By [@rosinni](https://github.com/rosinni) and [other contributors](https://github.com/breatheco-de/configuring-firewall-and-acl-exercise-tutorial/graphs/contributors) at [4Geeks Academy](https://4geeksacademy.co/)

![last commit](https://img.shields.io/github/last-commit/breatheco-de/configuring-firewall-and-acl-exercise-tutorial)
[![build by developers](https://img.shields.io/badge/build_by-Developers-blue)](https://4geeks.com)
[![build by developers](https://img.shields.io/twitter/follow/4geeksacademy?style=social&logo=twitter)](https://twitter.com/4geeksacademy)

*Estas instrucciones [están disponibles en 🇪🇸 español](https://github.com/breatheco-de/configuring-firewall-and-acl-exercise-tutorial/blob/main/README.es.md) :es:*
<!-- endhide -->

## 📝 Instructions

In this activity, we will use the BeeBox virtual machine, which contains the vulnerable application bWAPP, to explore and exploit vulnerabilities included in the [OWASP Top 10](https://owasp.org/www-project-top-ten/). We will focus on the **Security Misconfiguration (A05:2021)** vulnerability, demonstrating how **Local File Inclusion (LFI)** can be exploited in this context.

**Local File Inclusion (LFI)**

Through this exploitation, we will demonstrate how incorrect configuration can allow an attacker to access sensitive local files on the server, revealing confidential information.


<!-- hide -->
### Before you start...

> We need you! These exercises are built and maintained in collaboration with contributors like yourself. If you find any bugs or misspellings, please contribute and/or report them.
<!-- endhide -->

## 🌱 How to start a project?

Clone this repository in your debian virtual machine ([how to clone this repository](https://4geeks.com/how-to/github-clone-repository)) and follow the steps below:

1. Install LearnPack, the package manager for learning tutorials and the node compiler plugin for learnpack, make sure you also have node.js 14:

```bash
$ npm i @learnpack/learnpack -g
```

2. Start the tutorial/exercises by running the following command at the same level where your learn.json file is:

```bash
$ learnpack start
```

<!-- hide -->
## Contributors

Thanks goes to these wonderful people ([emoji key](https://github.com/kentcdodds/all-contributors#emoji-key)):

1. [Rosinni Rodriguez (rosinni)](https://github.com/rosinni) contribution: (build-tutorial) ✅, (documentation) 📖
  
2. [Alejandro Sanchez (alesanchezr)](https://github.com/alesanchezr),  contribution: (bug reports) 🐛


This project follows the [all-contributors](https://github.com/kentcdodds/all-contributors) specification. Contributions of any kind are welcome!

This and many other exercises are built by students as part of the 4Geeks Academy [Coding Bootcamp](https://4geeksacademy.com/us/coding-bootcamp) by [Alejandro Sánchez](https://twitter.com/alesanchezr) and many other contributors. Find out more about our [Full Stack Developer Course](https://4geeksacademy.com/us/coding-bootcamps/part-time-full-stack-developer), and  [Data Science Bootcamp](https://4geeksacademy.com/us/coding-bootcamps/datascience-machine-learning).You can alse deepdive in the world of cybersecurity with our [Cybersecurity Bootcamp](https://4geeksacademy.com/us/coding-bootcamps/cybersecurity)
<!-- endhide -->