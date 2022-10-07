# Class 3

[Back to home page](../README.md)

In this class we learned about **The cloud** and **Making revisions**. We also learned alot about git and uploading our work from vscode to github.

## Background of Git

- **Version control** or VCS is a system made to save previous versions of your work to come back to.
- **Local Version control** is one database on a local computer that stores all previous changes.
- **Centralized Version control** or CVCS is similar to local, but can be accessed by multiple developers, but is still saved on a single computer.
_ **Distributed Version control** is the solution to the one downside of a CVS, having a single computer save all previous changes in a database could be bad if file corruption happens, so developers make mirror repositories in case of faliure.

### So what is *Git*?

- Git is a DVCS (distributed version control) that will store any and all data in the repository as *snapshots*.
- Think of snap shots as taking a reference picture, once it is taken, you can go back and view it. Git will use these snapshots as reference if a new save is not made to the file.
- Git will track all of the changes made and to files and gate keep them, making it very hard for any file corruption to occur.

To make these saves to your repositories-

1. Find your project in the terminal and type "git status", this will initiate a sweep to see what files are modified and not uploaded yet to Github. Any file in red will need to be saved.
2. Type in the terminal "git add (name of file)", this will add the file to be staged to be commited for the snapshot. An easier way to save all your files is typing in the terminal (git add .) this will stage all unsaved changes.
3. Next type in the terminal git commit -m. You will then need to put a message of what is being updated in quotation marks ("") after -m.
4. Once everything is saved in a snapshot, upload your work to Github by using the command git push origin main. Your website should be updated automatically through Github after that!
![Visual](https://blog.udemy.com/wp-content/uploads/2015/08/image066.png)
