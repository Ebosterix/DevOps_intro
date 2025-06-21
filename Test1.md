Testing the git repo connection
Features_branch created


# This is a test file for the git repository connection_

This is a rebase exercise STEPS
1. Create a new branch called `Features_branch`.
2. Make some changes to this file.
3. Commit the changes.
4. Switch back to the `main` branch.
5. Make some changes to this file in the `main` branch.
6. Commit the changes in the `main` branch.     

git checkout -b feature/dev1

  203  git add .

  204  git commit -m  "2nd commit in dev1 branch"

  205  git push

  206  git push --set-upstream origin feature/dev1

  207  clear

  208  git checkout main
  209  git add .

  210  git commit -m "2nd commit in main"

  211  git push

  212  git checkout feature/dev1

  213  git rebase main

  214  clear

  215  git checkout main

  216  git merge feature/dev1

  217  git pushp


