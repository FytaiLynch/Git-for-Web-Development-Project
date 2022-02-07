## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
- Git is an open source control system designed to handle projects.

2. What is the difference between Git and GitHub?
- GitHub is hosted in the cloud and is a GUI created for devs while git is a command line tool and installed locally.

3. Why do we create a branch?
- We create a branch in order to branch off from the main repository and make changes/do testing that won't directly affect the main file.

4. What is the purpose of a Pull Request?
- The purpose of a pull request is for you to notify to the owner of the repository that you've made some changes and you'd like for them to pull those changes from your fork.

5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
- git switch

6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
- git fetch command gets changes from repository 
- git pull command fetches changes and merges those changes
- git merge command integrates changes from another branch

7. What is a merge conflict?
- A merge conflict happens when two branches have made edits to the same line in a file.

8. How do you resolve a merge conflict?
- There are a number of ways to resolve a merge conflict. You could use git checkout to undo the changes made to the file. git reset --mixed to undo changes to the working directory. git merge --abort to exit the merge process and return it back to the state before merging began. git reset can be used at the time of the conflict to reset the conflicted files to their original state.