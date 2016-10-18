#### Test 88496963b27c91e_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/88496963b27c91e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/A4004FC0-3087-4963-ACD0-12426ACA150A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/A4004FC0-3087-4963-ACD0-12426ACA150A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/88496963b27c91e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/88496963b27c91e/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54762"
,(lldb)     command script import "/tmp/A4004FC0-3087-4963-ACD0-12426ACA150A/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-18 03:13:40.956 ThaliTest[4375:10040581] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E7995A22-E8CB-4108-827C-AC24FF07BC81/Library/Cookies/Cookies.binarycookies
,2016-10-18 03:13:41.074 ThaliTest[4375:10040581] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-18 03:13:41.077 ThaliTest[4375:10040581] Multi-tasking -> Device: YES, App: YES
,2016-10-18 03:13:41.095 ThaliTest[4375:10040581] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-18 03:13:42.530 ThaliTest[4375:10040581] Using UIWebView
,2016-10-18 03:13:42.543 ThaliTest[4375:10040581] [CDVTimer][handleopenurl] 0.469029ms
,2016-10-18 03:13:42.554 ThaliTest[4375:10040581] [CDVTimer][intentandnavigationfilter] 10.376990ms
2016-10-18 03:13:42.555 ThaliTest[4375:10040581] [CDVTimer][gesturehandler] 0.418007ms
2016-10-18 03:13:42.555 ThaliTest[4375:10040581] [CDVTimer][TotalPlu,ginStartup] 13.311982ms
,2016-10-18 03:13:48.369 ThaliTest[4375:10040581] Resetting plugins due to page load.
,2016-10-18 03:13:52.123 ThaliTest[4375:10040581] Finished load of: file:///var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/index.html
,2016-10-18 03:13:52.442 ThaliTest[4375:10040581] JXcore Cordova plugin initializing
,2016-10-18 03:13:52.444 ThaliTest[4375:10040805] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-18 01:14:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-18 01:14:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-18 01:14:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-10-18 01:14:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-18 01:14:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,XCTAssertNil failed: "ConnectionFailed" -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/TCPListenerTests.swift"), line: 321
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,2016-10-18 01:14:30 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  104
,Number of passed tests:  100
,Number of failed tests:  4
,Number of ignored tests:  0
,Total duration:  24.66284096240997
,Failed to execute UT.
,2016-10-18 01:14:30 - DEBUG UnitTest_app: 'Failed to execute UT.'
,2016-10-18 01:14:30 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,2016-10-18 01:14:31 - DEBUG UnitTest_app: 'My device name is: Apple-Iphone5s-1'
2016-10-18 01:14:31 - WARN testUtils: 'myNameCallback not set!'
,2016-10-18 01:14:31 - DEBUG UnitTest_app: 'Running for NATIVE network type'
,2016-10-18 01:14:33 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2016-10-18 01:14:34 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2016-10-18 01:14:34 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2016-10-18 01:14:35 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2016-10-18 01:14:35 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2016-10-18 01:14:35 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2016-10-18 01:14:35 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2016-10-18 01:14:36 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2016-10-18 01:14:36 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2016-10-18 01:14:36 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2016-10-18 01:14:36 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2016-10-18 01:14:37 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2016-10-18 01:14:37 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2016-10-18 01:14:37 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2016-10-18 01:14:37 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2016-10-18 01:14:37 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2016-10-18 01:14:37 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2016-10-18 01:14:37 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2016-10-18 01:14:37 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2016-10-18 01:14:37 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2016-10-18 01:14:38 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2016-10-18 01:14:38 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2016-10-18 01:14:38 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2016-10-18 01:14:38 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2016-10-18 01:14:38 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2016-10-18 01:14:38 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2016-10-18 01:14:38 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2016-10-18 01:14:38 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2016-10-18 01:14:38 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2016-10-18 01:14:38 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2016-10-18 01:14:38 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2016-10-18 01:14:38 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2016-10-18 01:14:38 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2016-10-18 01:14:38 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2016-10-18 01:14:38 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2016-10-18 01:14:38 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2016-10-18 01:14:38 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2016-10-18 03:14:38.336 ThaliTest[4375:10040581] THREAD WARNING: ['JXcore'] took '8070.468018' ms. Plugin should use a background thread.
,2016-10-18 01:14:38 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 01:14:38 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 01:14:38 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 01:14:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 01:14:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 01:14:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 01:14:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 01:14:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 01:14:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 01:14:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 01:14:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 01:14:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 01:14:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 01:14:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 01:14:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 01:14:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 01:14:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 01:14:46 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 01:14:46 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 01:14:47 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 01:14:47 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 01:14:48 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 01:14:48 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 01:14:49 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 01:14:49 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 01:14:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 01:14:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 01:14:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 01:14:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 01:14:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 03:14:52.739 ThaliTest[4375:10040805] Error!: error is undefined
Stack:[{"_fileName":"/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js","_functionName":"Coo,rdinatedClient.prototype._error","_lineNumber":"220","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/lib/CoordinatedClient,.js:220:1"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":,"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Ap,plication/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/private/var/mobile/Co,ntainers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app,/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-,1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manage,r.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modu,les/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.recon,nect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/ma,nager.js:528:11"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber,":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName",:"/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNu,mber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/pri,vate/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socke,t.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
2016-10-18 01:14:52 - ERROR TestsProcess: 'uncaught exception, error: ,'TypeError: error is undefined', stack: 'TypeError: error is undefined
    at CoordinatedClient.prototype._error@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:220:1,
    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7
    at Socket.prototype.emit@/private/var/mobile/Containers/Bundl,e/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
    at Manager.prototype.emitAll@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest,.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
    at Manager.prototype.reconnect@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.,js:507:5
    at Manager.prototype.reconnect/timer</<@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
    at Manager.prototype.connect/erro,rSub<@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7
    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/A2CF9E,FB-B94D-4770-BCDF-1DBBFA63A6CE/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7
    at Socket.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B94D-4770-BCDF-1DBBFA63A6CE/Thal,iTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3''
2016-10-18 01:14:52 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
TypeError: error is undefined (/private/var/mobile/Containers/Bundle/Application/A2CF9EFB-B9
```
