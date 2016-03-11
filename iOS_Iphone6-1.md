#### Test 62509094a319d1d_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/62509094a319d1d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/6314FD9E-CF45-40DE-B402-C56A74E524DE/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/6314FD9E-CF45-40DE-B402-C56A74E524DE/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/62509094a319d1d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/62509094a319d1d/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49318"
,(lldb)     command script import "/tmp/6314FD9E-CF45-40DE-B402-C56A74E524DE/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-03-11 15:35:16.191 ThaliTest[1140:1730661] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C7245AF4-FB41-44BA-B591-9D851AE413A4/Library/Cookies/Cookies.binarycookies
,2016-03-11 15:35:16.573 ThaliTest[1140:1730661] Apache Cordova native platform version 4.0.1 is starting.
,2016-03-11 15:35:16.575 ThaliTest[1140:1730661] Multi-tasking -> Device: YES, App: YES
,2016-03-11 15:35:16.603 ThaliTest[1140:1730661] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-03-11 15:35:18.388 ThaliTest[1140:1730661] Using UIWebView
,2016-03-11 15:35:18.395 ThaliTest[1140:1730661] [CDVTimer][handleopenurl] 0.438035ms
,2016-03-11 15:35:18.403 ThaliTest[1140:1730661] [CDVTimer][intentandnavigationfilter] 7.296026ms
2016-03-11 15:35:18.404 ThaliTest[1140:1730661] [CDVTimer][gesturehandler] 0.385046ms
2016-03-11 15:35:18.404 ThaliTest[1140:1730661] [CDVTimer][TotalPluginStartup] 9.872019ms
,2016-03-11 15:35:24.614 ThaliTest[1140:1730661] Resetting plugins due to page load.
,2016-03-11 15:35:27.645 ThaliTest[1140:1730661] Finished load of: file:///var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/index.html
,2016-03-11 15:35:27.870 ThaliTest[1140:1730661] JXcore Cordova plugin initializing
,2016-03-11 15:35:27.871 ThaliTest[1140:1730874] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,INFO testUtils Toggling radios to: true
,Unit Test app is loaded
,My device name is: Apple-Iphone6-1
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/bv_tests/testTests.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js
,2016-03-11 15:35:38.244 ThaliTest[1140:1730874] jxcore: didRegisterToNative peerAvailabilityChanged
2016-03-11 15:35:38.244 ThaliTest[1140:1730874] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-03-11 15:35:38.244 ThaliTest[1140:1730874] jxcore: didRegisterToNative networkChanged
,INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-03-11 15:35:38.246 ThaliTest[1140:1730874] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
,Reconnected to the test server
,TAP version 13
,# setup
,# 1. closeAll can close even when connections open
,# teardown
,ok 1 not possible to connect to the server anymore
,# setup
,# 2. closeAll with promise
,# teardown
,ok 2 not possible to connect to the server anymore
,# setup
,# 3. multiplex can send data
,# teardown
,ok 3 String should be length:200
,# setup
,# 4. enqueue and run in order
,# teardown
,ok 4 firstPromise setTimeout
,ok 5 firstPromise result
,ok 6 firstPromise testValue
,ok 7 secondPromise setTimeout
,ok 8 secondPromise result
,ok 9 secondPromise testValue
,ok 10 thirdPromise in promise
,ok 11 thirdPromise result
,ok 12 thirdPromise testValue
,# setup
,# 5. enqueueAtTop and run backwards
,# teardown
,ok 13 thirdPromise - first to run
,ok 14 thirdPromise - in resolve
,ok 15 secondPromise - second to run
,ok 16 secondPromise - in catch
,ok 17 firstPromise - third to run
,ok 18 firstPromise - in then
,ok 19 testing promises
,# setup
,# 6. mix enqueue and enqueueAtTop
,# teardown
,ok 20 fourth
,ok 21 fourth
,ok 22 second
,ok 23 secondPromise - in then
,ok 24 first
,ok 25 firstPromise - in catch
,ok 26 third
,ok 27 thirdPromise - in then
,ok 28 testingPromises
,# setup
,# 7. queues handled independently
,# teardown
,ok 29 all short operations completed before the long resolves
,# setup
,# 8. basic
,# teardown
,ok 30 sane
,# setup
,# 9. another
,# teardown
,ok 31 sane
,# setup
,# 10. #startListeningForAdvertisements should fail if start not called
,# teardown
,ok 32 specific error should be returned
,# setup
,ok 33 error should be null
,ok 34 error should be null
,# 11. #startUpdateAdvertisingAndListening should fail if start not called
,# teardown
,ok 35 specific error should be returned
,# setup
,ok 36 error should be null
,ok 37 error should be null
,# 12. should be able to call #stopListeningForAdvertisements many times
,# teardown
,ok 38 error should be null
,ok 39 error should be null
,ok 40 error should be null
,ok 41 error should be null
,# setup
,ok 42 error should be null
,ok 43 error should be null
,# 13. should be able to call #startListeningForAdvertisements many times
,# teardown
,ok 44 error should be null
,ok 45 error should be null
,ok 46 error should be null
,ok 47 error should be null
,# setup
,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 48 error should be null
,ok 49 error should be null
,# 14. should be able to call #startUpdateAdvertisingAndListening many times
,# teardown
,ok 50 error should be null
,ok 51 error should be null
,ok 52 error should be null
,ok 53 error should be null
,# setup
,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 54 error should be null
,ok 55 error should be null
,# 15. should be able to call #stopAdvertisingAndListening many times
,# teardown
,ok 56 error should be null
,ok 57 error should be null
,ok 58 error should be null
,ok 59 error should be null
,# setup
,ok 60 error should be null
,ok 61 error should be null
,# 16. #start should fail if called twice in a row
,# teardown
,ok 62 first call should succeed
,ok 63 first call should succeed
,ok 64 specific error should be returned
,# setup
,ok 65 error should be null
,ok 66 error should be null
,# 17. does not emit duplicate discoveryAdvertisingStateUpdate
,# teardown
,ok 67 called only once
,ok 68 discovery state matches
,ok 69 advertising state matches
,# setup
,INFO thaliMobile Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 70 error should be null
,ok 71 error should be null
,# 18. does not send duplicate availability changes
,# teardown
,ok 72 should be called once
,ok 73 should not have been called more than once
,# setup
,ok 74 error should be null
,ok 75 error should be null
,# 19. can get the network status
,# teardown
,ok 76 network status should have certain non-empty properties
,# setup
,ok 77 error should be null
,ok 78 error should be null
,# 20. wifi peer is marked unavailable if announcements stop
,# teardown
,ok 79 host address should match
,ok 80 port should match
,ok 81 host address should be null
,ok 82 port should should be null
,# setup
,INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,ok 83 error should be null
,ok 84 error should be null
,# 21. can get the network status before starting
,# teardown
,ok 85 network status should have certain non-empty properties
,# setup
,# 22. #generatePreambleAndBeacons bad args
,# teardown
,2016-03-11 15:39:10.441 ThaliTest[1140:1730874] Error!: crypto.createECDH is not a function
Stack:[{"_fileName":"/private/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification,Beacons.js","_functionName":"","_lineNumber":"35","_columnNumber":"21","_msg":"    at @/private/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js:35:21"},{"_fileN,ame":"/private/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/lib/thali-tape.js","_functionName":"declareTest/</<","_lineNumber":"91","_columnNumber":"7","_msg":"    at declareTest/</<@/private/var/mo,bile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/lib/thali-tape.js:91:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/node_mod,ules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"on","_lineNumber":"63","_columnNumber":"5","_msg":"    at on@/private/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/nod,e_modules/socket.io-client/node_modules/component-emitter/index.js:63:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emi,tter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/node_modul,es/socket.io-client/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":",Socket.prototype.onevent","_lineNumber":"263","_columnNumber":"5","_msg":"    at Socket.prototype.onevent@/private/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/sock,et.js:263:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onpacket","_lineNumber":"221","_colum,nNumber":"7","_msg":"    at Socket.prototype.onpacket@/private/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:221:7"},{"_fileName":"/private/var/mobile/Cont,ainers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exp,orts/<@/private/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/private/var/mobile/Containers/Bundle/Applicatio,n/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/p,rivate/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/F08B,CD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.ondecoded","_lineNumber":"333","_columnNumber":"3","_msg":"    at Manager.prototype.ondecoded@/private/var/mobile/Co,ntainers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:333:3"}]
Uncaught Exception: TypeError: crypto.createECDH is not a function
,[ { _fileName: '/private/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js',
    _functionName: '',
    _lineNumber: '35',
    _columnNumber: '21',
    _msg: ,'    at @/private/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js:35:21' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC,3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/lib/thali-tape.js',
    _functionName: 'declareTest/</<',
    _lineNumber: '91',
    _columnNumber: '7',
    _msg: '    at declareTest/</<@/private/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3,-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/lib/thali-tape.js:91:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emi,tter/index.js',
    _functionName: 'on',
    _lineNumber: '63',
    _columnNumber: '5',
    _msg: '    at on@/private/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/node_modules/socket.io-client/n,ode_modules/component-emitter/index.js:63:5' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js',
    _f,unctionName: 'Emitter.prototype.emit',
    _lineNumber: '131',
    _columnNumber: '7',
    _msg: '    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/node_modules/,socket.io-client/node_modules/component-emitter/index.js:131:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js',
    _function,Name: 'Socket.prototype.onevent',
    _lineNumber: '263',
    _columnNumber: '5',
    _msg: '    at Socket.prototype.onevent@/private/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/node_modules/soc,ket.io-client/lib/socket.js:263:5' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js',
    _functionName: 'Socket.prototype.onpac,ket',
    _lineNumber: '221',
    _columnNumber: '7',
    _msg: '    at Socket.prototype.onpacket@/private/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js,:221:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js',
    _functionName: 'module.exports/<',
    _l,ineNumber: '21',
    _columnNumber: '12',
    _msg: '    at module.exports/<@/private/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.j,s:21:12' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js',
    _functionName: 'Emitter.prototype.emit,',
    _lineNumber: '131',
    _columnNumber: '7',
    _msg: '    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/node_modules/socket.io-client/node_modules/compon,ent-emitter/index.js:131:7' },
  { _fileName: '/private/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js',
    _functionName: 'Manager.prototype.ondecoded',,
    _lineNumber: '333',
    _columnNumber: '3',
    _msg: '    at Manager.prototype.ondecoded@/private/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:,333:3' },
  toString: [Function] ]
****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
TypeError: crypto.createECDH is not a function (/private/var/mobile/Containers/Bundle/Application/F08BCD63-A696-4EC3-AB49-113ABE8A3AB4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js 35:20)


```
