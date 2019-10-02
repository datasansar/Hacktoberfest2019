# Hacktoberfest 2019
Hello hackers!!! :octocat: This is a beginner-friendly repo for Hacktoberfest to help get your first PR and takes you a step closer to earning your Hacktoberfest T-shirt 👕.

🎯 If you are a beginner and looking for your first contribution, we are here to help. Just append your favorite git command and its short description in our <a href="https://github.com/sdnepal/Hacktoberfest2019/blob/master/beginner/json-files/git-commands.json" target="blank">git-commands.json</a> and that counts as your first PR.


> Note: Put description under 60 words at max. 

Also, add your github username in the <a href="https://github.com/sdnepal/Hacktoberfest2019/blob/master/beginner/contributers_list.md" target="blank">contributors_list.md</a>

🎯 In case you are an intermediate or advanced level programmer or developer, we have got you covered too!! Step to our <a href="https://github.com/sdnepal/Hacktoberfest2019/tree/master/Intermediate" target="blank"> intermediate folder</a> and make contributions as per as your interests.

> 💻 We are open to contributions from anyone to help us in making bigger and better. 

<br>

> Check our site: <a href="https://hacktm.js.org/" target="blank">hacktm.js.org</a>  and reference guide [how to use git](https://www.digitalocean.com/community/tutorials/how-to-use-git-a-reference-guide).

## Instructions to follow:

### 1. Register yourself for Hacktoberfest 2019

- Link: [hacktoberfest.digitalocean.com](https://hacktoberfest.digitalocean.com/)

### 2. Getting Started

- First, visit our site: [hacktm.js.org](https://hacktm.js.org)

- Move to Instructions by clicking on the button <pre>START CONTRIBUTING</pre> 

- Read the Instructions and click Done at the end to move to the repository or <a href="https://github.com/sdnepal/Hacktoberfest2019">click here</a> to head to the repository.

### 3. Star and Fork this Repository

- You can star ⭐ and fork 🍽️ this repository on GitHub by navigating at the top of this repository.

- Here, **sdnepal** is the owner of the hacktoberfest repository, so the GitHub URL for this project is: 

> <a href="https://github.com/sdnepal/Hacktoberfest2019" target="blank">https://github.com/sdnepal/Hacktoberfest2019</a>

- When you’re on the main page for the repository, you’ll see a button to "Star" and “Fork” the repository on your upper right-hand side of the page, underneath your user icon.

### 4. Clone the Repository

- To make your local copy of the repository you would like to contribute to, let’s first open up a terminal window.

- We’ll use the `git clone`  command along with the URL that points to your fork of the repository.

- This URL will be similar to the URL above, except now it will end with `.git.` In the example above, the URL will look like this:

> https://github.com/your-username/Hacktoberfest2019.git

- You can alternatively copy the URL by using the green “Clone or download” button from your repository page that you just forked from the original repository page. Once you click the button, you’ll be able to copy the URL by clicking the binder button next to the URL.

- Once we have the URL, we’re ready to clone the repository. To do this, we’ll combine the git clone command with the repository URL from the command line in a terminal window:

> `git clone https://github.com/your-username/Hacktoberfest2019.git`


### 4. Create a New Branch

- To create your branch, go to your terminal window and change your current directory to your working directory. Also, use actual name of the repository (i.e. Hacktoberfest2019) to change into that directory.

> ` cd Hacktoberfest2019`

- Now, we’ll create our new branch with the git branch command. Make sure you name it descriptively so that others working on the project understand what you are working on.

> `git branch new-branch`

- Now that our new branch is created, we can switch to make sure that we are working on that branch by using the git checkout command:

 ` git checkout new-branch `

- Once you enter the git `checkout` command, you will receive the following output:

> `Output:` 
> `Switched to branch 'new-branch' `

 
- At this point, you can now modify existing files or add new files to the project on your branch.

- Make sure you have read the <a href="https://github.com/sdnepal/Hacktoberfest2019/blob/master/.github/ISSUE_TEMPLATE/contributing.md">contributing.md</a> before you start contributing such that you make remarkable and easily acceptable PRs.

<br>

#### Make Changes Locally.

- When making your beginner level contribution in this repository, find <a href="https://github.com/sdnepal/Hacktoberfest2019/tree/master/beginner/json-files">git-commands.json</a> and add your favourite git command along with a two-three lines short description in the JSON file.

> Note: JSON files follow a certain format, do not forget to add a comma before you start editing your block and it's good if you append a comma after finishing your block.

-  Also, if you are interested in making intermediate or advanced level contributions, head to our <a href="https://github.com/sdnepal/Hacktoberfest2019/tree/master/Intermediate">intermediate section</a> and make your mark.

- Once you have modified existing files or added new files to the project, you can add them to your local repository, which you can do with the git add command. Let’s add the -A flag to add all changes that we have made:

> ` git add -A ` or ` git add . `

- Next, we’ll want to record the changes that we made to the repository with the git commit command.

- The commit message is an important aspect of your code contribution; it helps the other contributors fully understand the change you have made, why you made it, and how significant it is. ` contributing.md `


- If you have a very short message, you can record that with the `-m` flag and the message in quotes:

> `git commit -m "Updated Readme.md" `



- At this point you can use the git push command to push the changes to the current branch of your forked repository:

> ` git push --set-upstream origin new-branch `


### 5. Update Local Repository

- While working on a project alongside other contributors, you need to keep your local repository up-to-date with the project as you don’t want to make a pull request for code that will cause conflicts. To keep your local copy of the codebase updated, you’ll need to sync changes.

- We’ll first go over configuring a remote for the fork, then syncing the fork.

### 6. Configure a Remote for the Fork

- Next, you’ll have to specify a new remote upstream repository for us to sync with the fork. This will be the original repository that you forked from. you’ll have to do this with the git remote add command.

> ` git remote add upstream https://github.com/sdnepal/Hacktoberfest2019 `

- In this example, // upstream // is the short name we have supplied for the remote repository since in terms of Git, “upstream” refers to the repository that you cloned from. If you want to add a remote pointer to the repository of a collaborator, you may want to provide that collaborator’s username or a shortened nickname for the short name.

### 7. Sync the Fork

-  Now you are ready to sync your fork of the repository to keep it up-to-date.

- To sync your fork, open terminal window, you’ll have to use the `git fetch` command to fetch the branches along with their respective commits from the upstream repository. Since you used the short name “upstream” to refer to the upstream repository, you’ll have to pass that to the command:

> ` git fetch upstream `

- Switch to the local master branch of our repository:

> ` git checkout master `

- Now merge any changes that were made in the original repository’s master branch, that you will access through your local upstream/master branch, with your local master branch:

> ` git merge upstream/master `

### 8. Create Pull Request

- At this point, you are ready to make a pull request to the original repository.

- Now navigate to your forked repository, and press the “New pull request” button on your left-hand side of the page.

### :congratulations: Congrats !!! You just completed a step for the hacktoberfest challenge. 😃

### Happy?? Star ⭐ this Repo. 
<br>

#### Check your <a href="https://hacktoberfest.digitalocean.com/profile" target="blank">Hacktoberfest Contribution status</a>

<center>
<br><br>

![ForTheBadge built-with-love](http://ForTheBadge.com/images/badges/built-with-love.svg) 

[Hacktoberfest Kathmandu](https://hacktm.js.org) &copy; 2019

</center>
