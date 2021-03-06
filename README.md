# Swagger Assertions

[![Build Status](https://travis-ci.org/Maks3w/SwaggerAssertions.svg?branch=master)](https://travis-ci.org/Maks3w/SwaggerAssertions)
[![Coverage Status](https://coveralls.io/repos/Maks3w/SwaggerAssertions/badge.svg?branch=master)](https://coveralls.io/r/Maks3w/SwaggerAssertions?branch=master)

Test any API requests and responses match with the models described in the documentation.

This project is compatible with [Swagger 2](http://swagger.io/) spec definitions.

## Installing via Composer

You can use [Composer](https://getcomposer.org) .

```bash
composer require fr3d/swagger-assertions
```

## Usage in PHPUnit

There are two traits for provide predefined helper functions for different assertions.

- [AssertsTrait](src/PhpUnit/AssertsTrait.php) For assert different parts of the response
- [GuzzleAssertsTrait](src/PhpUnit/GuzzleAssertsTrait.php) For assert [Guzzle](https://github.com/guzzle/guzzle) responses.

See examples at [examples/PhpUnit](examples/PhpUnit)

## FAQ

<dl>
  <dt>Q: Can this library validate my Swagger definition?</dt>
  <dd>A: No. This library validate your API responses against your Swagger definition.</dd>
</dl>

## License

  Code licensed under BSD 2 clauses terms & conditions.

  See [LICENSE.txt](LICENSE.txt) for more information.
