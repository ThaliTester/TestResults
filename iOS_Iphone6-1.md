#### Test 50650278b04e3e5_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278b04e3e5/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/9E6D4206-753F-4D23-ABF3-DE6086B865BA/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/9E6D4206-753F-4D23-ABF3-DE6086B865BA/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.4 (12H143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278b04e3e5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278b04e3e5/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/EE0F8DE5-0B1A-46FE-9A58-B5106ACF68D0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60833"
,(lldb)     command script import "/tmp/9E6D4206-753F-4D23-ABF3-DE6086B865BA/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2015-12-03 18:08:28.345 ThaliTest[2656:2228597] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/ED1AEF8D-10C1-484B-B1EA-A4ECB67168C1/Library/Cookies/Cookies.binarycookies
,2015-12-03 18:08:28.738 ThaliTest[2656:2228597] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-03 18:08:28.739 ThaliTest[2656:2228597] Multi-tasking -> Device: YES, App: YES
,2015-12-03 18:08:28.748 ThaliTest[2656:2228597] Unlimited access to network resources
,2015-12-03 18:08:28.753 ThaliTest[2656:2228597] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-03 18:08:32.263 ThaliTest[2656:2228597] Resetting plugins due to page load.
,2015-12-03 18:08:32.622 ThaliTest[2656:2228597] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/EE0F8DE5-0B1A-46FE-9A58-B5106ACF68D0/ThaliTest.app/www/index.html
,2015-12-03 18:08:32.748 ThaliTest[2656:2228597] JXcore Cordova plugin initializing
,2015-12-03 18:08:32.749 ThaliTest[2656:2228732] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2015-12-03 18:08:35.199 ThaliTest[2656:2228732] Error!: Cannot find module '../../lib/thali-tape'
Stack:[{"_fileName":"module.js","_functionName":"Module._oldRes","_lineNumber":"776","_columnNumber":"15","_msg":"    at Module._oldRes@module.js:776:15"},{"_fileName":"module.js","_functionName":"Module._resolveFilename","_lineNumber":"1608","_columnNumber":"1","_msg":"    at Module._resolveFilename@module.js:1608:1"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"337","_columnNumber":,"18","_msg":"    at Module._load@module.js:337:18"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionN,ame":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/EE0F8DE5-0B1A-46FE-9A58-B5106ACF68D0/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationMan,ager.js","_functionName":"","_lineNumber":"9","_columnNumber":"12","_msg":"    at @/private/var/mobile/Containers/Bundle/Application/EE0F8DE5-0B1A-46FE-9A58-B5106ACF68D0/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js:9:12"},{"_fileName":",module.js","_functionName":"Module.prototype._compile","_lineNumber":"597","_columnNumber":"10","_msg":"    at Module.prototype._compile@module.js:597:10"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnN,umber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"}]

```
