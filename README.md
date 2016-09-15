# Yii2 FontAwesome simple asset

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
composer require webvimark/yii2-fontawesome "*"
```

or add

```
"webvimark/yii2-fontawesome": "^1"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
webvimark\fontawesome\FontAwesomeAsset::register($this)
```

OR

```php
class AppAsset extends AssetBundle
{
    public $depends = [
        ...
        'webvimark\fontawesome\FontAwesomeAsset',
    ];
}
```