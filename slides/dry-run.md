### Dry run

When performing destructive options, consider a `--dry-run` flag

```php
$dry_run = isset( $assoc_args['dry-run'] );

if ( ! $dry_run ) {
	do_something_destructive();
}
WP_CLI::log( 'Something destructive happened' );
```
