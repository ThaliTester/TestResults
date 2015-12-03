#### Test 506502788a86afe_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502788a86afe/build_ios/ThaliTest.app
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
,(lldb) command source -s 0 '/tmp/CFF19C2E-7D9D-4D23-8B1C-B4BC9E3D2560/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/CFF19C2E-7D9D-4D23-8B1C-B4BC9E3D2560/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/7.1.2 (11D257)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502788a86afe/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502788a86afe/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Applications/D18ACDC0-03E0-480A-865A-ED552C21335F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60898"
,(lldb)     command script import "/tmp/CFF19C2E-7D9D-4D23-8B1C-B4BC9E3D2560/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-03 18:52:44.046 ThaliTest[1260:60b] Apache Cordova native platform version 3.9.2 is starting.
2015-12-03 18:52:44.049 ThaliTest[1260:60b] Multi-tasking -> Device: YES, App: YES
,2015-12-03 18:52:44.054 ThaliTest[1260:60b] Unlimited access to network resources
2015-12-03 18:52:44.062 ThaliTest[1260:60b] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For mo,re information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-03 18:52:53.820 ThaliTest[1260:60b] Resetting plugins due to page load.
,2015-12-03 18:52:54.609 ThaliTest[1260:60b] Finished load of: file:///var/mobile/Applications/D18ACDC0-03E0-480A-865A-ED552C21335F/ThaliTest.app/www/index.html
,2015-12-03 18:52:54.792 ThaliTest[1260:60b] JXcore Cordova plugin initializing
,2015-12-03 18:52:54.795 ThaliTest[1260:6907] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2015-12-03 18:53:08.232 ThaliTest[1260:6907] Error!: parsedJSON is not defined
Stack:[{"_fileName":"/private/var/mobile/Applications/D18ACDC0-03E0-480A-865A-ED552C21335F/ThaliTest.app/www/jxcore/lib/thali-tape.js","_functionName":"getCoordinator","_lineNu,mber":"62","_columnNumber":"3","_msg":"    at getCoordinator@/private/var/mobile/Applications/D18ACDC0-03E0-480A-865A-ED552C21335F/ThaliTest.app/www/jxcore/lib/thali-tape.js:62:3"},{"_fileName":"/private/var/mobile/Applications/D18ACDC0-03E0-480A-865A-ED55,2C21335F/ThaliTest.app/www/jxcore/lib/thali-tape.js","_functionName":"thaliTape.begin","_lineNumber":"205","_columnNumber":"3","_msg":"    at thaliTape.begin@/private/var/mobile/Applications/D18ACDC0-03E0-480A-865A-ED552C21335F/ThaliTest.app/www/jxcore/lib,/thali-tape.js:205:3"},{"_fileName":"/private/var/mobile/Applications/D18ACDC0-03E0-480A-865A-ED552C21335F/ThaliTest.app/www/jxcore/runTests.js","_functionName":"","_lineNumber":"17","_columnNumber":"1","_msg":"    at @/private/var/mobile/Applications/D18A,CDC0-03E0-480A-865A-ED552C21335F/ThaliTest.app/www/jxcore/runTests.js:17:1"},{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"597","_columnNumber":"10","_msg":"    at Module.prototype._compile@module.js:597:10"},{"_fileNa,me":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_column,Number":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Modul,e.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{,"_fileName":"/private/var/mobile/Applications/D18ACDC0-03E0-480A-865A-ED552C21335F/ThaliTest.app/www/jxcore/app.js","_functionName":"","_lineNumber":"16","_columnNumber":"1","_msg":"    at @/private/var/mobile/Applications/D18ACDC0-03E0-480A-865A-ED552C213,35F/ThaliTest.app/www/jxcore/app.js:16:1"},{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"597","_columnNumber":"10","_msg":"    at Module.prototype._compile@module.js:597:10"},{"_fileName":"module.js","_functionName":"M,odule._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.,prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber",:"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionNa,me":"internal_methods.loadMainFile","_lineNumber":"280","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:280:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"300","_columnNumber":"7","_msg":"    at JX,Mobile.executeJSON@main.js:300:7"},{"_fileName":"eval","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @eval:1:1"},{"_fileName":"/private/var/mobile/Applications/D18ACDC0-03E0-480A-865A-ED552C21335F/ThaliTest.app/www/jxcore/lib/thali-tape.js","_functionName":"unknown","_lineNumber":62,"_columnNumber":2,"_msg":"    at "}]

```
