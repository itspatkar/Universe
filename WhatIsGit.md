## What is Git?
Once upon a time, there was a developer named Linus Torwalds who developed a Linux kernel.
He is the only one who developed a kernel and published source code online.
He is updating and adding many features to the existing code.
While doing so, some things go wrong, and the kernel does not compile.
He doesn't know exactly which file was edited and which line code was changed by him because he's been doing it for a long time.
He felt that I needed something to keep track of my code and manage different versions of my code.
So it will be easier to fix bugs and move to the existing code if the updated code fails.
He also knew that he alone couldn't fix something if other developers also contributed to the kernel, making it more stable.

So he created a software tool which is called a version control system (VCS) and named it git.
But git is not only for single developers, that is, it's not centralised. Anyone can contribute, or say it's distributed among all.
That's why it's called a "distributed version control system."


## So, what is Git?
- It is a distributed version control system (VCS).
- It is used to track changes in the source code.
- It allows you to create different versions of code called as branches
- It allows multiple developers to work together.
- Other than this, Git offers many DevOps features.


## How is Git different from Github?
- Git is a version control system, and Github is a software company that offers a git service with online storage (repository) and other extra services.
- So basically, Github uses git.
- Many companies provide git services, including Github, GitLab, Bitbucket, Gitea, SourceForge, AWS CodeCommit, Cloud Source Repositories (Google), and others.


## How does Git operate?
- First we create a git repository. It is our main source code or project folder.
- Then we clone it locally on our computer.
- We make some changes in the code (in the working tree or unstage area).
- Then we add these changes to the index or stage area.
- We commit the changes with a commit message (comment of code changes).
- we push changes to the remote repo (the remote repo is the original repo - online).

**Note:**
- Commit is finalising changes. Whatever we commit shows in track history or logs.
- We can't commit without adding changes to the stage/index area (unstaged changes will not be commited).


## Branches
- We always work with branches, and the main branch is always the main branch by default.
- Whatever we commit will be uploaded on the main branch unless we create a new one and change it.

**For example,** <br>
An app can have a stable branch which will be used for updating users and a development/beta branch for adding new features and experiments.


## Clone vs Push vs Pull
- Cloning is for a new repo we're working on for the first time.
- Pushing is updating commit, i.e., uploading changes to our remote repo.
- Pulling is downloading changes from a repo if some other developer has pushed his commits.
