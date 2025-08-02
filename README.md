# Git-Github_Interview Questions & Answer

✅ 1. What is Git?

    Git is a distributed version control system used to track changes in source code during software development. It allows multiple developers to work on a project simultaneously without overwriting each other’s work.
  
✅ 2. What is GitHub?

    GitHub is a cloud-based hosting platform that lets you manage Git repositories. It provides features like pull requests, issues, CI/CD, access control, and project management tools for collaborative development.

✅ 3. What is the difference between Git and GitHub?

    Git	GitHub
    Version control system	Git repository hosting service
    Installed locally	Hosted online
    Command-line based	Web-based GUI
    Open source	Owned by Microsoft

✅ 4. What is a repository (repo)?

    A repository is a storage space for your project. It contains all your project files, including the history of changes made to them.

✅ 5. What is the difference between git clone and git fork?

    git clone: Creates a local copy of an existing Git repository.
  
    Fork: Creates a personal copy on GitHub which you can modify independently and propose changes via pull requests.

✅ 6. What are branches in Git?

    Branches are used to create different versions of a repository. The main or master branch is the default. Feature or fix branches are created to work independently, and then merged back.

✅ 7. What is the difference between git fetch and git pull?

    Command	Function
    git fetch	Downloads updates from remote but doesn’t merge
    git pull	Fetches and merges in one step

✅ 8. How do you resolve merge conflicts in Git?

    Use git status to see conflicted files.
  
    Open the file and manually edit the conflicts.
  
    Add the file using git add <filename>.
  
    Commit the merge with git commit.

✅ 9. What is a pull request (PR)?

    A pull request is a way to propose changes from one branch to another, typically from a feature/fork branch to the main branch. It allows code review and collaboration before merging.

✅ 10. What does git stash do?

    It temporarily saves your uncommitted changes so you can switch branches without losing work. Use git stash pop to apply them later.

✅ 11. What is the difference between git merge and git rebase?

    Merge	Rebase
    Keeps history of both branches	Rewrites history as linear
    Can result in extra commits	Cleaner history
    Safe for public branches	Best for local changes

✅ 12. What is .gitignore file?

    .gitignore tells Git which files or folders to ignore (e.g., log files, build folders). This helps keep the repository clean.

✅ 13. How to undo a commit in Git?

    git reset --soft HEAD~1: Undo commit but keep changes staged.
  
    git reset --hard HEAD~1: Undo commit and delete changes permanently.
  
    git revert <commit>: Safely undo a commit by creating a new one that negates it.

✅ 14. What is origin in Git?

    origin is the default name for the remote repository from which you cloned. You interact with it using commands like git push origin main.

✅ 15. What are some best practices for using Git and GitHub?

    Commit often with meaningful messages.

    Use feature branches.

    Always pull before pushing.

    Write clear PR descriptions.

    Review code before merging.
