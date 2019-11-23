## Introduction

Read *Pro Git*, Scott Chacon and Ben Straub. You don't have to read it cover-to-cover, nor do you have to understand everything you read. Keep going back to it as you get more familiar with using git. You'll be surprised at how much you get even from the first two chapters after you've been using git for a while. 

What you *must* understand at this stage is that a file can be 'modified,' 'staged' or 'comitted,' and correspondingly, your git project has three main sections, the working directory, the staging area and the git repository.

The best way of really understanding git is to use the command line. Sure, it takes a bit of effort, but it will pay off (trust me on this!). With the gui (and the online interface to github), we're in the 'monkey-see, monkey-do' mode of operation.

In the subsequent sections, I will outline the commands I used to set up a repository for our class and a basic checkout/commit cycle

### Let's git started!
I'm already set up, so if I do:
> ~ 3> git config --list --show-origin

I get plenty of information on the settings that are being used.

Here are the contents of my .gitconfig:
> ~ 4> type .gitconfig
>
> [user]
>
>         email = skk.lists@gmail.com
>
>         name = shrirangkarandikar
>
> [winUpdater]
>
>         recentlySeenVersion = 2.18.0.windows.
>
> [gui]
>
>         recentrepo = C:/Users/shrirang/temp/PyFun
>
>         recentrepo = C:/Users/shrirang/git/PyFun
>
>         recentrepo = C:/Users/shrirang/PerceptivePython
>
        
I'm going to run as algoaslyum



Initializing the repository:


> ~\git 8> cd '.\git\Python 201911\'
>
> ~\git\Python 201911 9> git init
>
> Initialized empty Git repository in C:/Users/shrirang/git/Python 201911/.git/


add a new file:
> ~\git\Python 201911 12> ls                                                                                                                      
>
>    Directory: C:\Users\shrirang\git\Python 201911
> 
> 
> Mode                LastWriteTime         Length Name
>
> ----                -------------         ------ ----
>
> -a----        23-Nov-19     11:05           2786 git.md
> 


### Your turn
Here are a few things that you should do on your own. Keep in mind that while the preceding sections may make sense as you read through them, you will only internalize the knowledge if you practice - and make mistakes on your own. 

Experiment - on your own!
- Create a new repository on your local machine
- Clone it to github
- Add a few files
- In a separate directory, clone this repository
- Make a few edits
- Check in your changes to the local repository and push them to github
- Sync your original directory and verify you see the changes
- Look a the history of your files and get familiar with the formats
- Think about how you want to organize your repository/repositories. One for this class? One for each project?

Experiment - jointly!
- Share your repository location with a friend and try making simulataneous changes to the same file, and sync them up

Use!
- Clone the AlgoAsylum repository
- This is the only way you should be accessing the material for this course. In particular, do not just use the web interface!
