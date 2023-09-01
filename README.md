Yii2-wechat
============
Fastwhale SCRM System Yii2 wechat SDK
This sdk must used in fastwhale scrm system.

[![Latest Stable Version](https://poser.pugx.org/fastwhale/yii2-wechat/v/stable.png)](https://packagist.org/packages/fastwhale/yii2-wechat)
[![Total Downloads](https://poser.pugx.org/fastwhale/yii2-wechat/downloads.png)](https://packagist.org/packages/fastwhale/yii2-wechat)
[![License](http://poser.pugx.org/fastwhale/yii2-wechat/license)](https://packagist.org/packages/fastwhale/yii2-wechat)
[![PHP Version Require](http://poser.pugx.org/fastwhale/yii2-wechat/require/php)](https://packagist.org/packages/fastwhale/yii2-wechat)

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist fastwhale/yii2-wechat "*"
```

or add

```
"fastwhale/yii2-wechat": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
/** @var Wechat $wechat */
$wechat = \Yii::createObject([
    'class'     => Wechat::className(),
    'appId'     => $appid,
    'appSecret' => $appSecret,
    'token'     => $token,
]);

/** @var Wechat $wechat */
$wechat = \Yii::createObject([
    'class'          => Wechat::className(),
    'appId'          => $appid,
    'appSecret'      => $appSecret,
    'token'          => $token,
    'componentAppId' => $componentAppId,
]);

/** @var Wechat $wechat */
$wechat = \Yii::createObject([
    'class'                 => Wechat::className(),
    'appId'                 => $appid,
    'appSecret'             => $appSecret,
    'token'                 => $token,
    'componentAppId'        => $componentAppId,
    '_componentAccessToken' => $componentAccessToken,
]);
```
