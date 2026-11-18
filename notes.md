# Git – Learning Notes

## 1. What is Git?
Git is a distributed version control system. It records changes to files over time so that a developer can review earlier versions, work on separate features, and collaborate with others.

## 2. Git vs GitHub
- **Git:** the version-control tool that runs on your computer.
- **GitHub:** an online platform for hosting Git repositories and collaborating.

Git can be used without GitHub.

## 3. Important terms
- **Repository (repo):** a project whose file changes are tracked by Git.
- **Working directory:** the files you are currently editing.
- **Staging area:** the place where you select changes for the next commit.
- **Commit:** a saved snapshot of staged changes, with a message.
- **Branch:** an independent line of development.
- **Merge:** combining changes from one branch into another.
- **Remote:** a repository hosted elsewhere, commonly on GitHub.
- **Clone:** creating a local copy of a remote repository.
- **Push:** sending local commits to a remote repository.
- **Pull:** fetching and integrating remote changes.

## 4. Basic workflow
1. Edit files in the working directory.
2. Use `git status` to inspect changes.
3. Use `git add` to stage selected changes.
4. Use `git commit` to save the staged snapshot.
5. Use `git push` to send commits to a remote repository.

## 5. Common commands

| Command | Purpose |
|---|---|
| `git --version` | Check whether Git is installed |
| `git config --global user.name "Your Name"` | Set commit author name |
| `git config --global user.email "you@example.com"` | Set commit author email |
| `git init` | Initialise a repository |
| `git status` | Show working-tree and staging status |
| `git add filename` | Stage one file |
| `git add .` | Stage changes under the current directory |
| `git commit -m "message"` | Commit staged changes |
| `git log --oneline` | View compact commit history |
| `git diff` | View unstaged changes |
| `git branch` | List local branches |
| `git switch -c feature-name` | Create and switch to a branch |
| `git switch main` | Switch to the main branch |
| `git merge feature-name` | Merge a branch into the current branch |
| `git remote -v` | Show configured remotes |
| `git push -u origin main` | Push main and set its upstream |
| `git pull` | Fetch and integrate remote changes |
| `git clone REPOSITORY_URL` | Clone a remote repository |

## 6. Why commits matter
A commit records a meaningful set of staged changes. Good commit messages describe the change, for example:
- `Add Python greeting example`
- `Document basic Git commands`
- `Fix greeting output`

## 7. What I learned
After completing the practice, write 3–5 points here in your own words. For example, explain the difference between staging and committing, and between Git and GitHub.
