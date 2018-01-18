### Follow the steps below to create a copy of this site in your own GitHub account

1. Login to [GitHub](https://github.com)
2. Search for "GHP-Tutorial", the name of this repository, or follow [this direct link](https://github.com/kevenson/GHP-Tutorial).
3. Open the repository page, and click the "Fork" button on the upper right of the screen. This should create a copy of this repo in your own GitHub account.
4. Once the copy is complete, you can click the "Settings" tab to change the name of your new repo if you choose. We'll come back to this tab later on to set up GitHub Pages.

#### You now have your own copy of this repository.

From here, you can use the online GitHub interface to add and modify your files directly in the browser.

However, many users will find it easier to modify files on a local machine, and then upload them to your GitHub repository. If you are modifying files locally, I recommend using [Atom](https://atom.io) as a text editor for Markdown, but you can also Notepad on Windows machines or TextEdit on Macs.

#### Using Git

Using git to manage your files and repos is completely optional. You can bypass this entirely by using the GitHub browser interface to manage your projects.

That said, if you plan to make changes to your project on your local machine (e.g. modifying or adding new files) and then push them back up to GitHub, git is a good choice.

It takes some getting used to, but once you have mastered a few basic commands, git is really quite easy to use and provides a more efficient and seamless workflow.

To get started using git, [make sure you have it installed on your machine](https://git-scm.com/downloads) and follow these simple steps:

1. Go to the homepage of your repo in GitHub, and click the green "Clone or download" button on the right. Copy the HTTPS link.
2. On your computer, open git bash (Windows) or the Terminal (Mac).
3. Using the terminal, navigate  to the location on your computer to which you would like to download your project.
>Hint: use the command "cd" to change your directory. For example, to navigate to `/Users/kevenson/Projects/GHP-Tutorial` I would type `cd /Users/kevenson/Projects/GHP-Tutorial` and hit enter). For more help with navigation, [see this tutorial](https://computers.tutsplus.com/tutorials/navigating-the-terminal-a-gentle-introduction--mac-3855).

4. Still in terminal, type `git clone ` and copy the URL from your GitHub repo (e.g. `git clone https://github.com/kevenson/GHP-Tutorial.git`). Hit enter, and you should see your project repo being copied to your local machine.

From here, you can add, delete, and modify your project files as you like, using your preferred applications.

5. Once you're ready to push your local changes back up to your GitHub repository, go back to the terminal application, and type `git status`. This should show you the status of the current  
