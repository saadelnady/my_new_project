# Git-Task-Day2

<img src="https://phantom-marca.unidadeditorial.es/59b11b2e37be610929bf4634536d3d10/resize/660/f/webp/assets/multimedia/imagenes/2022/12/28/16721837440133.jpg" alt="Search TextInput" width="100%" height="" />

# Deleting a Branch:

# git branch -d test:

Use this command to safely delete the local branch 'test' after ensuring all changes are merged into the current branch.

# git branch -D test:

This command forcefully deletes the local branch 'test' without checking for unmerged changes. Use with caution to avoid data loss.
Removing a Remote Branch:

# git push origin --delete test:

This command removes the 'test' branch from the remote repository, effectively deleting it from the remote server.
Temporarily Saving Uncommitted Changes:

# git stash:

Temporarily save your uncommitted changes in a "stash" to switch to another branch without committing them.
Applying Stashed Changes:

# git stash pop:

Pop the most recent stash and apply those saved changes to your working directory. This action also removes the changes from the stash.
Getting a Specific Tag:

# git tag :

List all tags in your local repository, and specify the tag name (e.g., "1.7") to view a specific tag.
Deleting a Tag Remotely:

# git push origin --delete 1.7:

Delete the tag '1.7' from the remote repository. This action removes the tag from the remote server.
Deleting a Tag Locally:

# git tag -d 1.7:

Delete the local tag '1.7' from your local repository. This action removes the tag from your local environment.
