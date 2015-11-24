#### Test 513350282ff9e94_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/513350282ff9e94/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image already mounted
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/D23F6695-37D5-4796-AE41-7F3ED05C3BFE/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/D23F6695-37D5-4796-AE41-7F3ED05C3BFE/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/513350282ff9e94/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/513350282ff9e94/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/293A234F-7F10-4B6F-A657-2F2C2E3616EC/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54525"
,(lldb)     command script import "/tmp/D23F6695-37D5-4796-AE41-7F3ED05C3BFE/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-11-24 12:46:01.389 ThaliTest[708:60b] Apache Cordova native platform version 3.9.2 is starting.
,2015-11-24 12:46:01.391 ThaliTest[708:60b] Multi-tasking -> Device: YES, App: YES
,2015-11-24 12:46:01.399 ThaliTest[708:60b] Unlimited access to network resources
,2015-11-24 12:46:01.407 ThaliTest[708:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-11-24 12:46:12.178 ThaliTest[708:60b] Resetting plugins due to page load.
,2015-11-24 12:46:12.616 ThaliTest[708:60b] Finished load of: file:///var/mobile/Applications/293A234F-7F10-4B6F-A657-2F2C2E3616EC/ThaliTest.app/www/index.html
,2015-11-24 12:46:12.793 ThaliTest[708:60b] JXcore Cordova plugin initializing
,2015-11-24 12:46:12.795 ThaliTest[708:6807] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Toggling radios to true
,Warning: iOS does not support ToggleBluetooth
,Could not toggle Bluetooth - Warning: iOS does not support ToggleBluetooth
,2015-11-24 12:46:13.080 ThaliTest[708:6807] Error!: callback is not a function
Stack:[{"_fileName":"/private/var/mobile/Applications/293A234F-7F10-4B6F-A657-2F2C2E3616EC/ThaliTest.app/www/jxcore/lib/testUtils.js","_functionName":"exports.toggleBluetooth/<,","_lineNumber":"36","_columnNumber":"5","_msg":"    at exports.toggleBluetooth/<@/private/var/mobile/Applications/293A234F-7F10-4B6F-A657-2F2C2E3616EC/ThaliTest.app/www/jxcore/lib/testUtils.js:36:5"},{"_fileName":"main.js","_functionName":"JXMobile.Toggle,Bluetooth","_lineNumber":"203","_columnNumber":"5","_msg":"    at JXMobile.ToggleBluetooth@main.js:203:5"},{"_fileName":"/private/var/mobile/Applications/293A234F-7F10-4B6F-A657-2F2C2E3616EC/ThaliTest.app/www/jxcore/lib/testUtils.js","_functionName":"expor,ts.toggleBluetooth","_lineNumber":"32","_columnNumber":"3","_msg":"    at exports.toggleBluetooth@/private/var/mobile/Applications/293A234F-7F10-4B6F-A657-2F2C2E3616EC/ThaliTest.app/www/jxcore/lib/testUtils.js:32:3"},{"_fileName":"/private/var/mobile/Appli,cations/293A234F-7F10-4B6F-A657-2F2C2E3616EC/ThaliTest.app/www/jxcore/lib/testUtils.js","_functionName":"exports.toggleRadios","_lineNumber":"15","_columnNumber":"3","_msg":"    at exports.toggleRadios@/private/var/mobile/Applications/293A234F-7F10-4B6F-A6,57-2F2C2E3616EC/ThaliTest.app/www/jxcore/lib/testUtils.js:15:3"},{"_fileName":"/private/var/mobile/Applications/293A234F-7F10-4B6F-A657-2F2C2E3616EC/ThaliTest.app/www/jxcore/app.js","_functionName":"","_lineNumber":"13","_columnNumber":"1","_msg":"    at @,/private/var/mobile/Applications/293A234F-7F10-4B6F-A657-2F2C2E3616EC/ThaliTest.app/www/jxcore/app.js:13:1"},{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"597","_columnNumber":"10","_msg":"    at Module.prototype._comp,ile@module.js:597:10"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.lo,ad","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"}]

```
