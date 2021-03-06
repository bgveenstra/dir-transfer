# dirTransfer

Transfer a directory  from one  repo to another, preserving commit history. Automates the process laid out at http://gbayer.com/development/moving-files-from-one-git-repository-to-another-preserving-history/.

# Setup

1. Add `dirTransfer.sh` to a directory of your choice.

1. Make it executable: `chmod 700 dirTransfer.sh`.

1. Recommend you run this file in a directory that is not a git repo. 

1. To run the script, `./dirTransfer.sh`.

# Sample Inputs

The script will ask for the source and destination repos and directories. Each directory path should be relative to the root folder of its repo. 

```
Clone url of source repo? -> 
    https://github.com/sf-wdi-22-23/modules-22.git
    
Source directory (relative path *inside* source repo)? -> 
    w02-working-with-objects/d3-dawn-forms
    
Clone url of destination repo? -> 
    https://github.com/bgveenstra/shared_modules.git
    
Destination directory (relative path *inside* destination repo)? -> 
    01-front-end-basics/json-and-html-string/22-23
```
