1. Configure tooling
    - commands 
        git config --global user.name "[name]"
        git config --global user.email "[email address]"
        git config --global color.ui auto
        
    - examples
        git config user.name "Daniel-Mingren-Li"
        git config user.email "lentenghelmy@gmail.com"
        git config --global color.ui auto
2. Branches
    - git branch [branch-name] -> Creates a new branch
    - git switch -c [branch-name] -> Switches to the specified branch and updates the working directory
    - git branch -d [branch-name] -> Deletes the specified branch
    - git push origin -d [branch-name] -> delete online branch

