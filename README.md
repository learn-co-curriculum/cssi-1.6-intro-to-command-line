---
tags: cssi, basic command line, code along
level: 1
languages: command line
---
#Intro to the Command Line

#Objective:
Students will be able to navigate their system’s file structure using the CLI (command line interface) in terminal.
Understand and explain what a terminal is and why we use it
Navigate and manipulate directories

#Motivation / Why Should You Care?
Back in the day (the 1980s!), computers only had a terminal to control them. Later on, Graphical User Interfaces (GUIs) were created to make computers more accessible and intuitive for those who weren't as computer savvy. Developers continue to use the terminal instead of the GUI because it speeds up development and allows for more fine-grained control.

#Lesson Plan
You're going to learn about the command line by planning for a trip.
1. Open Terminal- Either click the icon, or hit Command + space and type Terminal, then click enter. A small white rectangle will appear with the name of your computer, a tilde (~) and your username followed by a $.
2. You’ll see a tilde: ~. This means you’re in your user's home directory. Directory is another word for folder.
3. Enter pwd : pwd means print working directory - it tells us where we are.
4. Enter ls : check what directories are within the directory where you are standing by using
5. Enter cd: change directories by using the cd <directory-name> command. Change to Desktop directory.
5. Enter mkdir <directory-name>: makes a new directory. Make a new directory in development called around-the-world.
6. Enter cd around-the-world: to change directories into around-the-world
7. Enter mkdir France: creates a directory called France inside of around-the-world
8. Enter cd France: to change directories into France
9. Enter mkdir Paris: to create  a directory called Paris inside of France
10. Enter cd Paris: to change directories into Paris
11. Enter touch eiffel_tower.txt: to create a text file called eiffel_tower in the Paris directory
12. Enter touch berlin_wall.txt: to create a text file called berlin_wall in Paris directory
13. Enter touch pyramids.txt: to create a text file called pyramids in Paris directory
14. Enter rm berlin_wall.txt: To remove the berlin_wall
15. Enter mv <file to move> <final destination>: mv pyramids.txt france/around-the-world or my pyramids.txt ../.. You have to list the path of directories in order to move the file to the final destination
16. Enter cd .. to move up the tree of directories. cd ../.. will bring you up two parent directories

#Student Activity
1. Create a directory called "Egypt" in the "around-the-world" directory
2. Create a directory called "Cairo" inside the "Egypt" directory
3. Move "pyramids.txt" into the "Cairo" directory. **Hint: List the path from around-the-world to Cairo**
4.  Stretch: Create a new country, city, and landmark file in the "around-the-world" directory

#Tips and tricks:
 If you start typing a directory name or file name you can click tab and the command line will automatically fill in the rest of the directory/file name. If you click tap twice it will show you all of the directories/files inside your current directory.
 Navigating your computer from the command line is a lot about muscle memory. The more practice you have the faster you will get!

#Conclusion / So What?
As we learn to build complicated applications, being able to swiftly navigate your computer using the command line will make your life much easier. The command line will be important not just for navigation, but you'll also use it to do things like boot the local server for your web apps, write scripts to automate tasks, and execute other important functions on your computer.

#Stretch Lab
If you are feeling comfortable with the command line try this advanced <a href= "https://github.com/learn-co-curriculum/hs-advanced-cli"> command line and shell scripting lab</a>
