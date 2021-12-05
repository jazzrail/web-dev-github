- Create a new branch: git checkout -b delete (anyname)

- git status - to quit = shift + q

- delete a file in git: navigate into the directory and run (e.g) git rm file3.txt

- Go back one commit: git reset --hard HEAD~1 This restored my deleted files (file2.txt and file3.txt) and reset the index.

- Delete a branch. We merged the feature branch, so let's get rid of it: git branch -D feature
