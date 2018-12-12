# qt-c++

https://wiki.qt.io/Install_Qt_5_on_Ubuntu
# Qt5 install
```
$ sudo apt-get install qt5-default qtcreator -y
$ sudo apt-get install qt5-doc qt5-doc-html qtbase5-doc-html qtbase5-examples -y
```
# Install qtgstreamer-plugins-qt5
```
sudo apt-get update
sudo apt-get install qtgstreamer-plugins-qt5
```
# Gstreamer config ( add blow line on project confige file)
```
CONFIG += link_pkgconfig
PKGCONFIG += gstreamer-1.0 glib-2.0 gobject-2.0
```
