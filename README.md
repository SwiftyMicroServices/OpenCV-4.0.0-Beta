# OpenCV Dynamic

This repository contains [podspec](https://guides.cocoapods.org/syntax/podspec.html) of [OpenCV](http://opencv.org) framework built as a dynamic library. It can be used as a dependency in any CocoaPod and will work correctly with Swift and/or Objective-C projects.

To add it to your project:

`pod 'OpenCV-4.0.0-beta', '~> 0.1.1'`

Do add it as a dependency to an existing CocoaPod:

`spec.dependency 'OpenCV-4.0.0-beta'`

# Building

For the pod to build correctly, please make sure **cmake** is available from command line, by running `cmake` command. You can install it with [Homebrew](http://brew.sh):

`brew install cmake`

Same as with [OpenCV](http://opencv.org), Python is required to build the framework (shipped with macOS).

Author
======

Dal Rupnik

- [legoless](https://github.com/legoless) on **GitHub**
- [@thelegoless](https://twitter.com/thelegoless) on **Twitter**
- [dal@unifiedsense.com](mailto:dal@unifiedsense.com)

License
======

**OpenCV-4.0.0-beta** is available under the **3-clause BSD** license. See [LICENSE](https://github.com/SwiftyMicroservices/OpenCV-4.0.0-beta/blob/master/LICENSE) file for more information.

Also respect [OpenCV License](https://github.com/opencv/opencv/blob/master/LICENSE) and conditions.
