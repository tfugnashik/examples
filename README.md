## Contribute with any of the Machine Learning code samples that you are interested in<br>

Have a look at CONTRIBUTING.md it has some ideas for examples. <br>
Fork this repo and clone it locally and you can start contributing to this repository via github workflow.
Some good code samples can be found at [examples](https://keras.io/examples/)


## A set of guidelines to help you during the contribution process.

### Step 1 : Find an issue 

Take a look at the Existing Issues or create your own Issues!
***
### Step 2 : Fork the Project 

##### A) fork 
<b>A fork is a copy of a repository. Forking a repository allows you to freely experiment with changes without affecting the original project.</b>
To fork a repository , click on top right corner fork button <br><br>
   ![image](https://github.com/tfugnashik/examples/assets/115561757/5af69008-32a4-40ad-aa02-37bccba10602)
   <br>

 Next, Keep the default options as it is and click on Create fork <br><br>
##### B) git clone 
To clone a repository click on code and copy the URL as shown below : <br> <br>
   ![image](https://github.com/tfugnashik/examples/assets/115561757/7be9e859-f80b-401e-8036-95cabe00da8f)

   open your git bash and type the command as given and to paste URL use shift+insert key <br><br>
  
   ![image](https://github.com/tfugnashik/examples/assets/115561757/8dae0fc8-476f-4089-9f19-3cde22954b3e) <br>
   
Fork this Repository. This will create a Local Copy of this Repository on your Github Profile. Keep a reference to the original project in upstream remote.
```
$ git clone https://github.com/tfugnashik/examples.git
$ cd examples.git
$ git remote add upstream https://github.com/tfugnashik/examples.git
```
#### If you fork the project, update your copy before working by:
```
$ git remote update
$ git checkout <branch-name>
$ git rebase upstream/<branch-name>
```
---
### Step 3 : Branch

#### To Create a new branch:
```
$ git checkout -b branch_name
```
It creates new branch. Switch to new branch 
***
### Step 4 : Work on the issue assigned
Work on the issue(s) assigned to you.<br>
Add all the files/folders needed.
After you've made changes or made your contribution to the project add changes to the branch you've just created by:
#### Add all new files to branch Branch_Name by:
```
$ git add .
```
***
### Step 5 : Commit 
#### To Commit give a descriptive message for the convenience of reviewer by:
```
$ git commit -m "type your message here"
```
***
### Step 6 : Work Remotely 
Now you are ready to push your work to the remote repository.
Once your work is ready and adheres to the project conventions, upload your changes to your fork:
#### To push your work to your remote repository :
```
$ git push -u origin Branch_Name
```
***
### Step 7 : Make a Pull Request
Go to your repository in browser and click on compare and pull requests. Then add a title and description to your pull request that explains your contribution.

Once your Pull Request has been submitted, it will be reviewed and merged.
***
### Need more help?
You can refer to the following articles:

[Forking a Repo](https://docs.github.com/en/get-started/quickstart/fork-a-repo) <br>
[Cloning a Repo](https://docs.github.com/en/desktop/working-with-your-remote-repository-on-github-or-github-enterprise/creating-an-issue-or-pull-request-from-github-desktop) <br>
[How to create a Pull Request](https://opensource.com/article/19/7/create-pull-request-github) <br>

