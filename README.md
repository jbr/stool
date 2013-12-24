# Stool

Stool: Because the world doesn't have enough build tools.

Stool is similar to make, cake, jake, and grunt, but is written in
sibilant. Stool looks for a stool.sibilant file in the root directory
of a project.

Stool files contain build instructions and dependencies for build
steps.

Stool can either be executed as: `$ stool build test` (where `build`
and `test` are stool tasks) or `$ ./stool.sibilant build test`.

To install the stool command on your path, `npm install stool -g`. To
install inside of a project, declare a devDependency on stool.
