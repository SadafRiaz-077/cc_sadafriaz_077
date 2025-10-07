#  Name: Sadaf Riaz  
#  Roll No: 2023-BSE-077  
#  Class: V-B  

---

#  CC Lab #02 – Git & GitHub

This lab covers Git and GitHub fundamentals, including SSH setup, repository management, branching, merging, and collaborative workflows.

---

##  Task 1: Create Private GitHub Repository
- Create a **private repository** named `cc_sadafriaz_077_lab-2`.
- Copy the SSH URL to connect locally.

** Screenshots:**  
![Picture 1](https://raw.githubusercontent.com/SadafRiaz-077/cc_sadafriaz_077_lab-2/main/screenshots/picture_1.png)

---

##  Task 2: Connect Repository via SSH
- Generate SSH keys using PowerShell.
- Add your public key to GitHub.
- Clone your repo using SSH link.

** Screenshots:**  
![Picture 2](https://raw.githubusercontent.com/SadafRiaz-077/cc_sadafriaz_077_lab-2/main/screenshots/picture_2.png)
![Picture 3](https://raw.githubusercontent.com/SadafRiaz-077/cc_sadafriaz_077_lab-2/main/screenshots/picture_3.png)

---

##  Task 3: Configure Git Username and Email
Set your Git username and email:
```bash
git config --global user.name "Sadaf Riaz"
git config --global user.email "your_email@example.com"
git config --list
```

** Screenshots:**  
![Picture 4](https://raw.githubusercontent.com/SadafRiaz-077/cc_sadafriaz_077_lab-2/main/screenshots/picture_4.png)

---

##  Task 4: Explore the `.git` Folder
- Navigate into the cloned repository folder.  
- Show hidden files and locate `.git` directory.  
- Explore Git internals.

**Screenshots:**  
![Picture 5](https://raw.githubusercontent.com/SadafRiaz-077/cc_sadafriaz_077_lab-2/main/screenshots/picture_5.png)

---

##  Task 5: Local Repository Management
1. Delete existing `.git` folder.  
2. Run:
   ```bash
   git init
   ```
3. Add `README.md`, commit and push.

** Screenshots:**  
![Picture 6](https://raw.githubusercontent.com/SadafRiaz-077/cc_sadafriaz_077_lab-2/main/screenshots/picture_6.png)

---

##  Task 6: File Status & Staging
1. Create `notes.txt` and add content.  
2. Check file status, stage, and commit.  
3. Edit again and commit changes.

**Screenshots:**  
![Picture 7](https://raw.githubusercontent.com/SadafRiaz-077/cc_sadafriaz_077_lab-2/main/screenshots/picture_7.png)

---

## Task 7: Branch Creation Using GitHub GUI
- Create a new branch using the GitHub interface.

** Screenshots:**  
![Picture 8](https://raw.githubusercontent.com/SadafRiaz-077/cc_sadafriaz_077_lab-2/main/screenshots/picture_8.png)

---

##  Task 8: Branch Creation and Push Using Git Bash
Create and push a branch via Git Bash:
```bash
git checkout -b feature/db-connection
git push origin feature/db-connection
```

** Screenshots:**  
![Picture 9](https://raw.githubusercontent.com/SadafRiaz-077/cc_sadafriaz_077_lab-2/main/screenshots/picture_9.png)
![Picture 10](https://raw.githubusercontent.com/SadafRiaz-077/cc_sadafriaz_077_lab-2/main/screenshots/picture_10.png)

---

##  Task 9: Branching & Merging
1. Create and switch to `feature-1`.  
2. Add a function to `main.py` and commit.  
3. Switch back to `main` and merge.

** Screenshots:**  
![Picture 11](https://raw.githubusercontent.com/SadafRiaz-077/cc_sadafriaz_077_lab-2/main/screenshots/picture_11.png)

---

##  Task 10: Pull Request and Branch Review
- Create a **Pull Request** from `feature/db-connection` → `main`.  
- Review and merge using GitHub.  
- Delete merged branch.

** Screenshots:**  
![Picture 12](https://raw.githubusercontent.com/SadafRiaz-077/cc_sadafriaz_077_lab-2/main/screenshots/picture_12.png)
![Picture 13](https://raw.githubusercontent.com/SadafRiaz-077/cc_sadafriaz_077_lab-2/main/screenshots/picture_13.png)

---

##  Task 11: Detailed Branch Strategy (Develop/Staging)
Create professional workflow branches:
- `develop`
- `staging`
- `feature/*`
- `bugfix/*`

**Workflow Example:**
- Work on `feature/*` and `bugfix/*`
- Merge into `develop`
- Merge `develop` → `staging`
- Merge `staging` → `main`

** Screenshots:**  
![Picture 14](https://raw.githubusercontent.com/SadafRiaz-077/cc_sadafriaz_077_lab-2/main/screenshots/picture_14.png)
![Picture 15](https://raw.githubusercontent.com/SadafRiaz-077/cc_sadafriaz_077_lab-2/main/screenshots/picture_15.png)

---

##  Task 12: Code Review Workflow
- Create PR and assign a reviewer.  
- Reviewer approves or requests changes.  
- Author fixes issues and updates branch.  
- Merge after approval.

** Screenshots:**  
![Picture 16](https://raw.githubusercontent.com/SadafRiaz-077/cc_sadafriaz_077_lab-2/main/screenshots/picture_16.png)

---

##  Task 13: Delete Remote Branch After Merge
After merge, delete branches and update local repository:
```bash
git fetch --prune
git pull
```

** Screenshots:**  
![Picture 17](https://raw.githubusercontent.com/SadafRiaz-077/cc_sadafriaz_077_lab-2/main/screenshots/picture_17.png)

---

##  Conclusion
This lab helped you learn:
- Git initialization and SSH configuration  
- Branch creation and merging  
- Pull request and review process  
- Professional Git branching strategy  

---

© 2025 – Created by **Sadaf Riaz (2023-BSE-077, V-B)**

