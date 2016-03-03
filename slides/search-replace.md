### Search + Replace

```php
# Update production URLs for staging
$ wp search-replace example.dev example.com

# Replace all instances of "foo" with "bar" *only* in wp_options
$ wp search-replace foo bar wp-options
```

*Intelligently handles PHP serialized data!*