# Instructions for working with git

1. **Open cmd.exe**

    1.1 (one time) Introduce yourself to git:
``` sh
git config --global user.name "Name"
git congig --global user.email "Email"
```
2. **Open folder which you need**

for Windows use this command:
``` sh
cd "file location"
```

3. **Start tracking this folder by git (create a repository)**
``` sh
git init
```

4. **Add files which you need to track**
``` sh
git add "Name of file" 
```
*Note: you can enter 3 letter and use button "Tab"*

5. **Add your message for this commit**
``` sh 
git commit --m "your message"
```
6. **Repeat n. 4-5 if you need to create a commit**

7. If you want ignore file, create new file in this folder ".gitignore" and write the name of file

## Command to work with git

1. *git init* - start tracking by git in this folder / create a new repository
2. *git add "Name.file* add file in this folder to track by git
3. *git add --all* - add all files in this folder to track by git
3. *git commit --m "message"* - attach message 
4. *git status* - see information about tracking by git
5. *git log* - see all commits 
6. *git log --oneline* - see all commits (compact view)
7. *git checkout "Name.file"* - see past commits
8. *git checkout master* - return at the last file
9. *git diff* - see different between commits
