# Please enter the commit message for your changes. Lines starting
# with '#' will be ignored, and an empty message aborts the commit.
# On branch master
#
# Initial commit
#
# Changes to be committed:
#   (use "git rm --cached <file>..." to unstage)
#
#   new file:   README.md
#
Save and exit from the text editor, and you should then see output that looks similar (but not identical) to this
[master (root-commit) 63d4556] Added the file README.md so that we have an initial file to play with in Git
 1 file changed, 10 insertions(+)
 create mode 100644 README.md
This output is Git telling you that it has committed a change that involved one file, which contained ten new lines of text.
Now, finally, we can use git status to see what Git now knows about this directory. You should see something like
# On branch master
nothing to commit, working directory clean
This is Git telling you that there are no unrecorded, uncommitted changes present in this directory. Note that Git refers to versioned_dir as the “working directory”. This is an important piece of terminology. The “working directory” is the term we use to refer to a directory that is being version controlled.
A “clean” working directory is one for which all changes have been committed, while a “dirty” working directory is one that contains changes that have not yet been committed (i.e. recorded/saved).

Exercise
Create a new file called something.md in versioned_dir. Type and add some text into this file, e.g. copy and paste in the text from this web page.
