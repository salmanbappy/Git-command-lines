# 1 To configuare the username and email.

- git config --global user.name "Salman"

- git config --global user.email "msalmanbappy@gmail.com"

# 2 Create a repository.

- git init

# 3 Add remote repository.

- git remote add origin https:<remote repository link>

# 4 Add files to the staging area for commit.

- git add filename.py
- git add \*.py <Add files with specific extension>
- git add . <add all file in the repository>

# 5 Commit changes

- git commit -m "Some Messages"

# 6 See remote link

- git remote -v

# 7 Rebase commit

- git commit --amend -m "Rebased Commit"

# 8 View Changes in Files

- git diff <This shows line-by-line changes in all modified files.>
- git diff filename.js <To see changes in a specific file>
- git diff --cached <After you stage files using git add, view the changes in the staging area with>
  HELOO

# GIT pull origin main --rebase
