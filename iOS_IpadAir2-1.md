#### Test 87998460d34ccd7_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/87998460d34ccd7/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/2CE734E4-D7F2-437E-96AD-81D5F8B2C304/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/2CE734E4-D7F2-437E-96AD-81D5F8B2C304/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/87998460d34ccd7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/87998460d34ccd7/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52433"
,(lldb)     command script import "/tmp/2CE734E4-D7F2-437E-96AD-81D5F8B2C304/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-10-05 02:44:42.524 ThaliTest[3816:7015957] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/BA75B32F-7297-4BE8-87DE-68DF53292719/Library/Cookies/Cookies.binarycookies
,2016-10-05 02:44:42.850 ThaliTest[3816:7015957] Apache Cordova native platform version 4.2.1 is starting.
,2016-10-05 02:44:42.851 ThaliTest[3816:7015957] Multi-tasking -> Device: YES, App: YES
,2016-10-05 02:44:42.867 ThaliTest[3816:7015957] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-10-05 02:44:44.827 ThaliTest[3816:7015957] Using UIWebView
,2016-10-05 02:44:44.834 ThaliTest[3816:7015957] [CDVTimer][handleopenurl] 0.325978ms
,2016-10-05 02:44:44.841 ThaliTest[3816:7015957] [CDVTimer][intentandnavigationfilter] 6.415009ms
2016-10-05 02:44:44.841 ThaliTest[3816:7015957] [CDVTimer][gesturehandler] 0.329018ms
2016-10-05 02:44:44.842 ThaliTest[3816:7015957] [CDVTimer][TotalPluginStartup] 8.652985ms
,2016-10-05 02:44:52.325 ThaliTest[3816:7015957] Resetting plugins due to page load.
,2016-10-05 02:44:55.912 ThaliTest[3816:7015957] Finished load of: file:///var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/index.html
,2016-10-05 02:44:56.121 ThaliTest[3816:7015957] JXcore Cordova plugin initializing
,2016-10-05 02:44:56.122 ThaliTest[3816:7016220] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-10-05 00:45:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-10-05 00:45:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-10-05 00:45:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-10-05 00:45:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-10-05 00:45:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,received session: <ThaliCore.Session: 0x1477e98e0>
,Asynchronous wait failed: Exceeded timeout of 2 seconds, with unfulfilled expectations: "connected to peer identifier". in file: Optional("<unknown>"), line: 0
,Asynchronous wait failed: Exceeded timeout of 2 seconds, with unfulfilled expectations: "connected to peer identifier". in file: Optional("<unknown>"), line: 0
,Optional("3B1CE08C-AF4D-4C85-BF15-7B838AF2E2CB")
,nil
,nil
,Optional("871EA070-9015-43E1-81F7-25D9E09DFDEC")
,Optional("E7B85ABC-6B0E-49D4-83CA-F5A4A25C46D2")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-10-05 00:45:24 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  56
,Number of passed tests:  54
Number of failed tests:  2
,Number of ignored tests:  0
,Total duration:  18.97196501493454
Failed to execute UT.
,2016-10-05 00:45:24 - DEBUG UnitTest_app: 'Failed to execute UT.'
,2016-10-05 00:45:24 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,2016-10-05 00:45:25 - DEBUG UnitTest_app: 'My device name is: Apple-IpadAir2-1'
,2016-10-05 00:45:25 - WARN testUtils: 'myNameCallback not set!'
,2016-10-05 00:45:25 - DEBUG UnitTest_app: 'Running for WIFI network type'
,2016-10-05 00:45:26 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2016-10-05 00:45:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2016-10-05 00:45:27 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2016-10-05 00:45:28 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2016-10-05 00:45:28 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2016-10-05 00:45:28 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2016-10-05 00:45:28 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2016-10-05 00:45:29 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2016-10-05 00:45:29 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2016-10-05 00:45:29 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2016-10-05 00:45:29 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2016-10-05 00:45:29 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2016-10-05 00:45:29 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2016-10-05 00:45:29 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2016-10-05 00:45:29 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2016-10-05 00:45:29 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2016-10-05 00:45:29 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2016-10-05 00:45:29 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2016-10-05 00:45:29 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2016-10-05 00:45:29 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2016-10-05 00:45:29 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2016-10-05 00:45:30 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2016-10-05 00:45:30 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2016-10-05 00:45:30 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2016-10-05 00:45:30 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2016-10-05 00:45:30 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2016-10-05 00:45:30 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2016-10-05 00:45:30 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2016-10-05 00:45:30 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2016-10-05 00:45:30 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2016-10-05 00:45:30 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2016-10-05 00:45:30 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2016-10-05 00:45:30 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2016-10-05 00:45:30 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2016-10-05 00:45:30 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2016-10-05 02:45:30.193 ThaliTest[3816:7015957] THREAD WARNING: ['JXcore'] took '5440.173828' ms. Plugin should use a background thread.
,2016-10-05 00:45:30 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-05 00:45:30 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-05 00:45:30 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-05 00:45:31 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-05 00:45:31 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-05 00:45:31 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-05 00:45:31 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-05 00:45:32 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-05 00:45:32 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-05 00:45:33 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-05 00:45:33 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-05 00:45:34 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-05 00:45:34 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-05 00:45:35 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-05 00:45:35 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-05 00:45:36 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-05 00:45:36 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-05 00:45:37 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-05 00:45:37 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-05 00:45:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-05 00:45:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-05 00:45:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-05 00:45:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-05 00:45:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-05 00:45:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-05 00:45:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-05 00:45:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-05 00:45:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-05 00:45:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-05 00:45:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-10-05 02:45:44.393 ThaliTest[3816:7016220] Error!: error is undefined
Stack:[{"_fileName":"/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js","_functionName":"Coor,dinatedClient.prototype._error","_lineNumber":"220","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/lib/CoordinatedClient.,js:220:1"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":",7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/App,lication/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/private/var/mobile/Con,tainers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/,www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D,55688EB9F13/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager,.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modul,es/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconn,ect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/man,ager.js:528:11"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber",:"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":,"/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNum,ber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/priv,ate/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket,.prototype.onError@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
2016-10-05 00:45:44 - ERROR TestsProcess: 'uncaught exception, error: ',TypeError: error is undefined', stack: 'TypeError: error is undefined
    at CoordinatedClient.prototype._error@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:220:1,
    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7
    at Socket.prototype.emit@/private/var/mobile/Containers/Bundle,/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
    at Manager.prototype.emitAll@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.,app/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
    at Manager.prototype.reconnect@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.j,s:507:5
    at Manager.prototype.reconnect/timer</<@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
    at Manager.prototype.connect/error,Sub<@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7
    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/186C98E,F-9282-45B0-AFBB-D55688EB9F13/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7
    at Socket.prototype.onError@/private/var/mobile/Containers/Bundle/Application/186C98EF-9282-45B0-AFBB-D55688EB9F13/Thali,Test.app/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3''
2016-10-05 00:45:44 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
TypeError: error is undefined (/private/var/mobile/Containers/Bundle/Application/186C98EF-928
```
