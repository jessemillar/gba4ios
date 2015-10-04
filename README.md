My own build/fork of GBA4iOS that allows easy sideloading on iOS 9 and Xcode 7.

To install, run `sudo gem install cocoapods; git clone https://github.com/jessemillar/GBA4iOS.git; cd GBA4iOS; pod install`. Once the command completes, open the Xcode project in the directory, connect your phone, select it as the target, and build the project.

If you hit a linker error upon build, quit Xcode, reopen the workspace file, and rebuild.

If you encounter other issues, follow the instructions at the bottom of [this site](http://bouk.co/blog/sideload-iphone/).

As a sidenote, this repository has been set up per these instructions:

![GBA4iOS](https://raw.githubusercontent.com/jessemillar/GBA4iOS/master/screenshot.png)
