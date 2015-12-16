#### Test 50650278e989a4f_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278e989a4f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/A8D1DD55-9578-46E8-809B-8441489914DD/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/A8D1DD55-9578-46E8-809B-8441489914DD/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278e989a4f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278e989a4f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2AA3B74D-7BD7-4A71-8764-064C7D9322D3/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58214"
,(lldb)     command script import "/tmp/A8D1DD55-9578-46E8-809B-8441489914DD/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-16 03:29:09.125 ThaliTest[247:36011] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/AB4B8E87-6FD5-4132-9086-8ADA00654EC4/Library/Cookies/Cookies.binarycookies
,2015-12-16 03:29:09.500 ThaliTest[247:36011] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-16 03:29:09.501 ThaliTest[247:36011] Multi-tasking -> Device: YES, App: YES
,2015-12-16 03:29:09.509 ThaliTest[247:36011] Unlimited access to network resources
,2015-12-16 03:29:09.519 ThaliTest[247:36011] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-16 03:29:18.440 ThaliTest[247:36011] Resetting plugins due to page load.
,2015-12-16 03:29:22.035 ThaliTest[247:36011] Finished load of: file:///var/mobile/Containers/Bundle/Application/2AA3B74D-7BD7-4A71-8764-064C7D9322D3/ThaliTest.app/www/index.html
,2015-12-16 03:29:22.311 ThaliTest[247:36011] JXcore Cordova plugin initializing
,2015-12-16 03:29:22.313 ThaliTest[247:36191] JXcore instance initializing
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
,2015-12-16 03:29:23.646 ThaliTest[247:36011] THREAD WARNING: ['JXcore'] took '90.504150' ms. Plugin should use a background thread.
,Connected to the server!
,teardown
,2015-12-16 03:51:02.282 ThaliTest[247:36191] Error!: self.currentTest is undefined
Stack:[{"_fileName":"/private/var/mobile/Containers/Bundle/Application/2AA3B74D-7BD7-4A71-8764-064C7D9322D3/ThaliTest.app/www/jxcore/perf_tests/PerfTestFrameworkClient.js",,"_functionName":"TestFrameworkClient/<","_lineNumber":"159","_columnNumber":"5","_msg":"    at TestFrameworkClient/<@/private/var/mobile/Containers/Bundle/Application/2AA3B74D-7BD7-4A71-8764-064C7D9322D3/ThaliTest.app/www/jxcore/perf_tests/PerfTestFramewor,kClient.js:159:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/2AA3B74D-7BD7-4A71-8764-064C7D9322D3/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit",,"_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/2AA3B74D-7BD7-4A71-8764-064C7D9322D3/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/inde,x.js:134:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/2AA3B74D-7BD7-4A71-8764-064C7D9322D3/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onevent","_lineNumber":"254","_columnNumber":"5","_msg":"    at Socket.prototype.onevent@/private/var/mobile/Containers/Bundle/Application/2AA3B74D-7BD7-4A71-8764-064C7D9322D3/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:254:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/2AA3B74D-7BD7-4A71-8764-064C7D9322D3/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onpacket","_lineNumber":"212","_columnNumber":"7","_msg":"    at Socket.prototype.onpacket@/,private/var/mobile/Containers/Bundle/Application/2AA3B74D-7BD7-4A71-8764-064C7D9322D3/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:212:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/2AA3B74D-7BD7-4A71-8764-064C7,D9322D3/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/private/var/mobile/Containers/Bundle/Applicatio,n/2AA3B74D-7BD7-4A71-8764-064C7D9322D3/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/2AA3B74D-7BD7-4A71-8764-064C7D9322D3/ThaliTest.app/ww,w/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/2AA3B74,D-7BD7-4A71-8764-064C7D9322D3/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/2AA3B74D-7BD7-4A71-8764-064C7D9322D3/ThaliTest.app/www/jxco,re/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.ondecoded","_lineNumber":"301","_columnNumber":"3","_msg":"    at Manager.prototype.ondecoded@/private/var/mobile/Containers/Bundle/Application/2AA3B74D-7BD7-4A71-8764-064C,7D9322D3/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:301:3"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/2AA3B74D-7BD7-4A71-8764-064C7D9322D3/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/,component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/private/var/mobile/Containers/Bundle/Application/2AA3B74D-7BD7-4A71-8764-064C7D9322D3/ThaliTest.app/www/jxcore/node_modules,/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/2AA3B74D-7BD7-4A71-8764-064C7D9322D3/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.,js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/2AA3B74D-7BD7-4A71-8764-064C7D9322D3/ThaliTest.app/www/jxcore/node_modules/socket.i,o-client/node_modules/component-emitter/index.js:134:7"}]
,Connected to the server!

```
