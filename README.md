Assignment Instructions
Follow these steps to complete the assignment:

Fork this repository: Click the "Fork" button in the upper right-hand corner of the repository's page on GitHub. This will create a copy of the repository in your GitHub account.

Clone your fork: Use the git clone command to clone your forked repository to your local machine.

git clone https://github.com/sumon2016/git-assignment-Group1.git
Create a branch: Create a new branch to work on your changes. Give your branch a descriptive name that reflects the task you are working on.

git checkout -b feature/add-new-feature
Make changes: Edit, add, or delete files as necessary to complete the assigned task.

Commit your changes: Use git commit to commit your changes with a meaningful commit message.

git add .
git commit -m "Add a new feature: Description of the feature"
Push your changes: Push your branch to your GitHub repository.

git push origin feature/add-new-feature
Create a Pull Request (PR): Go to your GitHub repository and click on the "New Pull Request" button. Make sure to compare your branch with the original repository's main branch. Write a clear description of your changes in the PR.

Review and Merge: After creating the PR, your instructor or a designated reviewer will review your code. They may provide feedback or request changes. Once the changes are approved, the PR will be merged into the main repository.

Update your fork: Periodically, you should update your fork with changes from the original repository by syncing your fork.

git fetch upstream
git checkout main
git merge upstream/main
git push origin main
Submission
Submit your assignment by creating a Pull Request (PR) in the original repository. Make sure to follow the assignment instructions and include a clear description of your changes in the PR.
