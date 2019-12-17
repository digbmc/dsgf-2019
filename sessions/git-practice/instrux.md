
# Git, GitHub, and Markdown


## Objectives

1. Gain familiarity with git, github, and markdown
2. Practice writing in markdown, using git with the command line and atom, and collaborating on a repository
3. Discover what else you can do with git, github, and markdown
4. Learn about git/atom features.

## Practice

For the relevant commands, see your cheatsheets for [git](https://education.github.com/git-cheat-sheet-education.pdf) and [markdown](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf). If you need help, consult your peers or the [answer key](/sessions/git-practice/answers.md).

### Setting up

1. Once you've made sure git is installed and set up a user account, you'll want to **Config**-ure your name and user account using the command line.
2. **Clone** this repository to your local machine and open it in atom


### Publishing

1. Create a new markdown document in your local version of the repository in the 'git' directory. Use the .md file extension.
4. Open the document in atom and write content using markdown syntax. Include headers, lists, text, and links or images. **NB**: You can check your work in atom using the markdown preview package.
2. Save your new document in **dsgf-2019/sessions/git-practice**
2. Check the **status** of your local repository according to git.
3. **Add** your document to git's plate so it knows you've made changes (also referred to as "staging" your changes)
4. **Commit** to the changes you've made (at least for now) and write a brief message about what you changed.
5. **Pull** in any new changes from the cloud-based or "remote" repository (always do this before you push your changes to a shared repo)
5. **Push** your changes to the remote repository. You will probably be prompted to log in with your github username and password.
6. Open the remote in your browser to see what happened.

### Collaborating

1. **Pull** your teammates' changes. Look at the folder to see what happened.
2. Choose a new file added by a teammate (make sure nobody else is editing it for now). Open it in Atom and make some changes to it.
3. Check the **status** of your local repo.
3. **Add** your changes.
4. **Commit** your changes with a message.
4. **Pull** any new changes, then **push** your changes to the remote repository.

#### Extra credit

1. Now things will get more complicated. Create a new **branch** of the repository so your changes won't interfere with anyone else's work.
3. **Checkout** your new branch (switch to it).
2. Open the file [/sessions/git-practice/collaboration.md](/sessions/git-practice/collaboration.md) in Atom, make some changes, and save the file. **Add** your changes and **commit** them.
4. **Push** your changes to your personal **branch** (you don't need to pull because nobody else should be working on this branch): git push origin [yourbranch]
5. Look at the remote in the browser and see if you can figure out where your changes went.  
6. Once you feel good about the changes you've made on your branch, you can try to **merge** it with the master branch.


## Additional resources

[DHRI Git Tutorial](https://github.com/DHRI-Curriculum/git)

[Overview of Atom features for git integration](https://flight-manual.atom.io/using-atom/sections/version-control-in-atom/)

[Programming Historian tutorial for Jekyll and GitHub Pages](https://programminghistorian.org/en/lessons/building-static-sites-with-jekyll-github-pages)

[Prog Hist Pandoc Tutorial](https://programminghistorian.org/en/lessons/sustainable-authorship-in-plain-text-using-pandoc-and-markdown)

[GitHub Workflow Overview](https://guides.github.com/introduction/flow/)

NB: you don't need the command line to contribute to github projects: [GitHub Desktop](https://programminghistorian.org/en/lessons/getting-started-with-github-desktop) is a popular GUI.
