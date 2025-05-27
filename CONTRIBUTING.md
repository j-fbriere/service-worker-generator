# Contributing to the Project

## Install specific Dart version

Windows:

```shell
choco install dart-sdk --version=3.8.0 --allow-downgrade --ignore-dependencies --yes --force
```

macOS:

```shell
brew install dart@3.8.0
```

## Install dependencies

```shell
dart pub get
```

## Run tests

```shell
dart test test/unit_test.dart --color --platform=vm
```
