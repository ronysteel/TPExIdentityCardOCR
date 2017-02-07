# TPExIdentityCardOCR

[![CI Status](http://img.shields.io/travis/kingdomrain/TPExIdentityCardOCR.svg?style=flat)](https://travis-ci.org/kingdomrain/TPExIdentityCardOCR)
[![Version](https://img.shields.io/cocoapods/v/TPExIdentityCardOCR.svg?style=flat)](http://cocoapods.org/pods/TPExIdentityCardOCR)
[![License](https://img.shields.io/cocoapods/l/TPExIdentityCardOCR.svg?style=flat)](http://cocoapods.org/pods/TPExIdentityCardOCR)
[![Platform](https://img.shields.io/cocoapods/p/TPExIdentityCardOCR.svg?style=flat)](http://cocoapods.org/pods/TPExIdentityCardOCR)

## Example

To run the example project, clone the repo, and run `pod install` from the Example directory first.

usage:

var iDentifyOCR =new TPExIdentityCardOCR();

iDentifyOCR.bFront = 'YES';    //识别正面还是背面，YES为正面，NO为背面
iDentifyOCR.success = function(date){
console.print(date);
}
iDentifyOCR.error = function(data){
console.print(date);
}
iDentifyOCR.start();


## Requirements

## Installation

TPExIdentityCardOCR is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod "TPExIdentityCardOCR"
```

## Author

kingdomrain, bygd2014@sina.com

## License

TPExIdentityCardOCR is available under the MIT license. See the LICENSE file for more info.
