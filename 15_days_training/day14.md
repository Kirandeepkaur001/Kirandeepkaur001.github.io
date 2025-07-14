# DAY 14 :

## What is Branching in Git?
Branching means creating a separate line of work in your project — so you can try something new without breaking the original (main) project.

## **_Real-Life Example:_**
You're writing a story. You want to try two different endings:
* One happy
* One sad
You make two copies of the story and write both endings separately. That’s branching.

## **_In Git:_**
You start with the main branch (usually called main or master). Then you create new branches to:
* Add a new feature
* Fix a bug
* Try something risky
* Work with teammates separately
* Each branch is like an independent workspace.

## **_Why Branching is Useful:_**
* Keeps the main code safe
* Helps multiple people work at the same time
* Easy to switch between ideas
* Let's you test things freely

## **_Common Git Branching Commands:_**

| Task                        | Command                                         | What it does                           |
| --------------------------- | ----------------------------------------------- | -------------------------------------- |
| See current branch          | `git branch`                                    | Lists all branches                     |
| Create a new branch         | `git branch new-branch`                         | Makes a new branch                     |
| Switch to a branch          | `git checkout new-branch`                       | Moves to that branch                   |
| Create & switch in one step | `git checkout -b new-branch`                    | Shortcut to create & switch            |
| Merge a branch into main    | `git checkout main` <br> `git merge new-branch` | Combines your branch changes into main |
| Delete a branch             | `git branch -d new-branch`                      | Deletes the branch (after merge)       |

## **_Branching Workflow Example:_**
    # Start on main branch
    git checkout main
    
    # Create and switch to a new branch
    git checkout -b feature-login
    
    # Work on your code (edit files)

## **_Visual Metaphor:_**
          main
            |
            |---------> feature-1
            |
            |---------> bug-fix
Each line is a branch. You can work on them independently, then merge when you're ready.

##  What is Merging in Git?
Merging means taking changes from one branch and combining them into another branch.

## **_Imagine This:_**
You and your friend are writing two parts of a story.
* You're working on main
* Your friend is working on feature-chapter2
Now you want to combine your friend's work into the main story. That’s called merging.

## **_Merge Commands:_**
    git checkout main        # Move to the branch you want to merge into
    git merge feature-branch # Merge the other branch into this one

## **_What happens:_**
* Git will try to automatically combine the changes.
* If two branches changed the same line = merge conflict (you fix it manually).

## What is Push and Pull?
### **_git push = Send changes from your computer → GitHub_**
        git push origin branch-name
* “Upload my work to the cloud.”

### **_git pull = Get latest changes from GitHub → your computer_**
        git pull origin branch-name
* “Download updates from the cloud.”

## What is Rebase? (A cleaner alternative to merge)
Instead of "combining" branches like merging, rebase moves your branch on top of another branch as if your work happened after it. Think of it like:
* Telling Git: “Pretend I started my work from the latest version of main.”

## **_Why use rebase?_**
* Keeps history clean and linear
* No messy merge commits
* Looks like all work happened one after another

## **_Rebase Commands:_**
    git checkout feature-branch
    git rebase main
    
    Then:

    git checkout main
    git merge feature-branch   # Fast-forward, clean merge

