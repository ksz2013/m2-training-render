# m2-training-render

### Installation

```sh
$ composer config repositories.koncz-m2-training-render git git@github.com:ksz2013/m2-training-render.git
$ composer require koncz/m2-koncz-hello:dev-master
```

Manually:

Copy the zip into app/code/Training/Render directory


#### After installation by either means, enable the extension by running following commands:

```sh
$ php bin/magento module:enable Training_Render --clear-static-content
$ php bin/magento setup:upgrade
```