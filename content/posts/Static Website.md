---
title: "Building a static website"
date: 2020-04-11T17:48:07+05:00
description: "Travel from beginer to master level via github"
tags: [github, training, tutorial]
---



## Adding time format to the new post

`YYYY-MM-DDThh:mm:ssZZZ`

### Remove module from .git folder

ls -a
cd .git
cd modules/
rm -rf mdl-docs/

### Git Pull with Submodule
For a repo with submodules, we can pull all submodules using
git submodule update --init --recursive

for the first time. All submodules will be pulled down locally.
To update submodules, we can use
```
git submodule update --recursive --remote
```

or simply
```
git pull --recurse-submodules
```


Pushing all submodules recursively

git1.7.11 ([ANNOUNCE] Git 1.7.11.rc1) mentions:
>"git push --recurse-submodules" learned to optionally look into the histories of submodules >bound to the superproject and push them out.
So you can use:

```
git push --recurse-submodules=on-demand
```

