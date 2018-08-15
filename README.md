# Project Maker

## Overview
This repository will allow you to create a skeleton project from the command line. When you start a new project, you start by creating your README.md, a licence and maybe a directory structure. To automate the pain away from doing this for every new project this project was created to boilerplate your directory structure depending on the language you choose. 

## User Journey
```
$ ./project python
OR
$./project go
OR
$./project terraform
```
Creates a file structure as follows:
```
/docs
/src
/bin
/deploy
.gitignore
LICENSE
README.md
requirements.txt
Dockerfile
```
## Language
Python 3