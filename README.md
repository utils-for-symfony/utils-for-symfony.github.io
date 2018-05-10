# symfony-util.github.io
Documentation for symfony-util

## Travis configuration (outdated)
```yaml
  - php: 7.1
    env:
    - SYMFONY_VERSION="2.3.*"
    - PHPUNIT=phpunit-5.7
    - TEST_LINT=`true`
    - PHP_CS_FIXER=`true`
    - SENSIO_SECURITY=`true`
  - php: 7.1
    env:
    - SYMFONY_VERSION="2.7.*"
    - PHPUNIT=phpunit-5.7
    - TEST_LINT=`true`
    - PHP_CS_FIXER=`true`
    - SENSIO_SECURITY=`true`
  - php: 7.1
    env:
    - SYMFONY_LTS="2"
    - PHPUNIT=phpunit-5.7
    - TEST_LINT=`true`
    - PHP_CS_FIXER=`true`
    - SENSIO_SECURITY=`true`
  - php: 7.1
    env:
    - SYMFONY_LTS="3"
    - PHPUNIT=phpunit-5.7
    - TEST_LINT=`true`
    - PHP_CS_FIXER=`true`
    - SENSIO_SECURITY=`true`
  - php: 7.1
    env:
    - SYMFONY_LTS="4.x-dev@dev"
    - PHPUNIT=phpunit-5.7
    - TEST_LINT=`true`
    - PHP_CS_FIXER=`true`
    - SENSIO_SECURITY=`true`
  - php: 7.2
    env:
    - SYMFONY_VERSION="2.3.*"
    - PHPUNIT=phpunit-5.7
    - TEST_LINT=`true`
    - PHP_CS_FIXER=`true`
    - SENSIO_SECURITY=`true`
  - php: 7.2
    env:
    - SYMFONY_VERSION="2.7.*"
    - PHPUNIT=phpunit-5.7
    - TEST_LINT=`true`
    - PHP_CS_FIXER=`true`
    - SENSIO_SECURITY=`true`
  - php: 7.2
    env:
    - SYMFONY_LTS="2"
    - PHPUNIT=phpunit-5.7
    - TEST_LINT=`true`
    - PHP_CS_FIXER=`true`
    - SENSIO_SECURITY=`true`
  - php: 7.2
    env:
    - SYMFONY_LTS="3"
    - PHPUNIT=phpunit-5.7
    - TEST_LINT=`true`
    - PHP_CS_FIXER=`true`
    - SENSIO_SECURITY=`true`
  - php: 7.2
    env:
    - SYMFONY_LTS="4.x-dev@dev"
    - PHPUNIT=phpunit-5.7
    - TEST_LINT=`true`
    - PHP_CS_FIXER=`true`
    - SENSIO_SECURITY=`true`
  - php: nightly
    env:
    - SYMFONY_VERSION="2.3.*"
    - PHPUNIT=phpunit-5.7
    - TEST_LINT=`true`
    - SENSIO_SECURITY=`true`
  - php: nightly
    env:
    - SYMFONY_VERSION="2.7.*"
    - PHPUNIT=phpunit-5.7
    - TEST_LINT=`true`
    - SENSIO_SECURITY=`true`
  - php: nightly
    env:
    - SYMFONY_LTS="2"
    - PHPUNIT=phpunit-5.7
    - TEST_LINT=`true`
    - SENSIO_SECURITY=`true`
  - php: nightly
    env:
    - SYMFONY_LTS="3"
    - PHPUNIT=phpunit-5.7
    - TEST_LINT=`true`
    - SENSIO_SECURITY=`true`
  - php: nightly
    env:
    - SYMFONY_LTS="4.x-dev@dev"
    - PHPUNIT=phpunit-5.7
    - TEST_LINT=`true`
    - SENSIO_SECURITY=`true`
```

# See also
* [symfony-flex-demo](https://symfony-flex-demo.github.io)
* [travis-util](https://travis-util.github.io/)
* [github-wiki](https://github-wiki.github.io/)
