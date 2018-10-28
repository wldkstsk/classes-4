# classes-4
DINO18Z Z.4.
Git manual

The task is to briefly describe key Git commands (as  a group).

Requirements:

 * The answer should have the form of a one-file HTML
 * All commands from the list below have to be included (description, use and exmple)
 * The file should be gramatically correct
    
How to do it:

 * Each student creates their own copy of the repository (fork)
 * All changes are made in the student's copy (preferably in the branch per feature model)
 * Next, the student sends a Pull Request to the original repository

The exercise is completed when a student:

 * made a significant input to the manual (command descripton, manual modification, code review)
 * & made their own repository (fork)
 * & sent a Pull Request to the original repository

The list of commands to describe:

 * Group Monday 13.45
   * git config --global user.name ""
   * git reset HEAD
   * gitk -all
   * git branch --merged
   * git branch "branch" "commit hash"
   * git pull "remote" "branch"
        
 * Gruoup Monday 15.30
   * git config --global user.email ""
   * git diff --staged
   * git checkout -b "branch"
   * git log --graph --all
   * git branch -d "branch"
   * git fetch "remote" "branch"

 * Group Friday 15.30
   * git config --global color.ui true
   * git commit "filename"
   * git branch -v
   * git push "remote" "branch"
   * git log "branch" --not "branch"
   * git bisect (start, bad, good, reset)

