##  Output: Tables

```php
$table = new cli\Table;
$table->setHeaders( array(
	'id'    => 'ID',
	'title' => 'Title'
) );

foreach ( $posts as $post ) {
	$table->addRow( array(
		'id'    => $post->ID,
		'title' => $post->post_title,
	) );
}

$table->display();
```
