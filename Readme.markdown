CommonCrypto
============

[![Carthage compatible](https://img.shields.io/badge/Carthage-compatible-4BC51D.svg?style=flat)](https://github.com/Carthage/Carthage)

This is a raw CommonCrypto module for Swift. This means there is no swift wrapper for the framework, just make it available for Swift. You should interface CommonCrypto's C interface in Swift all by yourself.

This project is Carthage and Swift Package Manager compatiable.

Usage
-----

For Carthage (supports OS X, iOS, watchOS and tvOS):

```
github "venj/CommonCrypto" ~> 0.3.0
```

For Swift Package Manager (supports OS X), add following dependency in your `Package.swift`:

```swift
#if os(OSX)
package.dependencies.append(.Package(url: "https://github.com/venj/CommonCrypto.git", versions: Version(0,3,0) ..< Version(1,0,0)))
#endif
```
