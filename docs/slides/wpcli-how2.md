## WP-CLI - What is it?

Installing WP-CLI
```
curl -O https://raw.githubusercontent.com/wp-cli/builds/gh-pages/phar/wp-cli.phar
chmod +x wp-cli.phar
sudo mv wp-cli.phar /usr/local/bin/wp
```

Using WP-CLI to install plugin and theme
```
wp plugin install buddypress
wp theme install twentysixteen
```

Updating plugins with WP-CLI
```
wp plugin update buddypress
wp plugin update --all
```

Note:
Talk about code