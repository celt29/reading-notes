### Setting the name and email that will be used with every git commit

`git config --global user.name "preferred name"`  

`git config --global user.email "example@email.com"`  

To make sure I entered in the name and email correctly, enter each command and see what they return.

To check different git settings (which include the settings above) use the `git config --list` command.
 
 ### Getting Help with understanding commands
 
  If I'm unclear on a command there are 3 ways to get more information on it.
- `git help` (command)
- `git` (command) `--help`
- `man git-`(command)  

### Setting up a Git Repository (Repo)

If I want to convert/import an exisiting directory into Git I need to follow these steps.
1. `cd` into the target directory
2. Use `git init` (git is created but files are not yet tracked.)
3. (performs an initial commit.)
    1. `git add *.c`
    2. `git add LICENSE` 
    3. `git commit -m "whatever I want to say here"`  

### Cloning

`git clone https://github.com/test` which is the repository URL that I want to clone. This creates a directory called "test".  

`git clone https://github.com/test blank`
To have it make the clone directory inside of the "blank" directory.


### Local Repository Structure  
Working Directory: The actual files reside here.
Index: The area used for staging
Head: Points to the most recent commit

### Saving Changes

Tracked:  
Tracked files can be modified, unmodified, or staged; they were part of the most recent file snapshot.  

Untracked:  
Untracked files were not in the last snapshot and do not currently reside in the staging area.

*After cloning a repository, files have tracked status and are unmodified because they have been checked out but not edited.

1. Edit -> Git flags as modified.
2. I stage the modded file. 
3. Then I commit.

### Check File Status

To check the status of files use `git status`

