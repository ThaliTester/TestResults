#### Test 884969639726768_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/884969639726768/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/2C539119-241B-47E3-B038-C5ECFF08CEA3/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/2C539119-241B-47E3-B038-C5ECFF08CEA3/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/884969639726768/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/884969639726768/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51676"
,(lldb)     command script import "/tmp/2C539119-241B-47E3-B038-C5ECFF08CEA3/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-14 17:55:21.741 ThaliTest[2382:4174460] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/62C8E2AE-F643-4B50-AAE4-DD58D79AC714/Library/Cookies/Cookies.binarycookies
,2016-10-14 17:55:21.826 ThaliTest[2382:4174460] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-14 17:55:21.829 ThaliTest[2382:4174460] Multi-tasking -> Device: YES, App: YES
,2016-10-14 17:55:21.852 ThaliTest[2382:4174460] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-14 17:55:22.360 ThaliTest[2382:4174460] Using UIWebView
,2016-10-14 17:55:22.367 ThaliTest[2382:4174460] [CDVTimer][handleopenurl] 0.365973ms
,2016-10-14 17:55:22.376 ThaliTest[2382:4174460] [CDVTimer][intentandnavigationfilter] 8.601010ms
2016-10-14 17:55:22.377 ThaliTest[2382:4174460] [CDVTimer][gesturehandler] 0.304997ms
2016-10-14 17:55:22.378 ThaliTest[2382:4174460] [CDVTimer][TotalPluginS,tartup] 10.950029ms
,2016-10-14 17:55:28.241 ThaliTest[2382:4174460] Resetting plugins due to page load.
,2016-10-14 17:55:28.778 ThaliTest[2382:4174460] Finished load of: file:///var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/index.html
,2016-10-14 17:55:29.141 ThaliTest[2382:4174460] JXcore Cordova plugin initializing
,2016-10-14 17:55:29.142 ThaliTest[2382:4174623] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-15 00:55:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-15 00:55:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-15 00:55:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-10-15 00:55:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-15 00:55:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/AdvertiserRelayTests.swift"), line: 95
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/BrowserRelayTests.swift"), line: 204
,XCTAssertTrue failed -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/RelayTests.swift"), line: 103
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-10-15 00:56:06 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  104
Number of passed tests:  101
Number of failed tests:  3
Number of ignored tests:  0
Total duration:  27.27717101573944
F,ailed to execute UT.
2016-10-15 00:56:06 - DEBUG UnitTest_app: 'Failed to execute UT.'
2016-10-15 00:56:06 - DEBUG UnitTest_app: 'Unit Test app is loaded'
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForegro,und wasn't registered
appEnteringBackground wasn't registered
,2016-10-15 00:56:07 - DEBUG UnitTest_app: 'My device name is: Apple-Iphone6-2'
2016-10-15 00:56:07 - WARN testUtils: 'myNameCallback not set!'
2016-10-15 00:56:07 - DEBUG UnitTest_app: 'Running for NATIVE network type'
,2016-10-15 00:56:09 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2016-10-15 00:56:10 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2016-10-15 00:56:10 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2016-10-15 00:56:11 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2016-10-15 00:56:11 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2016-10-15 00:56:11 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2016-10-15 00:56:11 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2016-10-15 00:56:12 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2016-10-15 00:56:12 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2016-10-15 00:56:12 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2016-10-15 00:56:12 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2016-10-15 00:56:12 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2016-10-15 00:56:12 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2016-10-15 00:56:12 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2016-10-15 00:56:12 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2016-10-15 00:56:12 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2016-10-15 00:56:12 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2016-10-15 00:56:13 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2016-10-15 00:56:13 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2016-10-15 00:56:13 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2016-10-15 00:56:13 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2016-10-15 00:56:13 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2016-10-15 00:56:13 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2016-10-15 00:56:13 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2016-10-15 00:56:13 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2016-10-15 00:56:13 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2016-10-15 00:56:13 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2016-10-15 00:56:13 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2016-10-15 00:56:13 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2016-10-15 00:56:13 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2016-10-15 00:56:13 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2016-10-15 00:56:13 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2016-10-15 00:56:13 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2016-10-15 00:56:13 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2016-10-15 00:56:13 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2016-10-15 00:56:13 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2016-10-15 00:56:13 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2016-10-14 17:56:13.333 ThaliTest[2382:4174460] THREAD WARNING: ['JXcore'] took '6332.032959' ms. Plugin should use a background thread.
,2016-10-15 00:56:13 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-15 00:56:13 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/53A3AA5B,-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-15 00:56:13 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/53A3AA5B,-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-15 00:56:14 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/53A3AA5B,-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-15 00:56:14 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-15 00:56:14 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/53A3AA5B,-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-15 00:56:14 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/53A3AA5B,-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-15 00:56:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/53A3AA5B,-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-15 00:56:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-15 00:56:16 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/53A3AA5B,-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-15 00:56:16 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-15 00:56:18 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/53A3AA5B,-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-15 00:56:18 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/53A3AA5B,-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-15 00:56:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/53A3AA5B,-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-15 00:56:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-15 00:56:20 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/53A3AA5B,-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-15 00:56:20 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-15 00:56:21 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/53A3AA5B,-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-15 00:56:21 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-15 00:56:22 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/53A3AA5B,-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-15 00:56:22 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/53A3AA5B,-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-15 00:56:23 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/53A3AA5B,-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-15 00:56:23 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-15 00:56:24 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/53A3AA5B,-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-10-15 00:56:24 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-15 00:56:25 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/53A3AA5B,-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-15 00:56:25 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/53A3AA5B,-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-15 00:56:26 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/53A3AA5B,-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-15 00:56:26 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/53A3AA5B,-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-15 00:56:27 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/53A3AA5B,-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-10-14 17:56:27.470 ThaliTest[2382:4174623] Error!: error is undefined
Stack:[{"_fileName":"/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js","_functionName":"Coordinated,Client.prototype._error","_lineNumber":"220","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:220:1"},{"_,fileName":"/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emi,tter.prototype.emit@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C,6,89C38C9920/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/private/var/containers/Bundle/Application/53A3AA5B-9893-4,FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/mana,ger.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/socket,.io-client/lib/manager.js:81:7"},{"_fileName":"/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumbe,r,":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/private/var/,containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager,.prototype.reconnect/timer</<@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/private/var/containers/Bundle/Application/53A3AA5B-9,893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/private/var,/,containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www,/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/containers/Bundle/Application/53A3AA5B-9893-4,FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules,/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/j,x,core/node_modules/engine.io-client/lib/socket.js:670:3"}]
,2016-10-15 00:56:27 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
    at CoordinatedClient.prototype._error@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C,38C9920/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:220:1
    at Emitter.prototype.emit@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7
    at So,cket.prototype.emit@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
    at Manager.prototype.emitAll@/private/var/containers/Bundle/Application/53A3,AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
    at Manager.prototype.reconnect@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_mo,dules/socket.io-client/lib/manager.js:507:5
    at Manager.prototype.reconnect/timer</<@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
    at Ma,nager.prototype.connect/errorSub<@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7
    at Emitter.prototype.emit@/private/var/containers/Bundle/Appl,ication/53A3AA5B-9893-4FA2-88D4-C689C38C9920/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7
    at Socket.prototype.onError@/private/var/containers/Bundle/Application/53A3AA5B-9893-4FA2-88D4-C689C38C99,20/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3''
2016-10-15 00:56:27 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
TypeError: error is undefined (/private/var/containers/Bundle/Application/53A3AA5B-98
```
