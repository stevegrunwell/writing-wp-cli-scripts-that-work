##  Output: The Simple Stuff

```php
# Simply output text.
WP_CLI::log( 'A normal message' );

# Prepend the text with a colored "Warning:".
WP_CLI::warn( '¯\_(ツ)_/¯' );

# Prepend the message with "Error:" and return.
WP_CLI::error( '(╯°□°）╯︵ ┻━┻' );

# Prepend the text with a colored "Success:"!
WP_CLI::success( 'GREAT SUCCESS!' );
```