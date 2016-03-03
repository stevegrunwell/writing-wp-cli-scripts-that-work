### Import/Export

```php
# Export WXR files for all post types in 5MB chunks
$ wp export --max_file_size=5

# Export only posts from 2016
$ wp export --start_date=2016-01-01 --post_type=post

# Import WXR files
$ wp import my-wxr-file.xml
```