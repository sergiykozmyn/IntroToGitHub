# IntroToGitHub

A beginner's learning repository for practicing Git, GitHub, and Markdown as part of CSCI 1000 at the University of Colorado Boulder.

## About This Repository

This repository documents foundational version control concepts and the Git commands I have practiced. It is a learning resource, not a software application, so there is no program to install or run.

## What Is Version Control?

Version control is a system for tracking changes to files over time. It helps developers review earlier versions, restore work, and collaborate while keeping a record of changes.

## What I Learned

I used this repository to practice initializing a repository, staging files, committing changes, and pushing work to GitHub. I also learned how SSH keys can authenticate a local Git connection to GitHub.

## SSH Authentication

SSH authentication uses a public and private key pair to connect a local Git repository to GitHub. The public key can be added to GitHub; the private key should remain secret and should never be committed to a repository.

## Basic Git Commands

| Command | Purpose |
|---|---|
| `git init` | Creates a new local Git repository. |
| `git add` | Stages changes for a commit. |
| `git commit` | Saves staged changes to local history. |
| `git push` | Uploads commits to GitHub. |
| `git pull` | Retrieves and integrates remote changes. |
| `git branch` | Lists or creates branches. |
| `git merge` | Combines changes from another branch. |
| `git stash` | Temporarily saves uncommitted changes. |
| `git checkout` | Switches branches or restores files. |

## Setup

You do not need to install this repository as an application. To view or edit the files locally:

1. Install [Git](https://git-scm.com/downloads) if it is not already installed.
2. Clone the repository using Git:

   ```bash
   git clone git@github.com:sergiykozmyn/IntroToGitHub.git
   ```

3. Open the `IntroToGitHub` folder in a text editor to review or edit its files.

If SSH is not configured on your computer, use GitHub's HTTPS clone option instead of the SSH address above.

## Usage

Use this repository to review the notes and Git command table. To update the README, edit `README.md`, save your changes, and then stage, commit, and push them:

```bash
git add README.md
git commit -m "Improve README with Markdown sections"
git push
```

## Markdown Image Example

To include an image in this README, first add an image file to the repository (for example, `images/readme-preview.png`), then use Markdown like this:

```markdown
![Screenshot showing the IntroToGitHub README on GitHub](images/readme-preview.png)
```

The example above is a template. Replace the path and description with the actual image you add. Do not leave it in place unless that image file exists in the repository.

## Helpful Resource

- [Markdown Guide](https://www.markdownguide.org/): a reference for Markdown syntax.

---

This README is part of my CSCI 1000 GitHub learning project.
