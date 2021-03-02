# cppm-packages
Official package tree for the cppm package manager. cppm stands for charpointer package manager.

`testing-branch` is the unstable, testing branch. Packages submitted here are not guaranteed to work
and should be avoided if possible.

To add the unstable testing branch to cppm, run `cppm vimirrors` and edit `mirrorlist` to have the following
```
# Mirror list for cppm
...
# Unstable mirror for cppm
https://github.com/cppm-package-manager/packages/tree/main/testing-branch unstable x86_64
```