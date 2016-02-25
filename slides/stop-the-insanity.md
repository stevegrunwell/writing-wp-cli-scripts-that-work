### `stop_the_insanity()`

```php
function stop_the_insanity() {
	global $wp_query;

	$wp_query = null;
}
```