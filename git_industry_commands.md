# Git Industry Level Commands Practice

---

## 1. Git Configuration Commands

### Command
git config --global user.name

Syntax
git config --global user.name "username"

Purpose
Sets the username for Git commits.

Example
git config --global user.name "Salma"

Screenshot

![Group1](screenshots/group11.png)

---

### Command
git config --global user.email

Syntax
git config --global user.email "email"

Purpose
Sets the email for Git commits.

Example
git config --global user.email "salma@email.com"

Screenshot

![Group1](screenshots/group11.png)

---

### Command
git config --list

Syntax
git config --list

Purpose
Displays all Git configuration settings.

Example
git config --list

Screenshot

![Group1](screenshots/group11.png)

---

### Command
git config --unset

Syntax
git config --unset user.name

Purpose
Removes a Git configuration value.

Example
git config --unset user.name

Screenshot

![Group1](screenshots/group12.png)

---

### Command
git config --global user.name

Syntax
git config --global user.name "username"

Purpose
Sets username again.

Example
git config --global user.name "Salma"

Screenshot

![Group1](screenshots/group12.png)


## 2. Repository Setup Commands

### Command
git init

Syntax
git init

Purpose
Initializes a new Git repository.

Example
git init

Screenshot

![Group2](screenshots/group2.png)



### Command
git clone

Syntax
git clone repository-url

Purpose
Creates a copy of a remote repository.

Example
git clone https://github.com/user/repo.git

Screenshot

![Group2](screenshots/group2.png)

---

### Command
git clone --branch

Syntax
git clone --branch branch-name repository-url

Purpose
Clones a specific branch from repository.

Example
git clone --branch main repo-url

Screenshot

![Group2](screenshots/group2.png)

---

### Command
git clone --depth

Syntax
git clone --depth 1 repository-url

Purpose
Creates shallow clone with limited history.

Example
git clone --depth 1 repo-url

Screenshot

![Group2](screenshots/group2.png)

---

### Command
git status

Syntax
git status

Purpose
Shows current repository status.

Example
git status

Screenshot

![Group2](screenshots/group2.png)

## Group 3 – Repository Inspection Commands

### Command
git status

Syntax
git status

Purpose
Shows current status of repository.

Example
git status

Screenshot
![Group3](screenshots/group31.png)

---

### Command
git log

Syntax
git log

Purpose
Shows commit history.

Example
git log

Screenshot
![Group3](screenshots/group31.png)

---

### Command
git log --oneline

Syntax
git log --oneline

Purpose
Shows commit history in short format.

Example
git log --oneline

Screenshot
![Group3](screenshots/group32.png)

---

### Command
git show

Syntax
git show commit_id

Purpose
Shows details of a specific commit.

Example
git show HEAD

Screenshot
![Group3](screenshots/group32.png)

---

### Command
git diff

Syntax
git diff

Purpose
Shows changes between file versions.

Example
git diff

Screenshot
![Group3](screenshots/group32.png)

---

## Group 4 – Advanced Inspection Commands

### Command
git diff --staged

Syntax
git diff --staged

Purpose
Shows staged changes before commit.

Example
git diff --staged

Screenshot
![Group4](screenshots/group4.png)

---

### Command
git blame

Syntax
git blame filename

Purpose
Shows who modified each line in a file.

Example
git blame README.md

Screenshot
![Group4](screenshots/group4.png)

---

### Command
git reflog

Syntax
git reflog

Purpose
Shows history of HEAD movements.

Example
git reflog

Screenshot
![Group4](screenshots/group4.png)

---

### Command
git shortlog

Syntax
git shortlog

Purpose
Shows commit summary by author.

Example
git shortlog

Screenshot
![Group4](screenshots/group4.png)

---

### Command
git describe

Syntax
git describe

Purpose
Shows nearest tag for a commit.

Example
git describe

Screenshot
![Group4](screenshots/group4.png)

# GROUP 5: File Tracking Commands

## 1. git add

Command Name:
git add

Syntax:
git add <file>

Purpose:
Adds a file to the staging area.

Example:
git add file1.txt

Screenshot:
![git add](screenshots/group5.png)


## 2. git add .

Command Name:
git add .

Syntax:
git add .

Purpose:
Adds all files in the current directory to staging.

Example:
git add .

Screenshot:
![git add dot](screenshots/group5.png)


## 3. git rm

Command Name:
git rm

Syntax:
git rm <file>

Purpose:
Removes a file from the repository.

Example:
git rm file1.txt

Screenshot:
![git rm](screenshots/group5.png)


## 4. git mv

Command Name:
git mv

Syntax:
git mv <old-name> <new-name>

Purpose:
Renames or moves a file.

Example:
git mv file2.txt newfile.txt

Screenshot:
![git mv](screenshots/group5.png)