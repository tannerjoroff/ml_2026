Git add is what adds the files to the staging area and sets them up to be committed.

Git commit is what saves the change to the local file and acts as the newest and most up to date version of the file. It also saves a snapshot of what the entire directory looked like at that moment.

Git push pushes the comitted files and changes that have been made to a remote repository so other people can look at your code and files. 

A branch is useful to do work in a directory that is basically like a test. I want to make edits away from the main branch that has my working code, so the tests and experiments and debugging doesn't mess anything else up. Merging is basically just adding those edits from the one branch onto the other. A rebase is replaying all of the edits you made on one branch onto another so the commit history becomes cleaner and more linear. Instead of a 3 way merge everything fast forwards. Rebase also makes changes one commit at a time while merge merges everything at once.