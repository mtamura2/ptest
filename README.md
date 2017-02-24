# ptest

## requiments

- php

```
$ sudo yum install php
```

- composer 

```
$ wget https://getcomposer.org/composer.phar
$ chmod +x composer.phar
$ sudo mv composer.phar /usr/local/bin/.
```

## test sample

composer install, run generate skelton, and run test!

```
$ git clone https://github.com/mtamura2/ptest.git
$ composer install
$ vendor/bin/phpunit-skelgen generate-test Sample
phpunit-skelgen 2.0.1-4-g2f2a501 by Sebastian Bergmann.

Wrote skeleton for "SampleTest" to "/path/to/ptest/SampleTest.php".

$ vendor/bin/phpunit SampleTest.php
PHPUnit 5.5.4 by Sebastian Bergmann and contributors.

...                                                                 3 / 3 (100%)

Time: 33 ms, Memory: 4.00MB

OK (3 tests, 3 assertions)
```

## show test and modiry

```
$ vim SampleTest.php
...
```
