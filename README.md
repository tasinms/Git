# Git Commands

List Of Important Git Commands.

<br />

## Index

* [Push Code into New GitHub Repository](#push-code-into-new-github-repository)
  
* [Push Code into Existing GitHub Repository](#push-code-into-new-github-repository)
  
* [Create Branch and Push Code to GitHub Repository](#push-code-into-new-github-repository)

<br />

## Push Code into New GitHub Repository

1. Create **[New Repository](https://github.com/new)** on GitHub

2. Open Terminal inside VS Code

3. Initialize Directory as Git Repository
	```bash
	git init
	```

4. Add Files for Commit
	```bash
	git add .
	```

5. Commit
	```bash
	git commit -m "Any Name"
	```

6. Add GitHub Repository Link
	```bash
	git remote add origin https://github.com/account/Repository-Name.git
	```

7. Push Code to GitHub
	```bash
	git push -u origin master/main
	```

<br />

## Push Code into Existing GitHub Repository

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

## Create Branch and Push Code to GitHub Repository

1. Create New Branch
	```bash
	git checkout -b branch_Name
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
