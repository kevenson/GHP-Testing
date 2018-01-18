### Follow the steps below to create a copy of this site in your own GitHub account

1. Login to [GitHub](https://github.com)
2. Search for "GHP-Tutorial", the name of this repository, or follow [this direct link](https://github.com/kevenson/GHP-Tutorial).
3. Open the repository page, and click the "Fork" button on the upper right of the screen. This should create a copy of this repo in your own GitHub account.
4. Once the copy is complete, you can click the "Settings" tab to change the name of your new repo if you choose. Note that you can also use this tab to set up GitHub Pages for your project if you choose.

#### You now have your own copy of this repository.

From here, you can use the online GitHub interface to add and modify your files directly in the browser.

However, many users will find it easier to modify files on a local machine, and then upload them to your GitHub repository. If you are modifying files locally, I recommend using [Atom](https://atom.io) as a text editor for Markdown, but you can also Notepad on Windows machines or TextEdit on Macs.

#### Using Git

Using git to manage your files and repos is completely optional. You can bypass this entirely by using the GitHub browser interface to manage your projects.

That said, if you plan to make changes to your project on your local machine (e.g. modifying or adding new files) and then push them back up to GitHub, git is a good choice. It takes some getting used to, but once you have mastered a few basic commands, git is really quite easy to use and provides a more efficient and seamless workflow.

To get started using git, [make sure you have it installed on your machine](https://git-scm.com/downloads) and follow these simple steps:

* Go to the homepage of your repo in GitHub, and click the green "Clone or download" button on the right. Copy the HTTPS link.
* On your computer, open a terminal program, preferably either git bash (Windows) or Terminal (Mac).
* Using the terminal, navigate  to the location on your computer to which you would like to download your project.

>Hint: use the command "cd" to change your directory. For example, let's say I want to clone my project into my "Projects" folder. To navigate to `/Users/kevenson/Projects/` I would type `cd /Users/kevenson/Projects/` and hit enter). For more help with navigation, [see this tutorial](https://computers.tutsplus.com/tutorials/navigating-the-terminal-a-gentle-introduction--mac-3855).

* Still in terminal, type `git clone ` and copy the URL from your GitHub repo (e.g. `git clone https://github.com/kevenson/GHP-Tutorial.git`). Hit enter, and you should see your project repo being copied to your local machine. In my case, this would be copied to: `/Users/kevenson/Projects/GHP-Tutorial`

>From here, you can navigate your project directory and add, delete, and modify your project files as you like, using your preferred applications.

* Once you're ready to push your local changes back up to your GitHub repository, go back to the terminal application, ensure you are in your project directory (e.g. `/Users/kevenson/Projects/GHP-Tutorial` **NOT** `/Users/kevenson/Projects/`) and execute the command `git status`.

This should show you the status of the repository--if you have added or modified files, you should see these changes noted here.

* To add new files and changes to be committed, execute `git add *`. Note that this will add *everything* so if you only want to add two specific files you should use `git add [filename1] [filename2]` instead. Execute `git status` again to ensure you've added everything you need.

* Now, to commit these changes that we've just added, execute `git commit -m "my message here"`, changing the message text to a short message that is meaningful to you (e.g. "added a new contact page"). This helps you and your collaborators make sense of all the changes to your project, and potentially roll them back if something doesn't work the way you want.

* Now we're ready to push these changes up to Github. Execute `git push origin master` and you should see git pushing your changes up to GitHub. Note that you will be prompted to login to GitHub if you are on a shared machine and/or have not setup a [credential helper](https://help.github.com/articles/caching-your-github-password-in-git/), [ssh keys](https://help.github.com/articles/about-ssh/) or another authentication method.
