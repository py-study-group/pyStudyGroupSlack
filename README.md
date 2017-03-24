# pyStudyGroupSlack

## About us
[Join us](https://pystudygroup.slack.com) on slack!

pyStudyGroup is a python user group located on slack in which members can:
 * Ask for help
 * Share code and ideas
 * Plan and create projects as teams

This repository is for pyStudyGroup members to introduce ourselves as well as share small pieces of code with other users

## Getting started with git
The following is a short introduction to git and getting started with pyStudyGroup but should by no means be considered a complete 
guide. Please take time to get familiar with git and github to better communicate with fellow members.
* www.git-scm.com
* www.github.com

Before getting started make sure you have installed [git](https://git-scm.com) on your system
and that you have a [github](https:github.com) account

### Fork pyStudyGroupSlack
To get started we must fork this project. Forking another user's project creates a copy in your own repository 
which you may edit and later send changes back to the original project.
  
To fork this project simply click on fork in the top right-hand corner of this page

### Clone pyStudyGroupSlack
A clone is copy of your git project located on your computer.
This is where we edit files in the project.

To create a clone run the following code, replacing \<user\> with your github username

```
$ git clone https://github.com/<user>/pyStudyGroupSlack.git .
```

Then go inside the pyStudyGroupSlack directory

```
$ cd pyStudyGroupSlack
```

### Create *your* directory
While inside pyStudyGroup, create a directory with your slack username

```
$ mkdir <username>
$ git add <username>
```

and go inside that directory

```
$ cd <username>
```

And there you can do what ever you want, this is your personal folder in our git project!
This is a great place to save and share code with other users

For this example I will create a README.md file
saying some things about me

```
$ vim README.md
```

Then add this folder to github tracking

```
$ git add .
```

Then commit with your slack username as the message and push (upload) the changes to github

```
$ git commit -m <username>
$ git push
```

Finally we must get this back to Belonias/pyStudyGroupSlack. So go to the project's github page
at https://github.com/Belonias/pyStudyGroupSlack and click "Compare and pull request" to submit your changes
to the original project (pending approval)

Thank you for reading and joining us at pyStudyGroup!
