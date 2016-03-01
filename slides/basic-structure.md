### Basic Structure

```php
class My_Awesome_Command extends WP_CLI_Command {

	// Magic will happen in here!

}

// Tell WP-CLI that My_Awesome_Command is 'awesome'.
WP_CLI::add_command( 'awesome', 'My_Awesome_Command' );
```