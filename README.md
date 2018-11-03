# booster-project-hello-world

This repository is part of the [RCOS Open Source Curriculum Project](https://github.com/codingandcommunity/rcos-open-source-curriculum-project). View that repository for additional documentation for the entire system.

This repository contains the booster-specific curriculum steps for a Hello World project.

The Booster Atom plugin "Fast-Forwards" a student froms stage to stage so that they can learn important programming concepts without writing boilerplate code.

This repository is not meant to stand alone. It is consumed by the Booster plugin and referenced by the Booster API.

## Getting Started

1. Clone the GitHub repository
1. Start editing the code

Since the Atom plugin pulls each stage of this repository sequentially into students' proejcts, we hopefully won't have any direct dependencies in this project.

As a result, there is no `package.json` or need to run `yarn install`.

## Formatting

This isn't a standard repository. It must be formatted in a very specific way for consumption by the Atom plugin. Each *stage* is stored in a folder with sequential numbering (e.g. `stage01`). When a student first starts a project, `stage01` is copied into their project directory, and they can play with the example code there. When the user "fast-forwards", the plugin stores certain sections of the student's code, deletes the contents of the directory, copies the next stage into the project directory, and re-inserts some sections of the student's code.

For more details on how this process works, see the Atom plugin repository.

More documentation will be added here as the actual formatting is finalized.
