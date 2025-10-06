# Git & GitHub Labs (1–9)

## **Lab 1: Git Installation & Setup**

**Q1:** What is the command to check if Git is installed on your computer?  
**A:** `git --version`

**Q2:** Install Git on your computer using git-scm.com.  
**A:** Git was downloaded and installed from [https://git-scm.com](https://git-scm.com).

**Q3:** Configure your Git username and email. Write the commands you used.  
**A:**  
```
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
```

**Q4:** What is the importance of setting your username and email in Git?  
**A:** It helps identify who made each commit in a project, useful for collaboration and version tracking.

**Q5:** Run `git config --list` and paste a screenshot of your configuration output.  
**A:** *[Screenshot attached in folder]*


---

## **Lab 2: Create a Local Website Project**

**Q1:** Create a folder named my-website on your Desktop.  
**A:** `mkdir my-website`

**Q2:** Inside the folder, create two files: index.html and style.css.  
**A:** Files created successfully.

**Q3:** Write a simple HTML code that displays a heading “Welcome to My Website”.  
**A:**  
```html
<h1>Welcome to My Website</h1>
```

**Q4:** Add CSS to make the heading text blue.  
**A:**  
```css
h1 {
  color: blue;
}
```

**Q5:** Show a screenshot of your folder structure and file contents.  
**A:** *[Screenshot attached in folder]*


---

## **Lab 3: Initialize Git Repository**

**Q1:** What command do you use to navigate to your project folder in Command Prompt?  
**A:** `cd Desktop/my-website`

**Q2:** Initialize Git inside the my-website folder.  
**A:** `git init`

**Q3:** What does the .git folder represent?  
**A:** It stores all version control information and history for the repository.

**Q4:** Run git status. What information does it display?  
**A:** It shows the current branch, staged/untracked files, and any pending commits.

**Q5:** Paste a screenshot showing successful initialization and Git status output.  
**A:** *[Screenshot attached in folder]*


---

## **Lab 4: Add and Commit Files**

**Q1:** What is the purpose of the staging area in Git?  
**A:** It’s where files are prepared before committing changes permanently.

**Q2:** Add index.html to the staging area.  
**A:** `git add index.html`

**Q3:** Commit the HTML file with a message.  
**A:** `git commit -m "Added index.html with welcome message"`

**Q4:** Repeat for style.css.  
**A:**  
```
git add style.css
git commit -m "Added style.css with blue heading"
```

**Q5:** Run git log and note down the commit IDs and messages.  
**A:** *[Screenshot attached in folder]*


---

## **Lab 5: Create GitHub Repository and Push Code**

**Q1:** Create a GitHub account (if not already created).  
**A:** Done via [https://github.com](https://github.com)

**Q2:** Create a new repository named my-website.  
**A:** Repository created successfully.

**Q3:** Write the command to connect your local repo with your GitHub repo.  
**A:**  
```
git remote add origin https://github.com/username/my-website.git
```

**Q4:** Push your commits to GitHub.  
**A:**  
```
git push -u origin master
```

**Q5:** What does `git push -u origin master` do?  
**A:** It uploads commits to the master branch and sets the upstream for future pushes.

**Q6:** Paste a screenshot of your GitHub repository showing both files.  
**A:** *[Screenshot attached in folder]*


---

## **Lab 6: Create and Switch Branches**

**Q1:** What is a branch in Git?  
**A:** A branch allows working on new features independently without affecting the main code.

**Q2:** Create a new branch named improve-styling.  
**A:** `git branch improve-styling`

**Q3:** View all branches.  
**A:** `git branch`

**Q4:** Modify style.css with background color and center-aligned heading.  
**A:** *Done and committed.*

**Q5:** Push the branch to GitHub.  
**A:** `git push -u origin improve-styling`

**Q6:** Paste a screenshot showing both branches.  
**A:** *[Screenshot attached in folder]*


---

## **Lab 7: Merge Branches**

**Q1:** What is the purpose of merging in Git?  
**A:** To combine changes from one branch into another.

**Q2:** Switch back to the master branch.  
**A:** `git checkout master`

**Q3:** Merge the improve-styling branch into master.  
**A:** `git merge improve-styling`

**Q4:** Push the updated master branch to GitHub.  
**A:** `git push origin master`

**Q5:** What happens to the feature branch after merging?  
**A:** It remains in the repo and can be deleted if no longer needed.

**Q6:** Paste a screenshot showing the updated style.css in master branch.  
**A:** *[Screenshot attached in folder]*


---

## **Lab 8: Collaboration Simulation**

**Q1:** What does it mean to "fork" a repository on GitHub?  
**A:** It creates your own copy of someone else’s repository under your account.



---

## **Lab 9: Reflection Task**

**Q1:** In your own words, explain what Git is and why it is important.  
**A:** Git is a version control system that tracks changes in files, allowing collaboration and rollback.

**Q2:** Explain the difference between git add, git commit, git push.  
**A:**  
- **git add**: Moves changes to staging area.  
- **git commit**: Saves staged changes locally.  
- **git push**: Uploads commits to GitHub.

**Q3:** What is a branch? Why do developers use it?  
**A:** A branch isolates work on different features without affecting main code.

**Q4:** What command would you use to see the commit history?  
**A:** `git log`

**Q5:** What was the most challenging part of this lab series for you?  
**A:** Understanding how branches and merges work initially.

**Q6:** What skill did you gain that will help in your future coding projects?  
**A:** Version control, collaboration, and managing projects efficiently using GitHub.
