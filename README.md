# Introduction-to-Github

## GitHub

- A conceptual image of the GitHub Platform with layers from top to bottom: AI, Collaboration, Productivity, Security, and Scale.

- GitHub is a cloud-based platform that uses Git, a distributed version control system, at its core. The GitHub platform simplifies the process of collaborating on projects and provides a website, command-line tools, and overall flow that allows developers and users to work together.

- As we learned earlier GitHub provides an AI powered developer platform to build, scale, and deliver secure software. Let’s break down each one of the core pillars of the GitHub Enterprise platform, AI, Collaboration, Productivity, Security and Scale.
-----
## Collaboration
Collaboration is at the core of everything GitHub does. We know inefficient collaboration results in wasted time and money. We counteract that with a suite of seamless tools that allow collaboration to happen effortlessly.

Repositories, Issues, Pull Requests, and other tools help to enable developers, project managers, operation leaders, and others at the same company to work faster together, cut down approval times, and ship more quickly.
----
## Productivity
 Productivity is accelerated with automation that the GitHub Enterprise Platform provides. With built-in CI/CD tools directly integrated into the workflow, the platform gives users the ability to set tasks and forget them, taking care 
 of routine administration, and speeding up day-to-day work. This gives your developers more time to focus on what matters most: creating innovative solutions.
-----
## Security
GitHub focuses on integrating security directly into the development process from the start. GitHub Enterprise platform includes native, first-party security features that minimize security risk with a built-in security solution. Plus, your code remains private within your organization, and at the same time you are able to take advantage of security overview and Dependabot.

GitHub has continued to make investments to ensure that our features are enterprise-ready. We’re backed by Microsoft, trusted by highly regulated industries, and meet compliance requirements globally.
-----
## Scale
GitHub is the largest developer community of its kind. With real-time data on over 100M+ developers, 330M+ repositories, and countless deployments, we’ve been able to understand the shifting needs of developers and make changes to our product to match.

This has translated into an incredible scale that is unmatched and unparalleled by any other company on the planet. Everyday we are gaining more and more insights from this impressive community and evolving the platform to meet their needs.

In essence the GitHub Enterprise Platform focuses on the developer experience–it has the scale to provide industry-changing insights, collaboration capabilities for transformative efficiency, the tools for increased productivity, security at every step, and AI to power it all to new heights in a single, integrated platform.

# Now let’s get into the backbone of GitHub, repositories.
-----
## What is a repository?
- How to create a repository
- Adding files to a repository
- How to search for repositories
- Introduction to gists, wikis, and GitHub pages
-----  
## What is a repository?
 A repository contains all of your project's files and each file's revision history. It is one of the essential parts that helps you collaborate with people. You can use repositories to manage your work, track changes, store revision 
 history and work with others. Before we dive too deep, let’s first start with how to create a repository.
-----
## How to create a repository
You can create a new repository on your personal account or any organization where you have sufficient permissions.

Let’s tackle creating a repository from github.com.

1.   In the upper-right corner of any page, use the drop-down menu, and select New repository.

2.  Use the Owner dropdown menu to select the account you want to own the repository.

3.  Type a name for your repository, and an optional description.
  
4. Choose a repository visibility.

- Public repositories are accessible to everyone on the internet.

- Private repositories are only accessible to you, people you explicitly share access with, and, for organization repositories, certain organization members.

5. Click Create repository and congratulations! You just created a repository!

----
## How to add a file to your repository

Files in GitHub can do a handful of things, but the main purpose of files is to store data and information about your project.

Let’s review how to add a file to your repository.

But before we begin, it is worth knowing in order to add a file to a repository you must first have minimum Write access within the repository you want to add a file.

- On GitHub.com, navigate to the main page of the repository.

- In your repository, browse to the folder where you want to create a file.

- Above the list of files, select the Add file ᐁ dropdown menu, then click ᐩ Create new file. Alternatively, you can click ᐩ in the file tree view on the left.

- In the file name field, type the name and extension for the file. To create subdirectories, type the / directory separator.

- In the file contents text box, type content for the file.

- To review the new content, above the file contents, click Preview.

- Click Commit changes...

- In the "Commit message" field, type a short, meaningful commit message that describes the change you made to the file. You can attribute the commit to more than one author in the commit message.

- If you have more than one email address associated with your account on GitHub.com, click the email address drop-down menu and select the email address to use as the Git author email address. Only verified email addresses appear in this drop-down menu. If you enabled email address privacy, then [username]@users.noreply.github.com is the default commit author email address.

- Below the commit message fields, decide whether to add your commit to the current branch or to a new branch. If your current branch is the default branch, you should choose to create a new branch for your commit and then create a pull request.

- Click Commit changes or Propose changes.
----
## What are gists
Now that we have a good understanding of repositories, we can review gists. Similarly to repositories, gists are a simplified way to share code snippets with others.

Every gist is a Git repository, which you can fork and clone and can be either public or secret.

Public gists are displayed publicly where people can browse new ones as they’re created. Public gists are also searchable.

Conversely, secret gists are not searchable, but they aren’t entirely private. If you send the URL of a secret gist to a friend, they'll be able to see it.

To learn more about gists see the linked article in our Resources section at the end of this module titled, Creating Gists.
----
## What are wikis?
Every repository on GitHub.com comes equipped with a section for hosting documentation, called a wiki.

You can use your repository's wiki to share long-form content about your project, such as how to use it, how you designed it, or its core principles.

While a README file quickly tells what your project can do, you can use a wiki to provide additional documentation.

It’s worth a reminder that if your repository is private only people who have at least read access to your repository will have access to your wiki.

----
# Now, weill be reviewing the following components of the GitHub flow:
- Branches
- Commits
- Pull Requests
- The GitHub Flow

----  
## What are branches  
 Branches are an essential part to the GitHub experience because they're where we can make changes without affecting the entire project we're working on.
 Your branch is a safe place to experiment with new features or fixes. If you make a mistake, you can revert your changes or push more changes to fix the mistake. Your changes won't update on the default branch until you merge your 
 branch.
----
# Note:
- Alternatively, you can create a new branch and check it out by simply using git in a terminal the command would be git checkout -b newBranchName
----

# What are commits
As you might have noticed in the previous unit, adding in a new file into the repository, you needed to push a commit.

Let’s briefly review what commits are.

1. A commit is a change to one or more files on a branch. Every time a commit is created, it's assigned a unique ID and tracked, along with the time and contributor. Commits provide a clear audit trail for anyone reviewing the history of a file or linked item, such as an issue or pull request.
2. Within a git repository, a file can exist in several valid states as it goes through the version control process:
3. The primary states for a file in a Git repository are:
 - Untracked: An initial state of a file when it isn't yet part of the Git repository. Git is unaware of its existence.
 - Tracked: A tracked file is one that Git is actively monitoring. It can be in one of the following substates:
 - Unmodified: The file is tracked, but it hasn't been modified since the last commit.
 - Modified: The file has been changed since the last commit, but these changes aren't yet staged for the next commit.
 - Staged: The file has been modified, and the changes have been added to the staging area (also known as the index). These changes are ready to be committed.
 - Committed: The file is in the repository's database. It represents the latest committed version of the file.

-----
# What are pull requests?

 A pull request is the mechanism used to signal that the commits from one branch are ready to be merged into another branch.
 The team member submitting the pull request requests one or more reviewers to verify the code and approve the merge. These reviewers have the opportunity to comment on changes, add their own, or use the pull request itself for further 
 discussion.
 Once the changes have been approved (if approval is required), the pull request's source branch (the compare branch) is merged into the base branch.
 Now that we know of all the ingredients, let’s review the GitHub flow.
----
## The GitHub flow
The GitHub flow can be defined as a lightweight workflow that allows for safe experimentation. You can test new ideas and collaboration with your team by using branching, pull requests, and merging.

Now that we know the basics of GitHub we can walk through the GitHub flow and its components.

1. The first step of the GitHub flow is creating a branch so that the changes, features, and fixes you create don't affect the main branch.
2. The second step is to make your changes. We recommend deploying changes to your feature branch before merging into the main branch. Doing so ensures the changes are valid in a production environment.
3. The third step is to create a pull request to ask collaborators for feedback. Pull request review is so valuable that some repositories require an approving review before pull requests can be merged.
4. Next is the fourth step of reviewing and implementing your feedback from your collaborators.
5. The fifth step, once you’re feeling great about your changes now it's time to get your pull request approved and merge it into the main branch.
6. The sixth and final step is to delete your branch. Deleting your branch signals your work on the branch is completed and prevents you or others from accidentally using old branches.
    And that’s it, you’ve been through a GitHub flow cycle!



