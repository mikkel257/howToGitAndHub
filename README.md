## How to create a local respository with git in Eclipse and afterwards link it to github.
**To create a local respository with git in Eclipse you will have to do the following**

1. Create a java project.
2. Right click on the java project in package/project explorer.
  1. Choose 'Team' and 'Share project'.
3. An new window opens.
  1. Click create next to the repository option.
  2. Now choose a name for the git repository. fx /Users/Mikkel/git/test.
  3. Click Finish.
4. Click finish.
5. Now click on your java project in package/project explorer once.
  1. Afterwards go to the git-staging window.
  2. Select all unstaged changes.
  3. Move them to staged changes.
  4. Enter a commit messages. fx initial commit.
  5. Click commit.
6. You now have a local git repository.

**To link your local repository with Github you will have to do the following**

1. Go to Github.com
  1. Click on the + in the upper right corner and select 'New repository'.
  2. Choose a name for your repository. fx test.
  3. Choose a description for your repository - Optional.
  4. Select a privacy setting (public or privat).
  5. Click 'Create repository'.
2. Copy the link which end with .git.
3. Open Eclipse and go to the window Git repositories.
4. Open your local git repository.
  1. Right click on remotes and select 'Create remote'.
  2. Choose a name. Default is origin.
  3. Click 'Ok'
5. Click 'Change' and paste the link.
  1. Click Finish.
6. Click 'Save and push'.
7. Your local git is now linked with github.

**To import a Github repository into Eclipse you will have to do the following**

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
  
  
Skriv noget om at lave nye branches og hvordan der opdateres.
Skriv også noget om hvordan man henter et github projekt, således at det bliver lokalt.
