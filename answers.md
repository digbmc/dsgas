# Answer key

## Tasks

### Setting up
1. Install git (should be installed with atom)

2. Create a github account

3. Slack your username to Alice so she can add you to the DSGAs team

4. **Config**-ure your name and user account using the command line

  git config --global user.name "[firstname lastname]"

5. **Clone** this repository and open it in atom

  git clone https://github.com/digbmc/dsgas.git

### Publishing
1. Create a new markdown document in your local copy of the repository.

  touch myname.md

2. Open the document in atom and write content: use markdown syntax to create headings, text, and links or images. Save the document.

  atom myname.md

4. **Add** your document to git's plate so it knows you've made changes (also referred to as "staging" your changes)

  git add --all

5. **Commit** to the changes you've made (at least for now) and write a note about what you changed

  git commit -m "added personal page"

6. **Pull** in any new changes from the cloud-based or "remote" repository (always do this before you publish your changes to a shared repo)

  git pull

7. **Push** your changes to the remote repository.gi

  git push origin master

8. Open the remote in your browser to see what happened.

### Collaborating
1. **Pull** your teammates' changes and see what happens.
2. Open the file [collaboration.md](/collaboration.md) in Atom, make some changes, and save the file.
3. **Add** your changes and **commit** them
2. Create a new **branch** of the repository so your changes won't interfering with anyone else's work.
3. **Checkout** your new branch (switch to it).
4. **Push** your changes to your personal **branch** (you don't need to pull because nobody else should be working on this branch): git push origin [yourbranch]
5. Look at the remote in the browser and see if you can figure out where your changes went.  
6. Once you feel good about the changes you've made on your branch, you can try to **merge** it with the master branch.
