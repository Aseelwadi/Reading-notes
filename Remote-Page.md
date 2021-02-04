# Remote Repositories
A remote URL is Git's fancy way of saying "the place where your code is stored." That URL could be your repository on GitHub, or another user's fork, or even on a completely different server.
___
* ## Creating remotes
You can use the git remote add command .
git remote add origin  <REMOTE_URL> 

* ## Seeing Your Remotes
By using < git remote>  and 
< git  remote -v >, you can view all the remote URLs next to their corresponding short names.

* ## Fetching
Fetching entails pulling data that you don’t have from a remote project.

Here is the command format:

git fetch [remote-name]

* ## Pushing
git push [remote-name][branch-name]

* ## Renaming/Removing Remotes
To rename a remote’s short name, use the git remote rename command.

### Remove

To remove a remote for whatever reason (e.g., a contributor has left the team, the server has moved), simply use the git remote rm command:

Example:

$ git remote rm jane





