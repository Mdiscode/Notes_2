## Git_Totutial 

## Download git
```
install the git 
```
## create a user name
```
git config --global user.name iserar
git config --global user.email israr@gmail.com

---check the user name or email----
git config --global user.name
git config --gloabl user.email
```
## git init
```
initialized the empty git repo

---ls -lart --command to show all hidden file ---
ls -lart
```

## Structur of git
```
1.Untracked 
2.Unmodified
3.Modified 
4.Staged

1.Untracked (add the file)
the is move to staged area

Untracked ---> staged---->commit---->Unmodified (the file is snapshort area and the git is record the file )

//--if modified the unmodified file
unmodired---(Edit-the-file)--->Modified---(Stage the file)---->Staged----->commit---->unmodified

git commit
press i
initial commit 
press EsC
::wq enter

the file is commit

```
## command
```
1.git status (show all untrack file)
2.touch about.html (create the blank file)
3. git add -A  (all file to staging area)
4. git commit -m "add htmls file"
5. git checkout contact.html  (it match the last commit) if any one can modify your file .

6. git checkout -f  (all file match last commit)

7.git log  (it show all commit name)
8. git log -p -2   ( it show the 2 commit only)

9. git diff  (it show to changes like body to sody-- it compare to working directory to staging area) 

10 . git diff --stage  (compare to last commit staging area)
11. git commit -a -m "skipped staging area and fixes <"

11. git rm fileName (it remove the file)

12. git rm --cached file.name ( it untrack file not remove the storage)

13. git status -s  (it show sort status)

14. touch .gitignore   
```
## .git ignore
```
/contact.html  ( it ignore only the currecnt dir)

*contact.html  (it ignore all folder);

```