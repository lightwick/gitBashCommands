# gitBashCommands
Quick summary of basic git bash commands; a refresher for when I come back from military service

## Ininitialization
**git init** - Initialization

**git remote add &lt;address&gt;** - adds remote access

## Remote to Local
**clone** - When downloading for the first time, in a new environment; e.g. different folder

**fetch** - Download Remote to local

**merge** - On master, merge the 

**pull** - **fetch** + **merge** 

## Branches
**git branch &lt;Branch Name&gt;** - creates a branch by the set name

**git checkout -b &lt;Branch Name&gt;** - changes to branch; the **-b** creates a new branch

**git stash** - stashes changes made

**git stash apply** - applies the stashed change

## etc
**git add &lt;file/folder name&gt;** - self explanatory

**git commit -a -m '&lt;commit message&gt;'** - -a skips staging process, -m is for adding commit message before the bash requests it; newly created files/folders are not tracked, ergo they must be added manually using "git add &lt;file/folder name&gt;"

**push** - Push the committed changes to remote repository

**git reset --hard origin/master** - reverts back to previously fetched version

## non git related
**rm &lt;file&gt;** - removes file

**touch &lt;file&gt;** - creates file in current directory

**mv &lt;file&gt; &lt;destination directory&gt;** - moves 'file' to designated directory

###current questions
1. reverting back to old version
2. where to write version of code