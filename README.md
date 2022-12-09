# Template_Full_Symfony

## Authors

- [@romzre](https://www.github.com/octokatherine) (Romain Tirepied)


Version: Symfony 5.4

## Features

- Doctrine
- WebPack Encore
- Phpunit
- Panther

## Installation

### composer.json

```json
 "installAllPackages": [
            "composer require symfony/orm-pack",
            "composer require --dev symfony/maker-bundle",
            "composer require symfony/webpack-encore-bundle",
            "composer require --dev symfony/test-pack",
            "composer req --dev symfony/panther",
            "composer require --dev dbrekelmans/bdi",
            "vendor/bin/bdi detect drivers"
        ],
```

To install packages, you have to run : 

```bash
$ composer installAllPackages
```

