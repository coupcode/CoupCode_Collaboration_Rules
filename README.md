# CoupCode_Collaboration_Rules
A must read for all developers. Talks about how to collaborate, Coding practices and many more

# INSTRUCTIONS FOR ALL DEVELOPERS

# Git Best Practices for Team Collaboration
When you're the only member working a project and pushing code to any repo, Git can be very basic. Everything is just add, commit, push, and repeat the cycle.

### Clone the project
```sh
git clone <repo-name>
```

### Open the repo: cd REPONAME 
```
cd <project-name>
```

### Ensure you are on the main/master branch depending on the projects root branch
```
git checkout <main or master> 
```

### Ensure you are up-to-date with the main or master branch

Pull in any new code from the main branch: `git pull origin <main-or-master>`

Resolve any merge conflicts that may now be revealed

```
git pull origin <main-or-master>
```

### Create a new branch for your task(should be short and descriptive enough)
```sh
git checkout -b <BRANCHNAME>
```

### Open VS Code: 
```
code .
```

### Make all your edits
Add all your updates

```
git add .
```

### Commit your updates
```
git commit -m "[FILENAME] UPDATE"
```
`Example`
```
git commit -m "[README] Updated"
```

### Push to the branch. NB: Never push to the main or master branch

```
git push origin <BRANCHNAME>
```

## Make a pull request to merge with main branch
When you are done and your code is very clean, request a PR via the GitHub page to merge with the master branch. Request for a review for it to be merged

Make sure your code passes all tests.




