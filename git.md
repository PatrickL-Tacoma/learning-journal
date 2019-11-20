## Learning about Git

Understanding GIT

A Distributed Version Control systems (DVCS) addresses the major vulnerability of the CVS: the server as a single point of failure. 

Git is a DVCS that stores data in a file system made up of snapshots. 

Git mostly relies on local operations because most necessary information can be found in local resources (i.e. local drive), allowing for continued working on files even when offline.

Ensure you have the correct repository or set up a new repository 

To work locally with Git, workfiles need to cloned to the local computer by copying the file link provided by the GitHub application into the correct local folder using Ubuntu terminal and line code: git clone <file link>.

Call up VS Code < code . > to edit the file 

Files in Git can reside in three main states: committed, modified and staged.
Committed - Data is securely stored in a local database
Modified - File has been changed but not committed to the database
Staged - Flagged a file’s changed version to be committed in the next snapshot
A - C - P:  This is the process of adding changes to the local file version, committing those changes by staging them for cloud database and finally pushing those snapshot changes to the cloud database using a reference hashtag.  

--Add - < git add . > Moves changes from the working directory to the staging area. 
---Check status < git status >
--Commit - < git commit -m “<message>” > Takes the staged snapshot and commits it to the project history. Use current active tense within message.
---Check status < git status >
--Push - < git push origin master > Pushing is the opposite of fetching (with a few caveats). It lets you move a local branch to another repository, which serves as a convenient way to publish contributions. 
---Check status < git status >
