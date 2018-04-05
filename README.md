# iid-use-module-bug

## Example

- git clone git@github.com:paulb777/iid-modular-header-bug.git
- cd iid-modular-header-bug/Example/
- pod update --no-repo-update
- open iid-use-module-bug.xcworkspace/
- Build and notice failure
- cp ./Pods/Headers/Public/FirebaseInstanceID/FirebaseInstanceID/*.h ./Pods/Headers/Public/FirebaseInstanceID
- Build and notice success from the workaround

## Requirements

## Installation

iid-use-module-bug is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod 'iid-use-module-bug'
```

## Author

Paul Beusterien, paulbeusterien@google.com

## License

iid-use-module-bug is available under the MIT license. See the LICENSE file for more info.
