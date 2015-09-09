![App Specs](http://i.imgur.com/XNpkcKK.png)

A curated list of applications specifications for you practice new technologies, improve your portfolio and sharpen your skills.

## Table of Contets

1. [Motivation](#motivation)
1. [Purpose](#purpose)
1. [How it works](#how-it-works)
1. [How to collaborate](#how-to-collaborate)
1. [Contributors](#contributors)
1. [References](#references)

## Motivation

Build software is similar to build a house, it takes **careful planning** and **precise information architecture** before you can hammer that first nail, or, in this case, punch up that first string of code.

We always need to be clear about what we want to achieve. Otherwise, we'll never know if we reached our goals.

Specifications are very important for several reasons:

- Understanding project requirements
- Developing a project scope
- Estimating project time-frame and pricing
- Creating a workable reference for development and design

Furthermore, practicing **deliberately** by building **real projects** is the <strike>unique</strike> best way to achieve mastery in this field. With all these specs and other resources, you will be able to do it in a **smooth way**.

## Purpose

Our intention is to provide professional specifications that are agnostic, i.e, can be implemented using any programming language/stack.

Sometimes is difficulty to think in a cool project to implent with the intention to validade some idea or new skill. With **app-specs** you'll be able to find lots of awesome specs and their respective implementations!

## How it works

We divided the project into three categories:

- [Frontend](/frontend)
- [Backend](/backend)
- [Fullstack](/fullstack)

We simplified the division by offering just three categories, but each category will have more responsibilities:

- **Frontend**: will take care of the Design, HTML, CSS and JavaScript related to the client-side application. 

  **ps**: The Frontend Engineer should also try to deploy the application using GtiHub pages, for example. You need  that your app be available for a live demo!

- **Backend**: will take care of the server side application, database development, database administration and DevOps.

- **Fullstack**: will take care of the Frontend and Backend respective tasks.

Each category has three levels of difficulty, that are `beginner`, `intermediate` and `advanced`. Inside these *levels folders* you'll find the specifications for different projects.

In these specification files, you will see all the functionalities that are expected that your software has.

You should break these functionalities in sprints, using your preferred [agile methodology](https://en.wikipedia.org/wiki/Agile_software_development).

After finish your implementation, fork and send a pull request to us linking your resolution in the respective specification file, in the section *Implementations*.

We also highly recommend that you register your progress while developing the project, so after finish all implementations you can write an article to explain how you make your app.

**Imagine how much knowledge we can generate/share following all these steps!!!** :smile:

### Sum up

1. Choose and read the specification of a project that you want to implement. You should consider to start with a [MVP](https://en.wikipedia.org/wiki/Minimum_viable_product) (beginner) application, and after create other specification with more complex functionalities.
1. Plan your sprints based on the functionalities that your app must have.
1. Start to implement the functionalities.
1. Register your progress.
1. After completing the implementation, create an article explaining all the process.
1. Fork our repository and submit the link of your implementation and others relevant informations.

## How to collaborate

You can help us in **several ways**! Some suggestions:

- Create a **new** specification. Use our [spec model](models/spec-model.md).
- Create an application based on one of our specs. Use our [App README model](models/app-readme-model.md) as the README file of your project.
- Choose an existing specification and add **more functionalities** to it, making this more complex, replicating this specification in the *intermediate* or *advanced* folder.
- Choose a *frontend* spec and create its respective *backend* spec.
- Choose a *backend* spec and create its respective *frontend* spec.
- Choose a *backend* and *frontend* specs and create its respective *fullstack* spec.
- Translate a spec to your native language. All the translations should be created inside the `i18n` folder in the respective `category/level` folder. The name of the file should first contain the acronyms that refer to the target language, and after the original name of the app/file.
  - **Ex**: `backend/advanced/i18n/PT-BR-social-network.md`
- Suggest new ideas for the project on the [issues](https://github.com/ericdouglas/app-specs/issues).

## Contributors

[![Eric Douglas](https://secure.gravatar.com/avatar/7b4b31bf5e791b6d316462bfe6f943aa?s=130)](https://github.com/ericdouglas) |
:---:|
[Eric Douglas](https://github.com/ericdouglas) - Founder |

## References

1. [Project Specification Documents](http://www.pixelearth.net/pages/project-specification)
1. [7 Killer Tips to Creating a Website Specification Document](http://www.bluefountainmedia.com/blog/how-to-write-a-specifications-document/)
1. [Getting Real, Step 1: No Functional Spec](https://signalvnoise.com/archives/001050.php)
1. [Writing specifications for web applications](http://www.lionite.com/articles/read/233)
1. [TodoMVC](https://github.com/tastejs/todomvc)
1. [todomvc-app-template](https://github.com/tastejs/todomvc-app-template)
