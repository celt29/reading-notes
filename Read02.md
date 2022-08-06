
## Command line notes

Command -> command line argument (The first is called an option, usually starts with a dash) -> command line arguments.

**Shortcut**: Use the arrow keys to go through already typed commands. Use side arrows to customize them.

pwd: print working directory  
ls: list. Can be used not just by itself.  
Cd: Change directory. Cd by itself brings back to home directory (but not root directory?). Usually done with one CLA.
Cd .. : Go up one level in the file tree.  
~: Shortcut for the home directory. Can use it instead of writing out the path.  
. : Refers to my current directory. More on it later.  
.. : Refers to the directory up one level aka parent directory.  

## Paths
**Absolute**: Specifies a location (file or directory) in relation to the root directory. Always begins with a (/)  
**Relative**: Specifies a location (file or directory) in relation to where I am currently are in the system. Doesn't begin with a (/).  


## Choosing a text editor
There are a bunch of different text editors. All computers come with some sort of one. Mostly they're bare bones and not as well suited as 3rd party ones. 3rd party code specific editors come with handy features that make code writting more efficient. They're updated a lot with newer features but mostly when it comes down to it, selecting one is mostly personal preference.

## About files  

Everything in Linux is a file.

Linux is case sensitive (for literally everything) where as windows isn't.

There are no extensions in Linux like .exe .jpg etc. Linux identifies the file by looking inside and doesn't use extensions to indentify files. There's a command called `file` that I can use to identify what the file actually is.

Spaces: So I can't space two words apart and think Linux will know which is which it won't. So if I cd to something the first CLA will be used even tho the directory I wanna go to is two words. The way to around this is by using quotes. Either single or double quotes. I do that and it's a package deal.

Escape Characters: The blackslash \ is such a character. It nullifies the special meaning of the next character. In the the tutorial they used Holiday Photos where normal Holiday Photos would be two seperate CLA's but with backslash after Holiday\ Photos it removes that space and it becomes Holiday Photos as a package in the eyes of the computer. SHORTCUT: if I do tab before I type the space between words the tab will complete what I want to say and automaically escape that space without me having to use the \.

Hidden files: To hide a file I just need to start the name with a period (.) or rename it later with a (.). Like .file.txt vs file.txt (even tho were not using extensions.
