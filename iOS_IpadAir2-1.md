#### Test 543122980a88295_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/543122980a88295/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/E87467B4-34BC-45B6-9F64-BFF0F67FE366/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/E87467B4-34BC-45B6-9F64-BFF0F67FE366/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/543122980a88295/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/543122980a88295/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4560FAFA-D92B-48E8-AAC7-CB8BC6EE387D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62270"
,(lldb)     command script import "/tmp/E87467B4-34BC-45B6-9F64-BFF0F67FE366/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2015-12-23 02:25:06.074 ThaliTest[747:977649] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B97BF511-40D3-4B9F-9AFD-0D0ABE16E21B/Library/Cookies/Cookies.binarycookies
,2015-12-23 02:25:06.435 ThaliTest[747:977649] Apache Cordova native platform version 3.9.2 is starting.
,2015-12-23 02:25:06.436 ThaliTest[747:977649] Multi-tasking -> Device: YES, App: YES
,2015-12-23 02:25:06.445 ThaliTest[747:977649] Unlimited access to network resources
,2015-12-23 02:25:06.454 ThaliTest[747:977649] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2015-12-23 02:25:15.769 ThaliTest[747:977649] Resetting plugins due to page load.
,2015-12-23 02:25:19.450 ThaliTest[747:977649] Finished load of: file:///var/mobile/Containers/Bundle/Application/4560FAFA-D92B-48E8-AAC7-CB8BC6EE387D/ThaliTest.app/www/index.html
,2015-12-23 02:25:19.612 ThaliTest[747:977649] JXcore Cordova plugin initializing
,2015-12-23 02:25:19.613 ThaliTest[747:977917] JXcore instance initializing
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
,2015-12-23 02:25:20.600 ThaliTest[747:977649] THREAD WARNING: ['JXcore'] took '70.726074' ms. Plugin should use a background thread.
,Connected to the server!
,--- start :testSendData2.js---
,2015-12-23 02:30:25.984 ThaliTest[747:977917] Error!: self.tests[testData.testName] is not a constructor
Stack:[{"_fileName":"/private/var/mobile/Containers/Bundle/Application/4560FAFA-D92B-48E8-AAC7-CB8BC6EE387D/ThaliTest.app/www/jxcore/perf_tests/PerfTe,stFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"146","_columnNumber":"24","_msg":"    at TestFrameworkClient/<@/private/var/mobile/Containers/Bundle/Application/4560FAFA-D92B-48E8-AAC7-CB8BC6EE387D/ThaliTest.app/www/jxcore/perf,_tests/PerfTestFrameworkClient.js:146:24"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/4560FAFA-D92B-48E8-AAC7-CB8BC6EE387D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":,"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/4560FAFA-D92B-48E8-AAC7-CB8BC6EE387D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_module,s/component-emitter/index.js:134:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/4560FAFA-D92B-48E8-AAC7-CB8BC6EE387D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onevent","_lin,eNumber":"254","_columnNumber":"5","_msg":"    at Socket.prototype.onevent@/private/var/mobile/Containers/Bundle/Application/4560FAFA-D92B-48E8-AAC7-CB8BC6EE387D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:254:5"},{"_fileName":"/pr,ivate/var/mobile/Containers/Bundle/Application/4560FAFA-D92B-48E8-AAC7-CB8BC6EE387D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onpacket","_lineNumber":"212","_columnNumber":"7","_msg":"    at Soc,ket.prototype.onpacket@/private/var/mobile/Containers/Bundle/Application/4560FAFA-D92B-48E8-AAC7-CB8BC6EE387D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:212:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/4560F,AFA-D92B-48E8-AAC7-CB8BC6EE387D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/private/var/mobile/Cont,ainers/Bundle/Application/4560FAFA-D92B-48E8-AAC7-CB8BC6EE387D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/4560FAFA-D92B-48E8-AAC7-CB8BC,6EE387D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bu,ndle/Application/4560FAFA-D92B-48E8-AAC7-CB8BC6EE387D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/4560FAFA-D92B-48E8-AAC7-CB8BC6EE387,D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.ondecoded","_lineNumber":"301","_columnNumber":"3","_msg":"    at Manager.prototype.ondecoded@/private/var/mobile/Containers/Bundle/Application/4560,FAFA-D92B-48E8-AAC7-CB8BC6EE387D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:301:3"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/4560FAFA-D92B-48E8-AAC7-CB8BC6EE387D/ThaliTest.app/www/jxcore/node_modules/socket,.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/private/var/mobile/Containers/Bundle/Application/4560FAFA-D92B-48E8-AAC7-CB8BC6EE387D/ThaliTest.app,/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/4560FAFA-D92B-48E8-AAC7-CB8BC6EE387D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/,component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/4560FAFA-D92B-48E8-AAC7-CB8BC6EE387D/ThaliTest.app/www/jxco,re/node_modules/socket.io-client/node_modules/component-emitter/index.js:134:7"}]
,Connected to the server!
,teardown
,2015-12-23 02:32:25.930 ThaliTest[747:977917] Error!: self.currentTest is undefined
Stack:[{"_fileName":"/private/var/mobile/Containers/Bundle/Application/4560FAFA-D92B-48E8-AAC7-CB8BC6EE387D/ThaliTest.app/www/jxcore/perf_tests/PerfTestFrameworkClient.js",,"_functionName":"TestFrameworkClient/<","_lineNumber":"159","_columnNumber":"5","_msg":"    at TestFrameworkClient/<@/private/var/mobile/Containers/Bundle/Application/4560FAFA-D92B-48E8-AAC7-CB8BC6EE387D/ThaliTest.app/www/jxcore/perf_tests/PerfTestFramewo,rkClient.js:159:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/4560FAFA-D92B-48E8-AAC7-CB8BC6EE387D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit,","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/4560FAFA-D92B-48E8-AAC7-CB8BC6EE387D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/ind,ex.js:134:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/4560FAFA-D92B-48E8-AAC7-CB8BC6EE387D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onevent","_lineNumber":"254","_column,Number":"5","_msg":"    at Socket.prototype.onevent@/private/var/mobile/Containers/Bundle/Application/4560FAFA-D92B-48E8-AAC7-CB8BC6EE387D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:254:5"},{"_fileName":"/private/var/mobile/Contai,ners/Bundle/Application/4560FAFA-D92B-48E8-AAC7-CB8BC6EE387D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onpacket","_lineNumber":"212","_columnNumber":"7","_msg":"    at Socket.prototype.onpacket@,/private/var/mobile/Containers/Bundle/Application/4560FAFA-D92B-48E8-AAC7-CB8BC6EE387D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:212:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/4560FAFA-D92B-48E8-AAC7-CB8B,C6EE387D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/private/var/mobile/Containers/Bundle/Applicati,on/4560FAFA-D92B-48E8-AAC7-CB8BC6EE387D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/4560FAFA-D92B-48E8-AAC7-CB8BC6EE387D/ThaliTest.app/w,ww/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/4560FA,FA-D92B-48E8-AAC7-CB8BC6EE387D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/4560FAFA-D92B-48E8-AAC7-CB8BC6EE387D/ThaliTest.app/www/jxc,ore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.ondecoded","_lineNumber":"301","_columnNumber":"3","_msg":"    at Manager.prototype.ondecoded@/private/var/mobile/Containers/Bundle/Application/4560FAFA-D92B-48E8-AAC7-CB8,BC6EE387D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:301:3"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/4560FAFA-D92B-48E8-AAC7-CB8BC6EE387D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/private/var/mobile/Containers/Bundle/Application/4560FAFA-D92B-48E8-AAC7-CB8BC6EE387D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/4560FAFA-D92B-48E8-AAC7-CB8BC6EE387D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index,.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/4560FAFA-D92B-48E8-AAC7-CB8BC6EE387D/ThaliTest.app/www/jxcore/node_modules/socket.,io-client/node_modules/component-emitter/index.js:134:7"}]
,Connected to the server!

```
