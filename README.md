# TPGIT
# DevOps Practical Work - Git Mastery
This practical work aims to familiarize you with Git, a widely-used decentralized version control system. The practical work covers the following aspects:
## Part 1: Setting up the Git Environment
  1. **SSH Key Generation:**
     - Generating SSH key: `ssh-keygen -t rsa -b 4096 -C kortashadil27@example.com`
     - Adding the SSH public key to the remote repository.
---
  2. **Git Configuration:**
     - Configuring the username: `git config --global user.name "Hadil kortas"`
     - Configuring the email address: `git config --global user.email kortashadil27@gmail.com`
---
  3. **SSH Connection to Remote Repositories:**
     - Testing SSH connection: `ssh -T git@github.com`
---
## Part 2: Creating a New Project
  1. **Creating the Project on GitHub:**
     - Creating a new project with appropriate options.
     - Cloning the project locally: `git clone git@github.com:hadil-kortas/Maitrise-de-Git.git`
     - `cd Maitrise-de-Git`
---
## Part 3: Basic Git Concepts
  1. **Working with Files:**
     - Creating a file named index.html: `touch index.html`
     - `echo 'My index.html Content' > index.html `
     - Using the following commands to add the file to the index and commitmy first change: `git add index.html`
     - `git commit -m "First commit: added index.html" `
---
  2. **Commit History:**
     - Viewing the commit history: `git log`
     - Showing the difference between two commits with their id: `git diff commit_id_1 commit_id_2`
---
## Part 4: Collaborating on Git
  1. **Creating a New Branch for a Specific Feature:**
     - `git branch ma-fonctionnalite`
     - `git checkout ma-fonctionnalite`
---
  2. **Making changes in my local repository:**
     - Making modifications in my local repository, adding them to the index, commit and then push: `git add .`
     - `git commit -m "changes in ma-fonctionnalite" `
     - `git push origin ma-fonctionnalite`
---
  3. **Conflict Management:**
     - modifying the same line in the two different branches, then merging the branches and resolve the conflict
     - `git checkout my-fonctionnalite`
     - `git commit -am "Changes in ma-fonctionnalite" `
     - `git checkout main`
     - `git commit -am "Changes in main"`
     - `git merge ma-fonctionnalite`
     - `git add .`
     - `git commit -m "Conflict resolution"`
---
## Part 5: Utilizing GitFlow
  1. **Initialization of GitFlow:**
     - `git flow init`
---
  2. **Creation of a New Feature:**
     - `git flow feature start ma-fonctionnalite`
---
  3. **Creation of a New Version:**
     - `git flow release start ma-version`
---
  4. **Merging a Feature Branch into Development:**
     - `git flow feature finish ma-fonctionnalite`
---
  5. **Creating a Hotfix:**
     - `git flow hotfix start mon-correctif`
---
This README provides an overview of the practical work steps and can be expanded based on specific experiences in each part of the practical work.












