# Revert Github Commit
You may use this code to revert your commits in your own repository

### Reverting The Working Copy to an Older Commit


Resets index to former commit; replace '56e05fced' with your commit code
```
git reset 56e05fced 
```

Moves pointer back to previous HEAD
```
git reset --soft HEAD@{1}
```

Commit your changes
```
git commit -m "Revert to 56e05fced"
```

Updates working copy to reflect the new commit
```
git reset --hard
```

Push your changes to respective branch
```
git push -f
```
