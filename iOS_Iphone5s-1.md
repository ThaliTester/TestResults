#### Test 5133502860beea6_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5133502860beea6/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/71280828-E469-4AFE-A837-18C5DD82FFF4/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/71280828-E469-4AFE-A837-18C5DD82FFF4/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5133502860beea6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5133502860beea6/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/548E8194-51A7-4239-9B75-27224054654F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54390"
,(lldb)     command script import "/tmp/71280828-E469-4AFE-A837-18C5DD82FFF4/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-24 11:35:08.154 ThaliTest[1475:1240214] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/339E34B6-FD52-4CAD-B962-33490C2033A7/Library/Cookies/Cookies.binarycookies
,2015-11-24 11:35:08.561 ThaliTest[1475:1240214] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-24 11:35:08.562 ThaliTest[1475:1240214] Multi-tasking -> Device: YES, App: YES
,2015-11-24 11:35:08.571 ThaliTest[1475:1240214] Unlimited access to network resources
,2015-11-24 11:35:08.577 ThaliTest[1475:1240214] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-24 11:35:12.247 ThaliTest[1475:1240214] Resetting plugins due to page load.
,2015-11-24 11:35:12.717 ThaliTest[1475:1240214] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/548E8194-51A7-4239-9B75-27224054654F/ThaliTest.app/www/index.html
,2015-11-24 11:35:12.877 ThaliTest[1475:1240214] JXcore Cordova plugin initializing
2015-11-24 11:35:12.878 ThaliTest[1475:1240340] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Toggling radios to true
,Warning: iOS does not support ToggleBluetooth
,Could not toggle Bluetooth - Warning: iOS does not support ToggleBluetooth
,2015-11-24 11:35:13.046 ThaliTest[1475:1240340] Error!: callback is not a function
Stack:[{"_fileName":"/private/var/mobile/Containers/Bundle/Application/548E8194-51A7-4239-9B75-27224054654F/ThaliTest.app/www/jxcore/lib/testUtils.js","_functionName":"expo,rts.toggleBluetooth/<","_lineNumber":"36","_columnNumber":"5","_msg":"    at exports.toggleBluetooth/<@/private/var/mobile/Containers/Bundle/Application/548E8194-51A7-4239-9B75-27224054654F/ThaliTest.app/www/jxcore/lib/testUtils.js:36:5"},{"_fileName":"mai,n.js","_functionName":"JXMobile.ToggleBluetooth","_lineNumber":"203","_columnNumber":"5","_msg":"    at JXMobile.ToggleBluetooth@main.js:203:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/548E8194-51A7-4239-9B75-27224054654F/ThaliTest.,app/www/jxcore/lib/testUtils.js","_functionName":"exports.toggleBluetooth","_lineNumber":"32","_columnNumber":"3","_msg":"    at exports.toggleBluetooth@/private/var/mobile/Containers/Bundle/Application/548E8194-51A7-4239-9B75-27224054654F/ThaliTest.app/ww,w/jxcore/lib/testUtils.js:32:3"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/548E8194-51A7-4239-9B75-27224054654F/ThaliTest.app/www/jxcore/lib/testUtils.js","_functionName":"exports.toggleRadios","_lineNumber":"15","_columnNumber":"3",",_msg":"    at exports.toggleRadios@/private/var/mobile/Containers/Bundle/Application/548E8194-51A7-4239-9B75-27224054654F/ThaliTest.app/www/jxcore/lib/testUtils.js:15:3"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/548E8194-51A7-4239-9B,75-27224054654F/ThaliTest.app/www/jxcore/app.js","_functionName":"","_lineNumber":"13","_columnNumber":"1","_msg":"    at @/private/var/mobile/Containers/Bundle/Application/548E8194-51A7-4239-9B75-27224054654F/ThaliTest.app/www/jxcore/app.js:13:1"},{"_file,Name":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"597","_columnNumber":"10","_msg":"    at Module.prototype._compile@module.js:597:10"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_,columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"mod,ule.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"}]

```
