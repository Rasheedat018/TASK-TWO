# TASK-TWO

VERSION CONTROL:
Version control can also be known as source control or revision control or source code, is a practice that is used for tracking, controlling, organising and managing changes to software code. Version control serves as a safety net to protect the source code from irreparable harm.

DIFFERENCE BETWEEN GIT AND GITHUB:
GIT is a free, open source version control system tool that developers install locally on their PCs. It is tool that tracks changes in ones code and allow multiple people to collaborate on a project. It also provides features like branching, merging and history tracking. While;  GITHUB is a git repeository hosting services which offers all the distributed revison control and source code management (SCM) functionality of git. 

GITHUB ALTERNATIVES:
1. GitLab
2. Azure DevOps
3. Harness

DIFFERENCE BETWEEN GIT FETCH AND GIT PULL:
GIT FETCH command is used to retrieve the latest commit history from the remote repository which does not affect the local working directory. Git fetch enables yoy to continue editing files in your local working directory without having to merge  your code with updates from the remote repo.  
While;  GIT PULL command is used to fetch all changes from the remote resporitory to the current working directory. It automatically try to merge or rebase them into your current working direction. Git pull is suitable for quickly reflecting remote changes in the local branch with caution needed because it can lead to conflicts especially ehen working with multiple people.

GIT REBASE AND ITS COMMAND:
GIT REBASE is a command that is use to move or combine sequence of commits to a new base commit so that it looks like they have been created their branch from a different commit.
COMMAND: 
''' bash
git rebase <README>

GIT CHERRY-PICK AND ITS COMMAND
GIT CHERRY-PICK command is used to allow you apply specific commits from one branch to another, without merging the entire branch. 
COMMAND:
git cherry-pick <commit-hash>
git cherry-pick <commit-hash>
