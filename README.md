# This GitHub repository was created to help graduate students in GPHY 504 learn how to use code repositories to collaborate and work together on large scale data projects!
GitHub is a wildly 
powerful tool, that when used correctly, can foster collaboration and creation among many scientists. If you are like me (me being MSc student Maddie Beck), understanding what exactly GitHub is 
doing can be a bit difficult. So, let's start with the basics.

## Markdown Files:
What are you looking at right now? In GitHub, it looks just like a description of the code that we will be using. You might look and see that this file is called "README.md". All good GitHub repositories have one, because without a description of what your code does, your viewers, collaborators, friends, mentors, and randos on the internet will have NO idea what you are doing. However, markdown (.md) files are not simply just text as they may appear. In fact, they are a powerful tool in themselves and have many shortcuts in order to organize your code descriptions. The first step 
of this lab is to learn a little bit more about how markdown files can help improve the useability of your code. 

## Getting started: 
You are likely reading this file on the GitHub page on a web browser such as Chrome, Firefox, Safari, or many others. To you, this file looks clean, compact, and has different fonts, bolding, numbered and bulled lists. However, this markdown file itself can be edited 

To get started with this lab, follow the steps below:

1. First, navigate to the MSU Tempest website. When prompted, enter your NetID and Password: https://tempest-web.msu.montana.edu
1. Once in here, you should see a home page. On this home page, there is a ribbon at the top. There should be tabs named "Files", "Jobs", "Clusters", and "Interactive Apps". Click on "Interactive Apps" and navigate to "Jupyter Earth Science Lab". When prompted, enter 2 hours and press "Launch". This step may take a few minutes, but wait until you are given the option to "Connect to Jupyter". 
1. Once in your Jupyter environment, you will be given many options in the launcher. Click on "Terminal" and a new window will open within your Jupyter environment. 
1. Once in your terminal, you should see a prompt something like this "[f--f---@tempest-epyc002 ~]$ ". This should match your NetID followed by an @tempest-epyc002 ~J$ This is your prompt line, and you will type code to the right of the $ sign. 
1. Type "$ls". This will bring up all of the folders in your working directory. You may have a few example folders, but at this point, you will have nothing related to the lab in here!
1. Now, navigate back to the top of the GitHub page you are reading this on. You should see a green button titled "Code". Click on this and copy the **HTPS** path. 
1. Now, back in your Terminal, use the command $git clone "Paste HTTPS Path". Press enter, and once it has finished, type "$ls" again. You should now see a folder titled "GPHY504_Lab".
1. Navigate to your new directory using $cd GPHY504_Lab

## Now comes the fun!
1. Once in your new directory, view the contents of the folder. You should see a code, a .csv file, and a README.md file.
1. Open the markdown file, the same one you are viewing now on your browser using the command $nano README.md
5. Now you should be viewing the md file in your own terminal! How cool!! 

## Add your name here: 
*If you run out of "1." add your own followed by your name!*
1. Maddie
1. Maddie Test 
1. 
1.
1.
1. 
1. 

## Now, exit out of markdown using "control x" on your computer. If prompted, type "y" to confirm exiting the markdown file
### You should be back in your terminal window

## We now want to add our updated file back to the GitHub page. To do so, follow the following code:
1. $ git add .
1. $ git commit -m "Add a descriptive detail to what you did. In this case, say something like 'adding my name'"
1. $ git push origin main

## That should have worked. Refresh your browser and make sure the GitHub read me file updated.

## How cool! Do you see your name? This is just a short example highlighting how working in GitHub can be an amazing, collaborative work experience. However, GitHub has many other benefits. Let's explore a few.

1. You should see two other contents of the "GPHY504_Lab". One named "Baseball_Decades.csv" and the other "Lab00_Fall2022.ipynb". We are going to work with these two files. 
1. Right click on the .ipynb file Lab00. Click copy, and then press paste in the contents of the GPHY504_Lab folder. Give it a descriptive name such as "Maddie Lab 00". 
1. Double click on your newly created .ipynb to open it, and start working through the lab. Make sure to answer the questions within the .ipynb!
1. Once you are done, make sure to save your .ipynb. Click on "file" in the upper left and download your notebook. You will turn this in for your lab!
1. Next, navigate back to your terminal window, and use the same steps as above to add your changes back to the original lab. Refresh the GitHub page to make sure your changes were saved. 
