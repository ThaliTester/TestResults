#### Test 50650278bb431e6_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278bb431e6/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/29E5D83B-5552-4308-B6C0-04D3D186277D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/29E5D83B-5552-4308-B6C0-04D3D186277D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278bb431e6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278bb431e6/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/3A0BF18E-A3A9-4F11-A32C-E5A42F748BC4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61156"
,(lldb)     command script import "/tmp/29E5D83B-5552-4308-B6C0-04D3D186277D/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-21 00:09:17.444 ThaliTest[635:666752] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/69AA546E-260B-4EBC-8619-4656C9B3B958/Library/Cookies/Cookies.binarycookies
,2015-12-21 00:09:17.837 ThaliTest[635:666752] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-21 00:09:17.838 ThaliTest[635:666752] Multi-tasking -> Device: YES, App: YES
,2015-12-21 00:09:17.847 ThaliTest[635:666752] Unlimited access to network resources
,2015-12-21 00:09:17.861 ThaliTest[635:666752] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-21 00:09:25.928 ThaliTest[635:666752] Resetting plugins due to page load.
,2015-12-21 00:09:29.130 ThaliTest[635:666752] Finished load of: file:///var/mobile/Containers/Bundle/Application/3A0BF18E-A3A9-4F11-A32C-E5A42F748BC4/ThaliTest.app/www/index.html
,2015-12-21 00:09:29.349 ThaliTest[635:666752] JXcore Cordova plugin initializing
,2015-12-21 00:09:29.350 ThaliTest[635:667067] JXcore instance initializing
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
,2015-12-21 00:09:30.670 ThaliTest[635:667067] Error!: unlabeled break must be inside loop or switch
Stack:[{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compi,le@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.loa,d","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"mo,dule.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"   , at require@module.js:471:12"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/3A0BF18E-A3A9-4F11-A32C-E5A42F748BC4/ThaliTest.app/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86",",_columnNumber":"30","_msg":"    at TestFrameworkClient/<@/private/var/mobile/Containers/Bundle/Application/3A0BF18E-A3A9-4F11-A32C-E5A42F748BC4/ThaliTest.app/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/private/var/mobile/Contain,ers/Bundle/Application/3A0BF18E-A3A9-4F11-A32C-E5A42F748BC4/ThaliTest.app/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/private/var/mobile/,Containers/Bundle/Application/3A0BF18E-A3A9-4F11-A32C-E5A42F748BC4/ThaliTest.app/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/3A0BF18E-A3A9-4F11-A32C-E5A42F748BC4/ThaliTest.app/www/,jxcore/app.js","_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/private/var/mobile/Containers/Bundle/Application/3A0BF18E-A3A9-4F11-A32C-E5A42F748BC4/ThaliTest.app/www/jxcore/app.js:74:21"}]
2015-12-21 00:09:30.671 ThaliTest[635,:666752] THREAD WARNING: ['JXcore'] took '77.039795' ms. Plugin should use a background thread.

```
