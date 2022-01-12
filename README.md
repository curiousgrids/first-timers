# FirstTimers

📺 **Video explanation:-** <a href="https://youtu.be/1Bv4bhtNIaA" target="_blank">https://youtu.be/1Bv4bhtNIaA</a>

<img src="https://github.com/AkhileshThite/Portfolio/blob/main/Logos/git-github.jpg"></img>

<div align="center">
  <img src="https://visitor-badge.glitch.me/badge?page_id=CuriousGrids.FirstTimers" alt="visitors" />
  <img src="https://img.shields.io/github/issues-search/CuriousGrids/FirstTimers?label=merged%20PRs&query=is%3Apr+is%3Aclosed+is%3Amerged&color=purple" alt="Merged Pull Requests" />
</div>

## Git installation

Install Git from this link:- <a href="https://git-scm.com/downloads" target="_blank">https://git-scm.com/downloads</a>

To check the Git version

```bash
git --version
```

To set the global Git username & email address

```bash
git config --global user.name "your name"
git config --global user.email "your email"
```

## STEPS to contribute

Before you follow all these STEPS, make sure you `fork` the repository in your account.

1. Clone the repository using HTTPS or SSH (If you don't have 2FA enabled).

```bash
git clone https://github.com/CuriousGrids/FirstTimers.git
```

or PAT, more about it in the STEP 8.

```bash
git clone https://<GitHubToken>@github.com/<username>/<RepositoryName>.git
```

2. Create a new branch.

```bash
git branch YourBranchName
```

3. Shift to that branch from `main` branch.

```bash
git checkout YourBranchName
```

Add your name under `contributors list` in README.md with format `FirstName_LastName`

4. Add all the changes you've made.

```bash
git add .
```

5. Make a commit with a message of the changes you've done. Learn more about conventional commits [here](https://www.conventionalcommits.org/en/v1.0.0/).

```bash
git commit -m 'Add my contribution'
```

6. Shift to the master branch.

```bash
git checkout main
```

7. Merge everything from your branch to the master branch.

```bash
git merge YourBranchName
```

8. Get ready to push from your local machine.

If you don't have 2FA enabled, then use the normal HTTPS or SSH link.

```bash
git remote add <message> https://github.com/CuriousGrids/FirstTimers.git
```

Personal Access Token (PAT) is required if you enable 2FA on your Github account [[link]](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token).

```bash
git remote add <message> https://<GitHubToken>@github.com/<username>/<RepositoryName>.git
```

9. Push everything on your forked repository.

```bash
git push -u <message> main
```

## Contributor's list
Fuck You all bitches
