# apriltag_bazel
A bazel consumable repository for apriltags.

## Installing dependencies.
The only dependency to install is OpenCV.
```
sudo apt install libopencv-dev
```

The file `externals/opencv.BUILD.bazel` contains hard-coded paths to the location of the OpenCV installation. If you run into trouble building the demos, you may need to fiddle with these.
