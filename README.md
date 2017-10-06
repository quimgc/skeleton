# skeleton

[![Latest Version on Packagist][ico-version]][link-packagist]
[![Software License][ico-license]](LICENSE.md)
[![Build Status][ico-travis]][link-travis]
[![Coverage Status][ico-scrutinizer]][link-scrutinizer]
[![Quality Score][ico-code-quality]][link-code-quality]
[![Total Downloads][ico-downloads]][link-downloads]

**Note:** Replace ```Quim Gonzalez Colat``` ```quimgc``` ```https://github.com/quimgc``` ```quimgonzalez@iesebre.com``` ```quimgc``` ```skeleton``` `````` with their correct values in [README.md](README.md), [CHANGELOG.md](CHANGELOG.md), [CONTRIBUTING.md](CONTRIBUTING.md), [LICENSE.md](LICENSE.md) and [composer.json](composer.json) files, then delete this line. You can run `$ php prefill.php` in the command line to make all replacements at once. Delete the file prefill.php as well.

This is where your description should go. Try and limit it to a paragraph or two, and maybe throw in a mention of what
PSRs you support to avoid any confusion with users and contributors.


## Com funciona?

S'ha creat dos projectes/carpetes:
- **skeleton**: Paquet que volem desenvolupar. Creat a partir d'un git clone de: https://github.com/thephpleague/skeleton

Comandes: 

    $ git clone git@github.com:thephpleague/skeleton.git
    $ adminlte skeleton_test 

1) dins de skeleton/skeleton s'ha executat:

        php prefill.php
    

- **skeleton_test**:  


## Structure

If any of the following are applicable to your project, then the directory structure should follow industry best practises by being named the following.

```
bin/        
config/
src/
tests/
vendor/
```


## Install

Via Composer

``` bash
$ composer require quimgc/skeleton
```

## Usage

``` php
$skeleton = new Quimgc\Skeleton();
echo $skeleton->echoPhrase('Hello, League!');
```

## Change log

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Testing

``` bash
$ composer test
```

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) and [CODE_OF_CONDUCT](CODE_OF_CONDUCT.md) for details.

## Security

If you discover any security related issues, please email quimgonzalez@iesebre.com instead of using the issue tracker.

## Credits

- [Quim Gonzalez Colat][link-author]
- [All Contributors][link-contributors]

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

[ico-version]: https://img.shields.io/packagist/v/quimgc/skeleton.svg?style=flat-square
[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square
[ico-travis]: https://img.shields.io/travis/quimgc/skeleton/master.svg?style=flat-square
[ico-scrutinizer]: https://img.shields.io/scrutinizer/coverage/g/quimgc/skeleton.svg?style=flat-square
[ico-code-quality]: https://img.shields.io/scrutinizer/g/quimgc/skeleton.svg?style=flat-square
[ico-downloads]: https://img.shields.io/packagist/dt/quimgc/skeleton.svg?style=flat-square

[link-packagist]: https://packagist.org/packages/quimgc/skeleton
[link-travis]: https://travis-ci.org/quimgc/skeleton
[link-scrutinizer]: https://scrutinizer-ci.com/g/quimgc/skeleton/code-structure
[link-code-quality]: https://scrutinizer-ci.com/g/quimgc/skeleton
[link-downloads]: https://packagist.org/packages/quimgc/skeleton
[link-author]: https://github.com/quimgc
[link-contributors]: ../../contributors
