>> MiniGit

A lightweight Git-like version control system implemented in C++.

>> Features

- init — Initialize a new MiniGit repository
- add — Stage files for commit
- commit — Save a snapshot of the staged files
- log — Show commit history (with hash, time, and message)
- branch — Create a new branch
- checkout — Switch between branches
- merge — Merge another branch into current one (basic conflict marking)
- diff — Show line-by-line file changes between two commits


.minigit/ ├── blobs/         # Stores file contents (blobs) by hash └── (in memory)    # Commit and branch data stored during runtime

>> How to Compile & Run

1.Compile
g++ -std=c++11 -o minigit minigit.cpp

2.Run
.\minigit

>> Author
Feyistu Endale
Aster Regasa
