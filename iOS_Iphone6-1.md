#### Test 54312298c831015_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/54312298c831015/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/3404E181-CE67-450B-81E3-0020F0E6C342/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/3404E181-CE67-450B-81E3-0020F0E6C342/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/54312298c831015/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/54312298c831015/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B7A21D67-DF2E-4DA6-9146-4A4AA34AAD0E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61750"
,(lldb)     command script import "/tmp/3404E181-CE67-450B-81E3-0020F0E6C342/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-21 23:59:31.346 ThaliTest[692:806571] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A3673354-E2E3-4070-ADB5-B76662F62C52/Library/Cookies/Cookies.binarycookies
,2015-12-21 23:59:31.631 ThaliTest[692:806571] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-21 23:59:31.632 ThaliTest[692:806571] Multi-tasking -> Device: YES, App: YES
,2015-12-21 23:59:31.640 ThaliTest[692:806571] Unlimited access to network resources
,2015-12-21 23:59:31.649 ThaliTest[692:806571] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-21 23:59:40.824 ThaliTest[692:806571] Resetting plugins due to page load.
,2015-12-21 23:59:44.201 ThaliTest[692:806571] Finished load of: file:///var/mobile/Containers/Bundle/Application/B7A21D67-DF2E-4DA6-9146-4A4AA34AAD0E/ThaliTest.app/www/index.html
,2015-12-21 23:59:44.384 ThaliTest[692:806571] JXcore Cordova plugin initializing
,2015-12-21 23:59:44.385 ThaliTest[692:806773] JXcore instance initializing
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
,2015-12-21 23:59:45.471 ThaliTest[692:806773] Error!: missing ) after argument list
Stack:[{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber",:"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_funct,ionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@modu,le.js:471:12"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/B7A21D67-DF2E-4DA6-9146-4A4AA34AAD0E/ThaliTest.app/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_columnNumber":",30","_msg":"    at TestFrameworkClient/<@/private/var/mobile/Containers/Bundle/Application/B7A21D67-DF2E-4DA6-9146-4A4AA34AAD0E/ThaliTest.app/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/private/var/mobile/Containers/Bundle/Appli,cation/B7A21D67-DF2E-4DA6-9146-4A4AA34AAD0E/ThaliTest.app/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/private/var/mobile/Containers/Bundl,e/Application/B7A21D67-DF2E-4DA6-9146-4A4AA34AAD0E/ThaliTest.app/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/B7A21D67-DF2E-4DA6-9146-4A4AA34AAD0E/ThaliTest.app/www/jxcore/app.js","_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/private/var/mobile/Containers/Bundle/Application/B7A21D67-DF2E-4DA6-9146-4A4AA34AAD0E/ThaliTest.app/www/jxcore/app.js:74:21"}]
2015-12-21 23:59:45.473 ThaliTest[692:806571] THREAD ,WARNING: ['JXcore'] took '68.070801' ms. Plugin should use a background thread.

```
