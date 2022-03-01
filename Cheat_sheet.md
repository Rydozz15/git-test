# Cheatsheet
*This is a reference list of the most commonly used Git commands. (You might consider bookmarking this handy page.) Try to familiarize yourself with the commands so that you can eventually remember them all:*

### 1. Commands related to a remote repository:
- git clone git@github.com:USER-NAME/REPOSITORY-NAME.git
- git push or git push origin main (Both accomplish the same goal in this context)
### 2. Commands related to the workflow:
- git add .
- git commit -m "A message describing what you have done to make this snapshot different"
### 3. Commands related to checking status or log history
- git status
- git log

## The basic Git syntax is program | action | destination.

  For example,

  - git add . is read as git | add | ., where the period represents everything in the current directory;
  - git commit -m "message" is read as git | commit -m | "message"; and
  - git status is read as git | status | (no destination).
### Atomic comits
- A commit that includes changes related to **only one feature or task** of your program.
>Reasons behind it: first, if something you change turns out to cause some problems, it is easy to revert the specific change without losing other changes; and second, it enables you to write better commit messages.
