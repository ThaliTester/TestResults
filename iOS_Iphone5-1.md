#### Test 543122980a88295_iOS_Iphone5-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/543122980a88295/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/43CA814F-CDDC-40DC-B3A0-A35B6F1FA6F7/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'
,Executing commands in '/tmp/43CA814F-CDDC-40DC-B3A0-A35B6F1FA6F7/fruitstrap-lldb-prep-cmds-17df3859480c382d3b761fa2643dde395ced1bd8'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/543122980a88295/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/543122980a88295/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4B8CA6FF-5908-455A-8C75-B479BC3B58F2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62237"
,(lldb)     command script import "/tmp/43CA814F-CDDC-40DC-B3A0-A35B6F1FA6F7/fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.py"
,(lldb)     command script add -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_17df3859480c382d3b761fa2643dde395ced1bd8.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-23 02:23:40.011 ThaliTest[612:1074950] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F7FB4973-3AF9-41D5-BD81-76F38FC1EDBD/Library/Cookies/Cookies.binarycookies
,2015-12-23 02:23:40.139 ThaliTest[612:1074950] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-23 02:23:40.140 ThaliTest[612:1074950] Multi-tasking -> Device: YES, App: YES
,2015-12-23 02:23:40.145 ThaliTest[612:1074950] Unlimited access to network resources
,2015-12-23 02:23:40.160 ThaliTest[612:1074950] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-23 02:23:50.705 ThaliTest[612:1074950] Resetting plugins due to page load.
,2015-12-23 02:23:54.997 ThaliTest[612:1074950] Finished load of: file:///var/mobile/Containers/Bundle/Application/4B8CA6FF-5908-455A-8C75-B479BC3B58F2/ThaliTest.app/www/index.html
,2015-12-23 02:23:55.209 ThaliTest[612:1074950] JXcore Cordova plugin initializing
,2015-12-23 02:23:55.211 ThaliTest[612:1075131] JXcore instance initializing
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
,found test : ./testSendData2.js
,2015-12-23 02:23:57.691 ThaliTest[612:1074950] THREAD WARNING: ['JXcore'] took '167.565918' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testSendData2.js---
,2015-12-23 02:30:25.687 ThaliTest[612:1075131] Error!: self.tests[testData.testName] is not a constructor
Stack:[{"_fileName":"/private/var/mobile/Containers/Bundle/Application/4B8CA6FF-5908-455A-8C75-B479BC3B58F2/ThaliTest.app/www/jxcore/perf_tests/PerfT,estFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"146","_columnNumber":"24","_msg":"    at TestFrameworkClient/<@/private/var/mobile/Containers/Bundle/Application/4B8CA6FF-5908-455A-8C75-B479BC3B58F2/ThaliTest.app/www/jxcore/per,f_tests/PerfTestFrameworkClient.js:146:24"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/4B8CA6FF-5908-455A-8C75-B479BC3B58F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName",:"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/4B8CA6FF-5908-455A-8C75-B479BC3B58F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modul,es/component-emitter/index.js:134:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/4B8CA6FF-5908-455A-8C75-B479BC3B58F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onevent","_li,neNumber":"254","_columnNumber":"5","_msg":"    at Socket.prototype.onevent@/private/var/mobile/Containers/Bundle/Application/4B8CA6FF-5908-455A-8C75-B479BC3B58F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:254:5"},{"_fileName":"/p,rivate/var/mobile/Containers/Bundle/Application/4B8CA6FF-5908-455A-8C75-B479BC3B58F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onpacket","_lineNumber":"212","_columnNumber":"7","_msg":"    at So,cket.prototype.onpacket@/private/var/mobile/Containers/Bundle/Application/4B8CA6FF-5908-455A-8C75-B479BC3B58F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:212:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/4B8C,A6FF-5908-455A-8C75-B479BC3B58F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/private/var/mobile/Con,tainers/Bundle/Application/4B8CA6FF-5908-455A-8C75-B479BC3B58F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/4B8CA6FF-5908-455A-8C75-B479,BC3B58F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/B,undle/Application/4B8CA6FF-5908-455A-8C75-B479BC3B58F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/4B8CA6FF-5908-455A-8C75-B479BC3B58,F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.ondecoded","_lineNumber":"301","_columnNumber":"3","_msg":"    at Manager.prototype.ondecoded@/private/var/mobile/Containers/Bundle/Application/4B8,CA6FF-5908-455A-8C75-B479BC3B58F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:301:3"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/4B8CA6FF-5908-455A-8C75-B479BC3B58F2/ThaliTest.app/www/jxcore/node_modules/socke,t.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/private/var/mobile/Containers/Bundle/Application/4B8CA6FF-5908-455A-8C75-B479BC3B58F2/ThaliTest.ap,p/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/4B8CA6FF-5908-455A-8C75-B479BC3B58F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules,/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/4B8CA6FF-5908-455A-8C75-B479BC3B58F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:134:7"}]
,Connected to the server!
,teardown
,2015-12-23 02:32:26.290 ThaliTest[612:1075131] Error!: self.currentTest is undefined
Stack:[{"_fileName":"/private/var/mobile/Containers/Bundle/Application/4B8CA6FF-5908-455A-8C75-B479BC3B58F2/ThaliTest.app/www/jxcore/perf_tests/PerfTestFrameworkClient.js,","_functionName":"TestFrameworkClient/<","_lineNumber":"159","_columnNumber":"5","_msg":"    at TestFrameworkClient/<@/private/var/mobile/Containers/Bundle/Application/4B8CA6FF-5908-455A-8C75-B479BC3B58F2/ThaliTest.app/www/jxcore/perf_tests/PerfTestFramew,orkClient.js:159:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/4B8CA6FF-5908-455A-8C75-B479BC3B58F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emi,t","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/4B8CA6FF-5908-455A-8C75-B479BC3B58F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/in,dex.js:134:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/4B8CA6FF-5908-455A-8C75-B479BC3B58F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onevent","_lineNumber":"254","_colum,nNumber":"5","_msg":"    at Socket.prototype.onevent@/private/var/mobile/Containers/Bundle/Application/4B8CA6FF-5908-455A-8C75-B479BC3B58F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:254:5"},{"_fileName":"/private/var/mobile/Conta,iners/Bundle/Application/4B8CA6FF-5908-455A-8C75-B479BC3B58F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onpacket","_lineNumber":"212","_columnNumber":"7","_msg":"    at Socket.prototype.onpacket,@/private/var/mobile/Containers/Bundle/Application/4B8CA6FF-5908-455A-8C75-B479BC3B58F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:212:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/4B8CA6FF-5908-455A-8C75-B47,9BC3B58F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/private/var/mobile/Containers/Bundle/Application/4B8CA6FF-5908-455A-8C75-B479BC3B58F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/4B8CA6FF-5908-455A-8C75-B479BC3B58F2/ThaliTest.app/,www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/4B8CA,6FF-5908-455A-8C75-B479BC3B58F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/4B8CA6FF-5908-455A-8C75-B479BC3B58F2/ThaliTest.app/www/jx,core/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.ondecoded","_lineNumber":"301","_columnNumber":"3","_msg":"    at Manager.prototype.ondecoded@/private/var/mobile/Containers/Bundle/Application/4B8CA6FF-5908-455A-8C75-B4,79BC3B58F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:301:3"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/4B8CA6FF-5908-455A-8C75-B479BC3B58F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_module,s/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/private/var/mobile/Containers/Bundle/Application/4B8CA6FF-5908-455A-8C75-B479BC3B58F2/ThaliTest.app/www/jxcore/node_modul,es/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/4B8CA6FF-5908-455A-8C75-B479BC3B58F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/inde,x.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/4B8CA6FF-5908-455A-8C75-B479BC3B58F2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:134:7"}]
,Connected to the server!

```
