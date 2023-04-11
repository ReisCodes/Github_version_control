## Git, GitHub and Version Control

### What is Git and how it came about?

Git is a distributed version control system (VCS) that tracks changes in any set of computer files, 
usually used for coordinating work among programmers collaboratively developing source code 
during software development. Its goals include speed, data integrity, and support for distributed, 
non-linear workflows.

The Linux kernel is an open source software project of fairly large scope. During the early years of 
the Linux kernel maintenance (1991–2002), changes to the software were passed around as patches and archived files. In 2002, 
the Linux kernel project began using a proprietary DVCS called BitKeeper.

In 2005, the relationship between the community that developed the Linux kernel and the commercial company
that developed BitKeeper broke down, and the tool’s free-of-charge status was revoked. This prompted the 
Linux development community (and in particular Linus Torvalds, the creator of Linux) to develop 
their own tool based on some of the lessons they learned while using BitKeeper. Some of the goals of the new system were as follows:

- Speed

- Simple design

- Strong support for non-linear development (thousands of parallel branches)

- Fully distributed

Able to handle large projects like the Linux kernel efficiently (speed and data size)

Since its birth in 2005, Git has evolved and matured to be easy to use and yet retain these initial qualities. 
It’s amazingly fast, it’s very efficient with large projects, and it has an incredible branching system for non-linear development

### What is GitHub?

GitHub is a webservice the offers cloud-based Git repository hosting service. Essentially it is a way of storing 
your Git repository on the internet to enable individuals or other developers to use Git for version 
control and collaboration. 

### What is the Difference between them & How do they work Together?
GitHub uses Git to be able to host local repository's on the cloud. So GitHub uses Git but Git is 
on its own is a type of distributed version control system. So you can think of Git by itself as a 
local memory stick to save versions of work. Whereas GitHub is a memory stick you can save on the internet for
your collaborators to access your work also. 

![](github_git_diagram.png)

### Benefits of version control

- Remembers each version update.
- Provides history of all changes.
- Can go back to an earlier version.
- Supports collaboration
- Provides an off-site copy of data

### Main Git Commands

These are a few of the main Git commands used:

- `git init` (Initiates your local repository.)
- `git status` (Gives you a brief overview of files in the repository and their status.)
- `git add` (This stages files ready to commit in your repository to the branch you are working on)
- `git commit -m "....."` (This commits these files from the staging area to the branch.)

### Branches

#### What is a Git branch?

Branching means you diverge from the main line of development and continue to do work without 
messing with that main line.

#### Git merge

 

Merging is Git's way of putting a forked history back together again. The `git merge` command lets you take 
the independent lines of development created by `git branch` and integrate them into a single branch.

#### Pull Requests

A pull request within git is when a contributor/developer is ready to merge new changes from a branch 
to the main project repository. This is where the team can review the changes made and add follow-up commits
before these changes are merged into the main branch 

