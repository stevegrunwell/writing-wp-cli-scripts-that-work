### WordPress Plugin API

The actions and filters you use on your site are still active, so use them!

```php
// Trigger some action in my theme
do_action( 'my_theme_some_action' );

// Remove filters you won't be needing.
remove_filter( 'the_content', 'wpautop' );
```
