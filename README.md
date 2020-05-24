# Git Features - Branch, Checkout, Merge and Resolve
Used to explore the different features of git including branching.

##Branch a repo
Branching a git project allows you to have a separate version
of the same project so that you can develop without fear of
damaging the main project. (i.e) adding a new feature

changes made on a new branch are not made to the master branch.

## Checkout a branch

To switch branches on the local machine, the branch must be kept
checked out. (In terminal or command prompt, it's 'git' checkout
branchName') Branches must be committed and pushed separately
to the git repository.

Often times local branches are not synced to the git repo until
the dev is confident that the branch may be implemented.

## Merging a branch into another

Once the branched version is ready to be implmented into another
branch, often the master. (could be another branch)
The branch can be merged into a parent branch. The current checked
out version is the branch that is being merged into.

## Resolving Conflict

When two different versions of the same file are merged. (there
are commited changes to the same file in different branches)
Those conflicts must be resolved. Most IDEs have an inbuilt
tool to resolve conflicts but it can be done at the source code
level itself.

Note:
    The branch cannot make any further commits until all conflicts
    are resolved
    

