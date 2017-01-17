# OpenCV Android Bindings for Gradle [![](https://jitpack.io/v/davidmigloz/opencv-android-gradle-repo.svg)](https://jitpack.io/#davidmigloz/opencv-android-gradle-repo)

OpenCV Android bindings packaged as Gradle dependecy.

> Native libraries are not included. It is intended for use with [OpenCV Manager](https://play.google.com/store/apps/details?id=org.opencv.engine).

## Usage

#### Step 1

Add the JitPack repository to your `build.gradle ` file:

```gradle
allprojects {
	repositories {
		...
		maven { url "https://jitpack.io" }
	}
}
```

#### Step 2

Add the dependency:

```gradle
dependencies {
	compile 'com.github.davidmigloz:opencv-android-gradle-repo:3.2.0'
}
```

## Versions supported

- OpenCV 3.2.0
- OpenCV 3.1.0

## API levels
```gradle
minSdkVersion 9
targetSdkVersion 25
compileSdkVersion 25
buildToolsVersion "25.0.0"
```
