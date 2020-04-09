---
title: "Setting up Hugo Site"
date: 2020-03-18T12:13:35+05:30
description: "Getting starts with hugo site - the best online static site generator"
tags: ['hugo', 'hugo-theme']
---

Download the latest release
```
[link](https://github.com/gohugoio/hugo/releases)
```

```
sudo dpkg -i <downloaded  file name >
```

## Adding a new Project

```
hugo new site mdlDocs
```


## Instaling them for Hugo

git submodule add https://github.com/digitalcraftsman/hugo-minimalist-theme.git themes/hugo-minimalist-theme


## Copy config.toml 

Copy config.toml file's content into the top level project directory `config.toml` file


## Delete after adding content

```
# Remove this line if you use this theme for a real website.
# It allows you to preview the theme within the exampleSite folder
# with the hugo server command
themesDir = "../.."
```

## Preview the site locally

```
hugo server -D
```

## Adding a post

```
hugo new post/hello-world
```


## Build static site

```
hugo
```

