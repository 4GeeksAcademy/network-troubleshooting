# VirtualBox Interactive Tutorial

<!-- hide -->
<a href="https://www.4geeksacademy.co"><img height="280" align="right" src="https://github.com/4GeeksAcademy/installing-windows-on-virtual-machine/blob/master/js-bg-badge.png"></a>

> By [@arnaldoperez](https://github.com/arnaldoperez) and [other contributors](https://github.com/4GeeksAcademy/installing-windows-on-virtual-machine/graphs/contributors) at [4Geeks Academy](https://4geeksacademy.co/)

![last commit](https://img.shields.io/github/last-commit/4geeksacademy/installing-windows-on-virtual-machine)
[![build by developers](https://img.shields.io/badge/build_by-Developers-blue)](https://4geeks.com)
[![build by developers](https://img.shields.io/twitter/follow/4geeksacademy?style=social&logo=twitter)](https://twitter.com/4geeksacademy)

*Estas instrucciones [están disponibles en 🇪🇸 español](https://github.com/4GeeksAcademy/installing-windows-on-virtual-machine/blob/main/README.es.md) :es:*
<!-- endhide -->

In this scenario you'll act as the person in charge of the network in a 4Geeks Academy campus. You must complete the configurations needed in order to get the network up and running, and also implement security policies to guarantee the correct use of the internal services in the network.

This practice covers the following subjects:

1. IP Adresses
2. Setting up a DHCP server
3. Setting up a DNS server
4. WiFi networks
5. Access control list (ACL)

<!-- hide -->
## Before you start... some related tutorials:

> We need you! These exercises are built and maintained in collaboration with contributors such as yourself. If you find any bugs or misspellings please contribute and/or report them.

## One click installation (recommended):

You can open these exercises in just a few seconds by clicking: [Open in Codespaces](https://codespaces.new/?repo=4GeeksAcademy/installing-windows-on-virtual-machine) (recommended) or [Open in Gitpod](https://gitpod.io#https://github.com/4GeeksAcademy/installing-windows-on-virtual-machine.git).

> Once you have VSCode open the LearnPack exercises should start automatically. If exercises don't run automatically, you can try typing on your terminal: `$ learnpack start`

## Local Installation

Clone this repository in your local environment ([Clone this repository](https://4geeks.com/how-to/github-clone-repository)) and follow the steps below:

1. Install LearnPack, the package manager for learning tutorials and the node compiler plugin for learnpack, make sure you also have node.js 14:

```bash
$ npm i @learnpack/learnpack -g
$ learnpack plugins:install learnpack-node
```

2. Start the tutorial/exercises by running the following command at the same level where your learn.json file is:

```bash
$ npm i jest@24.8.0 -g
$ learnpack start
```

<!-- endhide -->

## How are the exercises organized?

Each exercise contains the following files:

1. **README.md:** contains exercise instructions.
2. **test.js:** contains the testing script for the exercise (you don't have to open this file).
3. **app.js:** ignore this file.

## Contributors

Thanks goes to these wonderful people ([emoji key](https://github.com/kentcdodds/all-contributors#emoji-key)):

1. [Arnaldo Perez (arnaloperez)](https://github.com/arnaloperez) contribution: (build-tutorial) ✅, (documentation) 📖
  
2. [Alejandro Sanchez (alesanchezr)](https://github.com/alesanchezr),  contribution: (bug reports) 🐛

3. [Lorena Gubaira (lorenagubaira)](https://github.com/lorenagubaira), contribution: (bug reports) 🐛, contribution: (coder), (translation) 🌎

This project follows the [all-contributors](https://github.com/kentcdodds/all-contributors) specification. Contributions of any kind are welcome!

This and many other exercises are built by students as part of the 4Geeks Academy [Coding Bootcamp](https://4geeksacademy.com/us/coding-bootcamp) by [Alejandro Sánchez](https://twitter.com/alesanchezr) and many other contributors. Find out more about our [Full Stack Developer Course](https://4geeksacademy.com/us/coding-bootcamps/part-time-full-stack-developer), and  [Data Science Bootcamp](https://4geeksacademy.com/us/coding-bootcamps/datascience-machine-learning).