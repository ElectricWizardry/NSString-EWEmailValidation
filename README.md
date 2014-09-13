NSString+EWEmailValidation
==========================

This [NSString](https://developer.apple.com/library/Mac/documentation/Cocoa/Reference/Foundation/Classes/NSString_Class/) [category](https://developer.apple.com/library/ios/documentation/general/conceptual/devpedia-cocoacore/Category.html) is nothing more than a convenient wrapper for [Matt Gallagher](http://www.cocoawithlove.com)'s [implementation](http://www.cocoawithlove.com/2009/06/verifying-that-string-is-email-address.html) of [RFC 2822](http://tools.ietf.org/html/rfc2822#section-3.4) verification.


## Usage
```objective-c
NSString *email = @"no@thanks.com";
if ([email isValidEmail]) {
  NSLog(@"%@ looks totally spamable.");
} else {
  NSLog(@"This isn't even an email address.");
}
```

## License
- My "work" &mdash; [MIT](http://ew.mit-license.org)
- Matt's code &mdash; [zlib-style](http://www.cocoawithlove.com/p/about.html)
