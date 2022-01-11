# Setting Up Your Computer

Welcome to day 1 at BloomTech, today we are going to spend time setting up your computer and learning the tools that you will be using to complete this program. Just like day 1 at a job, you will need to get your environment set up to build and run your code. Complete the set up tasks below and then get started on the research questions. Once you have finished check out the submission instructions in the `README.md` file to turn in your assignment for the day.

## Set Up Tasks

1. [x] [Download xcode](https://apps.apple.com/us/app/xcode/id497799835?mt=12) - these are your developer tools for mac
2. [x] sign up for a [GitHub account](https://github.com/join) - please use a professional username. We recommending using your `firstname` `lastname`
3. [x] [Set up your SSH key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) - GitHub uses SSH to keep their files secure. You will need to set up one SSH key for every computer that you want to access your GitHub account on. Please ensure you go through all of the steps to generate a new key, add a new key and test your connection.
4. [x] [Download Zoom](https://zoom.us/download) - make sure your zoom display name is your `first name` `last name`
5. [x] [Download Slack](https://slack.com/help/articles/207677868-Download-Slack-for-Mac) - make sure your slack display name is your `first name` `last name`
6. [x] [Download VS code](https://code.visualstudio.com/download) - this will be the tool you use to write all of your code. We recommend installing the following extensions:

- [ES Lint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
- [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)

7. [x] [Download Node.JS](https://nodejs.org/en/) - Please download the latest stable version. We will be using Node.JS to run the tests in all of our javaScript assignments. Test driven development is a common practice in the world of web dev. You can read more about it [here](https://www.freecodecamp.org/news/test-driven-development-what-it-is-and-what-it-is-not-41fa6bca02a2/)
8. [x] Sign up for a free [codepen account](https://codepen.io/accounts/signup/user/free)
9. [ ] Sign up for a free account on [Lucid Chart](https://www.lucidchart.com/pages/landing?utm_source=google&utm_medium=cpc&utm_campaign[…]tTwOoXp_lCeLTC97pikTFa5cE58FWHwjjpTSGsGPRqR2AAaAh-MEALw_wcB)

## Research Questions

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You can type your answer below the questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en) doc short for documentation are the instructions on how to use a languge, or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your google skills.

1. What is git? What is the difference between git and GitHub?
   A: Git is an Open Source Distributed version Control System. GitHub on the other hand is a for profit company that offers a cloud based git hosting service & is the largest host of source code in the world.Projects on GitHub can be accessed and manipulated using the standard git command-line interface, and all of the standard git commands work with it.
2. Why do we create a branch?
   A: we create a branch to isolate your work from other team members when working on new features or bug fixes.
3. What is the purpose of a pull request?
   A: for a developer to notify team members that they have completed a feature.
4. What is the command you can use to switch between branches? For example you are working on a feature branch and you want to switch back to main.
   A: Use the "git checkout" command and specify the name of the branch you want to switch to. if the destination branch doesn't exist , you have to add "-b", otherwise you won;t be able to switch to that branch.
5. Explain the difference between `git fetch`, `git merge` and `git pull` what does each command do?
   A: `git fetch`: The `git fetch` command tells your local git to retrieve the latest meta-data info from the original (yet doesn't do any file transferring.its just checking to see if there are any changes available)
   `git pull`: The `git pull` command not only tells the local git to retrieve the latest meta data from the original but also transfers the files. it is used to update the local version of the repository from the remote.
   `git merge`: The `git merge` command puts the a forked history back together. The `git merge` command lets you take the independent lines of development created by git branch and integrate them into a single branch. The current branch will be updated to reflect the merge, but the target branch will be completely unaffected.

6. What is a merge conflict? How do you resolve a merge conflict?
   A: A merge conflict happens when people make different changes to the same line of the same file or when Git is unable to automatically resolve the differences in code between two commits.To resolve these conflicts, you pull the changes to your local repository and fix them there.
