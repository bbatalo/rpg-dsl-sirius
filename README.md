# RPGLang - Graphical Concrete Syntax

Concrete syntax for a DSL created for the purpose of designing talent trees and ability systems for role-playing video games. This project maps graphical representations to concepts specified in the abstract syntax. As the most user-oriented part of the DSL, the design of the syntax should be intuitive, so end users can easily grasp the basics of using this syntax for executing their day to day domain tasks.

This repo is part of a larger project, which contains the following:

* abstract syntax - this repo
* graphical concrete syntax - `https://github.com/bbatalo/rpg.design`
* code generator - `https://github.com/bbatalo/rpg.generator`
* example game engine - `https://github.com/bbatalo/rpg.engine`

Together, these provide the user with the ability to design talent trees and ability systems using the graphical syntax (diagrams), generate code that is runnable in the example game engine and test the validity of the build by playing the game!

## Motivation

The choice for the implementation of concrete syntax was between textual and graphical - and here graphical was choosen. Main reason was that the ability systems and talent trees are inherently graphical. Almost every talent tree is represented graphicaly as a tree, or a graph, containing linked nodes, with some textual notation here and there. It seems only natural to proceed with this choice, even though textual syntax possibly offers more flexibility for experienced users.

Main focus for the implementation of the concrete syntax is functionality. Users should be able to create games and their ability systems easily, without much pain in the process. AS this is primarily a tool for creative persons, limiting that creativity with low functionality and flexibility is detrimental.

Secondary is the design, the look-and-feel. While it is important for the syntax to look pretty, when forced to make a choice between function and design, most of the time the choice will be made in favour of function.

## Getting started

To start working on this project, it is required to clone the repo and setup the required Eclipse IDE with specified plugins. Also, a working version of RPGLang (abstract syntax) should be setup in the development environment, as the code generator project requires the metamodel created in abstract syntax.

### Prerequisites

* Eclipse IDE
* Eclipse Modeling Tools
* Eclipse Ecore Tools

For FTN students: provided Eclipse IDE installation (for DSL course) contains everything you need.

Also, clone and setup RPGLang as instructed in its README.md. Open that project in Eclipse and run it as Eclipse Application. This will open a new Eclipse process, only this time it will contain the metamodel as a plugin, which is essential. Import the code generator project in this runtime workspace and everything is set.

### Project structure

Todo.

### Usage

Todo.

## TODO