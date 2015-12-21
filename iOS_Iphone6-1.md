#### Test 506502782e2cb10_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502782e2cb10/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/01C1926F-7888-4B30-9946-1201E40D0235/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/01C1926F-7888-4B30-9946-1201E40D0235/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502782e2cb10/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502782e2cb10/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/72305B04-A223-4C4A-8455-666A1F659D16/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61631"
,(lldb)     command script import "/tmp/01C1926F-7888-4B30-9946-1201E40D0235/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-21 23:12:43.287 ThaliTest[682:800557] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/ACFBCFC7-625A-4BE9-A383-B1590946A104/Library/Cookies/Cookies.binarycookies
,2015-12-21 23:12:43.698 ThaliTest[682:800557] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-21 23:12:43.699 ThaliTest[682:800557] Multi-tasking -> Device: YES, App: YES
,2015-12-21 23:12:43.710 ThaliTest[682:800557] Unlimited access to network resources
,2015-12-21 23:12:43.725 ThaliTest[682:800557] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-21 23:12:53.014 ThaliTest[682:800557] Resetting plugins due to page load.
,2015-12-21 23:12:56.438 ThaliTest[682:800557] Finished load of: file:///var/mobile/Containers/Bundle/Application/72305B04-A223-4C4A-8455-666A1F659D16/ThaliTest.app/www/index.html
,2015-12-21 23:12:56.621 ThaliTest[682:800557] JXcore Cordova plugin initializing
,2015-12-21 23:12:56.622 ThaliTest[682:800788] JXcore instance initializing
,Initializing JXcore engine
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
,2015-12-21 23:12:57.697 ThaliTest[682:800788] Error!: missing ) after argument list
Stack:[{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567,:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber",:"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_funct,ionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@modu,le.js:471:12"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/72305B04-A223-4C4A-8455-666A1F659D16/ThaliTest.app/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_columnNumber":",30","_msg":"    at TestFrameworkClient/<@/private/var/mobile/Containers/Bundle/Application/72305B04-A223-4C4A-8455-666A1F659D16/ThaliTest.app/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/private/var/mobile/Containers/Bundle/Appli,cation/72305B04-A223-4C4A-8455-666A1F659D16/ThaliTest.app/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/private/var/mobile/Containers/Bundl,e/Application/72305B04-A223-4C4A-8455-666A1F659D16/ThaliTest.app/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/72305B04-A223-4C4A-8455-666A1F659D16/ThaliTest.app/www/jxcore/app.js",,"_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/private/var/mobile/Containers/Bundle/Application/72305B04-A223-4C4A-8455-666A1F659D16/ThaliTest.app/www/jxcore/app.js:74:21"}]
2015-12-21 23:12:57.698 ThaliTest[682:800557] THREAD WARNING: ['JXcore'] took '67.104248' ms. Plugin should use a background thread.

```
