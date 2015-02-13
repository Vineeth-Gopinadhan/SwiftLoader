# SwiftLoader
SwiftLoader is a simple and beautiful activity indicator written in Swift.

###Example
<img src="https://raw.githubusercontent.com/leoru/SwiftLoader/master/images/loader.gif">


## Usage

In case you installed SwiftLoader via CocoaPods you need to import it (add this somewhere at the top of your source code file):
```swift
import SwiftLoader
```

Show SwiftLoader without text:
```swift
  SwiftLoader.show(animated: true)
```

Show SwiftLoader with text: 
```swift
  SwiftLoader.show(title: "Loading...", animated: true)
```

Hide SwiftLoader:
```swift
  SwiftLoader.hide()
```

## Configuration
SwiftLoader has simple configuration system.

You need to create SwiftLoader.Config object, set params:
```swift
  var config : SwiftLoader.Config = SwiftLoader.Config()
  config.size = 150
  config.spinnerColor = UIColor.redColor()
```
and set new config for SwiftLoader:
```swift
  SwiftLoader.setConfig(config)
```


## Install
SwiftSpinner is available through CocoaPods. To install it, simply add the following line to your Podfile:

```swift
pod install 'SwiftLoader'
```
NB: Currently Swift Cocoapods work only with 0.36 pre-release version. If you want to learn how to install a Swift cocoapod read more here: http://blog.cocoapods.org/Pod-Authors-Guide-to-CocoaPods-Frameworks/

In case you don’t want to use CocoaPods - just copy the file SwiftLoader/SwiftLoader.swift to your Xcode project.

### Maintainers
- [Kirill Kunst](https://github.com/leoru) ([@kirill_kunst](https://twitter.com/kirill_kunst))

## License

SwiftLoader is available under the MIT license. See the LICENSE file for more info.
