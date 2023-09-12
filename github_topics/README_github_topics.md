Date Created: 2023-08-30 by the SFA Data Management Team (Amy Goldman, Brieanne Forbes, Bibi Powers-McCormack)
Date Updated: 2023-09-11 by Bibi Powers-McCormack

## SFA GitHub Topics Overview
Any GitHub repository created under the SFA GitHub Organization should choose from the controlled vocabulary of topics provided and add appropriate choices to the repository’s Topics list. Using the exact wording and having a controlled vocabulary will facilitate searching for specific repositories as the number of repositories grows through time. You can add other topics in addition to the ones you have chosen from the controlled vocabulary.
## What are GitHub Topics?
GitHub Topics are akin to keywords or tags, allowing you to search repositories using specific terms. When you conduct a search, you will see a list of repositories that have also chosen to list that keyword as one of their Topics. You can choose to search within a repository, within an organization, or across all of GitHub. The format for a Topic is no spaces, only hyphens as special characters, and must start with a lowercase letter. You can include multiple Topics for each repository. 

The more specific you make your Topic, the more restrictive the search will be. If we use "sss" instead of "rcsfa-SSS", many extraneous repositories would show up in the search across all of GitHub if we were searching outside the SFA GitHub Organization. The required Topics are restrictive to encourage easier navigation within the SFA, however, you are welcome to additionally add broader topics if you would like your repository to be findable outside of the context of the SFA. 
## Why is the SFA using GitHub Topics?
Within a GitHub Organization, there is no way to organize or categorize repositories; each repo is listed under the river-corridors-sfa in a flat hierarchy. We are using topics to help group like-repos together. For example, every repo created under RC-4 gets the "rcsfa-rc4" Topic added. 
## How do you use GitHub Topics?
The SFA Data Management Team has created required, recommended, and optional Topics. Be generous with adding Topics. If you think your repository is related to a Topic, feel free to add it. There are two required topics. Be sure to add your associated project element and project type. Any additional topics are either recommended or optional. 
### Required Topics
- **Project Element** - Include at least one

Topic | Definition
--- | --- 
rcsfa-rc1 | The repo is associated with the RC SFA Research Campaign 1 on cumulative impacts
rcsfa-rc2 | The repo is associated with the RC SFA Research Campaign 2 on hydrobiogeochemical variability
rcsfa-rc3 | The repo is associated with the RC SFA Research Campaign 3 on watershed disturbances
rcsfa-rc4 | The repo is associated with the RC SFA Research Campaign 4 on multi-basin studies, including WHONRS
rcsfa-mm | The repo is associated with the RC SFA multi-scale ModEx

- **Project Type** - Include only one

Topic | Definition
--- | --- 
rcsfa-manuscript | The repo is associated with a specific manuscript
rcsfa-resource | The repo is associated with a resource that will be used by others (e.g. QAQC scripts, graphics, etc.)
### Recommended Topics
- **Study Code** - Include the relevant associated study codes
	- See the associated `github_topics_StudyCodes.csv` file to find the study code Topics to select from. If your study code is not on the list, see the FAQs below for how to include it. 
### Optional Topics
- **Calendar Year** - Include any years in which the data were collected, the lab work completed, the analyses run, and/or the year of publication. Be generous. 
	- Use the formatting "rcsfa-YYYY" (e.g. "rcsfa-2023")
- **Authors** - Include the names of anyone affiliated with the repository
	- See the associated `github_topics_Authors.csv` file to find the author Topics to select from. If an author name is not on the list, see the FAQs below for how to include it. 
	- Use the format "lastname-Firstname" (e.g. "smith-John")
- Any additional Topics you wish to include
	- Prefix "rcsfa-" to any topic you want to be able to associate strictly with the SFA (e.g. "rcsfa-qaqc")
	- Do not include "rcsfa-" if you would like your included topic to be discoverable outside of the scope of the SCA (e.g. "machine-learning")
## FAQs
- What do you do if your topic is not included in the guidance?
	- On the [RCSFA_GitHub_Organization_Guidance repo](https://github.com/river-corridors-sfa/RCSFA_GitHub_Organization_Guidance), click the "issues" tab
	- Click on the green "New issue" button on the right hand side.
	- Under "Title" write your issue (e.g. "new topic to add")
	- Under the "Leave a comment" section...
		- include the Topic you'd like to add. Recall is the format for a Topic is no spaces, only hyphens as special characters, and must start with a lowercase letter.
		- include the definition of the topic
	- On the right hand side, add the label "documentation"
	- Click the green "Submit new issue" button to complete your request
	- You can now add your newly proposed topic to your own repository and the Data Management Team will update the list in the guidance. 
- What if it's not allowing me to add a topic?
	- If you don't have permission, reach out to the SFA Data Management Team. 
- How do I search for a Topic?
	- There are multiple ways to use Topics as a search tool.
	- If you're in a repo that has a Topic of interest, click on it the Topic. If any public repositories exist, they will appear here. Any private repositories you have access to will also appear. Note that this search method restricts your search to the organization you are searching within. 
	- Use the main search bar to look for your Topic. After running the search, you will initially see all of the public repositories that include your search criteria (whether as a Topic or elsewhere in the repo) across all of GitHub. Use the "Filter by" section on the left side to further restrict your search criteria. 


