# Git Commands

To push a file from your local system to a specific folder named datasets in a Git repository for the first time, follow these steps:

#### 1. Navigate to Your Project Directory
Open your terminal (Command Prompt, PowerShell, Terminal, etc.) and navigate to your project's directory:
```
cd path/to/your/project
```

#### 2. Initialize the Git Repository (if not already initialized)
If you haven't initialized a Git repository in your project folder yet, run:

```
git init

```

#### 3. Add the Remote Repository
If you haven't added the remote repository yet, you'll need to add it using the following command:

```
git remote add origin https://github.com/your-username/your-repository.git

```

#### 4. Stage the File
Add the file to the staging area:

```
git add datasets/your-file-name

```

#### 5. Commit the Changes
Commit the changes with a descriptive message:

```
git commit -m "Add initial dataset to datasets folder"
```

#### 6.  Push to the Remote Repository
Push the changes to your GitHub repository:

```
git push origin main
```
