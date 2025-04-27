# Graded Assignment: Git and GitHub

##  Overview

This repository demonstrates Git and GitHub workflows including branching, merging,PR, LFS, and stash operations.

---

## 🛠 Tech Stack 

-Python, Git, GitHub


##  Questions & Implementation Summary

### **Q1: Feature Implementation in CalculatorPlus App**

1. Created a Repository: git_assignment_HeroVired Branch -Dev
2. Added initial code:
    - Basic arithmetic functions: add, subtract, multiply, divide
3. Testing: All basic arithmatic functions were tested
4. Merged dev branch to main and created a release Tagged as v1.0
5. Code Review and Collaboration with a colleaugue on GitHub
6. Pull Request and code review : feature/sqrt ➝ main Merged feature/sqrt to dev Finalally Merged dev to main and created a release tagged as v2.0


### Q2: Git LFS Integration
#### Steps:

1. Created Branch: `lfs`
2. Git LFS configuration:
```bash command
git lfs install
git lfs track "*.zip"
```
3.  Uploaded a file >200MB
4. Committed & Pushed to Ensured LFS tracked file properly
5. Cloned repo on another system to validate zip file download

---

### **Q3: Geometry Calculator with Git Stash**
#### Steps:
#### Circle Area:

1. Created branch  `feature/circle-area` and started implementing `calculate_circle_area` function
2. Stashed Incomplete Work:
```bash
git stash
```

####  Rectangle Area Feature

3. Created branch `feature/rectangle-area` and started implementing `calculate_rectangle_area` function
4. Stashed Incomplete Work
5.Verified working directory clean


6. Switched back to `feature/circle-area` branch
7. Get the stashed code & completed circle area code then Commit & push.
8. Switch to `feature/rectangle-area` branch
9.  Get the stashed code & completed rectangle area code commit & push.

Pull Requests
10. Created PRs to `dev` from both branches
11. Reviewed and approved by reviewer
12. Merged both features to `dev`
13. Ceated PR to `master` from `dev`
14. Requested review and got approval
15. Merged `dev` to `master`
---

## **🚀 How to Run**

 Q1. CalculatorPlus App
Navigate to the **CalculatorPlus** directory and run:
```bash
python app.py
```

 Q2. Large binary file with Git FFS
1. **Checkout branch** : `lfs`
2. Navigate to the **LFS** directory 
3. Able to find **Large binary file** as *testFile.zip*

 Q3. Geometry Calculator
Navigate to the **GeometryCalculator** directory and run:
```bash
python app.py
```
---


> 📌 Note: `lfs` branch is kept **separated and not mergerd** with `master` to isolate  Git LFS functionality as a separate demonstration.

---

## 🔍 Git Commands Used

``` bash

# General Commands
git init
git clone
git add .
git commit -m "message"9[-
git push origin <branch_name>
git pull origin <branch_name>

# Branching & Merging
git checkout -b <branch_name>
git merge <branch_name>

# Stash
git stash
git stash list
git stash apply

# LFS
git lfs install
git lfs track "*.zip"

# Tagging
git tag v1.0
git push tag
```

---

Collaboration

- Added [@kushal1997](https://github.com/kushal1997) and **[@govind02420](https://github.com/govind02420) as collaborator to the repository as per the assignment requirement.
- Provided code reviews to [@kushal1997](https://github.com/kushal1997) on the GitHub repository.

