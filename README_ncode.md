# Building Ardupilot code for plane

## Step 1
Clone https://github.com/ds-u/ardupilot.git in local folder

## Step 2 (only to test that the clone was successful. CAN BE SKIPPED!)
1) Open the cloned repository folder.
2) Make a new text file and save it in the folder.
3) Open git shell -> enter 'git status' to see the new file that will be added in the new comit -> git add -A -> git commit -m "adding a file to repository"
![alt text](image.png)
![alt text](image-2.png)
![alt text](image-3.png)
4) enter 'git push origin' to add it to the origin repository

## Step 3
1) Open Visual Studio and make a new 'Empty Project' in the local folder(in which the git repo has been cloned)
2) Save and close Visual Studio and open the folder. 
3) Find the Visual Studio project folder that was just made, and copy all its files and paste them in the local folder (outside the Visual Studio project folder). Next, delete the project folder.
4) Open Visual Studio again and open the '.sln' file that was just copied.

## Step 4
1) 