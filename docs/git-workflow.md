# Git Workflow Documentation

## Basic Commands

- git init: Initialize a repository.
- git status: Check working tree status.
- git add: Stage changes.
- git commit: Save a snapshot.
- git push: Upload commits.
- git pull: Fetch and integrate changes.
- git fetch: Download remote updates without integrating them.
- git log: View commit history.

## Branching

- main: Stable project branch.
- dev: Integration and testing branch.
- feature: Branch for individual changes.

## Merge and Rebase

Merge combines histories and can preserve a merge commit.
Rebase replays commits on top of another base and rewrites commit history.

## Pull Request

A pull request proposes changes for review before merging them into another branch.

## Merge Conflicts

Inspect conflicting files, edit the conflict markers, test the changes,
stage the resolved files, and complete the merge.

## Tags

Tags identify specific commits, commonly used for releases.
Example: git tag -a v1.0.0 -m "First release"

## Git Stash

Git stash temporarily saves uncommitted changes so you can work on something else.

## Gitignore

.gitignore specifies intentionally untracked files that Git should ignore.
It does not automatically untrack files already committed.
