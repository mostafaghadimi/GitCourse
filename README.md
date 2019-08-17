# **Git Course Syllabus**

- What is Version Control (Final, Final Final Final :)), Final ... Final Project, Copy Paste! Project into different systems)
- Why should we use VC?
- What is GIT?
> Version Control System (VCS) for tracking changes in computer files. 
1. distributed version control (Photo + Description)
2. Coordinates work between multiple developers
3. Who made what changes and when
4. Revert back at any time
5. Local & remote repositories

- Git Concepts
1. keeps track of code history
takes snapshots of your files
you decide when to take a snapshot by making a commit
You can visit any snapshot any time
You can stage files before commiting

- Git usage in Programming Interviews and prerequisites (Show Ads on different sites)
- Installing git for different Platforms (www.git-scm.com) -> git --version
- Create account on Github.com
- 

- working tree
- staging area (Commited, untracked, Staged, Modified) {git Locations}
 
 > set config values
 git config --global user.name "Your name"
 git config --global user.email "Your email"
 git config --list


git help <verb>
git <verb> --help

 - git stages (Commited, Staged, Modified)
 Basic Commands
 - git init
 - git add
 - git status
 - git commit
 - git push
 - git pull
 - git clone
 - git log
 - .gitignore
 - git branches
 - talk about github
 - git tag
 - git conflict
 - debug


advanced
git reset
git revert


 GIT best tools: :?
 
 
 change the origin:
git remote rm origin
git remote add origin git@github.com:username/repositoryName.git
git config master.remote origin
git config master.merge refs/heads/master



ssh key
cd ~/.ssh
ssh-keygen -o
cat ~/.ssh/id_rsa.pub
