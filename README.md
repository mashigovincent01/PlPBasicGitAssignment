# Summary of Steps Followed: Basic Git And GitHub Workflow

## Objective

In this assignment, I learned how to set up a GitHub repository, connect it to a local folder, and manage files using Git. The goal was to get hands-on experience with the basic Git and GitHub workflow.

## Steps Followed

### 1. GitHub Repository Creation

- I logged into my GitHub account and created a new repository named "PLPBasicGitAssignment."
- I initialized the repository with a README file to establish the initial structure.

### 2. Setting Up the Local Environment

- On my local machine, I created a new folder named "PLPBasicGitAssignment."
- Using the terminal, I navigated to this folder to work within it.

### 3. Initializing Git Locally

- I initialized a new Git repository within the local folder using the `git init` command.

### 4. Connecting Local Repository to GitHub

- I connected the local repository to the GitHub repository I created earlier using the command:
  
  ```bash

  git remote add origin https://github.com/mashigovincent01/PlPBasicGitAssignment.git
  ```
### 5. Creating and Managing Files
I created a new file named hello.txt inside the local folder and added a simple greeting message: "Hello, Git!"
### 6. Staging and Committing Changes
I staged the changes using:

bash

Copy code
```bash
git add hello.txt
```
Then, I committed the changes with a descriptive message:

bash
Copy code
```bash
git commit -m "Add hello.txt with a greeting"
```
### 7. Pushing Changes to GitHub
I pushed the committed changes from my local repository to the GitHub repository using:

bash
Copy code
git push -u origin main
### 8. Verifying the Changes
Finally, I visited my GitHub repository in the web browser to confirm that the hello.txt file and the commit message were successfully uploaded.
## Conclusion
By following these steps, I successfully completed the assignment, demonstrating my ability to manage code using Git and GitHub.