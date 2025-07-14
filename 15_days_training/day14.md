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
