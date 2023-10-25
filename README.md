Making human readable github files
================

- [Make a repo](#make-a-repo)
- [Make your first RMD file](#make-your-first-rmd-file)
- [Push changes to github](#push-changes-to-github)

This document shows how I made this github repository.

## Make a repo

> - Initialize a new github repository
> - Clone the github repository

``` bash
cd /aryeelab/users/corri/Oct24_Presentation/ # directory I want to clone the github into
git clone https://github.com/corriene-sept/Aryee_LM_Oct24_2023.git # clone the repository
cd Aryee_LM_Oct24_2023
```

## Make your first RMD file

*First make a directory to put your figures in*

``` bash
cd /aryeelab/users/corri/Oct24_Presentation/
mkdir Figures # going to store figures here
pwd
```

**Make the RMD file and knit it before pushing the changes to github**

## Push changes to github

``` bash
cd /aryeelab/users/corri/Oct24_Presentation/Aryee_LM_Oct24_2023
ls # Example_RMD.md  Example_RMD.Rmd  Figures  README.md

git add .
git commit -m "Add files"

# check that commit was successful
#git log
git cherry -v

git branch
git pull https://github.com/corriene-sept/Aryee_LM_Oct24_2023.git main
git push https://github.com/corriene-sept/Aryee_LM_Oct24_2023.git main
```
