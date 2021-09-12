# Module Bootstrap

Custom magento 2 module bootstrap.

## Setup module development with composer

- Make custom folder in your root magento for your modules: `mkdir -p sindria`

- Move into folder: `cd sindria`

- Clone this repo: `git clone https://github.com/SindriaInc/module-bootstrap.git`

- Configure custom folder as local composer repository: `composer config repositories.dev-sindria path sindria/\*`

- Require your custom module: `composer require sindria/module-bootstrap:@dev` 

- Run setup upgrade: `php bin/magento setup:upgrade`


### Screenshots

#### composer.json
![composer](https://raw.githubusercontent.com/SindriaInc/module-bootstrap/master/docs/screenshots/composer.png)


#### composer require
![require](https://raw.githubusercontent.com/SindriaInc/module-bootstrap/master/docs/screenshots/require.png)
