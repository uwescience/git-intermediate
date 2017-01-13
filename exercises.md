*Exercise: local branch*

(a)

1. Initialize a repo
2. commit a file called `file.txt` with text `Parent commit` on the first line.
3. Create a branch my_experiment.
4. Switch to it.
5. Add a line with text `Feature commit 1` and commit the changes.
6. Merge the branch with master (remember you need to be on master to do that).
7. Delete the branch.

(b)

1. Create a branch another_experiment.
2. Add a line with text `Feature commit 2` and commit the changes.
3. Switch to master, and add a line `Improvement of master`, and commit the changes.
4. Now try to merge the another_experiment branch with master.

***You stumble into a merge conflict!***

(c)

1. Go to the file to select the version you want

2. Add and commit the file.

3. Delete the branch.

Remember to regularly use `git status`, `git log`,  and `git branch` to know where you are and what you have done.

*Exercise: local branch*

***What if you want to contribute to a repo which you are not collaborator to?***

*Exercise: forking*

(a) Submitting a separate file to a centralized repo.

1. Fork the repo.

2. Create a local copy of the fork
    - be careful how you use the git clone command.

2. Create a file named after your initials (vms.txt).

3. Commit the changes, and push to github.

4. Submit a Pull Request of your updated version.

5. Bring the changes from my version to your local copy
    - pull but from where?

Note: while a Pull Request is pending, everything that you push to github will be added to the pending PR!!!

(b) Modifying the same file in a centralized repo.

We will be working with the file [git-review.md](git-review.md).

    1. Remember your number.
    2. Respond to the corresponding question in your own words.
    3. Commit the changes to the file.
    4. Before you push check if your first Pull Request has been accepted: if not any new changes will be added to the existing Pull Request!!!
    5. Submit a Pull Request with the modified file.

***Did this activity cause some problems: why or why not?***


*Exercise: public branch*

Work in your fork.

1. Create a branch named: your_initials_branch.
2. Write more text in the file with your initials.
3. Push to the corresponding public branch.
4. Submit a Pull Request from the branch on your fork to the master of the repo from which you forked.

Note: in general it is good to pull every time before you push so that you are sure that your version is up to date and compatible with the main version. If there are conflicts you need to resolve them by hand.
