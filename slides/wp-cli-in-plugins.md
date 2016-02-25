##  WP-CLI in Plugins

WP-CLI commands make a great addition to most plugins!

```php
// Only load our CLI command when loaded via WP_CLI.
if ( defined( 'WP_CLI' ) && WP_CLI ) {
	require_once dirname( __FILE__ ) . '/my-cli-class.php';
}
```
