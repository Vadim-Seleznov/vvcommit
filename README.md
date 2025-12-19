## VVCOMMIT
(P.S IF SOMEONE IS USING THIS TOOL ALREADY, IM REALY SORRY:) CURRENTLY IM DOING EVERYTHING IN 1 BRANCH, so unstable versions
are in main branch. This is actually 0.0.1b version of tool, please, just wait until I do formal documentation and seperate dev and main branches,
thank you!)

# CURRENT
VERSION OF PROGRAM IS 0.0.1a and we got dev branch, so you can use this tool with stable version from main!

Simple console tool written fully in python. Thats kind of thing that makes daily workflow faster.

## TODO
1. Functionality to work with branches - BASIC IMPLEMENTATION
2. Functionality to solve some basic common github problems - NOT IMPLEMENTED
## USAGE
Just copy vvcommit.py into yours project dirrectory, then
``
  python ./vvcommit.py request commit_message
``

this program has different request so to get help with it just use:
``
  python ./vvcommit.py help
``

## EXAMPLE
Pushing changes into main branch with commit message = "small fix"
``
  python ./vvcommit.py cbranch "main" "small fix"
``

or if main its current branch:

``
  python ./vvcommit.py curr "small fix"
``

Of course we can pull things too

## INTRESTING FEATURES
This is program is actually updating itself.

for example
``
    python ./vvcommit.py update
``

this command will update file and create .bak file with older version
also if you dont want to get .bak file you can just:

``
    python ./vvcommit.py update --no-backup
``

this command will just update vvcommit.py

Also we can initialize github repo from scratch with only 1 command
to use this feature just copy vvcommit into yours project dir
then go to github and create new empty repo, and now you are good to go with:

``
  python ./vvcommit.py init "GITHUB-LOGIN-HERE" "REPO-NAME-HERE"
``
