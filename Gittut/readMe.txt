git clone <url>
git status                                                            // difference btwn us and the github
git add  <fileName.whatever>                      // to add the new file
git add .                                                              // to add all files 
git add -A                                                          // same as above command
git commit -m <the message/comment> // commit the changes with a message
git push                                                             // to make the changes available in github
git pull filename                                             // get file from repo

esc :wq

Refer https://www.youtube.com/watch?v=0fKg7e37bQE


GITHUB PULL REQUEST, Branching, Merging & Team Workflow
Branching       // this is to copy the master branch so that you can do change
                           // and only the changes are approved the branch can be merged with                               
                           // master
git branch       // to see the current branch
git branch <branchName>  // to copy the current branch under named <branchName>
git checkout <branchName> // to switch to <branchName> branch


Refer  https://www.youtube.com/watch?v=oFYyTZwMyAg

Man
These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone     Clone a repository into a new directory
   init         Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add        Add file contents to the index
   mv         Move or rename a file, a directory, or a symlink
   reset      Reset current HEAD to the specified state
   rm          Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect     Use binary search to find the commit that introduced a bug
   grep        Print lines matching a pattern
   log           Show commit logs
   show      Show various types of objects
   status     Show the working tree status

grow, mark and tweak your common history
   branch     List, create, or delete branches
   checkout   Switch branches or restore working tree files
   commit    Record changes to the repository
   diff            Show changes between commits, commit and working tree, etc
   merge      Join two or more development histories together
   rebase      Forward-port local commits to the updated upstream head
   tag            Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch       Download objects and refs from another repository
   pull         Fetch from and integrate with another repository or a local branch
   push       Update remote refs along with associated objects

