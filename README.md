# Little Qairoes Polymer Style Guide

_Still under construction_


## Purpose

_Opinionated Polymer style guide for teams by @tjmonsi, heavily inspired by [John Papa's Angular Style Guide](https://github.com/johnpapa/angular-styleguide/blob/master/a1/README.md)_

The purpose of this style guide is to provide guidance in building easy to understand and maintainable Polymer web app projects. These conventions are based on my development experience on Polymer and [Polymer patterns](https://github.com/PolymerLabs/polymer-patterns). You can take it as it is or modify it. If you have suggestions that would make this better, please feel free to make an issue above.

Many of my styles are influenced by patterns from Angular (from [John Papa's Angular Style Guide](https://github.com/johnpapa/angular-styleguide/blob/master/a1/README.md)) and React (from [Arunoda's Mantra Framework](https://github.com/kadirahq/mantra)). It is also heavily influenced by [Brad Frost's Atomic design](http://atomicdesign.bradfrost.com/table-of-contents/)


## Table of Contents
1. [Single Responsibility](#single-responsibility)
2. [Modules](#modules)
3. 


## Single Responsibility

### Rule of 1

- Define One (1) Polymer component per file, recommended to be less than 400 lines of code.

*Why?*: For easier testing.

*Why?*: Easier maintainability

### Small Methods

- Define methods, no more than 75 LOC (less is better)

*Why?*: Easier to read


## Modules

### Avoid Naming Collisions

- Use unique prefixes and then a one-to-two word description of the module

*Why?*: For avoiding namespace collision when using 3rd party polymer elements

*Why?*: Should you plan to publish your module, it will be easier to just use the same name

Example:
```
littleqairoes-core      // core components and behaviors to be used in the project
project-name-components // unique components to be used in the project 
```


## 











