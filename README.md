# sync-upstream
Bash script to sync a forked project with its upstream repository

## How to use:

1. Find a cool project you are willing to contribute to, for instance this one https://github.com/Juraci/swamp
2. Fork it!
3. Clone your forked repository
4. Copy this bash script to the root folder of that repository
5. bash sync-upstream <original-url> <branch-to-sync-to>
example: `bash sync-upstream git@github.com:Juraci/swamp.git master`
6. Create a branch and submit your changes by pushing it and opening a pull request in the original repository

All made with help from those links:
* [Fork a repo](https://help.github.com/articles/fork-a-repo/)
* [Syncing a fork](https://help.github.com/articles/syncing-a-fork/)
* [Using pull requests](https://help.github.com/articles/using-pull-requests/)
