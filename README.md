# FirstTimers
📺 Video explanation:- https://youtu.be/1Bv4bhtNIaA

<img src="https://github.com/AkhileshThite/Portfolio/blob/main/Logos/git-github.jpg"></img>

<div align="center">
  <img src="https://visitor-badge.glitch.me/badge?page_id=CuriousGrids.FirstTimers" alt="visitors" />
  <img src="https://img.shields.io/github/issues/CuriousGrids/FirstTimers" alt="GitHub issues" />
  <img src="https://img.shields.io/github/issues-pr/CuriousGrids/FirstTimers" alt="GitHub pull requests" />
  <img src="https://img.shields.io/github/issues-search/CuriousGrids/FirstTimers?label=merged%20PRs&query=is%3Apr+is%3Aclosed+is%3Amerged&color=purple" alt="Merged Pull Requests" />
</div>


## git installation
Install git from this link:- https://git-scm.com/downloads

To check the git version
```
git --vesrion
```
To set the global git username & email address
```
git config --global user.name "your name"
git config --global user.email "your email"
```

## STEPS to contribute:
1. Initialize git repository.
```
git init
```
2. Create a new branch.
```
git branch YourBranchName
```
3. Shift to that branch from master branch.
```
git checkout YourBranchName
```
Add your name under ```contributors list``` in README.md with format ```FirstName_LastName```

4. Add all the changes you've made.
```
git add .
```
5. Make a commit message.
```
git commit -m 'your_message'
```
6. Shift to the master branch.
```
git checkout main
```
7. Merge everything from your branch to the master branch.
```
git merge YourBranchName
```
8. Get ready to push from your local machine.
```
git remote add <message> https://<GitHubToken>@github.com/<username>/<RepositoryName>.git
```
If you haven't setup your **Personal Access Token** yet, then follow the steps from [here](https://docs.github.com/en/github/authenticating-to-github/keeping-your-account-and-data-secure/creating-a-personal-access-token).

9. Push everything on your forked repository.
```
git push -u <message> main
```

## Contributors list :-
Firstname_Lastname
1. Hrishikesh Thite
2. Yashoda Rajmani
3. Shubham
4. Rahul_Agarwal
