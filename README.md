CocoaPods

Add pod 'YYKit' to your Podfile.
Run pod install or pod update.
Import <YYKit/YYKit.h>.
Carthage

Add github "ibireme/YYKit" to your Cartfile.
Run carthage update --platform ios and add the framework to your project.
Import <YYKit/YYKit.h>.
Notice: carthage framework doesn't include webp component, if you want to support webp, use CocoaPods or install manually.
Manually


kaishiapidiannodolhopdiancyoujieshu

Download all the files in the YYKit subdirectory.
Add the source files to your Xcode project.
Add -fno-objc-arc compiler flag to NSObject+YYAddForARC.m and NSThread+YYAdd.m.
Link with required frameworks:
UIKit
CoreFoundation
CoreText
CoreGraphics
CoreImage
QuartzCore
ImageIO
AssetsLibrary
Accelerate
MobileCoreServices
SystemConfiguration
sqlite3
libz
Add Vendor/WebP.framework(static library) to your Xcode project if you want to support WebP.
Import YYKit.h.
