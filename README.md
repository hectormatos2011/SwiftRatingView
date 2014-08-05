SwiftRatingView
===============

A five star rating view made in Swift. It's also an IBDesignable as well!

The SwiftRatingView class is fully compatible with storyboards and up to date with the latest version of Xcode 6 Beta.

To use, just drop it in to your Swift project by either using a UIView in your storyboard and changing the Class to SwiftRatingView, or by usingcopying and pasting this code wherever you need it:

```swift
let ratingView = SwiftRatingView()
ratingView.emptyStarImage = UIImage(named: "emptyImage")
ratingView.starImage = UIImage(named: "fullImage")
```

After you're done creating it, you can update the rating of the SwiftRatingView by setting it's ```rating``` property. It accepts a CGFloat so feel free to throw what you want at it. 

```swift
ratingView.rating = 4.3
```

[![CI Status](http://img.shields.io/travis/Hector Matos/SwiftRatingView.svg?style=flat)](https://travis-ci.org/Hector Matos/SwiftRatingView)
[![Version](https://img.shields.io/cocoapods/v/SwiftRatingView.svg?style=flat)](http://cocoadocs.org/docsets/SwiftRatingView)
[![License](https://img.shields.io/cocoapods/l/SwiftRatingView.svg?style=flat)](http://cocoadocs.org/docsets/SwiftRatingView)
[![Platform](https://img.shields.io/cocoapods/p/SwiftRatingView.svg?style=flat)](http://cocoadocs.org/docsets/SwiftRatingView)

## Usage

To run the example project, clone the repo, and run `pod install` from the Example directory first.

## Requirements

## Installation

SwiftRatingView is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

    pod "SwiftRatingView"

## Author

Hector Matos, hectormatos2011@gmail.com

## License

SwiftRatingView is available under the MIT license. See the LICENSE file for more info.

