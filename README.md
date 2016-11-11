# Alamofire-iOS8
Add iOS 8 support for Alamofire.
It is NOT Official version!

## Requirements

- iOS 8.0+ / macOS 10.11+ / tvOS 9.0+ / watchOS 2.0+
- Xcode 8.0+
- Swift 3.0+

## Communication

DONOT dicuss this patched version in the official Alamofire repo.

- If you **found a bug**, open an issue.
- If you **have a feature request**, open an issue.
- If you **want to contribute**, submit a pull request.

## Installation

### CocoaPods

[CocoaPods](http://cocoapods.org) is a dependency manager for Cocoa projects. You can install it with the following command:

```bash
$ gem install cocoapods
```

> CocoaPods 1.1.0+ is required to build Alamofire 4.0.0+.

To integrate Alamofire into your Xcode project using CocoaPods, specify it in your `Podfile`:

```ruby
source 'https://github.com/CocoaPods/Specs.git'
platform :ios, '8.0'
use_frameworks!

target '<Your Target Name>' do
pod 'sirius/Alamofire', :git => 'https://github.com/51test2003/Alamofire-iOS8.git', :tag => '~> 4.0.1'
end
```

Then, run the following command:

```bash
$ pod install
```
