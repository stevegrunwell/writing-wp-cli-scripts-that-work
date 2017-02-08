### Input: Accepting Arguments

```php
/**
 * ...
 *
 * --option=<required>
 * : This is a required, associative argument.
 *
 * [--option2=<optional>]
 * : This associative argument is optional.
 *
 * [--flag]
 * : An optional flag.
 */
public function my_command( $args, $assoc_args ) {
	// ...
```
