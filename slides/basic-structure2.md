### Basic Structure

```php
class My_Awesome_Command extends WP_CLI_Command {

	/**
	 * Convert terms from taxonomy A to taxonomy B.
	 *
	 * ...
	 */
	public function convert_terms( $args, $assoc_args ) {
		// All sorts of fancy logic.
	}

}
```

```php
$ wp awesome convert_terms
```
<!-- .element: class="fragment" -->
