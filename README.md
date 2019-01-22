# IRCA-RobotGrinder

### Development process

#### 1. Create a branch from master on computer
>\>>git checkout -b Myfeature

#### 2. Create same branch on github
>\>>git push -u origin Myfeature

#### 3. Do stuff on branch
>\>>vim main.cpp

> int main(argc, argv\*\*)\
>{\
>cout << "Robogrinder Win"!\
>}

#### 4. COMMIT AND PUSH OFTEN
>\>>git commit -a\
\>>git push

#### 5. Go to Manifold and test your changes
#### 6. If everthing works and you are done, go to step 7. If you broke something or you are not done go back to step 3.
#### 7. Initiate a pull-request
After you have finished and have tested your work, you will merge your branch with the branch called "integration".
follow these steps:
1. Got to this reposotory in GitHub 
2. In the "Branch" menu, choose your branch.
3. To the right of the Branch menu, click New pull request.
4. **\*IMPORTANT\*** Change the base branch to **"integration"** NOT "master."
5. Change the compare branch to your branch.
6. Type a title and description for your pull request.
7.  Click "Create pull request".

You can find more information on creating a pull-request here: https://help.github.com/articles/creating-a-pull-request/

Once you create a pull request the team lead will review it and test what you have done. The team lead will tell you if you need to make changes. \
Once the team lead says evertyhing is okay, you will close the pull-request using the following steps:
1. Under your repository name, click  "Pull requests".
2. In the "Pull Requests" list, click the pull request you'd like to merge.
3. Select "Merge pull request".
4. Type a commit message or accept the default message. Under the commit message box, click "Confirm merge".
5. If you are done with the branch, then you should delete it.

You can find more information on merging a pull-request here: https://help.github.com/articles/merging-a-pull-request/

Remember, **DO NOT** merge anything into master. Only the team lead will be allowed to do so. If you try it will not work anyway.

If you have any questions you can post them on the group chat.
