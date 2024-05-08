# git commit automation

A Python script that creates 1-3 commits daily, at random times of the day, from a specified start date to today. This is perfect for generating a realistic Git history or simulating daily contributions for a GitHub streak.


## Features

- Automatically generates backdated commits from a specified start date to today
- Ensures 1-3 commits per day with sequential timestamps to maintain a clean Git history.
- Modifies a file (`changes.txt`) to include unique changes for each commit.
- Commits include timestamps set using `GIT_AUTHOR_DATE` and `GIT_COMMITTER_DATE`.

## Setup

1. Clone this repository:

```bash
git clone https://github.com/Caparino/git_committed
cd git_committed
```

2. Run the script to generate commits:

```bash
python git_committed.py
```
