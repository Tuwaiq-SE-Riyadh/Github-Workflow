# Github command 
## you can find below the steps for collaborating with git:
Git Forking Workflow
1. The project lead should create a new repository and push to Git
2. Other members should Fork 
3. Clone `git clone FORKED_REPO_URL`
4. Add upstream as a remote repository
   - `git remote -v `
   - `git remote add upstream Organization_URL`
   - `git remote -v` you should see 2 origin and 2 upstream remotes 
5. Create and checkout to a new feature branch
    - `git checkout -b Feature_Name`
6. Do some work on the new branch
7. Add your work to the staging area `git add .`
8. Save the staged changes via commit `git commit -m “”`
9. Push the new branch to origin g`it push -u origin Feature_Name`
10. Submit pull request
11. merge the changes 
12. Update the local master by pulling changes from Upstream master `pull upstream master`

Some Notes:
* Steps 1 to 4 should only be done once.
* Steps 1, 11, and 12 should only be done by the project lead.
* The rest of the steps are done by contributors/teammates.
