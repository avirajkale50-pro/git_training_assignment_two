# git_training_assignment_two

I created this repository as part of a Git training assignment to understand how to create and manage a GitHub repository from scratch. The goal of this assignment was to practice the complete Git workflow, starting from initializing a local repository to pushing it to GitHub.

First, I created a new directory on my local system and initialized it as a Git repository. I then added a `README.md` file to document the project and made commits to track changes. Finally, I connected the local repository to a remote GitHub repository and pushed the code.

## Commands Used

Below are the Git commands I used to create and push this repository:

```bash
echo "# git_training_assignment_two" >> README.md
git init
git add README.md
git commit -m "README.md file added"
git branch -M main
git remote add origin https://github.com/avirajkale50-pro/git_training_assignment_two.git
git push -u origin main
```