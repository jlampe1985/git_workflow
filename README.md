Hello this is John and this is my first git project. I am attempting to write a git workflow using git commands in the process for practice.

Step 1.
Make some changes to your file. Then to show that git hasn't staged your changes yet type the command git status

Once you are satisfied with the changes you made add file to staging by typing in the command:

git add filename

Step 2.
In order to document the changes you have made  you must commit your changes.  The command you use is git:

 commit -m "The description of your changes made"

Step 3.
After you commit your changes you need to push it to your repo. The command you use is:

 git push origin master

This will now update your repository on github or where ever you have it stored.

- Check your status constantly to get an idea if git has noticed changes to your file.

modified:   filename output in red means that git noticed a change but the file isn't staged.
type git add filename to the stage the file.

Text will now output modified:   filename but the text will be in green.

- Using the log feature will allow you to see a log of the commits you have made.
This is handy for when you want to see a list off all your commits git has noted.

git log

- cloning your repo is vital for you to get a copy of your repo. The command you type is:

git clone https://github.com/YourUsername/git_test
