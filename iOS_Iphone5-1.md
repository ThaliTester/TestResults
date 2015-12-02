#### Test 52383621d5a0cb8_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/52383621d5a0cb8/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image already mounted
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/322439F8-627F-45FC-B932-8BEAF0DFED96/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/322439F8-627F-45FC-B932-8BEAF0DFED96/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/52383621d5a0cb8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/52383621d5a0cb8/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/06DDBAD9-5307-480E-A725-4ED90E2E0EC1/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59054"
,(lldb)     command script import "/tmp/322439F8-627F-45FC-B932-8BEAF0DFED96/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-02 12:40:59.366 ThaliTest[1080:60b] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-02 12:40:59.371 ThaliTest[1080:60b] Multi-tasking -> Device: YES, App: YES
,2015-12-02 12:40:59.376 ThaliTest[1080:60b] Unlimited access to network resources
,2015-12-02 12:40:59.385 ThaliTest[1080:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-02 12:41:10.124 ThaliTest[1080:60b] Resetting plugins due to page load.
,2015-12-02 12:41:10.993 ThaliTest[1080:60b] Finished load of: file:///var/mobile/Applications/06DDBAD9-5307-480E-A725-4ED90E2E0EC1/ThaliTest.app/www/index.html
,2015-12-02 12:41:11.173 ThaliTest[1080:60b] JXcore Cordova plugin initializing
,2015-12-02 12:41:11.175 ThaliTest[1080:6707] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2015-12-02 12:41:11.413 ThaliTest[1080:6707] Error!: Cannot find module '../server-address.js'
Stack:[{"_fileName":"module.js","_functionName":"Module._oldRes","_lineNumber":"776","_columnNumber":"15","_msg":"    at Module._oldRes@module.js:776:15"},{"_fi,leName":"module.js","_functionName":"Module._resolveFilename","_lineNumber":"1608","_columnNumber":"1","_msg":"    at Module._resolveFilename@module.js:1608:1"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"337","_columnNumber":"18,","_msg":"    at Module._load@module.js:337:18"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName,":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/private/var/mobile/Applications/06DDBAD9-5307-480E-A725-4ED90E2E0EC1/ThaliTest.app/www/jxcore/app.js","_functionName":"","_lineNumber":"11","_colu,mnNumber":"21","_msg":"    at @/private/var/mobile/Applications/06DDBAD9-5307-480E-A725-4ED90E2E0EC1/ThaliTest.app/www/jxcore/app.js:11:21"},{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"597","_columnNumber":"10","_msg,":"    at Module.prototype._compile@module.js:597:10"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_fu,nctionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"}]

```
