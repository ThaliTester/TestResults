#### Test 93142442ff07d87_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/93142442ff07d87/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/E7824A8C-3FE8-4EFE-A4EA-03435B559CFD/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/E7824A8C-3FE8-4EFE-A4EA-03435B559CFD/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/93142442ff07d87/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/93142442ff07d87/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56485"
,(lldb)     command script import "/tmp/E7824A8C-3FE8-4EFE-A4EA-03435B559CFD/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-10 13:57:51.452 ThaliTest[5489:13812788] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/81B83844-145B-4D47-A917-BBFBA5D3C65C/Library/Cookies/Cookies.binarycookies
,2016-11-10 13:57:51.514 ThaliTest[5489:13812788] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-10 13:57:51.515 ThaliTest[5489:13812788] Multi-tasking -> Device: YES, App: YES
,2016-11-10 13:57:51.532 ThaliTest[5489:13812788] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-10 13:57:52.310 ThaliTest[5489:13812788] Using UIWebView
,2016-11-10 13:57:52.314 ThaliTest[5489:13812788] [CDVTimer][handleopenurl] 0.177026ms
2016-11-10 13:57:52.317 ThaliTest[5489:13812788] [CDVTimer][intentandnavigationfilter] 2.792001ms
2016-11-10 13:57:52.318 ThaliTest[5489:13812788] [CDVTimer][gesturehandler] 0.147998ms
2016-11-10 13:57:52.318 ThaliTest[5489:13812788] [CDVTimer][TotalPluginStartup] 3.764987ms
,2016-11-10 13:57:55.289 ThaliTest[5489:13812788] Resetting plugins due to page load.
,2016-11-10 13:57:56.924 ThaliTest[5489:13812788] Finished load of: file:///var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/index.html
,2016-11-10 13:57:57.117 ThaliTest[5489:13812788] JXcore Cordova plugin initializing
,2016-11-10 13:57:57.118 ThaliTest[5489:13812962] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-10 12:58:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-10 12:58:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-10 12:58:09 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2016-11-10 12:58:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-11-10 12:58:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-10 12:58:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,failed - Unexpected disconnect received on socket <GCDAsyncSocket: 0x148c53a40> in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/Utils/MultipeerConnectHelper.swift"), line: 56
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-10 12:58:32 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  102
Number of passed tests:  98
Number of failed tests:  4
Number of ignored tests:  0
,Total duration:  22.58634501695633
Failed to execute UT.
2016-11-10 12:58:32 - DEBUG UnitTest_app: 'Failed to execute UT.'
,2016-11-10 12:58:32 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
,2016-11-10 12:58:32 - DEBUG UnitTest_app: 'My device name is: Apple-Iphone5s-1'
2016-11-10 12:58:32 - WARN testUtils: 'myNameCallback not set!'
2016-11-10 12:58:32 - DEBUG UnitTest_app: 'Running for NATIVE network type'
,2016-11-10 12:58:35 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2016-11-10 12:58:35 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2016-11-10 12:58:35 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2016-11-10 12:58:37 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2016-11-10 12:58:37 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2016-11-10 12:58:37 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2016-11-10 12:58:37 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2016-11-10 12:58:38 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2016-11-10 12:58:38 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2016-11-10 12:58:38 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2016-11-10 12:58:38 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2016-11-10 12:58:38 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2016-11-10 12:58:38 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2016-11-10 12:58:39 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2016-11-10 12:58:39 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2016-11-10 12:58:39 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2016-11-10 12:58:39 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2016-11-10 12:58:39 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2016-11-10 12:58:39 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2016-11-10 12:58:39 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2016-11-10 12:58:39 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2016-11-10 12:58:39 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2016-11-10 12:58:39 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2016-11-10 12:58:39 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2016-11-10 12:58:39 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2016-11-10 12:58:39 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2016-11-10 12:58:39 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2016-11-10 12:58:39 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2016-11-10 12:58:39 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2016-11-10 12:58:39 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2016-11-10 12:58:39 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2016-11-10 12:58:39 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2016-11-10 12:58:39 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2016-11-10 12:58:39 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2016-11-10 12:58:39 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2016-11-10 12:58:39 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2016-11-10 12:58:39 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2016-11-10 12:58:39 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2016-11-10 13:58:39.777 ThaliTest[5489:13812788] THREAD WARNING: ['JXcore'] took '7277.582031' ms. Plugin should use a background thread.
,2016-11-10 12:58:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:46 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:46 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:48 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:48 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:49 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:49 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
2016-11-10 12:58:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:54 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:54 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:56 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 13:58:56.519 ThaliTest[5489:13812962] Error!: error is undefined
Stack:[{"_fileName":"/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"220","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/lib/CoordinatedClient,.js:220:1"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":,"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Ap,plication/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/private/var/mobile/Co,ntainers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app,/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-,24493D177051/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manage,r.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modu,les/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.recon,nect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/ma,nager.js:528:11"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber,":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName",:"/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNu,mber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/pri,vate/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socke,t.prototype.onError@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
2016-11-10 12:58:56 - ERROR TestsProcess: 'uncaught exception, error: ,'TypeError: error is undefined', stack: 'TypeError: error is undefined
    at CoordinatedClient.prototype._error@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:220:1,
    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7
    at Socket.prototype.emit@/private/var/mobile/Containers/Bundl,e/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
    at Manager.prototype.emitAll@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest,.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
    at Manager.prototype.reconnect@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.,js:507:5
    at Manager.prototype.reconnect/timer</<@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
    at Manager.prototype.connect/erro,rSub<@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7
    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/15050F,AD-769B-4FB0-B1EC-24493D177051/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7
    at Socket.prototype.onError@/private/var/mobile/Containers/Bundle/Application/15050FAD-769B-4FB0-B1EC-24493D177051/Thal,iTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3''
2016-11-10 12:58:56 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
TypeError: error is undefined (/private/var/mobile/Containers/Bundle/Application/15050FAD-76
```
