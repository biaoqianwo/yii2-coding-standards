Yii 2 Web Framework Coding Standard
===================================

This repository contains settings for [Yii2 coding style](https://github.com/yiisoft/yii2/wiki/Core-framework-code-style)
for various tools.

Getting code
------------

```
$ php composer.phar install biaoqianwo/yii2-coding-standards
```

PHP_Codesniffer
---------------

[PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer) coding standard, rule set
and sniff token parsing classes for the [Yii 2 Web Framework](https://github.com/yiisoft/yii2/). Overally rules
are based on PSR-2 standard with some minor exceptions and changes. Rules derived from PSR-2 standard and excluded
in Yii2 standard were implemented (or planned to be) as sniff classes.

Rules could also be used for checking code style of an existing Yii2 applications.

Everything that is merged into main [Yii2 development repository](https://github.com/yiisoft/yii2) being checked
with these rule set as well.

### Using code style

After CodeSniffer is installed you can launch it with custom code style using the following syntax:

```
$ ./vendor/bin/phpcs --extensions=php --standard=Yii2 /home/resurtm/work/Yii2MegaApp/
```

If you're using PhpStorm you can configure it to use CodeSniffer using Settings → PHP → Code Sniffer.
Yii2 code style can be specified at Inspections → PHP → PHP Code Sniffer validation.


PhpStorm
--------

Yii uses PSR-1 and PSR-2 as code style standards. You can choose these via `Settings` → `Code Style` → `PHP` → `Set from...` → `Predefined Style` → `PSR1/PSR2`.

### More 

[中文Yii规范](http://www.jianshu.com/p/02cc5d507841)