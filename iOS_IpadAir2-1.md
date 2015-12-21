#### Test 506502781c2754f_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/506502781c2754f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/84734D19-E732-4A2B-B43E-8CBE8C60BA1F/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/84734D19-E732-4A2B-B43E-8CBE8C60BA1F/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/506502781c2754f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/506502781c2754f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/10621FB8-D9E6-48B5-A6BF-0D0451F7FA2E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61387"
,(lldb)     command script import "/tmp/84734D19-E732-4A2B-B43E-8CBE8C60BA1F/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-21 01:31:07.426 ThaliTest[618:700654] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0FD368A1-92E8-4070-A046-EF970E19A0FF/Library/Cookies/Cookies.binarycookies
,2015-12-21 01:31:07.779 ThaliTest[618:700654] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-21 01:31:07.780 ThaliTest[618:700654] Multi-tasking -> Device: YES, App: YES
,2015-12-21 01:31:07.789 ThaliTest[618:700654] Unlimited access to network resources
,2015-12-21 01:31:07.798 ThaliTest[618:700654] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-21 01:31:16.431 ThaliTest[618:700654] Resetting plugins due to page load.
,2015-12-21 01:31:19.948 ThaliTest[618:700654] Finished load of: file:///var/mobile/Containers/Bundle/Application/10621FB8-D9E6-48B5-A6BF-0D0451F7FA2E/ThaliTest.app/www/index.html
,2015-12-21 01:31:20.102 ThaliTest[618:700654] JXcore Cordova plugin initializing
,2015-12-21 01:31:20.103 ThaliTest[618:700929] JXcore instance initializing
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
,2015-12-21 01:31:21.089 ThaliTest[618:700929] Error!: unlabeled break must be inside loop or switch
Stack:[{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.loa,d","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"mo,dule.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    ,at require@module.js:471:12"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/10621FB8-D9E6-48B5-A6BF-0D0451F7FA2E/ThaliTest.app/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_,columnNumber":"30","_msg":"    at TestFrameworkClient/<@/private/var/mobile/Containers/Bundle/Application/10621FB8-D9E6-48B5-A6BF-0D0451F7FA2E/ThaliTest.app/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/private/var/mobile/Containe,rs/Bundle/Application/10621FB8-D9E6-48B5-A6BF-0D0451F7FA2E/ThaliTest.app/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/private/var/mobile/C,ontainers/Bundle/Application/10621FB8-D9E6-48B5-A6BF-0D0451F7FA2E/ThaliTest.app/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/10621FB8-D9E6-48B5-A6BF-0D0451F7FA2E/ThaliTest.app/www/j,xcore/app.js","_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/private/var/mobile/Containers/Bundle/Application/10621FB8-D9E6-48B5-A6BF-0D0451F7FA2E/ThaliTest.app/www/jxcore/app.js:74:21"}]
2015-12-21 01:31:21.090 ThaliTest[618:,700654] THREAD WARNING: ['JXcore'] took '60.622070' ms. Plugin should use a background thread.

```
