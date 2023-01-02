## Creating a new repo
- create an empty 'test' directory in local machine
- cd to the directory
- create a GitHub repo 'test'

`echo "# test" >> README.md`  
`git init`  
`git add .`  
`git commit -m "first commit"`  
`git branch -M main`  
`git remote add origin git@github.com:mabalam/test.git`  
`git push -u origin main`  

# Adding contents to the directory

- add new files/folders or edit existign ones
git add .
git commit -m "commit message"
git push -u origin main

    
## Cheatsheet
- `git pull` sync any changes made on remote repo
- `git log --all --graph` all commits in a graph
    


## notes
- local machine and remote can be connected either via HTTPS or SSH (same either way)
	- For HTTPS needs token, for SSH need SSH key

*****************


## Add an existing project to git (local + remote) (did not work, may be try again)
- initialize the local project folder: 
    - `git init`
    - `git add .`
    - `git commit -m "commit message"`
- create a new remote repo on github
- `git remote add origin <repo url>`
- `git push origin main`

## Creating a new repo
- create a GitHub repo 'git-basics'
- create a local directory
- clone GitHub repo
	- `git clone <repo http url> <optional folder name>`
- make changes to the directory e.g.:
    - transfer files from other directory
    - create new files
    - make any changes locally
- staging/commits etc
	- `git add .`
	- `git commit -m "<commit message here>"`
- push to GitHub
	- `git push origin main`