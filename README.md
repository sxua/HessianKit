# HessianKit v.2.0.0

HessianKit is a Framework for Objective-C 2.0 to allow OS X 10.5+, and
iOS 4.0+ applications to seamlessly communicate with hessian web services.
Hessian web services can be implemented using Java, .NET and [more](http://hessian.caucho.com/).

HessianKit provided typed proxy objects to formward calls to, and handle 
responses from any hessian web service, seamlessly just as if they where local
objects. HessianKit also provide functionality to automatically generate classes
for published value objects. Both web service proxies and value objects are 
defined as basic Objective-C Protocols.

### Installation

The easiest way to get HessianKit installed is to use [CocoaPods](http://cocoapods.org/).
Just add this line to your `Podfile`:

```ruby
pod "HessianKit", "~> 2.0.0"
```

### Documentation

Documentation can be found at [CocoaDocs](http://cocoadocs.org/docsets/HessianKit/2.0.0).
Also it can be generated using an [appledoc](http://gentlebytes.com/appledoc/) or a native utility [headerdoc2html](https://developer.apple.com/library/mac/documentation/Darwin/Reference/ManPages/man1/headerdoc2html.1.html).

### Contents

The HessianKit project consist of several targets:

* __Documentation__ generates headerdoc documentation for the OS X and iOS APIs.
* __HessianKit__ generates a framework to be bundled with applications for Mac OS X 10.5 and later, includes documentation.
* __StaticHessianKit__ generates a static library to be linked with applications for iOS 4.0 and later.
* __MacTests__ executes unit tests for HessianKit target against Mac OS X 10.5 and later.
* __iPhoneTests__ executes unit tests for StaticHessianKit against iOS 4.0 and later.

### License
Copyright 2008-2009 Fredrik Olsson, Cocoway. All rights reserved.
Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License. 
You may obtain a copy of the License at [http://www.apache.org/licenses/LICENSE-2.0 ](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, 
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
