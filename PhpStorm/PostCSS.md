---
title: File Watchers : PostCSS
---

## Pre-requirements

* Install nodeJS _([Nodejs website](https://nodejs.org/en/))_
* Install PostCSS with Autoprefixer _(`npm install -g postcss-cli autoprefixer`)_

CSS files autoprefixer settings.

## Paths:

| Path | Location |
| --- | --- |
| Input path : | `/public/css/*.css` |
| Output path : | `/public/css/*.dist.css` |

## File watcher settings

| Field | Value |
| --- | --- |
| **Name** | PostCSS - Autoprefixer |
| **File type** | Cascading style sheet |
| **Scope** | Project Files |
| **Program** | `postcss` |
| **Arguments** | `$FileName$ --use autoprefixer -o $ProjectFileDir$/public/css/$FileNameWithoutExtension$.dist.css` |
| **Output paths to refresh** | `$ProjectFileDir$/public/css/$FileNameWithoutExtension$.dist.css` |
| **Working directory** | `$FileDir$` |
