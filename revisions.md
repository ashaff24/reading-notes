# Revisions and the Cloud

## Version Control Systems:

Without version control, you would have multiple files with slightly different names and have to save them to keep documentation of any changes you may have made (for example: a college term paper with termpaper.doc, termpaper_2.doc, final_termpaper.doc). Version control allows you to track these changes (taking a snapshot) while keeping just one named file.

### Local Version Control (Local VCS)
Entails one database on your hard disk that stores changes to files

### Centralized Version Control (CVCS)
Entails a single server storing all changes and file versions, which can be accessed by various clients

- Allowed programmers to have more knowledge of team member's activities with certain files
- Gave admin much more control over divvying up responsibilities
- Server can be a single point of failure
- If server goes down, collaborators cannot work with each other or save changes or new versions

### Distributed Version Control (DVCS)
Allows clients to create mirrored repositories

- These data backups can be easily placed on the server to replace any lost data
- Enables the use of various simultaneous workflows

## Git
Used for sharing code and collaboration: DVCS for the masses

- Version control system 
- Lets multiple developers work on the same code
- Has a history of changes to your files
- Gives the ability to view, apply, and remove those changes
- Keeps all of your project files in one depository
- Makes collaboration possible
- Files can reside in 3 main states:
  - Committed - data is securely stored in local database
  - Modified - file has been changed but not committed to databalse
  - Staged - flagged a file's changed version to be committed in next snapshot

#### Snapshots in time

- "Commits" represent each successive version of a file or files
- "Commits" are like a "save as"
- Each version creates a new snapshot on the timeline of a project
- Have one file but remember all of the changes made along the way
- Can easily refer back to an old commit

#### Keeping track

- Working directory - actual files reside here
- Index - the area used for staging
- Tracked - file can be modified, unmodified, or staged; they are part of the most recent commit
- Untracked - file is not in the last snapshot and do not currently reside in the staging area
- Each "commit" has a label that points to it
- HEAD - means "you are here" and refers to the most recent version
- Assign messages to commits so you can remember what changes you made to that version when looking back at it

## GitHub
Your code in the cloud

- A way to share code in the cloud
- Online backup for your code
- Uses Git to help manage team's work
  - version tracking
  - reviewing changes
  - keeps changes seperate until you want to add them in
  
## Git + GitHub
- Have lots of team members work together on some files
- Keep a history of each file over time
- Work on code on your own computer and sync it with what's online

## Repositories ("repos")
A collection of files I have told Git to pay attention to

- Usually one project = one repository
- Really large projects might have different repos for different parts (front end vs back end)
- Can live on GitHub and/or your computer

### Making a new Repo
- On GitHub, click + sign next to name and select "new repository"
- Can be named anything, but should be meaningful 
- Add a description
- Make sure it's public
- Initialize with a README.md file

### Linking Repos
- Need to copy the repo onto our computer and connect them to eachother
- If they are connecting, they can give and receive code from the other repo
- Do this by cloning: from the cloud, to our local computer

#### Cloning
- Click big green "code" button
- Make sure it says HTTPS
- Copy IRL using the little clipboard icon
- Open Terminal
- Navigate into projects directory
- Check where you are
- Put in repository (git clone function)

#### Making changes
- Open up VS Code
- Make changes and hit save
- acp - add, commit, push (see list of functions below)
- do git status between each stage to make sure you are on the right path

##### Important functions
- Create directory - mkdir filename
- Change directory - cd
- List what's in current directory - ls
- Where am I - pwd
- Clone repository - git clone link
- Show hidden files - ls -a
- Show path where it gets and sends information - git remote -v
- Open up VS Code - code .
- Status of repo - git status
- Tell what changes to commit - git add README.md (can also use git add . to add any files with changes)
- Take snapshot - git commit -m "your message goes here"
- Sync code to your GitHub - git push origin main (other computers use master instead of main)
- Go back one directory - cd ..
- Remove folder/file - rm -rf filename THIS IS PERMANENT!
- Get changes from GitHub to computer - git pull origin main

#### Merge conflict
If different changes were made in multiple locations (i.e. GitHub and local computer), tring to "push" at the same time will bring up error

- Can avoid this by making changes only in one place
- Gets difficult when collaborating
- Communication is very important
- Pull changes before pushing updates

#### Verify on GitHub
- In repository in blue box - says when last updated and number of commits
- Can click on commits to see when and messages
- Can click on a commit to see what changes were made

#### Deployment
- Any repo can be published with GitHub Pages
- Each repo can be styled with a theme
- Whenever you push changes, the published site will be updated
- Thats called deployment
- Click Settings--> GitHub Pages-->Source --> Main--> Save
- Then save the link and go back to repository
- Under settings next to "about" enter link to page
- Webpage URL is: username.github.io/REPO-NAME




[<== Back](README.md)
