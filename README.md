**Task 1: Freestyle Project in Jenkins**

a) Create New Freestyle Project in Jenkins.

- Click on the new Item and write the item name and select freestyle project after it click on the ok
- once open the project add description, source code mangaement, build triggers[build periodically(H/10 * * * *)]
- create build and add the file or command
- example:- go inside the folder path where the file is present using "cd"
-           run the file like:- javac filename.java
- click on Apply and save
- click on build now

b) Pass few of your builds.

- Click on the new Item and write the item name and select copy from and write the file name and click on ok
- add description, source code management (None), Build Triggers[select after other projects are build and add the project name]
- select trigger only if build is stable
- create build and add the file or command
- example:- go inside the folder path where the file is present using "cd"
-           run the file like:- python filename.python
- click on Apply and save
- click on build now

c) Fail few of your builds.

- Click on the new Item and write the item name and select copy from and write the file name and click on ok
- add description, source code management (None), Build Triggers[select after other projects are build and add the project name]
- select trigger only if build is stable
- create build and add the wrong file path or make mistake in command
- example:- go inside the folder path where the file is present using "cd"
-           run the file like:- robot filename.robot
- click on Apply and save
- click on build now

**Task 2: Git Operations**

a) Create Repository in git with your terralogic credentials.

- create a new repository in git
- open the git bash in my folder 
- run git status to check the status
- add the files in staching area using "git add <File name>" or "git add ."
- commit the files using "git commit -m 'title'"
- check your branch using "git branch"
- change branch using "git branch -M <branch name>"
- connect you repo to you folder ("git remote add origin 'git repo path'")

b) Push your source code into your repository.

- push you code into git repo ("git push -u origin <branch name>" or "git push origin <branch name>")
