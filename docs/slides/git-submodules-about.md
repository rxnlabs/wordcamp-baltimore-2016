## Git Submodules: What are they?

Git Submodules are a way of including reusable code with your project. If you have multiple sites that use the same plugin and you want to maintain the code of that plugin in one place, submodules are great for that.

.gitmodules
```
[submodule "wp-content/plugins/gravityforms-gaparse-add-on"]
	path = wp-content/plugins/gravityforms-gaparse-add-on
	url = git@github.com:rxnlabs/gravityforms-gaparse.git
	branch = master
[submodule "wp-content/plugins/wp-enqueuer"]
	path = cms/assets/plugins/wp-enqueuer
	url = git@github.com:rxnlabs/wp-enqueuer.git
[submodule "wp-content/themes/avada-jupiter-divi"]
	path = wp-content/themes/avada-jupiter-divi
	url = git@github.com:rxnlabs/avada-jupiter-divi.git
```

Note:
- Git Submodules are a way of including reusable code with your project. 
- If you have multiple sites that use the same plugin and you want to maintain the code of that plugin in one place, submodules are great for that
- Here is code for a Git submodule