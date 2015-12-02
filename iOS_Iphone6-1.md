#### Test 52383621d5a0cb8_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/52383621d5a0cb8/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/0B2543ED-0578-4681-A89C-37D99CAF9B09/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/0B2543ED-0578-4681-A89C-37D99CAF9B09/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/52383621d5a0cb8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/52383621d5a0cb8/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4899D490-58F0-4423-985F-F85E954CF01C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59052"
,(lldb)     command script import "/tmp/0B2543ED-0578-4681-A89C-37D99CAF9B09/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-02 12:40:05.349 ThaliTest[2409:2071628] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/569C303D-96D0-4640-A527-80FE8E4F3F21/Library/Cookies/Cookies.binarycookies
,2015-12-02 12:40:05.754 ThaliTest[2409:2071628] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-02 12:40:05.755 ThaliTest[2409:2071628] Multi-tasking -> Device: YES, App: YES
,2015-12-02 12:40:05.764 ThaliTest[2409:2071628] Unlimited access to network resources
,2015-12-02 12:40:05.769 ThaliTest[2409:2071628] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-02 12:40:09.312 ThaliTest[2409:2071628] Resetting plugins due to page load.
,2015-12-02 12:40:09.708 ThaliTest[2409:2071628] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/4899D490-58F0-4423-985F-F85E954CF01C/ThaliTest.app/www/index.html
,2015-12-02 12:40:09.835 ThaliTest[2409:2071628] JXcore Cordova plugin initializing
,2015-12-02 12:40:09.836 ThaliTest[2409:2071757] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2015-12-02 12:40:09.952 ThaliTest[2409:2071757] Error!: Cannot find module '../server-address.js'
Stack:[{"_fileName":"module.js","_functionName":"Module._oldRes","_lineNumber":"776","_columnNumber":"15","_msg":"    at Module._oldRes@module.js:776:15"},{"_fileName":"module.js","_functionName":"Module._resolveFilename","_lineNumber":"1608","_columnNumber":"1","_msg":"    at Module._resolveFilename@module.js:1608:1"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"337","_columnNumber":,"18","_msg":"    at Module._load@module.js:337:18"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionN,ame":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/4899D490-58F0-4423-985F-F85E954CF01C/ThaliTest.app/www/jxcore/app.js","_functionName":"","_lin,eNumber":"11","_columnNumber":"21","_msg":"    at @/private/var/mobile/Containers/Bundle/Application/4899D490-58F0-4423-985F-F85E954CF01C/ThaliTest.app/www/jxcore/app.js:11:21"},{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNum,ber":"597","_columnNumber":"10","_msg":"    at Module.prototype._compile@module.js:597:10"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:,627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"}]

```
