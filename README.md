[![CI Status](https://img.shields.io/travis/Andrea%20Mario%20Lufino/Deviice.svg?style=flat)](https://travis-ci.org/Andrea%20Mario%20Lufino/Deviice)
[![Version](https://img.shields.io/cocoapods/v/Deviice.svg?style=flat)](http://cocoapods.org/pods/Deviice)
[![License](https://img.shields.io/cocoapods/l/Deviice.svg?style=flat)](http://cocoapods.org/pods/Deviice)
[![Platform](https://img.shields.io/cocoapods/p/Deviice.svg?style=flat)](http://cocoapods.org/pods/Deviice)

![Logo](./Example/Deviice/Deviice.png)

## Usage

To run the example project, clone the repo, and run `pod install` from the Example directory first.

<pre><code>let device = Deviice.current
</code></pre>
device is a Deviice struct and has some properties:
 
<pre><code>device.identifier
device.type
device.modelName
device.size
device.connectivity
device.year
device.completeDeviceName
</code></pre>

## Requirements
 
This library works on iOS 8 or higher.

## Installation

Deviice is available through [CocoaPods](http://cocoapods.org) and Swift Package Manager.

### CocoaPods

To install
it, simply add the following line to your Podfile:

```ruby
pod "Deviice"
```

### Swift Package Manager

To add Deviice to your Xcode project, select File -> Swift Packages -> Add Package Depedancy. Enter `https://github.com/andrealufino/Deviice` for the URL. Check the use branch option and enter `master`.

## Author

Andrea Mario Lufino, [andrealufino.com](https://andrealufino.com).

## License

Deviice is available under the MIT license. See the LICENSE file for more info.
