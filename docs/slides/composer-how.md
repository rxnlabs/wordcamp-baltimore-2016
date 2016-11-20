## Composer - How to use it?

Installing Composer

```
curl -O https://getcomposer.org/composer.phar && mv composer.phar /usr/local/bin/composer
```
Create a composer.json file

```json
{
    "name": "my-awesome-site",
    "description": "Theme and plugin dependencies for the site http://example.com",
    "repositories": [
        {
            "type": "composer",
            "url": "https://wpackagist.org"
        }
    ]
}
```