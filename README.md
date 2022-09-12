#This GitHub repository was created to help graduate students in GPHY 504 learn how to use code repositories to collaborate and work together on large scale data projects! GitHub is a wildly 
#powerful tool, that when used correctly, can foster collaboration and creation among many scientists. If you are like me (me being MSc student Maddie Beck), understanding what exactly GitHub is 
#doing can be a bit difficult. So, let's start with the basics.

## Markdown Files:
What are you looking at right now? In GitHub, it looks just like a description of the code that we will be using. You might look and see that this file is called "README.md". All good GitHub 
repositories have one, because without a description of what your code does, your viewers, collaborators, friends, mentors, and randos on the internet will have NO idea what you are doing. However, 
markdown (.md) files are not simply just text as they may appear. In fact, they are a powerful tool in themselves and have many shortcuts in order to organize your code descriptions. The first step 
of this lab is to learn a little bit more about how markdown files can help improve the useability of your code. 

## Getting started: 
You are likely reading this file on the GitHub page on a web browser such as Chrome, Firefox, Safari, or many others. To you, this file looks clean, compact, and has different fonts, bolding, 
numbered and bulled lists. However, this markdown file itself can be edited on your home computer, and is a good first step to understanding the helpfullness of GitHub. 

To get started with this lab, follow the steps below:

1. Open a terminal on your home computer. You can do this many ways, but I like to open the search bar and type in "terminal". You can also navigate to your applications and search for terminal in 
there. Regardless, a new window should open on your computer. You should see a prompt similar to what shows on my personal computer $ (base) CLS2019095:~ f6____ . For me, my computer is registered 
to my school account, therefore, my usernam is my student ID, a six letter code. Yours will be different, but as long as you see a prompt to start writing, you are good to go.
1. Type "ls" in the prompt line and press enter. You will see a list (get it, ls for list) of all the different paths on your computer. Mine include, Applications, Desktop, Music, Zotero, and many 
more. 
1. Change your directory to your OneDrive account. This will allow for you to save your data to be worked on at a different time. However, if you have a Mac or LINEX computer and would like to save 
this work to your own storage, feel free to navigate to your Desktop.
* Note that hashtags "#" mean comments when talking about coding and $ mean "copy the code after the $". Do not copy the $ in your code or it will not work!
* To change directories, we use the "cd" command (change directory, cd)
* Type this: $ cd OneDrive - Montana State ...
* Once you have typed enough characters to differentiate the new location from any other folder on your computer, you can press the "tab" button on your computer to autopopulate the rest and save 
you time
* Press enter and you should be changed to to a new directory. Mine is now (base) CLS2019095:OneDrive - Montana State University f6____$
1. Now, lets create a new folder within your new directory:
* Use the "mkdir" command (make directory, mkdir) and use a descriptive name
* $ mkdir 504_GitHub_Lab
1. Check to make sure your new directory is there: 
* $ ls
*If at any point you need to delete a directory, say you made a type, use "$ rm -r DirectoryName"*
1. Navigate to your new directory: 
* $ cd 504_GitHub_Lab

## Now comes the fun!

1. Now we want to clone the GitHub repository into our new folder. To do so, got back to repository on your browser. Press the green button that says "Code" and copy the SSH path
1. Now, back in your terminal window, use the following code: $ git clone SSHPath
* You should see updates for the data cloning into your directory. Once done, if you press ls you should see a new folder called "GPHY504_Lab"
1. Change your directory to the new folder just created and view the list of contents
1. Open the markdown file, the same one you are viewing now on your browser using the command $ nano README.md
1. Now you should be viewing the md file in your own terminal! How cool!! 

## Add your name here: 
*If you run out of "1." add your own followed by your name*
1. Maddie
1. 
1.
1.
1. 
1. 

## Now, exit out of markdown using "control x" on your computer
### You should be back in your terminal window

## We now want to add our updated file back to the GitHub page. To do so, follow the following code:
1. $ git add .
1. $ git commit -m "Add a descriptive detail to what you did. In this case, say something like 'adding my name'"
1. $ git push origin main

## That should have worked. Refresh your browser and make sure the GitHub read me file updated. 

TEST!
