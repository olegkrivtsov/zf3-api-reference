# ZF3 API Reference

This project's ame is to provide a reference of Zend Framework 3 components and their PHP classes (API). The latest published version of the reference can be found on the [ZF3 API Reference Website](https://olegkrivtsov.github.io/zf3-api-reference/html/). This reference is integrated with my book, [Using Zend Framework 3](https://github.com/olegkrivtsov/using-zend-framework-3-book), so you can take a look at it, too.

# Background

Some time ago I wanted to have a well-structured API reference for Zend Framework 3 in an HTML format to read it online. Unfortunatelly, I couldn't find one, so I decided to generate it myself. To do that, I've created a tool, [php-api-doc-maker](https://github.com/olegkrivtsov/php-api-doc-maker).

# Generating Yourself

If you want to generate this API reference yourself (for example, to contribute), you need the [php-api-doc-maker](https://github.com/olegkrivtsov/php-api-doc-maker) tool.

Before you install the tool, you need to have PHP 5.6 or later installed.

The tool needs the source code of ZF3 components to generate the class reference. Install ZF3 components with the following command:

```
php composer.phar update
```

Generate the reference in HTML format with the following command:

```
php php-api-doc-maker.php /path/to/api/reference/dir 
```

If everything is OK, you should find HTML files inside the `/path/to/api/reference/dir/html` subdirectory.
