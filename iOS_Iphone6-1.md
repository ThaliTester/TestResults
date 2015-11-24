#### Test 5133502860beea6_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5133502860beea6/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/96D1620A-0AC9-4EC6-8FF2-C056F3B8ED1F/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/96D1620A-0AC9-4EC6-8FF2-C056F3B8ED1F/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5133502860beea6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5133502860beea6/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5553E5E7-464E-4D51-9B7A-78AF3E8E9AE6/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54388"
,(lldb)     command script import "/tmp/96D1620A-0AC9-4EC6-8FF2-C056F3B8ED1F/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-24 11:35:04.931 ThaliTest[1525:1175074] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/32D2C46C-A545-46D2-BC69-703AC0C93B30/Library/Cookies/Cookies.binarycookies
,2015-11-24 11:35:05.320 ThaliTest[1525:1175074] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-24 11:35:05.321 ThaliTest[1525:1175074] Multi-tasking -> Device: YES, App: YES
,2015-11-24 11:35:05.330 ThaliTest[1525:1175074] Unlimited access to network resources
,2015-11-24 11:35:05.336 ThaliTest[1525:1175074] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-24 11:35:08.832 ThaliTest[1525:1175074] Resetting plugins due to page load.
,2015-11-24 11:35:09.287 ThaliTest[1525:1175074] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/5553E5E7-464E-4D51-9B7A-78AF3E8E9AE6/ThaliTest.app/www/index.html
,2015-11-24 11:35:09.492 ThaliTest[1525:1175074] JXcore Cordova plugin initializing
2015-11-24 11:35:09.493 ThaliTest[1525:1175221] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Toggling radios to true
,Warning: iOS does not support ToggleBluetooth
Could not toggle Bluetooth - Warning: iOS does not support ToggleBluetooth
,2015-11-24 11:35:09.656 ThaliTest[1525:1175221] Error!: callback is not a function
Stack:[{"_fileName":"/private/var/mobile/Containers/Bundle/Application/5553E5E7-464E-4D51-9B7A-78AF3E8E9AE6/ThaliTest.app/www/jxcore/lib/testUtils.js","_functionName":"expo,rts.toggleBluetooth/<","_lineNumber":"36","_columnNumber":"5","_msg":"    at exports.toggleBluetooth/<@/private/var/mobile/Containers/Bundle/Application/5553E5E7-464E-4D51-9B7A-78AF3E8E9AE6/ThaliTest.app/www/jxcore/lib/testUtils.js:36:5"},{"_fileName":"mai,n.js","_functionName":"JXMobile.ToggleBluetooth","_lineNumber":"203","_columnNumber":"5","_msg":"    at JXMobile.ToggleBluetooth@main.js:203:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/5553E5E7-464E-4D51-9B7A-78AF3E8E9AE6/ThaliTest.,app/www/jxcore/lib/testUtils.js","_functionName":"exports.toggleBluetooth","_lineNumber":"32","_columnNumber":"3","_msg":"    at exports.toggleBluetooth@/private/var/mobile/Containers/Bundle/Application/5553E5E7-464E-4D51-9B7A-78AF3E8E9AE6/ThaliTest.app/ww,w/jxcore/lib/testUtils.js:32:3"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/5553E5E7-464E-4D51-9B7A-78AF3E8E9AE6/ThaliTest.app/www/jxcore/lib/testUtils.js","_functionName":"exports.toggleRadios","_lineNumber":"15","_columnNumber":"3",",_msg":"    at exports.toggleRadios@/private/var/mobile/Containers/Bundle/Application/5553E5E7-464E-4D51-9B7A-78AF3E8E9AE6/ThaliTest.app/www/jxcore/lib/testUtils.js:15:3"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/5553E5E7-464E-4D51-9B,7A-78AF3E8E9AE6/ThaliTest.app/www/jxcore/app.js","_functionName":"","_lineNumber":"13","_columnNumber":"1","_msg":"    at @/private/var/mobile/Containers/Bundle/Application/5553E5E7-464E-4D51-9B7A-78AF3E8E9AE6/ThaliTest.app/www/jxcore/app.js:13:1"},{"_file,Name":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"597","_columnNumber":"10","_msg":"    at Module.prototype._compile@module.js:597:10"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_,columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"mod,ule.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"}]

```
