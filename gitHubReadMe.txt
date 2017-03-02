Push files to GitHub
====================

1.Create a new repository

2.Change the current directory to local project.

3.Initialize the local directory as a Git repository.

		$ git init
		
4.Add the files in your new local repository.

		$ git add .
		
5.Commits the tracked changes and prepares them to be pushed to a remote repository

		$ git commit -m "First Commit"
		
6.At the top of your GitHub repository's Quick Setup page, click  to copy the remote repository URL.

7.In Terminal, add the URL for the remote repository where your local repository will be pushed.

		$ git remote add origin remote-repository-URL
		
		$ git remote -v (Verifies the new remote URL)
		
8.Push the changes in your local repository to GitHub.

		$ git push origin master
