# OpenCV 4.10.0 With Contrib SDK for Android

```
# cmake
#export PATH=/home/zj/software/cmake/cmake-3.14.0-rc3-Linux-x86_64/bin:$PATH

# ant
export ANT_HOME=/usr/share/ant
export PATH=$PATH:$ANT_HOME/bin

## android
export ANDROID_NDK=/home/i/android-ndk-r18b
export ANDROID_SDK=/home/i/Android/Sdk
export ANDROID_HOME=/home/i/Android/Sdk
export ANDROID_NDK_HOME=/home/i/android-ndk-r18b

#export http_proxy=http://192.168.60.1:7897
#export https_proxy=http://192.168.60.1:7897

# JAVA
export JAVA_HOME=/home/i/jdk-11.0.25
export CLASSPATH=.:$JAVA_HOME/lib:$JRE_HOME/lib:$CLASSPATH
export PATH=$JAVA_HOME/bin:$JRE_HOME/bin:$PATH
export JRE_HOME=$JAVA_HOME/jre
```

```
python /home/i/opencv-4.10.0/platforms/android/build_sdk.py --config=/home/i/opencv-4.10.0/platforms/android/ndk-18.config.py --extra_modules_path=/home/i/opencv_contrib-4.10.0/modules --no_ccache /home/i/opencv-4.10.0/build /home/i/opencv-4.10.0
```
