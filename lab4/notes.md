Q1. --global means the Git username and email are saved as the default settings for my user account on this computer, so they apply to all my Git repositories. If I leave it out, the settings apply only to the current repository.

Q2. The .git directory appeared in ls -a but not in the normal ls output because it is a hidden directory. It contains Git's internal files and information, such as the repository's history, configuration, and references.

Q3. Git was offering to track roughly the files and folders in my coding-cafe directory, including the .venv folder and its many files. The .venv folder contains Python environment files that I did not write, so it should not be tracked by Git.

Q4. After adding .gitignore, the .venv/ folder and its files disappeared from git status because Git is now ignoring them. The .gitignore file itself appears as an untracked file.

Q5. .gitignore should be committed, not ignored. It tells Git which files and folders to ignore, so keeping it in the repository makes sure the same rules apply to everyone working on the project.

Q6. README.md moved from “Untracked files” to “Changes to be committed.” In the three-places model, it moved from the working directory to the staging area because git add README.md staged it.

Q7. [master (root-commit) 684bE34] Initial commit
5 files changed, 360 insertions(+)

Q8. The first seven characters of my commit are 684be34. They are an abbreviated commit hash (commit ID), used to uniquely identify a particular commit and refer to it easily.

Q9. The four steps are edit → check git status → stage with git add → commit with git commit. This loop is repeated whenever I make changes that I want to save in Git history.

Q10. README.md has a special name and place because GitHub automatically displays it on the repository’s main page. It acts as an introduction and documentation for the project, so visitors can understand the repository without opening another file.

Q11. gh auth login authenticated my GitHub account and configured Git to use my GitHub credentials for HTTPS operations. This means Git can authenticate my pushes without asking me for my GitHub password each time.

Q12. The README.md file is showing on the front page of the GitHub repository. GitHub automatically displays a root README.md as the repository’s introduction and documentation.

Q13. No, pushing did not change my local history. It only copied my existing local commits to the GitHub repository; the commits and their history remained the same locally.

Q14. a private repository exists on GitHub, but only the owner and people who have been given access can view or work with it. If a repository does not exist on GitHub, there is no online copy of the project or its Git history to access.Q1. --global means the Git username and email are saved as the default settings for my user account on this computer, so they apply to all my Git repositories. If I leave it out, the settings apply only to the current repository.

