
# Git Commands Documentations

## 1. **Basic Linux Commands**
- **Create a directory:**
```bash
mkdir git-for-devops
```

- **List files in the current directory:**
```bash
ls
```

- **Print the working directory path:**
```bash
pwd
```

- **Change to a directory:**
```bash
cd <directory-name>
```

- **Clear the terminal screen:**
```bash
clear
```

- **Display the content of a file:**
```bash
cat <filename>
```

- **Remove a file:**
```bash
rm <filename>
```

- **Edit a file using Vim:**
```bash
vim <filename>
```

---

## 2. **Git Initialization**
- **Initialize a new Git repository:**
```bash
git init
```

---

## 3. **File Operations**
- **Create new files:**
```bash
touch nibba.txt
touch nibbi.txt
```

- **Restore a deleted file:**
```bash
git restore <filename>
```

---

## 4. **Staging and Unstaging Files**
- **Add files to the staging area:**
```bash
git add nibba.txt
git add nibbi.txt
```

- **Unstage a file:**
```bash
git rm --cached <filename>
```

---

## 5. **Committing Changes**
- **Commit staged changes with a message:**
```bash
git commit -m "Your commit message"
```

---

## 6. **Branching**
- **Create and switch to a new branch:**
```bash
git checkout -b dev
```

- **Switch between branches:**
```bash
git checkout master
git checkout dev
git switch <branch-name>
```

- **List all branches:**
```bash
git branch
```

---

## 7. **Viewing History**
- **View commit history:**
```bash
git log
```

- **View concise commit history:**
```bash
git log --oneline
```

---

## 8. **Git Configuration**
- **Set global username:**
```bash
git config --global user.name "lakshayvermaa"
```

- **Set global email:**
```bash
git config --global user.email "lakshayverma692@gmail.com"
```

- **List global Git configuration:**
```bash
git config --global --list
```

---

## 9. **Status and Logs**
- **Check the status of the repository:**
```bash
git status
```

- **View history of terminal commands:**
```bash
history
```

---

## 10. **Miscellaneous**
- **Display hidden files:**
```bash
ls -a
```

- **View detailed file list:**
```bash
ls -l
```

- **Attempt a typo command (`to`):**
```bash
to
```

> **Note:** Replace `<filename>` or `<branch-name>` with actual names as needed.
