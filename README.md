# CoffeeTranslation

A simple PHP localization library. This relies on no extensions and has no additional dependencies.

## Installation

The recommended installation method is via [Composer](//getcomposer.org):

```sh
composer require yukiscoffee/coffeetranslation
```

## Usage

CoffeeTranslation stores translation files in a YAML-like language.

`en-US/hello.i18n`

```yaml
# This is a comment.

hello: "Hello."
```

`ja-JP/hello.i18n`

```yaml
# This is a comment.

hello: "こんにちは。"
```

There is an extensive configuration API which can be accessed by `CoffeeTranslation::getConfigApi()`.

## Acknowledgements

CoffeeTranslation has been supported by the work of the following developers or projects:

- [Rehike](//github.com/Rehike/Rehike) - The primary project for which CoffeeTranslation was made.
- [Isabella (kawapure)](//github.com/kawapure) - A lead developer of Rehike who revised the CoffeeTranslation source code during its use in Rehike.