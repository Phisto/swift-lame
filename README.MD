[![Swift Package Manager](https://img.shields.io/badge/Swift_Package_Manager-compatible-green?style=flat)](https://img.shields.io/badge/Swift_Package_Manager-compatible-green?style=flat)
[![Platforms](https://img.shields.io/badge/Platforms-macOS_iOS_tvOS-green?style=flat)](https://img.shields.io/badge/Platforms-macOS_iOS_tvOS-Green?style=flat)
[![License](https://img.shields.io/github/license/phisto/swift-lame.svg?style=flat)](https://github.com/Phisto/swift-lame)
                
# swift-lame

This is a mirror of the [LAME](https://lame.sourceforge.io) 3.100.0 source modified to make it available as a library via [Swift Package Manager](https://www.swift.org/package-manager/).

## Requirements
                           
- XCode 16.3+
- swift-tools-version: 6.1+

LAME library     | macOS  |  iOS   |  tvOS
-----------------|--------|--------|--------
3.100.0          | 10.13+ |  12.0+ |  12.0+
                               
## Installation

### Swift Package Manager

The [Swift Package Manager](https://swift.org/package-manager/) is a tool for automating the distribution of Swift code and is integrated into the `swift` compiler.

Once you have your Swift package set up, adding LAME as a dependency is as easy as adding it to the `dependencies` value of your `Package.swift`.

```swift
dependencies: [
.package(url: "https://github.com/Phisto/swift-lame.git", .upToNextMajor(from: "3.100.0"))
]
```

## Usage

I really dont know a source for how to use the LAME framework, but you can check out my [CoreAudioConverter](https://github.com/Phisto/CoreAudioConverter) project to see how i use it.

## License

LAME is released under the [**GNU Lesser General Public License v3.0**](./LICENSE).
