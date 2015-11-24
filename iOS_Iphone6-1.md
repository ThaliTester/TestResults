#### Test 513350282ff9e94_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/513350282ff9e94/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/8BB2392E-0867-4557-A322-1050EE45F8E9/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/8BB2392E-0867-4557-A322-1050EE45F8E9/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/513350282ff9e94/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/513350282ff9e94/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5F06DEF0-36F5-4E95-BCEC-E9D9D6328CAC/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54527"
,(lldb)     command script import "/tmp/8BB2392E-0867-4557-A322-1050EE45F8E9/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2015-11-24 12:45:08.672 ThaliTest[1537:1181774] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9DD4F39A-58DC-4E65-A8F9-356B339F353E/Library/Cookies/Cookies.binarycookies
,2015-11-24 12:45:09.061 ThaliTest[1537:1181774] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-24 12:45:09.062 ThaliTest[1537:1181774] Multi-tasking -> Device: YES, App: YES
,2015-11-24 12:45:09.071 ThaliTest[1537:1181774] Unlimited access to network resources
,2015-11-24 12:45:09.076 ThaliTest[1537:1181774] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-24 12:45:12.648 ThaliTest[1537:1181774] Resetting plugins due to page load.
,2015-11-24 12:45:13.022 ThaliTest[1537:1181774] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/5F06DEF0-36F5-4E95-BCEC-E9D9D6328CAC/ThaliTest.app/www/index.html
,2015-11-24 12:45:13.146 ThaliTest[1537:1181774] JXcore Cordova plugin initializing
2015-11-24 12:45:13.147 ThaliTest[1537:1181910] JXcore instance initializing
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
,2015-11-24 12:45:13.287 ThaliTest[1537:1181910] Error!: callback is not a function
Stack:[{"_fileName":"/private/var/mobile/Containers/Bundle/Application/5F06DEF0-36F5-4E95-BCEC-E9D9D6328CAC/ThaliTest.app/www/jxcore/lib/testUtils.js","_functionName":"exports.toggleBluetooth/<","_lineNumber":"36","_columnNumber":"5","_msg":"    at exports.toggleBluetooth/<@/private/var/mobile/Containers/Bundle/Application/5F06DEF0-36F5-4E95-BCEC-E9D9D6328CAC/ThaliTest.app/www/jxcore/lib/testUtils.js:36:5"},{"_fileName":"mai,n.js","_functionName":"JXMobile.ToggleBluetooth","_lineNumber":"203","_columnNumber":"5","_msg":"    at JXMobile.ToggleBluetooth@main.js:203:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/5F06DEF0-36F5-4E95-BCEC-E9D9D6328CAC/ThaliTest.app/www/jxcore/lib/testUtils.js","_functionName":"exports.toggleBluetooth","_lineNumber":"32","_columnNumber":"3","_msg":"    at exports.toggleBluetooth@/private/var/mobile/Containers/Bundle/Application/5F06DEF0-36F5-4E95-BCEC-E9D9D6328CAC/ThaliTest.app/ww,w/jxcore/lib/testUtils.js:32:3"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/5F06DEF0-36F5-4E95-BCEC-E9D9D6328CAC/ThaliTest.app/www/jxcore/lib/testUtils.js","_functionName":"exports.toggleRadios","_lineNumber":"15","_columnNumber":"3",",_msg":"    at exports.toggleRadios@/private/var/mobile/Containers/Bundle/Application/5F06DEF0-36F5-4E95-BCEC-E9D9D6328CAC/ThaliTest.app/www/jxcore/lib/testUtils.js:15:3"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/5F06DEF0-36F5-4E95-BC,EC-E9D9D6328CAC/ThaliTest.app/www/jxcore/app.js","_functionName":"","_lineNumber":"13","_columnNumber":"1","_msg":"    at @/private/var/mobile/Containers/Bundle/Application/5F06DEF0-36F5-4E95-BCEC-E9D9D6328CAC/ThaliTest.app/www/jxcore/app.js:13:1"},{"_file,Name":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"597","_columnNumber":"10","_msg":"    at Module.prototype._compile@module.js:597:10"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_,columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"mod,ule.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"}]

```
