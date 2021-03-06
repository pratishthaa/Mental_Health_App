# Contributing Guidelines

We are happy to welcome every contibutor who is willing to improve/add new things to our project.

### Need some help regarding the basics?🤔

You can refer to the following articles on basics of Git and Github and also contact the Project Mentors,
in case you are stuck:
- [Getting started with Git and GitHub](https://towardsdatascience.com/getting-started-with-git-and-github-6fcd0f2d4ac6)
- [Forking a Repo](https://help.github.com/en/github/getting-started-with-github/fork-a-repo)
- [Cloning a Repo](https://help.github.com/en/desktop/contributing-to-projects/creating-an-issue-or-pull-request)
- [How to create a Pull Request](https://opensource.com/article/19/7/create-pull-request-github)
- [Learn about Github issues](https://docs.github.com/en/issues)
- [Learn GitHub from Scratch](https://lab.github.com/githubtraining/introduction-to-github)

## Submitting Contributions👩‍💻👨‍💻

Below you will find the process and workflow used to review and merge your changes.

### Step 0 : Find an issue

- Take a look at the Existing Issues or create your **own** Issues!
- Wait for the Issue to be assigned to you after which you can start working on it.
- Note : Every change in this project should/must have an associated issue.



### Step 1 : Fork the Project

- Fork this Repository. This will create a Local Copy of this Repository on your Github Profile.
Keep a reference to the original project in `upstream` remote.  

```bash
git clone https://github.com/<your-username>/<repo-name>  
cd <repo-name>  
git remote add upstream https://github.com/<upstream-owner>/<repo-name>  
```  

  

- If you have already forked the project, update your copy before working.

```bash
git remote update
git checkout <branch-name>
git rebase upstream/<branch-name>
```  

### Step 2 : Branch

Create a new branch. Use its name to identify the issue your addressing.

```bash
# It will create a new branch with name Branch_Name and switch to that branch 
git checkout -b branch_name
```

### Step 3 : Work on the issue assigned

- Work on the issue(s) assigned to you.
- Add all the files/folders needed.
- After you've made changes or made your contribution to the project add changes to the branch you've just created by:

```bash  
# To add all new files to branch Branch_Name  
git add .  
# To add only a few files to Branch_Name
git add <some files>
```

### Step 4 : Commit

- To commit give a descriptive message for the convenience of reviewer by:

```bash
# This message get associated with all files you have changed  
git commit -m "message"  
```

- **NOTE**: A PR should have only one commit. Multiple commits should be squashed.

### Step 5 : Work Remotely

- Now you are ready to your work to the remote repository.
- When your work is ready and complies with the project conventions, upload your changes to your fork:

```bash  
# To push your work to your remote repository
git push -u origin Branch_Name
```

 

### Step 6 : Pull Request

- Go to your repository in browser and click on compare and pull requests.
Then add a title and description to your pull request that explains your contribution.  
  


- Voila! Your Pull Request has been submitted and will be reviewed by the moderators and merged.🥳

### Tip from us😇

It always takes time to understand and learn. So, do not worry at all. We know **you have got this**!💪
We believe every contribution is 'worth it'. Always keep in mind that **No contribution is too small**,so
just go ahead and be a part of our contributor family.
