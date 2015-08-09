# repos-check
Simple scripts which make easier (for ME;) working with multiple Git repositories stored in one directory.

Scripts:
--------
*`gstatus [-r] [-p]`*

List all Git repositories in current directory, with current branch name and number of tracked files to commit.

  `-p`  - add information about commits you haven't yet pushed to your remotes (slower)
  
  `-r`  - perform *git remote update* in each repo, display informations about commits to push AND pull (MUCH slower)

--

*`gup`*

Run *[git up](https://github.com/aanand/git-up)* in every Git repo residing directly in current directory.
