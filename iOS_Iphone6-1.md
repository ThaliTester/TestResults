#### Test 88496963b27c91e_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/88496963b27c91e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/44E8324F-24DB-43C5-91EA-4F1D35CE237D/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/44E8324F-24DB-43C5-91EA-4F1D35CE237D/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/88496963b27c91e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/88496963b27c91e/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54764"
,(lldb)     command script import "/tmp/44E8324F-24DB-43C5-91EA-4F1D35CE237D/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-18 03:13:43.151 ThaliTest[2376:5013066] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/10B254B9-EE3A-4302-B490-613879F5A61A/Library/Cookies/Cookies.binarycookies
,2016-10-18 03:13:43.189 ThaliTest[2376:5013066] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-18 03:13:43.190 ThaliTest[2376:5013066] Multi-tasking -> Device: YES, App: YES
,2016-10-18 03:13:43.202 ThaliTest[2376:5013066] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-18 03:13:43.489 ThaliTest[2376:5013066] Using UIWebView
,2016-10-18 03:13:43.493 ThaliTest[2376:5013066] [CDVTimer][handleopenurl] 0.162005ms
,2016-10-18 03:13:43.497 ThaliTest[2376:5013066] [CDVTimer][intentandnavigationfilter] 4.614949ms
2016-10-18 03:13:43.498 ThaliTest[2376:5013066] [CDVTimer][gesturehandler] 0.165999ms
2016-10-18 03:13:43.498 ThaliTest[2376:5013066] [CDVTimer][TotalPluginStartup] 5.903959ms
,2016-10-18 03:13:48.475 ThaliTest[2376:5013066] Resetting plugins due to page load.
,2016-10-18 03:13:48.828 ThaliTest[2376:5013066] Finished load of: file:///var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/index.html
,2016-10-18 03:13:49.159 ThaliTest[2376:5013066] JXcore Cordova plugin initializing
,2016-10-18 03:13:49.160 ThaliTest[2376:5013233] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-18 01:13:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-18 01:13:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-18 01:13:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-10-18 01:13:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-18 01:13:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,XCTAssertNil failed: "ConnectionFailed" -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/TCPListenerTests.swift"), line: 321
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,2016-10-18 01:14:25 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  104
,Number of passed tests:  100
,Number of failed tests:  4
,Number of ignored tests:  0
,Total duration:  25.56661802530289
,Failed to execute UT.
,2016-10-18 01:14:25 - DEBUG UnitTest_app: 'Failed to execute UT.'
,2016-10-18 01:14:25 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,2016-10-18 01:14:26 - DEBUG UnitTest_app: 'My device name is: Apple-Iphone6-1'
2016-10-18 01:14:26 - WARN testUtils: 'myNameCallback not set!'
2016-10-18 01:14:26 - DEBUG UnitTest_app: 'Running for NATIVE network type'
,2016-10-18 01:14:28 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2016-10-18 01:14:28 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2016-10-18 01:14:28 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2016-10-18 01:14:29 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2016-10-18 01:14:29 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2016-10-18 01:14:29 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2016-10-18 01:14:29 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2016-10-18 01:14:30 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2016-10-18 01:14:30 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2016-10-18 01:14:30 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2016-10-18 01:14:30 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2016-10-18 01:14:30 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2016-10-18 01:14:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2016-10-18 01:14:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2016-10-18 01:14:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2016-10-18 01:14:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2016-10-18 01:14:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2016-10-18 01:14:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2016-10-18 01:14:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2016-10-18 01:14:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2016-10-18 01:14:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2016-10-18 01:14:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2016-10-18 01:14:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2016-10-18 01:14:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2016-10-18 01:14:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2016-10-18 01:14:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2016-10-18 01:14:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2016-10-18 01:14:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2016-10-18 01:14:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2016-10-18 01:14:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2016-10-18 01:14:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2016-10-18 01:14:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2016-10-18 01:14:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2016-10-18 01:14:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2016-10-18 01:14:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2016-10-18 01:14:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2016-10-18 01:14:31 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2016-10-18 03:14:31.787 ThaliTest[2376:5013066] THREAD WARNING: ['JXcore'] took '6286.629883' ms. Plugin should use a background thread.
,2016-10-18 01:14:31 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 01:14:31 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-18 01:14:31 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/053A01B6,-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 01:14:32 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/053A01B6,-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-18 01:14:32 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/053A01B6,-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-18 01:14:33 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/053A01B6,-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-18 01:14:33 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 01:14:34 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/053A01B6,-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-18 01:14:34 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/053A01B6,-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-18 01:14:35 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/053A01B6,-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-18 01:14:35 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 01:14:36 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/053A01B6,-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-18 01:14:36 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 01:14:37 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/053A01B6,-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-18 01:14:37 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 01:14:38 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/053A01B6,-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-18 01:14:38 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 01:14:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/053A01B6,-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-18 01:14:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/053A01B6,-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-18 01:14:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/053A01B6,-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-18 01:14:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 01:14:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/053A01B6,-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-18 01:14:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 01:14:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/053A01B6,-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-18 01:14:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 01:14:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/053A01B6,-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-18 01:14:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 01:14:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/053A01B6,-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-18 01:14:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/053A01B6,-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-18 01:14:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/053A01B6,-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-18 03:14:45.781 ThaliTest[2376:5013233] Error!: error is undefined
Stack:[{"_fileName":"/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js","_functionName":"Coordinated,Client.prototype._error","_lineNumber":"220","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:220:1"},{"_,fileName":"/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emi,tter.prototype.emit@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D,1,892A888029/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/private/var/containers/Bundle/Application/053A01B6-F443-4,86C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/mana,ger.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/socket,.io-client/lib/manager.js:81:7"},{"_fileName":"/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumbe,r,":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/private/var/,containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager,.prototype.reconnect/timer</<@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/private/var/containers/Bundle/Application/053A01B6-F,443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/private/var,/,containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www,/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/containers/Bundle/Application/053A01B6-F443-4,86C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules,/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/j,x,core/node_modules/engine.io-client/lib/socket.js:670:3"}]
,2016-10-18 01:14:45 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
    at CoordinatedClient.prototype._error@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892,A888029/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:220:1
    at Emitter.prototype.emit@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7
    at So,cket.prototype.emit@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
    at Manager.prototype.emitAll@/private/var/containers/Bundle/Application/053A,01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
    at Manager.prototype.reconnect@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_mo,dules/socket.io-client/lib/manager.js:507:5
    at Manager.prototype.reconnect/timer</<@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
    at Ma,nager.prototype.connect/errorSub<@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7
    at Emitter.prototype.emit@/private/var/containers/Bundle/Appl,ication/053A01B6-F443-486C-8124-D1892A888029/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7
    at Socket.prototype.onError@/private/var/containers/Bundle/Application/053A01B6-F443-486C-8124-D1892A8880,29/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3''
2016-10-18 01:14:45 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
