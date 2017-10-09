# OpenCV Android Bindings for Gradle [![](https://jitpack.io/v/davidmigloz/opencv-android-gradle-repo.svg)](https://jitpack.io/#davidmigloz/opencv-android-gradle-repo)

OpenCV Android bindings packaged as Gradle dependency.

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
	compile 'com.github.davidmigloz:opencv-android-gradle-repo:3.3.0'
}
```

## Versions supported

- OpenCV 3.3.0
- OpenCV 3.2.0
- OpenCV 3.1.0

## API levels
```gradle
minSdkVersion 14
targetSdkVersion 26
compileSdkVersion 26
buildToolsVersion "26.0.1"
```

## License

[3-clause BSD License](https://github.com/opencv/opencv/blob/master/LICENSE)

Copyright (C) 2000-2016, Intel Corporation, all rights reserved.  
Copyright (C) 2009-2011, Willow Garage Inc., all rights reserved.  
Copyright (C) 2009-2016, NVIDIA Corporation, all rights reserved.  
Copyright (C) 2010-2013, Advanced Micro Devices, Inc., all rights reserved.  
Copyright (C) 2015-2016, OpenCV Foundation, all rights reserved.  
Copyright (C) 2015-2016, Itseez Inc., all rights reserved.  
Third party copyrights are property of their respective owners.
