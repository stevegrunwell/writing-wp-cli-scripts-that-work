####  DocBlock: Tags

* <!-- .element: class="fragment" --> `@synopsis`
	* Used to validate required arguments automatically
* <!-- .element: class="fragment" --> `@subcommand`
	* Set the canonical name for the command (defaults to method name)
* <!-- .element: class="fragment" --> `@alias`
	* Additional name for this command

```php
/**
 * ...
 *
 * @synopsis   <origin> <destination>
 * @subcommand convert-terms
 * @alias      do-conversion
 */
```
<!-- .element: class="fragment" -->
