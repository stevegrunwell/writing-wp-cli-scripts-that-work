###  Output: Progress Indicators

Show the user that progress is being made.

```php
$progress = WP_CLI\Utils\make_progress_bar( 'Making progress', 10 );

for ( $i = 0; $i < 10; $i++ ) {
	sleep( 1 ); // Do something real here, please.
	$progress->tick();
}
```

```markdown
Making progress  100%[=================================] 0:10 / 0:10
```
<!-- .element: class="fragment" -->