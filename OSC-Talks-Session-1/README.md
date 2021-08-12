# 📢 The First Git Session

Hey there, welcome to the Git Session-1 documentation. We've compiled the contents of Git and Github for you into a concise guide, so, let's get you a step closer to your first open source contribution.

## 🔧 What's a Version Control System?

Consider being in a project with changes in the code being constant.
The addition of new modules, bug fixes, and the removal of unnecessary or deprecated options.

As humans, we sometimes make mistakes.
Generally, these mistakes mean that the product becomes unstable and may even fail.
At this point, as a developer, you see your entire career flash by your eyes.

However, this is where Version Control comes into the picture.
Version Control works as a checkpoint system much like in games.
It creates checkpoints in the form of commits, and you can roll back to the previous version of your project.

We have different kinds of Version Control Systems, but `git` is the considerably the most popular version control system.
Here's a list of the Version Control Systems that you might come across though,
- Git 
- Mercurial
- Apache Subversion System 
- Monotone
- Bazaar

## ❔ Why do we even need Git?

If the career dependent guy above wasn't enough to make a mark on why you should be using git, here's a few more points that should sell it,
  - Git keeps track of changes made to a file, basically functioning as it's own changelog.
  - It keeps a note of all the files that are there inside a project.
  - Git can compare and analyse different pieces of codes with the help of the `git diff` utility.
  - You can commit your changes even whilst being offline and disconnected from the internet.
  - Every change you make is noted in the hidden folder of git, the verification of the files is done by decoding the hash codes in your commit.
  
  All the commits made on Git, is denoted by a unique hash code, this allows you to turn back time to back when the issue never even existed!
  While this is not the end of how git makes your life easier, we must proceed to finally working with it now.
  
  In order to learn more about how Git actually works, consider checking out the [Book](https://git-scm.com/book/en/v2).

## 🔧 So, how do I work with Git?

There's two forms of working with Git,
  1. Command Line Interface (CLI Mode)
  2. Graphical User Interface (GUI Mode)

Random Fun Fact?
Most Developers Prefer CLI Mode.

Before we go further we suggest that you download the Git CLI version, checkout [resource](https://github.com/Open-Source-Community-VIT-AP/OSC-Talks/tree/main/OSC-Talks-Session-1#Resources-On-Git-And-Github) section for the download link.
  
 ## Configuring Git

  1. Open Your CMD/ git bash shell
  2. Type the command:     
      ```shell
        git config --global user.name "YOUR GITHUB USER NAME"
        git config --global user.email "EMAIL ADDRESS"
      ```
      These commands will let the locally installed git know that you are person `xyz` with email `xyz@email.com`. Yeah, now your git client is associated with your account.
      
  ## Some Basic Terminal Commands
  
   Some CMD Commands that you may need for switching directories, creating folders, creating files, opening files, deleting files, deleting directories, and the such, 
    
  ```cmd
      1. cd path/to/dir       (It changes the current working directory to the path mentioned by you)
      2. cd ..                        (It Goes Up by one directory)
      3. mkdir folderName         (It Creates a new folder with the name mentioned by you)
      3. echo >> FileName.FileType    (It Creates a file, with the type/format specified by you)
      4. notepad FileName.FileType    (Opens the file specified by you in the notepad)
      5. rm FileName.FileType         (Deletes the file mentioned by you)
      6. rmdir path/to/dir     (Deletes a particular folder/directory that was specified)
  ```
      
  #### Working with Git on your system:
  
  - #### 👉🏻 Initialization:
  
   First you need to create a local repository, so create a new folder.
   Now, open your command prompt/terminal and migrate to a folder where you want to create a repository.

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
