#### Test 8944331487965e9_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8944331487965e9/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/8469425D-E1A3-4C5C-9E64-B9B0165C18EB/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/8469425D-E1A3-4C5C-9E64-B9B0165C18EB/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8944331487965e9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8944331487965e9/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65040"
,(lldb)     command script import "/tmp/8469425D-E1A3-4C5C-9E64-B9B0165C18EB/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-14 22:04:24.875 ThaliTest[4206:8212747] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/EA38C3B0-8B19-4309-87C7-A56C3CE15658/Library/Cookies/Cookies.binarycookies
,2016-10-14 22:04:25.254 ThaliTest[4206:8212747] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-14 22:04:25.255 ThaliTest[4206:8212747] Multi-tasking -> Device: YES, App: YES
,2016-10-14 22:04:25.269 ThaliTest[4206:8212747] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-14 22:04:26.867 ThaliTest[4206:8212747] Using UIWebView
,2016-10-14 22:04:26.873 ThaliTest[4206:8212747] [CDVTimer][handleopenurl] 0.536978ms
,2016-10-14 22:04:26.880 ThaliTest[4206:8212747] [CDVTimer][intentandnavigationfilter] 6.339014ms
,2016-10-14 22:04:26.881 ThaliTest[4206:8212747] [CDVTimer][gesturehandler] 0.285983ms
,2016-10-14 22:04:26.881 ThaliTest[4206:8212747] [CDVTimer][TotalPluginStartup] 8.794010ms
,2016-10-14 22:04:33.314 ThaliTest[4206:8212747] Resetting plugins due to page load.
,2016-10-14 22:04:36.249 ThaliTest[4206:8212747] Finished load of: file:///var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/index.html
,2016-10-14 22:04:36.522 ThaliTest[4206:8212747] JXcore Cordova plugin initializing
,2016-10-14 22:04:36.523 ThaliTest[4206:8213017] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-14 20:04:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-14 20:04:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-14 20:04:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-10-14 20:04:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-14 20:04:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,failed - Unexpected disconnect received on socket <GCDAsyncSocket: 0x153a79350> in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/Utils/MultipeerConnectHelper.swift"), line: 56
,XCTAssertNil failed: "ConnectionFailed" -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/TCPListenerTests.swift"), line: 321
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,2016-10-14 20:05:19 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  104
,Number of passed tests:  99
,Number of failed tests:  5
,Number of ignored tests:  0
,Total duration:  33.67001003026962
,Failed to execute UT.
,2016-10-14 20:05:19 - DEBUG UnitTest_app: 'Failed to execute UT.'
,2016-10-14 20:05:19 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,2016-10-14 20:05:20 - DEBUG UnitTest_app: 'My device name is: Apple-IpadAir2-1'
2016-10-14 20:05:20 - WARN testUtils: 'myNameCallback not set!'
2016-10-14 20:05:20 - DEBUG UnitTest_app: 'Running for WIFI network type'
,2016-10-14 20:05:22 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2016-10-14 20:05:23 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2016-10-14 20:05:23 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2016-10-14 20:05:24 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2016-10-14 20:05:24 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2016-10-14 20:05:24 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2016-10-14 20:05:24 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2016-10-14 20:05:25 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2016-10-14 20:05:25 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2016-10-14 20:05:25 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2016-10-14 20:05:25 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2016-10-14 20:05:25 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2016-10-14 20:05:25 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2016-10-14 20:05:25 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2016-10-14 20:05:25 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2016-10-14 20:05:25 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2016-10-14 20:05:25 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2016-10-14 20:05:25 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2016-10-14 20:05:25 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2016-10-14 20:05:26 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2016-10-14 20:05:26 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2016-10-14 20:05:26 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2016-10-14 20:05:26 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2016-10-14 20:05:26 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2016-10-14 20:05:26 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2016-10-14 20:05:26 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2016-10-14 20:05:26 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2016-10-14 20:05:26 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2016-10-14 20:05:26 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2016-10-14 20:05:26 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2016-10-14 20:05:26 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2016-10-14 20:05:26 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2016-10-14 20:05:26 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2016-10-14 20:05:26 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2016-10-14 20:05:26 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2016-10-14 22:05:26.223 ThaliTest[4206:8212747] THREAD WARNING: ['JXcore'] took '6369.147949' ms. Plugin should use a background thread.
,2016-10-14 20:05:26 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 20:05:26 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 20:05:26 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 20:05:26 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 20:05:26 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 20:05:27 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 20:05:27 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 20:05:28 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 20:05:28 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 20:05:29 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 20:05:29 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 20:05:30 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 20:05:30 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 20:05:31 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 20:05:31 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 20:05:32 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 20:05:32 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 20:05:33 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 20:05:33 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 20:05:34 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 20:05:34 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 20:05:35 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 20:05:35 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 20:05:36 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 20:05:36 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 20:05:37 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 20:05:37 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 20:05:38 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 20:05:38 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 20:05:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-14 22:05:39.982 ThaliTest[4206:8213017] Error!: error is undefined
Stack:[{"_fileName":"/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js","_functionName":"Coor,dinatedClient.prototype._error","_lineNumber":"220","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:220:1"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/private/var/mobile/Con,tainers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/,www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6,DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager,.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modul,es/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconn,ect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/man,ager.js:528:11"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber",:"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":,"/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNum,ber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/priv,ate/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket,.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
2016-10-14 20:05:39 - ERROR TestsProcess: 'uncaught exception, error: ',TypeError: error is undefined', stack: 'TypeError: error is undefined
    at CoordinatedClient.prototype._error@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:220:1,
    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7
    at Socket.prototype.emit@/private/var/mobile/Containers/Bundle,/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
    at Manager.prototype.emitAll@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.,app/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
    at Manager.prototype.reconnect@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.j,s:507:5
    at Manager.prototype.reconnect/timer</<@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
    at Manager.prototype.connect/error,Sub<@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7
    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/C9547AE,7-7689-4FA3-A796-6DB3A2DE876D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7
    at Socket.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C9547AE7-7689-4FA3-A796-6DB3A2DE876D/Thali,Test.app/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3''
2016-10-14 20:05:39 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
TypeError: error is undefined (/private/var/mobile/Containers/Bundle/Application/C9547AE7-768
```
