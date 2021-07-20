# Android WebRTC Library

## Integrate Into Android Project
Add repository in the root gradle file:
```xml
...
allprojects {
    repositories {
        ...
        maven {
            url 'https://raw.github.com/ATOS-VIRTUAL-CARE/webrtc-android/repo/'
        }
    }
}
```

Add dependency to your app module (such as app/build.gradle), latest available stable version in this repo is **M90**:
```xml
dependencies {
    implementation 'atos.virtual.care:libwebrtc:M90'
}
```

## Description

This is precompiled google webrtc library for android, [https://webrtc.org/](https://webrtc.org/).

WebRTC [license](https://webrtc.org/support/license#software_license)
