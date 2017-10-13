# LAB 1:

## Markdown

**What is Markdown**

   Markdown is an easy-to-use syntax for formatting in GITHub. It allows the use of special characters (syntax) to apply formatting such as **bolding**, indentations, *italics* ~~and more~~ etc.

**Command line 101**

   Opened up the console terminal and tested each of the given commands; this is what each line stands for.

*ls*
* Looks into the directory.

*cd /tmp*
* Takes us to the directory "/tmp".

*cd $HOME*
* Takes us back to the home directory. 
* The $ symbol brings you back to the start of the directory line.

***NOTE: cd - takes you back to the previous directory you were in.***

*mkdir [Directory Name]*
* Creates a new directory.

*echo "Hello" > hello.md*
* **echo "Hello"** prints the message within parenthasis to the terminal.
* **> hello.md** creates a Markdown file which calls the function echo "Hello" when input.

*cat hello.md*
* *cat {File}* calls up whatever is inside the file, and prints it to the terminal. 

*cp hello.md hello-again.md*
* *cp {Source} {Destination}* copies the source file to a destination file.

*mv hello-again.md hello-hello.md*
* *mv {Source} {Destination}* renames or moves the source file to a destination. If we use *cat hello-hello.md*, it calls up the "Hello" message from earlier. (Showing we have copied hello.md to hello-again.md, then renamed hello-again.md to hello-hello.md.)

*rm hello.md*
* *rm {File}* removes the file.

*rm -rf*
* *rm -r* deletes the directory and all its contents. **Typically, rm without the -r does not delete directories.** The f after -r voids the statement.

*cat /proc/cpuinfo*
* As mentioned above, this calls up a file, in this case "/cpuinfo", located inside the directory "/proc".

---------------------------------------------
## Git & GitHub.

Created a GitHub account and committed my journal.

**NOTE** "git log" and "gitk" are nice tools to allow you to track and display your commit history.

A "commit" essentially saves a version of whatever you're committing and allows you to attach a comment describing the changes you've made to whatever document you are "saving". 

**Git commands:**

*git add "file name"
* Adds the file name to git.

*git commit*/*git commit -m"commit message"* 
* Lets you commit your changes.

*git status*
* Gives details on number of commits, files associated and untracked files.

**NOTE** "git log" and "gitk" are nice tools to allow you to track and display your commit history.

*git push*
* Pushes the git repository online.

**NOTE** Set up online communication to GitHub using:

*git remote add origin https://github.com/(account)/(repo).git* 
* Adds a "remote" called origin.

*git push -u origin*

---------------------------------------------
# LAB 2:

***Motor Design: Initial Version.***

Created an initial commutator from a cork as a base, and two pieces of copper tape for the brushes to press against.

Supported the armature with two metal pins to act as a shaft to allow the motor to spin.

Note: *Had issues with the shaft falling off the supports, and this was something we had to consider for improvement.*

We then wound 120 turns of copper wire around the armature.

Created supports to hold both the motor and magnets using paper clips, and aligned everything using the provided board.

*The image of the first draft of the motor is provided in "motor_one.png".*




