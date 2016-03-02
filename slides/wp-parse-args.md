### `wp_parse_args()`

Don't forget useful WordPress functions like `wp_parse_args()` for setting defaults!

```php
$assoc_args = wp_parse_args( $assoc_args, array(
	'foo' => true,
	'bar' => 'baz',
) );
```
