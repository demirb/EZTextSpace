# EZText.Space

-![demo](11.gif)

-![demo](222.gif)

## Easy to use:
```swift
EZTextSpace.show("Doctor Amy", text: "Hello my name is Doctor Amy, I will show you how to use this library.", image: UIImage(named: "doctor")!, imageLocation: EZTextSpaceImageStartLocation.TopOfBlack, onClick: { () -> () in
   EZTextSpace.hide() 
})
```

## Editing:
```swift
EZTextSpace.Settings.padding = 40
EZTextSpace.Settings.height = 400
EZTextSpace.Settings.textSpeed = 0.5 // Characters per second
```

|Settings Options|
| -------------|
|padding|
|height|
|textSpeed|

## No object tracking:
EZTextSpace is a singleton object so you don't need to keep track of its instance or anything. Just show than hide.  

##Installation (~10 seconds)

1. Download and drop 'EZTextSpace.swift' in your project.  
2. Congratulations!  

## Install via CocoaPods

You can use [Cocoapods](http://cocoapods.org/) to install `EZTextSpace` by adding it to your `Podfile`:

```ruby
platform :ios, '8.0'
use_frameworks!

pod 'EZTextSpace'
```

Then on the top of files where you are going to use this:

```swift
import EZTextSpace
```

##Requirements

- Xcode 6 or later (Tested on 7.2)
- iOS 7 or later (Tested on 9.2)

##Possible features

- More customization
- Pod support 
- More examples
- Horizontal option
- Show the person at the right option
- OSX compatibility

##License
EZTextSpace is available under the MIT license. See the [LICENSE file](https://github.com/goktugyil/EZText.Space/blob/master/LICENSE).

##Keywords
swift, text, message, conversation, speech, dialog, dialogue, rpg, jrpg, game, rick and morty,
