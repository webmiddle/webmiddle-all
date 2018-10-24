# webmiddle-all
Submodules container for all the webmiddle repositories

## Installing

```sh
git clone --recurse-submodules https://github.com/webmiddle/webmiddle-all.git
cd webmiddle-all
git submodule foreach --recursive git checkout master

cd webmiddle.org/webmiddle.github.io
git checkout develop
cd -
```
