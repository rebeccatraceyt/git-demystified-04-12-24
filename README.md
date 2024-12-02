![Code Institute Logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)
# Git Demystified!
(Live tutoring session 04/12/2024)

## 👋 Intro
Welcome to the pratical repository for the Live tutoring session on Git: Demystified

## 🎯 Purpose
The purpose of the repository is to test your knowledge on what was covered during the session!
You can fork this repository, and create a new branch using the steps below:

### To fork:
1. At the top of the repository, on the right side of the page, select "Fork".
2. You should now have a copy of the original repository in your GitHub account.
3. In your copy of the repository, you can click the green GitPod button to open a new workspace

Table of Contents:
1. [🤝 Contribute](#-contribute)
2. [💻 Make a Pull Request](#-make-a-pull-request)
3. [📢 Roll Call!](CONTRIBUTORS.md)

## 🤝 Contribute
Once you're up and running in your own workspace, you can create a new branch and contribute to [contributors list](./CONTRIBUTORS.md) 

To do that you can use the following steps (make sure to replace placeholders with your GitHub username):
1. Create a new branch with:
```
git checkout -b your_github_username
```
2. Add a new remote pointing to the session repo, to make sure we are working with the most up-to-date version of the repository:
```
git remote add upstream https://github.com/rebeccatraceyt/git-demystified-04-12-24.git
```
3. Once the remote has been connected, verify that you have two remotes with:
```
git remote -v 
```
4. Check the logs, to see the commits of the repo:
```
git log origin
```

5. Check the list of branches on the tree (to make sure your branch is included):
```
git branch
```

6. Add your GitHub username to the [contributors list](./CONTRIBUTORS.md), with a link to your GitHub page. You can use this template below:
```
[@your_github_username](https://github.com/your_github_username)
```

7. Save and commit your changes with:
```
git add .
git commit -m "Docs: Add your_github_username"
```

8. Make sure your branch stays up to date with the original repository by checking out the main branch and pulling from the upstream repository:
```
git checkout main
git pull upstream main
```

9. Then, go back to your branch and make sure your branch incorporates any changes:
```
git checkout your_github_username
git merge main
```

10. Then, push to your new branch with:
```
git push origin your_github_username
```

## 💻 Make a Pull Request

1. Navigate to the original repository (where you created your fork)

2. Above the list of files,  click `Compare & pull request` to create a pull request for the associated branch.

3. On the page to create a new pull request, click `compare across forks`.

4. In the "base branch" dropdown menu, select the branch of the upstream repository you'd like to merge changes into. This would be the original repository (`rebeccatraceyt/main`)

5. In the "head fork" dropdown menu, select your fork, then use the "compare branch" drop-down menu to select the branch you made your changes in.

6. Add a title and description for your pull request.
#### Title:
```
[DOCS]Add your_github_username
```

#### Description:
```
Adding your_github_username to the list of contributors
```
7. To create a pull request that is ready for review, click Create Pull Request.