# Fetching Data
The file fetchdata.ipynb contains all fucntion for collection recent xx commits and the PRs related to them.
To run the code you have to do:
- [ ] Save you GitHub REST API access token to `token.secret` file (Delete aftwards or add *.secret to you .gitignore file)
- [ ] Specifiy the target repository and branch under `Target Repository Specification` Section
- [ ] Adjust the perpage and page count in `fetch_commits`(perpage max 100, the total commit you fetch is perpage times page count)
The fetching process generatly takse 1.25 seconds per commit 
- [ ] Chechk the \{Repository Name\}.json file and error.log for any error happened during the process


There is actually a local method by cloning the repository However it is not tested(See local.md)