#### Test 931424420cf4179_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/931424420cf4179/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/0ABCB6B6-0CDF-40B2-A72F-EA9CEDCAA3C7/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/0ABCB6B6-0CDF-40B2-A72F-EA9CEDCAA3C7/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/931424420cf4179/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/931424420cf4179/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49843"
,(lldb)     command script import "/tmp/0ABCB6B6-0CDF-40B2-A72F-EA9CEDCAA3C7/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-21 14:28:39.002 ThaliTest[6074:15503432] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FCADE99D-4775-4040-AAE7-10DD754359B9/Library/Cookies/Cookies.binarycookies
,2016-11-21 14:28:39.118 ThaliTest[6074:15503432] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-21 14:28:39.120 ThaliTest[6074:15503432] Multi-tasking -> Device: YES, App: YES
,2016-11-21 14:28:39.143 ThaliTest[6074:15503432] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-21 14:28:40.700 ThaliTest[6074:15503432] Using UIWebView
,2016-11-21 14:28:40.709 ThaliTest[6074:15503432] [CDVTimer][handleopenurl] 0.841022ms
,2016-11-21 14:28:40.717 ThaliTest[6074:15503432] [CDVTimer][intentandnavigationfilter] 8.115947ms
2016-11-21 14:28:40.718 ThaliTest[6074:15503432] [CDVTimer][gesturehandler] 0.396013ms
2016-11-21 14:28:40.719 ThaliTest[6074:15503432] [CDVTimer][TotalPlug,inStartup] 11.258960ms
,2016-11-21 14:28:46.709 ThaliTest[6074:15503432] Resetting plugins due to page load.
,2016-11-21 14:28:50.273 ThaliTest[6074:15503432] Finished load of: file:///var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/index.html
,2016-11-21 14:28:50.592 ThaliTest[6074:15503432] JXcore Cordova plugin initializing
,2016-11-21 14:28:50.593 ThaliTest[6074:15503675] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-21 13:29:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-21 13:29:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-21 13:29:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2016-11-21 13:29:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-21 13:29:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-21 13:29:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-21 13:29:27 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  24.31532001495361
,2016-11-21 13:29:27 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,2016-11-21 13:29:28 - DEBUG UnitTest_app: 'My device name is: Apple-Iphone5s-1'
2016-11-21 13:29:28 - WARN testUtils: 'myNameCallback not set!'
,2016-11-21 13:29:31 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: ios'
,2016-11-21 13:29:31 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2016-11-21 13:29:31 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2016-11-21 13:29:31 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2016-11-21 13:29:33 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2016-11-21 13:29:33 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2016-11-21 13:29:33 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2016-11-21 13:29:33 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2016-11-21 13:29:34 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2016-11-21 13:29:34 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2016-11-21 13:29:34 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2016-11-21 13:29:34 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2016-11-21 13:29:34 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2016-11-21 13:29:34 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2016-11-21 13:29:35 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2016-11-21 13:29:35 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2016-11-21 13:29:35 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2016-11-21 13:29:35 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2016-11-21 13:29:35 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2016-11-21 13:29:35 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2016-11-21 13:29:35 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2016-11-21 13:29:35 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2016-11-21 13:29:35 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2016-11-21 13:29:35 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2016-11-21 13:29:35 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2016-11-21 13:29:35 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2016-11-21 13:29:35 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2016-11-21 13:29:35 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2016-11-21 13:29:35 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2016-11-21 13:29:35 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2016-11-21 13:29:35 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2016-11-21 13:29:35 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2016-11-21 13:29:35 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2016-11-21 13:29:35 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2016-11-21 13:29:35 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2016-11-21 13:29:35 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2016-11-21 13:29:35 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2016-11-21 13:29:35 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2016-11-21 13:29:35 - INFO runTests: 'Test runner loading file: /private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2016-11-21 14:29:35.691 ThaliTest[6074:15503432] THREAD WARNING: ['JXcore'] took '7702.260010' ms. Plugin should use a background thread.
,2016-11-21 13:29:35 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:36 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:36 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:37 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:37 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:47 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:47 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:49 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:49 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:29:54 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2016-11-21 13:29:54 - DEBUG CoordinatedClient: 'connected to the test server'
,2016-11-21 13:34:55 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2016-11-21 13:34:56 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:34:56 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:34:56 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:34:56 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:34:57 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:34:57 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:34:58 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:34:58 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:34:59 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:34:59 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:35:00 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:35:00 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:35:01 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:35:01 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:35:02 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:35:02 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:35:03 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:35:03 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:35:04 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:35:04 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:35:05 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:35:05 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:35:06 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:35:06 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:35:07 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:35:07 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:35:09 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:35:09 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 13:35:10 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.,addEventListeners/this.ws.onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/mobile/Containers/Bundle,/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/,node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 14:35:10.129 ThaliTest[6074:15503675] Error!: error is undefined
Stack:[{"_fileName":"/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js","_functionName":"Coo,rdinatedClient.prototype._error","_lineNumber":"223","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/lib/CoordinatedClient,.js:223:1"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":,"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Ap,plication/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/private/var/mobile/Co,ntainers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app,/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-,329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manage,r.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modu,les/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.recon,nect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/ma,nager.js:528:11"},{"_fileName":"/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber,":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName",:"/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNu,mber":"7","_msg":"    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/pri,vate/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socke,t.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
2016-11-21 13:35:10 - ERROR TestsProcess: 'uncaught exception, error: ,'TypeError: error is undefined', stack: 'TypeError: error is undefined
    at CoordinatedClient.prototype._error@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:223:1,
    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7
    at Socket.prototype.emit@/private/var/mobile/Containers/Bundl,e/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
    at Manager.prototype.emitAll@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest,.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
    at Manager.prototype.reconnect@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.,js:507:5
    at Manager.prototype.reconnect/timer</<@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
    at Manager.prototype.connect/erro,rSub<@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7
    at Emitter.prototype.emit@/private/var/mobile/Containers/Bundle/Application/56E569,DF-F46A-4924-8684-329A7332CDCF/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7
    at Socket.prototype.onError@/private/var/mobile/Containers/Bundle/Application/56E569DF-F46A-4924-8684-329A7332CDCF/Thal,iTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3''
2016-11-21 13:35:10 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
TypeError: error is undefined (/private/var/mobile/Containers/Bundle/Application/56E569DF-F4
```
