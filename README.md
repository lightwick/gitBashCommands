# gitBashCommands
Quick summary of basic git bash commands; a refresher for when I come back from military service

## Ininitialization
**git init** - Initialization

**git remote add $<$address$>$** - adds remote access

## Remote to Local
**clone** - When downloading for the first time, in a new environment; e.g. different folder

**fetch** - Download Remote to local

**merge** - On master, merge the 

**pull** - **fetch** + **merge** 


## etc
**git add $<$file/folder name$>$** - self explanatory

**git commit -a -m '$<$commit message$>$'** - -a skips staging process, -m is for adding commit message before the bash requests it; newly created files/folders are not tracked, ergo they must be added manually using "git add $<$file/folder name$>$"

**push** - Push the committed changes to remote repository

## non git related
**rm $<$file$>$** - removes file

**touch $<$file$>$** - creates file in current directory

**mv $<$file$>$ $<$destination directory$>$** - moves 'file' to designated directory
