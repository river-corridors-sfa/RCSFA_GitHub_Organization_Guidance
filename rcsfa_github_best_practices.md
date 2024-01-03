# GitHub Best Practices

Date Created: 2024-01-02 by Bibi Powers-McCormack
Date Updated: 2024-01-02 by Bibi Powers-McCormack

The purpose of this document is to provide an overview for how to work with GitHub repositories within the RC SFA GitHub Organization. The three main sections (how to set up a repo, how to organize your repo, and expectations for collaboration) offer guidance for getting started, managing, and collaborating using GitHub. 
## How to set up a repo within the river-corridor-sfa GitHub Organization

You should add your work to a GitHub repo within the river-cooridors-sfa GitHub Organization if any of the following criteria are met: 
- [ ] ==FILL OUT CRITERIA==

You can either create a new repository in the GitHub Organization, or add an existing repo. Directions can be found below:
- Creating a new repo in a GitHub Organization
- Adding an existing repo to a GitHub Organization

When a new repository is added, we recommend the following actions occur:
- Follow ==x== guidance for how to name your repo.
- Follow ==x== guidance for what topics to add to your repo.
- Identify a Repository Steward; this is the person who will manage the `main` branch and champion any collaborations between branches and merge requests.  
## How to organize your repo

### Recommended folder structure

### Tips for repo readmes


## Expectations for collaboration

### When do I commit changes?
- When collaborating, you should commit and push a change as soon as you're done making the edit. This will keep the main branch as up to date as possible and will reduce the likelihood of people working off of differing versions of the same file. 
- If you are making edits to several documents or reorganizing multiple files, consider staging and committing your changes in batches based on your reason for making each change. Making multiple commits creates a finer resolution version history and makes it easier for others to track both what and why changes were made within a repo. 
### When should I push/pull?
- You should pull right before you're about to make edits to a file. This ensures you will be working off the most up to date version. 
- You should also pull right before you commit. This again ensures you are committing your changes to the most up to date version. 
- You should push directly after you commit your changes. When you commit, you are sending your changes into the version control system on your local machine. Pushing then sends those changes up to GitHub for collaborators to be able to view and access. 
### When should I clone?
- You can clone a repo when you want to work on it directly from your local machines. This is useful if you are wanting to run anything in R or make large changes to any of the files. 
- If you are making small changes, such as to text in a markdown file or to comments in a script, then you can also edit via the online GitHub web interface. 
### When should I branch? 
- There a a few reasons when you should branch, but branching is generally used when multiple people want to actively collaborate within the same repo. The differing methodologies vary based on project need and scope and you should discuss with your Repository Steward before branching. 
- You can branch when you want to work with others on the same file. This allows two people to make edits simultaneously and then merge them back into the main branch when edits are complete. If you are doing this, be sure to pull before you edit, pull before you commit, and then commit, push, and merge as soon as you're done editing. 
- You can also branch when you want to work with others on different files. Branching allows collaborators to have their own isolated workspace and it encourages parallel development. When using this method, be sure that any two people are never editing the same file. 
- You can branch when you want to experiment without affecting the main working version. This works well when you have a functional script and want to add a brainstorm, draft, and develop a new feature. Creating this new feature off of the main branch ensures the version that currently works doesn't get altered until the new feature is confirmed to harmoniously integrate into the existing pipeline. If you are doing this, the main branch should generally not be changed until the other feature branch(es) are merged back in. 
### When should I fork?
- You should fork when you want to make a personal copy of another person's repo so that when you make your own edits, it won't affect the original repo. Forking is generally advised when you don't plan to directly collaborate with the original repo's author. Forking works well when you want to work with and/or contribute to an open-source project. 
- You can fork when you want to use someone else's repo as a starting point to your own new idea or direction. Note that when you branch, everyone is still working off a single repository. When you fork, however, you create a duplicated copy of the repository, thus creating two repos. 
### When should I merge?

### What should I do when there is a merge conflict?

### When should I submit a pull request?

### When do I create a release?




