# RC SFA GitHub Topics
## GitHub Topics Overview
We are using GitHub Topics to organize our repos and allow them to be more easily searchable. When you add a GitHub repository to the [SFA GitHub Organization](https://github.com/river-corridors-sfa), review the [controlled vocabulary](https://github.com/river-corridors-sfa/RCSFA_GitHub_Organization_Guidance/blob/main/github_topics/README.md#controlled-vocabulary-of-topics) of "Topics" provided and add appropriate choices to your repository's Topic list (in settings). Using a controlled vocabulary will better facilitate searching across repositories through time, however you can also add additional Topics to your repo that are not listed in the controlled vocabulary. 
## What are GitHub Topics?
GitHub Topics are akin to keywords or tags, allowing you to search repositories using specific terms. When you conduct a search, you will see a list of repositories that have also chosen to list that term as one of their Topics. Topic formatting allows lowercase letters, numbers, and hyphens. You can include multiple Topics for each repository. 

You can choose to search within a repository, within an organization, or across all of GitHub. The more specific you make your Topic, the more restrictive the search will be. If we use "sss" instead of "rcsfa-sss", many extraneous repositories would show up in the search across all of GitHub if we were searching outside the SFA GitHub Organization. The required Topics are restrictive to encourage easier navigation within the SFA, however, you are welcome to also add broader topics if you would like your repository to be findable outside of the context of the SFA. 
## Why is the SFA using GitHub Topics?
Within a GitHub Organization, there is no way to organize or categorize repositories; each repo is listed under the river-corridors-sfa in a flat hierarchy. We are using topics to help group like-repos together. For example, every repo created under RC-4 gets the "rcsfa-rc4" Topic added. 
## How do you use GitHub Topics?
Below you will find required, recommended, and optional Topics. There are two required Topic categories: project element and project type. Any additioanl Topics are either recommended or optional. Be generous with adding Topics. If you think your repository is related to a Topic, feel free to add it. 
## Controlled Vocabulary of Topics
### Required Topics
- **Project Element** - Include at least one

Topic | Definition
--- | --- 
**rcsfa-rc1** | The repo is associated with the RC SFA Research Campaign 1 on cumulative impacts
**rcsfa-rc2** | The repo is associated with the RC SFA Research Campaign 2 on hydrobiogeochemical variability
**rcsfa-rc3** | The repo is associated with the RC SFA Research Campaign 3 on watershed disturbances
**rcsfa-rc4** | The repo is associated with the RC SFA Research Campaign 4 on multi-basin studies, including WHONDRS
**rcsfa-mm** | The repo is associated with the RC SFA multi-scale ModEx
**rcsfa-fy24renewal** | The repo is associated with the RC SFA FY 2024 science plan renewal

- **Project Type** - Include only one

Topic | Definition
--- | --- 
**rcsfa-manuscript** | The repo is associated with a specific manuscript
**rcsfa-resource** | The repo is associated with a resource that will be used by others (e.g. QAQC scripts, graphics, etc.)
### Recommended Topics
- **Study Code** - Include the relevant associated study codes.
	- See the associated [github_topics_StudyCodes.csv](https://github.com/river-corridors-sfa/RCSFA_GitHub_Organization_Guidance/blob/main/github_topics/github_topics_StudyCodes.csv) file to find the study code Topics to select from. If your study code is not on the list, see the FAQs below for how to include it. 
### Optional Topics
- **Calendar Year** - Include any years in which the data were collected, the lab work completed, the analyses run, and/or the year of publication. Be generous. 
	- Use the format `rcsfa-YYYY` (e.g., "rcsfa-2023")
- **Authors** - Include the names of anyone affiliated with the repository
	- Use the format `lastname-firstname` (e.g., "smith-john")
- Any additional Topics you wish to include
	- Prefix `rcsfa-` to any topic you want to be able to associate strictly with the SFA (e.g., `rcsfa-qaqc`)
	- Do not include `rcsfa-` if you would like your included topic to be discoverable outside of the scope of the SFA (e.g., "machine-learning")
## FAQs
- What do you do if your Study Code topic is not included in the guidance?
	- On the [RCSFA_GitHub_Organization_Guidance repo](https://github.com/river-corridors-sfa/RCSFA_GitHub_Organization_Guidance), click the "Issues" tab.
	- Click on the green "New issue" button on the right hand side.
	- Under "Title" write your issue (e.g., "new topic to add").
	- Under the "Leave a comment" section...
		- include the Topic you'd like to add. Recall Topic formatting allows lowercase letters, numbers, and hyphens. We recommend using hyphens to separate words over using camelCase.
		- include the definition of the topic.
	- On the right hand side, add the label "documentation".
	- Click the green "Submit new issue" button to complete your request.
	- You can now add your newly proposed topic to your own repository and the Data Management Team will update the list in the guidance. 
- What if it's not allowing me to add a topic?
	- If you don't have permission, reach out to the Repository Steward. If you are still having issues, reach out to the SFA Data Management Team. 
