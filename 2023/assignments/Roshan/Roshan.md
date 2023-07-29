# <p align='center'>Git Workshop 2023 <p>

### <p align='center'>`Roshan Pandey`</p>

<p align="center">
    <a href="https://www.facebook.com/R.Pandey198/" target="blank"
    ><img
        align="center"
        src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg"
        alt="your_name"
        height="24"
        width="32"
    /></a>
    <a href="https://www.linkedin.com/in/rpandox/" target="blank"
    ><img
        align="center"
        src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg"
        alt="your_name"
        height="24"
        width="32"
    /></a>
    <a href="https://github.com/rpandox" target="blank"
    ><img
        align="center"
        src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/github.svg"
        alt="your_name"
        height="24"
        width="32"
    /></a>
       <a href="https://www.instagram.com/roshan_pandey097/" target="blank"
    ><img
        align="center"
        src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg"
        alt="your_name"
        height="24"
        width="32"
    /></a>

</p>

<br>

## <p align='center'>Learned Commands</p>

1.  `git init`

    **Description** :

        It is used to initialize git repository

    **Examples**:

        $ git init

2.  `git add <file_name>`

    **Description**:

        It is used to add files or changes in the working directory to the staged area.

    **Examples**:

        $ git add .gitignore hangman.c

3.  `git status`

    **Description**:

        It is used to view the status of the files in the repository

    **Examples**:

        $ git status

4.  `git commit `

    **Description**:

        It is used to commit the changes in the repository
        There is a flag -m which is used to write the commit message

    **Examples**:

        $ git commit -m "Initial commit"

5.  `git diff`

    **Description**:

        It is used to see the difference between the files in the working directory and the staging area
        There is a flag --staged which helps us to find the difference between the staged files and last commit
    **Examples**:

        $ git diff
        $ git diff --staged

6.  `git log`

    **Description**:

        It is used to display the previous commits in reverse order
        there is a flag -/<i/> where i is a any number this flag is used to show only that much amount of commit 

    **Examples**:

        $ git log
        $ git log -5

7.  `git restore <file_name>`

    **Description**:

        It is used to discard changes made to a specific file in the working directory and revert it to the state of the last commit

    **Examples**:

        $ git restore hangman.c

8.  `git reset`

    **Description** :

        It is used to Reset the remove all the files from the staged area
        it is useful when we mistakenly add a file in staged area 

    **Examples**:

        $ git reset

9.  `git help`

    **Description** :

        It is used to get general help of most used commands
        if we add a command names after the command it helps us get help regarding the given program

    **Examples**:

        $ git help
        $ git help remote

10.   `git remote`
	
 	
  **Description** :
     
    The git remote command lets you create, view, and delete connections to other repositories.

			
   **Examples**:

        $ git remote add dev1 https://github.com/rpandox/First-Contribution.git
        $ git remote rename dev1 developer1
        $ git remote remove developer1

11.  `git push`


**Description**:

    It is used to upload local repository content to a remote repository

     
**Examples**:

        $ git push developer1 main

12.  `git fetch`

**Description** :

    It is used to download commits, files, and refs from a remote repository into your local repo.
**Examples**:

        $ git fetch https://github.com/rpandox/First-Contribution.git

13. `git pull`


  **Description** :

    It is used to fetch and download content from a remote repository and immediately update the local repository to match that content.

    
  **Examples**:

        $ git pull https://github.com/rpandox/First-Contribution.git

14. `git clone`

**Description** :

    It is used to point to an existing repo and make a clone or copy of that repo at in a new directory, at another location.

**Examples**:

        $ git clone https://github.com/rpandox/First-Contribution.git

15.  `git branch`

***Description** :

        It is used to create rename switch publish delete a branch

**Examples**:

        $ git branch new-branch
        $ git branch -m old_branch_name new_branch_name
        $ git switch switching_branch_name
        $ git branch -d deleting_branch_name

16.  `git merge `

**Description** :

        It is used to combine two branches

**Examples**:

        $ git merge another_branch

17.  `git rebase`

**Description** :

        It is used to changing the base of your branch from one commit to another making it appear as if you'd created your branch from a different commit

**Examples**:

        $ git rebase branch_name

