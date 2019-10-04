# Merge conflicts
I believe most of you who have worked on remote and local repositories have atleast once stumbled upon a merge conflicts.
Merge conflicts are very common and countless dependind on your situation.
Today I am going to touch a few that I have across and how i solved it.

## fatal: refusing to merge unrelated histories
This common error occurs when you are committing a remote and local repository in parrallel with different stuff without merging. The result is that both repository have different history 
For example if I create a local repository and commit all my codes in it and then create a remote repository and put different stuff there in parallel.
Run this code to resolve this
```
git pull --allow-unrelated-histories
```