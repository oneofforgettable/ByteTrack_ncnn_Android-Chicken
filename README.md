# ByteTrack_ncnn_Android


This is an android app about pedestrian identification and tracking, use ByteTrack

# how to build and run
## step1
https://github.com/Tencent/ncnn/releases

1.Download ncnn-YYYYMMDD-android-vulkan.zip or build ncnn for android yourself

2.Extract ncnn-YYYYMMDD-android-vulkan.zip into **app/src/main/jni** and change the **ncnn_DIR** path to yours in **app/src/main/jni/CMakeLists.txt**

## step2
https://github.com/nihui/opencv-mobile

1.Download opencv-mobile-XYZ-android.zip

2.Extract opencv-mobile-XYZ-android.zip into **app/src/main/jni** and change the **OpenCV_DIR** path to yours in **app/src/main/jni/CMakeLists.txt**

## step3

https://drive.google.com/file/d/1rqO74CYCNrmRAg8Rra0JP3yZtJ-rfket/view or 百度网盘:https://pan.baidu.com/share/init?surl=5kEfCxpy-T7tz60msxxExg (code:ueq4)

1.Download eigen-3.3.9.zip 

2.Extract eigen-3.3.9.zip into **app/src/main/jni** 

## step4
Open this project with Android Studio, build it and enjoy!

