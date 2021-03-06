# ActionPicker

[![Version](https://img.shields.io/cocoapods/v/ActionPicker.svg?style=flat)](https://cocoapods.org/pods/ActionPicker)
[![License](https://img.shields.io/cocoapods/l/ActionPicker.svg?style=flat)](https://cocoapods.org/pods/ActionPicker)
[![Platform](https://img.shields.io/cocoapods/p/ActionPicker.svg?style=flat)](https://cocoapods.org/pods/ActionPicker)

![teaser](/Screenshots/header_v2.png)

## Description

`ActionPicker` is an interactive replication of iOS-style action sheets that are widely used across the system to setup AirPods, HomePod, etc. 

## Usage

1. Import `ActionPicker`

```swift
import ActionPicker
```

2. Present your content

```swift
let setupViewController = /* Your awesome view controller */
let actionPickerViewController = ActionPickerViewController(contentViewController: setupViewController)
self.present(actionPickerViewController, animated: false, completion: nil)
```

3. Dismiss
```swift
actionPickerViewController.dismiss(animated: true, completion: nil)
```
*Note*: Since `ActionPickerViewController` is interactive, other dismissal options are available:
* Tap outside the content view
* Pan content view out of the screen

## Screenshots

<p align="center">
<img src="/Screenshots/screenshot_3.png" width="420">
<img src="/Screenshots/screenshot_4.png" width="420">
</p>

## Let's see in action

<p align="center">
    <kbd>
        <img src="/Screenshots/demo.gif" width="420">
    </kbd>
</p>

## Example

To run the example project, clone the repo, and run `pod install` from the Example directory first.

## Requirements

`ActionPicker` requires iOS11+. 

## Installation

ActionPicker is available through [CocoaPods](https://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod 'ActionPicker'
```

## Author

Serg Krivoblotsky, krivoblotsky@me.com

## Roadmap

See [Issues](https://github.com/Krivoblotsky/ActionPicker/issues)

## License

ActionPicker is available under the MIT license. See the LICENSE file for more info.

## Trademarks

Apple, the Apple logo, Finder, Mac and Macintosh, AidPods, HomePod are trademarks of Apple Inc.
