#### Test 946263757280694_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/946263757280694/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/C0D7043A-964F-4393-B555-7E68023E0341/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/C0D7043A-964F-4393-B555-7E68023E0341/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/946263757280694/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/946263757280694/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56395"
,(lldb)     command script import "/tmp/C0D7043A-964F-4393-B555-7E68023E0341/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-21 07:23:40.448 ThaliTest[3843:8708346] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4AE07530-CE02-4F89-B0C3-2021006F18ED/Library/Cookies/Cookies.binarycookies
,2016-11-21 07:23:40.540 ThaliTest[3843:8708346] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-21 07:23:40.543 ThaliTest[3843:8708346] Multi-tasking -> Device: YES, App: YES
,2016-11-21 07:23:40.566 ThaliTest[3843:8708346] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-21 07:23:41.112 ThaliTest[3843:8708346] Using UIWebView
,2016-11-21 07:23:41.119 ThaliTest[3843:8708346] [CDVTimer][handleopenurl] 0.401020ms
,2016-11-21 07:23:41.127 ThaliTest[3843:8708346] [CDVTimer][intentandnavigationfilter] 7.192016ms
2016-11-21 07:23:41.128 ThaliTest[3843:8708346] [CDVTimer][gesturehandler] 0.308037ms
2016-11-21 07:23:41.128 ThaliTest[3843:8708346] [CDVTimer][TotalPluginStartup] 9.738028ms
,2016-11-21 07:23:47.074 ThaliTest[3843:8708346] Resetting plugins due to page load.
,2016-11-21 07:23:47.505 ThaliTest[3843:8708346] Finished load of: file:///var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/index.html
,2016-11-21 07:23:47.844 ThaliTest[3843:8708346] JXcore Cordova plugin initializing
,2016-11-21 07:23:47.845 ThaliTest[3843:8708530] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-21 15:23:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-21 15:23:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-21 15:23:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2016-11-21 15:23:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-21 15:23:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-21 15:23:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2016-11-21 15:23:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,Asynchronous wait failed: Exceeded timeout of 15 seconds, with unfulfilled expectations: "Advertiser's fake node server received a message". in file: Optional("<unknown>"), line: 0
,2016-11-21 15:24:38 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  115
Number of failed tests:  1
Number of ignored tests:  0
Total duration:  39.863097012043
Fai,led to execute UT.
2016-11-21 15:24:38 - DEBUG UnitTest_app: 'Failed to execute UT.'
2016-11-21 15:24:38 - DEBUG UnitTest_app: 'Unit Test app is loaded'
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForegroun,d wasn't registered
appEnteringBackground wasn't registered
,2016-11-21 15:24:38 - DEBUG UnitTest_app: 'My device name is: Apple-Iphone6-2'
2016-11-21 15:24:38 - WARN testUtils: 'myNameCallback not set!'
,2016-11-21 15:24:40 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: ios'
,2016-11-21 15:24:40 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2016-11-21 15:24:41 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2016-11-21 15:24:41 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2016-11-21 15:24:42 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2016-11-21 15:24:42 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2016-11-21 15:24:42 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2016-11-21 15:24:42 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2016-11-21 15:24:43 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2016-11-21 15:24:43 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2016-11-21 15:24:43 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2016-11-21 15:24:43 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2016-11-21 15:24:43 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2016-11-21 15:24:43 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2016-11-21 15:24:44 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2016-11-21 15:24:44 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2016-11-21 15:24:44 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2016-11-21 15:24:44 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2016-11-21 15:24:44 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2016-11-21 15:24:44 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2016-11-21 15:24:44 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2016-11-21 15:24:44 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2016-11-21 15:24:44 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2016-11-21 15:24:44 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2016-11-21 15:24:44 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2016-11-21 15:24:44 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2016-11-21 15:24:44 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2016-11-21 15:24:44 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2016-11-21 15:24:44 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2016-11-21 15:24:44 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2016-11-21 15:24:44 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2016-11-21 15:24:44 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2016-11-21 15:24:44 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2016-11-21 15:24:44 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2016-11-21 15:24:44 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2016-11-21 15:24:44 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2016-11-21 15:24:44 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2016-11-21 15:24:44 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2016-11-21 15:24:44 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2016-11-21 15:24:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/439A350F,-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-11-21 15:24:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/439A350F,-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-11-21 15:24:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/439A350F,-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-11-21 15:24:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/439A350F,-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-11-21 15:24:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 15:24:46 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/439A350F,-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-11-21 15:24:46 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 15:24:47 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/439A350F,-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-11-21 15:24:47 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 15:24:48 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/439A350F,-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-11-21 15:24:48 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 15:24:49 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/439A350F,-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-11-21 15:24:49 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 15:24:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/439A350F,-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-11-21 15:24:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 15:24:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/439A350F,-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-11-21 15:24:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/439A350F,-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-11-21 15:24:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/439A350F,-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-11-21 15:24:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-21 15:24:54 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2016-11-21 15:24:54 - DEBUG CoordinatedClient: 'connected to the test server'
,2016-11-21 15:24:54 - ERROR CoordinatedClient: 'device disqualified from the test server, reason: 'Native unit tests failed''
,2016-11-21 15:24:54 - DEBUG CoordinatedClient: 'test client failed'
2016-11-21 15:24:54 - DEBUG CoordinatedClient: 'device disconnected from the test server'
2016-11-21 15:24:54 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: Test client fail,ed: Native unit tests failed', stack: 'CoordinatedClient.prototype._disqualify/<@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:187:20
tryCatcher@/private/var/containers/Bu,ndle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E,35A199842/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
module.exports/Promise.prototype._settlePromise@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/bl,u,ebird/js/release/promise.js:567:13
module.exports/Promise.prototype._settlePromise0@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
module.exports/,Promise.prototype._settlePromises@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13''
2016-11-21 15:24:54 - DEBUG CoordinatedThaliTape: '****TEST_LOG,GER:[PROCESS_ON_EXIT_FAILED]****'
2016-11-21 15:24:54 - ERROR runTests: 'Test client failed: Native unit tests failed
CoordinatedClient.prototype._disqualify/<@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/,www/jxcore/lib/CoordinatedClient.js:187:20
tryCatcher@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
module.exports/Promise.prototype._settlePromise,F,romHandler@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
module.exports/Promise.prototype._settlePromise@/private/var/containers/Bundle/Applicati,on/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:567:13
module.exports/Promise.prototype._settlePromise0@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.,app/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
module.exports/Promise.prototype._settlePromises@/private/var/containers/Bundle/Application/439A350F-C392-4443-8F31-94E35A199842/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13'

```
