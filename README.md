UniqueDeviceID
==============

This cordova plugin provides a unique device identifier. This is to avoid problems when using UUID or other solutions.

## Installation

```cordova plugin add lycwed-cordova-plugin-udid```

## Supported Platforms

- Android
- iOS
- Windows Phone 8

## Usage

    // Get UUID
    window.plugins.uniqueDeviceID.get(success, fail);

Success callback function:

    function success(uuid)
    {
        console.log(uuid);
    };
