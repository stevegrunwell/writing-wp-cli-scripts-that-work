### `WP_IMPORTING`

* Little-known constant that tells WordPress we're moving a lot of data around.
* Prevent some post-import pings and extraneous checks

```php
if ( ! defined( 'WP_IMPORTING' ) ) {
	define( 'WP_IMPORTING', true );
}
```
