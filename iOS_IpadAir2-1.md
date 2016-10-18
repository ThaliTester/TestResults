#### Test 884969634f55f99_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/884969634f55f99/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/C9B1ED24-47DD-495A-B6ED-F6B67FEAE8ED/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/C9B1ED24-47DD-495A-B6ED-F6B67FEAE8ED/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/884969634f55f99/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/884969634f55f99/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53891"
,(lldb)     command script import "/tmp/C9B1ED24-47DD-495A-B6ED-F6B67FEAE8ED/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-10-18 02:55:23.600 ThaliTest[4349:8603674] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B758CB38-A68E-412A-AF1E-15D6102F6BBD/Library/Cookies/Cookies.binarycookies
,2016-10-18 02:55:24.004 ThaliTest[4349:8603674] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-18 02:55:24.005 ThaliTest[4349:8603674] Multi-tasking -> Device: YES, App: YES
,2016-10-18 02:55:24.026 ThaliTest[4349:8603674] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-18 02:55:26.023 ThaliTest[4349:8603674] Using UIWebView
,2016-10-18 02:55:26.033 ThaliTest[4349:8603674] [CDVTimer][handleopenurl] 0.344992ms
,2016-10-18 02:55:26.040 ThaliTest[4349:8603674] [CDVTimer][intentandnavigationfilter] 6.624997ms
,2016-10-18 02:55:26.041 ThaliTest[4349:8603674] [CDVTimer][gesturehandler] 0.326037ms
,2016-10-18 02:55:26.041 ThaliTest[4349:8603674] [CDVTimer][TotalPluginStartup] 9.141982ms
,2016-10-18 02:55:32.643 ThaliTest[4349:8603674] Resetting plugins due to page load.
,2016-10-18 02:55:35.707 ThaliTest[4349:8603674] Finished load of: file:///var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/index.html
,2016-10-18 02:55:35.917 ThaliTest[4349:8603674] JXcore Cordova plugin initializing
,2016-10-18 02:55:35.918 ThaliTest[4349:8603918] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-18 00:55:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-18 00:55:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-18 00:55:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-10-18 00:55:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-18 00:55:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,2016-10-18 00:56:19 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  104
,Number of passed tests:  101
,Number of failed tests:  3
,Number of ignored tests:  0
,Total duration:  33.67541301250458
,Failed to execute UT.
,2016-10-18 00:56:19 - DEBUG UnitTest_app: 'Failed to execute UT.'
,2016-10-18 00:56:19 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,2016-10-18 00:56:20 - DEBUG UnitTest_app: 'My device name is: Apple-IpadAir2-1'
2016-10-18 00:56:20 - WARN testUtils: 'myNameCallback not set!'
,2016-10-18 00:56:20 - DEBUG UnitTest_app: 'Running for NATIVE network type'
,2016-10-18 00:56:22 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2016-10-18 00:56:22 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2016-10-18 00:56:22 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2016-10-18 00:56:23 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2016-10-18 00:56:23 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2016-10-18 00:56:23 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2016-10-18 00:56:23 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2016-10-18 00:56:24 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2016-10-18 00:56:24 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2016-10-18 00:56:24 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2016-10-18 00:56:24 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2016-10-18 00:56:24 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2016-10-18 00:56:24 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2016-10-18 00:56:25 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2016-10-18 00:56:25 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2016-10-18 00:56:25 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2016-10-18 00:56:25 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2016-10-18 00:56:25 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2016-10-18 00:56:25 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2016-10-18 00:56:25 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2016-10-18 00:56:25 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2016-10-18 00:56:25 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2016-10-18 00:56:25 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2016-10-18 00:56:25 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2016-10-18 00:56:25 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2016-10-18 00:56:25 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2016-10-18 00:56:25 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2016-10-18 00:56:25 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2016-10-18 00:56:25 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2016-10-18 00:56:25 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2016-10-18 00:56:25 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2016-10-18 00:56:25 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2016-10-18 00:56:25 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2016-10-18 00:56:25 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2016-10-18 00:56:25 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2016-10-18 00:56:25 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2016-10-18 00:56:25 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2016-10-18 02:56:25.542 ThaliTest[4349:8603674] THREAD WARNING: ['JXcore'] took '6282.372070' ms. Plugin should use a background thread.
,2016-10-18 00:56:25 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 00:56:25 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 00:56:25 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 00:56:26 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 00:56:26 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 00:56:27 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 00:56:27 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 00:56:28 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 00:56:28 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 00:56:29 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 00:56:29 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 00:56:30 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 00:56:30 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 00:56:31 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 00:56:31 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 00:56:32 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 00:56:32 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 00:56:33 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 00:56:33 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 00:56:34 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 00:56:34 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 00:56:35 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 00:56:35 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 00:56:36 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 00:56:36 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 00:56:37 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 00:56:37 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 00:56:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 00:56:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 00:56:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-18 02:56:40.101 ThaliTest[4349:8603918] Error!: error is undefined
Stack:[{"_fileName":"/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js","_functionName":"Coor,dinatedClient.prototype._error","_lineNumber":"220","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/lib/CoordinatedClient.,js:220:1"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":",7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/App,lication/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/private/var/mobile/Con,tainers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/,www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-D,AB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager,.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modul,es/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconn,ect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/man,ager.js:528:11"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber",:"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":,"/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNum,ber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/priv,ate/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket,.prototype.onError@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
2016-10-18 00:56:40 - ERROR TestsProcess: 'uncaught exception, error: ',TypeError: error is undefined', stack: 'TypeError: error is undefined
    at CoordinatedClient.prototype._error@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:220:1,
    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7
    at Socket.prototype.emit@/private/var/mobile/Containers/Bundle,/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
    at Manager.prototype.emitAll@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.,app/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
    at Manager.prototype.reconnect@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.j,s:507:5
    at Manager.prototype.reconnect/timer</<@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
    at Manager.prototype.connect/error,Sub<@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7
    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/49DA88F,6-F020-4126-AEB1-DAB1BF5E512F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7
    at Socket.prototype.onError@/private/var/mobile/Containers/Bundle/Application/49DA88F6-F020-4126-AEB1-DAB1BF5E512F/Thali,Test.app/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3''
2016-10-18 00:56:40 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
TypeError: error is undefined (/private/var/mobile/Containers/Bundle/Application/49DA88F6-F02
```
