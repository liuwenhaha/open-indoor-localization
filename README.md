# open-indoor-localization
And simple indoor localization app and script for new beginner to start
![ScreenShop](https://github.com/LeslieXong/open-indoor-localization/blob/master/pictures/screeshot.jpg?raw=true)

## Features:
* Collecting WiFi and iBeacon data at the same time.
* Group data as train database and test points with timestamp.
* Load image map as the floor map of designated place.
* Move position by clicking on the map.
* Customizable collecting time and data source.

## How to use:
* You can clone the source code for customizing or just download the apk file to install.
* Requirement:
   1. Android grant location/storage permission for scan beacon and wifi.
   2. Open WiFi and Bluetooth function on device.
* Prepare a map: This app take a image as a floor map, user should input the real width and height(in meters) for conduct coordinate conversion.
* After collecting data, extract the train and test data to computer and use the PyLocalizer for knn localization.
![Data format](https://github.com/LeslieXong/open-indoor-localization/blob/master/pictures/data_format.png?raw=true)

## Troubleshooting:
If App can not load or no data collected, please double check:
* The location/storage permission has been granted at you setting
* Bluetooth/WiFi has been enabled.

## Dependencies:
https://github.com/davemorrissey/subsampling-scale-image-view



