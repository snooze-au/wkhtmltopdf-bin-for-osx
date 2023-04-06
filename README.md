# wkhtmltopdf-binaries-osx
This package includes symlinked wkhtmltopdf binaries for MacOS from wkhtmltopdf.org as a composer package

``Current version of binaries: 0.12.6 released on June 11, 2020``

See (http://wkhtmltopdf.org/downloads.html) for more details!

## Binaries Included
- bin/wkhtmltoimage-amd64-osx
- bin/wkhtmltopdf-amd64-osx

### Package Installation

Require this package as a --dev dependency in your composer.json and update composer.

```bash
composer require --dev snooze/wkhtmltopdf-binaries-osx
```

### Symlinked paths:

```
vendor/bin/wkhtmltoimage-amd64-osx

vendor/bin/wkhtmltopdf-amd64-osx
```

### License

This package is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT)
