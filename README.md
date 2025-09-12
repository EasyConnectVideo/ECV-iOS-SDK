# ECV-iOS-SDK
iOS SDK for EasyConnect Video

Add the Podfile to your project, configure it accordingly.

Close Xcode.

Then:
```
pod install
```

Open MyApp.xcworkspace (not MyApp.xcodeproj).

In Xcode, select the Project and the Target → Build Settings → search for ENABLE_USER_SCRIPT_SANDBOXING → set to No.

Then you can build the project successfully.
