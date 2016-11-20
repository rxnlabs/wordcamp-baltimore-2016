## Git Submodules: Pro vs Cons

| Pros          | Cons                |
| ---------------- | -------------------------- |
| Reduce the code in your repo| Pulling down changes can be difficult. Unless you track a branch, Git checkouts out your submodule with a detached HEAD  |
| Use specific versions of plugins across sites | Removing submodules requires lots of code |
| Make changes to a plugin on one site and push those changes to master repo  | You need to add the server's SSH key to your git account or enter in your password to everytime you push or pull changes |

Note:
Pros:
- Reduces code in your repo
- Use specific versions of plugins across site (Git commits as well)
- Make changes to code. Push to repo. Pull down code

Cons:
- Pulling down changes can be difficult
- Removing submodules
- You need to add the server's SSH key to your git account or enter in your password to everytime you push or pull changes
