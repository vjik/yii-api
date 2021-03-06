<p align="center">
    <a href="http://www.yiiframework.com/" target="_blank">
        <img src="https://www.yiiframework.com/files/logo/yii.png" width="400" alt="Yii Framework" />
    </a>
    <h1 align="center">Yii Framework REST API Extension</h1>
    <br>
</p>

This extension provides the REST API for the [Yii framework](http://www.yiiframework.com).

For license information check the [LICENSE](LICENSE.md)-file.

Documentation is at [docs/guide/README.md](docs/guide/README.md).

[![Latest Stable Version](https://poser.pugx.org/yiisoft/yii-api/v/stable.png)](https://packagist.org/packages/yiisoft/yii-api)
[![Total Downloads](https://poser.pugx.org/yiisoft/yii-api/downloads.png)](https://packagist.org/packages/yiisoft/yii-api)
[![Build status](https://github.com/yiisoft/yii-api/workflows/build/badge.svg)](https://github.com/yiisoft/yii-api/actions?query=workflow%3Abuild)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/yiisoft/yii-api/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/yiisoft/yii-api/?branch=master)
[![Code Coverage](https://scrutinizer-ci.com/g/yiisoft/yii-api/badges/coverage.png?b=master)](https://scrutinizer-ci.com/g/yiisoft/yii-api/?branch=master)
[![Mutation testing badge](https://img.shields.io/endpoint?style=flat&url=https%3A%2F%2Fbadge-api.stryker-mutator.io%2Fgithub.com%2Fyiisoft%2Fyii-api%2Fmaster)](https://dashboard.stryker-mutator.io/reports/github.com/yiisoft/yii-api/master)
[![static analysis](https://github.com/yiisoft/yii-api/workflows/static%20analysis/badge.svg)](https://github.com/yiisoft/yii-api/actions?query=workflow%3A%22static+analysis%22)


Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

```
php composer.phar require --prefer-dist yiisoft/yii-api
```

## Testing

### Unit testing

The package is tested with [PHPUnit](https://phpunit.de/). To run tests:

```shell
./vendor/bin/phpunit
```

### Mutation testing

The package tests are checked with [Infection](https://infection.github.io/) mutation framework. To run it:

```shell
./vendor/bin/infection
```

### Static analysis

The code is statically analyzed with [Psalm](https://psalm.dev/). To run static analysis:

```shell
./vendor/bin/psalm
```
