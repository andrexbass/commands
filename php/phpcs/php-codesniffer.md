#### PHP Code Sniffer:

Varre o fonte validando com o padrão PSR2
path = pasta do projeto que deseja fazer o scan

```

$ phpcs path --standard=PSR2

```

ou .phar

curl -OL https://squizlabs.github.io/PHP_CodeSniffer/phpcs.phar
php phpcs.phar -h

```

$ php phpcs.phar path --standard=PSR2

```
