# **Getting Started With GitHub; Part 1**

## **Table of Content**
[What is Github](#what-is-github)

[Github terms](#github-terms)

[Add a Repository project](#add-a-repository-project)

[Create file in a Repository](#create-files-in-a-repository)

[Create a Branch](#create-a-branch)

[Create a Pull Request](#create-a-pull-request)

[Merge a Pull Request](#merge-a-pull-request)

## **What is GitHub**
Github is a web-hosted Git repository which is a version control system that allows you to keep track of changes to your document. Git is an open source version that allows multiple users make separate changes to documents at the same time. Github allows numerous developers to work on one project at the same time therefore it is used for collaborative coding. Developers can write a code, build a project and track changes to the project. Github as version control system are used widely for things involving codes, but can also be used to version control images, documents, and other types of files.

## **Github terms**
**Repository** Also known as Repo`s are folders in which your project files and their version histories are stored. It is a data structure for storing documents including application source code. 

**Working Directory** is a directory of hierarchical file system which includes its files and subdirectories that is a dynamically associated with a git repository.

**Commit Changes** is a way of saving a change made to a file within a repo.

**Branch** is a workspace in which you can create a new similar file and make changes without affecting the original file. All files created on github are stored on a branch. The master branch is created by default but when you plan to change things you create a new branch and give it a descriptive name. The new branch is an exact copy of the original branch. When you make changes it only affects the new branch while the original branch stays intact. The changes can only affect the original branch when you commit and merge the changes back into the master or original branch.

**Merge** is done after a change to a branch of a repo has been approved or a pull request is approved. Developers can change source files in a branch but the changes are not released until they are committed. A pull command is issued. The code is reviewed and approved. The approved code is merged back into the main branch.

**Pull Request** is used to initiate the merging of branches in a way to capture changes. This a way to ask for the changes made to a branch to be reviewed and approved by other users before merging into another branch or main branch.

**Staging** which is normally referred to as staging area is an area where commits can be formatted and reviewed before completing the commit. So before a repo is committed to the main branch it is first sent to the staging area. 

## **Add a Repository project**
To add a new repository to your github. Go to the homepage of your Github, click on the `+` icon and select `New repository`. 

![Click to view Image](./images/github%2001.png)

A new window will open, enter the repository name, You can fill in the description box which is optional(this describes what the repo is all about). Select the `Initialize this repository with a README` check box. A README file is to describe the purpose of the project.
Select repo visibility whether `Public` or `Private`. When it is public it is visible on the web wen searched for by any random web user.

![Click to View Image](./images/github%202.png)

![Click to View Image](./images/github%203.png)

Click create Repository. The Repo is created and the homepage will be displayed.

![Click to View Image](./images/github%204.png)

## **Create files in a Repository**
Select the Repo where you wish to add files to. It will take you to the main branch

![Click to View Image](./images/github%205.png)

Click `Add file` and select `Create new file`. This will create a new file in the Repository.

![Click to View Image](./images/github%206.png)

Enter file name and its extension. example we want create a markdown file the file name is html and extension is *.md* therefore we have *html.md*. Add the lines of text or code to your file depending on the purpose of your file.

![Click to View Image](./images/github%2007.png)

Scroll down to page bottom and add description for you file and click `commit` to create your new file.

![Click to View Image](./images/gihub%208.png)

Your repository list shows that the new file that was created and added.

![Click to View Image](./images/github%209.png)

**You can upload files from your local computer** to your repository. To do this go to the repo you want to add the file to click `Add file` and select `Upload files`.

![Click to View Image](./images/github%2010.png)

A new page opens and you can either **Drag and drop files on the space** or **Choose your files** which will take you to your system file directories. 

![Click to View Image](./images/github%2011.png)

![Click to View Image](./images/github%2012.png)

when the files finishes uploading. Click `Commit changes`

![Click to View Image](./images/github%2013.png)

![Click to View Image](./images/github%2014.png)

Your file is then uploaded to your repository

![Click to View Image](./images/github%2015.png)

## **Create a Branch**
is a workspace in which you can create a new similar file and make changes without affecting the original file. All files created on github are stored on a branch. The master branch is created by default but when you plan to change things you create a new branch and give it a descriptive name.

When you created your repository a main branch was created. So to add a branch to your repository, open the repo by going to its main page and you will notice that it states it has just one branch which is the main branch.

![Click to View Image](./images/github%2016.png)

Go to the top of the github page locate the `main/branch` drop-down menu. Click the drop-down menu, type the name you want to give the new branch and click `Create Branch:` or click `Enter` on your Keyboard.

![Click to View Image](./images/github%2017.png)

![Click to View Image](./images/github%2018.png)

Now your Repo has two branches

![Click to View Image](./images/github%2019.png)

Any file that were in the `main branch` have now been copied to the the newly created branch, and any change made on the newly created branch will not be made on the main branch.


To add a file to the new branch is the same process for adding a file to a repo as discussed above.

## **Create a pull request**
When you create a new branch and you add files to the new branch, note that this files wont be added to the main branch. This means any change made on the new branch wont be added to the main branch. A `pull request` and `merge` must be carried out to apply this changes to the from the new branch unto the main branch. To create a pull request follow this process;

Firtsly add a file to the new branch using the add a file metthod explained above

In the new branch(Repo Update), click `Contribute` and select `Pull Request`

![Click to View Image](./images/github%2020.png)

Scroll down to the bottom of the page and there is **1 changed file** listed

![Click to View Image](./images/github%2021.png)

When you scroll up to the top and will see a box were there is a comparison between the main branch and new branch and next to it you see the phrase `Able to merge` which means there are no conflicts between the two branch.
You can add a comment(this is optional)
click `Create pull request`

![Click to View Image](./images/github%2022.png)

![Click to View Image](./images/github%2023.png)

The pull request is created and is ready to be merged.

## **Merge a pull request**
To merge a pull request to the main branch;
Click the `Pull Request` tab at the top of the Github home page which indicates any pull request. A list of pending pull request will be displayed if you have any. 

![Click to View Image](./images/github%2024.png)

Select the  pull request that you want to merge into its main branch. Click `Merge pull request` to accept the pull request and merge the updates. 

![Click to View Image](./images/githu%2025.png)

After clicking the `Merge pull request` it changes to `Confirm merge` button. Click that button to complete the merge.

![Click to View Image](./images/githuib%2025.png)

Now the pull request and merging are complete you can delete the new branch if you wish or keep for future usage. You can delete branch by clicking the `Delete branch`.

![Click to View Image](./images/github%2026.png)

Go to the main branch and check to see that the new file has now been added.
