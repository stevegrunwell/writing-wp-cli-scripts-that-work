### Hear me roar (or not)!

Great scripts will include options for `--verbose`, `--quiet`, or both.

```php
// Define the value once.
$verbose = isset( $assoc_args['verbose'] );

// Simple conditional around output.
if ( $verbose ) {
	WP_CLI::log( 'Thank you for reading me!' );
}
```

<!-- .element: class="fragment" --> Always **remember your audience** and build your command around their needs.