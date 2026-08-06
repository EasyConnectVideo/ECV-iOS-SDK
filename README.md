# ECV-iOS-SDK
iOS SDK for EasyConnect Video

**Latest version: `1.2.0.208`** (pod `ECV175_iOS_SDK`, distributed via CocoaPods) — see [Releases](https://github.com/EasyConnectVideo/ECV-IOS-SDK/releases) for release notes.

## Installation

0- if cocoapods not installed
```
sudo gem install cocoapods
```

1- Add the Podfile to your project, configure it accordingly (change 'MyApp' to your project's name):
```ruby
platform :ios, '12.0'

target 'MyApp' do
  pod 'ECV175_iOS_WebRTC', '~> 134'
  pod 'ECV175_iOS_SDK', '~> 1.2.0.208'
end
```

2- Make sure Xcode is closed.

3- Then:
```
pod install --repo-update
```

4- Open MyApp.xcworkspace (not MyApp.xcodeproj).

5- In Xcode, select the Project and the Target → Build Settings → search for 'User Script Sandboxing' → set to No.

6- Then you can build the project successfully.

## Upgrading

To upgrade an existing integration to the latest version:
```
pod update ECV175_iOS_SDK --repo-update
```
