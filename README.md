## VVCOMMIT
Simple console tool written fully in python. Thats kind of thing that makes daily workflow faster.
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
  python ./vvcommit.py branch "main" "small fix"
``

or if main its current branch:

``
  python ./vvcommit.py curr "small fix"
``

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
