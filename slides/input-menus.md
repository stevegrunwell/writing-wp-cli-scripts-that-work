### Input: Menus

Present the user with a list of options.

```php
$options = array(
	'foo' => 'Foo',
	'bar' => 'Bar',
	'baz' => 'Baz',
);

$selected = cli\menu( $options, 'foo', 'What to do?' );
```

```markdown
  1. Foo
  2. Bar
  3. Baz

What to do? [Foo]:
```
<!-- .element: class="fragment" -->