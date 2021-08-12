# 📢 Git Session-1

Hey there, welcome to the Git Session-1 documentation. We have compiled the contents on Git and Github for you, so get a step closer to your first open source contribution.

## Table of Contents

| # | Topic |
| :-------: | :-------:|
| 1 | [Version Control System (VCS)](https://github.com/Open-Source-Community-VIT-AP/OSC-Talks/tree/main/OSC-Talks-Session-1#-version-control-system-ever-heard-of-it-) |
| 2 | [Distributed Version Control System (DVCS)](https://github.com/Open-Source-Community-VIT-AP/OSC-Talks/tree/main/OSC-Talks-Session-1#-distributed-version-control-system-dvcs-and-git) |
| 3 | [Life with Git](https://github.com/Open-Source-Community-VIT-AP/OSC-Talks/tree/main/OSC-Talks-Session-1#-life-with-git) | 
| 4 | [Getting your hands dirty with Git](https://github.com/Open-Source-Community-VIT-AP/OSC-Talks/tree/main/OSC-Talks-Session-1#%EF%B8%8F-getting-your-hands-dirty-with-git) |
| 5 | [Some advanced git commands](https://github.com/Open-Source-Community-VIT-AP/OSC-Talks/tree/main/OSC-Talks-Session-1#some-advanced-git-commands) |
| 6 | [Contributing using two Features of GitHub](https://github.com/Open-Source-Community-VIT-AP/OSC-Talks/tree/main/OSC-Talks-Session-1#contributing-using-two-features-of-github) |
| 7 | [Git in a Nutshell](https://github.com/Open-Source-Community-VIT-AP/OSC-Talks/tree/main/OSC-Talks-Session-1#-git-in-a-nutshell) |
| 8 | [Resources](https://github.com/Open-Source-Community-VIT-AP/OSC-Talks/tree/main/OSC-Talks-Session-1#-resources-on-git-and-github) |

## 🔧 Version Control System, Ever heard of it ?

Consider you are in a project and there constant changes in codes like addition of new modules, fixing of existing bugs, removing of un-necessary or outdated options then, sometimes due to some mistakes, the product goes unstable. then if you have the old code of your project, somewhere(Maybe Cloud/ Secondary Storage Devices) and you can go 
back to the last stable version, it would be very much helpful to you. And this concept is known as version control.

We have different versions of Version Control System, but git is the most popular version control system: 
- Git 
- Mercurial
- Apache Subversion System 
- Monotone
- Bazaar


## 🔧 Distributed Version Control System (DVCS) and Git

The truth is, Git is a distributed version control system. Distributed Version Control System is a type of version control system, where the complete code/files in the repository
including its full history of different versions, is shown on every developer's computer. Using git, a user can make changes to an entire repository on their local system and update it to the server when network is available. Git asks you about the changes you make and stores them as log files, this ensures that no changes can be made without git knowing it so there will not be any problem with managin your previous version of the repositories.

## 🔧 Life with Git

Git supports both :
  1. Command Line Interface (CLI Mode)
  2. Graphical User Interface (GUI Mode)

Guess what: Most Developers Prefer CLI Mode.

### ❔ Why do we even need Git?

  Here are some things to consider about git:
  - Git keeps track of changes made to a file.(makes note of different versions of the same file)
  - It also keeps a note of all the files that are there inside a project
  - Git can compare and analyse different codes with the help of `diff` tool.
  - You can publish your changes offline in your local repository and update it to the server(GitHub) later, so yeah git lets you finish your work even if you are travelling and       have no access to the internet.
  - Every change you make is known to git, the verification of the files is done by decoding the hash codes in your commit.
  
    ***Fact: Every commit is denoted by a unique hash code.***
  
  This is not the end of how git makes your life easier but yeah we won't have enough space for other contents if we continued stating other features of github.
  
  Here is a secret 🤫, checkout [features of git](https://www.geeksforgeeks.org/git-features/).
  
### ⚙️ Getting your hands dirty with Git
  
  This section covers some basics and enough knowledge on how to use git. To work with git or github, you need to have either a local repository or a remote repository.
  
  #### Local Repository ❔
  
   - A local clone of the remote repository which can be done by cloning the remote repository using the `git clone` command, don't worry we will explain more in detail soon.
  
  #### Remote Repository ❔
  
   - A remote repository is the repository hosted on github and it can be cloned and will be accessible to others if the repository is public.
  
  #### Public Repository ❔
  
   - The repository that is open to public to see and make contributions freely. It's open to everyone.
  
  #### Private Repository ❔
  
   - The repository that is not public and has lot of restrictions handled by the owner of the repository. To make a contribution, you need to ask the owner to give you access.
   Note that private repositories are not visible to public, so you can create a private repository if you are working on a secret project 😜.

  Before we go further we suggest you to download the Git CLI version, checkout [resource](https://github.com/Open-Source-Community-VIT-AP/OSC-Talks/tree/main/OSC-Talks-Session-1#-resources-on-git-and-github) section for the download link.
  
  #### Configuring Git:

  1. Open Your CMD/ git bash shell
  2. Type the command:     
      ```shell
        git config --global user.name "YOUR GITHUB USER NAME"
        git config --global user.email "EMAIL Address Associated with your github Account"
      ```
      These commands will let the locally installed git know that you are person `xyz` with email `xyz@email.com`. Yeah, now your git client is associated with your account.
      
  #### Some Basic Terminal Commands
  
   Some CMD Commands that you may need for switching directories, creating folders,creating files, opening files,deleting files, deleting directories 
    
  ```cmd

      1. cd Path_Of_Directory        (It changes the current working directory to the path mentioned by you)
      2. cd..                        (It Goes Up by one directory)
      3. mkdir Name_Of_Folder         (It Creates a new folder with the name mentioned by you)
      3. echo >> FileName.FileType    (It Creates a file, with the type/format specified by you)
      4. notepad FileName.FileType    (Opens the file specified by you in the notepad)
      5. rm FileName.FileType         (Deletes the file mentioned by you)
      6. rmdir PathOfTheDirectory     (Deletes a particular folder/directory that was specified)

  ```
      
  #### Working with git on your system:
  
  - #### 👉🏻 Initialization:
  
   First you need to create a local repository, so create a new folder ... now open your command prompt/terminal and migrate to a folder where you want to create a repository.

  > Command:  `git init`
  > 
  > This command will initialize a empty github repository

  - #### 👉🏻 Checking Git-Status:

  To check the git status

  > command: `git status`
  >
  > It will display on which branch you are and say the status of the files in that repo.
  >
  > It will display whether you need to update any files or not.

  - #### 👉🏻 Staging:
  
  Before publishing your changes(Commiting), your files should be added or staged. In short, git tracks the staged files for modifications.
  
  > command:   `git add <filename>`
  >
  > This command will add the file to git's staging directory and hence tracks changes made to the specific file.
  > 
  > Another command: `git add *` (if you put * symbol, all the files will be added)
  
- #### 👉🏻 Committing:

When you commit, git takes a snapshot of the current status of the file and saves it to the git logs. Committing saves your changes permanently.
> Command: `git commit -m "short commit message"`
>
> This command lets you commit with short commit message.
>
> Command: `git commit`
> 
> This command lets you commit with a long commit message. To run this command, you must [set the default editor](https://git-scm.com/book/en/v2/Customizing-Git-Git-Configuration) for git.

- #### 👉🏻 Pushing:
Here Comes the step after commiting, the `git push` command is used to upload the content on the local repository to the remote repository.

Pushing has the potential, to over write changes, and we should be careful while pushing.

> Command: `git push <remote_Repo> <Name of the branch>`
> 
> Run this command if you are pushing for the first time, to avoid ay errors.
>
> Simpler command: `git push`
>
> This command also works.

### Some advanced git commands

- #### 👉🏻 Stashing:

Stashing is a process in which, your files get stored in a secret place and you can work on it later.
Stashing comes handy when you need to quickly switch context and get working on something else, but you are in the middle of the task and 
not yet completely ready.

> Command: `git stash`

Now you're free to make changes, create new commits, switch branches, and perform any other Git operations;
then come back and re-apply your stash when you're ready.

The tasks that happen after using the above command are: 
 1. Changes that have been added to your index will get stashed.
 2. Changes made to the files, that are being currently tracked by git will be stashed.

 New files that your working copy that have not yet been tracked by git are ignored.
 And, also the files that have been ignored aren't stashed.



 - Adding un-tracked files to git:

 > command: `git stash -u`       
 >
 > This command includes then untracked files.

 > Adding all the files to stash:
 > 
 > command: `git stash -a`        

You can have multiple stashes; it means you aren't limited to one stash

you can run the git stash command multiple times to create stashes.
To View all the stashes made: use the commadn: git stash list
As default, stashes are identifed as WIP (Work in Progress)

So, if all the stashes look same, it's difficult to identify what you've done.
so, adding context to your stash helps:

> command: `git stash save "Stash Message"`
>
> Now to Verify the Context, 
> 
> Command: `git stash list`

Stashing is a local task and it's not pushed to the server when you push.

- Re-applying the stashed changes:

> command: `git stash popular`
> 
> This command removes the changes from your stash, and then re-applies them to your working copy.

- #### 👉🏻 Cloning Repository

> Command: `git clone <remote repository link>`
> 
> This will clone the remote repository to the current directory and now the new repository directory on your machine becomes a local repostiory.

### Contributing using two Features of GitHub

There are two popular features of GitHub that makes working with git to contribute more awesome. 
  1. Pull Request
  2. Issues
 
- 👉🏻 Pull Request
  
    You might be hearing this word for the first time but trust me, to your open source contribution.
    Up until now, we saw on how to access git and use the tools to work on public repositories but ever
    wondered how we share our work with other repositories? It's really simple, you just send a Pull Request.

    Pull request is a feature, something like asking or requesting the owner of a repository to look
    on the changes you made and check if the changes you've made are compatible with the original
    contents in the repository or not. So, in short pull requests speaks for the work you have contributed.

    Sending a Pull Request is really easy to be honest. You can send a pull request by submitting a branch which contains your work
    or you can submit your work done in a forked repository.

    Once you push your changes to both, either the branch you were working on or the fork repository.
    You will be able to send in pull requests.

    - PR by branching:

        After pushing, open the repository and the branch you were working on and you will be able to see an alert stating that `you are x commits ahead of main branch`, this      simply tells you that there are unmerged or unpublished changes on the current branch which can be updated to the main branch. And thus you will be sending your changes to the main branch from the current branch using a PR.

        Click on the `Compare and Pull Request` button in the alert and you will be able to see a small form, fill in your PR details and submit your PR and the 
        merging of your changes will be decided by the owner of the repository. 

        Fun Fact: You can automate merging of PRs.

    - PR by Forking:

        Once your changes are committed and pushed to the server, your forked repository will notify you that you are eligible to 
        send a Pull Request as some changes were made. Again, press the `Compare and Pull Request` button displayed on the screen and
        voila, fill in the form and all that is left it to press the submit button!

        Then all you need to do is to wait for the owner of the repository to accept the changes by merging
        your pull request into the main or some other branch.

        Another Fun Fact: You can send pull request between any branches. It is not only restricted to the main branch.


## 🔩 Git in a NutShell

#### 🔵 Features

- Provides strong support for non-linear development.
- Distributed repository model.
- Compatible with existing systems and protocols like HTTP, FTP, ssh.
- Capable of efficiently handling small to large sized projects.
- Cryptographic authentication of history.
- Pluggable merge strategies.
- Toolkit-based design.
- Periodic explicit object packing.
- Garbage accumulates until collected.

#### 🟢 Pros

- Super-fast and efficient performance.
- Cross-platform
- Code changes can be very easily and clearly tracked.
- Easily maintainable and robust.
- Offers an amazing command line utility known as git bash.
- Also offers GIT GUI where you can very quickly re-scan, state change, sign off, commit & push the code quickly with just a few clicks.

#### 🔴 Cons

- Complex and bigger history log become difficult to understand.
- Does not support keyword expansion and timestamp preservation.


## 📚 Resources On Git And Github
### Git CLI
  - [Download Git Bash](https://git-scm.com/downloads), yep you will need to install git in order to use it.

### Git GUI
  - [Download GitHub Software](https://desktop.github.com/), you won't need to run any console commands if you use this version of git. But we recommend CLI version.

### Some known contents for beginners
- [OpenSource101](https://github.com/Open-Source-Community-VIT-AP/OpenSource101), the sanctuary of OpenSourcing.
- Read or Download the [ProGit book](https://git-scm.com/book/en/v2) by Git. If you finish reading this book by any chance then you might be able to even contribute to git.
- [Content By OSC's Community Leader](https://docs.vijaybalaji.me/resources/git-and-github-resources) 
- [Learn Git under 10 mins](https://www.freecodecamp.org/news/learn-the-basics-of-git-in-under-10-minutes-da548267cc91/) for speedrunners.
