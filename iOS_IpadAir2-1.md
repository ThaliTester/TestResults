#### Test 5133502860beea6_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5133502860beea6/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/51EB26A8-F143-40EA-B737-5AFC527DEF5A/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/51EB26A8-F143-40EA-B737-5AFC527DEF5A/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5133502860beea6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5133502860beea6/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/98873E32-DBCE-44D8-90F1-A4B006E1E311/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54363"
,(lldb)     command script import "/tmp/51EB26A8-F143-40EA-B737-5AFC527DEF5A/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-24 11:34:17.135 ThaliTest[1188:1561299] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F2132D8F-5742-4307-9C65-3B4F97B2C87E/Library/Cookies/Cookies.binarycookies
,2015-11-24 11:34:17.431 ThaliTest[1188:1561299] Apache Cordova native platform version 3.9.2 is starting.
2015-11-24 11:34:17.432 ThaliTest[1188:1561299] Multi-tasking -> Device: YES, App: YES
,2015-11-24 11:34:17.437 ThaliTest[1188:1561299] Unlimited access to network resources
,2015-11-24 11:34:17.443 ThaliTest[1188:1561299] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-24 11:34:21.610 ThaliTest[1188:1561299] Resetting plugins due to page load.
,2015-11-24 11:34:22.931 ThaliTest[1188:1561299] Finished load of: file:///var/mobile/Containers/Bundle/Application/98873E32-DBCE-44D8-90F1-A4B006E1E311/ThaliTest.app/www/index.html
,2015-11-24 11:34:23.068 ThaliTest[1188:1561299] JXcore Cordova plugin initializing
,2015-11-24 11:34:23.068 ThaliTest[1188:1561512] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Toggling radios to true
,Warning: iOS does not support ToggleBluetooth
,Could not toggle Bluetooth - Warning: iOS does not support ToggleBluetooth
,2015-11-24 11:34:23.196 ThaliTest[1188:1561512] Error!: callback is not a function
Stack:[{"_fileName":"/private/var/mobile/Containers/Bundle/Application/98873E32-DBCE-44D8-90F1-A4B006E1E311/ThaliTest.app/www/jxcore/lib/testUtils.js","_functionName":"exports.toggleBluetooth/<","_lineNumber":"36","_columnNumber":"5","_msg":"    at exports.toggleBluetooth/<@/private/var/mobile/Containers/Bundle/Application/98873E32-DBCE-44D8-90F1-A4B006E1E311/ThaliTest.app/www/jxcore/lib/testUtils.js:36:5"},{"_fileName":"mai,n.js","_functionName":"JXMobile.ToggleBluetooth","_lineNumber":"203","_columnNumber":"5","_msg":"    at JXMobile.ToggleBluetooth@main.js:203:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/98873E32-DBCE-44D8-90F1-A4B006E1E311/ThaliTest.,app/www/jxcore/lib/testUtils.js","_functionName":"exports.toggleBluetooth","_lineNumber":"32","_columnNumber":"3","_msg":"    at exports.toggleBluetooth@/private/var/mobile/Containers/Bundle/Application/98873E32-DBCE-44D8-90F1-A4B006E1E311/ThaliTest.app/www/jxcore/lib/testUtils.js:32:3"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/98873E32-DBCE-44D8-90F1-A4B006E1E311/ThaliTest.app/www/jxcore/lib/testUtils.js","_functionName":"exports.toggleRadios","_lineNumber":"15","_columnNumber":"3",",_msg":"    at exports.toggleRadios@/private/var/mobile/Containers/Bundle/Application/98873E32-DBCE-44D8-90F1-A4B006E1E311/ThaliTest.app/www/jxcore/lib/testUtils.js:15:3"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/98873E32-DBCE-44D8-90,F1-A4B006E1E311/ThaliTest.app/www/jxcore/app.js","_functionName":"","_lineNumber":"13","_columnNumber":"1","_msg":"    at @/private/var/mobile/Containers/Bundle/Application/98873E32-DBCE-44D8-90F1-A4B006E1E311/ThaliTest.app/www/jxcore/app.js:13:1"},{"_file,Name":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"597","_columnNumber":"10","_msg":"    at Module.prototype._compile@module.js:597:10"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_,columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"mod,ule.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"}]

```
