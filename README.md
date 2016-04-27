# Plugins para desenvolvimento

## Sublime Linter Dependencies

### PHPMD
```sh
$ wget -c http://static.phpmd.org/php/latest/phpmd.phar && chmod +x phpmd.phar
$ sudo mv phpmd.phar /usr/local/bin/phpmd
$ phpmd --version
```

### PHPCS
```sh
$ curl -OL https://squizlabs.github.io/PHP_CodeSniffer/phpcs.phar && chmod +x phpcs.phar
$ sudo mv phpcs.phar /usr/local/bin/phpcs
$ phpcs -h
```

### PHPCBF
```sh
$ curl -OL https://squizlabs.github.io/PHP_CodeSniffer/phpcbf.phar && chmod +x phpcbf.phar
$ sudo mv phpcbf.phar /usr/local/bin/phpcbf
$ phpcbf -h
```
