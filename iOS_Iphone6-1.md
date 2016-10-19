#### Test 90041481d4625bb_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/90041481d4625bb/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,(lldb) command source -s 0 '/tmp/8BC0CBB1-BBD4-4168-BA20-3D337C472866/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/8BC0CBB1-BBD4-4168-BA20-3D337C472866/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/90041481d4625bb/build_ios/ThaliTest.app"
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Current executable set to '/Users/thali/Github/CI/builder/builds/90041481d4625bb/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61261"
,(lldb)     command script import "/tmp/8BC0CBB1-BBD4-4168-BA20-3D337C472866/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-19 18:29:02.071 ThaliTest[2481:5231730] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D65C5462-29A1-4E35-B978-FC24E5AFB58D/Library/Cookies/Cookies.binarycookies
,2016-10-19 18:29:02.111 ThaliTest[2481:5231730] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-19 18:29:02.112 ThaliTest[2481:5231730] Multi-tasking -> Device: YES, App: YES
,2016-10-19 18:29:02.126 ThaliTest[2481:5231730] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-19 18:29:02.456 ThaliTest[2481:5231730] Using UIWebView
,2016-10-19 18:29:02.460 ThaliTest[2481:5231730] [CDVTimer][handleopenurl] 0.213027ms
,2016-10-19 18:29:02.464 ThaliTest[2481:5231730] [CDVTimer][intentandnavigationfilter] 4.307032ms
2016-10-19 18:29:02.465 ThaliTest[2481:5231730] [CDVTimer][gesturehandler] 0.150025ms
2016-10-19 18:29:02.465 ThaliTest[2481:5231730] [CDVTimer][TotalPluginStartup] 5.532026ms
,2016-10-19 18:29:07.542 ThaliTest[2481:5231730] Resetting plugins due to page load.
,2016-10-19 18:29:07.902 ThaliTest[2481:5231730] Finished load of: file:///var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/index.html
,2016-10-19 18:29:08.233 ThaliTest[2481:5231730] JXcore Cordova plugin initializing
,2016-10-19 18:29:08.234 ThaliTest[2481:5231891] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-19 16:29:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-19 16:29:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-19 16:29:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-10-19 16:29:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-19 16:29:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-10-19 16:29:42 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  104
Number of passed tests:  101
Number of failed tests:  3
Number of ignored tests:  0
Total duration:  23.85173201560974
F,ailed to execute UT.
2016-10-19 16:29:42 - DEBUG UnitTest_app: 'Failed to execute UT.'
,2016-10-19 16:29:42 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,2016-10-19 16:29:43 - DEBUG UnitTest_app: 'My device name is: Apple-Iphone6-1'
,2016-10-19 16:29:43 - DEBUG UnitTest_app: 'Running for NATIVE network type'
,2016-10-19 16:29:45 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2016-10-19 16:29:46 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2016-10-19 16:29:46 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2016-10-19 16:29:47 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2016-10-19 16:29:47 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2016-10-19 16:29:47 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2016-10-19 16:29:47 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2016-10-19 16:29:48 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2016-10-19 16:29:48 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2016-10-19 16:29:48 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2016-10-19 16:29:48 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2016-10-19 16:29:48 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2016-10-19 16:29:48 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2016-10-19 16:29:49 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2016-10-19 16:29:49 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2016-10-19 16:29:49 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2016-10-19 16:29:49 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2016-10-19 16:29:49 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2016-10-19 16:29:49 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2016-10-19 16:29:49 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2016-10-19 16:29:49 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2016-10-19 16:29:49 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2016-10-19 16:29:49 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2016-10-19 16:29:49 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2016-10-19 16:29:49 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2016-10-19 16:29:49 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2016-10-19 16:29:49 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2016-10-19 16:29:49 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2016-10-19 16:29:49 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2016-10-19 16:29:49 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2016-10-19 16:29:49 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2016-10-19 16:29:49 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2016-10-19 16:29:49 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2016-10-19 16:29:49 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2016-10-19 16:29:49 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2016-10-19 16:29:49 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2016-10-19 16:29:49 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2016-10-19 16:29:49 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6C1E170F,-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-19 16:29:49 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6C1E170F,-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-19 16:29:49 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-19 16:29:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6C1E170F,-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-19 16:29:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6C1E170F,-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-19 16:29:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6C1E170F,-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-19 16:29:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-19 16:29:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6C1E170F,-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-19 16:29:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-19 16:29:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6C1E170F,-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-19 16:29:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6C1E170F,-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-19 16:29:54 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6C1E170F,-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-19 16:29:54 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-19 16:29:55 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6C1E170F,-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-19 16:29:55 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6C1E170F,-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-19 16:29:56 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6C1E170F,-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-19 16:29:56 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-19 16:29:57 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6C1E170F,-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-19 16:29:57 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-19 16:30:06 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6C1E170F,-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-19 16:30:06 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-19 16:30:07 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6C1E170F,-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-19 16:30:07 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6C1E170F,-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-19 16:30:08 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6C1E170F,-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-19 16:30:08 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6C1E170F,-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-19 16:30:09 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6C1E170F,-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-19 16:30:09 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-19 16:30:10 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6C1E170F,-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-19 16:30:10 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-19 16:30:11 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6C1E170F,-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-19 18:30:11.783 ThaliTest[2481:5231891] Error!: error is undefined
Stack:[{"_fileName":"/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js","_functionName":"Coordinated,Client.prototype._error","_lineNumber":"220","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:220:1"},{"_,fileName":"/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emi,tter.prototype.emit@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D,2,A477B95D88/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/private/var/containers/Bundle/Application/6C1E170F-5665-4,D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/mana,ger.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/socket,.io-client/lib/manager.js:81:7"},{"_fileName":"/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumbe,r,":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/private/var/,containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager,.prototype.reconnect/timer</<@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/private/var/containers/Bundle/Application/6C1E170F-5,665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/private/var,/,containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www,/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/containers/Bundle/Application/6C1E170F-5665-4,D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules,/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/j,x,core/node_modules/engine.io-client/lib/socket.js:670:3"}]
,2016-10-19 16:30:11 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
    at CoordinatedClient.prototype._error@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A47,7B95D88/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:220:1
    at Emitter.prototype.emit@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7
    at So,cket.prototype.emit@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
    at Manager.prototype.emitAll@/private/var/containers/Bundle/Application/6C1E,170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
    at Manager.prototype.reconnect@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_mo,dules/socket.io-client/lib/manager.js:507:5
    at Manager.prototype.reconnect/timer</<@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
    at Ma,nager.prototype.connect/errorSub<@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7
    at Emitter.prototype.emit@/private/var/containers/Bundle/Appl,ication/6C1E170F-5665-4D1D-AE77-D2A477B95D88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7
    at Socket.prototype.onError@/private/var/containers/Bundle/Application/6C1E170F-5665-4D1D-AE77-D2A477B95D,88/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3''
2016-10-19 16:30:11 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
