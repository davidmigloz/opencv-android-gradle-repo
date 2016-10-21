# OpenCV Android Bindings for Gradle

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
	compile 'com.github.davidmigloz:opencv-android-gradle-repo:3.1.0'
}
```

## Versions supported

- OpenCV 3.1.0