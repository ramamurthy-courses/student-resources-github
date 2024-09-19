# GitHub Classroom Instructions for Students

### Must Watch GitHub Tutorials (Please watch this videos first before reading further)
- [Git and GitHub Crash Course:](https://www.youtube.com/watch?v=RGOj5yH7evk)
- [Install Java and Visual Studio Code Instructions](https://www.youtube.com/watch?v=BB0gZFpukJU)
- [Set SSH access to GitHub in your computer](https://www.youtube.com/watch?v=snCP3c7wXw0)


### Instructions for Using GitHub Classroom as a Student

**1. Set Up Your GitHub Account**
- If you don't already have a GitHub account, sign up at [GitHub](https://github.com/).
- Ensure your account is properly set up, with a username, email, and any necessary verifications.
  
**2. Accept the GitHub Classroom Assignment**
- Your instructor will provide a GitHub Classroom link to the assignment using Blackboard.
- Click the link to accept the assignment.
- You may be prompted to authorize GitHub Classroom to access your GitHub account—approve this request.

**3. Choose or Create a GitHub Repository**
- After accepting the assignment, a new repository will be automatically created for you by GitHub Classroom.
- This repository will be named according to your assignment or class (e.g., `assignment-1-your-username`).
  
**4. Clone the Repository to Your Local Machine**
- In the repository page, click on the **Code** button to get the repository URL.
- Use the following command to clone the repository locally:
  ```
  git clone <repository-url>
  ```
  Replace `<repository-url>` with the actual link to your repository.

**5. Work on the Assignment**
- Navigate to the cloned repository on your local machine:
  ```
  cd <repository-folder>
  ```
- Write your code, complete the assignment, or make any necessary changes in the repository files.
- Note: Please make sure to write your full name on the top of the file and comment the line. Otherwise, it will be difficult to associate your GitHub repository to you. 

**6. Stage, Commit, and Push Changes**
- When you've made changes to the assignment, you need to **stage** and **commit** them to your repository:
  ```
  git add .
  git commit -m "Completed Assignment"

  or

  git add .
  git commit -m "Ready to Grade"
  ```

- Push the changes back to your GitHub repository:
  ```
  git push origin main
  ```
  Ensure that "main" is the correct branch name (some projects may use "master" or other names).

**7. Review Your Work on GitHub**
- After pushing your changes, visit the GitHub repository page to verify your work is properly uploaded.
- You can check the files or view the commit history to ensure everything is correct.

**8. Submit the Assignment (If Required)**
- If your instructor requires any additional submission steps (like filling out a form or sending a link), follow the instructions provided.

**9. Receive Feedback or Grades**
- Click on the Pull Requests tab, and click on Feedback. 
- Check there to review any feedback, grades, or automated test results.
- Click on Files Changed tab to see all those lines you have edited (should be highlighted in green). Use the + sign to add comments and approve the comments, so that the instructor can see them. 


---

### Common Git Commands Overview:
- **Cloning a Repository**: `git clone <repository-url>`
- **Checking Repository Status**: `git status`
- **Adding Files to Staging**: `git add .` (or specify specific files)
- **Committing Changes**: `git commit -m "commit message"`
- **Pushing Changes**: `git push origin <branch>`
- **Pulling Updates**: `git pull origin <branch>`


Make sure to stay in sync with your repository and communicate with your instructor if you encounter any issues.



## Signing Up for GitHub Student Developer Pack (Optional, but recommended)

1. **Visit the Student Developer Pack Page:**
    - Go to [GitHub Student Developer Pack](https://education.github.com/pack).

2. **Apply for the Pack:**
    - Click on "Get your pack" and follow the instructions to apply.
    - You may need to provide proof of your student status.


## General Tips

- **Be Professional:** Maintain a professional tone in all communications.
- **Be Prompt:** Respond to feedback and messages in a timely manner.
- **Be Clear:** Provide clear and concise descriptions in your commits, pull requests, and comments.

------
***Disclosure: Some of the contents in this blogs were generated using Generative AI