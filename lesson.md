# Lesson specific things

Link to the etherpad is: http://pad.software-carpentry.org/2018-04-23-umich

Link to the course site is: https://umswc.github.io/2018-04-23-umich/

Link to the data that will be used: https://github.com/swcarpentry/shell-novice/blob/gh-pages/data/data-shell.zip
  * Instructions on how to obtain the data file:
    * Use link and hit the download button on the right (do not seem to need a GitHub ID to do this).
    
# Useful Resources

A site that will breakdown any shell command: https://explainshell.com/

A site that will check scripts for spelling errors: http://www.shellcheck.net

## Introducing the Shell

Link to lesson is [here](http://swcarpentry.github.io/shell-novice/01-intro/)

* Make sure to optimize space by running the command `PS1='$ `. 
* What does a computer do?
* What is a GUI?
* The REPL acronym: Read, Evaluate, Print, Loop
* Set the stage for our lesson (i.e. we are all Nelle)


## Navigating Files and Directories

Before getting started need to go over the general layout of the filesystem in the UNIX environment. The link to the lesson can be found [here](http://swcarpentry.github.io/shell-novice/02-filedir/).

![](http://swcarpentry.github.io/shell-novice/fig/filesystem.svg)

![](http://swcarpentry.github.io/shell-novice/fig/home-directories.svg)

**Key points to hit in this lesson include:**

* General structure and overview
* Absolute path
* Relative path

Need to point out that the file system if using Git Bash may be slightly different than what they are used to.
i.e. my path to the desktop is: `/mnt/c/Users/marc/Desktop`
 * so my `home` directory is in the `root` directory that also has `mnt`, `root`, `opt`, etc.
  * `mnt` commonly is used for mounted drives (e.g. `c` in this case)
  
## Working with Files and Directories

The link to this lesson can be found [here](http://swcarpentry.github.io/shell-novice/03-create/).

**Key points to hit in this lesson include:**

* Good file naming practices
  * If you do have spaces then you will need to use `""`.
* Go over what nano is and other text editors (e.g. notepad, notepad++, sublime, atom, vim, emacs, etc.)
  * When in nano go over that `^` is short for the `ctrl` command
* Deleting is forever
* The up arrow and tab key shortcuts

**Key functions:** `ls`, `cd`, `mkdir`, `pwd`, `nano`, `rm`, `mv`, `cp`

## Pipes and Filters:

The link to the lesson can be found [here](http://swcarpentry.github.io/shell-novice/04-pipefilter/).

![](http://swcarpentry.github.io/shell-novice/fig/redirects-and-pipes.png)


**Key points to hit in this lesson include:**

* The use of wildcards (e.g. `*`, `?`)
* The use of pipes `|`
 * The modularity that this allows. Make simple things that together can do complex things.
* Intro to wildcard expressions (skip if time is short)


**Key functions:** `wc`, `>`, `cat`, `less`, `sort`, `head`, `>>`, `|`, `<`, `uniq`

## Loops:

The link to this lesson is found [here](http://swcarpentry.github.io/shell-novice/05-loop/).

**Key points to hit in this lesson include:**

* A `for loop` in the bash shell
 * what the `>` means when writing a loop on the command line
* Use of `echo` as a debugging technique.
 

**Key functions:** `$`, `echo`, `history`, `!`

## Shell Scripts:

The link to this lesson is found [here](http://swcarpentry.github.io/shell-novice/06-script/). ONLY COVER IF THERE IS TIME!!

**Key points to hit in this lesson include:**

* `ctrl-c` to kill programs
* the use of `$1` within programs
  * Why we surrond variables with `""`
* the importance of commenting scripts


**Key functions:** `$1`, `$@`



