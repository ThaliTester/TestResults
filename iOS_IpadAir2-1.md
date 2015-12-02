#### Test 52383621d5a0cb8_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/52383621d5a0cb8/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/6DC90AB7-9471-409D-BCA7-6593D230C97D/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/6DC90AB7-9471-409D-BCA7-6593D230C97D/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.0.2 (13A452)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/52383621d5a0cb8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/52383621d5a0cb8/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/62100E33-A177-4EBB-849B-539BC11D8324/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59038"
,(lldb)     command script import "/tmp/6DC90AB7-9471-409D-BCA7-6593D230C97D/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-02 12:39:18.296 ThaliTest[1758:2800189] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B6FBBB3B-4FAC-4850-960B-1BB5EFB8EA62/Library/Cookies/Cookies.binarycookies
,2015-12-02 12:39:18.587 ThaliTest[1758:2800189] Apache Cordova native platform version 3.9.2 is starting.
2015-12-02 12:39:18.588 ThaliTest[1758:2800189] Multi-tasking -> Device: YES, App: YES
,2015-12-02 12:39:18.594 ThaliTest[1758:2800189] Unlimited access to network resources
,2015-12-02 12:39:18.601 ThaliTest[1758:2800189] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-02 12:39:22.881 ThaliTest[1758:2800189] Resetting plugins due to page load.
,2015-12-02 12:39:24.175 ThaliTest[1758:2800189] Finished load of: file:///var/mobile/Containers/Bundle/Application/62100E33-A177-4EBB-849B-539BC11D8324/ThaliTest.app/www/index.html
,2015-12-02 12:39:24.323 ThaliTest[1758:2800189] JXcore Cordova plugin initializing
,2015-12-02 12:39:24.324 ThaliTest[1758:2800406] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2015-12-02 12:39:24.423 ThaliTest[1758:2800406] Error!: Cannot find module '../server-address.js'
Stack:[{"_fileName":"module.js","_functionName":"Module._oldRes","_lineNumber":"776","_columnNumber":"15","_msg":"    at Module._oldRes@module.js:776:15"},{",_fileName":"module.js","_functionName":"Module._resolveFilename","_lineNumber":"1608","_columnNumber":"1","_msg":"    at Module._resolveFilename@module.js:1608:1"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"337","_columnNumber":,"18","_msg":"    at Module._load@module.js:337:18"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionN,ame":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/62100E33-A177-4EBB-849B-539BC11D8324/ThaliTest.app/www/jxcore/app.js","_functionName":"","_lin,eNumber":"11","_columnNumber":"21","_msg":"    at @/private/var/mobile/Containers/Bundle/Application/62100E33-A177-4EBB-849B-539BC11D8324/ThaliTest.app/www/jxcore/app.js:11:21"},{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNum,ber":"597","_columnNumber":"10","_msg":"    at Module.prototype._compile@module.js:597:10"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"}]

```
