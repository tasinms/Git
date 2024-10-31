<p align="center">
  <img src="https://i.imgur.com/3V3y5NC.png" height="150">
  <h1 align="center">Git</h1>
  <p align="center">Git Cheatsheet<p>
</p>

<br />

<h1 align="center">Prerequisite</h1>

<br />

Open Terminal inside VS Code to Execute Git Commands 

![How to Open the Terminal in Visual Studio Code](https://i.imgur.com/CzXHxDd.gif)

<br />

<h1 align="center">Index</h1>

<br />

* [Push Code into New GitHub Repository](#push-code-into-new-github-repository)
  
* [Push Code into Existing GitHub Repository](#push-code-into-existing-github-repository)
  
* [Create Branch and Push Code to GitHub Repository](#create-branch-and-push-code-to-github-repository)

* [Fetch Latest Changes from GitHub Repository's Main Branch](#fetch-latest-changes-from-github-repositorys-main-branch)

* [View Commit History](#view-commit-history)

* [Clone GitHub Repository](#clone-github-repository)

* [Rename Repository on GitHub](#rename-repository-on-github)

* [Change Default Branch Name on GitHub](#change-default-branch-name-on-github)

<br />

<h1 align="center">Push Code into New GitHub Repository</h1>

<br />

1. Create **[New Repository](https://github.com/new)** on GitHub

2. Initialize Local Directory as Git Repository
	```bash
	git init
	```

3. Add Files for Commit
	```bash
	git add .
	```

4. Commit
	```bash
	git commit -m "Any Name"
	```

5. Add GitHub Repository Link
	```bash
	git remote add origin https://github.com/account/Repository-Name.git
	```

6. Push Code to GitHub
	```bash
	git push -u origin master/main
	```

<br />

<h1 align="center">Push Code into Existing GitHub Repository</h1>

<br />

1. Add Files for Commit
	```bash
	git add .
	```

2. Commit
	```bash
	git commit -m "Any Name"
	```

3. Push Code to GitHub
	```bash
	git push -u origin master/main
	```

<br />

<h1 align="center">Create Branch and Push Code to GitHub Repository</h1>

<br />

1. Create New Branch Locally
	```bash
	git checkout -b branchName
	```

2. Add Files for Commit
	```bash
	git add .
	```

3. Commit
	```bash
	git commit -m "Any Name"
	```

4. Push Code to GitHub
	```bash
	git push -u origin master/main
	```

<br />

<h1 align="center">Fetch Latest Changes from GitHub Repository's Main Branch</h1>

<br />

```bash
git pull origin master/main
```

<br />

<h1 align="center">View Commit History</h1>

<br />

```bash
git log --oneline --all
```

<br />

# Run Previous Commit

```bash
git checkout commitId
```

<br />

<h1 align="center">Clone GitHub Repository</h1>

<br />

# Clone Inside Sub-Directory

```bash
git clone https://github.com/account/Repository-Name.git
```

<br />

# Clone Inside Current Directory

```bash
git clone https://github.com/account/Repository-Name.git .
```

<br />

<h1 align="center">Rename Repository on GitHub</h1>

<br />

1. Change Repository Name on GitHub

2. Update GitHub Repository Link Locally
	```bash
	git remote set-url origin NEW_URL
	```

<br />

<h1 align="center">Change Default Branch Name on GitHub</h1>

<br />

1. Change Default Branch Name on GitHub

2. Rename Local Branch
	```bash
	git branch -m currentBranchName newBranchName
	```

3. Push Code to GitHub
	```bash
	git push -u origin newBranchName
	```

<br />

<br />

<br />

<!-- Signature -->
<img align="right" src="https://i.imgur.com/38Bcp0K.png" alt="Logo" style="width:200px;">
<!-- Signature -->
