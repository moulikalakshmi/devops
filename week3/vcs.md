# Version Control System (VCS) / Source Control Management (SCM)

A **Version Control System (VCS)** or **Source Control Management (SCM)** is a tool that helps developers manage changes to source code over time. It allows teams to collaborate on projects, track changes, and maintain a history of modifications.

## Key Features:
- **Version Tracking**: Keeps a history of changes made to files.
- **Collaboration**: Enables multiple developers to work on the same project simultaneously.
- **Branching and Merging**: Supports parallel development by creating branches and merging changes.
- **Backup and Recovery**: Provides a backup of the codebase and allows reverting to previous versions.

## Types of VCS:
1. **Centralized VCS (CVCS)**: A single central server stores all versions (e.g., Subversion, Perforce).
2. **Distributed VCS (DVCS)**: Each developer has a full copy of the repository (e.g., Git, Mercurial).
![Image](https://github.com/user-attachments/assets/04c0f875-94f5-4c83-ae6a-1fc9a3ffc32d)


## Popular VCS Tools:
- **Git**: A distributed VCS widely used in software development.
- **Subversion (SVN)**: A centralized VCS.
- **Mercurial**: A distributed VCS similar to Git.

Using a VCS ensures better collaboration, code quality, and project organization.
## Difference Between Git and GitHub

### Git:
- **What It Is**: A distributed version control system that helps track changes in source code during software development.
- **Functions**:
    - Manages code history.
    - Tracks changes and versions.
    - Supports branching, merging, and collaboration.
- **Usage**: Installed locally on a developer’s machine, Git is used via the command line or a GUI. It’s independent and doesn’t require an internet connection for most operations.
- **Key Features**: Speed, simplicity, strong support for non-linear development (thousands of parallel branches), and distributed nature.

### GitHub:
- **What It Is**: A web-based platform built on top of Git that provides hosting for Git repositories.
- **Functions**:
    - Centralized hosting for Git repositories.
    - Collaboration tools (pull requests, code reviews, discussions).
    - Integrations with CI/CD pipelines, project management tools, and more.
- **Usage**: Developers push their Git repositories to GitHub to collaborate with others, share code, and manage open-source projects.
- **Key Features**: Social features like following users, starring repositories, and forking projects, as well as project management tools like issue tracking and wikis.

## Getting Started with Git and GitHub

### Create a GitHub Account
1. Visit [GitHub](https://github.com) and sign up for an account.

### Download Git Bash
1. Download and install Git Bash from [Git's official website](https://git-scm.com).

### Create a Repository in GitHub
1. Log in to your GitHub account.
2. Click on the **New Repository** button.
3. Provide a repository name and description, then click **Create Repository**.

### Common Git Commands

#### First-Time Git Setup
```bash
# Add global configurations
git config --global user.email "your.email@example.com"
git config --global user.name "Your Name"

# To show branch name in "git log" outputs
git config --global log.decorate auto
```

#### Starting a Local Repository
```bash
# Initialize a new repository
git init

# Check the status of your repository
git status

# Stage all changes
git add .

# Commit changes with a message
git commit -m "Initial commit"
```

#### Rename the Branch
```bash
# Rename the branch to match the remote repository
git branch -M main 
```

#### Add a Remote Repository and Push Changes
```bash
# Add a new remote repository
git remote add origin <repository-url>

# Push changes to the remote repository
git push -u origin main 

```