To install GoCV, run the following command:

go get -u -d gocv.io/x/gocv
To run code that uses the GoCV package, you must also install OpenCV 3.4.3 on your system. Here are instructions for Ubuntu, Raspian, macOS, and Windows.

Ubuntu/Linux
Installation
You can use make to install OpenCV 4.0.0 with the handy Makefile included with this repo. If you already have installed OpenCV, you do not need to do so again. The installation performed by the Makefile is minimal, so it may remove OpenCV options such as Python or Java wrappers if you have already installed OpenCV some other way.

Quick Install
The following commands should do everything to download and install OpenCV 4.0.0 on Linux:

cd $GOPATH/src/gocv.io/x/gocv
make install
If it works correctly, at the end of the entire process, the following message should be displayed:

gocv version: 0.17.0
opencv lib version: 4.0.0
That's it, now you are ready to use GoCV.

