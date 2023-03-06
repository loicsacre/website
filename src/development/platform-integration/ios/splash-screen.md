---
title: Adding a splash screen to your iOS app
short-title: Splash screen
description: Learn how to add a splash screen to your iOS app.
toc: false
---

<img src='/assets/images/docs/development/ui/splash-screen/android-splash-screen/splash-screens_header.png'
class="mw-100" alt="A graphic outlining the launch flow of an app including a splash screen">

Splash screens (also known as launch screens) provide
a simple initial experience while your iOS app loads.
They set the stage for your application,
while allowing time for the app engine
to load and your app to initialize.

All apps submitted to the Apple App Store
[must provide a launch screen][apple-requirement]
with an Xcode storyboard.

## Customize the launch screen

The default Flutter template includes an Xcode
storyboard named `LaunchScreen.storyboard`
that can be customized your own assets.
By default, the storyboard displays a blank image,
but you can change this. To do so,
open the Flutter app's Xcode project
by typing `open ios/Runner.xcworkspace`
from the root of your app directory.
Then select `Runner/Assets.xcassets`
from the Project Navigator and
drop in the desired images to the `LaunchImage` image set.

Apple provides detailed guidance for launch screens as
part of the [Human Interface Guidelines][].

[apple-requirement]: {{site.apple-dev}}/documentation/xcode/specifying-your-apps-launch-screen
[Human Interface Guidelines]: {{site.apple-dev}}/design/human-interface-guidelines/patterns/launching#launch-screens