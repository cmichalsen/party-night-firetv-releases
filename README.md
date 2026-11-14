# Party Night for Fire TV: downloads

APK builds of Party Night, a party game where the TV hosts and phones are the controllers.

## Install on a Fire TV

1. On the Fire TV: Settings > My Fire TV > Developer options > turn on **Install unknown apps** for the Downloader app.
2. Open Downloader and enter this link (always the newest build):
   https://github.com/cmichalsen/party-night-firetv-releases/releases/latest/download/party-night.apk
3. Install, then open **Party Night** from Your Apps.

Or from a PC with ADB debugging enabled on the Fire TV:

    adb connect <fire-tv-ip>:5555
    adb install -r party-night.apk

Phones join by scanning the QR code on the TV. The TV and phones must be on the same Wi-Fi.
