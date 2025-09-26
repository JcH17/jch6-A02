# jch6-A02
Repo created for IS117 a02

**Software to Install**
* Git (required): https://git-scm.com/downloads
* Windows direct link: https://git-scm.com/downloads/win
* macOS options (Homebrew/MacPorts): https://git-scm.com/downloads/mac
* Linux: https://git-scm.com/downloads/linux

* GitHub account (free): https://github.com/signup

* WebStorm (IDE): https://www.jetbrains.com/webstorm/download/

**Directions for using webstorm with git/github
* Install Git using the links above (Windows/macOS/Linux)[2,8]
* Install WebStorm and start it
* Create or sign in to your GitHub account[9]
* Open Settings[3]
* Go to Version Control | Git and verify the Path to Git executable (WebStorm often auto-detects it). [3]
* Click Test; you should see “Git executed successfully.”[3]
* Click OK.[3]
* Open Settings -> Version Control -> GitHub, click Add account, then log in via GitHub and authorize JetBrains in the browser window[4]
* Create a project in WebStorm
* Open the project, then go VCS -> Enable Version Control Integration -> Git[3]
* Go Git -> Commit (or use the Commit tool window), write a short message, and Commit[5]
* Go Git -> GitHub -> Share Project on GitHub[4]
* Open the repo -> click Code -> copy the HTTPS or SSH URL[10]
* On the Welcome screen click Get from VCS, paste the URL, choose a local folder, and click Clone.[3,4,10]
* Pull (or Fetch) before you start[6]
* Make your changes and Commit often[5]
* Push changes when ready[5]

**Glossary**
* **Branch**: A movable pointer to a series of commits, used to develop features or fixes in isolation before merging back
* **Clone**: A local copy of a remote repository, including all history, branches, and files
* **Commit**: A snapshot of changes in your repository, recorded with a unique ID and message
* **Fetch**: Downloads new commits and refs from the remote without merging them into your current branch
* **GIT**: A distributed version control system for tracking changes in code and coordinating work across teams
* **Github**: A hosting platform for Git repositories that adds collaboration tools like issues, pull requests, and actions
* **Merge**: Combining the histories of two branches, typically bringing a feature branch back into main
* **Merge Conflict**: A situation where Git can’t automatically merge changes and needs you to choose the correct result
* **Push**: Uploading your local commits to the remote repository on GitHub
* **Pull**: Fetching from the remote and then merging into your current branch
* **Remote**: A named reference to a repository hosted elsewhere
* **Repository**: The project’s database of files and full history. It can be local (on your computer) or remote (on GitHub)

**Resources**
* [1]Hendela, A. Introduction to GitHub and WebStorm (IS117)
* [2]Hendela, A. Additional Instructions on Creating a Git & GitHub Repository
* [3]JetBrains — Set up a Git repository (WebStorm Help)
* [4]JetBrains — Manage projects hosted on GitHub (Share/Clone from WebStorm)
* [5]JetBrains — Commit and push changes
* [6]JetBrains — Sync with a remote repository (fetch/pull/update)
* [7]JetBrains — Tutorial: Getting started with Git in WebStorm (branches/merges/conflicts) 
* [8]Git — Downloads (Windows/macOS/Linux) and Installing Git
* [9]GitHub Docs — Creating an account on GitHub.
* [10]GitHub Docs — Cloning a repository
