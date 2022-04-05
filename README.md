# Koshin

CLI Tool to sync local repositories to one or multiple remotes

---
## Prerequisites and Initialisation
### Git
Since this application is based on the functionality of git, a basic installation is required.

---
## Commands
Each Command also comes with a help page that can be acquired by appending the `-h/--help` flag.

### Index
#### Description
By default, this command will print the path of the Koshin Index file. If it does not exist, then it will be created in `!!FIXME/PATH`.
With the `-ls/--list` flag, the command will print all the repositories tracked by Koshin.
#### Usage
To print the path
```koshin index```
To print the repositories
```koshin index -ls```
#### Options
`-ls/--list` To list the repositories

---

### Status
#### Description
#### Usage
#### Options
---

### New
#### Description
Creates a new directory in a path, tracked by git and optionally connected to a remote repository.
If not all neccessary flags are supplied, the application will require you to fill out the specific details at runtime.
The Koshin index will be updated with the location of your created folder.

#### Usage
This invocation will require you to fill out the details at runtime
```
koshin new
```
This invocation is complete and will not require additional details
```
koshin new -p YOUR_PATH -n DIR_NAME
```
#### Options
`-p/--path` Path to the host directory
`-n/--name` Name of the created directory
`-r/--remote` Link to remote repository (eg. GitHub/GitLab etc.)

---

### Add
#### Description
#### Usage
#### Options
---

### Remove
#### Description
#### Usage
#### Options
---

### Update
#### Description
#### Usage
#### Options
---