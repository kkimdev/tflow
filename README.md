# tflow
tflow is a flexible task execution engine, and currently at the idea phase.

## motivation
We don't have any shortage of build systems, e.g., make, cmake, scons, bazel, ... .  However, developer's workflow is often more than just building the source code.  For example, what if we want to ensure that git submodules are up-to-date before build?  What if we want to package new build into a Docker image and run it automatically on every edit?

## References
- http://gittup.org/tup/
- https://github.com/apenwarr/redo
