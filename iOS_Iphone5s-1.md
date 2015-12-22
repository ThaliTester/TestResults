#### Test 54312298239818e_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/54312298239818e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/B5370F6F-42CF-482F-941F-F1A18F5A0D3B/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/B5370F6F-42CF-482F-941F-F1A18F5A0D3B/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/54312298239818e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/54312298239818e/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A96F6036-11DB-4FB3-8B86-B7E6A9C7CF25/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61890"
,(lldb)     command script import "/tmp/B5370F6F-42CF-482F-941F-F1A18F5A0D3B/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-22 01:08:51.573 ThaliTest[719:808989] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/DCDBF56B-94CB-41AB-90FD-18A6EF2B16DC/Library/Cookies/Cookies.binarycookies
,2015-12-22 01:08:51.963 ThaliTest[719:808989] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-22 01:08:51.964 ThaliTest[719:808989] Multi-tasking -> Device: YES, App: YES
,2015-12-22 01:08:51.974 ThaliTest[719:808989] Unlimited access to network resources
,2015-12-22 01:08:51.987 ThaliTest[719:808989] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-22 01:09:00.426 ThaliTest[719:808989] Resetting plugins due to page load.
,2015-12-22 01:09:03.552 ThaliTest[719:808989] Finished load of: file:///var/mobile/Containers/Bundle/Application/A96F6036-11DB-4FB3-8B86-B7E6A9C7CF25/ThaliTest.app/www/index.html
,2015-12-22 01:09:03.780 ThaliTest[719:808989] JXcore Cordova plugin initializing
,2015-12-22 01:09:03.782 ThaliTest[719:809206] JXcore instance initializing
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
,2015-12-22 01:09:05.069 ThaliTest[719:809206] Error!: missing ) after argument list
Stack:[{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567,:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber",:"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_funct,ionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@modu,le.js:471:12"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/A96F6036-11DB-4FB3-8B86-B7E6A9C7CF25/ThaliTest.app/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_columnNumber":",30","_msg":"    at TestFrameworkClient/<@/private/var/mobile/Containers/Bundle/Application/A96F6036-11DB-4FB3-8B86-B7E6A9C7CF25/ThaliTest.app/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/private/var/mobile/Containers/Bundle/Appli,cation/A96F6036-11DB-4FB3-8B86-B7E6A9C7CF25/ThaliTest.app/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/private/var/mobile/Containers/Bundl,e/Application/A96F6036-11DB-4FB3-8B86-B7E6A9C7CF25/ThaliTest.app/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/A96F6036-11DB-4FB3-8B86-B7E6A9C7CF25/ThaliTest.app/www/jxcore/app.js",",_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/private/var/mobile/Containers/Bundle/Application/A96F6036-11DB-4FB3-8B86-B7E6A9C7CF25/ThaliTest.app/www/jxcore/app.js:74:21"}]
2015-12-22 01:09:05.070 ThaliTest[719:808989] THREAD ,WARNING: ['JXcore'] took '74.311768' ms. Plugin should use a background thread.

```
