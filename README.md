# Git_Workflows_Project
This is the final project for the course Version Control with Git

### Forking Workflow in Git

Forking workflow differs from other workflows that use a single "centralized" repository by having a server-side repository for every developer; those repositories are forked from the official repository.
This is most common with public open source projects.

---

<img src="fork-flow.png" alt="Forking Workflow">

*Source: https://docs.rhodecode.com/4.x/rce/collaboration/workflow-fork.html*

---

### The Benefits of Forking Workflow
- Contributers of the project may add, edit and commit changes without giving them write access to the official codebase.
- Only the project maintainer may push commits to the official repository.
- It provide a flexible way for large, organic teams to collaborate sercurely, that is including untrusted third parties.


## Summary

We summarized here **4 popular version control workflows**. 

1. **Centralized Workflow** - A single central repository is used, and all changes are committed directly to it.

2. **Feature Branch Workflow** - Each new feature is developed in its own branch, which is merged back into the main branch once complete.

3. **Gitflow Workflow** - A more complex workflow that uses multiple branches for feature development, releases, and hotfixes to manage the project lifecycle.

4. **Forking Workflow** - Developers create their own fork of the repository, make changes, and then submit pull requests to the original repository for review and integration.

Each of these workflows can be tailored to fit different project requirements and team structures. By understanding the advantages of each workflow, teams can select the one that best aligns with their *development practices* and *project goals*, *ensuring efficient and organized collaboration*.
