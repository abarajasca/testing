# testing
Testing repository for Git Commands.

## Squash internal commits.
1. Run command to start the squash task. n represent the last n commits to include in the list to choice.
```
git rebase -i HEAD~n
```
2. Edit the list and change squash for the commits we wanto to squash, it will be squash with before commit and so and save.
3. If all go well, edit commit title will be show, edit title of new commit accordingly.
4. Push the changes to preserve the new commit as is.
```
git push --force-with-lease
```

## Delete the pushed commits.
1. Delete last commit and back changes as unstaged, here you can delete or do changes.
```
git reset HEAD~1
```
2. Push changes to yor repository.
```
git push -f 
```

