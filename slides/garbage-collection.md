##  Garbage Collection

When a variable, instance, etc. is no longer being used, PHP will try to clean up the memory in a process known as **garbage collection**

```php
unset( $instance_var );
$my_global_var = null;
```
<!-- .element: class="fragment" -->

Normally handled at end of request, but CLI commands can run far longer! <!-- .element: class="fragment" -->
