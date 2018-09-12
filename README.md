# iOS-Depth-Sampler

[![Platform](http://img.shields.io/badge/platform-ios-blue.svg?style=flat
)](https://developer.apple.com/iphone/index.action)
[![Language](http://img.shields.io/badge/language-swift-brightgreen.svg?style=flat
)](https://developer.apple.com/swift)
[![License](http://img.shields.io/badge/license-MIT-lightgrey.svg?style=flat
)](http://mit-license.org)
[![Twitter](https://img.shields.io/badge/twitter-@shu223-blue.svg?style=flat)](http://twitter.com/shu223)

Code examples of Depth APIs in iOS

## How to build

Open `ARKit-Sampler.xcworkspace` with Xcode 10 and build it!

It can **NOT** run on **Simulator**. (Because it uses Metal.)


## Contents

### Real-time Depth

Depth visualization in real time using AV Foundation.

![](README_resources/depth_1.gif)

### Real-time Dpeth Mask

Blending a background image with a mask created from depth.

![](README_resources/blend.gif)

### Depth from Camera Roll

Depth visualization from pictures in the camera roll.

![](README_resources/depth_baby_histoeq.png)

Plaease try this after taking **a picture with the Camera app using the PORTRAIT mode**.

### Portrait Matte

Background removal demo using Portrait Effect Matte (or Portrait Effect Matte). 

![](README_resources/portraitmatte.gif)

Plaease try this after taking **a picture of a HUMAN with PORTRAIT mode**.

Available in iOS 12 or later.

### ARKit Depth

![](README_resources/arkit-depth.gif)

Depth visualization on ARKit. The depth on ARKit is available only when using `ARFaceTrackingConfiguration`.


## Author

**Shuichi Tsutsumi**

Freelance iOS programmer from Japan.

- PAST WORKS:  [My Profile Summary](https://medium.com/@shu223/my-profile-summary-f14bfc1e7099#.vdh0i7clr)
- PROFILES: [LinkedIn](https://www.linkedin.com/in/shuichi-tsutsumi-525b755b/)
- BLOGS: [English](https://medium.com/@shu223/) / [Japanese](http://d.hatena.ne.jp/shu223/)
- CONTACTS: [Twitter](https://twitter.com/shu223) / [Facebook](https://www.facebook.com/shuichi.tsutsumi)