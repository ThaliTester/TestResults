#### Test 931424420ae5e52_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/931424420ae5e52/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/19B003C1-2D29-415A-A919-7518FBA73229/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/19B003C1-2D29-415A-A919-7518FBA73229/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/931424420ae5e52/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/931424420ae5e52/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49571"
,(lldb)     command script import "/tmp/19B003C1-2D29-415A-A919-7518FBA73229/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-22 12:56:15.948 ThaliTest[3880:9863314] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/80ACF499-4D01-48CE-B6AA-6839313CA9D3/Library/Cookies/Cookies.binarycookies
,2016-11-22 12:56:15.993 ThaliTest[3880:9863314] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-22 12:56:15.994 ThaliTest[3880:9863314] Multi-tasking -> Device: YES, App: YES
,2016-11-22 12:56:16.007 ThaliTest[3880:9863314] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-22 12:56:16.356 ThaliTest[3880:9863314] Using UIWebView
,2016-11-22 12:56:16.361 ThaliTest[3880:9863314] [CDVTimer][handleopenurl] 0.334024ms
,2016-11-22 12:56:16.366 ThaliTest[3880:9863314] [CDVTimer][intentandnavigationfilter] 4.673004ms
2016-11-22 12:56:16.367 ThaliTest[3880:9863314] [CDVTimer][gesturehandler] 0.203013ms
2016-11-22 12:56:16.367 ThaliTest[3880:9863314] [CDVTimer][TotalPluginStartup] 6.287992ms
,2016-11-22 12:56:21.607 ThaliTest[3880:9863314] Resetting plugins due to page load.
,2016-11-22 12:56:21.894 ThaliTest[3880:9863314] Finished load of: file:///var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/index.html
,2016-11-22 12:56:22.241 ThaliTest[3880:9863314] JXcore Cordova plugin initializing
,2016-11-22 12:56:22.241 ThaliTest[3880:9863495] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-22 11:56:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-22 11:56:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-22 11:56:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2016-11-22 11:56:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-22 11:56:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-22 11:56:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-11-22 11:56:55 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  22.8320620059967
,2016-11-22 11:56:55 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
,2016-11-22 11:56:56 - DEBUG UnitTest_app: 'My device name is: Apple-Iphone6-1'
,2016-11-22 11:56:56 - WARN testUtils: 'myNameCallback not set!'
,2016-11-22 11:56:57 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: ios'
,2016-11-22 11:56:57 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2016-11-22 11:56:58 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2016-11-22 11:56:58 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2016-11-22 11:56:59 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2016-11-22 11:56:59 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2016-11-22 11:56:59 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2016-11-22 11:56:59 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2016-11-22 11:57:00 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2016-11-22 11:57:00 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2016-11-22 11:57:00 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2016-11-22 11:57:00 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2016-11-22 11:57:00 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2016-11-22 11:57:00 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2016-11-22 11:57:01 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2016-11-22 11:57:01 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2016-11-22 11:57:01 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2016-11-22 11:57:01 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2016-11-22 11:57:01 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2016-11-22 11:57:01 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2016-11-22 11:57:01 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2016-11-22 11:57:01 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2016-11-22 11:57:01 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2016-11-22 11:57:01 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2016-11-22 11:57:01 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2016-11-22 11:57:01 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2016-11-22 11:57:01 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2016-11-22 11:57:01 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2016-11-22 11:57:01 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2016-11-22 11:57:01 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2016-11-22 11:57:01 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2016-11-22 11:57:01 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2016-11-22 11:57:01 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2016-11-22 11:57:01 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2016-11-22 11:57:01 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2016-11-22 11:57:01 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2016-11-22 11:57:01 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2016-11-22 11:57:01 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2016-11-22 11:57:01 - INFO runTests: 'Test runner loading file: /private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2016-11-22 12:57:01.524 ThaliTest[3880:9863314] THREAD WARNING: ['JXcore'] took '5578.852783' ms. Plugin should use a background thread.
,2016-11-22 11:57:01 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-11-22 11:57:02 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3529F0CE,-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-11-22 11:57:02 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3529F0CE,-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-22 11:57:02 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3529F0CE,-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-22 11:57:02 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3529F0CE,-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-22 11:57:03 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3529F0CE,-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-11-22 11:57:03 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transp,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-22 11:57:04 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3529F0CE,-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-11-22 11:57:04 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3529F0CE,-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-11-22 11:57:05 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3529F0CE,-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-22 11:57:05 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3529F0CE,-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-22 11:57:06 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3529F0CE,-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-22 11:57:06 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3529F0CE,-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-22 11:57:07 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3529F0CE,-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-11-22 11:57:07 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transp,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-22 11:57:08 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3529F0CE,-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-11-22 11:57:08 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3529F0CE,-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-22 11:57:10 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3529F0CE,-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-11-22 11:57:10 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3529F0CE,-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-22 11:57:11 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3529F0CE,-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-11-22 11:57:11 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transp,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-22 11:57:12 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3529F0CE,-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-11-22 11:57:12 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3529F0CE,-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-22 11:57:13 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-11-22 11:57:13 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3529F0CE,-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-11-22 11:57:14 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3529F0CE,-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-11-22 11:57:14 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/trans,p,ort.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/cont,ainers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/j,xcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1'
,2016-11-22 11:57:16 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3529F0CE,-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-11-22 11:57:16 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEven,tListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3529F0CE,-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
,2016-11-22 11:57:17 - ERROR CoordinatedClient: ' Transport.prototype.onError@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3529F0CE,-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocke,t.js:686:5
emit@events.js:82:1'
2016-11-22 12:57:17.355 ThaliTest[3880:9863495] Error!: error is undefined
Stack:[{"_fileName":"/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/lib/CoordinatedClien,t.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"223","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/li,b/CoordinatedClient.js:223:1"},{"_fileName":"/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_co,lumnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/private/var/containers/Bundle/Appl,ication/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/private/var/containers/,Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node,_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.,app/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager,.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:,5,07:5"},{"_fileName":"/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnN,umber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/private/var/contai,ners/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototy,pe.connect/errorSub<@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-,9,A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/private/var/containers/,Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/Tha,liTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69,-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,2016-11-22 11:57:17 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
    at CoordinatedClient.prototype._error@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0,C3DF9E3/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:223:1
    at Emitter.prototype.emit@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7
    at So,cket.prototype.emit@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
    at Manager.prototype.emitAll@/private/var/containers/Bundle/Application/3529,F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
    at Manager.prototype.reconnect@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_mo,dules/socket.io-client/lib/manager.js:507:5
    at Manager.prototype.reconnect/timer</<@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
    at Ma,nager.prototype.connect/errorSub<@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7
    at Emitter.prototype.emit@/private/var/containers/Bundle/Appl,ication/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7
    at Socket.prototype.onError@/private/var/containers/Bundle/Application/3529F0CE-48C2-44D0-9A69-5CFA0C3DF9,E3/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3''
2016-11-22 11:57:17 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
