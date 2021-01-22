# GitHub_Command_1

    1. initilized as git:   git init
    2. show the untracked and tracked file: git status
    3. For making tracked file(single file) use the command:    git add test.txt
    4. for making tracking all file: git add .

    Note: After make sure the files as tracked, all the file are ready to commited

    5. for commit: git commit -m "first Commit"
    Note: git commit "comment: -m 'first Commit' "
    6. Again theck status(Is master / is main): git status
    7. For checking commit: git log  (show all information)
                                    OR, git log --oneline (show needed information)
    8. Back to any commit: git checkout bce3411 index.js
         Note: checkout "commit address" "file name"
    9. Check git status: git status
    10. Again need to git command; git commit -m "Forth Commit"

Now unstage the git:
    11. Entered the required git: git checkout ce3f6e8 index.js
    
    12. Reset the git: git reset index.js
    
    13. Further check the git status: git status
    
    14. Back to previous version: git checkout -- index.js
    
    15. Further check the git status to ensure: git status
    
