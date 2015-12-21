#### Test 506502782e2cb10_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502782e2cb10/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/7753119F-6B09-4377-9EE8-45E915F5D6BA/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/7753119F-6B09-4377-9EE8-45E915F5D6BA/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502782e2cb10/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502782e2cb10/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/FDDB04CA-6BED-4923-8CBF-E935F6D03136/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61597"
,(lldb)     command script import "/tmp/7753119F-6B09-4377-9EE8-45E915F5D6BA/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-21 23:11:22.610 ThaliTest[563:904454] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F41FF59B-0D8A-4AE7-90DC-33A960922721/Library/Cookies/Cookies.binarycookies
,2015-12-21 23:11:22.740 ThaliTest[563:904454] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-21 23:11:22.742 ThaliTest[563:904454] Multi-tasking -> Device: YES, App: YES
,2015-12-21 23:11:22.749 ThaliTest[563:904454] Unlimited access to network resources
,2015-12-21 23:11:22.764 ThaliTest[563:904454] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-21 23:11:32.547 ThaliTest[563:904454] Resetting plugins due to page load.
,2015-12-21 23:11:36.596 ThaliTest[563:904454] Finished load of: file:///var/mobile/Containers/Bundle/Application/FDDB04CA-6BED-4923-8CBF-E935F6D03136/ThaliTest.app/www/index.html
,2015-12-21 23:11:36.806 ThaliTest[563:904454] JXcore Cordova plugin initializing
,2015-12-21 23:11:36.808 ThaliTest[563:904665] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Perf Test app loaded loaded
,check test folder
,found test : ./testFindPeers.js
,found test : ./testSendData.js
,found test : ./testSendData2.js
,2015-12-21 23:11:39.226 ThaliTest[563:904665] Error!: missing ) after argument list
Stack:[{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567,:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber",:"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_funct,ionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@modu,le.js:471:12"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/FDDB04CA-6BED-4923-8CBF-E935F6D03136/ThaliTest.app/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_columnNumber":",30","_msg":"    at TestFrameworkClient/<@/private/var/mobile/Containers/Bundle/Application/FDDB04CA-6BED-4923-8CBF-E935F6D03136/ThaliTest.app/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/private/var/mobile/Containers/Bundle/Appli,cation/FDDB04CA-6BED-4923-8CBF-E935F6D03136/ThaliTest.app/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/private/var/mobile/Containers/Bundl,e/Application/FDDB04CA-6BED-4923-8CBF-E935F6D03136/ThaliTest.app/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/FDDB04CA-6BED-4923-8CBF-E935F6D03136/ThaliTest.app/www/jxcore/app.js",,"_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/private/var/mobile/Containers/Bundle/Application/FDDB04CA-6BED-4923-8CBF-E935F6D03136/ThaliTest.app/www/jxcore/app.js:74:21"}]
2015-12-21 23:11:39.228 ThaliTest[563:904454] THREAD, WARNING: ['JXcore'] took '130.869873' ms. Plugin should use a background thread.

```
