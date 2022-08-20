
## Command line notes

Command -> command line argument (The first is called an option, usually starts with a dash) -> command line arguments.

**Shortcut**: Use the arrow keys to go through already typed commands. Use side arrows to customize them.

`pwd`: **print working directory**  
`ls`: **list**. Can be used in conjunction with other code.  
`cd`: **Change directory**. *Cd by itself brings me back to home directory.* Usually done with one CLA.  
`cd` .. : **Go up one level in the file tree.**  
`~`: **Shortcut for the home directory**. Can use it instead of writing out the path.  
`.` : **Refers to my current directory**. More on it later.  
`..` : **Refers to the directory up one level aka parent directory.**  
`file`: **Identifies the type of file.**  
`ls -a`: **Reveals all hidden folders and files.**  

[Cheat Sheet](https://www.guru99.com/linux-commands-cheat-sheet.html)

## Paths
**Absolute**: Specifies a location (file or directory) in relation to the root directory. Always begins with a (/).  

**Relative**: Specifies a location (file or directory) in relation to where I am currently are in the system. Doesn't begin with a (/).  


## Choosing a text editor  
All computers come with some sort of text editor. Mostly they're bare bones and lack a lot of features that make code writing easy and efficient. Code specific editors (made by 3rd parties) come with handy features that make code writing more efficient. These features include code completion, syntax highlighting, a variety of themes and a healthy selection of extensions. They're updated a lot with newer features but mostly when it comes down to it, selecting one is mostly personal preference. That said VS Code is usually what's recommended. 

## About files  

**Everything in Linux is a file.**  

**Linux is case sensitive** (for literally everything) where as windows isn't.

**There are no extensions in Linux** like, .exe, .jpg, etc. Linux identifies the file by looking inside and doesn't use extensions to identify files. There's a command called `file` that I can use to identify what the file actually is.

**Spaces:** I can't space two words apart and think Linux will know which is which, it won't. So if I cd to something only the first CLA will be used even though the directory I wanna go to is two words. The way to around this is by using quotes. Either single or double quotes. I do that and it's a package deal.

**Escape Characters:** The backslash \ is such a character. It nullifies the special meaning of the next character. In the the tutorial they used Holiday Photos where normal Holiday Photos would be two separate CLA's but with backslash after Holiday\ Photos it removes that space and it becomes Holiday Photos as a package in the eyes of the computer. SHORTCUT: if I do tab before I type the space between words the tab will complete what I want to say and automatically escape that space without me having to use the \.

**Hidden files:** To hide a file I just need to start the name with a period (.) or rename it later with a (.). Like .file.txt vs file.txt (even though were not using extensions. To show all files including hidden files and directories use `ls -a`.
