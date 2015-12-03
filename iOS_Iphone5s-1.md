#### Test 506502788a86afe_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502788a86afe/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/050B8A8F-D5CF-4089-B9AE-45F5478154BD/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/050B8A8F-D5CF-4089-B9AE-45F5478154BD/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/8.2 (12D508)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502788a86afe/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502788a86afe/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/56BFC930-966B-451E-BB0D-98F6D7370236/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60899"
,(lldb)     command script import "/tmp/050B8A8F-D5CF-4089-B9AE-45F5478154BD/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-03 18:51:55.334 ThaliTest[2524:2329250] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F9704AB9-80EB-49D3-B7F3-ED92BDB147E6/Library/Cookies/Cookies.binarycookies
,2015-12-03 18:51:55.784 ThaliTest[2524:2329250] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-03 18:51:55.785 ThaliTest[2524:2329250] Multi-tasking -> Device: YES, App: YES
,2015-12-03 18:51:55.794 ThaliTest[2524:2329250] Unlimited access to network resources
,2015-12-03 18:51:55.802 ThaliTest[2524:2329250] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-03 18:51:59.417 ThaliTest[2524:2329250] Resetting plugins due to page load.
,2015-12-03 18:51:59.853 ThaliTest[2524:2329250] Finished load of: file:///private/var/mobile/Containers/Bundle/Application/56BFC930-966B-451E-BB0D-98F6D7370236/ThaliTest.app/www/index.html
,2015-12-03 18:52:00.012 ThaliTest[2524:2329250] JXcore Cordova plugin initializing
,2015-12-03 18:52:00.016 ThaliTest[2524:2329368] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2015-12-03 18:52:07.067 ThaliTest[2524:2329368] Error!: parsedJSON is not defined
Stack:[{"_fileName":"/private/var/mobile/Containers/Bundle/Application/56BFC930-966B-451E-BB0D-98F6D7370236/ThaliTest.app/www/jxcore/lib/thali-tape.js","_functionName":"getC,oordinator","_lineNumber":"62","_columnNumber":"3","_msg":"    at getCoordinator@/private/var/mobile/Containers/Bundle/Application/56BFC930-966B-451E-BB0D-98F6D7370236/ThaliTest.app/www/jxcore/lib/thali-tape.js:62:3"},{"_fileName":"/private/var/mobile/Cont,ainers/Bundle/Application/56BFC930-966B-451E-BB0D-98F6D7370236/ThaliTest.app/www/jxcore/lib/thali-tape.js","_functionName":"thaliTape.begin","_lineNumber":"205","_columnNumber":"3","_msg":"    at thaliTape.begin@/private/var/mobile/Containers/Bundle/Applic,ation/56BFC930-966B-451E-BB0D-98F6D7370236/ThaliTest.app/www/jxcore/lib/thali-tape.js:205:3"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/56BFC930-966B-451E-BB0D-98F6D7370236/ThaliTest.app/www/jxcore/runTests.js","_functionName":"","_li,neNumber":"17","_columnNumber":"1","_msg":"    at @/private/var/mobile/Containers/Bundle/Application/56BFC930-966B-451E-BB0D-98F6D7370236/ThaliTest.app/www/jxcore/runTests.js:17:1"},{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lin,eNumber":"597","_columnNumber":"10","_msg":"    at Module.prototype._compile@module.js:597:10"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module,.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_column,Number":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_fun,ctionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/56BFC930-966B-451E-BB0D-98F6D7370236/ThaliTest.app/www/jxcore/app.js","_functionName":"",,"_lineNumber":"16","_columnNumber":"1","_msg":"    at @/private/var/mobile/Containers/Bundle/Application/56BFC930-966B-451E-BB0D-98F6D7370236/ThaliTest.app/www/jxcore/app.js:16:1"},{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lin,eNumber":"597","_columnNumber":"10","_msg":"    at Module.prototype._compile@module.js:597:10"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module,.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_column,Number":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_fun,ctionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"280","_columnNumber":"5","_msg":"    at internal_methods.loadMainF,ile@main.js:280:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"300","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:300:7"},{"_fileName":"eval","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg,":"    at @eval:1:1"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/56BFC930-966B-451E-BB0D-98F6D7370236/ThaliTest.app/www/jxcore/lib/thali-tape.js","_functionName":"unknown","_lineNumber":62,"_columnNumber":2,"_msg":"    at "}]

```
