[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/8wgCKhpZ)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=19201889&assignment_repo_type=AssignmentRepo)


ANSWERS

1. 
Version control allows continuous saving of different states of your files in your working directory.
GitHub allows versioning of your work (your files) and hosting your project to make it accessible to everyone involved.
The integrity of the project is maintained because it’s hosted on GitHub, so it can’t be lost and is always available to team members.

2. 
To create a new repository on GitHub, you need to give it a name, choose whether it's public or private, and optionally add a README file.

3.
 The README file describes the project: its name, purpose, license, what it does, and how someone can contribute to improve it.

4.
A public Git repository is accessible to everyone.
A private Git repository is only accessible to invited collaborators.

Public repo
Advantage: Great for sharing code and open source projects.
Disadvantage: Anyone can see it.

Private repo
Advantage: Protected and accessible only by invitation.
Disadvantage: You must be invited to access it.


5.
For my first commit, I copied the remote repository URL, moved to my working directory with cd, then ran:

git clone <remote_url>

Next, I added my files to the staging area with:

git add .

Then I saved them locally with:

git commit -m "first save"

Finally, I pushed the changes to GitHub with:

git push -u origin main

Commits are snapshots—saves of our files at a specific point in the project.
They help track progress because we can list them using git log to view all project saves.

6.
Git branches help maintain a good workflow and task distribution among developers.
Each branch can represent a specific feature of the project.
You create a branch with:

git checkout -b branchName

After your work is done, you push it to the remote branch with:

git push origin branchName

Then you merge it with:

git merge branchName

7.
A Pull Request (PR) lets you propose changes from one branch to another.
It’s used to review the code before merging.
You open a PR on GitHub, discuss the changes, and if everything is okay, you merge it.

8.
A fork is a copy of a project on your GitHub account, while cloning is a copy of the project on your local machine.
Forks are used when you don’t have write access to a repository.
You can make changes on your fork and open a pull request to suggest modifications.

9.
Issues are used to report bugs, share ideas, or ask questions.
Project boards help follow project progress and track tasks.
These tools support collaboration by showing everyone what problems exist and what needs to be done.

10.

Best Practices:

Make commits with clear, short messages.

Save (commit) when your feature is working well.


Problems encountered:

Committing without pulling recent changes (git pull)

Merging the wrong branch

Not collaborating enough with the team


Solutions:

Make good commits

Make sure the feature works before saving

Communicate with the team

Regularly open pull requests.








# se-day-2-git-and-github
## Explain the fundamental concepts of version control and why GitHub is a popular tool for managing versions of code. How does version control help in maintaining project integrity?

## Describe the process of setting up a new repository on GitHub. What are the key steps involved, and what are some of the important decisions you need to make during this process?

## Discuss the importance of the README file in a GitHub repository. What should be included in a well-written README, and how does it contribute to effective collaboration?

## Compare and contrast the differences between a public repository and a private repository on GitHub. What are the advantages and disadvantages of each, particularly in the context of collaborative projects?

## Detail the steps involved in making your first commit to a GitHub repository. What are commits, and how do they help in tracking changes and managing different versions of your project?

## How does branching work in Git, and why is it an important feature for collaborative development on GitHub? Discuss the process of creating, using, and merging branches in a typical workflow.

## Explore the role of pull requests in the GitHub workflow. How do they facilitate code review and collaboration, and what are the typical steps involved in creating and merging a pull request?

## Discuss the concept of "forking" a repository on GitHub. How does forking differ from cloning, and what are some scenarios where forking would be particularly useful?

## Examine the importance of issues and project boards on GitHub. How can they be used to track bugs, manage tasks, and improve project organization? Provide examples of how these tools can enhance collaborative efforts.

## Reflect on common challenges and best practices associated with using GitHub for version control. What are some common pitfalls new users might encounter, and what strategies can be employed to overcome them and ensure smooth collaboration?
