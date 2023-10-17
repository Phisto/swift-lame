[![Swift Package Manager](https://img.shields.io/badge/Swift_Package_Manager-compatible-orange?style=flat-square)](https://img.shields.io/badge/Swift_Package_Manager-compatible-orange?style=flat-square)
[![Platforms](https://img.shields.io/badge/Platforms-macOS_iOS_tvOS-yellowgreen?style=flat-square)](https://img.shields.io/badge/Platforms-macOS_iOS_tvOS-Green?style=flat-square)
[![License](https://img.shields.io/github/license/phisto/swift-lame.svg)](https://github.com/Phisto/swift-lame)
                
#swift-lame
                
## Overview

This is a mirror of the [LAME](https://lame.sourceforge.io) 3.100 source modified to make it available as a library via [Swift Package Manager](https://www.swift.org/package-manager/).

## Requirements
                           
- XCode 15.0+
- swift-tools-version: 5.9+

LAME library     | macOS  |  iOS   |  tvOS
-----------------|--------|--------|--------
3.100.0          | 10.13+ |  12.0+ |  12.0+

## TO-DO
                               
- Implement test target
- Write a short usage guide
                               
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

LAME is released under the [GNU Lesser General Public License (LGPL)](https://www.gnu.org/licenses/).


