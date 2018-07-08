# This is a simple PHP static site generator.

Build the site with php. Mostly to make good use of the:

```php
<?php
	include 'page.php';
?>
```

This will let us build the page out the way we want in PHP.

When done, serve the page in one tab. In a second tab run:

`wget -m localhost:1234` into the `docs` folder.
