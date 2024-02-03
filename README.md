# Branching-strategy
This is a test repository for experimenting with version control branching strategies.


## Git Flow
The Git Flow branching strategy is a popular branching strategy that is used by many development teams. It is a great branching strategy for teams that are working on a project that has a regular release cycle. The Git Flow branching strategy is based on the master branch and the develop branch. The master branch is used to store the production code, and the develop branch is used to store the code that is being developed. The Git Flow branching strategy also uses feature branches, release branches, and hotfix branches.

### Feature Branches
	Feature branches are used to develop new features for the project. When a new feature is being developed, a new feature branch is created from the develop branch. The feature branch is used to develop the new feature, and when the feature is complete, the feature branch is merged back into the develop branch.
	
### Release Branches
	Release branches are used to prepare the code for a new release. When the code is ready for a new release, a new release branch is created from the develop branch. The release branch is used to prepare the code for the new release, and when the code is ready, the release branch is merged into the master branch and the develop branch.
	
### Hotfix Branches
	Hotfix branches are used to fix bugs in the production code. When a bug is found in the production code, a new hotfix branch is created from the master branch. The hotfix branch is used to fix the bug, and when the bug is fixed, the hotfix branch is merged into the master branch and the develop branch.

### Git Flow Commands
	```	
	# Initialize a new git repository		
	
	- git init 
	
	# Create a new feature branch
	
	- git checkout -b feature_branch_name
		
	# Create a new release branch
	
	- git checkout -b release_branch_name

# Create a new hotfix branch

	- git checkout -b hotfix_branch_name

```