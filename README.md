# cordova-sunmi-inner-printer

#V1.0.0
Changed from canvas.save(Canvas.ALL_SAVE_FLAG) to canvas.save()
Added android:exported="false" receiver and android:exported="true" service in plugin.xml ( Androidmanifest section)
Fixed Printer.java


Steps to follow

1. cordova plugin rm cordova-sunmi-inner-printer
2. cordova plugin add https://github.com/S3nivus/cordova-sunmi-inner-printer.git

sunmiInnerPrinter.printOriginalText("Hello World!")

you can see the list of available command in 

www\innerprinter.js file.
