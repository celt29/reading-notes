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
4. 
