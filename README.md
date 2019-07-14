# lumen-middleware-trim-or-convert-strings
 Dealing with Spaces in Form Inputs using Middleware in Lumen.
 
 ## Installation

```sh
composer require phabloraylan/lumen-middleware-trim-or-convert-strings
```

## Configuration

Inside your `bootstrap/app.php` file, add:

```php
 $app->middleware([
    LumenMiddlewareTrimOrConvertString\TrimStrings::class,
    LumenMiddlewareTrimOrConvertString\ConvertEmptyStringsToNull::class,
	//your middleware...
 ]);
```
