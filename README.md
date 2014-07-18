# Cordova Progress-Indicator Plugin#
This plugin allows you to show a native Progress Indicator on iOS - by [Paolo Bernasconi](https://github.com/pbernasconi)

There are several types of indicators available:

* [Simple](#simple)
* [Determinate](#determinate)
* [Annular](#annular)
* [Bar](#bar)
* [Success](#others)
* [Simple Text](#others)


Installation
============


### Platforms

Currently **this plugin supports iOS**, with plans to *soon* implement Android.

* **iOS**
* *Android coming soon*


### Automatically

**Cordova** - To install this plugin simply type into the command line: (If you don't have the cordova CLI install using `npm install -g cordova`)
```bash
cordova plugin add https://github.com/pbernasconi/cordova-progressIndicator.git
```

**PhoneGap** - Installing this plugin is just as easy and requires this command:
```bash
phonegap local plugin add https://github.com/pbernasconi/cordova-progressIndicator.git
```

## 2. Screenshots

iOS

![ScreenShot](demo/screenshots/simple-arge-img.jpg)

|Simple|Label|Label-Detail|
|------|-----|------------|
|![](demo/screenshots/simple.jpg)|![](demo/screenshots/simple-label.jpg)|![](demo/screenshots/simple-label-detail.jpg)|

|Determinate|Determinate Label|
|---|---|
|![](demo/screenshots/determinate-simple.jpg)|![](demo/screenshots/determinate-label.jpg)


|Annular|Annular Label|
|---|---|
|![](demo/screenshots/annular-simple.jpg)|![](demo/screenshots/annular-label.jpg)


|Bar|Bar Label|
|---|---|
|![](demo/screenshots/bar-simple.jpg)|![](demo/screenshots/bar-label.jpg)

|Success|Text Top|Text Botom|
|---|---|--|
|![](demo/screenshots/success.jpg)|![](demo/screenshots/text-top.jpg)|![](demo/screenshots/text-bottom.jpg)




### 5. CHANGELOG

1.0: initial version supporting iOS

### 6. CREDITS

 - [MBProgressHUD](https://github.com/jdg/MBProgressHUD)
 - [Cordova-ActivityIndicator](https://github.com/Initsogar/cordova-activityindicator)


### 7. License

[The MIT License (MIT)](http://www.opensource.org/licenses/mit-license.html)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.



## Adding the plugin to your project ##
To install the plugin, use the Cordova CLI and enter the following:<br />
`cordova plugin add https://github.com/Initsogar/cordova-activityindicator`

## Platforms ##
- Android
- iOS

## Use ##
To show the dialog, use the following code:<br />
`ActivityIndicator.show(message)`


To hide the dialog, use the following code:<br />
`ActivityIndicator.hide()`

## Credits ##
This plugin is inspired in the following projects:<br />
https://github.com/jdg/MBProgressHUD<br />
https://github.com/pebois/phonegap-plugin-ProgressHUD<br />
https://github.com/bormansquirrel/WaitingDialog




