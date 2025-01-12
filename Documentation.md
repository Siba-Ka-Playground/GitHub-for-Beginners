# Beginners Level Git and GitHub Commands 

## Git: 
  Git is a distributed version control system that helps developers track changes to their code and collaborate on software projects.

## The main features of Git:
1.  Version Control:
Git keeps track of all changes made to a codebase, allowing developers to manage different versions of files over time.

2. Local Repositories: 
Git works on a local repository on a developer's machine. This means developers can work offline and commit changes to their local repository without needing 
to be connected to the internet.

3. Branching and Merging: 
Git allows for branching, which lets developers create separate versions of the project to work on different features. Once a feature is complete, it can be 
merged back into the main project.

4. Distributed:
Every developer has a full copy of the entire repository, meaning they can work independently and later synchronize changes with others.

5. Tracking History: 
Git tracks all changes made to the code, allowing developers to see the history of a project and revert to previous versions if necessary.

## GitHub:

GitHub is a cloud-based platform that uses Git for version control, but it adds several collaborative features. They are;
Remote Repository Hosting: GitHub provides cloud-based repositories where developers can store their code, making it easy to share with others and collaborate on projects.

Collaboration: GitHub allows developers to work together on a single project by pushing and pulling changes from a shared repository. It also supports features like issues, pull requests, and code reviews, making it easier to manage collaborative workflows.

Pull Requests: Developers can create pull requests (PRs) to propose changes to the codebase, which can be reviewed and merged by other contributors.

Documentation and Wikis: GitHub provides tools for hosting documentation alongside the code, including markdown support and wikis for detailed project descriptions.

Continuous Integration (CI): GitHub integrates with various CI/CD (Continuous Integration/Continuous Deployment) tools, allowing automated testing, builds, and deployments directly from GitHub repositories.

Social Features: GitHub also has a social aspect, where developers can follow each other, star repositories, and contribute to open-source projects.

Configuring Git:

git config -- global user.name "My Name"
git config -- global user.email "name@gmail.com"
git config -- list {To check the list of configuration}

Clone and Status Command:

Clone :- Cloning a Repository on the local Machine.
git clone <-link->

Status :- Displays the state of the code.
git status

Types of state of the code:

Untracked (new file)
Modified (Changes made in existing file)
Unmodified (Unchanged)
Staged (File is ready to be committed)

Add and Commit Command:

Add :- Add a new file
git add <-file name->

Commit :- Record of change
git commit - m "message to display"

Push Command:

Push :- Upload local repository to the remote repository.
git push origin main

init Command:

init :- Used to create a new git repository
git init
git remote add origin <-link->
git remote - v  (To verify Remote)
git branch  (To check Branch)
git branch - m main (To rename branch)
git push origin main

Git Branch:

git branch (To check Branch)
git branch - m  main  (To rename branch)
git checkout <-branch name->  (To navigate)
git checkout - b <-new branch name->  (To create new branch)
git branch - d <-branch name->  (To delete Branch)

Merging Code :

Way 1 :-
git diff <-branch name->  (To compare commits, branches, files & more) 
git merge <-branch name->  (To merge two branches)

Way 2 :-
By creating a Pull Request

Pull Request:

It tells other about the changes that you want to push in Git hub Repository.

Pull Command:
git pull origin main    (Used to fetch and download content from a remote repository and immediately update the local repository to match the content)

Resolving Merge Conflicts :-
An event that takes place when Git is unable to resolve automatically the difference in the commits that are made.

Undoing Changes:

CASE 1 :- Staged Changes
git reset  <-file name->
git reset

CASE 2 :- Committed Changes (For one Commit)
git reset HEAD~1

CASE 3 :- Committed Changes (For Many Commits)
git reset  <-commit hash->
git reset --hard   <-commit hash->

Fork :-

It is a Rough Copy.





