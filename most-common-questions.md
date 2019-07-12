- How to make Git “forget” about a file that was tracked but is now in .gitignore?
    
    To stop tracking a file you need to remove it from the index. This can be achieved with this command.

        git rm --cached <file>

    If you want to remove a whole folder, you need to remove all files in it recursively.

        git rm -r --cached <folder>

- How do I undo the most recent local commits in Git?
  
        git commit -m "Something terribly misguided"
        git reset HEAD~
        << edit files as necessary >>
        git add ...
        git commit -c ORIG_HEAD

- Difference between “git add -A” and “git add ."
  
        git add -A stages all changes
        git add . stages new files and modifications, without deletions
        git add -u stages modifications and deletions, without new files