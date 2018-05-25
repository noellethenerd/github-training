# Git Bash notes

Copy repo url
###### Found under green Clone/Download button in GitHub repo

Open GitBash
###### Note: use use shift+insert to paste url
```
git clone [url]
cd [repo name]
atom .
```
  *This will open atom in the current directory but you can use any IDE you prefer*

Now make your changes!
___
To view changes you've made (_Remember to save your changes in your IDE first! Or enable autosave_)
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
