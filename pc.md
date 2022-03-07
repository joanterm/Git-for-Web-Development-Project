## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
A: It's a software that you download onto your computer and it allows you to write commands to manage your projects/code. It's a terminal that allows you to communicate with your github.

2. What is the difference between Git and GitHub?
A: Git is a software that is installed on your computer. Github is an online service (a website) that allows you to upload your code there for public sharing. We need Git to post code on Github. 

3. Why do we create a branch?
A: We create a branch off of main code so that we can modifiy that code and work on it without changing the original (main) code.  

4. What is the purpose of a Pull Request?
A: We create a pull request to let other team members know that our part of the code is done and ready for review.

5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
A: git switch main

6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
A: git fetch retrieves files from repository but does not make any changes, used to review
current updated files. Git merge lets you combine changes into a single branch. Git pull takes content from repository and updates your local repository to match the remotes content

7. What is a merge conflict?
A: When git isnt able to resolve differences between 2 code commits

8. How do you resolve a merge conflict?
A: Check the files and make changes, "git merge --abort" can undo the merge. Can
   also accept incoming change, accept both changes.