# Prework Bash Practice

[Back to home page](../README.md)

## The command line

- The command line (or terminal) is a text based interface for navigating through your computer. The user will typically be issuing commands and receive feedback. This could be a variety of things such as viewing a file, creating or deleting a file, navigating through files, etc. while not as visual, once you get the hang of navigating through your terminal, it can easily be just as or even more effecient than navigating through the user interface. Shortcuts are one of the many benefits to using a command line as well.

## Basic navigation

- Navigating through your terminal is the most important part, and there are tons of commands to issue to see where you are. A few examples of these commands include pwd, ls, and cd. pwd(print working directory) will tell you the directory you are currently in. ls (list) will list all the other directorys in the file you are currently in. And cd (change directory) will change to a specific directory you want to go to. You can also go backwards through directorys by using the cd .. command.

## More about files

- Everything in your navigation is a file! Every file has an identifier at the end of its name, like .txt or .png. This signifies what type of file it is like an image or text file. An important thing to note is the terminal is case sensitive! so writing a file wrong will cause an error. Spaces in naming can also cause some issue, as the command could be seen as 2 seperate commands, hence the spacing. You can get around this by using single quotes, or an escape character like the back slash \ . A directorys hidden files can be seen by using the command ls -a.

## Manuel pages

- The man pages are a set of pages that explain every command the user has to use. using the command man followed by the specific command you want to look up will show some info on the command. to quit this page, simply press q. You can also search for a certain commans by typing man -k (search term). you can also search inside the manuel page with /(term), as well as going to the next page with n. The manuel page is a great resource!

## File manipulation

- Manipulating files is where the meat of the terminal is. Its very simple to make, copy, delete, and do much more with files. For instance, making a directory is as easy as using the command mkdir (file name), and removing a directory with rmdir (file name). Creating files inside directorys is a little different and uses the touch (file name) command, with removing a file using rm (file name). As for copying a file, you need to specify the source and the destination with the command cp (source) (destination). Lastly, move/rename files mv. this one is probably the trickiest, so ive included a cheat sheet with all the specifics in the next section.

## cheat sheet

- useful cheatsheet with commands and what they do! [cheatsheet](https://ryanstutorials.net/linuxtutorial/cheatsheet.php). Use when in need of a refresher or for reference.
