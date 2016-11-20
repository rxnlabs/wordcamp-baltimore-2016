#### WP-CLI + Composer - Pros vs Cons

| Pros          | Cons                |
| ---------------- | -------------------------- |
| If WP-CLI isn't installed, use Composer and vice-versa | Installing another thing to use your plugins
| Works with WordPress.org hosted plugins and themes | No support for non-wordpress.org hosted plugins. Can still use composer for that |
| Manage the plugins across your multisite | N/A |
| Automatically add the plugins you install with wp-cli to the composer.json file | N/A |

Note:
Pros:
- If WP-CLI isn't installed on a server, use Composer and vice-versa
- Works with WordPress.org hosted plugins
- Have dev plugins and required plugins
- Automatically add the plugins you install with wp-cli to the composer.json file 

Cons:
- Install another thing for your plugins
- No support for non-wordpress hosted plugins at the moment
- I cannot think of another thing