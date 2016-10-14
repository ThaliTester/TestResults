#### Test 893786075849728_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/893786075849728/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/0271EBDD-E7CF-4589-8BB7-E12B0A2C0497/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/0271EBDD-E7CF-4589-8BB7-E12B0A2C0497/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/893786075849728/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/893786075849728/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56654"
,(lldb)     command script import "/tmp/0271EBDD-E7CF-4589-8BB7-E12B0A2C0497/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-14 15:08:35.652 ThaliTest[4182:8174881] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/493A9EAB-FB81-483C-B406-EDC2CDA49DC8/Library/Cookies/Cookies.binarycookies
,2016-10-14 15:08:36.015 ThaliTest[4182:8174881] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-14 15:08:36.016 ThaliTest[4182:8174881] Multi-tasking -> Device: YES, App: YES
,2016-10-14 15:08:36.036 ThaliTest[4182:8174881] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-14 15:08:38.020 ThaliTest[4182:8174881] Using UIWebView
,2016-10-14 15:08:38.031 ThaliTest[4182:8174881] [CDVTimer][handleopenurl] 0.384986ms
,2016-10-14 15:08:38.038 ThaliTest[4182:8174881] [CDVTimer][intentandnavigationfilter] 6.491005ms
,2016-10-14 15:08:38.039 ThaliTest[4182:8174881] [CDVTimer][gesturehandler] 0.364006ms
,2016-10-14 15:08:38.039 ThaliTest[4182:8174881] [CDVTimer][TotalPluginStartup] 9.014010ms
,2016-10-14 15:08:45.044 ThaliTest[4182:8174881] Resetting plugins due to page load.
,2016-10-14 15:08:48.833 ThaliTest[4182:8174881] Finished load of: file:///var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/index.html
,2016-10-14 15:08:49.043 ThaliTest[4182:8174881] JXcore Cordova plugin initializing
,2016-10-14 15:08:49.044 ThaliTest[4182:8175148] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-14 13:08:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-14 13:08:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-14 13:08:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-10-14 13:08:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-14 13:08:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-10-14 13:09:31 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  104
,Number of passed tests:  101
,Number of failed tests:  3
,Number of ignored tests:  0
,Total duration:  33.056057035923
,Failed to execute UT.
,2016-10-14 13:09:31 - DEBUG UnitTest_app: 'Failed to execute UT.'
,2016-10-14 13:09:31 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,2016-10-14 13:09:32 - DEBUG UnitTest_app: 'My device name is: Apple-IpadAir2-1'
,2016-10-14 13:09:32 - WARN testUtils: 'myNameCallback not set!'
,2016-10-14 13:09:32 - DEBUG UnitTest_app: 'Running for WIFI network type'
,2016-10-14 13:09:34 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2016-10-14 13:09:35 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2016-10-14 13:09:35 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2016-10-14 13:09:36 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2016-10-14 13:09:36 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2016-10-14 13:09:36 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2016-10-14 13:09:36 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2016-10-14 13:09:37 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2016-10-14 13:09:37 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2016-10-14 13:09:37 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2016-10-14 13:09:37 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2016-10-14 13:09:37 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2016-10-14 13:09:37 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2016-10-14 13:09:37 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2016-10-14 13:09:37 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2016-10-14 13:09:37 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2016-10-14 13:09:37 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2016-10-14 13:09:37 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2016-10-14 13:09:37 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2016-10-14 13:09:38 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2016-10-14 13:09:38 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2016-10-14 13:09:38 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2016-10-14 13:09:38 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2016-10-14 13:09:38 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2016-10-14 13:09:38 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2016-10-14 13:09:38 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2016-10-14 13:09:38 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2016-10-14 13:09:38 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2016-10-14 13:09:38 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2016-10-14 13:09:38 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2016-10-14 13:09:38 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2016-10-14 13:09:38 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2016-10-14 13:09:38 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2016-10-14 13:09:38 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2016-10-14 13:09:38 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2016-10-14 15:09:38.222 ThaliTest[4182:8174881] THREAD WARNING: ['JXcore'] took '6417.541992' ms. Plugin should use a background thread.
,2016-10-14 13:09:38 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 13:09:38 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 13:09:38 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 13:09:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 13:09:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 13:09:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 13:09:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 13:09:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 13:09:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 13:09:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 13:09:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 13:09:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 13:09:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 13:09:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 13:09:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 13:09:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 13:09:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 13:09:46 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 13:09:46 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 13:09:47 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 13:09:47 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 13:09:48 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 13:09:48 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 13:09:49 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 13:09:49 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 13:09:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 13:09:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 13:09:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 13:09:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 13:09:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 15:09:52.671 ThaliTest[4182:8175148] Error!: error is undefined
Stack:[{"_fileName":"/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js","_functionName":"Coor,dinatedClient.prototype._error","_lineNumber":"220","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/lib/CoordinatedClient.,js:220:1"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":",7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/App,lication/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/private/var/mobile/Con,tainers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/,www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0,585FD266217/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager,.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modul,es/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconn,ect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/man,ager.js:528:11"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber",:"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":,"/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNum,ber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/priv,ate/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket,.prototype.onError@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
2016-10-14 13:09:52 - ERROR TestsProcess: 'uncaught exception, error: ',TypeError: error is undefined', stack: 'TypeError: error is undefined
    at CoordinatedClient.prototype._error@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:220:1,
    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7
    at Socket.prototype.emit@/private/var/mobile/Containers/Bundle,/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
    at Manager.prototype.emitAll@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.,app/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
    at Manager.prototype.reconnect@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.j,s:507:5
    at Manager.prototype.reconnect/timer</<@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
    at Manager.prototype.connect/error,Sub<@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7
    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/4A9172A,6-8236-4EC6-97BB-0585FD266217/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7
    at Socket.prototype.onError@/private/var/mobile/Containers/Bundle/Application/4A9172A6-8236-4EC6-97BB-0585FD266217/Thali,Test.app/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3''
2016-10-14 13:09:52 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
TypeError: error is undefined (/private/var/mobile/Containers/Bundle/Application/4A9172A6-823
```
