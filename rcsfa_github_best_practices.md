# GitHub Best Practices

The Data Management Team created this document to provide an overview for how to work with GitHub repositories (also referred to as "repo") within the [River Corridor Science Focus Area (RC SFA) GitHub Organization](https://github.com/river-corridors-sfa). Below you will find guidance for getting started, managing, and collaborating using GitHub.
## How to set up a repo within the river-corridor-sfa GitHub Organization

You should add your work to a GitHub repository within the `river-corridors-sfa` GitHub Organization when the contents of your repo are associated in any way with the RC SFA. Examples include, but are not limited to, creating figures for a manuscript, writing scripts to process data, and developing analyses. 

You can either create a new repository in the GitHub Organization, or transfer an existing repo to the GitHub Organizaiton. Directions can be found below:
- [Creating a new repo](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-new-repository) in a GitHub Organization. At step 4, select `river-corridors-sfa` as the Owner.
- [Adding an existing repo](https://docs.github.com/en/repositories/creating-and-managing-repositories/transferring-a-repository#transferring-a-repository-owned-by-your-personal-account) to a GitHub Organization. At step 4, select `river-corridors-sfa` as the New Owner.
### After you add (create or transfer) a repo to the GitHub Organization...
1. Name your repo with the following syntax: `rcsfa-[RC#]-[StudyCode]-[keyword]`.
	  - e.g. `rcsfa-RC3-SSF-fire_party`, `rcsfa-RC2-scaling_manuscript`
2. Add **Project Element** and **Project Type** Topics to your repo. Choose topics from the list found in [README_github_topics.md](github_topics/README_github_topics.md).
3. Write the README.md to include a `Title`, `Summary`, and `Contact`, and update to ensure it reflects the contents of the repo.
4. As the repository owner, identify a Repository Steward (this can be you, or you can delegate the role).
	- The Repository Steward is is the person who will organize the folder structure in the repo, ensure collaborators have access, manage the main branch, and champion any collaborations between branches and merge requests. 
### Manuscript Associated Repositories
If your repo is, or will be, associated with a manuscript, please reach out to the Data Management Team and read through the internally facing [How-to-Prepare-and-Publish-a-Manuscript-Associated-Data-Package](https://pnnl.sharepoint.com/:w:/r/teams/SubsurfaceBiogeochemicalResearchSFA/Shared%20Documents/General/SFA%20Data%20and%20Software%20Management/Data-Publishing/Manuscript-Data-Package/How-to-Prepare-and-Publish-a-Manuscript-Associated-Data-Package.docx?d=w3bafc8fcacca4b2cacf3d9e92a290a05&csf=1&web=1&e=MDW790) guidance document on SharePoint for more guidance.
## How to organize your repo

### Recommended folder structure
The recommended folder structure depends on project and collaboration needs. Reach out to the Data Management Team if you would like recommendations on how to structure your repository. 
### Tips for repo readmes
- Individuals who read your README should be able to understand the purpose and contents of your repo, how your repo is organized, and who to contact if they want to reach out.
- The following sections should be included: `Title`, `Summary`, and `Contact`.
## FAQs

### When do I commit changes?
- When collaborating, you should commit and push a change as soon as you're done making the edit. This will keep the main branch as up to date as possible and will reduce the likelihood of people working off of differing versions of the same file. 
- If you are making edits to several documents or reorganizing multiple files, consider staging and committing your changes in batches based on your reason for making each change. Making multiple commits creates a finer resolution version history and makes it easier for others to track both what and why changes were made within a repo. 
### When should I push/pull?
- You should pull right before you're about to make edits to a file. This ensures you will be working off the most up to date version. 
- You should also pull right before you commit. This again ensures you are committing your changes to the most up to date version. 
- You should push directly after you commit your changes. When you commit, you are sending your changes into the version control system on your local machine. Pushing then sends those changes up to GitHub for collaborators to be able to view and access. 
### When should I clone?
- You can clone a repo when you want to work on it directly from your local machine. This is useful if you are wanting to run anything in R or make large changes to any of the files. 
- If you are making small changes, such as updating text in a markdown file or to comments in a script, then you can also edit via the online GitHub web interface. 
### When should I branch? 
- There a few reasons when you should branch, but branching is generally used when multiple people want to actively collaborate within the same repo. The differing methodologies vary based on project need and scope and you should discuss with your Repository Steward before branching. 
- You can branch when you want to work with others on the same file. This allows two people to make edits simultaneously and then merge them back into the main branch when edits are complete. If you are doing this, be sure to pull before you edit, pull before you commit, and then commit, push, and merge as soon as you're done editing. 
- You can also branch when you want to work with others on different files. Branching allows collaborators to have their own isolated workspace and it encourages parallel development. When using this method, be sure that any two people are never editing the same file. 
- You can branch when you want to experiment without affecting the main working version. This works well when you have a functional script and want to add a brainstorm, draft, and develop a new feature. Creating this new feature off of the main branch ensures the version that currently works doesn't get altered until the new feature is confirmed to harmoniously integrate into the existing pipeline. If you are doing this, the main branch should generally not be changed until the other feature branch(es) are merged back in. 
### When should I fork?
- Forking is generally not recommended within the scope of RC SFA work. 
- You should fork when you want to make a personal copy of another person's repo so that when you make your own edits, it won't affect the original repo. Forking is generally advised when you don't plan to directly collaborate with the original repo's author and works well when you want to work with and/or contribute to an open-source project. 
- You can fork when you want to use someone else's repo as a starting point to your own new idea or direction. Note that when you branch, everyone is still working off a single repository. When you fork, however, you create a duplicated copy of the repository, thus creating two repos. 
### When do I create a release?
- You should create a release when you have identified the static version of your repo that best represents how you want your repository to be associated with a Data Package. This release will create a human readable name associated with a particular commit, allowing you to easily reference a specific snapshot in your Data Package. 




