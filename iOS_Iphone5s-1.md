#### Test 5065027873d6a28_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5065027873d6a28/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/D202C9A9-AFE4-4B24-A6D2-EEB2FC4F7315/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/D202C9A9-AFE4-4B24-A6D2-EEB2FC4F7315/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5065027873d6a28/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5065027873d6a28/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/70E0DB6F-1622-4D23-932F-63B324BFB4D3/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51790"
,(lldb)     command script import "/tmp/D202C9A9-AFE4-4B24-A6D2-EEB2FC4F7315/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-09 03:01:52.523 ThaliTest[554:360459] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E1F5AC89-B2B3-4AA2-91AB-FE1B63D2FF71/Library/Cookies/Cookies.binarycookies
,2015-12-09 03:01:52.967 ThaliTest[554:360459] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-09 03:01:52.969 ThaliTest[554:360459] Multi-tasking -> Device: YES, App: YES
,2015-12-09 03:01:52.979 ThaliTest[554:360459] Unlimited access to network resources
,2015-12-09 03:01:52.994 ThaliTest[554:360459] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-09 03:02:02.247 ThaliTest[554:360459] Resetting plugins due to page load.
,2015-12-09 03:02:06.127 ThaliTest[554:360459] Finished load of: file:///var/mobile/Containers/Bundle/Application/70E0DB6F-1622-4D23-932F-63B324BFB4D3/ThaliTest.app/www/index.html
,2015-12-09 03:02:06.337 ThaliTest[554:360459] JXcore Cordova plugin initializing
,2015-12-09 03:02:06.339 ThaliTest[554:360676] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2015-12-09 03:02:06.470 ThaliTest[554:360676] Error!: missing ) after argument list
Stack:[{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber",:"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_funct,ionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@modul,e.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"280","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:280:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNu,mber":"300","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:300:7"},{"_fileName":"eval","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @eval:1:1"}]

```
