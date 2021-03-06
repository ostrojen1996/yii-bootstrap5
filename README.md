<p align="center">
    <a href="https://github.com/yiisoft" target="_blank">
        <img src="https://avatars0.githubusercontent.com/u/993323" height="80px">
    </a>
    <a href="http://getbootstrap.com/" target="_blank" rel="external">
        <img src="https://v4-alpha.getbootstrap.com/assets/brand/bootstrap-solid.svg" height="80px">
    </a>
    <h1 align="center">Yii Framework Twitter Bootstrap 5 Extension</h1>
    <br>
</p>

This [Yii Framework] extension encapsulates [Twitter Bootstrap 5] components
and plugins in terms of Yii widgets, and thus makes using Bootstrap components/plugins
in Yii applications extremely easy.

[Yii Framework]:        http://www.yiiframework.com/
[Twitter Bootstrap 4]:  https://getbootstrap.com/docs/5.0/getting-started/introduction/

For license information check the [LICENSE](LICENSE.md)-file.

Documentation is at [docs/guide/README.md](docs/guide/README.md).

[![Latest Stable Version](https://poser.pugx.org/yiisoft/yii-bootstrap5/v/stable.png)](https://packagist.org/packages/yiisoft/yii-bootstrap5)
[![Total Downloads](https://poser.pugx.org/yiisoft/yii-bootstrap5/downloads.png)](https://packagist.org/packages/yiisoft/yii-bootstrap5)
[![Build Status](https://travis-ci.com/yiisoft/yii-bootstrap5.svg?branch=master)](https://travis-ci.com/yiisoft/yii-bootstrap5)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/yiisoft/yii-bootstrap5/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/yiisoft/yii-bootstrap5/?branch=master)
[![Code Coverage](https://scrutinizer-ci.com/g/yiisoft/yii-bootstrap5/badges/coverage.png?b=master)](https://scrutinizer-ci.com/g/yiisoft/yii-bootstrap5/?branch=master)

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

```
php composer.phar require --prefer-dist yiisoft/yii-bootstrap5
```

Usage
----

For example, the following
single line of code in a view file would render a Bootstrap Progress plugin:

```php
<?= Yiisoft\Yii\Bootstrap5\Progress::widget(['percent' => 60, 'label' => 'test']) ?>
```
