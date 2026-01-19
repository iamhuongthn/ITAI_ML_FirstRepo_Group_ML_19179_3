# ITAI_ML_FirstRepo_Group_ML_19179_3

## Course
ITAI-1371 – Intro to Machine Learning

## Group Assignment
Getting Started with GitHub & Your First Repository Objective

---

## Purpose
This repository is an introductory group project designed to help students become familiar with GitHub and collaborative workflows.  
It is used to practice creating repositories, working with branches, committing changes, and submitting pull requests.

---

## Group Information
**Group Name:** ML_19179 3

### Group Members
- Alissa Canesim Bento  
- Stuart Fairchild  
- Ruben Quang Anh Kuijpers  
- Huong Thi Hue Nguyen  

---

## Professor
- Viswanatha Rao (viswanatha.rao@hccs.edu)

---

## Repository Contents
- `README.md` — Project overview and collaboration guide
- `hello_ml.txt` — Shared file edited by all group members

---

## Notes
- Each student must contribute using their **own branch**
- Pull Requests are required for grading
- This repository serves as a foundation for future GitHub-based assignments

---

## Team Workflow Guide (IMPORTANT – Please Read)

Each group member must add **one greeting line** to the shared file `hello_ml.txt` using **their own Git branch** and submit the change via a **Pull Request (PR)**.

**Do NOT edit the `master` branch directly.**

---

## Step-by-Step Instructions (Command Line)

### 1. Clone the Repository
```bash
git clone https://github.com/iamhuongthn/ITAI_ML_FirstRepo_Group_ML_19179_3.git
cd ITAI_ML_FirstRepo_Group_ML_19179_3
```

---

### 2. Create Your Personal Branch
Use your **name or username**, no spaces.

Examples:
- alissa-line
- stuart-line
- ruben-line
- huongthn-line

```bash
git checkout -b your-branch-name
```

---

### 3. Add Your Greeting Line
Open `hello_ml.txt` and add **one new line at the bottom** in this exact format:

```
Hello from Your Full Name
```

Command-line option:
```bash
echo "Hello from Your Full Name" >> hello_ml.txt
```

---

### 4. Verify the File
```bash
cat hello_ml.txt
```

Make sure:
- The first line remains unchanged
- Your greeting is added only once

---

### 5. Commit Your Change
```bash
git add hello_ml.txt
git commit -m "Add greeting from Your Full Name"
```

---

### 6. Push Your Branch to GitHub
```bash
git push -u origin your-branch-name
```

---

### 7. Create a Pull Request (PR)
1. Go to the repository on GitHub
2. Click **Compare & pull request**
3. Use this title format:
   ```
   Add greeting from Your Full Name
   ```
4. Submit the Pull Request

Wait for the group lead to review and merge your PR.

---

### 8. After PR Is Merged (Optional Check)
```bash
git checkout main
git pull
cat hello_ml.txt
```

You should see greetings from **all group members**.
