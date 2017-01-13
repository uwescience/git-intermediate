### Review of Version Control
----
git add, commit, push, pull

### Branches
----

*Exercise: local branch*

* Initialize a repo
    - commit a file called `file.txt` with text `Parent commit` on the first line.
* Create a branch my_experiment.
* Switch to it.
* Add a line with text `Feature commit 1` and commit the changes.
* Merge the branch with master (remember you need to be on master to do that).
* Delete the branch.

* Create a branch another_experiment.
* Add a line with text `Feature commit 2` and commit the changes.
* Switch to master, and add a line `Improvement of master`, and commit the changes.
* Now try to merge the another_experiment branch with master.

***You stumble into a merge conflict!***

### Merge Conflicts
----
Go through steps to resolve the conflict.


Possible Scenarios:
* two people add material at different places of the file
* two people change the same line in a document
* person A adds a line, person B deletes a different line

Quiz (on how two files get merged)

### Forks and Pull Requests
----------------------------------

***What if you want to contribute to a repo which you are not collaborator to?***

*Exercise: forking*

Use the repo importer to create a temporary copy of this repository for the purpose of the tutorial (change the name by adding the date). The students will practice contributing to this dummy repo, which could be deleted after the lesson. (This should be done before the lesson)

1. Show (best with two screens)
    - how to fork it, add a file, and submit a PR
    - how to review PR, discuss, request more details, and merge the PR.

2. Ask students to add a file to the repo named after their initials.

3. Try to merge all of them right away??? Stress that if their PR is pending and they push to a repo, the new commits will be automatically added to the PR

4. Ask all of them to work on modifying the same file.

    We will be working with the file [git-review.md](git-review.md).

    Assign a number to each participant and ask them to
    - respond to the corresponding question in their own words (if they have never seen the command they can google the answer but more important is their interpretation)
    - submit a PR with the modified file



***Did this activity cause some problems: why or why not?***

This was a very simple workflow in which you only work on master and all changes follow a line. But what if you want to work on different aspects of projects and we are not sure if in the end we will like our experiments to go into the main projects. It is still important to keep track of the changes so that we do not lose something important.


*Exercise: public branch*

Work in your fork.

* Create a branch named: your_initials_branch
* Write more text in the file with your initials
* Push to the corresponding public branch
* Merge the branch through github with the master of the repo from which you forked


### Navigating the Git Tree
----------------------------

### Reset, checkout, revert
---------------------------

### Rebasing vs. Merging
-------------------------
