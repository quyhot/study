// git init
// git status
// git add
// git commit( -m "File's name" )

// git log
// git show
// git diff

// working directory(is here)
// staging area(when i commit)
// git repository(when commit finishde)

// git checkout -- <file> (staging area --> working directory)
// git reset HEAD <file>
// git restore 

// git checkout -b <branch> (branching) 
// git checkout <branch> (open branch that decleared)
// git merge <branch>
// A <-- B
// git checkout A 
// git merge B

// git reset --soft (git repository --> staging area)
// git reset --mixed (git repository --> working directory)
// git reset --hard (delete)

// git revert (comback previous state)

// .gitignore (remove files that write in .gitignore from git)

// github 
// git push

// enter username, password once
// git config--global credential.helper store
// (~/.git-credentials) (weak security)
// git config --global credential.helper "cache --timeout=18000"
// git ssh

// git clone (dowload code from github)
// git pull (pull code to my computer)

// pull request
// 1. git checkout -b <branch>
// 2. git push origin <branch>
// 3. create a pull request on Github
// 4. review code
	4.1. review code online (github)
	4.2. fetch branch into local to test offline (optional)
	4.3. approve the pull request
//5. merge branch to master

// resolve conflicts
When will conflicts happen?
	1. Changing the same file + same line.
	2. A deleted file X, B modified file X.
Method 1: git base
	1: Using 'git base',
	2: resolve conflict
	3: push agian with -f
Method 2: 
	1: merge updated master to feature branch
	2: resolve conflict
	3: commit and push.










