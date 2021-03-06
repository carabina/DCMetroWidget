# DC Metro Widget [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/clrung/DCMetroWidget/master/LICENSE) [![platforms](https://img.shields.io/badge/platform-macOS-lightgrey.svg)]()

<p align="center">
<a href="http://appstore.com/mac/dcmetro"><img src="https://www.mapdiva.com/wp-content/uploads/2011/01/Mac_App_Store_Badge_US_UK1.png" width="400" height="200" alt="Available on the Mac App Store"/></a>
</p>

A Today extension for macOS' Notification Center that tracks DC Metro arrival times.

<img src="https://raw.githubusercontent.com/clrung/DCMetroWidget/master/Screenshots/GitHub/Main.png" width="331"/> <img src="https://raw.githubusercontent.com/clrung/DCMetroWidget/master/Screenshots/GitHub/Settings.png" width="331"/>

## Requirements
* macOS 10.10+

## Installation
This project uses [CocoaPods](https://cocoapods.org).  You know what to do:

```bash
$ pod install
```

### WMATA API Key
The extension will not fetch information from WMATA's API without an API key.  You can setup a free account and get a key [here](https://developer.wmata.com/).  Replace [WMATA\_KEY\_GOES\_HERE] in [TodayViewController.swift](https://github.com/clrung/DCMetroWidget/blob/master/DCMetroWidget/TodayViewController.swift) with your key.

## Dependencies
* [WMATAFetcher](https://cocoapods.org/pods/WMATAFetcher)
* [Crashlytics](https://cocoapods.org/pods/Crashlytics)
