# devops-project
interview questions:
1. What is Git?

A version control system that tracks changes in code and helps developers collaborate.

2. Difference between merge and rebase?

Merge: Combines branches with a new merge commit.

Rebase: Moves your commits on top of another branch (cleaner history).

3. What is a pull request?

A request to merge your branch into another branch, usually reviewed by others before merging.

4. How do you resolve merge conflicts?

Edit the conflicting file → choose correct changes → save →

git add .
git commit

5. What are Git tags?

Labels used to mark important points in history, like version numbers (v1.0, v2.0).

6. What is Git workflow?

A branching strategy for development, e.g.:
main → dev → feature branches → PR → merge.

7. Explain git stash.

Temporarily saves uncommitted changes so you can work on something else.

8. What is the use of .gitignore?

It tells Git which files or folders to ignore (logs, temp files, secrets, etc.).
