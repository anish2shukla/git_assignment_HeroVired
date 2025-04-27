# Graded Assignment: Git and GitHub

## 📘 Overview

This repository demonstrates Git and GitHub workflows including branching, merging,PR, LFS, and stash operations.

---

## 🛠 Tech Stack 

-Python, Git, GitHub


## ✅ Questions & Implementation Summary



### **Q1: Feature Implementation in CalculatorPlus App**

1. Created a Repository: git_assignment_HeroVired Branch -Dev
2. Added initial code:
    - Basic arithmetic functions: add, subtract, multiply, divide
3. Testing: All basic arithmatic functions were tested
4. Merged dev branch to main and created a release Tagged as v1.0
5. Code Review and Collaboration with a colleaugue on GitHub
6. Pull Request and code review : feature/sqrt ➝ main Merged feature/sqrt to dev Finalally Merged dev to main and created a release tagged as v2.0



#### 🔁 Further Feature Sqrt Workflow

9. **New Branch**: `feature/sqrt` created from `dev`
10. **Square Root Logic Added**
11. **Bug Reported**: In `divide()` method
12. **Fix Applied in `dev`**: 
```python
def divide(self, a, b):
    if b == 0:
        raise ValueError("Cannot divide by zero.")
    return a / b

```
13.  **Pull Request Raised**: `feature/sqrt` ➝ `main`
14.  **Peer Review**: Review requested, feedback applied
15.  **Merged** `feature/sqrt` ➝ `dev`, tested
16.  **Final Merge**: `dev` ➝ `main`
17.  **Release Created**: Tagged as `v2.0`

---

### **Q2: Git LFS Integration**
#### 🔨 Steps Followed:

1. **Created Branch**: `lfs`
2. **Configured Git LFS**:
```bash
git lfs install
git lfs track "*.zip"
```
3. **Added Large File**: Uploaded a file >200MB (e.g., testFile.zip)
4. **Committed & Pushed**: Ensured LFS tracked file properly
5. **Clone Verification**: Cloned repo on another system to validate zip file download

---

### **Q3: Geometry Calculator with Git Stash**
#### 🔨 Steps Followed:
#### 🟠 Circle Area Feature

1. **Created branch**: `feature/circle-area`
2. **Began implementing**: `calculate_circle_area` function
3. **Stashed Incomplete Work**:
```bash
git stash
```
4. **Verified working directory clean**

#### 🟡 Rectangle Area Feature

5. **Created branch**: `feature/rectangle-area`
6. **Began implementing**: `calculate_rectangle_area` function
7. **Stashed Incomplete Work**
8. **Verified working directory clean**

#### 🟢 Completed Features

9. **Switched back to** `feature/circle-area`
10. **Retrieved stash & completed circle area code**
11. **Committed & pushed**
12. **Switched to** `feature/rectangle-area`
13. **Retrieved stash & completed rectangle area code**
14. **Committed & pushed**

#### 🔁 Pull Requests
15. **Created PRs to `dev` from both branches**
16. **Requested review and got approval**
17. **Merged both features to `dev`**
18. **Ceated PR to `master` from `dev`**
19. **Requested review and got approval**
20. **Merged `dev` to `master`**
---

## **🚀 How to Run**

### Q1. CalculatorPlus App
Navigate to the **CalculatorPlus** directory and run:
```bash
python app.py
```

### Q2. Large binary file with Git FFS
1. **Checkout branch** : `lfs`
2. Navigate to the **LFS** directory 
3. Able to find **Large binary file** as *testFile.zip*

### Q3. Geometry Calculator
Navigate to the **GeometryCalculator** directory and run:
```bash
python app.py
```
---


## 📁 Folder Structure  

```
git_assignment_HeroVired/
│─── README.md
│
├─── CalculatorPlus
│       app.py
│
├─── GeometryCalculator
│       app.py
│
└─── LFS
```

> 📌 Note: `lfs` branch is kept **separated and not mergerd** with `master` to isolate  Git LFS functionality as a separate demonstration.

---

## 🔍 Git Commands Used

``` bash

# General Commands
git init
git clone
git add .
git commit -m "message"
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

## 🙌 Collaboration

- Added **[@anish2shukla](https://github.com/anish2shukla)** and **[@KevinKoreth](https://github.com/KevinKoreth)** as a collaborator to the repository as per the assignment requirement.
- Provided multiple code reviews to **[@anish2shukla](https://github.com/anish2shukla)** and **[@KevinKoreth](https://github.com/KevinKoreth)** on their GitHub repository.

---

## 👤 Author

- **U KUSHAL RAO**
- GitHub: [@kushal1997](https://github.com/kushal1997)
- Email: kushalrao103@gmail.com
