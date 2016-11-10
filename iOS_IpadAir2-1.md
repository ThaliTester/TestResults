#### Test 93142442ff07d87_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/93142442ff07d87/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/189A1203-F6EF-4711-A16A-AC63F0D8E80E/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/189A1203-F6EF-4711-A16A-AC63F0D8E80E/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/93142442ff07d87/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/93142442ff07d87/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56483"
,(lldb)     command script import "/tmp/189A1203-F6EF-4711-A16A-AC63F0D8E80E/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success,
(lldb)     autoexit
,2016-11-10 13:57:54.035 ThaliTest[5375:11512340] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3CB67690-4E41-4FFC-9464-DD4FE066F1DF/Library/Cookies/Cookies.binarycookies
,2016-11-10 13:57:54.267 ThaliTest[5375:11512340] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-10 13:57:54.268 ThaliTest[5375:11512340] Multi-tasking -> Device: YES, App: YES
,2016-11-10 13:57:54.281 ThaliTest[5375:11512340] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-10 13:57:55.120 ThaliTest[5375:11512340] Using UIWebView
,2016-11-10 13:57:55.123 ThaliTest[5375:11512340] [CDVTimer][handleopenurl] 0.095963ms
,2016-11-10 13:57:55.125 ThaliTest[5375:11512340] [CDVTimer][intentandnavigationfilter] 1.856029ms
2016-11-10 13:57:55.125 ThaliTest[5375:11512340] [CDVTimer][gesturehandler] 0.083983ms
2016-11-10 13:57:55.125 ThaliTest[5375:11512340] [CDVTimer][TotalPluginStartup] 2.483010ms
,2016-11-10 13:57:58.259 ThaliTest[5375:11512340] Resetting plugins due to page load.
,2016-11-10 13:57:59.652 ThaliTest[5375:11512340] Finished load of: file:///var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/index.html
,2016-11-10 13:57:59.792 ThaliTest[5375:11512340] JXcore Cordova plugin initializing
,2016-11-10 13:57:59.793 ThaliTest[5375:11512511] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-10 12:58:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-10 12:58:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-10 12:58:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2016-11-10 12:58:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-10 12:58:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-10 12:58:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-11-10 12:58:42 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  102
,Number of passed tests:  99
Number of failed tests:  3
Number of ignored tests:  0
Total duration:  33.05665099620819
,Failed to execute UT.
,2016-11-10 12:58:42 - DEBUG UnitTest_app: 'Failed to execute UT.'
,2016-11-10 12:58:42 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
,2016-11-10 12:58:42 - DEBUG UnitTest_app: 'My device name is: Apple-IpadAir2-1'
2016-11-10 12:58:42 - WARN testUtils: 'myNameCallback not set!'
2016-11-10 12:58:42 - DEBUG UnitTest_app: 'Running for NATIVE network type'
,2016-11-10 12:58:44 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2016-11-10 12:58:44 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2016-11-10 12:58:44 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2016-11-10 12:58:45 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2016-11-10 12:58:45 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2016-11-10 12:58:45 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2016-11-10 12:58:45 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2016-11-10 12:58:46 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2016-11-10 12:58:46 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2016-11-10 12:58:46 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2016-11-10 12:58:46 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2016-11-10 12:58:46 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2016-11-10 12:58:46 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2016-11-10 12:58:47 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2016-11-10 12:58:47 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2016-11-10 12:58:47 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2016-11-10 12:58:47 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2016-11-10 12:58:47 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2016-11-10 12:58:47 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2016-11-10 12:58:47 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2016-11-10 12:58:47 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2016-11-10 12:58:47 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2016-11-10 12:58:47 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2016-11-10 12:58:47 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2016-11-10 12:58:47 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2016-11-10 12:58:47 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2016-11-10 12:58:47 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2016-11-10 12:58:47 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2016-11-10 12:58:47 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2016-11-10 12:58:47 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2016-11-10 12:58:47 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2016-11-10 12:58:47 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2016-11-10 12:58:47 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2016-11-10 12:58:47 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2016-11-10 12:58:47 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2016-11-10 12:58:47 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2016-11-10 12:58:47 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2016-11-10 12:58:47 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2016-11-10 13:58:47.570 ThaliTest[5375:11512340] THREAD WARNING: ['JXcore'] took '5299.074707' ms. Plugin should use a background thread.
,2016-11-10 12:58:47 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:48 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
2016-11-10 12:58:48 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:48 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:48 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:49 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
2016-11-10 12:58:49 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:55 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
2016-11-10 12:58:55 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:56 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:56 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:57 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:57 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:58 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:58 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:59 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:58:59 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:59:00 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:59:00 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:59:01 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:59:01 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-10 12:59:02 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/,2016-11-10 13:59:02.740 ThaliTest[5375:11512511] Error!: error is undefined
Stack:[{"_fileName":"/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js","_functionName":"Coo,rdinatedClient.prototype._error","_lineNumber":"220","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/lib/CoordinatedClient,.js:220:1"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":,"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Ap,plication/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/private/var/mobile/Co,ntainers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app,/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-,3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manage,r.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.recon,nect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/ma,nager.js:528:11"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber,":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName",:"/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/pri,vate/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
2016-11-10 12:59:02 - ERROR TestsProcess: 'uncaught exception, error: ,'TypeError: error is undefined', stack: 'TypeError: error is undefined
    at CoordinatedClient.prototype._error@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:220:1,
    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7
    at Socket.prototype.emit@/private/var/mobile/Containers/Bundl,e/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
    at Manager.prototype.emitAll@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest,.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
    at Manager.prototype.reconnect@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.,js:507:5
    at Manager.prototype.reconnect/timer</<@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
    at Manager.prototype.connect/erro,rSub<@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7
    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/C0B066,A6-CF69-4727-A5AA-3C6C182482A6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7
    at Socket.prototype.onError@/private/var/mobile/Containers/Bundle/Application/C0B066A6-CF69-4727-A5AA-3C6C182482A6/Tha,liTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3''
2016-11-10 12:59:02 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
TypeError: error is undefined (/private/var/mobile/Containers/Bundle/Application/C0B066A6-C
```
