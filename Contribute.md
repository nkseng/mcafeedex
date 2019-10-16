Download and install git for your operating system: https://git-scm.com/downloads
Make a GitHub account: https://github.com/join?source=header-home


on your computer, choose a directory to store the repo.
Clone your fork, replacing [your-github-username] with your GitHub username:
git clone https://github.com/[your-github-username]/mcafeedex.git
cd mcafeedex
Create a branch (replace 'feature-branch-name' with a short descriptive name of your feature, no spaces):
git checkout -b feature-branch-name
Push the new branch to your github fork:
git push -u origin feature-branch-name
Edit code using the code editor of your choice, when you are ready, commit your changes
git commit -am "A descriptive commit message"
git push origin feature-branch-name

Now that you have pushed updates to your fork, you can create the pull request
Login and go to your repo fork page on Github, Click on the "Pull Requests" tab
https://github.com/[your-github-username]/mcafeedex/pulls

Click the "New pull request" green button

This will take you to a page, "Comparing changes" ...

Choose the base repository as "Mshuu/mcafeedex", master branch, in the left select options

Choose your fork, and the new branch you just created in the right set of select options

Click the "Create pull request" green button

Enter a short descriptive title for the pull request title. 

Enter a description, any relevant information necessary for the developers to understand what the pull request is for.

If you are working on an existing issue in the repo's issue queue, include a link to the issue.


