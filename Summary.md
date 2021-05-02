# What is _**Git**_?
**Git** is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project called commit **Git** creates a snapshot of the file and stores a reference to it. If the file has not changed, **Git** only stores a reference to the already-stored identical version of it.

## The main states of a file in Git:
1. **Committed**: Data is securely stored in a local database.

2. **Modified**: File has been changed but not committed to the database.

3. **Staged**: Flagged a file’s changed version to be committed in the next snapshot.


# Remote Repositories
In order to collaborate on Git projects, you must interact with remote repositories, versions of a project residing online or on a network. You can work with multiple repositories, for which you can have read/write or read-only privileges. Teams can use remote repositories to push information to and pull data from.
## Seeing Your Remotes:
+ By running the _git remote_ command, you can view the short names, such as “origin,” of all specified remote handles.
+ By using git remote -v, you can view all the remote URLs next to their corresponding short names.

remote1 https://github.com/remote1/example (fetch)

remote1 https://github.com/remote1/example (push)
