# Version Control

Version Control is also known as Source control. It is the practice of tracking and managing changes to software code.  
A Version Control software keeps track of every modification to the code in a special kind of database and if a mistake is made, developers can compare earlier versions of the code to help fix the mistake.  
The primary goals of version control include tracking changes, facilitating collaboration, and providing a history of the project's development.  
Version control systems are of three forms:

1. Local version control
2. Central version control
3. Distributed version control

Some popular version control systems and tools include:

- Git
- Subversion (SVN)
- Team Foundation Server (TFS)
- Mercurial

# Difference between Git and Github

Git is a distributed version control system for tracking changes in the source code during software development. It is designed for coordinating work among programmers and to manage the history and versions of the source code. Git is maintained by Linux.  
while  
GitHub is a web-based platform for Git repository hosting service, which offers all of the distributed revision control and source code management functionality of Git. It also has its own features such as social networking for developers and provides tools for collaboration. GitHub is maintained by Microsoft.

You can use Git without GitHub, but you need Git to use GitHub.

# 3 other github alternatives include:

1. GitLab
2. BitBucket
3. SourceForge

# Difference between git fetch and git pull

git fetch is used to fetch all changes from the remote repository to the local repository without bringing the changes into the working directory i.e. it does not automatically merge or apply those changes to your working branch.

git pull is a combination of two actions: **git fetch** and **git merge**. It used to fetch changes from a remote repository which it then automatically merges it into the working branch.

# git rebase

git rebase is used to modify the commit history of a branch. It allows one to reapply a series of commits onto a different base commit. The primary purpose is to maintain a cleaner, straightforward and easy to understand commit history.  
**command:**
git rebase source_branch

# git cherry-pick

git cherry-pick is used to apply a specific commit from one branch to another branch in the repository. It is a way of selecting individual commits and copying them to a different branch, independent of the commit history. It is useful for undoing changes.  
**command:**
git cherry-pick <commit-hash>
