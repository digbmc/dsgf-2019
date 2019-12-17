# Answer key

## Practice

### Setting up

**Config**-ure your name and user account using the command line

    git config --global user.name "<firstname lastname>"

**Clone** this repository and open it in atom

    git clone https://github.com/digbmc/dsgas.git

### Publishing

Create a new markdown document in your local copy of the repository.

    touch myname.md

Open the document in atom and write content: use markdown syntax to create headings, text, and links or images. Save the document.

    atom myname.md

Check the **status** of your local repository according to git.

    git status

**Add** your document to git's plate so it knows you've made changes (also referred to as "staging" your changes)

    git add --all

**Commit** to the changes you've made (at least for now) and write a note about what you changed

    git commit -m "added personal page"

**Pull** in any new changes from the cloud-based or "remote" repository (always do this before you publish your changes to a shared repo)

    git pull

**Push** your changes to the remote repository.gi

    git push origin master

Open the remote in your browser to see what happened.

### Collaborating

**Pull** your teammates' changes. Look at the folder to see what happened.

    git pull

Choose a new file added by a teammate. Open it in Atom and make some changes to it.

    atom newfile.md

Check your **status**, **add** your changes, **commit** them with a message, **pull** others' new changes, then **push** your changes to the remote repo.

    git status
    git add --all
    git commit -m "commenting"
    git pull
    git push origin master

Create a new **branch** of the repository so your changes won't interfering with anyone else's work.

        git branch newbranch

**Checkout** your new branch (switch to it).

        git checkout newbranch

Open the file [collaboration.md](/collaboration.md) in Atom, make some changes, and save the file.

    atom collaboration.md

**Add** your changes and **commit** them

    git add --all
    git commit -m "mychanges"


**Push** your changes to your personal **branch** (you don't need to pull because nobody else should be working on this branch)

    git push origin newbranch

Look at the remote in the browser and see if you can figure out where your changes went.  

Once you feel good about the changes you've made on your branch, you can try to **merge** it with the master branch.

    git checkout master
    git merge newbranch

Nice job!
