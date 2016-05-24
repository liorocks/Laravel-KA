# Laravel KA

[Laravel (5.x)](http://laravel.com/) Georgian Language Pack.


## Installation

Open terminal and run the following command from the root directory of your Laravel application:

```
$ git clone git@github.com:Landish/Laravel-KA.git resources/lang/ka
```

Open `/config/app.php` file, replace `locale` key from `en` to `ka` and you're ready to go.

```php
'locale' => 'ka',
```
*These translated files also exists in [caouecs/Laravel-lang](https://github.com/caouecs/Laravel-lang) repository, which can be installed with [composer](https://getcomposer.org/).*

Alternatively, you can [download the archive](https://github.com/Landish/laravel-ka/archive/master.zip) and place the translated file into your `/resources/lang/ka` directory.

## Validation Translation

If you want to translate form field names, during [validation](http://laravel.com/docs/validation), open the `/resources/lang/ka/validation.php` and at the end of the file set up the `attributes` array:

```php
'attributes' => [
	'title' => 'სათაური'
],
```

In that case, if you have `required` rule on the `title` field and you'll leave blank during form submit, you'll get the validation error message `სათაური აუცილებელია` instead of `title აუცილებელია`.

## Contribution & Bugs

Feel free to [open an issue](https://github.com/Landish/laravel-ka/issues/new) or pull request, if you find any bugs, have a question or an improved version of translaton. :thumbsup:


## Licence

[The MIT License (MIT)](https://opensource.org/licenses/MIT).
