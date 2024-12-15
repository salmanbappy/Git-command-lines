# To configuare the username and email.

- git config --global user.name "Salman"

- git config --global user.email "msalmanbappy@gmail.com"

# Create a repository.

- git init

# Add remote repository.

- git remote add origin https:<remote repository link>

# Add files to the staging area for commit.

- git add filename.py
- git add \*.py <Add files with specific extension>
- git add . <add all file in the repository>

# See remote link

- git remote -v

# Rebase commit

- git commit --amend -m "Rebased Commit"
