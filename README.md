# tflow
tflow is a flexible task execution engine, and currently at the idea phase.

## Motivation
We don't have any shortage of build systems, e.g., make, cmake, scons, bazel, ... .  However, developer's workflow is often more than just building the source code.  For example, what if we want to ensure that git submodules are up-to-date before build?  What if we want to package new build into a Docker image and run it automatically on every edit?

## Requirements
- Each task has 3 parts: 1. listening event(s) 2. task command(s) 3. emiting event(s)
- Listening event should be configurable with custom scripts.
- Task commands are exec form or sh/bash/customm shell scripts

## Desired properties
- Easy and intuitive configuration
- Tup-like dependency verification?

## References
- http://gittup.org/tup/
- https://github.com/apenwarr/redo
- https://apenwarr.ca/log/20181113
