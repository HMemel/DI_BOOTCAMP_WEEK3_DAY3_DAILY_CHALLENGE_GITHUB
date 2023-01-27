********* Daily Challenge - Github ********

1 - Create a new github repository

2 - On your computer, create a new folder, and link it to your github repository

3 - In your local folder, create a file called planets.md with a list of the planets in the solar system. Markdown CheatSheet here and here

4 - Push this file to your repository

5 - Clone your repository to 2 separate locations.
I.e. Clone it to folder1 and clone it again to folder2. This will simulate 2 different developers working on the same project.

6 - Create 2 different branches, one in each of the local repos (folder1 and folder2).

7 - In each local repo (folder1 and folder2) update the code (differently) in the file planets.md.

8 - Push the file from one branch to github and merge to master. Then try to push the corresponding file from the other repo and merge it.

9 - Check out the conflict that you get, and fix it.


************ Some Recap *******************
Steps:

1 - Check if github is installed running the command git --version from terminal

2 - Install if necessary

3 - Create a GitHub account and login

4 - Create a new repository

5 - Make a new folder from command line using mkdir command (followed by the directory’s name)

6 - Go to your Github repository, and copy the link for cloning that repository

7 - Clone your GitHub repository to your computer from terminal with command: git clone {url to your repository}

8 - Create a new file on your computer within the cloned folder

9 - Add that file to GitHub with git add {filename} (can add all files using .)

10 - Commit git commit -m 'message

11 - Push to GitHub cloud with git push origin main


************** Creating A New Branch ******************

1 - Create a new folder totally unrelated to the other directory

2 - Clone the repository into the new folder

3 - View your current branch git branch

4 - Create a new branch git checkout -b {new branch name}

5 - Make changes in the new branch and then push them

6 - When you open the two branches in GitHub, you can compare the two versions, create a pull request, check if the two versions are compatible, and merge them