# AR Doodling
**AR Doodling** is an AR application inspired by Google. You can draw different colorful lines in 3d space by pressing your screen and moving the phone around the space. 

The code is base on [AR Drawing](https://github.com/googlecreativelab/ar-drawing-java). The original codes can only draw white line in 3d space. So I changed some codes to make the lines can have different colors, where I used [colorpicker](https://github.com/QuadFlask/colorpicker) for this part. I also added some comments in Chinese to help understanding the codes.

**AR涂鸦**是受Google开源项目启发的AR应用程序。您可以通过按屏幕并在空间周围移动手机，在3d空间中绘制彩色线条。

该代码基于[AR Drawing](https://github.com/googlecreativelab/ar-drawing-java)。原始代码只能在3d空间中绘制白色线条。所以我更改了一些代码，使线条可以有不同的颜色，这块使用了开源项目[colorpicker](https://github.com/QuadFlask/colorpicker)来挑选不同颜色。我还在代码关键位置添加了一些中文注释，以帮助理解代码。

## Get started
To build the project, download it and open it in Android Studio 3.0. All dependencies should automatically be fetched by Android Studio. 

Before launching the app on your phone you have to install [ARCore](https://github.com/google-ar/arcore-android-sdk/releases/download/sdk-preview/arcore-android-sdk-preview.zip) on it. 

You can check if your device is supported on [this list](https://developers.google.com/ar/discover/#supported_devices)

## Demo

<img src="https://github.com/gjgjh/AR-Doodling/blob/master/support_files/demo.gif" width = 40% height = 40% />

## TODO

At present, although AR Doodling can change the color of lines, it can only change the color of all lines at the same time, and cannot change the color of a certain line segment separately. This is because in the original code, the line rendering class are encapsulated. It needs OpenGL stuff to change this part, but still the rendering efficiency may be lower than the original code.

Feel free to contribute to improve this repo.

目前AR Doodling虽然可以改变线条的颜色，但是只能同时改变所有线条的颜色，而不能单独改变某一线段的颜色。这是因为原始代码中，将线渲染类封装在了一起。因此改动起来需要涉及OpenGL的内容，而且渲染的效率可能会比原始代码要低。

欢迎提pull request将这部分继续改进。
