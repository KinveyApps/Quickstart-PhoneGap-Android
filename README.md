# TestDrive-PhoneGap-Android

> The TestDrive sample application provides you with a near blank template to get started with. It is great for learning and trying Kinvey, or to build your first application upon.

*It is recommended to update to [v1 of the library](http://devcenter.kinvey.com/phonegap/). The TestDrive for that version is available [here](https://github.com/KinveyApps/TestDrive-PhoneGap).*

## Run It
After downloading or cloning the repository:

* Replace `<your-app-key>` and `<your-app-secret>` (lines 27–28 in `assets/www/index.html`).
* [Set-up](https://developer.android.com/tools/devices/emulator.html) a virtual Android device. Then, deploy the project to this device.

## Functionality
This application demonstrates:

* Basic set-up for PhoneGap apps using Kinvey
* Pinging the service

## Architecture
The starting point of this application is `assets/www/index.html`. Here, you will find placeholders and hints on where to put your application content, styles, and scripts. Code to connect your app with Kinvey is already inserted.

By default, the sample app includes a button to ping the Kinvey service. If you want to get rid of this functionality, simply remove `assets/www/scripts/ping.js`, and delete the button HTML tag from `assets/www/index.html`.

To learn more about the features PhoneGap provides, read the [PhoneGap Documentation](http://docs.phonegap.com).