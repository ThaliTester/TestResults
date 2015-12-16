#### Test 50650278dbf8a2a_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/50650278dbf8a2a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/23851745-F317-49E1-910F-D9C638AAB5C3/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/23851745-F317-49E1-910F-D9C638AAB5C3/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/50650278dbf8a2a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/50650278dbf8a2a/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E6050FD7-710C-4A22-942F-8C2B158260D5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57944"
,(lldb)     command script import "/tmp/23851745-F317-49E1-910F-D9C638AAB5C3/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-16 01:38:02.254 ThaliTest[214:22823] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FAD419A9-0205-4C05-B1B6-D21AB8C02E8F/Library/Cookies/Cookies.binarycookies
,2015-12-16 01:38:02.593 ThaliTest[214:22823] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-16 01:38:02.594 ThaliTest[214:22823] Multi-tasking -> Device: YES, App: YES
,2015-12-16 01:38:02.602 ThaliTest[214:22823] Unlimited access to network resources
,2015-12-16 01:38:02.610 ThaliTest[214:22823] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.ap,ple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-16 01:38:11.648 ThaliTest[214:22823] Resetting plugins due to page load.
,2015-12-16 01:38:15.411 ThaliTest[214:22823] Finished load of: file:///var/mobile/Containers/Bundle/Application/E6050FD7-710C-4A22-942F-8C2B158260D5/ThaliTest.app/www/index.html
,2015-12-16 01:38:15.578 ThaliTest[214:22823] JXcore Cordova plugin initializing
,2015-12-16 01:38:15.579 ThaliTest[214:23062] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Perf Test app loaded loaded
,check test folder
,found test : ./testFindPeers.js
,found test : ./testSendData.js
,2015-12-16 01:38:16.569 ThaliTest[214:22823] THREAD WARNING: ['JXcore'] took '70.255127' ms. Plugin should use a background thread.
,Connected to the server!
,teardown
,2015-12-16 02:01:36.255 ThaliTest[214:23062] Error!: self.currentTest is undefined
Stack:[{"_fileName":"/private/var/mobile/Containers/Bundle/Application/E6050FD7-710C-4A22-942F-8C2B158260D5/ThaliTest.app/www/jxcore/perf_tests/PerfTestFrameworkClient.js",,"_functionName":"TestFrameworkClient/<","_lineNumber":"159","_columnNumber":"5","_msg":"    at TestFrameworkClient/<@/private/var/mobile/Containers/Bundle/Application/E6050FD7-710C-4A22-942F-8C2B158260D5/ThaliTest.app/www/jxcore/perf_tests/PerfTestFramewor,kClient.js:159:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/E6050FD7-710C-4A22-942F-8C2B158260D5/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit",,"_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/E6050FD7-710C-4A22-942F-8C2B158260D5/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/inde,x.js:134:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/E6050FD7-710C-4A22-942F-8C2B158260D5/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onevent","_lineNumber":"254","_columnN,umber":"5","_msg":"    at Socket.prototype.onevent@/private/var/mobile/Containers/Bundle/Application/E6050FD7-710C-4A22-942F-8C2B158260D5/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:254:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/E6050FD7-710C-4A22-942F-8C2B158260D5/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onpacket","_lineNumber":"212","_columnNumber":"7","_msg":"    at Socket.prototype.onpacket@/,private/var/mobile/Containers/Bundle/Application/E6050FD7-710C-4A22-942F-8C2B158260D5/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:212:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/E6050FD7-710C-4A22-942F-8C2B1,58260D5/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/private/var/mobile/Containers/Bundle/Applicatio,n/E6050FD7-710C-4A22-942F-8C2B158260D5/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/E6050FD7-710C-4A22-942F-8C2B158260D5/ThaliTest.app/ww,w/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/E6050FD,7-710C-4A22-942F-8C2B158260D5/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/E6050FD7-710C-4A22-942F-8C2B158260D5/ThaliTest.app/www/jxco,re/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.ondecoded","_lineNumber":"301","_columnNumber":"3","_msg":"    at Manager.prototype.ondecoded@/private/var/mobile/Containers/Bundle/Application/E6050FD7-710C-4A22-942F-8C2B,158260D5/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:301:3"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/E6050FD7-710C-4A22-942F-8C2B158260D5/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/,component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/private/var/mobile/Containers/Bundle/Application/E6050FD7-710C-4A22-942F-8C2B158260D5/ThaliTest.app/www/jxcore/node_modules,/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/E6050FD7-710C-4A22-942F-8C2B158260D5/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.,js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/E6050FD7-710C-4A22-942F-8C2B158260D5/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:134:7"}]
,Connected to the server!

```
