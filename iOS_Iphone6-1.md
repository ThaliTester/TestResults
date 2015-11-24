#### Test 513350288bfb88c_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/513350288bfb88c/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/7ADAC666-967B-48CF-A6B9-32BDE14E0BDC/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/7ADAC666-967B-48CF-A6B9-32BDE14E0BDC/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/513350288bfb88c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/513350288bfb88c/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8E4CDB7D-64F3-42BE-B694-47BC990BC5CA/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54659"
,(lldb)     command script import "/tmp/7ADAC666-967B-48CF-A6B9-32BDE14E0BDC/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-24 13:24:52.007 ThaliTest[1547:1186123] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/AFEE5038-0070-47E4-B684-E8842F026657/Library/Cookies/Cookies.binarycookies
,2015-11-24 13:24:52.398 ThaliTest[1547:1186123] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-24 13:24:52.399 ThaliTest[1547:1186123] Multi-tasking -> Device: YES, App: YES
,2015-11-24 13:24:52.407 ThaliTest[1547:1186123] Unlimited access to network resources
,2015-11-24 13:24:52.413 ThaliTest[1547:1186123] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-24 13:24:55.955 ThaliTest[1547:1186123] Resetting plugins due to page load.
,2015-11-24 13:24:56.350 ThaliTest[1547:1186123] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/8E4CDB7D-64F3-42BE-B694-47BC990BC5CA/ThaliTest.app/www/index.html
,2015-11-24 13:24:56.475 ThaliTest[1547:1186123] JXcore Cordova plugin initializing
,2015-11-24 13:24:56.476 ThaliTest[1547:1186252] JXcore instance initializing
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
,2015-11-24 13:24:56.613 ThaliTest[1547:1186252] Error!: this.toggleWifi is not a function
Stack:[{"_fileName":"/private/var/mobile/Containers/Bundle/Application/8E4CDB7D-64F3-42BE-B694-47BC990BC5CA/ThaliTest.app/www/jxcore/lib/testUtils.js","_functionName,":"exports.toggleRadios/<","_lineNumber":"16","_columnNumber":"5","_msg":"    at exports.toggleRadios/<@/private/var/mobile/Containers/Bundle/Application/8E4CDB7D-64F3-42BE-B694-47BC990BC5CA/ThaliTest.app/www/jxcore/lib/testUtils.js:16:5"},{"_fileName":"/p,rivate/var/mobile/Containers/Bundle/Application/8E4CDB7D-64F3-42BE-B694-47BC990BC5CA/ThaliTest.app/www/jxcore/lib/testUtils.js","_functionName":"exports.toggleBluetooth/<","_lineNumber":"36","_columnNumber":"5","_msg":"    at exports.toggleBluetooth/<@/pri,vate/var/mobile/Containers/Bundle/Application/8E4CDB7D-64F3-42BE-B694-47BC990BC5CA/ThaliTest.app/www/jxcore/lib/testUtils.js:36:5"},{"_fileName":"main.js","_functionName":"JXMobile.ToggleBluetooth","_lineNumber":"203","_columnNumber":"5","_msg":"    at JXM,obile.ToggleBluetooth@main.js:203:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/8E4CDB7D-64F3-42BE-B694-47BC990BC5CA/ThaliTest.app/www/jxcore/lib/testUtils.js","_functionName":"exports.toggleBluetooth","_lineNumber":"32","_columnNumbe,r":"3","_msg":"    at exports.toggleBluetooth@/private/var/mobile/Containers/Bundle/Application/8E4CDB7D-64F3-42BE-B694-47BC990BC5CA/ThaliTest.app/www/jxcore/lib/testUtils.js:32:3"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/8E4CDB7D-6,4F3-42BE-B694-47BC990BC5CA/ThaliTest.app/www/jxcore/lib/testUtils.js","_functionName":"exports.toggleRadios","_lineNumber":"15","_columnNumber":"3","_msg":"    at exports.toggleRadios@/private/var/mobile/Containers/Bundle/Application/8E4CDB7D-64F3-42BE-B69,4-47BC990BC5CA/ThaliTest.app/www/jxcore/lib/testUtils.js:15:3"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/8E4CDB7D-64F3-42BE-B694-47BC990BC5CA/ThaliTest.app/www/jxcore/app.js","_functionName":"","_lineNumber":"13","_columnNumber":"1",,"_msg":"    at @/private/var/mobile/Containers/Bundle/Application/8E4CDB7D-64F3-42BE-B694-47BC990BC5CA/ThaliTest.app/www/jxcore/app.js:13:1"},{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"597","_columnNumber":"10","_ms,g":"    at Module.prototype._compile@module.js:597:10"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_f,unctionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"}]

```
