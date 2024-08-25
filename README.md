# Git Assignment - TinaToronto - Aug 24, 2024
a. What is an issue?

[TL] - GitHub Issues are a way to track and manage the work needed to improve your projects. Each issue can represent a task, bug report, or feature request and can be assigned to team members, tagged with labels, and linked to milestones.

b. What is a pull request?

[TL] - A pull request is a proposal to merge a set of changes from one branch into another. In a pull request, collaborators can review and discuss the proposed set of changes before they integrate the changes into the main codebase.

c. Describe the steps to open a pull request?

[TL] - Once you've committed changes to your local copy of the repository, click the Create Pull Request icon.
Check that the local branch and repository you're merging from, and the remote branch and repository you're merging into, are correct. Then give the pull request a title and a description.
Click Create.

d. Describe the steps to add a collaborator to a repository (share write permissions)

[TL] - Under your repository name, click Settings. If you cannot see the "Settings" tab, select the dropdown menu, then click Settings. In the "Access" section of the sidebar, click Collaborators. Click Add people.

e. What is the difference between git and GitHub?

[TL] - The key difference between Git and GitHub is that Git is a free, open source version control tool that developers install locally on their personal computers, while GitHub is a pay-for-use online service built to run Git in the cloud. Git is a piece of software. GitHub is an online SaaS service.

f. What does git diff do?

[TL] - The git diff command helps you see, compare, and understand changes in your project. You can use it in many different situations, e.g. to look at current changes in your working copy, past changes in commits, or even to compare branches.

g. What is the main branch?

[TL] - The default branch name in Git is master . As you start making commits, you're given a master branch that points to the last commit you made.

h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?

[TL] - If you're working alone, it doesn't really matter. But if you want to do it "right", you'd create a branch for each feature you're working on.

The master branch will contain complete, working code. Then you'll have a branch which has all the changes required for whatever new feature/fix you're making... where the idea is once you have that feature/fix working properly (all tests pass), THEN you finally merge it to master.

So your master branch always contains functional, working code.

You do all your development/testing/trial&error on a branch until you get everything working correctly, THEN you create a PR and merge it.

Also, that way if you need to rollback a change, it's just a single commit (the PR merge) you have to rollback, you don't have to try to figure out which commit in the master branch was where you started making your changes.

Again, if you're the only one working on the repo, it doesn't really matter. But it's good to get in the habit of doing things the right way.
