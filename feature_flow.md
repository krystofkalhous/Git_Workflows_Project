### Feature Branch Workflow in Git

The core idea of the feature branch workflow is to avoid making direct updates to the main branch while creating features on independent branches.
This allow multiple developers to work on a feature without disrupting the main branch.
Due to this, the main branch will never contain broken code.

### The process for the developer
- Start in the latest main commit. (All feature branches must be created of the latest state of the project)
- Create a new branch and name it according to the feature being added.
- On the new branch, add, edit and commit changes.
- Once your feature is ready, push your commits to the central repository.
- Now your teammates can comment and approve the pushed commits.
- Finally create a merge pull request, making sure to resolve any issues and conflict before the final merge.
