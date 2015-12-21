#### Test 506502781c2754f_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502781c2754f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/73D1ED9C-4320-4964-B6D9-606EF6A6D0B6/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/73D1ED9C-4320-4964-B6D9-606EF6A6D0B6/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502781c2754f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502781c2754f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/0219E23F-10A9-4D6F-8F9C-CC910A31270F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61392"
,(lldb)     command script import "/tmp/73D1ED9C-4320-4964-B6D9-606EF6A6D0B6/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-21 01:31:10.223 ThaliTest[658:677258] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/59356CE4-9F2C-465B-924C-9F022A9BEF73/Library/Cookies/Cookies.binarycookies
,2015-12-21 01:31:10.553 ThaliTest[658:677258] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-21 01:31:10.554 ThaliTest[658:677258] Multi-tasking -> Device: YES, App: YES
,2015-12-21 01:31:10.563 ThaliTest[658:677258] Unlimited access to network resources
,2015-12-21 01:31:10.575 ThaliTest[658:677258] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-21 01:31:19.333 ThaliTest[658:677258] Resetting plugins due to page load.
,2015-12-21 01:31:23.291 ThaliTest[658:677258] Finished load of: file:///var/mobile/Containers/Bundle/Application/0219E23F-10A9-4D6F-8F9C-CC910A31270F/ThaliTest.app/www/index.html
,2015-12-21 01:31:23.570 ThaliTest[658:677258] JXcore Cordova plugin initializing
,2015-12-21 01:31:23.572 ThaliTest[658:677480] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Perf Test app loaded loaded
,check test folder
,found test : ./testFindPeers.js
,found test : ./testSendData.js
,found test : ./testSendData2.js
,2015-12-21 01:31:24.882 ThaliTest[658:677480] Error!: unlabeled break must be inside loop or switch
Stack:[{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.loa,d","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"   , at require@module.js:471:12"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/0219E23F-10A9-4D6F-8F9C-CC910A31270F/ThaliTest.app/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86",",_columnNumber":"30","_msg":"    at TestFrameworkClient/<@/private/var/mobile/Containers/Bundle/Application/0219E23F-10A9-4D6F-8F9C-CC910A31270F/ThaliTest.app/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/private/var/mobile/Contain,ers/Bundle/Application/0219E23F-10A9-4D6F-8F9C-CC910A31270F/ThaliTest.app/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/private/var/mobile/,Containers/Bundle/Application/0219E23F-10A9-4D6F-8F9C-CC910A31270F/ThaliTest.app/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/0219E23F-10A9-4D6F-8F9C-CC910A31270F/ThaliTest.app/www/,jxcore/app.js","_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/private/var/mobile/Containers/Bundle/Application/0219E23F-10A9-4D6F-8F9C-CC910A31270F/ThaliTest.app/www/jxcore/app.js:74:21"}]
2015-12-21 01:31:24.883 ThaliTest[658,:677258] THREAD WARNING: ['JXcore'] took '76.533936' ms. Plugin should use a background thread.

```
