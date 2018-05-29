# CodeSniffer test

This is a short proof-of-concept for a possible bug in CodeSniffer.

Run:

1. `composer install`
2. `composer phpcs`

`test.php` contains the source code that will be modified by CodeSniffer, `test.php.original` is an unmodified copy of
`test.php` and `test.php.output` contains my local output.
