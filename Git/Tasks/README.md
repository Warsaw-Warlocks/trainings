# GIT Tasks

## Simple introduction
1. Clone this repository;
2. Create branch named YOURNAME_DATE;
3. Create commit with additional URLS / Things you found about github;
4. Add another commit with 1 new idea in main readme file for Git training;
5. Create one more commit with Your directory within this task, in this directory put two or more text files with some example text / code;
6. If you want try adding one more file to your directory, this time, try using git commit --amend 
7. Push your branch to repository;
8. Create pull request for your branch, and tag Me(michalmietlinski) to do review;
9. In pull request include information about what you did, and try adding some tags;

## Detached head
1. Set remotes for origin / upstream (or check if you have them);
2. Checkout remote branch - can be master;
3. Try to add some valuable content (or just work with your directory), and try to push to branch;
You can try to change branch before or after making a commit, but see what happens if you want to checkout to different branch, after making a commit on detached head;

## Resetting changes
1. Pull recent changes;
2. Make new branch (local);
3. Make changes;
4. Try resetting single file from command line;
5. Try resetting all changes within directory from command line;
6. Checkout master again;
7. Delete your temporary local branch using command line;

## Merging branches
1. Create new branch;
2. Add changes to your directory content and commit - you can split it into multiple commits;
3. Checkout master;
4. Create and checkout new branch;
5. Add different changes to your directory - you can split those into different commits as well;
6. Try merging those two into one, and push that one into repository, make a Pull Request;

## Cherry picking
1. Create new branch;
2. Add Changes to documentation (links, comments, ideas)
3. Commit changes:
4. Create and checkout new branch;
5. Cherry pick that commit to your new branch;
6. Push to repository;
7. Create Pull Request

## Using GitK
1. Checkout branch gitK_test
2. Add one commit with some made up data in gitKTest directory file GitKHistory;
3. Use GitK to view history and see the differences in file!

## Using Diff:
1. Checkout new branch;
2. Modify one of text files with irrelevant content - don't change anything in any Readme or real task;
3. Check your changes using git diff;
4. Compare your changes with master using git diff;
5. Compare branches - your new branch with master - using... you guest it - git diff;
6. Checkout master;
7. Delete your branch

## Amend
1. Checkout new branch (local)
2. Create changes to one of irrelevant text files;
3. Commit changes within branch;
4. Git log your changes - see your new commit/commits
5. Push to remote depository;
6. Create additional changes to those files;
7. Use git commit --amend to change name of the commit and add those changes;
8. Push amended commit to remote (this might be tricky, learn about force!)
9. Check you history using git log;
10. Check commit history on github;
11. Remove your branch from local and remote;

## Making use of gitignore;
1. Create new local branch;
2. Create directory within Git dir - it's name should be your nick;
3. Create directories perm, and hidden within your own dir;
4. Check if gitignore exists, if not - create it and add your hidden directory to it;
5. Commit those changes;
6. Push to remote;
7. Create a PR;
8. Remove local branch(Do not remove upstream branch!)
