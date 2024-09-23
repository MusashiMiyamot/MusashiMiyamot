C:\Users\Acer>D:

D:\>cd FCIT

D:\FCIT>git init
Initialized empty Git repository in D:/FCIT/.git/

D:\FCIT>git add junior.html

D:\FCIT>git add senior.html

D:\FCIT>git commit -m "People who work"
[master (root-commit) bb55dcd] People who work
 2 files changed, 2 insertions(+)
 create mode 100644 junior.html
 create mode 100644 senior.html

D:\FCIT>git add student.html

D:\FCIT>git commit -m "People who study"
[master 39cf27f] People who study
 1 file changed, 1 insertion(+)
 create mode 100644 student.html

D:\FCIT>git checkout -b addition
Switched to a new branch 'addition'

D:\FCIT>git status
On branch addition
nothing to commit, working tree clean

D:\FCIT>git add calc.cpp
fatal: pathspec 'calc.cpp' did not match any files

D:\FCIT>git add calc.cpp

D:\FCIT>git commit -m "addition"
[addition 5a874e3] addition
 1 file changed, 37 insertions(+)
 create mode 100644 calc.cpp

D:\FCIT>git status
On branch addition
nothing to commit, working tree clean

D:\FCIT>git checkout master
Switched to branch 'master'

D:\FCIT>git status
On branch master
nothing to commit, working tree clean

D:\FCIT>git checkout -b subtraction
Switched to a new branch 'subtraction'

D:\FCIT>git status
On branch subtraction
nothing to commit, working tree clean

D:\FCIT>git merge master
Already up to date.

D:\FCIT>git checkout addition
Switched to branch 'addition'

D:\FCIT>git status
On branch addition
nothing to commit, working tree clean
