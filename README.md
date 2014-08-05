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
