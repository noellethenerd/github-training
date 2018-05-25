# Git Bash notes

#### Pull repo from GitHub.
The repo url is found under green Clone/Download button in GitHub repo. Press copy button and use use shift+insert to paste url in GitBash. Be sure you are pulling from the appropriate branch; in other words **do not work in the master branch**.
```
git clone [url]
cd [repo name]
```
This will add a copy of the repo to your local device. You can now edit files on your computer.
```
atom .
```
  This will open atom in the current directory but you can use any IDE you prefer.

Now make your changes!
___
#### View changes you've made.
Remember to save your changes in your IDE first! I advise you to enable autosave.
```
git status
git diff
```
#### Stage changes.
You can stage all changes in the current directory and all directories underneath.
```
git add .
```
You can also stage specific files.
```
git add filename
```
#### Commit changes to your branch.
Now you are ready to commit changes
```
git commit -m "This is my commit message"
```
After commit, we want to push
```
git push
```
