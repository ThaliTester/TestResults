#### Test 543122980a88295_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/543122980a88295/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/796AF06A-A74A-46F1-BCBB-8344DC0D7B8F/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/796AF06A-A74A-46F1-BCBB-8344DC0D7B8F/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/543122980a88295/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/543122980a88295/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/BC90CE1F-C8FD-4E23-8BA6-3AEDCC9FE325/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62274"
,(lldb)     command script import "/tmp/796AF06A-A74A-46F1-BCBB-8344DC0D7B8F/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-23 02:25:12.538 ThaliTest[778:949077] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4AAA085A-D124-468C-93D9-8AAE1F9EFA72/Library/Cookies/Cookies.binarycookies
,2015-12-23 02:25:13.005 ThaliTest[778:949077] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-23 02:25:13.007 ThaliTest[778:949077] Multi-tasking -> Device: YES, App: YES
,2015-12-23 02:25:13.017 ThaliTest[778:949077] Unlimited access to network resources
,2015-12-23 02:25:13.031 ThaliTest[778:949077] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-23 02:25:22.146 ThaliTest[778:949077] Resetting plugins due to page load.
,2015-12-23 02:25:26.142 ThaliTest[778:949077] Finished load of: file:///var/mobile/Containers/Bundle/Application/BC90CE1F-C8FD-4E23-8BA6-3AEDCC9FE325/ThaliTest.app/www/index.html
,2015-12-23 02:25:26.353 ThaliTest[778:949077] JXcore Cordova plugin initializing
2015-12-23 02:25:26.354 ThaliTest[778:949300] JXcore instance initializing
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
,2015-12-23 02:25:27.700 ThaliTest[778:949077] THREAD WARNING: ['JXcore'] took '99.375000' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testSendData2.js---
,2015-12-23 02:30:27.750 ThaliTest[778:949300] Error!: self.tests[testData.testName] is not a constructor
Stack:[{"_fileName":"/private/var/mobile/Containers/Bundle/Application/BC90CE1F-C8FD-4E23-8BA6-3AEDCC9FE325/ThaliTest.app/www/jxcore/perf_tests/PerfTe,stFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"146","_columnNumber":"24","_msg":"    at TestFrameworkClient/<@/private/var/mobile/Containers/Bundle/Application/BC90CE1F-C8FD-4E23-8BA6-3AEDCC9FE325/ThaliTest.app/www/jxcore/perf,_tests/PerfTestFrameworkClient.js:146:24"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/BC90CE1F-C8FD-4E23-8BA6-3AEDCC9FE325/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":,"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/BC90CE1F-C8FD-4E23-8BA6-3AEDCC9FE325/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_module,s/component-emitter/index.js:134:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/BC90CE1F-C8FD-4E23-8BA6-3AEDCC9FE325/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onevent","_lin,eNumber":"254","_columnNumber":"5","_msg":"    at Socket.prototype.onevent@/private/var/mobile/Containers/Bundle/Application/BC90CE1F-C8FD-4E23-8BA6-3AEDCC9FE325/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:254:5"},{"_fileName":"/pr,ivate/var/mobile/Containers/Bundle/Application/BC90CE1F-C8FD-4E23-8BA6-3AEDCC9FE325/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onpacket","_lineNumber":"212","_columnNumber":"7","_msg":"    at Soc,ket.prototype.onpacket@/private/var/mobile/Containers/Bundle/Application/BC90CE1F-C8FD-4E23-8BA6-3AEDCC9FE325/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:212:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/BC90C,E1F-C8FD-4E23-8BA6-3AEDCC9FE325/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/private/var/mobile/Cont,ainers/Bundle/Application/BC90CE1F-C8FD-4E23-8BA6-3AEDCC9FE325/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/BC90CE1F-C8FD-4E23-8BA6-3AEDC,C9FE325/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bu,ndle/Application/BC90CE1F-C8FD-4E23-8BA6-3AEDCC9FE325/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/BC90CE1F-C8FD-4E23-8BA6-3AEDCC9FE32,5/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.ondecoded","_lineNumber":"301","_columnNumber":"3","_msg":"    at Manager.prototype.ondecoded@/private/var/mobile/Containers/Bundle/Application/BC90,CE1F-C8FD-4E23-8BA6-3AEDCC9FE325/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:301:3"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/BC90CE1F-C8FD-4E23-8BA6-3AEDCC9FE325/ThaliTest.app/www/jxcore/node_modules/socket,.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/private/var/mobile/Containers/Bundle/Application/BC90CE1F-C8FD-4E23-8BA6-3AEDCC9FE325/ThaliTest.app,/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/BC90CE1F-C8FD-4E23-8BA6-3AEDCC9FE325/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/,component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/BC90CE1F-C8FD-4E23-8BA6-3AEDCC9FE325/ThaliTest.app/www/jxco,re/node_modules/socket.io-client/node_modules/component-emitter/index.js:134:7"}]
,Connected to the server!
,teardown
,2015-12-23 02:32:27.891 ThaliTest[778:949300] Error!: self.currentTest is undefined
Stack:[{"_fileName":"/private/var/mobile/Containers/Bundle/Application/BC90CE1F-C8FD-4E23-8BA6-3AEDCC9FE325/ThaliTest.app/www/jxcore/perf_tests/PerfTestFrameworkClient.js",,"_functionName":"TestFrameworkClient/<","_lineNumber":"159","_columnNumber":"5","_msg":"    at TestFrameworkClient/<@/private/var/mobile/Containers/Bundle/Application/BC90CE1F-C8FD-4E23-8BA6-3AEDCC9FE325/ThaliTest.app/www/jxcore/perf_tests/PerfTestFramewo,rkClient.js:159:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/BC90CE1F-C8FD-4E23-8BA6-3AEDCC9FE325/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit,","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/BC90CE1F-C8FD-4E23-8BA6-3AEDCC9FE325/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/ind,ex.js:134:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/BC90CE1F-C8FD-4E23-8BA6-3AEDCC9FE325/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onevent","_lineNumber":"254","_column,Number":"5","_msg":"    at Socket.prototype.onevent@/private/var/mobile/Containers/Bundle/Application/BC90CE1F-C8FD-4E23-8BA6-3AEDCC9FE325/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:254:5"},{"_fileName":"/private/var/mobile/Contai,ners/Bundle/Application/BC90CE1F-C8FD-4E23-8BA6-3AEDCC9FE325/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onpacket","_lineNumber":"212","_columnNumber":"7","_msg":"    at Socket.prototype.onpacket@,/private/var/mobile/Containers/Bundle/Application/BC90CE1F-C8FD-4E23-8BA6-3AEDCC9FE325/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:212:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/BC90CE1F-C8FD-4E23-8BA6-3AED,CC9FE325/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/private/var/mobile/Containers/Bundle/Applicati,on/BC90CE1F-C8FD-4E23-8BA6-3AEDCC9FE325/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/BC90CE1F-C8FD-4E23-8BA6-3AEDCC9FE325/ThaliTest.app/w,ww/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/BC90CE1F-C8FD-4E23-8BA6-3AEDCC9FE325/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/BC90CE1F-C8FD-4E23-8BA6-3AEDCC9FE325/ThaliTest.app/www/jxc,ore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.ondecoded","_lineNumber":"301","_columnNumber":"3","_msg":"    at Manager.prototype.ondecoded@/private/var/mobile/Containers/Bundle/Application/BC90CE1F-C8FD-4E23-8BA6-3AE,DCC9FE325/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:301:3"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/BC90CE1F-C8FD-4E23-8BA6-3AEDCC9FE325/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules,/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/private/var/mobile/Containers/Bundle/Application/BC90CE1F-C8FD-4E23-8BA6-3AEDCC9FE325/ThaliTest.app/www/jxcore/node_module,s/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/BC90CE1F-C8FD-4E23-8BA6-3AEDCC9FE325/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index,.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/BC90CE1F-C8FD-4E23-8BA6-3AEDCC9FE325/ThaliTest.app/www/jxcore/node_modules/socket.,io-client/node_modules/component-emitter/index.js:134:7"}]
,Connected to the server!

```
