# 🚀 Project 1 — Git & GitHub

> **Learn Git. Learn GitHub. Work as a Team. Submit Like a Developer.**

Welcome to **Project 1: Git & GitHub**!

In this project, you will learn how software teams use **Git and GitHub** to collaborate, manage code, and submit projects safely.

There are **58 students divided into multiple teams**, so **DO NOT push everyone's code into this repository**.

Each team will work in its **own repository** and submit only the project details to this central repository using a **Pull Request (PR)**.

---

## 🎯 What You Will Learn

By completing this project, you should understand:

* What Git is
* What GitHub is
* How to create a repository
* How to clone a repository
* How to create branches
* How to make commits
* How to push code
* How to pull changes
* How to work with teammates
* How to fork a repository
* How to create a Pull Request
* How to review and merge a Pull Request

---

# 🏗️ How This Project Works

We will use the following workflow:

```text
                    CENTRAL REPOSITORY
                    ┌─────────────────┐
                    │     projects    │
                    │                 │
                    │ project1_git&   │
                    │ github/         │
                    └────────┬────────┘
                             │
                             │ FORK
                             ▼
              ┌──────────────────────────┐
              │      TEAM LEAD FORK      │
              │                          │
              │ Add Team Name            │
              │ Add Members              │
              │ Add Live URL             │
              │ Add GitHub URL           │
              └────────────┬─────────────┘
                           │
                           │ PULL REQUEST
                           ▼
                    ┌─────────────────┐
                    │ CENTRAL REPO    │
                    │                 │
                    │ Review → Merge  │
                    └─────────────────┘
```

---

# 👥 Team Structure

Each team will have members with different responsibilities.

### 👑 Tech Lead

The **Tech Lead** is responsible for:

* Creating/managing the team's project repository
* Coordinating team members
* Making sure the project is pushed to GitHub
* Deploying the project
* Forking the central `projects` repository
* Updating the submission registry
* Creating the Pull Request

### 👨‍💻 Team Members

Team members should:

* Work on the project assigned to the team
* Use Git for version control
* Make meaningful commits
* Push their work to the team's repository
* Coordinate with the Tech Lead

---

# 📌 IMPORTANT — DO NOT DO THIS

❌ Do **NOT** clone the central `projects` repository and start adding your project code there.

❌ Do **NOT** create folders for your entire team inside the central repository.

❌ Do **NOT** ask all team members to push to the central repository.

❌ Do **NOT** edit other teams' submissions.

The central repository is only used as the **official project directory/registry**.

---

# ✅ What Your Team Should Have

Before submitting, your team should have:

* [ ] A separate GitHub repository
* [ ] Project code pushed to GitHub
* [ ] A proper `README.md`
* [ ] Meaningful Git commits
* [ ] A deployed/live version of the project
* [ ] Live project URL
* [ ] GitHub repository URL
* [ ] Team member list
* [ ] Tech Lead identified
* [ ] Pull Request submitted to the central repository

---

# 🛠️ STEP 1 — Create Your Team Repository

Your Tech Lead should create a **separate GitHub repository** for the team project.

Example:

```text
team-alpha-devhub
```

or

```text
team-alpha-git-project
```

The repository should contain your actual project code.

Example:

```text
team-alpha-devhub/
│
├── README.md
├── index.html
├── style.css
├── script.js
└── ...
```

---

# 💻 STEP 2 — Clone Your Team Repository

Once your repository is created, clone it to your computer.

```bash
git clone <YOUR-TEAM-REPOSITORY-URL>
```

Example:

```bash
git clone https://github.com/team-alpha/team-alpha-devhub.git
```

Move into the project:

```bash
cd team-alpha-devhub
```

---

# 🌿 STEP 3 — Create a Branch

Do not make all changes directly on `main`.

Create a branch for your work.

```bash
git checkout -b feature/project-page
```

Example:

```bash
git checkout -b feature/homepage
```

---

# ✏️ STEP 4 — Work on Your Project

Add your files and build your project.

After making changes, check the status:

```bash
git status
```

You should see the files you changed.

---

# 📦 STEP 5 — Stage Your Changes

Add your changes:

```bash
git add .
```

Or add a specific file:

```bash
git add index.html
```

---

# 💾 STEP 6 — Commit Your Changes

Create a meaningful commit.

```bash
git commit -m "feat: add project homepage"
```

### Good commit messages

```text
feat: add homepage
feat: add navigation bar
fix: correct mobile layout
docs: update project README
style: improve landing page
```

### Avoid

```text
update
changes
final
done
hello
asdf
```

Your commit message should tell us **what you changed**.

---

# ☁️ STEP 7 — Push Your Branch

Push your branch to GitHub:

```bash
git push -u origin feature/project-page
```

Your changes should now appear on GitHub.

---

# 🔗 STEP 8 — Deploy Your Project

Your team must deploy the completed project so that it can be viewed online.

Use **GitHub Pages** if your project is compatible with it.

Your final project should have a URL similar to:

```text
https://team-alpha.github.io/team-alpha-devhub/
```

### Your submission needs TWO links:

**1. Live Project**

```text
https://your-live-project-url
```

**2. Source Code**

```text
https://github.com/your-team/your-repository
```

Make sure both links work before submitting.

---

# 🍴 STEP 9 — Fork the Central Repository

Now comes the **submission phase**.

Go to the central:

```text
projects
```

repository.

Find:

```text
project1_git&github
```

On GitHub:

```text
Central Repository
       ↓
      Fork
       ↓
Your GitHub Account
```

Click **Fork**.

This creates your own copy of the central repository.

---

# 📝 STEP 10 — Update the Submission Registry

Open your fork.

Navigate to:

```text
project1_git&github/README.md
```

Find the section:

```text
## 📋 Submission Registry
```

You will see a table similar to:

| Team       | Tech Lead | Members               | Live Project | Source Code |
| ---------- | --------- | --------------------- | ------------ | ----------- |
| Team Alpha | Name      | Member 1, Member 2... | Link         | Link        |
| Team Beta  | Name      | Member 1, Member 2... | Link         | Link        |

Add **your team's information**.

### Example

```markdown
| Team Alpha | Shravya | A, B, C, D, E | [Live](https://example.com) | [GitHub](https://github.com/example/team-alpha) |
```

### ⚠️ IMPORTANT

Only modify the row assigned to your team.

**Do NOT delete or modify another team's information.**

---

# 🌿 STEP 11 — Create a Submission Branch

Inside your fork, create a new branch.

Example:

```bash
git checkout -b submission/team-alpha
```

Your branch name should clearly identify your team.

Example:

```text
submission/team-alpha
submission/team-beta
submission/team-gamma
```

---

# 💾 STEP 12 — Commit Your Submission

After updating the registry:

```bash
git add project1_git&github/README.md
```

Then:

```bash
git commit -m "docs: add Team Alpha project submission"
```

---

# ☁️ STEP 13 — Push Your Branch

```bash
git push -u origin submission/team-alpha
```

Your branch will now appear on your GitHub fork.

---

# 🔀 STEP 14 — Create a Pull Request

Go to your fork on GitHub.

You should see an option such as:

```text
Compare & pull request
```

Click it.

Your Pull Request should look like:

```text
YOUR FORK
   │
   │ Pull Request
   ▼
CENTRAL projects REPOSITORY
```

---

# 📋 Pull Request Title

Use this format:

```text
docs: submit Team Alpha project
```

Examples:

```text
docs: submit Team Beta project
docs: submit Team Gamma project
docs: submit Team Delta project
```

---

# 📝 Pull Request Description

Use this format:

```markdown
## Team Submission

### Team Name
Team Alpha

### Tech Lead
Shravya

### Members
- Member 1
- Member 2
- Member 3
- Member 4
- Member 5

### Live Project
https://example.com

### Source Code
https://github.com/example/team-alpha

### Checklist
- [x] Project repository created
- [x] Project code pushed
- [x] README added
- [x] Project deployed
- [x] Live URL tested
- [x] Source code URL tested
- [x] Submission registry updated
```

---

# 👀 STEP 15 — Wait for Review

After submitting your Pull Request:

**DO NOT merge it yourself.**

The Senior/Instructor will review the submission.

The review process is:

```text
Team submits PR
       ↓
Instructor reviews
       ↓
       ├── ❌ Changes required
       │       ↓
       │   Team fixes PR
       │
       └── ✅ Approved
               ↓
             MERGE
               ↓
       Official submission
```

---

# 🔧 If Changes Are Requested

If the instructor asks you to fix something:

1. Make the required changes in your fork.
2. Commit the changes.
3. Push them to the same branch.

Example:

```bash
git add .
git commit -m "fix: correct project submission links"
git push
```

You **do not need to create another Pull Request**.

The existing PR will automatically update.

---

# 🎉 After Your PR Is Merged

Once your Pull Request is merged:

Your team's information becomes part of the official central repository.

The final structure will look like:

```text
projects/
│
├── project1_git&github/
│   └── README.md
│
├── project2_...
├── project3_...
└── ...
```

And the registry will contain all team submissions.

---

# 🧠 The Complete Workflow

Remember this:

```text
1. CREATE
   ↓
Create your team's GitHub repository

2. CODE
   ↓
Build your project

3. COMMIT
   ↓
Save changes using Git

4. PUSH
   ↓
Push code to your team's repository

5. DEPLOY
   ↓
Put your project online

6. FORK
   ↓
Fork the central projects repository

7. UPDATE
   ↓
Add your team information to the registry

8. COMMIT
   ↓
Commit your submission

9. PUSH
   ↓
Push your submission branch

10. PULL REQUEST
    ↓
Submit your work to the central repository

11. REVIEW
    ↓
Instructor checks your submission

12. MERGE
    ↓
Your project officially appears in the registry 🎉
```

---

# 🚨 Common Mistakes

### ❌ Mistake 1: Everyone pushes to the central repository

**Don't do this.**

Each team works in its own repository.

---

### ❌ Mistake 2: Editing another team's row

Only modify your team's submission.

---

### ❌ Mistake 3: Using vague commit messages

Don't use:

```text
final
update
changes
```

Use:

```text
docs: add Team Alpha submission
```

---

### ❌ Mistake 4: Submitting a broken URL

Before creating your PR, open both links yourself:

```text
🌐 Live Project → Does it open?
💻 GitHub → Does the repository open?
```

If either doesn't work, fix it before submitting.

---

### ❌ Mistake 5: Merging your own PR

**Do not merge your submission unless the instructor explicitly tells you to.**

The instructor will perform the final merge.

---

# 📊 Submission Registry

All approved teams will appear here.

| Team    | Tech Lead | Members | Live Project | Source Code |
| ------- | --------- | ------- | ------------ | ----------- |
| Team 1  | —         | —       | —            | —           |
| Team 2  | —         | —       | —            | —           |
| Team 3  | —         | —       | —            | —           |
| Team 4  | —         | —       | —            | —           |
| Team 5  | —         | —       | —            | —           |
| Team 6  | —         | —       | —            | —           |
| Team 7  | —         | —       | —            | —           |
| Team 8  | —         | —       | —            | —           |
| Team 9  | —         | —       | —            | —           |
| Team 10 | —         | —       | —            | —           |
| Team 11 | —         | —       | —            | —           |
| Team 12 | —         | —       | —            | —           |

> **Only approved submissions will be added to the official registry.**

---

# 🏆 Definition of Done

Your team has successfully completed Project 1 when:

* ✅ Everyone understands basic Git commands
* ✅ Your team has a GitHub repository
* ✅ Your project is pushed to GitHub
* ✅ Your team has meaningful commits
* ✅ Your project is deployed
* ✅ Your live URL works
* ✅ Your source-code URL works
* ✅ Your team information is added to the registry
* ✅ Your Pull Request is created
* ✅ Your PR is reviewed
* ✅ Your PR is merged

---

# 💡 Golden Rule

> **Your team's repository contains your CODE.**
>
> **The central repository contains your SUBMISSION.**

```text
TEAM REPOSITORY
      │
      │
      │  YOUR CODE
      ▼
┌───────────────────┐
│   Team Project    │
│   GitHub Repo     │
└───────────────────┘
          │
          │
          │ Submit details
          ▼
┌───────────────────┐
│ Central Projects  │
│     Repository    │
│                   │
│  Team Name        │
│  Members          │
│  Live URL         │
│  GitHub URL       │
└───────────────────┘
          │
          ▼
     Pull Request
          │
          ▼
       REVIEW
          │
          ▼
        MERGE ✅
```

## 🚀 Build. Commit. Push. Fork. Submit. Merge.

**This is how real developers collaborate on GitHub.**
