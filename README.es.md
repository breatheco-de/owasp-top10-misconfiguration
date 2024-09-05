<!-- hide -->
# OWASP top 10 - Security Misconfiguration

> By [@rosinni](https://github.com/rosinni) and [other contributors](https://github.com/breatheco-de/configuring-firewall-and-acl-exercise-tutorial/graphs/contributors) at [4Geeks Academy](https://4geeksacademy.co/)

![last commit](https://img.shields.io/github/last-commit/breatheco-de/configuring-firewall-and-acl-exercise-tutorial)
[![build by developers](https://img.shields.io/badge/build_by-Developers-blue)](https://4geeks.com)
[![build by developers](https://img.shields.io/twitter/follow/4geeksacademy?style=social&logo=twitter)](https://twitter.com/4geeksacademy)

*These instructions are [available in english](https://github.com/breatheco-de/configuring-firewall-and-acl-exercise-tutorial/blob/main/README.md)*
<!-- endhide -->

## 📝 Instrucciones

En esta actividad, utilizaremos la máquina virtual BeeBox, que contiene la aplicación vulnerable bWAPP, para explorar y explotar vulnerabilidades incluidas en el [OWASP Top 10](https://owasp.org/www-project-top-ten/). Nos centraremos en la vulnerabilidad **Security Misconfiguration (A05:2021)**, demostrando cómo se puede explotar **Local File Inclusion (LFI)** en este contexto.

**Local File Inclusion (LFI)**
A través de esta explotación demostraremos cómo una configuración incorrecta puede permitir a un atacante acceder a archivos locales sensibles del servidor, revelando información confidencial.



### Antes de empezar...

> ¡Te necesitamos! Estos ejercicios se crean y mantienen en colaboración con personas como tú. Si encuentras algún error o falta de ortografía, contribuye y/o repórtalo.

<!-- endhide -->

## 🌱 ¿Cómo empezar este proyecto?

Clona este repositorio dentro de tu maquina virtual debian y sigue los siguientes pasos:

1. Instale LearnPack, el administrador de paquetes para tutoriales de aprendizaje y el complemento del compilador de nodos para learnpack, asegúrese de tener también node.js 14:

```bash
$ npm i @learnpack/learnpack -g
```

2. Inicializa el tutorial/ejercicios ejecutando el siguiente comando en el mismo nivel donde se encuentra tu archivo learn.json:

```bash
$ learnpack start
```

<!-- hide -->

## Colaboradores

Gracias a estas personas maravillosas ([emoji key](https://github.com/kentcdodds/all-contributors#emoji-key)):

1. [Rosinni Rodriguez (rosinni)](https://github.com/rosinni) contribution: (build-tutorial) ✅, (documentation) 📖
  
2. [Alejandro Sanchez (alesanchezr)](https://github.com/alesanchezr),  contribution: (bug reports) 🐛

Este proyecto sigue la especificación [all-contributors](https://github.com/kentcdodds/all-contributors). ¡Todas las contribuciones son bienvenidas!

Este y otros ejercicios son usados para [aprender a programar](https://4geeksacademy.com/es/aprender-a-programar/aprender-a-programar-desde-cero) por parte de los alumnos de 4Geeks Academy [Coding Bootcamp](https://4geeksacademy.com/us/coding-bootcamp) realizado por [Alejandro Sánchez](https://twitter.com/alesanchezr) y muchos otros contribuyentes. Conoce más sobre nuestros [Cursos de Programación](https://4geeksacademy.com/es/curso-de-programacion-desde-cero?lang=es) para convertirte en [Full Stack Developer](https://4geeksacademy.com/es/coding-bootcamps/desarrollador-full-stack/?lang=es), o nuestro [Data Science Bootcamp](https://4geeksacademy.com/es/coding-bootcamps/curso-datascience-machine-learning).Tambien puedes adentrarte al mundo de ciberseguridad con nuestro [Bootcamp de ciberseguridad](https://4geeksacademy.com/es/coding-bootcamps/curso-ciberseguridad).
<!-- endhide -->