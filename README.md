# IOX Output Dev

Sends a message to a device, turning the IOX on or off, with a failsafe timer.

To install this add-in, navigate to Settings => Add-Ins => Click the "+ Add-In" button.
Paste the following into the Configuration:

{
  "name": "IOX Output Dev",
  "supportEmail": "dbrown@cameramatics.com",
  "version": "1.0",
  "items": [
    {
      "url": "https://cdn.jsdelivr.net/gh/deanjbrown/addin-iox-output-dev@master/addin-iox-output-dev.html",
      "path": "AdministrationLink/",
      "menuName": {
        "en": "IOX Output Dev"
      },
      "icon": "https://cdn.jsdelivr.net/gh/Geotab/sdk-addin-samples@master/addin-iox-output/dist/images/icon.svg"
    }
  ],
  "isSigned": false
}
