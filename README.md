# PostgresKit
An experiment in connecting to Postgres with Swift

https://colindrake.me/post/wrapping-a-c-library-in-a-swift-framework/

[![Carthage](https://img.shields.io/badge/Carthage-compatible-brightgreen.svg?style=flat)](https://github.com/Carthage/Carthage)

## Installation with Carthage

[Carthage](https://github.com/Carthage/Carthage) is a decentralized dependency manager that builds your dependencies and provides you with binary frameworks.

You can install Carthage with [Homebrew](http://brew.sh/) using the following command:

```bash
$ brew update
$ brew install carthage
```

To integrate PostgresKit into your Xcode project using Carthage, specify it in your `Cartfile`:

```ogdl
github "infinitetoken/PostgresKit" ~> 1.0
```

Run `carthage update` to build the framework and drag the built `PostgresKit.framework` into your Xcode project.
