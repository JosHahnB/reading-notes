# Git

In the past, programmers would collaborate by saving a file on a hard disk and sharing, add content and share etc.
It was more challenging to share data and if a file got corrupted, then that was the end, unless there were backups
It evolved into a Centralized version control system, which is a server that holds the data and changes. It was more 
accessable for collaboration and coontrol for divvying up revision access. The major flaw of the CVCS is 
if the server fails, then nobody can work or save changes. Also data corruption could destory the whole project unless
it is saved on a seperate machien.

Distributed Version Control Systems (DVCS) adresses that weakeness by creating a mirror of the repository. If data on the server is 
corrupt, then you or anyone who is working with you can just re-upload your file, and boom! The system is estored. 

Git is a DVCS that can take 'snapshots' of your material and save it, in case you need to look back at a previous version.
Git also tracks all changes you make and can tell you if a file is corrupted.

The local Git repository has three componets:
1. Working Directory: the actual files reside here
2. Index: The area used for staging
3. Head: Points to the most recent commit


## Things I want to know more about:
* I woudl like to be more fluent in Git

[day-3 notes]()
