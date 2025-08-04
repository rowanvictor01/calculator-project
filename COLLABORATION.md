# Collaboration Guide

Welcome! This project uses a simple collaboration cycle where the collaborator will submit **HTML and CSS mockups**, and the project maintainer will handle integrating them into Vue components.

Please follow the steps below:

---

## 🧑‍💻 Step 1: Fork the Repository

1. Click the **"Fork"** button on the top right of this GitHub repo.
2. This will create a copy of the repository under your GitHub account.

---

## 📥 Step 2: Clone Your Fork

```bash
git clone https://github.com/YOUR_USERNAME/calculator-project.git
cd calculator-project
```

## 🌱 Step 3: Switch to the `mockups` Branch

This is the branch for the **HTML and CSS** files where you'll be working on.

```bash
git checkout mockups
cd mockups
```

## ✍️ Step 4: Add Your Mockup Files

Add your HTML and CSS files into the mockups/ directory.

## ✅ Step 5: Commit and Push

git add .
git commit -m "Add calculator-project HTML/CSS mockup"
git push origin mockups

## 🔁 Step 6: Create a Pull Request

1. Go to your fork on GitHub.

2. Click “Compare & pull request”.

3. Make sure the PR is:

     `From: your-username:mockups`

     `To: original-repo:mockups`

4. Add a short description of what the mockup is (e.g., "Landing page layout").

5. Click “Create pull request”.

## 🚫 Please Do Not:

Do *not* work on the `components` or `main` branch.

## 🔄 What Happens Next?

Once your PR is merged into the original repo's `mockups` branch:
    - Your layout will be converted into a Vue component
    - After testing, it will be pushed into the main branch

## 🙏 Thanks

Your contribution means a lot! We’re learning and building this project together, and your work helps bring it to life.

