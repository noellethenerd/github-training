# Git Bash notes

Copy url
  Under green Clone/Download button in GitHub repo

Open git Bash (_Note: use use shift+insert to paste url_)
```
git clone [url]
cd [repo name]
atom .
```
  *This will open atom in the current directory but you can use any IDE you prefer*
Make your changes!
___
To view changes you've made
```
git status
git diff
```
To stage all changes in the current directory and all directories underneath
```
git add .
```
You can also stage specific files
```
git add filename
```
Now you are ready to commit changes
```
git commit -m "This is my commit message"
```
After commit, we want to push
```
git push
```
