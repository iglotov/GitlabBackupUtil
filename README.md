# GitlabBackupUtil

A Small utility to backup all of your gitlab repositories to local filesystem.

Before running the script, make sure you have persisted authentication on local cli with gitlab.

Create a file named `token.json` with the structure
```
{
    "token" : "YOUR_GITLAB_TOKEN"
}

```

place the file in the root directory of the project.

run the following commands
```
npm install
npm start
```

#### Future Scope
1. If the repository already exists, `git pull` instead of cloning
2. Gui for entering token


### Thats It !
