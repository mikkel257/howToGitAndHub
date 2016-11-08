# How to create a local respository with git in Eclipse and afterwards link it to github.

## Content
* [Creating a local Repository](#to-create-a-local-respository-with-git-in-eclipse-you-will-have-to-do-the-following)
* [Linking an existing Repository to Github](#to-link-your-local-repository-with-github-you-will-have-to-do-the-following)* 
[Import a gitHub project to eclipse](#to-import-a-github-repository-into-eclipse-you-will-have-to-do-the-following)'
[Creating new brances](#to-create-a-new-branch-in-the-local-repository-you-will-have-to-do-the-following)
[Update a locale Branch](#to-update-a-local-branch-you-will-have-to-do-the-following)
[Merging branches](#to-merge-a-branch-with-another-you-will-have-to-do-the-following)
[Pushing to Github](#to-update-the-github-repository-you-will-have-to-do-the-following)



#### To create a local respository with git in Eclipse you will have to do the following

1. Create a java project.
2. Right click on the java project in package/project explorer.
3. Choose 'Team' and 'Share project'.
4. An new window opens.
5. Click create next to the repository option.
6. Now choose a name for the git repository. fx /Users/Mikkel/git/test.
7. Click Finish.
8. Click finish.
9. Now click on your java project in package/project explorer once.
10. Afterwards go to the git-staging window.
11. Select all unstaged changes.
12. Move them to staged changes.
13. Enter a commit messages. fx initial commit.
14. Click commit.
15. You now have a local git repository.

#### To link your local repository with Github you will have to do the following

1. Go to Github.com
2. Click on the + in the upper right corner and select 'New repository'.
3. Choose a name for your repository. fx test.
4. Choose a description for your repository - Optional.
5. Select a privacy setting (public or privat).
6. Click 'Create repository'.
7. Copy the link which end with .git.
8. Open Eclipse and go to the window Git repositories.
9. Open your local git repository.
10. Right click on remotes and select 'Create remote'.
11. Choose a name. Default is origin.
12. Click 'Ok'
13. Click 'Change' and paste the link.
14. Click Finish.
15. Click 'Save and push'.
16. Your local git is now linked with github.

#### To import a Github repository into Eclipse you will have to do the following

1. Go to Github.com.
2. Find the project that you want to import.
3. Click on the green 'Clone or download' button.
4. Copy the link.
5. Open Eclipse.
6. Go to the project/package explorer window.
7. Right-click and select 'Import'.
8. Open the 'Git' folder and select 'Projects from Git'.
9. Click 'Next' and select 'Clone URL'.
10. Enter the required information 'Host', 'Repository path', 'user' and 'password' and click 'Next'.
11. Select the branches that you want to import. and click 'Next'.
12. Click 'Next', 'Next' and 'Finish'.
  
#### To create a new branch in the local repository you will have to do the following

1. Open Eclipse
2. Go to the 'Git repositories' window.
3. Open your project -> branches -> local.
4. Select the branch that you want to create a new branch from. Fx the master branch.
5. Right click the selected branch.
6. Click 'Create branch'. 
7. Enter a branch name.
8. Click 'Finish'.

#### To update a local branch you will have to do the following

1. Open Eclipse
2. Go to the 'Git repositories' window.
3. Select the branch you want to update.
4. Update it.
5. Go to the 'Git staging' window.
6. Select all the files in the 'unstaged changes'.
7. Move them to 'Staged changes'.
8. Write a commit messages.
9. Click 'Commit'.

#### To merge a branch with another you will have to do the following

1. Open Eclipse.
2. Go to the 'Git repositories' window.
3. Select the branch (fx master) you want to be updated from another (fx myBranch).
4. Right-click the other branch (myBranch)
5. Select Merge.

#### To update the Github repository you will have to do the following

1. Open Eclipse.
2. Go to the 'Git repositories' window.
3. Select the project you want to be updated on Github.
4. Right-click the project and select 'Pull'. If you failed click 'Fetch' instead of 'Pull' you can correct your mistake by going to remote tracking and mergeing your master with the origin/master
5. Right-click again and select 'Push to Upstream'.
6. You have now updated the project on Github.
