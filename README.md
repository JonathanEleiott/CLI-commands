# CLI (Command Line Interface) commands

- Tell your computer what to do
- Commands
  - ls -> lists out the contents of the current directory
  - cd [directory name] -> change directory
    - .. -> goes up one directory
    - / -> separate navigating multiple directories
  - mkdir [directory name] -> makes a new directory
  - touch [file name] -> create a file
  - mv and rm -> noving and removing a file (I recommend doing this in the explorer bar)
  - code [directory name] -> open VS Code
    - . -> refers to the current directory
  - && -> do one command after another finishes
- Flags
  - extensions of the command
  - Example: ls -a (shows all files and directories in the current folder)

# Git vs GitHub

- Git -> version control system using git commands that keeps track of the history of files and folders
- GitHub -> place to store your projects (repository)

- git commands
  - git init -> allows a project to use git commands
  - git status -> shows what has been added/changed/deleted since the last commit
  - git add [file names]-> moves files/folders to the staging area
  - git commit -> takes everything from the staging area and makes it permanent
    - -m "message" -> shortcut for writing a message on your commit
  - git remote -> another location
    - add -> add connection
    - nickname -> name of the connection (most commonly origin)
    - location -> where is the actual connection
  - git push -> send your code somewhere
    - nickname -> nickname of the place you want to send your code to
    - branch name -> which branch do you want to push

- 3 stages
  - working directory (red)
  - staging area (green)
  - project

# File Naming and Structure for HTML and CSS files

- Don't use special character (!, @, #, $, %, ^, &, *, (, ), /, +, =) (except hyphens)
- Don't use spaces (use hyphens)
- Start the file name with a letter
- Use all lowercase letters separated by hyphens
- Keep your file names short and descriptive
- Always put a file extension on files
