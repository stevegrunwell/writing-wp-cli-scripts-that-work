### Output: `format_items()`

Shortcut for table construction, also works for YAML, JSON, and more:

```php
$headers = array(
	'id'    => 'ID',
	'title' => 'Title'
);
$rows    = array();

foreach ( $posts as $post ) {
	$rows[] = array(
		'id'    => $post->ID,
		'title' => $post->post_title,
	);
}

WP_CLI\Utils\format_items( 'table', $rows, $headers );
```
