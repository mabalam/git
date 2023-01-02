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

# Modifying existing directory

- add new files/folders or edit existing ones
`git add .`  
`git commit -m "commit message"`  
`git push origin main`

    
## Cheatsheet
- `git pull` sync any changes made on remote repo
- `git log --all --graph` all commits in a graph
    


## notes
- local machine and remote can be connected either via HTTPS or SSH (same either way)
	- For HTTPS needs token, for SSH need SSH key

