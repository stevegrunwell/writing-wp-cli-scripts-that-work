### Sub-commands

![Yo dawg, I heard you liked CLI commands so I launched some CLI commands from your CLI commands](resources/yo-dawg.png)

```php
# Launch an external process.
WP_CLI::launch( WP_CLI\Utils\esc_cmd( $command ) );

# Call another WP-CLI command.
WP_CLI::launch_self( $command, $args, $assoc_args );
```
