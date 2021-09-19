## Answers
> by Joanne

**1. What does git clean do?**
*Git clean is a convenience method for deleting untracked files in a repo's working directory. Untracked files are those that are in the repo's directory but have not yet been added to the repo's index with git add .*

**2. What do the -d and -f flags for git clean do?**
*Run ‘git clean -f’ to force untracked file deletion. Use ‘git clean -f -d’ to remove untracked directories*


**3. What git command creates a branch?**
*When you want to start a new feature, you create a new branch off main using git branch new_branch .*


**4. What is the difference between a fast-forward and recursive merge?**
*Recursive is the default merge strategy when pulling or merging one branch. Additionally this can detect and handle merges involving renames, but currently cannot make use of detected copies. This is the default merge strategy when pulling or merging one branch.*

*A fast-forward merge can occur when there is a linear path from the current branch tip to the target branch. Instead of “actually” merging the branches, all Git has to do to integrate the histories is move (i.e., “fast forward”) the current branch tip up to the target branch tip.*

**5. What git command changes to another branch?**
*Once created you can then use git checkout new_branch to switch to that branch.*


**6. How do you remove modified or deleted files from the working directory?**
*git rm is used to remove a file from a Git repository. It is a convenience method that combines the effect of the default shell rm command with git add . This means that it will first remove a target from the filesystem and then add that removal event to the staging index.*


**7. What git command deletes a branch?**
*Delete a branch with git branch -d <branch> . The -d option will delete the branch only if it has already been pushed and merged with the remote branch. Use -D instead if you want to force the branch to be deleted, even if it hasn't been pushed or merged yet.*


**8. What does the git diff command do?**
*Diff command is used in git to track the difference between the changes made on a file. Since Git is a version control system, tracking changes are something very vital to it. Diff command takes two inputs and reflects the differences between them.*

**9. How do you remove files from the staging area?**
*The git rm command does that, and also removes the file from your working directory so you don't see it as an untracked file the next time around.*

**10. How do merge conflicts happen?**
*A merge conflict happens when two branches both modify the same region of a file and are subsequently merged. Git can't know which of the changes to keep, and thus needs human intervention to resolve the conflict.*