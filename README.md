# Daily-Git-Commit

Commit to repo every day for the perfect commit streak

## Requirments

`pip install -r requirements.txt`



## Setup

1. 	Download this repository.
2. 	Create your own repository on your GitHub account.
3. 	It's very important to first commit the `update_me.yaml` file first before you begin the daily commit.
4. 	That's really it.. Assuming your logged into git on your system it should work fine.

Now that your repository and git is setup, its time to set up the most important part. DAILY commit. Since the script handles all of the updates and processing, all we need to do is call that script. There are alot of ways to achieve this, depending on what operating system you are on. Below are instructions for both Windows and Linux solutions, you can do this how ever you feel. 

### Possible Issues

1.  If for some reason it doesn't commit, re-clone or merge the repository to your PC again. It's just a funny issue it has.

### Windows

I will be showing you how to set this up using task sceduler on windows.

1.  Open 'Task Scheduler' from search bar.
2.  Press 'Create Task...'.
3.  Name it: "Daily Git Commit" just so you know what it is later on, and not some wierd virus.
4.  I would suggest, to check both of the following: "Run with highest privileges" to insure no issues ever occure when reading and writing to files, and: "Run where user is logged on or not" Just so you never miss a day when your PC is logged out.
5.  Head over to the "Triggers" tab, and create a "New" trigger.
6.  Set the trigger to DAILY (or how ever you want :) ) and set the time how ever you want. Make sure the "Status" is: "Enabled"
7.  Next go to the "Actions" tab. (This is where we specify what program to run.
8.  Press "Browse" and go to the path of the `run.bat` script and double click it. There is no need for additional arguments. Press OK.
9.  There are a few additions settings you can change in the "Settings" tab, such as if the task fails restart it every couple seconds, maybe a network error. Run task ASAP. There is not more to setup, this is pretty much it for windows setup.

**NOTE**
- Make sure you edit the `run.bat` file to the correct paths.
- If for some reason, the directory changed/`run.bat` got renamed or deleted/or you deleted the project and re-downloaded. REPEAT step 8.
- If there are errors that occur, open up an issue and I will get it fixed ASAP.

From JareBear12418 

