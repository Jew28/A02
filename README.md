# A02---IS117
**Part 1: Webstorm, Github, and GIT**

*Step 1: Downloading Webstorm*
- Go to : [https://www.jetbrains.com/webstorm/download/?section=windows]
- Download and install Webstorm for your operating system (Windows, Linux, or macOS)
- Sign in to Webstorm via a JetBrains account (if you do not have one, you can create one)

*Step 2: Install **Git***
- Go to: [https://git-scm.com/downloads]
- Download and install GIT for your operating system (Windows, Linux, or macOS)
- Complete the Git software setup (via the installation wizard)

*Step 3: Connecting Git to Webstorm*
- Open Webstorm, go to File, Settings, Version Control, and then Git
- Set the path to where your Git executable file is located (typically, it is auto-detected)
- Click the "Test" button to show that Git is working

_Step 3.5: Creating A **Repository**(Note: If you already have a repository created, you can skip this step)_
- Log in / Create your **GitHub** account
- Go to home, on the left, across from the text that says "Dashboard", click the green button that says "New" (This will allow you to create a repository)
- Fill out the steps to create your repository. Once it's created, move on to Step #4
- **Note: Make sure to add a README file!!**

*Step 4: Cloning Your Repository (In Webstorm)*
- Copy the link to your repository [Ex: https://github.com/yourGithubUsername/RepositoryName]
- Open Webstorm, go to File, then New, then "Project From Version Control"
- Paste the URL of your repository, then choose "from Local Directory"
- Then click "**Clone**"

*Step 4.5: Cloning your Repository (In GIT)*
- If you already cloned your repository in Webstorm, this step is unnecessary (this step is for those who don't want to use Webstorm)

*Step 5: Adding Files & Committing*
*Adding Files (Creating Files via Webstorm)*
- Choose File, then New, then HTML or CSS File (Ex: index.html or index.css)
- Write the content of the stated file in your code editor 

*Committing File (via GIT)*
- Once you've finished editing your files, go to 'GIT' and then move to the '**Commit**' button at the bottom
- Select the files you have changed
- Write a clear, concise message about changes made (Ex: added a timer feature)
- Then click 'Commit and **Push**' to send these changes to GitHub

*Step 6: Pull and **Fetch** any Updates*
- Go to 'Git' then '**Fetch**' to check if there are any updates from GitHub
- If there are updates, go to 'Git' and then '**Pull**' (this way local/**remote** files can be up to date)

*Step 7: **Merge Conflicts***
- If there are any issues attempting to merge, WebStorm will indicate it.
- Utilize the built-in 'Merge Tool' to solve any issues that arise
- Once changes are resolved, commit these changes to GitHub.
_________________________________________________________________________________________________________________________________________________________________

***Part 2: Terms and References***
_Terms:_
- ***Branch***: A separate line of development in a Git repository that allows you to work on features or fixes without affecting the main codebase.

- ***Clone***: To copy a remote Git repository (like one on GitHub) to your local machine so you can work on it.

- ***Commit***: A snapshot of changes you've made to files in your repository, saved with a message describing what was changed.

- ***Fetch***: Retrieves updates from a remote repository without applying them to your local branch. It lets you see what others have changed before merging.

- ***GIT***: A distributed version control system that tracks changes in source code during software development.

- **GitHub***: A cloud-based platform that hosts Git repositories and provides tools for collaboration, version control, and project management.

- ***Merge***: Combines changes from one branch into another, typically used to integrate feature branches into the main branch.

- ***Merge Conflict***: Occurs when Git cannot automatically combine changes from different branches because the same lines of code were changed in both.

- ***Push***: Sends your local commits to a remote repository, updating it with your latest changes.

- ***Pull***: Fetches changes from a remote repository and merges them into your local branch, keeping your code up to date.

- ***Remote***: A version of your repository hosted on a server like GitHub, which you can interact with using Git commands.

- ***Repository***: A storage space for your project that contains all files, folders, and version history tracked by Git.
__________________________________________________________________________________________________________________________________________________________________
**References**
- “Quickstart for Repositories.” GitHub Docs, docs.github.com/en/repositories/creating-and-managing-repositories/quickstart-for-repositories. Accessed 29 Sept. 2025.
- “Add Files to Git and Track Changes: WebStorm.” WebStorm Help, www.jetbrains.com/help/webstorm/adding-files-to-version-control.html. Accessed 29 Sept. 2025. 
- Hendela, Arthur  H. “Intro to GitHub.” 29 Sept. 2025. 
