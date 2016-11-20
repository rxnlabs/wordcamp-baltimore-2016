WP-CLI + Composer - How to combine them?

Plugin used to combine WP-CLI and Composer

```
wp package install rxnlabs/wp-composer-dependencies
```

Create a composer.json file with the plugins you need for your site
```json
{
	"name": "my-awesome-site",
	"repositories": [
		{
			"type": "composer",
			"url": "https://wpackagist.org"
		}
	],
	"require": {
		"wpackagist-plugin/bbpress": "*",
		"wpackagist-plugin/buddypress": "*",
		"wpackagist-theme/twentysixteen": "*"
	},
	"require-dev": {
		"wpackagist-plugin/debug-bar": "*",
		"wpackagist-plugin/show-current-template": "*"
	}
}
```

Note:
- I developed a plugin for combining the power of Composer and WP-CLI.
- Uses Composer.json
- Bulk install plugins