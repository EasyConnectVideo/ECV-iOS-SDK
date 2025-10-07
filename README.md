# ECV-iOS-SDK
iOS SDK for EasyConnect Video

0- if cocoapods not installed
```
sudo gem install cocoapods
```

1- Add the Podfile to your project, configure it accordingly (change 'MyApp' to your project's name).

2- Make sure Xcode is closed.

3- Then:
```
pod install
```

4- Open MyApp.xcworkspace (not MyApp.xcodeproj).

5- In Xcode, select the Project and the Target → Build Settings → search for 'User Script Sandboxing' → set to No.

6- Then you can build the project successfully.
