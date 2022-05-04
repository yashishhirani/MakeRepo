# How to Make a Repository Using VS Code

## Let's make a repository, here are the methods:

1) First make a new (Empty) Repository using your Git Account. 
2) Make a new Folder on VS Code, and go into the directory of that folder using the line "cd ../foldername"
3) Add a File Under the new Folder, let's call it README.md, make changes in the file.
4) In Terminal, type "git init" to initialise the repository
5) In Terminal, type "git add ." to add the files in it to the repository
6) In Terminal, type "git commit -m "Commit Title" -m "Commit Description"
7) Then start connection with GitHub through, in Terminal, "git remote add origin (add the SSH link you see when you made an empty Repo)". To check if connection is live, use line, "git remote -v"
8) Put command "git remote set-url origin https://github.com/<user_name>/<repo_name>.git"
9) Now in Terminal, input, "git push origin master", and the file will be pushed onto the initialised repo onto github.
10) YAY!! 