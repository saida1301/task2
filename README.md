When we make commits in a git repository, you choose which files to stage and commit by using git add FILENAME and then git commit. But what if there are some files that you never want to commit? It's too easy to accidentally commit them (especially if you use git add . to stage all files in the current directory). That's where a .gitignore file comes in handy. It lets Git know that it should ignore certain files and not track them.A .gitignore file is a plain text file where each line contains a pattern for files/directories to ignore. Generally, this is placed in the root folder of the repository, and that's what I recommend. However, you can put it in any folder in the repository and you can also have multiple .gitignore files. The patterns in the files are relative to the location of that .gitignore file.
