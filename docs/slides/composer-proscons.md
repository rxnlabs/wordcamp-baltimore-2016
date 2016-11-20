## Composer - Pro vs Cons

| Pros          | Cons                |
| ---------------- | -------------------------- |
| Reduce the code in your repo | Needs to be installed on your webhost. Requires shell access  |
| Use it to install plugins and themes from the command line | One dependency failure will cause the other dependencies not to install |
| Can be used across other PHP projects  | Not every plugin can be installed with wpackagist |

Note:
Pros:
- Reduces code in your repo
- Use specific versions of files in your repo
- Can be used with other PHP projects

Cons:
- Needs to be installed on your webhost. Requires shell access
- One dependency failure will cause other dependencies to fail
- Not every plugin can be installed with wpackagist