# ZF3 API Reference

This is the reference of Zend Framework 3 API. The latest published version can be found here: https://olegkrivtsov.github.io/zf3-api-reference/html/

# How to Generate

To generate this reference you need the [PHP API Doc Maker](https://github.com/olegkrivtsov/php-api-doc-maker) tool.

You need to have PHP 5.6 or later installed.

Install ZF3 components with the following command:

```
php composer.phar update
```

Generate the reference in HTML format with the following command:

```
php php-api-doc-maker.php /path/to/api/reference/dir 
```

If everything is OK, you should file HTML files inside the `/path/to/api/reference/dir/html` subdirectory.

That's all, enjoy!
