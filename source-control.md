* Prefer Git unless you have any oher strong reason to use somthing else.
* Keep your runnables on root of your repo.
* Have to main branches - prod (for production) and dev (development) branches.
* And other branches as required - hotfix-*  and feature-* 
* You NEVER commit directly on prod.
* If there are any severe bugs in prod, then you may checkout hotfix-* from prod, fix the issue and merge it back into prod.
* The only activity on prod branch is to pull from a stable dev or a hotfix-*.
* If you want to add a new feature, then you should checkout feature-* from dev, Implement the feature and merge it back to dev.
* The activities on dev should only pulling from feature-* and pulling from prod which has a hotfix-* merge.
* Avoid usage  of GUI tools. GUIs are great for code review. But always use git command line for committing and stuff.
* Try to user --no-ff to preserve branching history.
* We almost always write our new code at the end of the file. This will lead to merge conflict if all of us work on same part of file. Instead, try to write new codes other than the end of file. some where it is more appropriate. This will prevent merge conflict to an extent.
* It is always a good idea to have release notes with a diff of codes. Great for reviews.
