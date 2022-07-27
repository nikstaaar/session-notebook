
1. Create a new repository on GitHub.com.

2. Open Terminal.

3. Change the current working directory to your local project.

4. Initialize the local directory as a Git repository.

    ` git init -b main`

5. Add the files in your new local repository. This stages them for the first commit.

    ` git add . `

    [^1]: Adds the files in the local repository and stages them for commit. To unstage a file, use `git reset HEAD YOUR-FILE`.

6. Commit the files that you've staged in your local repository.

    `$ `git commit -m "First commit"'

    [^1]: Commits the tracked changes and prepares them to be pushed to a remote repository.

 7. At the top of your repository on GitHub.com's Quick Setup page, click  to copy the remote repository URL.

 8. Copy remote repository URL field

 9. In Terminal, add the URL for the remote repository where your local repository will be pushed.

    `git remote add origin  <REMOTE_URL> `

    [^a]:Sets the new remote

    ` git remote -v`

    [^1]: Verifies the new remote URL
    Push the changes in your local repository to GitHub.com.

    `git push -u origin main`

    [^1]: Pushes the changes in your local repository up to the remote repository you specified as the origin

10. Push the changes in your local repository to GitHub.com.

    `git push -u origin main`

    [^1]: Pushes the changes in your local repository up to the remote repository you specified as the origin