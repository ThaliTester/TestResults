#### Test 888381025b93203_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/888381025b93203/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/BE0DE781-F66F-4360-A83A-71502CDC67D8/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/BE0DE781-F66F-4360-A83A-71502CDC67D8/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/888381025b93203/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/888381025b93203/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51659"
,(lldb)     command script import "/tmp/BE0DE781-F66F-4360-A83A-71502CDC67D8/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-13 15:59:31.025 ThaliTest[2182:4432224] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0065B858-8A64-4E90-B2C4-EAC6D46E2592/Library/Cookies/Cookies.binarycookies
,2016-10-13 15:59:31.069 ThaliTest[2182:4432224] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-13 15:59:31.070 ThaliTest[2182:4432224] Multi-tasking -> Device: YES, App: YES
,2016-10-13 15:59:31.082 ThaliTest[2182:4432224] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-13 15:59:31.373 ThaliTest[2182:4432224] Using UIWebView
,2016-10-13 15:59:31.377 ThaliTest[2182:4432224] [CDVTimer][handleopenurl] 0.137985ms
,2016-10-13 15:59:31.381 ThaliTest[2182:4432224] [CDVTimer][intentandnavigationfilter] 3.555954ms
2016-10-13 15:59:31.382 ThaliTest[2182:4432224] [CDVTimer][gesturehandler] 0.117004ms
2016-10-13 15:59:31.382 ThaliTest[2182:4432224] [CDVTimer][TotalPluginS,tartup] 4.476011ms
,2016-10-13 15:59:36.752 ThaliTest[2182:4432224] Resetting plugins due to page load.
,2016-10-13 15:59:37.086 ThaliTest[2182:4432224] Finished load of: file:///var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/index.html
,2016-10-13 15:59:37.422 ThaliTest[2182:4432224] JXcore Cordova plugin initializing
,2016-10-13 15:59:37.423 ThaliTest[2182:4432400] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-13 13:59:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-13 13:59:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-13 13:59:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-10-13 13:59:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-13 13:59:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,2016-10-13 14:00:12 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  104
,Number of passed tests:  101
,Number of failed tests:  3
,Number of ignored tests:  0
,Total duration:  24.80518597364426
,Failed to execute UT.
,2016-10-13 14:00:12 - DEBUG UnitTest_app: 'Failed to execute UT.'
,2016-10-13 14:00:12 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,2016-10-13 14:00:13 - DEBUG UnitTest_app: 'My device name is: Apple-Iphone6-1'
2016-10-13 14:00:13 - WARN testUtils: 'myNameCallback not set!'
2016-10-13 14:00:13 - DEBUG UnitTest_app: 'Running for WIFI network type'
,2016-10-13 14:00:15 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2016-10-13 14:00:15 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2016-10-13 14:00:15 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2016-10-13 14:00:17 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2016-10-13 14:00:17 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2016-10-13 14:00:17 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2016-10-13 14:00:17 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2016-10-13 14:00:18 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2016-10-13 14:00:18 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2016-10-13 14:00:18 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2016-10-13 14:00:18 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2016-10-13 14:00:18 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2016-10-13 14:00:18 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2016-10-13 14:00:18 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2016-10-13 14:00:18 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2016-10-13 14:00:18 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2016-10-13 14:00:18 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2016-10-13 14:00:18 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2016-10-13 14:00:19 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2016-10-13 14:00:19 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2016-10-13 14:00:19 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2016-10-13 14:00:19 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2016-10-13 14:00:19 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2016-10-13 14:00:19 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2016-10-13 14:00:19 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2016-10-13 14:00:19 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2016-10-13 14:00:19 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2016-10-13 14:00:19 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2016-10-13 14:00:19 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2016-10-13 14:00:19 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2016-10-13 14:00:19 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2016-10-13 14:00:19 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2016-10-13 14:00:19 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2016-10-13 14:00:19 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2016-10-13 14:00:19 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2016-10-13 16:00:19.275 ThaliTest[2182:4432224] THREAD WARNING: ['JXcore'] took '6331.192139' ms. Plugin should use a background thread.
,2016-10-13 14:00:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-13 14:00:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/060692B6,-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-13 14:00:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-13 14:00:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/060692B6,-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-13 14:00:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-13 14:00:20 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/060692B6,-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-13 14:00:20 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/060692B6,-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-13 14:00:21 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/060692B6,-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-13 14:00:21 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-13 14:00:22 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/060692B6,-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-13 14:00:22 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-13 14:00:23 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/060692B6,-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-13 14:00:23 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-13 14:00:24 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/060692B6,-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-13 14:00:24 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-13 14:00:25 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/060692B6,-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-13 14:00:25 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-13 14:00:26 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/060692B6,-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-13 14:00:26 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-13 14:00:27 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/060692B6,-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-13 14:00:27 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/060692B6,-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-13 14:00:28 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/060692B6,-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-13 14:00:28 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-13 14:00:29 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/060692B6,-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-13 14:00:29 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-13 14:00:31 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/060692B6,-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-13 14:00:31 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-13 14:00:32 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/060692B6,-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-13 14:00:32 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-13 14:00:33 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/060692B6,-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-13 16:00:33.126 ThaliTest[2182:4432400] Error!: error is undefined
Stack:[{"_fileName":"/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js","_functionName":"Coordinated,Client.prototype._error","_lineNumber":"220","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:220:1"},{"_,fileName":"/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emi,tter.prototype.emit@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A,61B572ADF0/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/private/var/containers/Bundle/Application/060692B6-5F1B-4,4BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/mana,ger.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/socket,.io-client/lib/manager.js:81:7"},{"_fileName":"/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber,":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/private/var/,containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager,.prototype.reconnect/timer</<@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/private/var/containers/Bundle/Application/060692B6-5,F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/private/var/,containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www,/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/containers/Bundle/Application/060692B6-5F1B-4,4BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules,/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jx,core/node_modules/engine.io-client/lib/socket.js:670:3"}]
2016-10-13 14:00:33 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
    at CoordinatedClient.prototype._error@/private/var/,containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:220:1
    at Emitter.prototype.emit@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxco,re/node_modules/component-emitter/index.js:131:7
    at Socket.prototype.emit@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
    at Manager.protot,ype.emitAll@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
    at Manager.prototype.reconnect@/private/var/containers/Bundle/Application/060692B6-5,F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
    at Manager.prototype.reconnect/timer</<@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/nod,e_modules/socket.io-client/lib/manager.js:528:11
    at Manager.prototype.connect/errorSub<@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7
    at, Emitter.prototype.emit@/private/var/containers/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7
    at Socket.prototype.onError@/private/var/conta,iners/Bundle/Application/060692B6-5F1B-44BC-A1CF-1A61B572ADF0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3''
2016-10-13 14:00:33 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
TypeError: error is undefi
```
