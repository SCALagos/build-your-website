# 🧑🏽‍💻 Assignment 3: Build Your Personal  Website – Git & GitHub Steps
 In this task, you’ll practice working with Git and GitHub by cloning a sample website repo, editing it, creating a new branch, and submitting your work via a pull request.
  
Follow the instructions below carefully. If you get stuck, ask for help — that's what we're here for!

## 📌 Step-by-Step Instructions

### ✅ Step 1: Fork the Repository
- Fork this repository -  https://github.com/SCALagos/build-your-website
- Click the "Fork" button at the top-right corner of the page.

This creates a copy of the repo under your GitHub account.

### ✅ Step 2: Clone Your Fork
- You'll now download your forked repo to your computer.
- On your forked repo, click the green "Code" button and copy the HTTPS URL.
- Open your terminal or Git Bash and run:

```
git clone https://github.com/YOUR_USERNAME/build-your-website.git
cd build-your-website

```


### ✅ Step 3: Create a New Branch
Run the following command to create and switch to a new branch:

```
git checkout -b assignment3-by-yourname

```

Replace `yourname` with your actual name or GitHub username (e.g., assignment3-by-chisomjude)

### ✅ Step 4: Edit the Website

- Open the files in your code editor (e.g., VS Code).
- Locate the sample HTML file and make changes 

- Add your name, Change colors or text, Add a picture or some basic styling, Don’t delete the original structure — just personalize and improve it!

✅ Step 5: Add, Commit & Push Changes
After saving your edits, go back to your terminal and run:

```
git add .

#Then commit your changes

git commit -m "Edited sample website for Assignment 3"

#Push your branch to your forked repo:

git push origin assignment3-by-yourname

```

### ✅ Step 6: Create a Pull Request

- Go back to your forked repo on GitHub.

- You should see a "Compare & Pull Request" button. Click it.

- Set the base branch to scalagos and the compare branch to assignment3-by-yourname.

- Add a short description (e.g., "Assignment 3 by Chioma") and click "Create Pull Request".