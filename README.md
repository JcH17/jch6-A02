# jch6-A02
Repo created for IS117 a02

**Software to Install**
* Git (required): https://git-scm.com/downloads
* Windows direct link: https://git-scm.com/downloads/win
* macOS options (Homebrew/MacPorts): https://git-scm.com/downloads/mac
* Linux: https://git-scm.com/downloads/linux

* GitHub account (free): https://github.com/signup

* WebStorm (IDE): https://www.jetbrains.com/webstorm/download/

Directions for using webstorm with git/github
* Install Git using the links above (Windows/macOS/Linux)
* Install WebStorm and start it
* Create or sign in to your GitHub account
* Open Settings
* Go to Version Control | Git and verify the Path to Git executable (WebStorm often auto-detects it). 
* Click Test; you should see “Git executed successfully.”
* Click OK.
* Open Settings -> Version Control -> GitHub, click Add account, then log in via GitHub and authorize JetBrains in the browser window
* Create a project in WebStorm
* Open the project, then go VCS -> Enable Version Control Integration -> Git
* Go Git -> Commit (or use the Commit tool window), write a short message, and Commit
* Go Git -> GitHub -> Share Project on GitHub
* Open the repo -> click Code -> copy the HTTPS or SSH URL. 
* On the Welcome screen click Get from VCS, paste the URL, choose a local folder, and click Clone.
* Pull (or Fetch) before you start
* Make your changes and Commit often
* Push changes when ready

Glossary
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
