# Read: 03 - Revisions and the Cloud
##  Git is a version control software.
Version control is a system that can be used to revisit previous versions of a file or multiple files by keeping record of all your changes. There are three main types:

* Local version control  that exists locally on one hard disk and can only be accessed  from one place.
* Centralized version control this system exists on one hard disk but can be accessed from more than one place.
* Distributed version control allows clients to create mirrored repositories. These data backups can be easily be placed on the server to replace any lost information.

While using Git the data can be in three  states we can check this by typing git status 
* Committed  : Data is securely stored in a local database
* Modified : file has been changed but not committed to the database
* staged : Flagged a file’s changed version to be committed in the next snapshot
## Check settings 
To check settings, use the git config --list command.

Example:

```
$ git config --list

user.name=Jane Smith

user.email=example@email.com

color.status=auto

color.branch=auto

color.interactive=auto

```
## Local Repository Structure workflow

The local Git repository has three components:

1. Working Directory: The actual files reside here
1.  Index: The area used for staging
1. Head: Points to the most recent commit

![](https://www.udemy.com/blog/wp-content/uploads/2015/08/image036.png)


 

