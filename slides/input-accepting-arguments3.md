##  Input: Accepting Arguments

```php
public function my_command( $args, $assoc_args ) {
	$assoc_args = wp_parse_args( $assoc_args, array(
		'option2' => false,
	) );

	if ( false !== $assoc_args['option2'] ) {
		// The user passed some value to --option2.
	}
}
```
