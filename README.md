# AR Doodling
AR Doodling is an AR application inspired by Google. You can draw different color and different width lines in 3d space by pressing your screen and moving the phone around the space. 

The code is base on [AR Drawing](https://github.com/googlecreativelab/ar-drawing-java), I changed the code to make the lines can have different colors, where I used [colorpicker](https://github.com/QuadFlask/colorpicker) for this part. I also added some comments in Chinese to the codes.

AR涂鸦是一款基于AR Drawing的开源app，可以绘制3d的线条并改变线条的颜色和粗细。为了便于理解，我还加入了一些中文注释，这些注释有些来自网络上的解读。

## Get started
To build the project, download it and open it in Android Studio 3.0. All dependencies should automatically be fetched by Android Studio. 

Before launching the app on your phone you have to install [ARCore](https://github.com/google-ar/arcore-android-sdk/releases/download/sdk-preview/arcore-android-sdk-preview.zip) on it. 

You can check if your device is supported on [this list](https://developers.google.com/ar/discover/#supported_devices)

## Demo

## TODO

目前AR Doodling虽然可以改变线条的颜色，但是只能同时改变所有线条的颜色，而不能单独改变某一线段的颜色。
