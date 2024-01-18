# GitHub Best Practices

The Data Management Team created this document to provide an overview for how to collaboratively work with GitHub repositories (also referred to as "repo") within the [River Corridor Science Focus Area (RC SFA) GitHub Organization](https://github.com/river-corridors-sfa). Below you will find guidance for getting started, managing, and collaborating using GitHub.

### How should I organize my repository?
- Recommended folder structures depend on project and collaboration needs. Reach out to the Data Management Team if you would like recommendations on how to structure your repository. 
### What should I include in my repo readme?
- Individuals who read your README should be able to understand the purpose and contents of your repo, how your repo is organized, and who to contact if they want to reach out.
- At a minimumn, the following information should be included: `Title`, `Summary`, and `Contact`.
### When should I commit changes?
- When collaborating, you should commit and push a change as soon as you're done making the edit. This will keep the main branch as up to date as possible and will reduce the likelihood of people working off of differing versions of the same file. 
- If you are making edits to several documents or reorganizing multiple files, consider making multiple commits. This creates a finer resolution version history and makes it easier for others to track both what and why changes were made within a repo. 
### When should I push/pull?
- You should pull right before you're about to make edits to a file. This ensures you will be working off the most up to date version. 
- You should also pull right before you commit. This again ensures you are committing your changes to the most up to date version. 
- You should push directly after you commit your changes. When you commit, you are sending your changes into the version control system on your local machine. Pushing then sends those changes up to GitHub for collaborators to be able to view and access. 
### When should I clone?
- You can clone a repo when you want to work on it directly from your local machine. This is useful if you are wanting to run anything in R or make large changes to any of the files. 
- If you are making small changes, such as updating text in a markdown file or to comments in a script, then you can also edit via the online GitHub web interface. 
### When should I branch? 
- There are a few reasons when you should branch; the differing methodologies vary based on project need and scope and you should discuss with your Repository Steward before branching.
- Branching is generally used when multiple people want to actively collaborate within the same repo.
  - You can branch when you want to work with others on the same file. This allows two people to make edits simultaneously and then merge them back into the main branch when edits are complete. If you are doing this, be sure to pull before you edit, pull before you commit, and then commit, push, and merge as soon as you're done editing. If changes between collaborators occur on different lines, then GitHub is usually able to merge edits back together seemlessly. However, if more than one person edits the same line, GitHub will return a "merge conflict". When this happens, you will be prompted to resolve the discrepency on your own. GitHub will show you where the merge conflict occured and you can go in and edit the line to determine what you want to save. 
  - You can also branch when you want to work with others on different files. Branching allows collaborators to have their own isolated workspace and it encourages parallel development. When using this method, be sure that any two people are never editing the same file. 
  - You can branch when you want to experiment without affecting the main working version. This works well when you have a functional script and want to add a brainstorm, draft, and develop a new feature. Creating this new feature off of the main branch ensures the version that currently works doesn't get altered until the new feature is confirmed to harmoniously integrate into the existing pipeline. If you are doing this, the main branch should generally not be changed until the other feature branch(es) are merged back in. 
### When should I fork?
- Forking is generally not recommended within the scope of RC SFA work. 
- You can fork when you want to use someone else's repo as a starting point to your own new idea or direction. Forking will make a personal copy of another person's repo so that when you make your own edits, it won't affect the original repo. This duplicated copy thus creates two repos; this is in contrast to branching, which maintains a single repository.
### When do I create a release?
- You should create a release when you have identified the static version of your repo that best represents how you want your repository to be associated with a Data Package. This release will create a human readable name associated with a particular commit, allowing you to easily reference a specific snapshot in your Data Package. 
