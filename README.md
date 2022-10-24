# FirstTimers

📺 **Video explanation:-** <a href="https://youtu.be/1Bv4bhtNIaA" target="_blank">https://youtu.be/1Bv4bhtNIaA</a>

<img src="https://github.com/AkhileshThite/Portfolio/blob/main/Logos/git-github.jpg"></img>

<div align="center">
  <img src="https://visitor-badge.glitch.me/badge?page_id=CuriousGrids.FirstTimers" alt="visitors" />
  <img src="https://img.shields.io/github/issues-pr-closed/curiousgrids/firsttimers?color=green" alt="Merged Pull Requests" />
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

1. Clone the repository.

If you don't have 2FA enabled, then use the normal HTTPS or SSH link.
```bash
git clone https://github.com/CuriousGrids/FirstTimers.git
```

Personal Access Token (PAT) is required if you enable 2FA on your Github account [[link]](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token).
For that, use the following command instead of the normal URL command.

```bash
git clone https://<GitHubToken>@github.com/<username>/<RepositoryName>.git
```

2. Create a new branch.

```bash
git branch YourBranchName
```

3. Shift to that branch from master (`main`) branch.

```bash
git checkout YourBranchName
```

Add your name under `contributors list` in README.md with format `FirstName_LastName`

4. Add all the changes you've made.

```bash
git add .
```

5. Make a commit message of the changes you've made. Learn more about conventional commits [here](https://www.conventionalcommits.org/en/v1.0.0/).

```bash
git commit -m 'Add my contribution'
```

6. Shift to the master (`main`) branch.

```bash
git checkout main
```

7. Merge everything from your branch to the master (`main`) branch.

```bash
git merge YourBranchName
```

8. Get ready to push from your local machine.

If you don't have 2FA enabled, then use the normal HTTPS or SSH link.

```bash
git remote add <message> https://github.com/CuriousGrids/FirstTimers.git
```

Personal Access Token (PAT) is required if you enable 2FA on your Github account [[link]](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token).
For that, use the following command instead of the normal URL command.

```bash
git remote add <message> https://<GitHubToken>@github.com/<username>/<RepositoryName>.git
```

9. Push everything on your forked repository.

```bash
git push -u <message> main
```

Now, click on `Pull Request` button, you'll have the option to **create a pull request**. i.e., `<your forked repo> -> <original repo>`, That's it you're done!

## Contributor's list

Firstname Lastname

1. Hrishikesh Thite
2. Yashoda Rajmani
3. Shubham
4. Rahul Agarwal
5. Manmeet Kaur
6. Jaideep Singh
7. Rohit Tewari
8. Pankaj
9. Ashutosh Kumar Choudhary
10. Priyanshu Vaishnavi
11. Pooja Bennabhaktula
12. Pranay Gupta
13. Km Pooja
14. Pranav Singh
15. Avid Coder
16. Rahul Mishra
17. Harshit Aditya
18. Sushant Patial
19. Raghav Gupta
20. Saloni Jain
21. Kinjalk Bajpai
22. Priyal Palkhiwala
23. Aman Shrivastava
24. Akshay Mohan
25. Nishant Shenoy
26. Narayan Soni
27. Faraz Hussain
28. Vrattica Yadav
29. Siddharth Sabale
30. Ishika Saha
31. Ashish Jaiswal
32. Ishika Jaiswal
33. Ramya Chinnadurai
34. Suraj P
35. MuhammadNurAshiddiqi
36. JonMoon
37. Harshit Vishwakarma
38. Skyrub dev
39. Aman Upadhyay
40. Hritvik Mohan
41. Kushagra Jaiswal
42. Rishika Garg
43. Will Kemp
44. Chandra Bose
45. kiran k
46. Sai Aswin Madhavan
47. Tran Nguyen Thuong Truong
48. Ayush Kumar
49. Rohan Kambli
50. Lavakush Biyani
51. Hrutika Badgeri
52. Kumaran T
53. Eleena Sarah
54. Anushka Jain
55. Josh Ball
56. Bibek Rai
57. Andrew M
58. Kruthi S
59. Aaryaman Shah
60. Karan Chandekar
61. Ashish Bibyan
62. Divya
63. Raj
64. Ghada
65. Anushree Pal
66. Fai Zaben
67. Varshitha Manjunath
68. Luis G
69. Hari Charan Kandregula
70. Fadhel Alanazi
71. Raghad Alsarhan
72. Matteo Spada
