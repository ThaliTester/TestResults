#### Test 884969639726768_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/884969639726768/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/F1635A0B-E3B2-4B14-829F-B2AB747DEF29/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/F1635A0B-E3B2-4B14-829F-B2AB747DEF29/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/884969639726768/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/884969639726768/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51678"
,(lldb)     command script import "/tmp/F1635A0B-E3B2-4B14-829F-B2AB747DEF29/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-15 02:55:26.918 ThaliTest[4226:8239214] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/EE951566-2DC0-4CD0-9007-58CFB860B496/Library/Cookies/Cookies.binarycookies
,2016-10-15 02:55:27.289 ThaliTest[4226:8239214] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-15 02:55:27.291 ThaliTest[4226:8239214] Multi-tasking -> Device: YES, App: YES
,2016-10-15 02:55:27.314 ThaliTest[4226:8239214] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-15 02:55:29.480 ThaliTest[4226:8239214] Using UIWebView
,2016-10-15 02:55:29.486 ThaliTest[4226:8239214] [CDVTimer][handleopenurl] 0.360012ms
,2016-10-15 02:55:29.494 ThaliTest[4226:8239214] [CDVTimer][intentandnavigationfilter] 6.684005ms
,2016-10-15 02:55:29.495 ThaliTest[4226:8239214] [CDVTimer][gesturehandler] 0.290036ms
,2016-10-15 02:55:29.495 ThaliTest[4226:8239214] [CDVTimer][TotalPluginStartup] 9.066999ms
,2016-10-15 02:55:37.665 ThaliTest[4226:8239214] Resetting plugins due to page load.
,2016-10-15 02:55:41.479 ThaliTest[4226:8239214] Finished load of: file:///var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/index.html
,2016-10-15 02:55:41.742 ThaliTest[4226:8239214] JXcore Cordova plugin initializing
2016-10-15 02:55:41.743 ThaliTest[4226:8239456] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-15 00:55:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-15 00:55:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-15 00:55:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-10-15 00:55:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-15 00:55:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,XCTAssertNil failed: "ConnectionFailed" -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/TCPListenerTests.swift"), line: 321
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-10-15 00:56:22 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  104
,Number of passed tests:  100
,Number of failed tests:  4
,Number of ignored tests:  0
,Total duration:  31.12812799215317
,Failed to execute UT.
,2016-10-15 00:56:22 - DEBUG UnitTest_app: 'Failed to execute UT.'
,2016-10-15 00:56:22 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,2016-10-15 00:56:23 - DEBUG UnitTest_app: 'My device name is: Apple-IpadAir2-1'
2016-10-15 00:56:23 - WARN testUtils: 'myNameCallback not set!'
,2016-10-15 00:56:23 - DEBUG UnitTest_app: 'Running for NATIVE network type'
,2016-10-15 00:56:25 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2016-10-15 00:56:26 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2016-10-15 00:56:26 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2016-10-15 00:56:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2016-10-15 00:56:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2016-10-15 00:56:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2016-10-15 00:56:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2016-10-15 00:56:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2016-10-15 00:56:28 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2016-10-15 00:56:28 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2016-10-15 00:56:28 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2016-10-15 00:56:28 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2016-10-15 00:56:28 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2016-10-15 00:56:28 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2016-10-15 00:56:28 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2016-10-15 00:56:28 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2016-10-15 00:56:28 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2016-10-15 00:56:28 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2016-10-15 00:56:28 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2016-10-15 00:56:28 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2016-10-15 00:56:28 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2016-10-15 00:56:28 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2016-10-15 00:56:28 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2016-10-15 00:56:28 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2016-10-15 00:56:28 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2016-10-15 00:56:28 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2016-10-15 00:56:28 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2016-10-15 00:56:28 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2016-10-15 00:56:28 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2016-10-15 00:56:28 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2016-10-15 00:56:28 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2016-10-15 00:56:28 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2016-10-15 00:56:28 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2016-10-15 00:56:28 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2016-10-15 00:56:28 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2016-10-15 00:56:28 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2016-10-15 00:56:28 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2016-10-15 02:56:29.043 ThaliTest[4226:8239214] THREAD WARNING: ['JXcore'] took '6443.598145' ms. Plugin should use a background thread.
,2016-10-15 00:56:29 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-15 00:56:29 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-15 00:56:29 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-15 00:56:29 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-15 00:56:29 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-15 00:56:30 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-15 00:56:30 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-15 00:56:31 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-15 00:56:31 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-15 00:56:32 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-15 00:56:32 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-15 00:56:33 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-15 00:56:33 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-15 00:56:34 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-15 00:56:34 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-15 00:56:35 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-15 00:56:35 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-15 00:56:36 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-15 00:56:36 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-15 00:56:38 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-15 00:56:38 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-15 00:56:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-15 00:56:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-15 00:56:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-15 00:56:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-15 00:56:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-15 00:56:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-15 00:56:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-15 00:56:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-15 00:56:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-15 02:56:43.239 ThaliTest[4226:8239456] Error!: error is undefined
Stack:[{"_fileName":"/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js","_functionName":"Coor,dinatedClient.prototype._error","_lineNumber":"220","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/lib/CoordinatedClient.,js:220:1"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":",7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/App,lication/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/private/var/mobile/Con,tainers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/,www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-5,4596B87F75C/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager,.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modul,es/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconn,ect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/man,ager.js:528:11"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber",:"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":,"/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNum,ber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/priv,ate/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket,.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
2016-10-15 00:56:43 - ERROR TestsProcess: 'uncaught exception, error: ',TypeError: error is undefined', stack: 'TypeError: error is undefined
    at CoordinatedClient.prototype._error@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:220:1,
    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7
    at Socket.prototype.emit@/private/var/mobile/Containers/Bundle,/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
    at Manager.prototype.emitAll@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.,app/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
    at Manager.prototype.reconnect@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.j,s:507:5
    at Manager.prototype.reconnect/timer</<@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
    at Manager.prototype.connect/error,Sub<@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7
    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/A07D70D,F-ECB4-4FA8-AD7B-54596B87F75C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7
    at Socket.prototype.onError@/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB4-4FA8-AD7B-54596B87F75C/Thali,Test.app/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3''
2016-10-15 00:56:43 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
TypeError: error is undefined (/private/var/mobile/Containers/Bundle/Application/A07D70DF-ECB
```
