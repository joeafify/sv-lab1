# SV Lab 1

_This is a demo web page for using git._

## 1. How to remove branch locally and remotely

- locally if fully merged
  <br>
  `git branch -d <branch-name>`
- locally if not fully merged
  <br>
  `git branch -D <branch-name>`
- remotely
  <br>
  `git push <remote-name> -d <branch-name>`

## 2. How to checkout another branch without commit changes

1. `git stash <stash-name>` 
2. `git checkout <new-branch-name>`

## 3. How to list tags

- `git tag`

## 4. How to delete tag  locally and remotely

- locally 
  <br>
  `git tag -d <tag-name>`
- remotely
  <br>
  `git push origin -d <tag-name>`