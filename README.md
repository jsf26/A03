# A03
Step 1: How to setup github
1.1: Create a repository
1.2: Clone your repository to a directory 
1.3: To commit changes to a file you can use two different avenues; you can commit on webstorm using the green check mark or you can commit on git by using the command "git commit -m '  ' "
1.4: To push changes to a file you can use two different avemues; you can push on on webstorm using the green diagonal arrow or you can push on git by using the command "git push origin master".



Step 2: How to setup webstorm
2.1: Create a new file HTML5 or Stylesheet
2.2: Using the whitespace, edit your code
2.3: After making changes to your file , you can commit these changes to your github by refering to step 1.3



Step 3: How to setup git
3.1: In order use git functionality within webstorm you will have to user version control
3.2: To access Version Control, press (ctrl +atl + s)->Git-> download and install git
3.3: (Other route)-> Run git as an administrator, use commands from 1.3 and 1.4 to commit and push changes 





# Glossary
Branch - A branch is a parallel version of a repository. It is contained within the repository, but does not affect the primary or master branch allowing you to work freely without disrupting the "live" version. When you've made the changes you want to make, you can merge your branch back into the master branch to publish your changes.

Clone - A clone is a copy of a repository that lives on your computer instead of on a website's server somewhere, or the act of making that copy. When you make a clone, you can edit the files in your preferred editor and use Git to keep track of your changes without having to be online. The repository you cloned is still connected to the remote version so that you can push your local changes to the remote to keep them synced when you're online.

Commit - A commit, or "revision", is an individual change to a file (or set of files). When you make a commit to save your work, Git creates a unique ID (a.k.a. the "SHA" or "hash") that allows you to keep record of the specific changes commited along with who made them and when. Commits usually contain a commit message which is a brief description of what changes were made.

Fetch - When you use git fetch, you're adding changes from the remote repository to your local working branch without committing them. Unlike git pull, fetching allows you to review changes before committing them to your local branch.

GIT - Git is an open source program for tracking changes in text files. It was written by the author of the Linux operating system, and is the core technology that GitHub, the social and user interface, is built on top of.

Github - GitHub Apps provide a service to an entire organization and use their own identity when performing their function. They can be installed directly on organizations and user accounts and granted access to specific repositories. They come with granular permissions and built-in webhooks.

Merge - Merging takes the changes from one branch (in the same repository or from a fork), and applies them into another. This often happens as a "pull request" (which can be thought of as a request to merge), or via the command line. A merge can be done through a pull request via the GitHub.com web interface if there are no conflicting changes, or can always be done via the command line.

Merge Conflict - A difference that occurs between merged branches. Merge conflicts happen when people make different changes to the same line of the same file, or when one person edits a file and another person deletes the same file. The merge conflict must be resolved before you can merge the branches.

Push - To push means to send your committed changes to a remote repository on GitHub.com. For instance, if you change something locally, you can push those changes so that others may access them.

Pull - Pull refers to when you are fetching in changes and merging them. For instance, if someone has edited the remote file you're both working on, you'll want to pull in those changes to your local copy so that it's up to date. See also fetch.

Remote - This is the version of a repository or branch that is hosted on a server, most likely GitHub.com. Remote versions can be connected to local clones so that changes can be synced.

Repository - A repository is the most basic element of GitHub. They're easiest to imagine as a project's folder. A repository contains all of the project files (including documentation), and stores each file's revision history. Repositories can have multiple collaborators and can be either public or private.


# Reference
https://docs.github.com/en/free-pro-team@latest/github/getting-started-with-github/github-glossary#pull
https://njit.instructure.com/courses/12494/files/984298?module_item_id=248629

