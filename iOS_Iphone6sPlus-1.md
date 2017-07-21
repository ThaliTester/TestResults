#### Test 113351851f8c1845_iOS_Iphone6sPlus-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/113351851f8c1845/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/B21EE332-A347-41E6-8BE7-FE741734DD58/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'
,Executing commands in '/tmp/B21EE332-A347-41E6-8BE7-FE741734DD58/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/113351851f8c1845/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/113351851f8c1845/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60740"
,(lldb)     command script import "/tmp/B21EE332-A347-41E6-8BE7-FE741734DD58/fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.py"
,(lldb)     command script add -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-07-21 10:51:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:51:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:51:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:51:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 10:51:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:51:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:51:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "37C1375D-6C65-4F25-82,64-C681E475859F", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:37C1375D-6C65-4F25-8264-C681E475859F
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2FEFF8FB-15BE-49BB-A7F4-374E7A3CC63B
[ThaliCore] Browser,.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8AFFA3C3-,3EA0-4B3D-9997-B0B2869C3FD8
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E056C607-1169-46EB-A6E6-6142B7798FE3", generation: 0)
[ThaliCore] Advertiser.startAdvertisi,ng with peerID:E056C607-1169-46EB-A6E6-6142B7798FE3
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E056C607-1169-46EB-A6E6-6142B7798FE3:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E056C607-1169-46EB-A6E6-6142B7798FE3", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCorrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-07-21 10:51:58 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
,Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.606982111930847
,2017-07-21 10:51:58 - DEBUG UnitTest_app: 'My device name is: 'Apple-Iphone6sPlus-1''
,2017-07-21 10:51:58 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:E056C607-1169-46EB-A6E6-6142B7798FE3:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "E056C607-1169-46EB-A6E6-6142B7798FE3", generation: 0)
,2017-07-21 10:52:00 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-21 10:52:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-21 10:52:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-21 10:52:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-21 10:52:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-21 10:52:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-21 10:52:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-21 10:52:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-21 10:52:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-21 10:52:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-21 10:52:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-21 10:52:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-21 10:52:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-21 10:52:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-21 10:52:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-21 10:52:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-21 10:52:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-21 10:52:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-21 10:52:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-21 10:52:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-21 10:52:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-21 10:52:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-21 10:52:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-21 10:52:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-21 10:52:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-21 10:52:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-21 10:52:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-21 10:52:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-21 10:52:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-21 10:52:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-21 10:52:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-21 10:52:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-21 10:52:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-21 10:52:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-21 10:52:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-21 10:52:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-21 10:52:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-21 10:52:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-21 10:52:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-21 10:52:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-21 10:52:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-21 10:52:01 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-21 10:52:01 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-21 10:52:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 10:52:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 10:52:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 10:52:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 10:52:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 10:52:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 10:52:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 10:52:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 10:52:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 10:52:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 10:52:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 10:52:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 10:52:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 10:53:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 10:53:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 10:53:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 10:53:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 10:53:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 10:53:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 10:53:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 10:53:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 10:53:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 10:53:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 10:53:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 10:53:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 10:54:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 10:54:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 10:54:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 10:54:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 10:54:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 10:54:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 10:54:31 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-07-21 10:54:31 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-21 10:54:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 1 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll with promise
,2017-07-21 10:54:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-21 10:54:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-07-21 10:54:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-07-21 10:54:42 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-07-21 10:54:42 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-07-21 10:54:43 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-07-21 10:54:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
,# teardown
,# setup
,# test defaultDirectory
,ok 4 should be equal
ok 5 should be equal
ok 6 should be equal
# teardown
,# setup
,# test defaultAdapter
,ok 7 should be equal
,ok 8 should be equal
ok 9 should be equal
ok 10 should be equal
ok 11 should be equal
ok 12 should be equal
ok 13 should be equal
ok 14 should be equal
,# teardown
,# setup
,# enqueue and run in order
,ok 15 firstPromise setTimeout
ok 16 firstPromise result
ok 17 firstPromise testValue
,ok 18 secondPromise setTimeout
ok 19 secondPromise result
ok 20 secondPromise testValue
ok 21 thirdPromise in promise
ok 22 thirdPromise result
ok 23 thirdPromise testValue
# teardown
,# setup
,# enqueueAtTop and run backwards
,ok 24 thirdPromise - first to run
ok 25 thirdPromise - in resolve
,ok 26 secondPromise - second to run
ok 27 secondPromise - in catch
ok 28 firstPromise - third to run
ok 29 firstPromise - in then
ok 30 testing promises
,# teardown
,# setup
,# mix enqueue and enqueueAtTop
,ok 31 fourth
ok 32 fourth
,ok 33 second
ok 34 secondPromise - in then
,ok 35 first
ok 36 firstPromise - in catch
ok 37 third
ok 38 thirdPromise - in then
ok 39 testingPromises
# teardown
,# setup
,# queues handled independently
,ok 40 all short operations completed before the long resolves
# teardown
,# setup
,# enqueued function are always executed asynchronously
,ok 41 executor is not called here
ok 42 executors is called
,# teardown
,# setup
,# exceptions in the executor are properly handled
,ok 43 got expected error
,# teardown
,# setup
,# basic
,ok 44 sane
,# teardown
,# setup
,# another
,ok 45 sane
,# teardown
,# setup
,# skip
,2017-07-21 10:54:51 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-07-21 10:54:56 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-07-21 10:54:57 - DEBUG testTests: 'test spy method for global sinon sansbox'
ok 46 test sandbox spy works correctly
,# teardown
,# setup
,# test sinon sansbox stub
,ok 47 test sandbox stub works correctly
,# teardown
,# setup
,# test sinon sansbox stub override
,ok 48 test sandbox stub works correctly
,# teardown
,# setup
,# test sinon sansbox mock
,# teardown
,# setup
,# test sinon sansbox restore after test end
,ok 49 test restore
,# teardown
,# setup
,# can pass data in setup
,ok 50 test participant has uuid
ok 51 participant data matches
,ok 52 test participant has uuid
ok 53 participant data matches
ok 54 test participant has uuid
ok 55 participant data matches
ok 56 own UUID is found from the participants list
,# teardown
,# setup
,# Correctly parses/stringifies USN
,ok 57 correctly parses USN string
,ok 58 throws if usn has invalid prefix
ok 59 throws if usn has invalid identifier format
ok 60 throws if usn has invalid generation
ok 61 correctly stringifies peer
,# teardown
,# setup
,# onPeerLost calls jxcore
,2017-07-21 10:55:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-21 10:55:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:55:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:55:15 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:55:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 10:55:15 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 10:55:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 10:55:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 10:55:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-21 10:55:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-21 10:55:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:55:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:55:15 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:55:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 10:55:15 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 10:55:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 10:55:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 10:55:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4CFC8FB6-C778-413E-A14A-D88597661F11
[ThaliCore] Browser.startListening
,2017-07-21 10:55:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 10:55:16 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:55:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 10:55:16 - DEBUG thaliMobileNativeWrapper: 'disco,veryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:55:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without e,r,ror
# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:55:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:55:16 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:55:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
,2017-07-21 10:55:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 10:55:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:55:16 - DEBUG thaliMo,bileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:55:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:55:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 10:55:16 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 10:55:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 10:55:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 10:55:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C5092825-B7F4-41A8-A00D-695F57245277
[ThaliCore] Browser.startListening
,2017-07-21 10:55:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 10:55:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:55:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 64 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-21 10:55:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"di,scoveryActive":true,"advertisingActive":false}'
2017-07-21 10:55:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":",B,OTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:55:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 10:55:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21, 10:55:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:55:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-07-21 10:55:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:55:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:55:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:55:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:55:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 10:55:24 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 10:55:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 10:55:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 10:55:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:55:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:55:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:55:25 - ,DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:55:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call sto,pListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:55:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:55:25 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:55:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 10:55:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:55:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:55:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:55:25 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:55:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:55:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:55:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:55:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:55:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6D695ECB-CB77-4C18-9E63-A06861836C7D", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:6D695ECB-CB77-4C18-9E63-A06861836C7D
,2017-07-21 10:55:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:55:29 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:55:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:6D695ECB-CB77-4C18-9E63-A06861836C7D
2017-07-21 10:55:29 ,- DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:55:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Can call ,s,topAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:55:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:55:29 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:55:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 10:55:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:55:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:55:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:55:29 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:55:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:55:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:55:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:55:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:55:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C7A93B7B-719D-4225-923D-46FBFA6F0980", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:C7A93B7B-719D-4225-923D-46FBFA6F0980
,2017-07-21 10:55:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:55:30 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:55:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 70 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C7A93B7B-719D-4225-923D-46FBFA6F0980", generation: 1)
[,ThaliCore] Advertiser.startAdvertising with peerID:C7A93B7B-719D-4225-923D-46FBFA6F0980
2017-07-21 10:55:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:55:30, ,- INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:55:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:55:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:55:30 - INFO thaliMobile: 'Receive,d state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:5,5:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:C7A93B7B-719D-4225-923D-46FBFA6F0980
[ThaliCore] Advertiser.s,topAdvertising() peerID:C7A93B7B-719D-4225-923D-46FBFA6F0980
2017-07-21 10:55:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:55:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 10:55:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:55:30 - DEBUG thaliMo,bileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:55:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:55:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:55:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:55:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:55:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:55:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:55:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:55:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 72 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:55:31 - DEBUG th,aliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:55:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Can call stopAdverti,singAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:55:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:55:31 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:55:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 10:55:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:55:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:55:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:55:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:55:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 10:55:31 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 10:55:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 10:55:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 10:55:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C698F9B2-FB30-44D1-8818-CDAB79F25800", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:C698F9B2-FB30-44D1-8818-CDAB79F25800
,2017-07-21 10:55:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:55:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:55:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:31C053E1-C751-4FE4-95DD-0564E546ED59
[ThaliCore] Browser.startListen,ing
2017-07-21 10:55:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 10:55:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-21 10:55:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E7E89EFF-C927-4E61-88A8-AA1DF588DD01:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E7E89EFF-C927-4E61-88A8-AA1DF588DD01", generation: 0)
ok 76 peers must be an array,
ok 77 peers must not be zero-length
ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
ok 79 peerIdentifier must be a string
ok 80 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CFC46F12-BB3B-4698-909C-4C2A69860CF7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CFC46F12-BB3B-4698-909C-4C2A69860CF7", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C698F9B2-FB30-44D1-8818-CDAB79F25800:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C698F9B2-FB30-44D1-8818-CDAB79F25800", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 10:55:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 ,10:55:34 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-21 10:55:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:C698F9B2-FB30-44D1-8818-C,DAB79F25800
2017-07-21 10:55:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:55:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
2017-07-21 10:55:34 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:55:34 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07,-21 10:55:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:55:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:55:34 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:55:34 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:55:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:55:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5964CC8A-CCBB-402E-9185-5196A4325050", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:5964CC8A-CCBB-402E-9185-5196A4325050
2017-07-21 10:55:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:55:39, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-21 10:55:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 81 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Thal,iCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F2CD3522-16CA-4752-8390-CCEA2E5E035C
[ThaliCore] Browser.startListening
2017-07-21 10:55:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adve,r,tisingActive":true}'
2017-07-21 10:55:39 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"rout,er":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:55:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9322C209-D516-4AC3-B9B3-B33D7BDE94FF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9322C209-D516-4AC3-B9B3-B33D7BDE94FF", generation: 0)
2017-07-21 10:55:40 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9322C209-D516-4AC3-B9B3-B33D7BDE94FF","generation":0}'
2017-07-21 10:55:40 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9322C209-D516-4AC3-B9B3-B33D7BDE94FF, (syncValue: olDqsBLNvki5qUgiZGCxraziwURqxiu4)'
2017-07-21 10:55:40 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9322C209-D516-4AC3-B9B3-B33D7BD,E94FF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9322C209-D516-4AC3-B9B3-B33D7BDE94FF", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9322C209-D516-4AC3-B9B3-B33D7BDE94FF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:44D1EA29-09FD-4DAF-A03B-8BB0AB5D04C4
[ThaliCore] Advertiser: session connected Peer(uuid: "5964CC8A-CCBB-402E-9185-5196A4325050", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:44D1EA29-09FD-4DAF-A03B-8BB0AB5D04C4 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CAF20AEF-B7EE-4000-B50D-44CEEEB61EDB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CAF20AEF-B7EE-4000-B50D-44CEEEB61EDB", generation: 0)
2017-07-21 10:55:40 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CAF20AEF-B7EE-4000-B50D-44CEEEB61EDB","generation":0}'
2017-07-21 10:55:40 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 10:55:40 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5964CC8A-CCBB-402E-9185-5196A4325050:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5964CC8A-CCBB-402E-9185-5196A4325050", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:9322C209-D516-4AC3-B9B3-B33D7BDE94FF:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:44D1EA29-09FD-4DAF-A03B-8BB0AB5D04C4
,[ThaliCore] Session.session(_:peer:didChange:) peer:44D1EA29-09FD-4DAF-A03B-8BB0AB5D04C4 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9322C209-D516-4AC3-B9B3-B33D7BDE94FF:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:9322C209-D516-4AC3-B9B3-B33D7BDE94FF:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "9322C209-D516-4AC3-B9B3-B33D7BDE94FF", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57081
2017-07-21 10:55:43 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"olDqsBLNvki5qUgiZGCxraziwURqxiu4","error":null,"portN,umber":57081}'
2017-07-21 10:55:43 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'olDqsBLNvki5qUgiZGCxraziwURqxiu4', error: 'null', listeningPort: '57081''
,2017-07-21 10:55:43 - INFO testThaliMobileNative: ''
ok 83 Must have listeningPort
ok 84 listeningPort must be a number
ok 85 listening port should not be 0
,# teardown
,2017-07-21 10:55:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 10:55:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:55:43 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:55:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:5964CC8A-CCBB-402E-9185-5196A4325050
,2017-07-21 10:55:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:55:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.disconnect peer:9322C209-D516-4AC3-B9B3-B33D7BDE94FF
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57081
[ThaliCore] Session.disconnect,() peer:9322C209-D516-4AC3-B9B3-B33D7BDE94FF:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:9322C209-D516-4AC3-B9B3-B33D7BDE94FF:0
[ThaliCore] BrowserRelay.deinit
,2017-07-21 10:55:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:55:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:55:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:55:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:55:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:55:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:55:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:55:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:44D1EA29-09FD-4DAF-A03B-8BB0AB5D04C4 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "5964CC8A-CCBB-402E-9185-5196A4325050", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:44D1EA29-09FD-4DAF-A03B-8BB0AB5D04C4
[ThaliCore] Advert,iserRelay.deinit
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C6A107A9-3C3D-474E-BE7A-580D8B57BEF0", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:C6A107A9-3C3D-474E-BE7A-580D8B57BEF0
,2017-07-21 10:55:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:55:44 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:55:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:172CA5F3-63C9-4F42-9246-81D93ED6,1B0B
[ThaliCore] Browser.startListening
2017-07-21 10:55:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 10:55:44 - INFO thaliMobile: 'Received state ({"discover,y,Active":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 10:55:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Session.deinit peer:44D1EA29-09FD-4DAF-A03B-8BB0AB5D04C4
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CAF20AEF-B7EE-4000-B50D-44CEEEB61EDB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CAF20AEF-B7EE-4000-B50D-44CEEEB61EDB", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:84A788E4-46FC-43D7-85F3-930F387C1ABA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "84A788E4-46FC-43D7-85F3-930F387C1ABA", generation: 0)
2017-07-21 10:55:45 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CAF20AEF-B7EE-4000-B50D-44CEEEB61EDB","generation":0}'
,2017-07-21 10:55:45 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CAF20AEF-B7EE-4000-B50D-44CEEEB61EDB (syncValue: sq9XLvQnYX69j6XRWij0f1GnFiXHRFFI)'
,2017-07-21 10:55:45 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CAF20AEF-B7EE-4000-B50D-44CEEEB61EDB", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CAF20AEF-B7EE-4000-B50D-44CEEEB61EDB", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CAF20AEF-B7EE-4000-B50D-44CEEEB61EDB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-07-21 10:55:45 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"84A788E4-46FC-43D7-85F3-930F387C1ABA","generation":0}'
,2017-07-21 10:55:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:55:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C6A107A9-3C3D-474E-BE7A-580D8B57BEF0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C6A107A9-3C3D-474E-BE7A-580D8B57BEF0", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8AC415B6-21AD-403C-9EBA-E6A7204A5D5F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8AC415B6-21AD-403C-9EBA-E6A7204A5D5F", generation: 0)
2017-07-21 10:55:45 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8AC415B6-21AD-403C-9EBA-E6A7204A5D5F","generation":0}'
2017-07-21 10:55:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 10:55:45 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 10:55:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:CAF20AEF-B7EE-4000-B50D-44CEEEB61EDB:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:CAF20AEF-B7EE-4000-B50D-44CEEEB61EDB:0
,[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "CAF20AEF-B7EE-4000-B50D-44CEEEB61EDB", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CAF20AEF-B7EE-4000-B50D-44CEEEB61EDB", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CAF20AEF-B7EE-4000-B50D-44CEEEB61EDB", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CAF20AEF-B7EE-4000-B50D-44CEEEB61EDB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.deinit peer:CAF20AEF-B7EE-4000-B50D-44CEEEB61EDB:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:CAF20AEF-B7EE-4000-B50D-44CEEEB61EDB:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:CAF20AEF-B7EE-4000-B50D-44CEEEB61EDB:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "CAF20AEF-B7EE-4000-B50D-44CEEEB61EDB", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,AF20AEF-B7EE-4000-B50D-44CEEEB61EDB", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CAF20AEF-B7EE-4000-B50D-44CEEEB61EDB", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:CAF20AEF-B7EE-4000-B50D-44CEEEB61EDB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:CAF20AEF-B7EE-4000-B50D-44CEEEB61EDB:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:CAF20AEF-B7EE-4000-B50D-44CEEEB61EDB:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:CAF20AEF-B7EE-4000-B50D-44CEEEB61EDB:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "CAF20AEF-B7EE-4000-B50D-44CEEEB61EDB", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,AF20AEF-B7EE-4000-B50D-44CEEEB61EDB", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CAF20AEF-B7EE-4000-B50D-44CEEEB61EDB", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CAF20AEF-B7EE-4000-B50D-44CEEEB61EDB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.deinit peer:CAF20AEF-B7EE-4000-B50D-44CEEEB61EDB:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:CAF20AEF-B7EE-4000-B50D-44CEEEB61EDB:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:CA,F20AEF-B7EE-4000-B50D-44CEEEB61EDB:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "CAF20AEF-B7EE-4000-B50D-44CEEEB61EDB", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:CAF20AEF,-B7EE-4000-B50D-44CEEEB61EDB error: max retries exceeded
2017-07-21 10:55:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"sq9XLvQnYX69j6XRWij0f1GnFiXHRFFI","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 10:55:56 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'sq9XLvQnYX69j6XRWij0f1GnFiXHRFFI', error: 'Connection could not be established', listeningPort: '%s''
2017-07-21 10:55:56 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"CAF20AEF-B7EE-4000-B50D-44CEEEB61EDB","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 10:55:56 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-21 10:55:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"CAF20AEF-B7EE-4000-B50D-44CEEEB61EDB","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-21 10:55:56 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 10:55:56 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-21 10:55:56 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 84A788E4-46FC-43D7-85F3-930F387C1ABA (syncValue: hvUt8ie,rDojRI6qFOluFrpKgJXvaYhOP)'
2017-07-21 10:55:56 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "84A788E4-46FC-43D7-85F3-930F387C1ABA", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "84A788E4-46FC-43D7-85F3-930F387C1ABA", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:84A788E4-46FC,-43D7-85F3-930F387C1ABA:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 10:55:56 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-07-21 10:55:56 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:CAF20AEF-B7EE-4000-B50D-44CEEEB61EDB:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:84A788E4-46FC-43D7-85F3-930F387C1ABA:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:84A788E4-46FC-43D7-85F3-930F387C1ABA:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:84A788E4-46FC-43D7-85F3-930F387C1ABA:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "84A788E4-46FC-43D7-85F3-930F387C1ABA", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57088
2017-07-21 10:55:58 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"hvUt8ierDojRI6qFOluFrpKgJXvaYhOP",,"error":null,"portNumber":57088}'
2017-07-21 10:55:58 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'hvUt8ierDojRI6qFOluFrpKgJXvaYhOP', error: 'null', listeningPort: '57088''
,Connecting to the localhost:57088
,Connected to the localhost:57088
2017-07-21 10:55:58 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
2017-07-21 10:55:58 - DEBUG testThaliMobileNative: 'Client data flushed'
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:84A788E4-46FC-43D7-85F3-930F387C1ABA:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:84A788E4-46FC-43D7-85F3-930F387C1ABA:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 88 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams,() vsID:1
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:1
[ThaliCore] VirtualSocket.deinit vsID:1 []
,# teardown
,2017-07-21 10:55:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 10:55:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:55:59 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:55:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:C6A107A9-3C3D-474E-BE7A-580D8B57BEF0
2017-07-21 10:55:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10,:55:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:84A788E4-46FC-43D7-85F3-930F387C1ABA
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57088
[ThaliCore] Session.disconnect() p,eer:84A788E4-46FC-43D7-85F3-930F387C1ABA:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:84A788E4-46FC-43D7-85F3-930F387C1ABA:0
[ThaliCore] BrowserRelay.deinit
,2017-07-21 10:55:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:55:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:55:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:55:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:55:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:55:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:55:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:55:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86
,2017-07-21 10:56:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:56:00 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:56:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 89 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6AA19F75-D6A3-4775-BB75-F9DD442C,CAF5
[ThaliCore] Browser.startListening
2017-07-21 10:56:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 10:56:00 - INFO thaliMobile: 'Received state ({"discover,y,Active":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:56:00 - INFO thaliMobi,le: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:84A788E4-46FC-43D7-85F3-930F387C1ABA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "84A788E4-46FC-43D7-85F3-930F387C1ABA", generation: 0)
2017-07-21 10:56:00 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"84A788E4-46FC-43D7-85F3-930F387C1ABA","generation":0}'
2017-07-21 10:56:00 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 84A788E4-46FC-43D7-85F3-930F387C1ABA, (syncValue: fpO1hk44nbwPIwzLaAqdthc1TaSK5tsp)'
2017-07-21 10:56:00 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "84A788E4-46FC-43D7-85F3-930F387,C1ABA", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "84A788E4-46FC-43D7-85F3-930F387C1ABA", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:84A788E4-46FC-43D7-85F3-930F387C1ABA:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8AC415B6-21AD-403C-9EBA-E6A7204A5D5F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8AC415B6-21AD-403C-9EBA-E6A7204A5D5F",, generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 10:56:01 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable,":true,"peerIdentifier":"8AC415B6-21AD-403C-9EBA-E6A7204A5D5F","generation":0}'
2017-07-21 10:56:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 10:56:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:62EDF300-F62B-48E1-984D-71A5F52E35C1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "62EDF300-F62B-48E1-984D-71A5F52E35C1", generation: 0)
2017-07-21 10:56:01 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"62EDF300-F62B-48E1-984D-71A5F52E35C1","generation":0}'
2017-07-21 10:56:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 10:56:01 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 10:56:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C6E0D61B-5C67-46BA-BD6E-1062AC583801:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C6E0D61B-5C67-46BA-BD6E-1062AC583801", generation: 0)
,2017-07-21 10:56:01 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C6E0D61B-5C67-46BA-BD6E-1062AC583801","generation":0}'
,2017-07-21 10:56:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:56:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:56:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:56:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:84A788E4-46FC-43D7-85F3-930F387C1ABA:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:84,A788E4-46FC-43D7-85F3-930F387C1ABA:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "84A788E4-46FC-43D7-85F3-930F387C1ABA", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,4A788E4-46FC-43D7-85F3-930F387C1ABA", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "84A788E4-46FC-43D7-85F3-930F387C1ABA", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:84A788E4-46FC-43D7-85F3-930F387C1ABA:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:84A788E4-46FC-43D7-85F3-930F387C1ABA:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:84A788E4-46FC-43D7-85F3-930F387C1ABA:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "84A788E4-46FC-43D7-85F3-930F387C1ABA", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:84A788E4-46FC-43D7-85F3-930F387C1ABA:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:84,A788E4-46FC-43D7-85F3-930F387C1ABA:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "84A788E4-46FC-43D7-85F3-930F387C1ABA", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,4A788E4-46FC-43D7-85F3-930F387C1ABA", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "84A788E4-46FC-43D7-85F3-930F387C1ABA", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 10:56:06 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"fpO1hk44nbwPIwzLaAqdthc1TaSK5tsp","error":"Peer is unavailable","portNumber":null}'
2017-07-21 10:56:06 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'fpO1hk44nbwPIwzLaAqdthc1TaSK5tsp', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 10:56:06 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"84A788E4-46FC-43D7-85F3-930F387C1ABA","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 10:56:06 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 10:56:06 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"84A788E4-46FC-43D7-85F3-930F387C1ABA","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-21 10:56:06 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 10:56:06 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 10:56:06 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 8AC415B6-21AD-403C-9EBA-E6A7204A5D5F (syncValue: BCF5uM5oAFNA3WcVyQPTFrn,MOP1SwBqc)'
2017-07-21 10:56:06 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8AC415B6-21AD-403C-9EBA-E6A7204A5D5F", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8AC415B6-21AD-403C-9EBA-E6A7204A5D5F", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8AC415B6-21AD-403C-9EBA-E6A72,04A5D5F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 10:56:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 ,1,0:56:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:84A788E4-46FC-43D7-85F3-930F387C1ABA:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:8AC415B6-21AD-403C-9EBA-E6A7204A5D5F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:8A,C415B6-21AD-403C-9EBA-E6A7204A5D5F:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "8AC415B6-21AD-403C-9EBA-E6A7204A5D5F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,AC415B6-21AD-403C-9EBA-E6A7204A5D5F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8AC415B6-21AD-403C-9EBA-E6A7204A5D5F", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:8AC415B6-21AD-403C-9EBA-E6A7204A5D5F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:8AC415B6-21AD-403C-9EBA-E6A7204A5D5F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:8AC415B6-21AD-403C-9EBA-E6A7204A5D5F:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "8AC415B6-21AD-403C-9EBA-E6A7204A5D5F", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:8AC415B6-21AD-403C-9EBA-E6A7204A5D5F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:8A,C415B6-21AD-403C-9EBA-E6A7204A5D5F:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "8AC415B6-21AD-403C-9EBA-E6A7204A5D5F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,AC415B6-21AD-403C-9EBA-E6A7204A5D5F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8AC415B6-21AD-403C-9EBA-E6A7204A5D5F", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 10:56:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"BCF5uM5oAFNA3WcVyQPTFrnMOP1SwBqc","error":"Peer is unavailable","portNumber":null}'
2017-07-21 10:56:11 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'BCF5uM5oAFNA3WcVyQPTFrnMOP1SwBqc', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 10:56:11 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"8AC415B6-21AD-403C-9EBA-E6A7204A5D5F","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 10:56:11 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 10:56:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"8AC415B6-21AD-403C-9EBA-E6A7204A5D5F","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-21 10:56:11 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 10:56:11 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 10:56:11 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 62EDF300-F62B-48E1-984D-71A5F52E35C1 (syncValue: vVrCtppvGYhBQ059RI8F8zZ,DCF6Asfvd)'
2017-07-21 10:56:11 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "62EDF300-F62B-48E1-984D-71A5F52E35C1", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "62EDF300-F62B-48E1-984D-71A5F52E35C1", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:62EDF300-F62B-48E1-984D-71A5F,52E35C1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 10:56:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:8AC415B6-21AD-403C-9EBA-E6A7204A5D5F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0E082915-1D5D-44C6-9131-F37022463E75
[ThaliCore] Advertiser: session connected Peer(uuid: "F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:0E082915-1D5D-44C6-9131-F37022463E75 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:62EDF300-F62B-48E1-984D-71A5F52E35C1:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0E082915-1D5D-44C6-9131-F37022463E75
,[ThaliCore] Session.session(_:peer:didChange:) peer:0E082915-1D5D-44C6-9131-F37022463E75 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0E082915-1D5D-44C6-9131-F37022463E75
[ThaliCore] Session.startOutputStream(with:) peer:0E082915-1D5D-44C6-9131-F37022463E75
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [2]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0E082915-1D5D-44C6-9131-F37022463E75
[ThaliCore] Session.startOutputStream(with:) peer:0E082915-1D5D-44C6-9131-F3702246,3E75
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [2, 3]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0E082915-1D5D-44C6-9131-F37022463E75
[ThaliCore] Session.st,artOutputStream(with:) peer:0E082915-1D5D-44C6-9131-F37022463E75
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [2, 3, 4]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPClient: didConnectToHost, active connections cou,nt: 1
[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-21 10:56:15 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
2017-07-21 10:56:15 - DEBUG testThaliMobileNative: 'Server received (5475 bytes):'
2017-07-21 10:56:15 - DEBUG testThaliMobileNative: 'Server received (5475 bytes):'
2017,-07-21 10:56:15 - DEBUG testThaliMobileNative: 'Server received (2149 bytes):'
2017-07-21 10:56:15 - DEBUG testThaliMobileNative: 'Server received all data: Jd5QDoiBCDeDK3KQpr3YNwormLOOC1wxwKMo8vUb8GQRB3DvzlEBYr8ecj77RwK7mUJHRPK8YkbRiC1kKl7AAnKr2EFjFxAqJ1,NxKuirhXonaP4nUSVJm3prxMa5FwDcA3sOr6ihogtePJsP01mzUldM2vX4dhsnApgSrRc90oZ4W7ZrNMoURMQjYXHhLRqPqvoAYpjVhrh9zw7u9XkRwaZF8rn0oPiXzRJ9DLn0MKPcSaoScr0342cOqUyTaewD6QBBcCdYdkuDBeA0VdgWBdU2sp2AgqtaTYHGRa7wuHG6NwXjaLpKBs6aEqeHtydIMV4x7uQ48IfWu10NrzbAetBloFB1mIYYIX,ESOwcUqHUxy5XHmRaXCiLdOCIl4PQFfom8P2K26Gl5QMRhJUpN6kSmOXumwSkyYJuumZ5acICfxwC9ukdPSbzzXzeFV0uuyvf3owhnZONIJikljkwj8R9QGQpcQ4cMHxSYk8GpEUsSDJqXIjHkhTVsay1dqU0MPmBOh0ifQ0HeRfV42ohBvSdohBLH0chPFldWTLB6jSdSw8UDo8L9VpC8GUbpGOf9NFcjdHWorvPMYFrHJirF9DYjYRIkvLMvo,F,ccUsGnVbh3OZubBgsLjd14M9SNGOxkO2NxlU0DEPq4W9dUy3WeLTWETE3VyPkTvOeM1L5ZCQXHuAc2qmnNuqq8XU0dtb6lYauLylG4M2vAcrVVlcUWp2cHMxT149aF4HOb7mfvltm1uB3LDdILD1Sb2tbXsh5scVPSqGcWaGEgbEq9hlJQW5DeV5aS9Uulexf8UeYFZrNoPs8FoW187qyZpw863CA8bKeLvpwEQpdDOhFizDdTdrWROaWG5X8D0L,2H3TJ5WKPERE6P0g3WrFIUTGF6R1W6sO841UzORXQef9qK1oBEMFWfb7bxO5ZG9NKOTX5xYabRxK2MEfmnflQB4jBQVeQgEtYfClB2SeRXPozYd27jBEd9bTg9h0vvXWuSUgFxKJUU2EsahSKmnxuFeBA3lDegZG0Wdr0VBLrLlIFR1K2u9HUa6WoCCkt9H5nDof3d4F6LIJX5G5W85MeSKbQ3nB3RILrgBsRlvTt5luI8qApNqENIu58LNvmp7R,CodBMmGgUPFxQmkOWcWBFT76JN6naLR8gYUd41NAoiWkA1B7UUjoWFIiZtDj58BjtHc8UuKhl7Qnz8qABt0jzyON9Z2RCkgC9aCDplydreoLPy0cRXes2UowLVRP7VOcbbY84RsAuwjO183hYiFoNJzC6edt0iCRNsoRVySrVPvyTjMzPMNzXm23BQMGm3OVKUiKtqHu2n7ofO34JOYXCGtURFce9PPX2OTbvureEttCeGhLioFreItP8WVr94zM,wWubHp48rPdeYP2KpkuZJqbcHHOTIzSNAao2ZdHXYKR5WJwB3G57Hf4prDWuIG2nZAsAKi6PkAiB5plBKP6TgkbppBHetuzfXF1RevnjDEY6WY3037mOYEhsJqkr4OSVGh4vvgTnf7Qlm5XcIUzuvFTF8VWakk4mr1lti02CWozVxTzB2n56eYyUt8Kt8Yq1KAqWe2HkxyD5K6mmlUPobOXLaHDsf1xGupLteEyKfMA0dcIQTCKyk8LsowBSOwD,H,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'
2017-07-21 10:56:15 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 byt,es):'
2017-07-21 10:56:15 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-21 10:56:15 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 10:56:15 - DEBUG testThaliMobileNative: 'Server received (5475 bytes):'
,2017-07-21 10:56:15 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-21 10:56:15 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 10:56:15 - DEBUG testThaliMobileNative: 'Server received (3244 bytes):'
,2017-07-21 10:56:15 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-21 10:56:15 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-21 10:56:15 - DEBUG testThaliMobileNative: 'Server data flushed',
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:2
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:3
,[ThaliCore] VirtualSocket.closeStreams() vsID:2
[ThaliCore] VirtualSocket.closeStreams() vsID:3
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:3
,[ThaliCore] VirtualSocket.deinit vsID:3 [2, 4]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-21 10:56:15 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-21 10:56:15 - DEBUG testThaliMobileNative: 'Server received (13099 bytes):'
,2017-07-21 10:56:15 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-21 10:56:15 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-21 10:56:15 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:4
[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:4
,[ThaliCore] VirtualSocket.deinit vsID:4 [2]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:62EDF300-F62B-48E1-984D-71A5F52E35C1:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:62EDF300-F62B-48E1-984D-71A5F52E35C1:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "62EDF300-F62B-48E1-984D-71A5F52E35C1", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57108
,2017-07-21 10:56:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"vVrCtppvGYhBQ059RI8F8zZDCF6Asfvd","error":null,"portNumber":57108}'
,2017-07-21 10:56:18 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'vVrCtppvGYhBQ059RI8F8zZDCF6Asfvd', error: 'null', listeningPort: '57108''
,Connecting to the localhost:57108
,Connecting to the localhost:57108
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:62EDF300-F62B-48E1-984D-71A5F52E35C1:0
Connecting to the localhost:57108
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:62EDF300-F62B-48E1-984D-71A5F52E35C1:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[Th,aliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:62EDF300-F62B-48E1-984D-71A5F52E35C1:0
,Connected to the localhost:57108
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:62EDF300-F62B-48E1-984D-71A5F52E35C1:0
Connected to the localhost:57108
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [2, 5]
Connected, to the localhost:57108
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:62EDF300-F62B-48E1-984D-71A5F52E35C1:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [2, 5, 6]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:62EDF300-F62B-48E1-984D-71A5F52E35C1:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [2, 5, 6, 7]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 91 correct string length
,2017-07-21 10:56:18 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 92 correct string length
,2017-07-21 10:56:18 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 93 correct string length
,2017-07-21 10:56:18 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-21 10:56:18 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-21 10:56:18 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-21 10:56:18 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:5
[ThaliCore] Browser,Relay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:5
[ThaliCore] VirtualSocket.deinit vsID:5 [2, 6, 7]
ok 94 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:6
[ThaliCore] Browser,Relay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:6
[ThaliCore] VirtualSocket.deinit vsID:6 [2, 7]
ok 95 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:7
[ThaliCore] Browser,Relay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:7
[ThaliCore] VirtualSocket.deinit vsID:7 [2]
ok 96 got the same data back
,# teardown
,2017-07-21 10:56:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 10:56:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:56:19 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:56:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86
2017-07-21 10:56:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"a,dvertisingActive":false}'
2017-07-21 10:56:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:62EDF300-F62B-48E1-984D-71A5F52E35C1
[ThaliCore] BrowserRelay.closeRelay(,) state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57108
[ThaliCore] Session.disconnect() peer:62EDF300-F62B-48E1-984D-71A5F52E35C1:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socke,t error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:0E082915-1D5D-44C6-9131-F37022463E75 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:0E082915-1D5D-44C6-9131-F37022463E75
,[ThaliCore] Session.deinit peer:62EDF300-F62B-48E1-984D-71A5F52E35C1:0
[ThaliCore] BrowserRelay.deinit
2017-07-21 10:56:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:56:19 - DEBUG thaliMobileNat,iveWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:56:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:56:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 10:56:19 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 10:56:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 10:56:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 10:56:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] AdvertiserRelay.deinit
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9BD2EEC5-BC28-4301-8B46-0C2C7D945274", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:9BD2EEC5-BC28-4301-8B46-0C2C7D945274
,2017-07-21 10:56:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:56:19 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 10:56:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 97 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DD1CD578-EC72-404F-BAE8-994A42F04A88
[ThaliCore] Browser.startListening
2017-07-21 10:56:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 10:56:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:56:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Session.deinit peer:0E082915-1D5D-44C6-9131-F37022463E75
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:62EDF300-F62B-48E1-984D-71A5F52E35C1:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "62EDF300-F62B-48E1-984D-71A5F52E35C1", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C6E0D61B-5C67-46BA-BD6E-1062AC583801:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C6E0D61B-5C67-46BA-BD6E-1062AC583801", generation: 0)
2017-07-21 10:56:20 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"62EDF300-F62B-48E1-984D-71A5F52E35C1","generation":0}'
,2017-07-21 10:56:20 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 62EDF300-F62B-48E1-984D-71A5F52E35C1 (syncValue: OqF5pusTTCrzNdAtU02xozDIuHljO4Im)'
2017-07-21 10:56:20 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "62EDF300-F62B-48E1-984D-71A5F52E35C1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "62ED,F300-F62B-48E1-984D-71A5F52E35C1", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:62EDF300-F62B-48E1-984D-71A5F52E35C1:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 10:56:20 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C6E0D61B-5C67-46BA-BD6E-1062AC583801","generation":0}'
2017-07-21 10:56:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:56:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9BD2EEC5-BC28-4301-8B46-0C2C7D945274:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9BD2EEC5-BC28-4301-8B46-0C2C7D945274", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3FDC5DDB-7B8C-46BB-9035-E7915D9CA128:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3FDC5DDB-7B8C-46BB-9035-E7915D9CA128", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C", generation: 0)
,2017-07-21 10:56:20 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3FDC5DDB-7B8C-46BB-9035-E7915D9CA128","generation":0}'
,2017-07-21 10:56:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:56:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:56:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:56:20 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C","generation":0}'
,2017-07-21 10:56:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:56:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:56:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:56:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:62EDF300-F62B-48E1-984D-71A5F52E35C1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:62,EDF300-F62B-48E1-984D-71A5F52E35C1:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "62EDF300-F62B-48E1-984D-71A5F52E35C1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,2EDF300-F62B-48E1-984D-71A5F52E35C1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "62EDF300-F62B-48E1-984D-71A5F52E35C1", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:62EDF300-F62B-48E1-984D-71A5F52E35C1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:62EDF300-F62B-48E1-984D-71A5F52E35C1:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:62EDF300-F62B-48E1-984D-71A5F52E35C1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:62,EDF300-F62B-48E1-984D-71A5F52E35C1:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "62EDF300-F62B-48E1-984D-71A5F52E35C1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,2EDF300-F62B-48E1-984D-71A5F52E35C1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "62EDF300-F62B-48E1-984D-71A5F52E35C1", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:62EDF300-F62B-48E1-984D-71A5F52E35C1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:62EDF300-F62B-48E1-984D-71A5F52E35C1:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:C6E0D61B-5C67-46BA-BD6E-1062AC583801:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "C6E0D61B-5C67-46BA-BD6E-1062AC583801", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:62EDF300-F62B-48E1-984D-71A5F52E35C1:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "62EDF300-F62B-48E1-984D-71A5F52E35C1", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:62EDF300-F62B-48E1-984D-71A5F52E35C1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:62,EDF300-F62B-48E1-984D-71A5F52E35C1:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "62EDF300-F62B-48E1-984D-71A5F52E35C1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,2EDF300-F62B-48E1-984D-71A5F52E35C1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "62EDF300-F62B-48E1-984D-71A5F52E35C1", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 10:56:28 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"OqF5pusTTCrzNdAtU02xozDIuHljO4Im","error":"Peer is unavailable","portNumber":null}'
2017-07-21 10:56:28 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'OqF5pusTTCrzNdAtU02xozDIuHljO4Im', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 10:56:28 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"62EDF300-F62B-48E1-984D-71A5F52E35C1","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 10:56:28 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 10:56:28 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"62EDF300-F62B-48E1-984D-71A5F52E35C1","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-21 10:56:28 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 10:56:28 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 10:56:28 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3FDC5DDB-7B8C-46BB-9035-E7915D9CA128 (syncValue: 6UZ9r1r9VSwyFMMLFDpAT7o,MvxeQHbE2)'
2017-07-21 10:56:28 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3FDC5DDB-7B8C-46BB-9035-E7915D9CA128", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3FDC5DDB-7B8C-46BB-9035-E7915D9CA128", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3FDC5DDB-7B8C-46BB-9035-E7915,D9CA128:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 10:56:28 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:62EDF300-F62B-48E1-984D-71A5F52E35C1:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:3FDC5DDB-7B8C-46BB-9035-E7915D9CA128:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3FDC5DDB-7B8C-46BB-9035-E7915D9CA128:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3FDC5DDB-7B8C-46BB-9035-E7915D9CA128:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "3FDC5DDB-7B8C-46BB-9035-E7915D9CA128", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57124
,2017-07-21 10:56:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6UZ9r1r9VSwyFMMLFDpAT7oMvxeQHbE2","error":null,"portNumber":57124}'
,2017-07-21 10:56:31 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '6UZ9r1r9VSwyFMMLFDpAT7oMvxeQHbE2', error: 'null', listeningPort: '57124''
,Connecting to the localhost:57124
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3FDC5DDB-7B8C-46BB-9035-E7915D9CA128:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3FDC5DDB-7B8C-46BB-9035-E7915D9CA128:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [2, 8]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:57124
,2017-07-21 10:56:32 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-21 10:56:32 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 99 got the same data back
# teardown
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed b,y remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.,closeStreams() vsID:8
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:8
[ThaliCore] VirtualSocket.deinit vsID:8 [2]
,2017-07-21 10:56:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 10:56:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:56:35 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:56:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:9BD2EEC5-BC28-4301-8B46-0C2C7D945274
2017-07-21 10:56:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10,:,56:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:3FDC5DDB-7B8C-46BB-9035-E7915D9CA128
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57124
[ThaliCore] Session.disconnect() peer:3FDC5DDB-7B8C-46BB-9035-E7915D9CA128:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:3FDC5DDB-7B8C-46BB-9035-E7915D9CA128:0
[ThaliCore] BrowserRelay.deinit
,2017-07-21 10:56:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:56:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:56:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:56:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:56:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-21 10:56:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:56:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:56:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "839E6042-1808-4159-8923-FD521909AFE8", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:839E6042-1808-4159-8923-FD521909AFE8
,2017-07-21 10:56:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:56:36 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:56:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 100 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1E7674A5-17B5-4B49-88C4-15FB4BEDF34A
,[ThaliCore] Browser.startListening
2017-07-21 10:56:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 10:56:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:56:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:3FDC5DDB-7B8C-46BB-9035-E7915D9CA128:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3FDC5DDB-7B8C-46BB-9035-E7915D9CA128", generation: 0)
,2017-07-21 10:56:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C","generation":0}'
,2017-07-21 10:56:37 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C (syncValue: ssATg9VIgmBgta7OyfzB1J6TIgiZmptU)'
,2017-07-21 10:56:37 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-07-21 10:56:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3FDC5DDB-7B8C-46BB-9035-E7915D9CA128","generation":0}'
,2017-07-21 10:56:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:56:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:839E6042-1808-4159-8923-FD521909AFE8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "839E6042-1808-4159-8923-FD521909AFE8", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B", generation: 0)
2017-07-21 10:56:38 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B","generation":0}'
2017-07-21 10:56:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 10:56:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 10:56:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F287E759-9DEE-41EC-A28C-0C2B4889AF65:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F287E759-9DEE-41EC-A28C-0C2B4889AF65", generation: 0)
2017-07-21 10:56:38 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F287E759-9DEE-41EC-A28C-0C2B4889AF65","generation":0}'
2017-07-21 10:56:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 10:56:38 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 10:56:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 10:56:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:4DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4D,CC7E8D-628B-41A5-9B46-C0A2FAFCD93C:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "4DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:4DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:4DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "4DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:4DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4D,CC7E8D-628B-41A5-9B46-C0A2FAFCD93C:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "4DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 10:56:42 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ssATg9VIgmBgta7OyfzB1J6TIgiZmptU","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 10:56:42 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ssATg9VIgmBgta7OyfzB1J6TIgiZmptU', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 10:56:42 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"4DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 10:56:42 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 10:56:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"4DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-21 10:56:42 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 10:56:42 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 10:56:42 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3FDC5DDB-7B8C-46BB-9035-E7915D9CA128 (syncValue: uozkZbe4SnsK1JlC6TJn74E,B83ic6y3W)'
2017-07-21 10:56:42 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3FDC5DDB-7B8C-46BB-9035-E7915D9CA128", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3FDC5DDB-7B8C-46BB-9035-E7915D9CA128", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3FDC5DDB-7B8C-46BB-9035-E7915,D9CA128:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 10:56:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 ,1,0:56:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:4DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:3FDC5DDB-7B8C-46BB-9035-E7915D9CA128:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "3FDC5DDB-7B8C-46BB-9035-E7915D9CA128", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B04A5574-A5F0-4CCE-9CD8-297EFD329A4A
[ThaliCore] Advertiser: session connected Peer(uuid: "839E6042-1808-4159-8923-FD521909AFE8", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:B04A5574-A5F0-4CCE-9CD8-297EFD329A4A state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:3FDC5DDB-7B8C-46BB-9035-E7915D9CA128:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:3F,DC5DDB-7B8C-46BB-9035-E7915D9CA128:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "3FDC5DDB-7B8C-46BB-9035-E7915D9CA128", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,FDC5DDB-7B8C-46BB-9035-E7915D9CA128", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3FDC5DDB-7B8C-46BB-9035-E7915D9CA128", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 10:56:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"uozkZbe4SnsK1JlC6TJn74EB83ic6y3W","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 10:56:45 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'uozkZbe4SnsK1JlC6TJn74EB83ic6y3W', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 10:56:45 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"3FDC5DDB-7B8C-46BB-9035-E7915D9CA128","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 10:56:45 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 10:56:45 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3FDC5DDB-7B8C-46BB-9035-E7915D9CA128","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-21 10:56:45 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 10:56:45 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 10:56:45 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B (syncValue: qUwbkn4sm0idVyxHUrw6gAI,DVnpizB3N)'
2017-07-21 10:56:45 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0FDE9EDA-3925-4EEE-8C07-B82DD,C023D3B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 10:56:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:3FDC5DDB-7B8C-46BB-9035-E7915D9CA128:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B04A5574-A5F0-4CCE-9CD8-297EFD329A4A
,[ThaliCore] Session.session(_:peer:didChange:) peer:B04A5574-A5F0-4CCE-9CD8-297EFD329A4A state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B04A5574-A5F0-4CCE-9CD8-297EFD329A4A
[ThaliCore] Session.startOutputStream(with:) peer:B04A5574-A5F0-4CCE-9CD8-297EFD329A4A
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9, [2, 9]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-21 10:56:46 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 10:56:46 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 10:56:46 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 10:56:46 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 10:56:46 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 10:56:46 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 10:56:46 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 10:56:46 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 10:56:46 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 10:56:46 - DEBUG testThaliMobileNative: 'Server received (2119 bytes):'
,2017-07-21 10:56:46 - DEBUG testThaliMobileNative: 'Server received (2261 bytes):'
,2017-07-21 10:56:46 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 10:56:46 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 10:56:46 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 10:56:46 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 10:56:46 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 10:56:46 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 10:56:46 - DEBUG testThaliMobileNative: 'Server received (2119 bytes):'
,2017-07-21 10:56:46 - DEBUG testThaliMobileNative: 'Server received (2261 bytes):'
,2017-07-21 10:56:46 - DEBUG testThaliMobileNative: 'Server received (2119 bytes):'
,2017-07-21 10:56:46 - DEBUG testThaliMobileNative: 'Server received (2261 bytes):'
,2017-07-21 10:56:46 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 10:56:46 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 10:56:46 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 10:56:46 - DEBUG testThaliMobileNative: 'Server received (13383 bytes):'
,2017-07-21 10:56:46 - DEBUG testThaliMobileNative: 'Server received (7258 bytes):'
,2017-07-21 10:56:46 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-21 10:56:46 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-21 10:56:46 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:9
[ThaliCore] VirtualSocket.closeStreams() vsID:9
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B:0 state: notConnected -> connecting
[ThaliCore] VirtualSocket exited RunLoop vsID:9
[ThaliCore] VirtualSocket.deinit vsID:9 [2]
[ThaliCore] TCPClient.socketDidDisco,nnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57139
2017-07-21 10:56:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"qUwbkn4sm0idVyxHUrw6gAIDVnpizB3N",,"error":null,"portNumber":57139}'
2017-07-21 10:56:48 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'qUwbkn4sm0idVyxHUrw6gAIDVnpizB3N', error: 'null', listeningPort: '57139''
,Connecting to the localhost:57139
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B:0
Connected to the localhost:57139
,2017-07-21 10:56:48 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-21 10:56:48 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [2, 10]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 102 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pe,er})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStream,s() vsID:10
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:10
[ThaliCore] VirtualSocket.deinit vsID:10 [2]
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:84651C3B-9AC1-4BF8-B558-49D4721AB6C9
[ThaliCore] Advertiser: session connected Peer(uuid: "839E6042-1808-4159-8923-FD521909AFE8", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:84651C3B-9AC1-4BF8-B558-49D4721AB6C9 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:84651C3B-9AC1-4BF8-B558-49D4721AB6C9
,[ThaliCore] Session.session(_:peer:didChange:) peer:84651C3B-9AC1-4BF8-B558-49D4721AB6C9 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:84651C3B-9AC1-4BF8-B558-49D4721AB6C9
[ThaliCore] Session.startOutputStream(with:) peer:84651C3B-9AC1-4BF8-B558-49D4721AB6C9
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [2, 11]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-21 10:56:57 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
2017-07-21 10:56:57 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-21 10:56:57 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-21 10:56:57 - DEBUG testThaliMobileNative: 'Server received (3072 bytes):'
,2017-07-21 10:56:57 - DEBUG testThaliMobileNative: 'Server received (5546 bytes):'
,2017-07-21 10:56:57 - DEBUG testThaliMobileNative: 'Server received (2332 bytes):'
,2017-07-21 10:56:57 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 10:56:57 - DEBUG testThaliMobileNative: 'Server received (3143 bytes):'
,2017-07-21 10:56:57 - DEBUG testThaliMobileNative: 'Server received (2332 bytes):'
,2017-07-21 10:56:57 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 10:56:57 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-21 10:56:57 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-21 10:56:57 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-21 10:56:57 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-21 10:56:57 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-21 10:56:57 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 10:56:57 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-21 10:56:57 - DEBUG testThaliMobileNative: 'Server received (3143 bytes):'
,2017-07-21 10:56:57 - DEBUG testThaliMobileNative: 'Server received (3427 bytes):'
,2017-07-21 10:56:57 - DEBUG testThaliMobileNative: 'Server received (2026 bytes):'
,2017-07-21 10:56:57 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-21 10:56:57 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-21 10:56:57 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:11
[ThaliCore] VirtualSocket.closeStreams() vsID:11
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:11
[ThaliCore] VirtualSocket.deinit vsID:11 [2]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-21 10:56:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 10:56:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 10:56:57 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 10:56:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:839E6042-1808-4159-8923-FD521909AFE8
,2017-07-21 10:56:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:56:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57139
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:84651C3B-9AC1-4BF8-B558-49D4721AB6C9 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "839E6042-1808-4159-8923-FD521909AFE8", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:84651C3B-9AC1-4BF8-B558-49D4721AB6C9
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B04A5574-A5F0-4CCE-9CD8-297EFD329A4A state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "839E6042-1808-4159-8923-FD521909AFE8", generation: 0)
,[ThaliCore] Session.deinit peer:0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B:0
[ThaliCore] BrowserRelay.deinit
2017-07-21 10:56:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:56:57 - DEBUG thaliMobileNat,iveWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:56:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:56:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 10:56:57 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 10:56:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:56:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:56:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:AA684890-65F8-414E-B43D-43C962CF2086
[ThaliCore] Browser.startListening
2017-07-21 10:56:58 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 10:56:58 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:56:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 103 We should start ,listening fine
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "49486435-1B49-404F-8A95-D65FB54627D3", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:49486435-1B49-404F-8A95-D65FB5462,7,D3
,2017-07-21 10:56:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 10:56:58 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 10:56:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 104 We should start updating fine
,# teardown
,[ThaliCore] Session.deinit peer:84651C3B-9AC1-4BF8-B558-49D4721AB6C9
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B", generation: 0)
2017-07-21 10:56:58 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B","generation":0}]'
2017-07-21 10:56:58 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B","generation":0}'
2017-07-21 10:56:58 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F287E759-9DEE-41EC-A28C-0C2B4889AF65:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F287E759-9DEE-41EC-A28C-0C2B4889AF65", generation: 0)
2017-07-21 10:56:58 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F287E759-9DEE-41EC-A28C-0C2B4889AF65","generation":0}]'
2017-07-21 10:56:58 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"F287E759-9DEE-41EC-A28C-0C2B4889AF65","generation":0}'
2017-07-21 10:56:58 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:06887905-6ACD-4B62-BBB9-4BB2FDAC62C3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "06887905-6ACD-4B62-BBB9-4BB2FDAC62C3", generation: 0)
2017-07-21 10:56:59 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"06887905-6ACD-4B62-BBB9-4BB2FDAC62C3","generation":0}]'
2017-07-21 10:56:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"06887905-6ACD-4B62-BBB9-4BB2FDAC62C3","generation":0}'
2017-07-21 10:56:59 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:49486435-1B49-404F-8A95-D65FB54627D3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "49486435-1B49-404F-8A95-D65FB54627D3", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0D7C3221-280B-4FF5-8FC8-0F4B9059DAA1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0D7C3221-280B-4FF5-8FC8-0F4B9059DAA1", generation: 0)
2017-07-21 10:57:01 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"0D7C3221-280B-4FF5-8FC8-0F4B9059DAA1","generation":0}]'
2017-07-21 10:57:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"0D7C3221-280B-4FF5-8FC8-0F4B9059DAA1","generation":0}'
2017-07-21 10:57:01 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 10:57:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 ,10:57:04 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-21 10:57:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:49486435-1B49-404F-8A95-D,65FB54627D3
,2017-07-21 10:57:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:57:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-21 10:57:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:57:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:57:04 ,- DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:57:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:57:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:57:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:57:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Test updating advertising and parallel data transfer
,2017-07-21 10:57:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:57:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:57:05 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:57:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 10:57:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:57:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:57:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:57:05 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 10:57:05 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 10:57:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 10:57:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 10:57:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D3B7F876-E62F-42AC-B122-27E372A9FC96
[ThaliCore] Browser.startListening
,ok 105 discoveryActive should be false
ok 106 advertisingActive should be true
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "028E20A9-7346-4920-BC2A-974E9AF8EBC2", generation: 0)
[ThaliCore] Advertise,r.startAdvertising with peerID:028E20A9-7346-4920-BC2A-974E9AF8EBC2
ok 107 discoveryActive should be false
ok 108 advertisingActive should be true
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
ok 109 d,iscoveryActive should be false
ok 110 advertisingActive should be true
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:028E20A9-7346-4920-BC2A-974E9AF8EBC2
ok 111 discoveryActive should be false
ok 112 a,dvertisingActive should be true
ok 113 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:57:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:57:05 - DEBUG thaliMobi,leNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:57:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 10:57:05 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 10:57:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 10:57:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 10:57:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-07-21 10:57:05 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:57:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:57:05 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 114 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:57:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:57:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 115 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-21 10:57:06 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:57:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:57:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 116 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:57:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:57:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 117 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-21 10:57:06 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:57:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:57:06 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 118 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:57:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:57:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 119 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-21 10:57:07 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:57:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:57:07 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:57:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:57:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-21 10:57:07 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:57:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:57:07 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 122 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:57:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:57:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 123 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-21 10:57:07 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:57:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:57:07 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 124 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:57:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:57:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 125 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 126 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:002eada0-1322-468e-af62-798439611d62 error: startListeningNotActive
2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved:, {"syncValue":"rP9K5icKHitfIJsp7f0is4fPeuhI9ZHk","error":"startListeningForAdvertisements is not active","portNumber":null}'
ok 127 Should only get called after multiConnect returned
ok 128 SyncValue matches
ok 129 Got right error
ok 130 listeningPort ,is null
2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"002eada0-1322-468e-af62-798439611d62","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 10:57:08 - DEBUG t,haliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"002eada0-1322-468e-af62-7,9,8439611d62","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:57:08 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 10:57:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:57:08 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 10:57:08 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D37EF8CF-38DE-4DC5-B683-A03E29E31E03
[ThaliCore] Browser.startListening
2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 10:57:08 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:57:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 131 No error on starting
ok 132 Got null as expected
2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper:, 'multiConnectResolved: {"syncValue":"FYomS1UWXQ0OGIvCU7Qy8FhHXqkAe5TZ","error":"Illegal peerID","portNumber":null}'
ok 133 Should only get called after multiConnect returned
ok 134 SyncValue matches
,ok 135 Got right error
,ok 136 listeningPort is null
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F287E759-9DEE-41EC-A28C-0C2B4889AF65:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F287E759-9DEE-41EC-A28C-0C2B4889AF65", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B:0
2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdent,ifier":"F287E759-9DEE-41EC-A28C-0C2B4889AF65","generation":0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B", generation: 0)
2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"F287E759-9DEE-41EC-A28C-0C2B4889AF65","generation":0}'
2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B","generation":0}]'
2017-07-21 10:57:08 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B","generation":0}'
2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent du,e to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:57:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:57:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:57:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# multiConnect properly fails on legal but non-existent peerID
,2017-07-21 10:57:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:57:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 10:57:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 10:57:09 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:786B9D24-BB9C-4F79-89FE-D680E39BCE01
[ThaliCore] Browser.startListening
2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 10:57:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-21 10:57:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 137 No error on starting
ok 138 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21, 10:57:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-07-21 10:57:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to n,ative'
2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 10:57:09 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call disconnect with invalid peer id
,ok 139 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:57:10 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 10:57:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:57:10 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 10:57:10 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:29ecd5a7-bd09-4ca6-9a20-b3770760f2d8
ok 140 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:57:10 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 10:57:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:57:10 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:57:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:57:10 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:57:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 141 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BD6C4CC2-84DF-43FC-8938-C7C4968,0F3EF
[ThaliCore] Browser.startListening
2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 10:57:10 - INFO thaliMobile: 'Received state ({"discove,r,yActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 10:57:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 142 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F287E759-9DEE-41EC-A28C-0C2B4889AF65:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F287E759-9DEE-41EC-A28C-0C2B4889AF65", generation: 0)
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B","generation":0}'
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B (syncValue: mbzXhn9yJhvJHSPaWhswRv75crDMF9ja)'
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F287E759-9DEE-41EC-A28C-0C2B4889AF65","generation":0}'
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:F287E759-9DEE-41EC-A28C-0C2B4889AF65:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "F287E759-9DEE-41EC-A28C-0C2B4889AF65", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:49FFE25D-37F9-42F8-A3F5-EE8F17EC34AA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "49FFE25D-37F9-42F8-A3F5-EE8F17EC34AA", generation: 0)
2017-07-21 10:57:12 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"49FFE25D-37F9-42F8-A3F5-EE8F17EC34AA","generation":0}'
2017-07-21 10:57:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 10:57:12 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:18A68881-1F66-4E2F-A9A0-409648231FCA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "18A68881-1F66-4E2F-A9A0-409648231FCA", g,eneration: 0)
2017-07-21 10:57:12 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"18A68881-1F66-4E2F-A9A0-409648231FCA","generation":0}'
2017-07-21 10:57:12 - DEBUG thaliMobileNativeTestUtils: 'Already running ,t,est!'
2017-07-21 10:57:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 10:57:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:0F,DE9EDA-3925-4EEE-8C07-B82DDC023D3B:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,FDE9EDA-3925-4EEE-8C07-B82DDC023D3B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:0F,DE9EDA-3925-4EEE-8C07-B82DDC023D3B:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,FDE9EDA-3925-4EEE-8C07-B82DDC023D3B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 10:57:16 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"mbzXhn9yJhvJHSPaWhswRv75crDMF9ja","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 10:57:16 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'mbzXhn9yJhvJHSPaWhswRv75crDMF9ja', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 10:57:16 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 10:57:16 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 10:57:16 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-21 10:57:16 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 10:57:16 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 10:57:16 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 49FFE25D-37F9-42F8-A3F5-EE8F17EC34AA (syncValue: YSxLdGBHDQk9AZJXVPTLLJN,NaWmXSGWQ)'
2017-07-21 10:57:16 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "49FFE25D-37F9-42F8-A3F5-EE8F17EC34AA", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "49FFE25D-37F9-42F8-A3F5-EE8F17EC34AA", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:49FFE25D-37F9-42F8-A3F5-EE8F1,7EC34AA:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 10:57:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:49FFE25D-37F9-42F8-A3F5-EE8F17EC34AA:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:49FFE25D-37F9-42F8-A3F5-EE8F17EC34AA:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:49FFE25D-37F9-42F8-A3F5-EE8F17EC34AA:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "49FFE25D-37F9-42F8-A3F5-EE8F17EC34AA", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57153
2017-07-21 10:57:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"YSxLdGBHDQk9AZJXVPTLLJNNaWmXSGWQ",,"error":null,"portNumber":57153}'
,2017-07-21 10:57:19 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'YSxLdGBHDQk9AZJXVPTLLJNNaWmXSGWQ', error: 'null', listeningPort: '57153''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:49FFE25D-37F9-42F8-A3F5-EE8F17EC34AA:0
,ok 143 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "49FFE25D-37F9-42F8-A3F5-EE8F17EC34AA", generation: 0) found active relay
,2017-07-21 10:57:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6KykVde7VBJkTPsPP73n8xxLCAyA95fV","error":null,"portNumber":57153}'
,ok 144 No error
,ok 145 Ports equal
,ok 146 Got null as expected
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:49FFE25D-37F9-42F8-A3F5-EE8F17EC34AA:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [2, 12]
[ThaliCore] BrowserManager.connectToPeer(_:syn,cValue:retryCount:completion:) Peer(uuid: "49FFE25D-37F9-42F8-A3F5-EE8F17EC34AA", generation: 0) found active relay
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 10:57:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"iIlgzu91saCoAwNoNKlPu8WMSIfr8ts8","error":null,"portNumber":57153}'
,ok 147 No error
,ok 148 Ports equal
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4AA06938-FA20-4E7B-AA69-D843B64A7770
[ThaliCore] Advertiser: session connected Peer(uuid: "4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:4AA06938-FA20-4E7B-AA69-D843B64A7770 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4AA06938-FA20-4E7B-AA69-D843B64A7770
,[ThaliCore] Session.session(_:peer:didChange:) peer:4AA06938-FA20-4E7B-AA69-D843B64A7770 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4AA06938-FA20-4E7B-AA69-D843B64A7770
[ThaliCore] Session.startOutputStream(with:) peer:4AA06938-FA20-4E7B-AA69-D843B64A7770
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,3 [2, 12, 13]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-21 10:57:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 10:57:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:57:24 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:57:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9
2017-07-21 10:57:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10,:,57:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed, by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:13
[ThaliCore] VirtualSocket.closeStreams() vsID:13
[ThaliCore] BrowserManager.disconnect peer:49FFE25D-37F9-42F8-A3F5-EE8F17EC34AA
[ThaliCore] BrowserRelay.closeRelay() state:connected
[Tha,liCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57153
[ThaliCore] VirtualSocket.closeStreams() vsID:12
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] TCPListener.socketDidDiscon,nect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] VirtualSocket exited RunLoop vsID:13
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconn,ecting
[ThaliCore] VirtualSocket exited RunLoop vsID:12
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] VirtualSocket.deinit vsID:13 [2, 12]
[ThaliCore] Session.disconnect() peer:49FFE25D-37F9-42F8-A3F5-EE8F17EC34AA:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket.deinit vsID:12 [2]
,[ThaliCore] TCPListener.deinit
[ThaliCore] Session.deinit peer:49FFE25D-37F9-42F8-A3F5-EE8F17EC34AA:0
[ThaliCore] BrowserRelay.deinit
2017-07-21 10:57:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21, 10:57:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:57:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:57:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:57:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:57:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:57:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:4AA06938-FA20-4E7B-AA69-D843B64A7770 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:4AA06938-FA20-4E7B-AA69-D843B64A7770
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:4AA06938-FA20-4E7B-AA69-D843B64A7770
,# initial peer discovery
,2017-07-21 10:57:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-07-21 10:57:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:57:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:57:25 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 10:57:25 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 10:57:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 10:57:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 10:57:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-07-21 10:57:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 10:57:26 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-07-21 10:57:26 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:57:26 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 10:57:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-07-21 10:57:26 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 10:57:26 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-07-21 10:57:27 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-07-21 10:57:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:57:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:57:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 10:57:27 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 10:57:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 10:57:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 10:57:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-07-21 10:57:27 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-07-21 10:57:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:57:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:57:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 10:57:27 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 10:57:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 10:57:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 10:57:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-21 10:57:27 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 10:57:27 - DEBUG createNativeListener: 'listening 57157'
,ok 149 Should throw
,# teardown
,2017-07-21 10:57:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:27 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'listening 57159'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 10:57:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 150 initial connection state should be CONNECTED
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 151 final connection state should be DISCONNECTED
,# teardown
,2017-07-21 10:57:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 10:57:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 10:57:28 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-07-21 10:57:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 10:57:28 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'listening 57162'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 10:57:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 152 tried to connect to right port
,ok 153 failed due to refused connection
,ok 154 routerPortConnectionFailed is emitted
,# teardown
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 10:57:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 10:57:28 - DEBUG createNativeListener: 'Native Server - close'
2017-07-21 10:57:28 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'listening 57166'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 155 Send/recvd #1 should be equal length
ok 156 Send/recvd #1 should be same
ok 157 Send/recvd #2 should be equal length
ok 158 Send/recvd #2 should be same
ok 159 Should be exactly 2 client sockets
,# teardown
,2017-07-21 10:57:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 10:57:29 - DEBUG createNativeListener: 'listening 57171'
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 10:57:29 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2017-07-21 10:57:29 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node -, 0 - 0 - closed'
,ok 160 socket shouldn't close until after stream
ok 161 incoming remains open
# teardown
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 10:57:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 10:57:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 10:57:29 - DEBUG createNativeListener: 'Native Server - close'
2017-07-21 10:57:29 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'listening 57175'
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 10:57:29 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 162 we should not have gotten an error
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 163 socket shouldn't close until after incoming
,ok 164 incoming is cleaned up
,# teardown
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 10:57:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 10:57:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 10:57:29 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'listening 57179'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 10:57:30 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-07-21 10:57:30 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 165 stream was closed
ok 166 incoming should survive
ok 167 mux should have no streams
,# teardown
,2017-07-21 10:57:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'listening 57183'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 168 we should not have gotten an error
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 169 Buffers are identical
,2017-07-21 10:57:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 170 native server is nulled out
,ok 171 native server should be closed
,ok 172 incoming has been removed
,ok 173 Incoming should be done
,ok 174 The mux object should be closed
,ok 175 The mux stream should be closed
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 10:57:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'listening 57187'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 10:57:30 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-07-21 10:57:30 - DEBUG createNativeListener: 'incom,ing - incoming Android TCP/IP client connection <-> Mux - 1'
2017-07-21 10:57:30 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-07-21 10:57:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux ,- 2'
2017-07-21 10:57:30 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-07-21 10:57:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
,2017-07-21 10:57:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 176 native server is nulled out
,ok 177 native server should be closed
,ok 178 incoming has been removed
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-21 10:57:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'listening 57239'
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 10:57:32 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 179 we should not have gotten an error
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 180 Buffers are identical
2017-07-21 10:57:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-07-21 10:57:32 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client co,nnection <-> Mux - 0 - close'
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 181 server should be fine
ok 182 server should be open
ok 183 incoming has been removed
ok 184 The mux object should be clos,ed
ok 185 The mux stream should be closed
2017-07-21 10:57:32 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-21 10:57:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 10:57:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 10:57:32 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'listening 57243'
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 186 we should not have gotten an error
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 187 Buffers are identical
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 188 server should be fine
,ok 189 server should be open
,ok 190 incoming has been removed
,ok 191 The mux object should be closed
,ok 192 The mux stream should be closed
,# teardown
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 10:57:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# can create servers manager
,ok 193 serversManager must not be null
,ok 194 serversManager must be an object
,# teardown
,# setup
,# calling stop without start causes error
,ok 195 We need to call start first
,# teardown
,# setup
,# can start/stop servers manager
,2017-07-21 10:57:33 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 10:57:33 - DEBUG createNativeListener: 'listening 57246'
ok 196 port must be in range
,# teardown
,2017-07-21 10:57:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 10:57:33 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-21 10:57:33 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 10:57:33 - DEBUG createNativeListener: 'listening 57247'
ok 197 second start should return same port
,# teardown
,2017-07-21 10:57:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 10:57:33 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-21 10:57:34 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 10:57:34 - DEBUG createNativeListener: 'listening 57249'
,2017-07-21 10:57:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 10:57:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 198 we should be connected
2017-07-21 10:57:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 199 now we are disconnected
,2017-07-21 10:57:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-21 10:57:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:34 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-07-21 10:57:34 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
,ok 200 Passed bogus id
,2017-07-21 10:57:34 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
,ok 201 Passed good id but bogus port
,2017-07-21 10:57:34 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
,ok 202 Passed right context
,ok 203 Right server
,ok 204 No error should be set
,ok 205 Retry should be false
,ok 206 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 57251
,ok 207 should be equal
# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:57:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:57:34 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:57:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 10:57:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:57:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 10:57:34 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:57:34 - DEBUG thaliMobileNativeWrapper: 'Method disc,overyAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:57:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 10:57:34 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 10:57:34 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 10:57:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 10:57:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "ACEDB61A-DE2E-4167-AED9-3A55C192CFAF", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:ACEDB61A-DE2E-4167-AED9-3A55C192CFAF
,2017-07-21 10:57:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:57:34 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:57:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 208 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:0D133F74-EC2E-4B96-A318-6FC3B07,FF232
[ThaliCore] Browser.startListening
2017-07-21 10:57:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 10:57:34 - INFO thaliMobile: 'Received state ({"discove,r,yActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:57:34 - INFO thaliMob,ile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 209 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:18A68881-1F66-4E2F-A9A0-409648231FCA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "18A68881-1F66-4E2F-A9A0-409648231FCA", generation: 0)
,2017-07-21 10:57:34 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"18A68881-1F66-4E2F-A9A0-409648231FCA","generation":0}'
,2017-07-21 10:57:34 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 18A68881-1F66-4E2F-A9A0-409648231FCA (syncValue: lmUZn8QdKDU1E78a4zo5eFmAHpbfbCEu)'
,2017-07-21 10:57:34 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "18A68881-1F66-4E2F-A9A0-409648231FCA", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "18A68881-1F66-4E2F-A9A0-409648231FCA", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:18A68881-1F66-4E2F-A9A0-409648231FCA:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7C3D7BAF-2475-406D-A529-BAFFF20512EB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7C3D7BAF-2475-406D-A529-BAFFF20512EB", generation: 0)
2017-07-21 10:57:36 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"7C3D7BAF-2475-406D-A529-BAFFF20512EB","generation":0}'
2017-07-21 10:57:36 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 10:57:36 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3", generation: 0)
2017-07-21 10:57:36 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3","generation":0}'
2017-07-21 10:57:36 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 10:57:36 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 10:57:36 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ACEDB61A-DE2E-4167-AED9-3A55C192CFAF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ACEDB61A-DE2E-4167-AED9-3A55C192CFAF", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:18A68881-1F66-4E2F-A9A0-409648231FCA:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:18,A68881-1F66-4E2F-A9A0-409648231FCA:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "18A68881-1F66-4E2F-A9A0-409648231FCA", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,8A68881-1F66-4E2F-A9A0-409648231FCA", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "18A68881-1F66-4E2F-A9A0-409648231FCA", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:18A68881-1F66-4E2F-A9A0-409648231FCA:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:18A68881-1F66-4E2F-A9A0-409648231FCA:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:18A68881-1F66-4E2F-A9A0-409648231FCA:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "18A68881-1F66-4E2F-A9A0-409648231FCA", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:18A68881-1F66-4E2F-A9A0-409648231FCA:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:18,A68881-1F66-4E2F-A9A0-409648231FCA:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "18A68881-1F66-4E2F-A9A0-409648231FCA", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,8A68881-1F66-4E2F-A9A0-409648231FCA", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "18A68881-1F66-4E2F-A9A0-409648231FCA", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 10:57:40 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"lmUZn8QdKDU1E78a4zo5eFmAHpbfbCEu","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 10:57:40 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'lmUZn8QdKDU1E78a4zo5eFmAHpbfbCEu', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 10:57:40 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"18A68881-1F66-4E2F-A9A0-409648231FCA","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 10:57:40 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 10:57:40 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"18A68881-1F66-4E2F-A9A0-409648231FCA","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-21 10:57:40 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 10:57:40 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 10:57:40 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 7C3D7BAF-2475-406D-A529-BAFFF20512EB (syncValue: KEwngU5cryASp7RJhcb9GNfr6bc88nO4)'
2017-07-21 10:57:40 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7C3D7BAF-2475-406D-A529-BAFFF20512EB", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7C3D7BAF-2475-406D-A529-BAFFF20512EB", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7C3D7BAF-2475-406D-A529-BAFFF,20512EB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 10:57:40 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:18A68881-1F66-4E2F-A9A0-409648231FCA:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:7C3D7BAF-2475-406D-A529-BAFFF20512EB:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:49FFE25D-37F9-42F8-A3F5-EE8F17EC34AA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "49FFE25D-37F9-42F8-A3F5-EE8F17EC34AA", generation: 0)
2017-07-21 10:57:40 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"49FFE25D-37F9-42F8-A3F5-EE8F17EC34AA","generation":0}'
2017-07-21 10:57:40 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 10:57:40 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 10:57:40 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:06D0FB89-E071-47C1-A098-41347350B3A8
[ThaliCore] Advertiser: session connected Peer(uuid: "ACEDB61A-DE2E-4167-AED9-3A55C192CFAF", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:06D0FB89-E071-47C1-A098-41347350B3A8 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7C3D7BAF-2475-406D-A529-BAFFF20512EB:0
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D538D25B-4837-4E0A-920D-A933F5A48F3B
[ThaliCore] Session.session(_:peer:didChange:) peer:D538D25B-4837-4E0A-920D-A933F5A48F3B state: notConnected -> connecting
[ThaliCore] Advertis,er: session connected Peer(uuid: "ACEDB61A-DE2E-4167-AED9-3A55C192CFAF", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:7C3D7BAF-2475-406D-A529-BAFFF20512EB:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "7C3D7BAF-2475-406D-A529-BAFFF20512EB", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57261
2017-07-21 10:57:43 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"KEwngU5cryASp7RJhcb9GNfr6bc88nO4",,"error":null,"portNumber":57261}'
2017-07-21 10:57:43 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'KEwngU5cryASp7RJhcb9GNfr6bc88nO4', error: 'null', listeningPort: '57261''
,ok 210 should be equal
,2017-07-21 10:57:43 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3 (syncValue: XoxkWv2GQuEyjK4he8qaZt3sqkxKFwRQ)'
,2017-07-21 10:57:43 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,2017-07-21 10:57:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:06D0FB89-E071-47C1-A098-41347350B3A8
,[ThaliCore] Session.session(_:peer:didChange:) peer:06D0FB89-E071-47C1-A098-41347350B3A8 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D538D25B-4837-4E0A-920D-A933F5A48F3B
,[ThaliCore] Session.session(_:peer:didChange:) peer:D538D25B-4837-4E0A-920D-A933F5A48F3B state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57265
2017-07-21 10:57:46 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"XoxkWv2GQuEyjK4he8qaZt3sqkxKFwRQ",,"error":null,"portNumber":57265}'
2017-07-21 10:57:46 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'XoxkWv2GQuEyjK4he8qaZt3sqkxKFwRQ', error: 'null', listeningPort: '57265''
,ok 211 should be equal
# teardown
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:49FFE25D-37F9-42F8-A3F5-EE8F17EC34AA:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "49FFE25D-37F9-42F8-A3F5-EE8F17EC34AA", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 10:57:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 ,10:57:49 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-21 10:57:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:ACEDB61A-DE2E-4167-AED9-3,A55C192CFAF
2017-07-21 10:57:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:57:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:7C3D7BAF-2475-406D-A529-BAFFF20512EB
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCo,re] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57261
[ThaliCore] Session.disconnect() peer:7C3D7BAF-2475-406D-A529-BAFFF20512EB:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TC,PListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:06D0FB89-E071-47C1-A098-41347350B3A8 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "ACEDB61A-DE2E-4167-AED9-3A55C192CFAF", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:D538D25B-4837-4E0A-920D-A933F5A48F3B
,[ThaliCore] Session.session(_:peer:didChange:) peer:D538D25B-4837-4E0A-920D-A933F5A48F3B state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "ACEDB61A-DE2E-4167-AED9-3A55C192CFAF", generation: 0)
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:7C3D7BAF-2475-406D-A529-BAFFF20512EB:0
[ThaliCore] BrowserRelay.deinit
[ThaliCore] BrowserManager.disconnect peer:ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCP,Listener.stopListeningForConnectionsAndDisconnectClients() port:57265
[ThaliCore] Session.disconnect() peer:ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:D538D25B-4837-4E0A-920D-A933F5A48F3B
[ThaliCore] Session.deinit peer:ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0
[ThaliCore] BrowserRelay.deinit
2017-07-21 10:57:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:57:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:57:50 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 10:57:50 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 10:57:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 10:57:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 10:57:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple local http requests
,listening on 57267
,ok 212 should be equal
,ok 213 should be equal
,ok 214 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:57:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:57:50 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:57:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 10:57:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:57:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 10:57:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:57:50 - DEBUG thaliMobileNativeWrapper: 'Method disc,overyAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:57:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 10:57:50 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 10:57:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 10:57:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 10:57:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "86190841-1E2B-499E-89FF-674E5A3AF1A8", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:86190841-1E2B-499E-89FF-674E5A3AF1A8
2017-07-21 1,0:57:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:57:51 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:57:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 215 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:16C21EA8-3BB0-4713-BED4-74947C1BFD77
[Tha,l,iCore] Browser.startListening
2017-07-21 10:57:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 10:57:51 - INFO thaliMobile: 'Received state ({"discoveryActive":tru,e,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:57:51 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 216 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3", generation: 0)
2017-07-21 10:57:51 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3","generation":0}'
2017-07-21 10:57:51 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3, (syncValue: 7KTSczdwEzxY9AWGFOit7ogzJjba86x1)'
2017-07-21 10:57:51 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "ED6CFA85-1D6F-4A9C-AF83-CBE3587,A10C3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7C3D7BAF-2475-406D-A529-BAFFF20512EB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7C3D7BAF-2475-406D-A529-BAFFF20512EB",, generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 10:57:51 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable,":true,"peerIdentifier":"7C3D7BAF-2475-406D-A529-BAFFF20512EB","generation":0}'
2017-07-21 10:57:51 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:57:51 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5CF26575-49BF-4D5C-BE65-95FBD5115ED6:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5CF26575-49BF-4D5C-BE65-95FBD5115ED6", generation: 0)
,2017-07-21 10:57:51 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5CF26575-49BF-4D5C-BE65-95FBD5115ED6","generation":0}'
,2017-07-21 10:57:51 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:57:51 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:57:51 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:93A0D9D1-6F45-4D45-8431-EC83225FE394:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "93A0D9D1-6F45-4D45-8431-EC83225FE394", generation: 0)
,2017-07-21 10:57:52 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"93A0D9D1-6F45-4D45-8431-EC83225FE394","generation":0}'
,2017-07-21 10:57:52 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:57:52 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:57:52 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:57:52 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:86190841-1E2B-499E-89FF-674E5A3AF1A8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "86190841-1E2B-499E-89FF-674E5A3AF1A8", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:ED,6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,D6CFA85-1D6F-4A9C-AF83-CBE3587A10C3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:7C3D7BAF-2475-406D-A529-BAFFF20512EB:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "7C3D7BAF-2475-406D-A529-BAFFF20512EB", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:ED,6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,D6CFA85-1D6F-4A9C-AF83-CBE3587A10C3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4931A5EF-19CB-4D3A-ACD4-6195FBE307AC
[ThaliCore] Advertiser: session connected Peer(uuid: "86190841-1E2B-499E-89FF-674E5A3AF1A8", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:4931A5EF-19CB-4D3A-ACD4-6195FBE307AC state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:ED,6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,D6CFA85-1D6F-4A9C-AF83-CBE3587A10C3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4931A5EF-19CB-4D3A-ACD4-6195FBE307AC
,[ThaliCore] Session.session(_:peer:didChange:) peer:4931A5EF-19CB-4D3A-ACD4-6195FBE307AC state: connecting -> connected
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:ED,6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:ED6CFA85,-1D6F-4A9C-AF83-CBE3587A10C3 error: max retries exceeded
2017-07-21 10:58:02 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"7KTSczdwEzxY9AWGFOit7ogzJjba86x1","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 10:58:02 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '7KTSczdwEzxY9AWGFOit7ogzJjba86x1', error: 'Connection could not be established', listeningPort: '%s''
2017-07-21 10:58:02 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 10:58:02 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-21 10:58:02 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-21 10:58:02 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 10:58:02 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-21 10:58:02 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5CF26575-49BF-4D5C-BE65-95FBD5115ED6 (syncValue: oVNCREP,w5UZz3nqPjeXWhb7t863m5K2z)'
2017-07-21 10:58:02 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5CF26575-49BF-4D5C-BE65-95FBD5115ED6", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5CF26575-49BF-4D5C-BE65-95FBD5115ED6", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5CF26575-49BF,-4D5C-BE65-95FBD5115ED6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 10:58:02 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-07-21 10:58:02 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5CF26575-49BF-4D5C-BE65-95FBD5115ED6:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5CF26575-49BF-4D5C-BE65-95FBD5115ED6:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:5CF26575-49BF-4D5C-BE65-95FBD5115ED6:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "5CF26575-49BF-4D5C-BE65-95FBD5115ED6", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57285
2017-07-21 10:58:05 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"oVNCREPw5UZz3nqPjeXWhb7t863m5K2z",,"error":null,"portNumber":57285}'
2017-07-21 10:58:05 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'oVNCREPw5UZz3nqPjeXWhb7t863m5K2z', error: 'null', listeningPort: '57285''
,ok 217 should be equal
ok 218 should be equal
ok 219 should be equal
2017-07-21 10:58:05 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 93A0D9D1-6F45-4D45-8431-EC83225FE394 (syncValue: zbgPevsE7tH04SHSZPmQWWntKASKmOEX)'
2017-07-21 10:58:05 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "93A0D9D1-6F45-4D45-8431-EC83225FE394", generation: 0) creating a new relay
[ThaliCore] Browser.i,nviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "93A0D9D1-6F45-4D45-8431-EC83225FE394", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:93A0D9D1-6F45-4D45-8431-EC83225FE394:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 10:58:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:93A0D9D1-6F45-4D45-8431-EC83225FE394:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:86EE609A-CE7D-42B6-AA31-49F7E0E4812F
[ThaliCore] Advertiser: session connected Peer(uuid: "86190841-1E2B-499E-89FF-674E5A3AF1A8", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:86EE609A-CE7D-42B6-AA31-49F7E0E4812F state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:93A0D9D1-6F45-4D45-8431-EC83225FE394:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:86EE609A-CE7D-42B6-AA31-49F7E0E4812F
,[ThaliCore] Session.session(_:peer:didChange:) peer:93A0D9D1-6F45-4D45-8431-EC83225FE394:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "93A0D9D1-6F45-4D45-8431-EC83225FE394", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57291
,2017-07-21 10:58:08 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"zbgPevsE7tH04SHSZPmQWWntKASKmOEX","error":null,"portNumber":57291}'
,2017-07-21 10:58:08 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'zbgPevsE7tH04SHSZPmQWWntKASKmOEX', error: 'null', listeningPort: '57291''
,[ThaliCore] Session.session(_:peer:didChange:) peer:86EE609A-CE7D-42B6-AA31-49F7E0E4812F state: connecting -> connected
,ok 220 should be equal
ok 221 should be equal
,ok 222 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 10:58:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 ,10:58:09 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-21 10:58:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:86190841-1E2B-499E-89FF-6,74E5A3AF1A8
2017-07-21 10:58:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
[ThaliCore] BrowserManager.disconnect peer:5CF26575-49BF-4D5C-BE65-95FBD5115ED6
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57285
[ThaliCore] Sessi,on.disconnect() peer:5CF26575-49BF-4D5C-BE65-95FBD5115ED6:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:5CF26575-49BF-4D5C-BE65-95FBD5115ED6:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:93A0D9D1-6F45-4D45-8431-EC83225FE394
[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57291
,[ThaliCore] Session.disconnect() peer:93A0D9D1-6F45-4D45-8431-EC83225FE394:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:4931A5EF-19CB-4D3A-ACD4-6195FBE307AC state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "86190841-1E2B-499E-89FF-674E5A3AF1A8", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:86EE609A-CE7D-42B6-AA31-49F7E0E4812F
,[ThaliCore] Session.deinit peer:93A0D9D1-6F45-4D45-8431-EC83225FE394:0
[ThaliCore] BrowserRelay.deinit
2017-07-21 10:58:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:58:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:58:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:58:09 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
[ThaliCore] Session.deinit peer:86EE609A-CE7D-42B6-AA31-49F7E0E4812F
[ThaliCore] AdvertiserRelay.deinit
,2017-07-21 10:58:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 10:58:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startListeningForAdvertisements should fail if start not called
,ok 223 specific error should be returned
,# teardown
,ok 224 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:10 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:10 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:58:10 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 10:58:10 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 225 specific error should be returned
,# teardown
,ok 226 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:58:10 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 10:58:10 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'listening 57295'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 227 no errors
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 228 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 229 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startListeningForAdvertisements many times
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'listening 57296'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3226AA1B-CEDA-416A-A56A-F32FF57F1B4F
[ThaliCore] Browser.startListening
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 230 no errors
[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 231 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 10:58:11 - INFO thaliMobile: 'Received state ({"d,iscoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:58:11 - INFO ,thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisi,ngStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 10:58:11 - DEBUG makeIntoCloseAllServer: 'closeAll called, ,on server'
ok 232 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 ,10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryA,ctive":false,"advertisingActive":false}'
2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:58:11 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'listening 57297'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8D8E0967-5042-496B-A9F9-D5AFC9A94E7F", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:8D8E0967-5042-496B-A9F9-D5AFC9A94E7F
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:58:11 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 233 no errors
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8D8E0967-5042-496B-A9F9-D5AFC9A94E7F", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:8D8E0967-5042-496B-A9F9-D5AFC9A94E7F
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:58:11 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 234 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:8D8E0967-5042-496B-A9F9-D5AFC9A94E7F
[ThaliCore] Advertiser.stopAdvertising() peerID:8D8E0967-5042-496B-A9F9-D5AFC9A94E7F
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:11 - INFO thaliMobile: 'Fi,ltered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 10:58:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 235 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:11 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'listening 57300'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingAct,ive":false}'
2017-07-21 10:58:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 236 no errors
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'discover,yAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 237 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:12 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
,2017-07-21 10:58:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 10:58:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 238 must be stopped
[ThaliCore] BrowserManager.stopListenin,gForAdvertisements()
2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate ,(was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:12 - INFO thaliM,obile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:58:12 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 10:58:12 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can get the network status before starting
,ok 239 network status should have certain non-empty properties
,# teardown
,ok 240 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:12 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-21 10:58:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:58:12 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 10:58:12 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# error returned with bad router
,2017-07-21 10:58:13 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
ok 241 specific error expected
,# teardown
,ok 242 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:13 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-21 10:58:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:58:13 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 10:58:13 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are started when we call start
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'listening 57301'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D8296B3B-8908-43C1-86CD-AD1F767E7ABD
[ThaliCore] Browser.st,artListening
2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 10:58:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:58:13 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "AB99DB99-48EF-4B2C-BB62-BC447B4B54DE", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,AB99DB99-48EF-4B2C-BB62-BC447B4B54DE
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 10:58:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 10:58:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 243 all connection succeed
,# teardown
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:93A0D9D1-6F45-4D45-8431-EC83225FE394:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "93A0D9D1-6F45-4D45-8431-EC83225FE394", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5CF26575-49BF-4D5C-BE65-95FBD5115ED6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5CF26575-49BF-4D5C-BE65-95FBD5115ED6", generation: 0)
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"93A0D9D1-6F45-4D45-8431-EC83225FE394","generation":0}]'
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"93A0D9D1-6F45-4D45-8431-EC83225FE394","generation":0}'
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5CF26575-49BF-4D5C-BE65-95FBD5115ED6","generation":0}]'
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"5CF26575-49BF-4D5C-BE65-95FBD5115ED6","generation":0}'
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"93A0D9D1-6F45-4D45-8431-EC83225FE394","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 10:58:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"93A0D9D1-6F45-4D45-8431-EC83225FE394","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5CF26575-49BF-4D5C-BE65-95FBD5115ED6","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 10:58:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5CF26575-49BF-4D5C-BE65-95FBD5115ED6","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:AB99DB99-48EF-4B2C-BB62-BC447B4B54DE
2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-21 10:58:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:58:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 10:58:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 244 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate ,(was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:58:13 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# TCP Servers Manager should be null when we call start on iOS
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'listening 57304'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DC3D00DB-D6A0-4BB7-BB07-BD052B1C6294
,[ThaliCore] Browser.startListening
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 10:58:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-21 10:58:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "15D319E1-8215-4C6E-B80B-91B4E8A69563", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:15D319E1-8215-4C6E-B80B-91B4E8A69563
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 10:58:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-21 10:58:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 245 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:15D319E1-8215-4C6E-B80B-91B4E8A69563
2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-21 10:58:14 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:58:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-21 10:58:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 246 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdate,NonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:14 - DEBUG thali,MobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 10:58:14 - DEBUG ,t,haliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:14 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are stopped when we call stop
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'listening 57306'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:32B02E16-F4C5-47AB-872E-7B59283F6723
[ThaliCore] Browser.st,artListening
2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 10:58:14 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:58:14 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4FF418D3-F3AF-4ED5-8249-0C7A5E251B49", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,4FF418D3-F3AF-4ED5-8249-0C7A5E251B49
2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 10:58:14 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:58:14 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:4FF418D3-F3AF-4ED5-8249-0C7A5E251B49
2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrap,per: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 10:58:14 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"list,ening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 10:58:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21, 10:58:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 247 is stopped after calling stop
,ok 248 connection should fail after stopping
,# teardown
,ok 249 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:14 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is properly hooked up
,2017-07-21 10:58:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
,# teardown
,ok 250 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:15 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:58:15 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 10:58:15 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is return error if we get called on iOS
,ok 251 error description matches
,# teardown
,ok 252 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-21 10:58:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:58:15 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 10:58:15 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is properly hooked up
,2017-07-21 10:58:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 253 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:16 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 10:58:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:58:16 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 10:58:16 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is return error if we get called on iOS
,ok 254 error description matches
,# teardown
,ok 255 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:16 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-21 10:58:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:58:16 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 10:58:16 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure we actually call kill connections properly
,ok 256 IMPLEMENT ME!!!!!!
,# teardown
,ok 257 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:16 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-21 10:58:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:16 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-07-21 10:58:16 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 258 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:16 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-07-21 10:58:16 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 259 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-07-21 10:58:17 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 260 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:17 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:58:17 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 10:58:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-07-21 10:58:17 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 261 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 10:58:17 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 262 NOT IMPLEMENTED # SKIP
,# teardown
,ok 263 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:18 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 10:58:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 10:58:18 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure bad PSK connections fail
,2017-07-21 10:58:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 264 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:18 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 10:58:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:58:18 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peer changes handled from a queue
,2017-07-21 10:58:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 265 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:18 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 10:58:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:58:18 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-07-21 10:58:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 266 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:18 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-21 10:58:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:58:18 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-07-21 10:58:19 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 267 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:19 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'listening 57309'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D9D0E049-26B7-49D0-ACBE-C60AF8C3716C
[ThaliCore] Browser.st,artListening
2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 10:58:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:58:19 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
ok 268 discoveryActive matches
ok 269 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonT,C,P: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 10:58:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkT,ype":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:58:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisemen,ts()
[ThaliCore] Browser.stopListening()
2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:19 - INFO thaliMobile: 'Filtered out discoveryAd,vertisingStateUpdate (was in stopped state).'
ok 270 discoveryActive matches
ok 271 advertisingActive matches
2017-07-21 10:58:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'listening 57310'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "98AF4CFC-C09F-4B6B-9888-8D9208E334CE", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:98AF4CFC-C09F-4B6B-9888-8D9208E334CE
,2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 10:58:19 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 10:58:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 272 discoveryActive matches
ok 273 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:98AF4CFC-C09F-4B6B-9888-8D9208E334CE
,2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 274 discoveryActive matches
ok 275 advertisingActive matches
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"adver,tisingActive":false}'
2017-07-21 10:58:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'listening 57312'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:20 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
,2017-07-21 10:58:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 10:58:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 276 must be stopped
[ThaliCore] BrowserManager.stopListenin,gForAdvertisements()
2017-07-21 10:58:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate ,(was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:20 - INFO thaliM,obile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:58:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:58:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:20 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS
,2017-07-21 10:58:20 - DEBUG thaliMobileNativeWrapper: 'listening 57313'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6392017C-A25F-4C85-B747-B58221A78423
[ThaliCore] Browser.st,artListening
2017-07-21 10:58:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 10:58:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:58:20 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "0718B333-9577-4BCF-9755-AE8E652E9BC9", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,0718B333-9577-4BCF-9755-AE8E652E9BC9
,2017-07-21 10:58:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 10:58:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-21 10:58:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5CF26575-49BF-4D5C-BE65-95FBD5115ED6:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5CF26575-49BF-4D5C-BE65-95FBD5115ED6", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:93A0D9D1-6F45-4D45-8431-EC83225FE394:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "93A0D9D1-6F45-4D45-8431-EC83225FE394", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:45E7D383-8196-4EB7-945B-FA5CF0BF7F6A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "45E7D383-8196-4EB7-945B-FA5CF0BF7F6A", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:82D348AA-5BD5-4D47-8814-DCA8EBEEF5A3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "82D348AA-5BD5-4D47-8814-DCA8EBEEF5A3", generation: 0)
,2017-07-21 10:58:21 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5CF26575-49BF-4D5C-BE65-95FBD5115ED6","generation":0}]'
,2017-07-21 10:58:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"5CF26575-49BF-4D5C-BE65-95FBD5115ED6","generation":0}'
,2017-07-21 10:58:21 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"93A0D9D1-6F45-4D45-8431-EC83225FE394","generation":0}]'
,2017-07-21 10:58:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"93A0D9D1-6F45-4D45-8431-EC83225FE394","generation":0}'
,2017-07-21 10:58:21 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"45E7D383-8196-4EB7-945B-FA5CF0BF7F6A","generation":0}]'
,2017-07-21 10:58:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"45E7D383-8196-4EB7-945B-FA5CF0BF7F6A","generation":0}'
,2017-07-21 10:58:21 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"82D348AA-5BD5-4D47-8814-DCA8EBEEF5A3","generation":0}]'
,2017-07-21 10:58:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"82D348AA-5BD5-4D47-8814-DCA8EBEEF5A3","generation":0}'
,2017-07-21 10:58:21 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5CF26575-49BF-4D5C-BE65-95FBD5115ED6","peerAvailable":true,"generation":0,"portNumber":null}'
,ok 277 portNumber equal null
,2017-07-21 10:58:21 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"93A0D9D1-6F45-4D45-8431-EC83225FE394","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 10:58:21 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"45E7D383-8196-4EB7-945B-FA5CF0BF7F6A","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 10:58:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"45E7D383-8196-4EB7-945B-FA5CF0BF7F6A","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 10:58:21 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"82D348AA-5BD5-4D47-8814-DCA8EBEEF5A3","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 10:58:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"82D348AA-5BD5-4D47-8814-DCA8EBEEF5A3","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0718B333-9577-4BCF-9755-AE8E652E9BC9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0718B333-9577-4BCF-9755-AE8E652E9BC9", generation: 0)
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:0718B333-9577-4BCF-9755-AE8E652E9BC9
2017-07-21 10:58:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-21 10:58:22 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:58:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-21 10:58:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 278 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdate,NonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:22 - DEBUG thali,MobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 10:58:22 - DEBUG ,t,haliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:22 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests between peers
,2017-07-21 10:58:22 - DEBUG CoordinatedClient: 'test was skipped, name: 'can do HTTP requests between peers''
,# teardown
,ok 279 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {,"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:58:22 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 10:58:22 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can still do HTTP requests between peers with coordinator
,2017-07-21 10:58:22 - DEBUG CoordinatedClient: 'test was skipped, name: 'can still do HTTP requests between peers with coordinator''
,# teardown
,ok 280 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:22 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-21 10:58:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:58:22 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:22 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calls correct starts when network changes
,2017-07-21 10:58:22 - DEBUG CoordinatedClient: 'test was skipped, name: 'calls correct starts when network changes''
,# teardown
,ok 281 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:23 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 10:58:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:58:23 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 10:58:23 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# test to coordinate connection cut
,# teardown
,ok 282 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:23 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 10:58:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:58:23 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests after connections are cut
,2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'listening 57315'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:800238E4-725F-4663-8820-A044C868E9BB
[ThaliCore] Browser.startListening
,2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 10:58:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 10:58:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B73639C8-17E8-4A13-9D2F-6958AEDF8A1C", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:B73639C8-17E8-4A13-9D2F-6958AEDF8A1C
,2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 10:58:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:58:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5CF26575-49BF-4D5C-BE65-95FBD5115ED6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5CF26575-49BF-4D5C-BE65-95FBD5115ED6", generation: 0)
2017-07-21 10:58:24 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5CF26575-49BF-4D5C-BE65-95FBD5115ED6","generation":0}]'
2017-07-21 10:58:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"5CF26575-49BF-4D5C-BE65-95FBD5115ED6","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:93A0D9D1-6F45-4D45-8431-EC83225FE394:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "93A0D9D1-6F45-4D45-8431-EC83225FE394", generation: 0)
2017-07-21 10:58:24 - DEBUG t,haliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5CF26575-49BF-4D5C-BE65-95FBD5115ED6","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 10:58:24 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"pe,erIdentifier":"5CF26575-49BF-4D5C-BE65-95FBD5115ED6","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 10:58:24 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5CF26575-49BF-4D5C-BE65-95FBD5115ED6 (syncValue: JeR9HDmeXPPk9wp,zBOHlD2Yn3WaidbGQ)'
2017-07-21 10:58:24 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5CF26575-49BF-4D5C-BE65-95FBD5115ED6", generation: 0) crea,t,ing a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5CF26575-49BF-4D5C-BE65-95FBD5115ED6", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5CF26575-49BF-4D5C-BE,65-95FBD5115ED6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 10:58:24 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChang,ed event from native layer [{"peerAvailable":true,"peerIdentifier":"93A0D9D1-6F45-4D45-8431-EC83225FE394","generation":0}]'
2017-07-21 10:58:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIde,ntifier":"93A0D9D1-6F45-4D45-8431-EC83225FE394","generation":0}'
,2017-07-21 10:58:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"93A0D9D1-6F45-4D45-8431-EC83225FE394","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 10:58:24 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"93A0D9D1-6F45-4D45-8431-EC83225FE394","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FED086A1-5F45-4FC0-ADED-825912AED435:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FED086A1-5F45-4FC0-ADED-825912AED435", generation: 0)
2017-07-21 10:58:24 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"FED086A1-5F45-4FC0-ADED-825912AED435","generation":0}]'
2017-07-21 10:58:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"FED086A1-5F45-4FC0-ADED-825912AED435","generation":0}'
,2017-07-21 10:58:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"FED086A1-5F45-4FC0-ADED-825912AED435","peerAvailable":true,"generation":0,"portNumber":null}'
[ThaliCore] Browser.browser(_:foundPeer:withDi,scoveryInfo:) found peer:926130BD-656F-4D54-AF29-33CBA7483320:0
2017-07-21 10:58:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"FED086A1-5F45-4FC0-ADED-825912AED435","connectionType":"MPCF","peerAvailable":tru,e,"generation":0,"newAddressPort":false}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "926130BD-656F-4D54-AF29-33CBA7483320", generation: 0)
2017-07-21 10:58:24 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"FED086A,1-5F45-4FC0-ADED-825912AED435","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 10:58:24 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"926130BD-656F-4D54-AF29-33CBA7483320","generation":0}]'
,2017-07-21 10:58:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"926130BD-656F-4D54-AF29-33CBA7483320","generation":0}'
,2017-07-21 10:58:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"926130BD-656F-4D54-AF29-33CBA7483320","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 10:58:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"926130BD-656F-4D54-AF29-33CBA7483320","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 10:58:24 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"926130BD-656F-4D54-AF29-33CBA7483320","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D9841D76-E0DD-48DA-91C5-39D5DBCF68BD
[ThaliCore] Advertiser: session connected Peer(uuid: "B73639C8-17E8-4A13-9D2F-6958AEDF8A1C", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:D9841D76-E0DD-48DA-91C5-39D5DBCF68BD state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B73639C8-17E8-4A13-9D2F-6958AEDF8A1C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B73639C8-17E8-4A13-9D2F-6958AEDF8A1C", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:5CF26575-49BF-4D5C-BE65-95FBD5115ED6:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "5CF26575-49BF-4D5C-BE65-95FBD5115ED6", generation: 0)
[ThaliCore] Browser.browser(_:lostPeer:) lost peer,:93A0D9D1-6F45-4D45-8431-EC83225FE394:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "93A0D9D1-6F45-4D45-8431-EC83225FE394", generation: 0)
2017-07-21 10:58:25 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from n,ative layer [{"peerAvailable":false,"peerIdentifier":"5CF26575-49BF-4D5C-BE65-95FBD5115ED6","generation":0}]'
2017-07-21 10:58:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"5CF,26575-49BF-4D5C-BE65-95FBD5115ED6","generation":0}'
2017-07-21 10:58:25 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"93A0D9D1-6F45-4D45-8431-EC83225FE394","generatio,n,":0}]'
2017-07-21 10:58:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"93A0D9D1-6F45-4D45-8431-EC83225FE394","generation":0}'
,2017-07-21 10:58:25 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"5CF26575-49BF-4D5C-BE65-95FBD5115ED6","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-21 10:58:25 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"5CF26575-49BF-4D5C-BE65-95FBD5115ED6","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21 10:58:25 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnav,ailable - Emitting {"peerIdentifier":"93A0D9D1-6F45-4D45-8431-EC83225FE394","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-21 10:58:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"93A0D9D1-6F45-4D45-8431-EC83225FE394","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:5CF26575-49BF-4D5C-BE65-95FBD5115ED6:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5C,F26575-49BF-4D5C-BE65-95FBD5115ED6:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "5CF26575-49BF-4D5C-BE65-95FBD5115ED6", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,CF26575-49BF-4D5C-BE65-95FBD5115ED6", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5CF26575-49BF-4D5C-BE65-95FBD5115ED6", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 10:58:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"JeR9HDmeXPPk9wpzBOHlD2Yn3WaidbGQ","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 10:58:26 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'JeR9HDmeXPPk9wpzBOHlD2Yn3WaidbGQ', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 10:58:26 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"5CF26575-49BF-4D5C-BE65-95FBD5115ED6","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 10:58:26 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed ,event with {"peerIdentifier":"5CF26575-49BF-4D5C-BE65-95FBD5115ED6","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 10:58:26 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"5CF26575-49BF-4D5C-BE65-95FBD5115ED6","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-21 10:58:26 - DEBUG thali,MobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5CF26575-49BF-4D5C-BE65-95FBD5115ED6","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-21 10:58:26 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peer,Identifier":"5CF26575-49BF-4D5C-BE65-95FBD5115ED6","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] BrowserManager.disconnect peer:5CF26575-49BF-4D5C-BE65-95FBD5115ED6
2017-07-21 10:58:26 - ERROR thaliMobileNativeTestUtils: 'Fatal co,nnect error: 'Peer is unavailable''
2017-07-21 10:58:26 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for FED086A1-5F45-4FC0-ADED-825912AED435 (syncValue: tdOYXMCQhAUuM3eApN0it1pkrnfnVuKK)'
2017-07-21 10:58:26 - DEBUG thaliMobileNativeTestUt,ils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FED086A1-5F45-4FC0-ADED-825912AED435", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FED086A1-5F45-4FC0-ADED-825912AED435", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FED086A1-5F45-4FC0-ADED-825912AED435:0
[ThaliCore] BrowserRelay.init(session:generation:crea,teVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5CF26575-49BF-4D5C-BE65-95FBD5115ED6:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:FED086A1-5F45-4FC0-ADED-825912AED435:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:71C3A9AE-75DD-4D87-AF39-0D0785A798F9
[ThaliCore] Advertiser: session connected Peer(uuid: "B73639C8-17E8-4A13-9D2F-6958AEDF8A1C", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:71C3A9AE-75DD-4D87-AF39-0D0785A798F9 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D9841D76-E0DD-48DA-91C5-39D5DBCF68BD
,[ThaliCore] Session.session(_:peer:didChange:) peer:D9841D76-E0DD-48DA-91C5-39D5DBCF68BD state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D9841D76-E0DD-48DA-91C5-39D5DBCF68BD
[ThaliCore] Session.startOutputStream(with:) peer:D9841D76-E0DD-48DA-91C5-39D5DBCF68BD
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,4 [2, 14]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FED086A1-5F45-4FC0-ADED-825912AED435:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:FED086A1-5F45-4FC0-ADED-825912AED435:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "FED086A1-5F45-4FC0-ADED-825912AED435", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57322
2017-07-21 10:58:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"tdOYXMCQhAUuM3eApN0it1pkrnfnVuKK",,"error":null,"portNumber":57322}'
2017-07-21 10:58:29 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'tdOYXMCQhAUuM3eApN0it1pkrnfnVuKK', error: 'null', listeningPort: '57322''
,2017-07-21 10:58:29 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FED086A1-5F45-4FC0-ADED-825912AED435:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FED086A1-5F45-4FC0-ADED-825912AED435:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [2, 14, 15]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 10:58:29 - DEBUG testUtils: 'Got response data'
2017-07-21 10:58:29 - DEBUG testUtils: 'Got end'
ok 283 response body should match testData
ok 284 must be started
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:71C3A9AE-75DD-4D87-AF39-0D0785A798F9
,[ThaliCore] Session.session(_:peer:didChange:) peer:71C3A9AE-75DD-4D87-AF39-0D0785A798F9 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:71C3A9AE-75DD-4D87-AF39-0D0785A798F9
[ThaliCore] Session.startOutputStream(with:) peer:71C3A9AE-75DD-4D87-AF39-0D0785A798F9
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,6 [2, 14, 15, 16]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:16
[ThaliCore] VirtualSocket.closeStreams() vsID:16
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,16
[ThaliCore] VirtualSocket.deinit vsID:16 [2, 14, 15]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay,.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:71C3A9AE-75DD-4D87-AF39-0D0785A798F9 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "B73639C8-17E8-4A13-9D2F-6958AEDF8A1C", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:71C3A9AE-75DD-4D87-AF39-0D0785A798F9
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:71C3A9AE-75DD-4D87-AF39-0D0785A798F9
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:B73639C8-17E8-4A13-9D2F-6958AEDF8A1C
,2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 10:58:31 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 10:58:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:14
[ThaliCore] VirtualSocket.closeStreams() vsID:14
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:14
[ThaliCore] VirtualSocket.deinit vsID:14 [2, 15]
,ok 285 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:FED086A1-5F45-4FC0-ADED-825912AED435
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57322
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] VirtualSocket.closeStreams() vsID:15
,[ThaliCore] VirtualSocket exited RunLoop vsID:15
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] VirtualSocket.deinit vsID:15 [2]
,[ThaliCore] Session.disconnect() peer:FED086A1-5F45-4FC0-ADED-825912AED435:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:FED086A1-5F45-4FC0-ADED-825912AED435:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "FED086A1-5F45-4FC0-ADED-825912AED435", generation: 0)
,2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"tdOYXMCQhAUuM3eApN0it1pkrnfnVuKK","error":"Session disconnected","portNumber":null}'
,2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"FED086A1-5F45-4FC0-ADED-825912AED435","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"FED086A1-5F45-4FC0-ADED-825912AED435","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:FED086A1-5F45-4FC0-ADED-825912AED435:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:D9841D76-E0DD-48DA-91C5-39D5DBCF68BD state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "B73639C8-17E8-4A13-9D2F-6958AEDF8A1C", generation: 0)
,# will fail bad PSK connection between peers
,ok 286 FIX ME, PLEASE!!!
,# teardown
,ok 287 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:31 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 10:58:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:58:31 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 10:58:31 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We provide notification when a listener dies and we recreate it
,2017-07-21 10:58:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'We provide notification when a listener dies and we recreate it''
,# teardown
,ok 288 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:32 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 10:58:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:58:32 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 10:58:32 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated
,2017-07-21 10:58:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''
,# teardown
,ok 289 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,ok 290 ThaliMobile should be stopped
,# #startListeningForAdvertisements should fail if start not called
,ok 291 specific error should be returned
,# teardown
,2017-07-21 10:58:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"45E7D383-8196-4EB7-945B-FA5CF0BF7F6A","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21, 10:58:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"82D348AA-5BD5-4D47-8814-DCA8EBEEF5A3","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21 10:58:33 ,- DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"FED086A1-5F45-4FC0-ADED-825912AED435","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21 10:58:33 - DEBUG th,aliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"926130BD-656F-4D54-AF29-33CBA7483320","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 292 error should be null
ok 293 error should be null
,# setup
,ok 294 ThaliMobile should be stopped
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 295 specific error should be returned
,# teardown
,ok 296 error should be null
ok 297 error should be null
,# setup
,ok 298 ThaliMobile should be stopped
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-21 10:58:33 - DEBUG thaliMobileNativeWrapper: 'listening 57325'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 299 error should be null
,ok 300 error should be null
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 301 error should be null
,ok 302 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 303 error should be null
,ok 304 error should be null
,# setup
,ok 305 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-07-21 10:58:34 - DEBUG thaliMobileNativeWrapper: 'listening 57326'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F49799ED-ECA4-4A03-B5EB-E788589B7D36
[ThaliCore] Browser.st,artListening
2017-07-21 10:58:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 306 error should be null
ok 307 error should be null
[ThaliCore] BrowserManager.startListe,ningForAdvertisements
2017-07-21 10:58:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 308 error should be null
ok 309 error should be null
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FED086A1-5F45-4FC0-ADED-825912AED435:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FED086A1-5F45-4FC0-ADED-825912AED435", generation: 0)
,2017-07-21 10:58:34 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"FED086A1-5F45-4FC0-ADED-825912AED435","generation":0}]'
,2017-07-21 10:58:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"FED086A1-5F45-4FC0-ADED-825912AED435","generation":0}'
,2017-07-21 10:58:34 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"FED086A1-5F45-4FC0-ADED-825912AED435","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 10:58:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"FED086A1-5F45-4FC0-ADED-825912AED435","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 10:58:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"FED086A1-5F45-4FC0-ADED-825912AED435","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 10:58:34 - INFO thaliMobile: 'Received state ({"discoveryAc,tive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-21 10:58:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was, in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 10:58:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActi,v,e":false}'
2017-07-21 10:58:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 10:58:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 310 error should be null
,ok 311 error should be null
,# setup
,ok 312 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-21 10:58:34 - DEBUG thaliMobileNativeWrapper: 'listening 57327'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "79589211-2AB7-48D0-846A-0E56E05E2F1B", generation: 0)
[ThaliCore] Advertiser.startA,dvertising with peerID:79589211-2AB7-48D0-846A-0E56E05E2F1B
2017-07-21 10:58:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 313 error should be null
ok 314 error should, be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "79589211-2AB7-48D0-846A-0E56E05E2F1B", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:79589211-2AB7-48D0-846A-0E56E05E2F1B
20,17-07-21 10:58:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 315 error should be null
ok 316 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:79589211-2AB7-48D0-846A-0E56E05E2F1B
[ThaliCore] Advertiser.stopAdvertising() peerID:79589211-2AB7-48D0-846A-0E56E05E2F1B
2017-07-21 10:58:34 - DEBUG thaliMo,bileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:34 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 10:58:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 317 error should be null
ok 318 error should be null
,# setup
,ok 319 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-21 10:58:35 - DEBUG thaliMobileNativeWrapper: 'listening 57330'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingAct,ive":false}'
ok 320 error should be null
ok 321 error should be null
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActi,ve":false}'
ok 322 error should be null
ok 323 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-21 10:58:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 324 error should be null
ok 325 error should be null
,# setup
,ok 326 ThaliMobile should be stopped
,# #start - Causing native or wifi to fail will cause a promise reject 
,2017-07-21 10:58:35 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
,ok 327 This should not cause wifi to fail
ok 328 native router should be bad
,# teardown
,ok 329 error should be null
ok 330 error should be null
,# setup
,ok 331 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-07-21 10:58:35 - DEBUG thaliMobileNativeWrapper: 'listening 57331'
,ok 332 first call should succeed
,ok 333 first call should succeed
,ok 334 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 335 error should be null
,ok 336 error should be null
,# setup
,ok 337 ThaliMobile should be stopped
,# #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)
,2017-07-21 10:58:36 - DEBUG CoordinatedClient: 'test was skipped, name: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''
,# teardown
,ok 338 error should be null
ok 339 error should be null
,# setup
,ok 340 ThaliMobile should be stopped
,# does not emit duplicate discoveryAdvertisingStateUpdate
,2017-07-21 10:58:36 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
,# teardown
,ok 341 error should be null
ok 342 error should be null
,# setup
,ok 343 ThaliMobile should be stopped
,# does not send duplicate availability changes
,2017-07-21 10:58:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"370ececc-c8e5-4716-80fa-a6d54b958ecd","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 344 should be called once
,ok 345 should not have been called more than once
,# teardown
,2017-07-21 10:58:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"370ececc-c8e5-4716-80fa-a6d54b958ecd","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 346 error should be null
,ok 347 error should be null
,# setup
,ok 348 ThaliMobile should be stopped
,# can get the network status
,ok 349 network status should have certain non-empty properties
,# teardown
,ok 350 error should be null
ok 351 error should be null
,# setup
,ok 352 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (native)
,ok 353 we have not added peer to the cache yet
2017-07-21 10:58:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"92a27158-3de3-4a87-b977-6151b2337068","connectionType":"MPCF","peerAvailable":true,"generation":0,,"newAddressPort":false}'
ok 354 peer should be available
ok 355 cache contains native peer
2017-07-21 10:58:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"92a27158-3de3-4a87-b977-6151b2337068","connectionTyp,e":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 356 peer should be unavailable
ok 357 peer has been removed from cache
,# teardown
,ok 358 error should be null
ok 359 error should be null
,# setup
,ok 360 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 361 we have not added peer to the cache yet
2017-07-21 10:58:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"e58a409f-aae4-4e66-b585-995d29e9354e","connectionType":"tcp","peerAvailable":true,"generation":0,",newAddressPort":false}'
ok 362 peer should be available
ok 363 cache contains wifi peer
2017-07-21 10:58:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"e58a409f-aae4-4e66-b585-995d29e9354e","connectionType":,"tcp","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 364 peer should be unavailable
ok 365 peer has been removed from cache
,# teardown
,ok 366 error should be null
ok 367 error should be null
,# setup
,ok 368 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-07-21 10:58:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7bde0c2b-20b3-40f2-9772-30d11c475231","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 369 first peer is a,vailable
2017-07-21 10:58:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"40c7ca3b-843f-48dc-ae4f-0f29ba1f52ae","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 370 second, peer is available
ok 371 first and second peers are different
,# teardown
,2017-07-21 10:58:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"7bde0c2b-20b3-40f2-9772-30d11c475231","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21, 10:58:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"40c7ca3b-843f-48dc-ae4f-0f29ba1f52ae","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 372 error should be null
ok 373 error should be null
,# setup
,ok 374 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 375 should not be in cache at start
,2017-07-21 10:58:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"28521126-9872-4869-89bb-4ca602688974","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 376 peer is available
,# teardown
,2017-07-21 10:58:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"28521126-9872-4869-89bb-4ca602688974","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 377 error should be null
ok 378 error should be null
,# setup
,ok 379 ThaliMobile should be stopped
,# native available - peer with same port and different generation is cached (BLUETOOTH)
,2017-07-21 10:58:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with same port and different generation is cached (BLUETOOTH)''
,# teardown
,ok 380 error should be null
ok 381 error should be null
,# setup
,ok 382 ThaliMobile should be stopped
,# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
,2017-07-21 10:58:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''
,# teardown
,ok 383 error should be null
ok 384 error should be null
,# setup
,ok 385 ThaliMobile should be stopped
,# native available - peer with greater generation is cached (MPCF)
,2017-07-21 10:58:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b64f732e-4b1f-4fb8-baff-67468c4b2a62","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
,ok 386 peer should be available
,2017-07-21 10:58:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b64f732e-4b1f-4fb8-baff-67468c4b2a62","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 387 peer should be ,available
ok 388 should store correct generation
,# teardown
,2017-07-21 10:58:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"b64f732e-4b1f-4fb8-baff-67468c4b2a62","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 389 error should be null
ok 390 error should be null
,# setup
,ok 391 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-07-21 10:58:39 - DEBUG thaliMobileNativeWrapper: 'listening 57332'
2017-07-21 10:58:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5e3aeff8-b07c-4a2a-9d2b-0bae8bcd4bf9","connectionType":"MPCF","peerAvaila,ble":true,"generation":2,"newAddressPort":false}'
ok 392 discovered correct peer
ok 393 got correct generation
,2017-07-21 10:58:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5e3aeff8-b07c-4a2a-9d2b-0bae8bcd4bf9","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 394 discovered corr,ect peer
ok 395 got correct generation
,# teardown
,2017-07-21 10:58:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5e3aeff8-b07c-4a2a-9d2b-0bae8bcd4bf9","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:40 - INFO thaliMobile: 'Fi,ltered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 10:58:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 396 error should be null
ok 397 error should be null
,# setup
,ok 398 ThaliMobile should be stopped
,# native unavailable - new peer is ignored
,2017-07-21 10:58:40 - DEBUG thaliMobileNativeWrapper: 'listening 57333'
,2017-07-21 10:58:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"80691d13-c440-4a6b-be4e-b08330678c5e","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 399 discovered avai,lable peer
ok 400 peer is available
,# teardown
,2017-07-21 10:58:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"80691d13-c440-4a6b-be4e-b08330678c5e","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:40 - INFO thaliMobile: 'Filtered out discoveryAdvert,isingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:40 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 10:58:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 401 error should be null
ok 402 error should be null
,# setup
,ok 403 ThaliMobile should be stopped
,# native unavailable - cached peer is removed
,2017-07-21 10:58:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ef3fb215-f30c-4749-905f-e75f47c7baeb","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 404 peer should be available
2017-07-21 10:58:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ef3fb215-f30c-4749-905f-e75f47c7baeb","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPor,t":null}'
ok 405 peer should be unavailable
ok 406 should be removed from cache
,# teardown
,ok 407 error should be null
ok 408 error should be null
,# setup
,ok 409 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-07-21 10:58:40 - DEBUG thaliMobileNativeWrapper: 'listening 57334'
2017-07-21 10:58:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"23561c23-b49e-456f-861a-2f732b0b67c2","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 410 first peer is expected to be available
2017-07-21 10:58:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ccb492fa-4cf2-441e-a333-1ee18f8ec53d","connectio,nType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 411 second peer is expected to be available
2017-07-21 10:58:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"ccb492fa-4cf2-,441e-a333-1ee18f8ec53d","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 412 peer became unavailable
ok 413 it was wifi peer
2017-07-21 10:58:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handle,Peer {"peerIdentifier":"ccb492fa-4cf2-441e-a333-1ee18f8ec53d","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 414 we found peer again
ok 415 it was wifi peer
2017-07-21 10:58:40 - DEBUG thaliMobile: 'Emitting peerA,vailabilityChanged from emitPeerUnavailable {"peerIdentifier":"ccb492fa-4cf2-441e-a333-1ee18f8ec53d","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 416 peer became unavailable
ok 417 it was wifi peer
,# teardown
,2017-07-21 10:58:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"23561c23-b49e-456f-861a-2f732b0b67c2","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 418 error should be null
,ok 419 error should be null
,# setup
,ok 420 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
,2017-07-21 10:58:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''
,# teardown
,ok 421 error should be null
ok 422 error should be null
,# setup
,ok 423 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
,2017-07-21 10:58:41 - DEBUG thaliMobileNativeWrapper: 'listening 57335'
2017-07-21 10:58:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1b5f9538-ffb6-4d5c-a476-1635441601d6","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 424 first peer is expected to be available
2017-07-21 10:58:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"660f9eb7-fc93-4e8d-a656-d54a25f9948d","connectio,nType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 425 second peer is expected to be available
,2017-07-21 10:58:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1b5f9538-ffb6-4d5c-a476-1635441601d6","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 426 pee,r became unavailable
2017-07-21 10:58:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"660f9eb7-fc93-4e8d-a656-d54a25f9948d","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPor,t":null}'
ok 427 peer became unavailable
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:41 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-21 10:58:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 428 error should be null
ok 429 error should be null
,# setup
,ok 430 ThaliMobile should be stopped
,# multiconnect failure - new peer is ignored (MPCF)
,2017-07-21 10:58:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
,# teardown
,ok 431 error should be null
ok 432 error should be null
,# setup
,ok 433 ThaliMobile should be stopped
,# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
,2017-07-21 10:58:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
,# teardown
,ok 434 error should be null
,ok 435 error should be null
,# setup
,ok 436 ThaliMobile should be stopped
,# newAddressPort field (TCP_NATIVE)
,2017-07-21 10:58:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"935a9be6-5ab7-4e86-9dc2-5dbfba097b13","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 437 peer discovered first time does not have new address
2017-07-21 10:58:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"935a9be6-5ab7-4e86-9dc2-5dbfba097b13","connectionType":"tcp","peerAvailable":true,"ge,neration":20,"newAddressPort":false}'
ok 438 address has not been changed
2017-07-21 10:58:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"935a9be6-5ab7-4e86-9dc2-5dbfba097b13","connectionType":"tcp","peerAvai,lable":true,"generation":20,"newAddressPort":true}'
ok 439 new port handled correctly
2017-07-21 10:58:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"935a9be6-5ab7-4e86-9dc2-5dbfba097b13","connectionType":"tc,p","peerAvailable":true,"generation":20,"newAddressPort":true}'
ok 440 new host handled correctly
2017-07-21 10:58:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"935a9be6-5ab7-4e86-9dc2-5dbfba097b13","connec,t,ionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}'
ok 441 newAddressPort is null for unavailable peers
,# teardown
,ok 442 error should be null
ok 443 error should be null
,# setup
,ok 444 ThaliMobile should be stopped
,# newAddressPort field (BLUETOOTH)
,2017-07-21 10:58:42 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort field (BLUETOOTH)''
,# teardown
,ok 445 error should be null
ok 446 error should be null
,# setup
,ok 447 ThaliMobile should be stopped
,# newAddressPort field (MPCF)
,ok 448 NOT IMPLEMENTED # SKIP
,# teardown
,ok 449 error should be null
ok 450 error should be null
,# setup
,ok 451 ThaliMobile should be stopped
,# newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)
,2017-07-21 10:58:42 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''
,# teardown
,ok 452 error should be null
,ok 453 error should be null
,# setup
,ok 454 ThaliMobile should be stopped
,# #getPeerHostInfo - error when peer has not been discovered yet
,ok 455 should be equal
,# teardown
,ok 456 error should be null
ok 457 error should be null
,# setup
,ok 458 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)
,2017-07-21 10:58:43 - DEBUG CoordinatedClient: 'test was skipped, name: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''
,# teardown
,ok 459 error should be null
,ok 460 error should be null
,# setup
,ok 461 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)
,2017-07-21 10:58:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 462 contains expected properties
ok 463 the same hostAddress
ok 464 the same portNumber
,# teardown
,2017-07-21 10:58:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 465 error should be null
ok 466 error should be null
,# setup
,ok 467 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached wifi peer
,2017-07-21 10:58:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 468 contains expected properties
ok 469 the same hos,tAddress
ok 470 the same portNumber
,# teardown
,2017-07-21 10:58:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 471 error should be null
ok 472 error should be null
,# setup
,ok 473 ThaliMobile should be stopped
,# #disconnect fails on wifi peers
,2017-07-21 10:58:44 - DEBUG thaliMobileNativeWrapper: 'listening 57336'
2017-07-21 10:58:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"05ddde38-3122-4842-97bf-3382b680b7ec","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 474 Got specific error message
,# teardown
,2017-07-21 10:58:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"05ddde38-3122-4842-97bf-3382b680b7ec","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore], AdvertiserManager.stopAdvertising()
2017-07-21 10:58:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:44 - INFO thaliMobile: 'Filtered out discoveryAdverti,singStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:44 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 475 error should be null
,ok 476 error should be null
,# setup
,ok 477 ThaliMobile should be stopped
,# #disconnect delegates native peers to the native wrapper
,2017-07-21 10:58:44 - DEBUG thaliMobileNativeWrapper: 'listening 57337'
,2017-07-21 10:58:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f248b016-fcf9-48b7-83c2-a8ec6861d9aa","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] BrowserManager.disconnect peer:f248b016-fcf9-48b7-83c2-a8ec6861d9aa
,ok 478 native wrapper `disconnect` called once
,ok 479 native wrapper `disconnect` called with peer data
,# teardown
,2017-07-21 10:58:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"f248b016-fcf9-48b7-83c2-a8ec6861d9aa","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 480 error should be null
,ok 481 error should be null
,# setup
,ok 482 ThaliMobile should be stopped
,# network changes emitted correctly
,2017-07-21 10:58:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes emitted correctly''
,# teardown
,ok 483 error should be null
,ok 484 error should be null
,# setup
,ok 485 ThaliMobile should be stopped
,# network changes not emitted in started state
,2017-07-21 10:58:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in started state''
,# teardown
,ok 486 error should be null
ok 487 error should be null
,# setup
,ok 488 ThaliMobile should be stopped
,# network changes not emitted in stopped state
,2017-07-21 10:58:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in stopped state''
,# teardown
,ok 489 error should be null
ok 490 error should be null
,# setup
,ok 491 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on Android
,2017-07-21 10:58:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on Android''
,# teardown
,ok 492 error should be null
,ok 493 error should be null
,# setup
,ok 494 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on iOS
,2017-07-21 10:58:46 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on iOS''
,# teardown
,ok 495 error should be null
,ok 496 error should be null
,# setup
,ok 497 ThaliMobile should be stopped
,# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
,2017-07-21 10:58:46 - DEBUG CoordinatedClient: 'test was skipped, name: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''
,# teardown
,ok 498 error should be null
ok 499 error should be null
,# setup
,ok 500 ThaliMobile should be stopped
,# does not fire duplicate events after peer listener recreation
,2017-07-21 10:58:46 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not fire duplicate events after peer listener recreation''
,# teardown
,ok 501 error should be null
ok 502 error should be null
,# setup
,ok 503 ThaliMobile should be stopped
,# #stop should change peers
,2017-07-21 10:58:46 - DEBUG thaliMobileNativeWrapper: 'listening 57338'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8089C683-BC6B-4D8D-B12A-E797AF8669CA
[ThaliCore] Browser.startListening
2017-07-21 10:58:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 10:58:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5d1ae305-d2b6-4cd2-a3e2-840d078acf78","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 504 Peer availabilities has one entry for our connection type
,2017-07-21 10:58:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f52af0c8-94cb-42b9-ba51-065e2074c048","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 505 Peer availabilities has one entry for our connection type
,2017-07-21 10:58:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5d1ae305-d2b6-4cd2-a3e2-840d078acf78","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 10:58:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"f52af0c8-94cb-42b9-ba51-065e2074c048","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 10:58:46 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,1,11],"networkType":"BOTH"}})'
,2017-07-21 10:58:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 10:58:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:58:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 506 No peers
,ok 507 No peers
,ok 508 No peers
,# teardown
,ok 509 error should be null
ok 510 error should be null
,# setup
,ok 511 ThaliMobile should be stopped
,# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
,2017-07-21 10:58:47 - DEBUG thaliMobileNativeWrapper: 'listening 57339'
2017-07-21 10:58:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3707838a-9cd6-4fb8-bae7-e2b7fe1946f5","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 512 1
ok 513 2
2017-07-21 10:58:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3e2c6c90-ae41-4f3b-ab72-5ce28228ae0f","connectionType":"MPCF","peerAvailabl,e":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-07-21 10:58:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"3707838a-9cd6-4fb8-bae7-e2b7fe1946f5","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21, 10:58:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"3e2c6c90-ae41-4f3b-ab72-5ce28228ae0f","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Advertis,erManager.stopAdvertising()
2017-07-21 10:58:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingState,Update (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10,:,58:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 10:58:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 514 error should be null
ok 515 error should be null
,# setup
,ok 516 ThaliMobile should be stopped
,# peer should be found once after listening and discovery started
,2017-07-21 10:58:47 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer should be found once after listening and discovery started''
,# teardown
,ok 517 error should be null
ok 518 error should be null
,# setup
,ok 519 ThaliMobile should be stopped
,# can get data from all participants
,2017-07-21 10:58:48 - DEBUG thaliMobileNativeWrapper: 'listening 57340'
ok 520 error should be null
ok 521 error should be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4CDF9656-B658-49DA-B347-1B,EC9558B984", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:4CDF9656-B658-49DA-B347-1BEC9558B984
2017-07-21 10:58:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive,":true}'
ok 522 error should be null
ok 523 error should be null
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:51E6DCB2-5EEF-4DB9-B264-3A653DE8361E
[ThaliCore] Browser.startLi,stening
2017-07-21 10:58:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
ok 524 error should be null
,ok 525 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FED086A1-5F45-4FC0-ADED-825912AED435:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FED086A1-5F45-4FC0-ADED-825912AED435", generation: 0)
,2017-07-21 10:58:48 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"FED086A1-5F45-4FC0-ADED-825912AED435","generation":0}]'
,2017-07-21 10:58:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"FED086A1-5F45-4FC0-ADED-825912AED435","generation":0}'
,2017-07-21 10:58:48 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"FED086A1-5F45-4FC0-ADED-825912AED435","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 10:58:48 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"FED086A1-5F45-4FC0-ADED-825912AED435","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 10:58:48 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for FED086A1-5F45-4FC0-ADED-825912AED435 (syncValue: 0)'
,2017-07-21 10:58:48 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FED086A1-5F45-4FC0-ADED-825912AED435", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FED086A1-5F45-4FC0-ADED-825912AED435", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FED086A1-5F45-4FC0-ADED-825912AED435:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:67A4F3A2-48D4-4914-A36B-20CC0B58C4CA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "67A4F3A2-48D4-4914-A36B-20CC0B58C4CA", generation: 0)
2017-07-21 10:58:49 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"67A4F3A2-48D4-4914-A36B-20CC0B58C4CA","generation":0}]'
2017-07-21 10:58:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"67A4F3A2-48D4-4914-A36B-20CC0B58C4CA","generation":0}'
,2017-07-21 10:58:49 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"67A4F3A2-48D4-4914-A36B-20CC0B58C4CA","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 10:58:49 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"67A4F3A2-48D4-4914-A36B-20CC0B58C4CA","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4CDF9656-B658-49DA-B347-1BEC9558B984:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4CDF9656-B658-49DA-B347-1BEC9558B984", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6978E7D7-0C42-4D2A-9BFB-FE6FCF46417D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6978E7D7-0C42-4D2A-9BFB-FE6FCF46417D", generation: 0)
2017-07-21 10:58:50 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"6978E7D7-0C42-4D2A-9BFB-FE6FCF46417D","generation":0}]'
2017-07-21 10:58:50 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"6978E7D7-0C42-4D2A-9BFB-FE6FCF46417D","generation":0}'
,2017-07-21 10:58:50 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"6978E7D7-0C42-4D2A-9BFB-FE6FCF46417D","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 10:58:50 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6978E7D7-0C42-4D2A-9BFB-FE6FCF46417D","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:FED086A1-5F45-4FC0-ADED-825912AED435:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "FED086A1-5F45-4FC0-ADED-825912AED435", generation: 0)
2017-07-21 10:58:50 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"FED086A1-5F45-4FC0-ADED-825912AED435","generation":0}]'
2017-07-21 10:58:50 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"FED086A1-5F45-4FC0-ADED-825912AED435","generation":0}'
,2017-07-21 10:58:50 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"FED086A1-5F45-4FC0-ADED-825912AED435","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-21 10:58:50 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"FED086A1-5F45-4FC0-ADED-825912AED435","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:FED086A1-5F45-4FC0-ADED-825912AED435:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FE,D086A1-5F45-4FC0-ADED-825912AED435:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "FED086A1-5F45-4FC0-ADED-825912AED435", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,ED086A1-5F45-4FC0-ADED-825912AED435", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FED086A1-5F45-4FC0-ADED-825912AED435", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 10:58:51 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":"Peer is unavailable","portNumber":null}'
2017-07-2,1 10:58:51 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"FED086A1-5F45-4FC0-ADED-825912AED435","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 10:58:51 - DEBUG thaliMobileNativeWr,apper: 'Received peer availability changed event with {"peerIdentifier":"FED086A1-5F45-4FC0-ADED-825912AED435","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 10:58:51 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 67A4F3A2-48D4-4914-A36B-20CC0B58C4CA (syncValue: 1)'
,2017-07-21 10:58:51 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "67A4F3A2-48D4-4914-A36B-20CC0B58C4CA", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "67A4F3A2-48D4-4914-A36B-20CC0B58C4CA", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:67A4F3A2-48D4-4914-A36B-20CC0B58C4CA:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 10:58:51 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"FED086A1-5F45-4FC0-ADED-825912AED435","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-21 10:58:51 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"FED086A1-5F45-4FC0-ADED-825912AED435","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] Session.deinit peer:FED086A1-5F45-4FC0-ADED-825912AED435:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5CF26575-49BF-4D5C-BE65-95FBD5115ED6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5CF26575-49BF-4D5C-BE65-95FBD5115ED6", generation: 0)
2017-07-21 10:58:51 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5CF26575-49BF-4D5C-BE65-95FBD5115ED6","generation":0}]'
2017-07-21 10:58:51 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"5CF26575-49BF-4D5C-BE65-95FBD5115ED6","generation":0}'
,2017-07-21 10:58:51 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5CF26575-49BF-4D5C-BE65-95FBD5115ED6","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 10:58:51 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5CF26575-49BF-4D5C-BE65-95FBD5115ED6","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:67A4F3A2-48D4-4914-A36B-20CC0B58C4CA:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:67A4F3A2-48D4-4914-A36B-20CC0B58C4CA:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:67A4F3A2-48D4-4914-A36B-20CC0B58C4CA:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "67A4F3A2-48D4-4914-A36B-20CC0B58C4CA", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57346
2017-07-21 10:58:53 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":null,"portNumber":57346,}'
,2017-07-21 10:58:53 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 6978E7D7-0C42-4D2A-9BFB-FE6FCF46417D (syncValue: 2)'
2017-07-21 10:58:53 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "6978E7D7-0C42-4D2A-9BFB-FE6FCF46417D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6978E7D7-0C42-4D2A-9BFB-FE6FCF46417D", ge,neration: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6978E7D7-0C42-4D2A-9BFB-FE6FCF46417D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnec,ted:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:67A4F3A2-48D4-4914-A36B-20CC0B58C4CA:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:67A4F3A2-48D4-4914-A36B-20CC0B58C4CA:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [2, 17]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 10:58:54 - DEBUG testUtils: 'Got response data'
,2017-07-21 10:58:54 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B365D1C2-555A-4A7A-BB92-990F524EE159
[ThaliCore] Advertiser: session connected Peer(uuid: "4CDF9656-B658-49DA-B347-1BEC9558B984", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:B365D1C2-555A-4A7A-BB92-990F524EE159 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:6978E7D7-0C42-4D2A-9BFB-FE6FCF46417D:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:5CF26575-49BF-4D5C-BE65-95FBD5115ED6:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "5CF26575-49BF-4D5C-BE65-95FBD5115ED6", generation: 0)
2017-07-21 10:58:55 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"5CF26575-49BF-4D5C-BE65-95FBD5115ED6","generation":0}]'
2017-07-21 10:58:55 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"5CF26575-49BF-4D5C-BE65-95FBD5115ED6","generation":0}'
,2017-07-21 10:58:55 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"5CF26575-49BF-4D5C-BE65-95FBD5115ED6","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-21 10:58:55 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"5CF26575-49BF-4D5C-BE65-95FBD5115ED6","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D43E4AEB-4557-45D2-ABF7-C38AD8B139CF
[ThaliCore] Advertiser: session connected Peer(uuid: "4CDF9656-B658-49DA-B347-1BEC9558B984", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:D43E4AEB-4557-45D2-ABF7-C38AD8B139CF state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6978E7D7-0C42-4D2A-9BFB-FE6FCF46417D:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:6978E7D7-0C42-4D2A-9BFB-FE6FCF46417D:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "6978E7D7-0C42-4D2A-9BFB-FE6FCF46417D", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57350
2017-07-21 10:58:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":null,"portNumber":57350,}'
,[ThaliCore] BrowserManager.disconnect peer:FED086A1-5F45-4FC0-ADED-825912AED435
,2017-07-21 10:58:56 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 5CF26575-49BF-4D5C-BE65-95FBD5115ED6 (syncValue: 3)'
,2017-07-21 10:58:56 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5CF26575-49BF-4D5C-BE65-95FBD5115ED6", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5CF26575-49BF-4D5C-BE65-95FBD5115ED6", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B365D1C2-555A-4A7A-BB92-990F524EE159
,[ThaliCore] Session.session(_:peer:didChange:) peer:B365D1C2-555A-4A7A-BB92-990F524EE159 state: connecting -> connected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 10:58:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":"Peer is unavailable","portNumber":null}'
,2017-07-21 10:58:57 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"5CF26575-49BF-4D5C-BE65-95FBD5115ED6","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 10:58:57 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"5CF26575-49BF-4D5C-BE65-95FBD5115ED6","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
2017-07-21 10:58:57 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"5CF26575-49BF-4D5C-BE65-95FBD5115ED6","pe,erAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
[ThaliCore] Session.startOutputStream(with:) peer:6978E7D7-0C42-4D2A-9BFB-FE6FCF46417D:0
,2017-07-21 10:58:57 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5CF26575-49BF-4D5C-BE65-95FBD5115ED6","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] BrowserManager.disconnect peer:5CF26575-49BF-4D5C-BE65-95FBD5115ED6
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6978E7D7-0C42-4D2A-9BFB-FE6FCF46417D:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:18 [2, 17, 18]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B365D1C2-555A-4A7A-BB92-990F524EE159
[ThaliCore] Session.startOutputStream(with:) peer:B365D1C2-555A-4A7A-BB92-990F524EE159
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,9 [2, 17, 18, 19]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-21 10:58:57 - DEBUG testUtils: 'Got response data'
,2017-07-21 10:58:57 - DEBUG testUtils: 'Got end'
,ok 526 received all uuids
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D43E4AEB-4557-45D2-ABF7-C38AD8B139CF
,[ThaliCore] Session.session(_:peer:didChange:) peer:D43E4AEB-4557-45D2-ABF7-C38AD8B139CF state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D43E4AEB-4557-45D2-ABF7-C38AD8B139CF
[ThaliCore] Session.startOutputStream(with:) peer:D43E4AEB-4557-45D2-ABF7-C38AD8B139CF
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [2, 17, 18, 19, 20]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-21 10:59:02 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"67A4F3A2-48D4-4914-A36B-20CC0B58C4CA","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21, 10:59:02 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"6978E7D7-0C42-4D2A-9BFB-FE6FCF46417D","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Advertis,erManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:4CDF9656-B658-49DA-B347-1BEC9558B984
,2017-07-21 10:59:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 10:59:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-21 10:59:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] Brows,erManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 10:59:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:59:02 - INFO ,thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 10:59:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:,O,ptional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
ok 527 error should be null
ok 528 error should be null
[ThaliCore] TCPClient.socketDidDisconnect(_:with,Error:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] Ad,vertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:19
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:20
[ThaliCore] VirtualSocket.closeStreams() vsID:19
[ThaliCore] VirtualSocket.closeStreams() vsID:,20
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:19
[ThaliCore] VirtualSocket.deinit vsID:19 [2, 17, 18, 20]
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:20
[ThaliCore] VirtualSocket.deinit vsID:20 [2, 17, 18]
,# setup
,ok 529 ThaliMobile should be stopped
,# test for data corruption
,2017-07-21 10:59:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'test for data corruption''
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:17
[ThaliCore] VirtualSocket.closeStreams() vsID:17
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:17
[ThaliCore] VirtualSocket.deinit vsID:17 [2, 18]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:18
[ThaliCore] VirtualSocket.closeStreams() vsID:18
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:18
[ThaliCore] VirtualSocket.deinit vsID:18 [2]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:ni,l
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,# teardown
,ok 530 error should be null
ok 531 error should be null
,# setup
,# #testThaliPeerAction - test getters
,ok 532 getPeerIdentifier
ok 533 getConnectionType
ok 534 getActionType
,ok 535 getActionState
ok 536 getPskIdentity
ok 537 getPskKey
,# teardown
,# setup
,# #testThaliPeerAction - start and kill
,ok 538 initial state
ok 539 after start
2017-07-21 10:59:04 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 540 after kill
,# teardown
,# setup
,# #testThaliPeerAction - double start
,ok 541 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - start after kill
,2017-07-21 10:59:04 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 542 clean kill
,ok 543 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - make sure ids are unique
,ok 544 should not be equal
,# teardown
,# setup
,# #testThaliPeerAction - check that forever agent can be destroyed
,ok 545 forever agent should have it's own destroy method
,ok 546 agent's destroy should be called
ok 547 agent's destroy should not be called again
ok 548 agent is destroyed
,# teardown
,# setup
,# Test PeerDictionary basic functionality
,ok 549 Entry counter must be 1
,ok 550 Entry exists
,ok 551 Size must be 1
,ok 552 Entry counter must be 2
,ok 553 Entry exists
,ok 554 Size must be 2
,ok 555 Entry counter must be 1
,ok 556 Entry exists
,ok 557 Size must be 3
,ok 558 Entry counter must be 2
,ok 559 Entry exists
,ok 560 Size must be 4
,ok 561 Entry 1_1 should not be found
,ok 562 Entry 1_1 does not exist
,ok 563 Size must be 3
,ok 564 Entry 1_2 should not be found
,ok 565 Entry 1_2 does not exist
,ok 566 Size must be 2
,ok 567 should be equal
,ok 568 Entry 2_1 should not be found
,ok 569 Entry 2_2 should not be found
,ok 570 Entry 2_1 does not exist
,ok 571 Entry 2_2 does not exist
,ok 572 Size must be 0
,# teardown
,# setup
,# Test PeerDictionary with multiple entries.
,ok 573 Size must be100
,ok 574 Entries between 20 and MAXSIZE + 20 should exist
,ok 575 WAITING state entry should not be removed
,# teardown
,# setup
,# RESOLVED entries are removed before WAITING state entry.
,ok 576 Entries between 6 and MAXSIZE + 4 should exist
ok 577 Size should be MAXSIZE
,ok 578 Size should be MAXSIZE+6
,# teardown
,# setup
,# WAITING entries are removed before CONTROLLED_BY_POOL state entry.
,ok 579 WAITING state entry should not be removed
,ok 580 Waiting entries between 6 and MAXSIZE + 4 should exist
,ok 581 Size should be MAXSIZE
,ok 582 entryCounter should be MAXSIZE+6
,# teardown
,# setup
,# When CONTROLLED_BY_POOL entry is removed and kill is called.
,ok 583 Kill should be called once
,ok 584 Size should be MAXSIZE
,# teardown
,# setup
,# #ThaliPeerPoolDefault - single action
,ok 585 is an agent
,ok 586 enqueue is fine
ok 587 Everything should be off the queue
,# teardown
,# setup
,# #ThaliPeerPoolDefault - multiple actions
,ok 588 is an agent
ok 589 first enqueue is fine
,ok 590 is an agent
ok 591 second enqueue is fine
ok 592 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 593 Queue is empty
,# teardown
,# setup
,# #ThaliPeerPoolDefault - PSK Pool works
,ok 594 is an agent
ok 595 good enqueue
,ok 596 Identity should match
,2017-07-21 10:59:09 - DEBUG testUtils: 'Got response data'
,2017-07-21 10:59:09 - DEBUG testUtils: 'Got end'
,ok 597 Got expected response
,ok 598 Got psk call back
,# teardown
,2017-07-21 10:59:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #ThaliPeerPoolDefault - stop
,ok 599 is an agent
ok 600 enqueue worked
,ok 601 is an agent
,ok 602 enqueue 2 worked
,ok 603 enqueue is not available when stopped
,ok 604 start action is killed
,ok 605 killed action is still killed
,ok 606 enqueued action when stopped is killed
,ok 607 inQueue is empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that start verifies queue length
,ok 608 good start
ok 609 good enqueue
,ok 610 queue is not empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - bad enqueues
,ok 611 null arg
ok 612 wrong arg type
ok 613 wrong arg type
,# teardown
,# setup
,# #ThaliPeerPoolInterface - do not allow same object type
,ok 614 good enqueue
ok 615 already enqueued
# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
,ok 616 good enqueue
,ok 617 2nd good enqueue
,ok 618 we are in the pool
,ok 619 We are out of the pool
,ok 620 Action was killed
,ok 621 The original kill was called too
,ok 622 second item is still in queue
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
,ok 623 good enqueue
,ok 624 first kill
,ok 625 second NOOP kill
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that stop removes all actions
,ok 626 1st good enqueue
,ok 627 2nd good enqueue
,ok 628 1st action is in the pool
,ok 629 2nd action is in the pool
,ok 630 1st action is out of the pool
,ok 631 2st action is out of the pool
,ok 632 pool is empty
,# teardown
,# setup
,# We reject unrecognized connection type
,2017-07-21 10:59:12 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 633 Got right error
,ok 634 Start should not be called
,ok 635 Kill should have been called at least once
,# teardown
,# setup
,# We reject unrecognized action type
,2017-07-21 10:59:12 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-21 10:59:12 - ERROR thaliPeerPoolOneAtATime: 'Got unsupported action type: blah'
,ok 636 Got right error
,ok 637 Start should not be called
,ok 638 Kill should have been called at least once
,# teardown
,# setup
,# One action on bluetooth
,2017-07-21 10:59:13 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 639 Got null
2017-07-21 10:59:13 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier,: peerID'
ok 640 is an agent
2017-07-21 10:59:13 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 641 Got killed at least once
,# teardown
,# setup
,# Two notification actions
,2017-07-21 10:59:13 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 642 Got Null
ok 643 Got another null
2017-07-21 10:59:13 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidB,luetooth, Peer Identifier: peerId1'
ok 644 is an agent
2017-07-21 10:59:13 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peer,Id1'
2017-07-21 10:59:13 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 645 is an agent
,2017-07-21 10:59:13 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 646 Action 1 killed at least once
,ok 647 Action 1 went first
,ok 648 Action 2 killed at least once
,# teardown
,# setup
,# replicateThroughProblems
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 649 should have gotten null
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activity time out - noActivityTimeOut'
,ok 650 Should have stopped nicely
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButNotAvailable'
,ok 651 Still looking for null
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'Replication action failed badly so we are going to retry'
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 652 Yup, another null
,ok 653 We cloned!
,# teardown
,# setup
,# Replication goes first
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 654 Null 1
ok 655 (unnamed assert)
2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBlu,etooth, Peer Identifier: notificationAction'
ok 656 is an agent
ok 657 Null 3
ok 658 Replication not yet called
ok 659 Notification 2 not yet called
2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action, ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidB,luetooth, Peer Identifier: replicationAction'
ok 660 is an agent
ok 661 Notification went first
ok 662 Notification 2 not called yet
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
2017-07-21 10:59:14 - DEBUG thaliPeerPoo,lOneAtATime: 'Got a replication response with no error!'
2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
ok 663 is, an agent
ok 664 Notification finished
ok 665 Replication finished
2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Ide,ntifier: notificationAction'
,# teardown
,# setup
,# wifi allows many parallel non-replication actions
,2017-07-21 10:59:15 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-21 10:59:15 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,ok 666 is an agent
,ok 667 First does not throw
,2017-07-21 10:59:15 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,ok 668 is an agent
,ok 669 Second does not throw
,2017-07-21 10:59:15 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,truetruefalsetrue
,2017-07-21 10:59:15 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,truetruetruetrue
,# teardown
,# setup
,# wifi allows no more than 2 simultaneous replication actions for same peerID
,2017-07-21 10:59:15 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-21 10:59:15 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 670 is an agent
,ok 671 first ok
,2017-07-21 10:59:15 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 672 is an agent
,ok 673 second ok
,ok 674 third ok
,2017-07-21 10:59:15 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-07-21 10:59:15 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-07-21 10:59:15 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-21 10:59:15 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,# teardown
,# setup
,# Client to server request coordinated
,2017-07-21 10:59:16 - DEBUG CoordinatedClient: 'test was skipped, name: 'Client to server request coordinated''
,# teardown
,2017-07-21 10:59:16 - INFO testThaliNotification: 'Participants:0 Peers Replied to us:0 Peers requested to:0'
,# setup
,# Test BEACONS_RETRIEVED_AND_PARSED locally
,ok 675 peerIdentifier should match
,ok 676 generation should match
,ok 677 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 678 good beacon
,ok 679 good preAmble
,ok 680 public keys match!
,ok 681 must return null after successful call
,ok 682 Once start returns the action should be in KILLED state
,# teardown
,2017-07-21 10:59:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test HTTP_BAD_RESPONSE locally
,2017-07-21 10:59:17 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test HTTP_BAD_RESPONSE locally''
,# teardown
,2017-07-21 10:59:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test NETWORK_PROBLEM locally
,ok 683 Response should be NETWORK_PROBLEM
ok 684 reject reason should be: Could not establish TCP connection
,# teardown
,2017-07-21 10:59:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails when getPeerHostInfo fails
,ok 685 Resolution should be BAD_PEER
,ok 686 correct error message
,# teardown
,2017-07-21 10:59:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the start two times
,ok 687 Call start once
,ok 688 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 689 must return null after successful call.
,# teardown
,2017-07-21 10:59:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill before calling the start
,ok 690 Should be Killed
,ok 691 Start after killed
,# teardown
,2017-07-21 10:59:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill immediately after the start
,ok 692 Should be KILLED
,ok 693 must return null after successful kill
,# teardown
,2017-07-21 10:59:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill while waiting a response from the server
,ok 694 Should be KILLED
ok 695 must return null after successful kill
,# teardown
,2017-07-21 10:59:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test to exceed the max content size locally
,ok 696 HTTP_BAD_RESPONSE should be response when content size is exceeded
ok 697 must return null after successful call
,# teardown
,2017-07-21 10:59:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Close the server socket while the client is waiting a response from the server. Local test.
,2017-07-21 10:59:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 698 Should be NETWORK_PROBLEM caused closing server socket
ok 699 Should be Could not establish TCP connection
,# teardown
,# setup
,# Close the client socket while the client is waiting a response from the server. Local test.
,ok 700 Should be NETWORK_PROBLEM caused closing client socket
ok 701 Should be Could not establish TCP connection
,# teardown
,2017-07-21 10:59:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #generatePreambleAndBeacons bad args
,ok 702 publicKeysToNotify cannot be null
ok 703 ecdh for local device cannot be null
ok 704 milliseconds cannot be less than 0
ok 705 milliseconds cannot be 0
ok 706 milliseconds cannot be greater than one_day
,# teardown
,# setup
,# #generatePreambleAndBeacons empty keys to notify
,ok 707 should be equal
,# teardown
,# setup
,# #generatePreambleAndBeacons multiple keys to notify
,ok 708 should be equal
ok 709 should be equal
,ok 710 (unnamed assert)
,ok 711 should be equal
,# teardown
,# setup
,# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
,ok 712 should throw
,# teardown
,# setup
,# #parseBeacons invalid expiration in beaconStreamWithPreAmble
,ok 713 Preamble expiration must be a 64 bit integer
,# teardown
,# setup
,# #parseBeacons expiration out of range lower
,ok 714 Expiration out of range
,# teardown
,# setup
,# #parseBeacons expiration out of range lower
,ok 715 Expiration out of range
,# teardown
,# setup
,# #parseBeacons no beacons returns null
,ok 716 should be equal
,# teardown
,# setup
,# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
,ok 717 Malformed encrypted beacon key ID
,# teardown
,# setup
,# #parseBeacons addressBookCallback fails decrypt
,ok 718 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns no matches
,2017-07-21 10:59:30 - DEBUG CoordinatedClient: 'test was skipped, name: '#parseBeacons addressBookCallback returns no matches''
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns spurious match
,ok 719 should be equal
,ok 720 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns public key
,ok 721 right number of calls to address book
ok 722 good preAmble
,ok 723 good unencryptedKeyId
,ok 724 good beacon
,# teardown
,# setup
,# validate generatePskIdentityField
,ok 725 decoded buffers match
,# teardown
,# setup
,# validate generatePskSecret
,ok 726 secrets match
,# teardown
,# setup
,# validate generatePskSecrets
,ok 727 Matching numbers
,ok 728 We have an entry!
,ok 729 keys match
,ok 730 secrets match
,ok 731 We have an entry!
,ok 732 keys match
,ok 733 secrets match
,ok 734 We have an entry!
ok 735 keys match
ok 736 secrets match
,# teardown
,# setup
,# validate generateBeaconStreamAndSecrets
,ok 737 Streams have same length
,ok 738 matching size
,ok 739 keys match
,ok 740 secrets match
,# teardown
,# setup
,# Add two Peers.
,ok 741 should be equal
,ok 742 peerDictionalty contains 2 peers
,ok 743 bluetooth peer's notification has correct connection type
,ok 744 tcp peer's notification has correct connection type
,2017-07-21 10:59:33 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,2017-07-21 10:59:33 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-21 10:59:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# TCP_NATIVE peer loses DNS
,ok 745 notification peer dictionary contains exactly 1 peer
2017-07-21 10:59:34 - WARN thaliNotificationClient: 'peer is not available'
,ok 746 notification peer dictionary does not contain any peers
,2017-07-21 10:59:34 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-21 10:59:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Received beacons with no values for us
,ok 747 entry exists
,ok 748 entry is resolved
,# teardown
,2017-07-21 10:59:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Notification action killed with a superseded
,ok 749 Action should be KILLED
,ok 750 Peer state should be RESOLVED
,# teardown
,2017-07-21 10:59:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally
,ok 751 hostAddress must match
,ok 752 portNumber must match
,ok 753 suggestedTCPTimeout must match
,ok 754 connectionType must match
,ok 755 peerIDs must match
,# teardown
,2017-07-21 10:59:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 756 Correct error
,# teardown
,2017-07-21 10:59:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally using ThaliPeerPoolDefault
,ok 757 hostAddress must match
,ok 758 portNumber must match
,ok 759 suggestedTCPTimeout must match
,ok 760 connectionType must match
,ok 761 peerIds must match
,# teardown
,2017-07-21 10:59:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails because of a bad hostname.
,2017-07-21 10:59:37 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 762 action should be resolved with NETWORK_PROBLEM error
,2017-07-21 10:59:37 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 763 action should be resolved with NETWORK_PROBLEM error
,2017-07-21 10:59:37 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 764 action should be resolved with NETWORK_PROBLEM error
,2017-07-21 10:59:38 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 765 action should be resolved with NETWORK_PROBLEM error
ok 766 correct number of requests
ok 767 correct number of failures
ok 768 correct final peer state
,# teardown
,2017-07-21 10:59:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# hostaddress is removed when the action is running. 
,2017-07-21 10:59:40 - WARN thaliNotificationClient: 'peer is not available'
2017-07-21 10:59:40 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 769 peerDictionary should become empty
,# teardown
,2017-07-21 10:59:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notificationClient does not retry action with BAD_PEER resolution
,2017-07-21 10:59:41 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 770 failed with expected error
,ok 771 peer state should be RESOLVED
,# teardown
,2017-07-21 10:59:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notification client correctly handles peer availability changes of the same peer
,2017-07-21 10:59:41 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 772 First action failed
,ok 773 second action killed
# teardown
,2017-07-21 10:59:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Client to server request locally
,ok 774 secrets are equal
,ok 775 Public key matches with the server key
ok 776 hostAddress must match
,ok 777 portNumber must match
,ok 778 suggestedTCPTimeout must match
ok 779 connectionType must match
,# teardown
,2017-07-21 10:59:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache clean and expiration
,ok 780 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
,ok 781 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
,ok 782 All entries should be expired after 1 second
# teardown
,2017-07-21 10:59:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache getSecret and getPublic
,ok 783 All keys need to be available in the cache
,ok 784 All entries should be expired after 1 second
,# teardown
,2017-07-21 10:59:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache multiple entries
,ok 785 Size of the cache should be 2
ok 786 Cache doesn't contain dictionary1
,ok 787 Size of the cache should be 1
ok 788 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
,2017-07-21 10:59:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start and stop ThaliNotificationServer
,ok 789 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
,ok 790 ThaliMobile.StopAdvertisingAndListeningshould be called once
,# teardown
,2017-07-21 10:59:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty array to ThaliNotificationServer.start
,ok 791 StartUpdateAdvertisingAndListening should not be called
,ok 792 ThaliMobile.StopAdvertisingAndListening should be called once
,ok 793 no error
,ok 794 should be 204
,# teardown
,2017-07-21 10:59:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass a string to ThaliNotificationServer.start
,ok 795 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-21 10:59:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty parameter to ThaliNotificationServer.start
,ok 796 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-21 10:59:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons
,ok 797 no error
,ok 798 should be 200
,ok 799 should be equal
,ok 800 should be equal
,ok 801 (unnamed assert)
,ok 802 no error
ok 803 should be 204
,# teardown
,2017-07-21 10:59:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons (no keys)
,ok 804 error should be null
ok 805 should be 204
# teardown
,2017-07-21 10:59:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeaconsbefore calling start
,ok 806 should be 404
# teardown
,2017-07-21 10:59:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure peerDictionaryKey is reasonable
,ok 807 equal keys
ok 808 not equal connection type
,ok 809 same connection type, different buffer
,# teardown
,# setup
,# Make sure start works
,2017-07-21 10:59:52 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 810 First start and on called correctly
,# teardown
,# setup
,# Make sure stop works
,ok 811 second cleared dictionary
2017-07-21 10:59:52 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 812 First start and on called correctly
,ok 813 First stop and removeListener called correctly
ok 814 first action kill called
ok 815 second action kill called
,ok 816 first cleared dictionary
ok 817 first cleared pool
ok 818 second cleared dictionary
ok 819 second cleared pool
,# teardown
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 820 Correct error
,# teardown
,# setup
,# Simple peer event
,2017-07-21 10:59:53 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,ok 821 listener has been set
ok 822 peer dictionary has expected number of entries
ok 823 Dictionary and pool have same action
ok 824 ads match
ok 825 PouchDB matches
ok 826 DB Names match
,ok 827 public keys match
,ok 828 peer dictionary has expected number of entries
,ok 829 Dictionary and pool have same action
,ok 830 ads match
,ok 831 PouchDB matches
,ok 832 DB Names match
,ok 833 public keys match
,2017-07-21 10:59:53 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
,ok 834 start called once
,ok 835 One entry left
,ok 836 Dictionary and pool have same action
,ok 837 Start never called
,ok 838 Kill called once
,ok 839 no entries left
,ok 840 Third action is dead
,ok 841 peer dictionary has expected number of entries
,ok 842 Dictionary and pool have same action
,ok 843 ads match
,ok 844 PouchDB matches
,ok 845 DB Names match
,ok 846 public keys match
,# teardown
,# setup
,# Coordinated pull replication from notification test
,2017-07-21 10:59:53 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated pull replication from notification test''
,# teardown
,# setup
,# Server is not there
,2017-07-21 10:59:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:59:53 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
,2017-07-21 10:59:53 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: connect ECONNREFUSED  and it caused us to complete'
,ok 847 right error
,# teardown
,2017-07-21 10:59:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server accepts & closes connection
,2017-07-21 10:59:54 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
,2017-07-21 10:59:54 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up  and it caused us to complete'
,ok 848 right error
,# teardown
,2017-07-21 10:59:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 500
,2017-07-21 10:59:55 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
,2017-07-21 10:59:55 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 849 Got error as expected
,# teardown
,2017-07-21 10:59:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 401
,2017-07-21 10:59:55 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
,2017-07-21 10:59:55 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 850 Got error as expected
,# teardown
,2017-07-21 10:59:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 403
,2017-07-21 10:59:56 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
,2017-07-21 10:59:56 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 851 Got error as expected
,# teardown
,2017-07-21 10:59:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with same name as local db
,2017-07-21 10:59:57 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-21 10:59:57 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-21 11:00:00 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 852 should be equal
,ok 853 All tests passed!
,# teardown
,2017-07-21 11:00:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with different name than local db
,2017-07-21 11:00:02 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-21 11:00:03 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-21 11:00:05 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 854 should be equal
ok 855 All tests passed!
,# teardown
,2017-07-21 11:00:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do nothing and make sure we time out
,2017-07-21 11:00:07 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-21 11:00:09 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-21 11:00:09 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
ok 856 action should be killed
ok 857 Error should be timed out
,ok 858 No doc found
,# teardown
,2017-07-21 11:00:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do something and make sure we time out
,2017-07-21 11:00:10 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-21 11:00:11 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,ok 859 should be equal
,2017-07-21 11:00:12 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-21 11:00:12 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
,ok 860 action should be killed
ok 861 Error should be timed out
,# teardown
,2017-07-21 11:00:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start replicating and then catch error when server goes
,ok 862 socket hung up
,# teardown
,2017-07-21 11:00:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure clone works
,ok 863 same getPeerAdvertisesDataForUs
ok 864 Same pouchdB
ok 865 same localDbName
ok 866 Same public key
,# teardown
,# setup
,# Coordinated replication action test - each device has the same local db name
,2017-07-21 11:00:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated replication action test - each device has the same local db name''
,# teardown
,# setup
,# Coordinated replication action test - each device has different local db name
,2017-07-21 11:00:17 - DEBUG thaliMobileNativeWrapper: 'listening 57479'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:5162A00F-000D-4C6B-81D4-895631E0BC01
,[ThaliCore] Browser.startListening
,2017-07-21 11:00:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "667385B3-84B4-4AAD-A98D-31F23F247C31", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:667385B3-84B4-4AAD-A98D-31F23F247C31
,2017-07-21 11:00:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C6B4B658-9B6C-4365-A441-47A5119A6F4B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C6B4B658-9B6C-4365-A441-47A5119A6F4B", generation: 0)
2017-07-21 11:00:17 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"C6B4B658-9B6C-4365-A441-47A5119A6F4B","generation":0}]'
2017-07-21 11:00:17 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"C6B4B658-9B6C-4365-A441-47A5119A6F4B","generation":0}'
,2017-07-21 11:00:17 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"C6B4B658-9B6C-4365-A441-47A5119A6F4B","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 11:00:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"C6B4B658-9B6C-4365-A441-47A5119A6F4B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 11:00:17 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for C6B4B658-9B6C-4365-A441-47A5119A6F4B (syncValue: 4)'
,2017-07-21 11:00:17 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C6B4B658-9B6C-4365-A441-47A5119A6F4B", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C6B4B658-9B6C-4365-A441-47A5119A6F4B", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C6B4B658-9B6C-4365-A441-47A5119A6F4B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D2E652DD-3DA8-412A-A000-E4D619975F36
[ThaliCore] Advertiser: session connected Peer(uuid: "667385B3-84B4-4AAD-A98D-31F23F247C31", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:D2E652DD-3DA8-412A-A000-E4D619975F36 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A4194BA7-1EB2-4E58-9EE4-605A14B2387A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A4194BA7-1EB2-4E58-9EE4-605A14B2387A", generation: 0)
,2017-07-21 11:00:18 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"A4194BA7-1EB2-4E58-9EE4-605A14B2387A","generation":0}]'
2017-07-21 11:00:18 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"A4194BA7-1EB2-4E58-9EE4-605A14B2387A","generation":0}'
,2017-07-21 11:00:18 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A4194BA7-1EB2-4E58-9EE4-605A14B2387A","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 11:00:18 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"A4194BA7-1EB2-4E58-9EE4-605A14B2387A","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:667385B3-84B4-4AAD-A98D-31F23F247C31:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "667385B3-84B4-4AAD-A98D-31F23F247C31", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:C6B4B658-9B6C-4365-A441-47A5119A6F4B:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D2E652DD-3DA8-412A-A000-E4D619975F36
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C6B4B658-9B6C-4365-A441-47A5119A6F4B:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:C6B4B658-9B6C-4365-A441-47A5119A6F4B:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "C6B4B658-9B6C-4365-A441-47A5119A6F4B", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57482
,2017-07-21 11:00:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":null,"portNumber":57482}'
,2017-07-21 11:00:21 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for A4194BA7-1EB2-4E58-9EE4-605A14B2387A (syncValue: 5)'
2017-07-21 11:00:21 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A4194BA7-1EB2-4E58-9EE4-605A14B2387A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A4194BA7-1EB2-4E58-9EE4-605A14B2387A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A4194BA7-1EB2-4E58-9EE4-605A14B2387A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:D2E652DD-3DA8-412A-A000-E4D619975F36 state: connecting -> connected
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:C6B4B658-9B6C-4365-A441-47A5119A6F4B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C6B4B658-9B6C-4365-A441-47A5119A6F4B:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:21 [2, 21]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D2E652DD-3DA8-412A-A000-E4D619975F36
[ThaliCore] Session.startOutputStream(with:) peer:D2E652DD-3DA8-412A-A000-E4D619975F36
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:22 [2, 21, 22]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:21
,[ThaliCore] VirtualSocket exited RunLoop vsID:21
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket.deinit vsID:21 [2, 22]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:C6B4B658-9B6C-4365-A441-47A5119A6F4B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C6B4B658-9B6C-4365-A441-47A5119A6F4B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:23 [2, 22, 23]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:22
[ThaliCore] VirtualSocket.closeStreams() vsID:22
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,22
[ThaliCore] VirtualSocket.deinit vsID:22 [2, 23]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.did,SocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D2E652DD-3DA8-412A-A000-E4D619975F36
[ThaliCore] Session.startOutputStream(with:) peer:D2E652DD-3DA8-412A-A000-E4D619975F36
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:24 [2, 23, 24]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D70C0246-53B9-45DE-9A1F-0F5509EBDD57
[ThaliCore] Advertiser: session connected Peer(uuid: "667385B3-84B4-4AAD-A98D-31F23F247C31", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:D70C0246-53B9-45DE-9A1F-0F5509EBDD57 state: notConnected -> connecting
,2017-07-21 11:00:21 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:C6B4B658-9B6C-4365-A441-47A5119A6F4B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C6B4B658-9B6C-4365-A441-47A5119A6F4B:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:25 [2, 23, 24, 25]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D2E652DD-3DA8-412A-A000-E4D619975F36
[ThaliCore] Session.startOutputStream(with:) peer:D2E652DD-3DA8-412A-A000-E4D619975F36
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:26 [2, 23, 24, 25, 26]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:C6B4B658-9B6C-4365-A441-47A5119A6F4B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C6B4B658-9B6C-4365-A441-47A5119A6F4B:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:27 [2, 23, 24, 25, 26, 27]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D2E652DD-3DA8-412A-A000-E4D619975F36
[ThaliCore] Session.startOutputStream(with:) peer:D2E652DD-3DA8-412A-A000-E4D619975F36
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:28 [2, 23, 24, 25, 26, 27, 28]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:peer:didChange:) peer:A4194BA7-1EB2-4E58-9EE4-605A14B2387A:0 state: notConnected -> connecting
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:C6B4B658-9B6C-4365-A441-47A5119A6F4B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C6B4B658-9B6C-4365-A441-47A5119A6F4B:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:29 [2, 23, 24, 25, 26, 27, 28, 29]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:C6B4B658-9B6C-4365-A441-47A5119A6F4B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C6B4B658-9B6C-4365-A441-47A5119A6F4B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:30 [2, 23, 24, 25, 26, 27, 28, 29, 30]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D2E652DD-3DA8-412A-A000-E4D619975F36
[ThaliCore] Session.startOutputStream(with:) peer:D2E652DD-3DA8-412A-A000-E4D619975F36
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:31 [2, 23, 24, 25, 26, 27, 28, 29, 30, 31]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D2E652DD-3DA8-412A-A000-E4D619975F36
[ThaliCore] Session.startOutputStream(with:) peer:D2E652DD-3DA8-412A-A000-E4D619975F36
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3,2 [2, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:29
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:31
[ThaliCore] VirtualSocket.closeStreams() vsID:31
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:31
,[ThaliCore] VirtualSocket.deinit vsID:31 [2, 23, 24, 25, 26, 27, 28, 29, 30, 32]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[Th,aliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D2E652DD-3DA8-412A-A000-E4D619975F36
[ThaliCore] Session.startOutputStream(with:) peer:D2E652DD-3DA8-412A-A000-E4D619975F36
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3,3 [2, 23, 24, 25, 26, 27, 28, 29, 30, 32, 33]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:C6B4B658-9B6C-4365-A441-47A5119A6F4B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C6B4B658-9B6C-4365-A441-47A5119A6F4B:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:34 [2, 23, 24, 25, 26, 27, 28, 29, 30, 32, 33, 34]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:33
[ThaliCore] VirtualSocket.closeStreams() vsID:33
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:33
[ThaliCore] VirtualSocket.deinit vsID:33 [2, 23, 24, 25, 26, 27, 28, 29, 30, 32, 34]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-21 11:00:22 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={N,SLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed,, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:34
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:34
[ThaliCore] VirtualSocket.deinit vsID:34 [2, 23, 24, 25, 26, 27, 28, 29, 30, 32]
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D70C0246-53B9-45DE-9A1F-0F5509EBDD57
,[ThaliCore] Session.session(_:peer:didChange:) peer:D70C0246-53B9-45DE-9A1F-0F5509EBDD57 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D70C0246-53B9-45DE-9A1F-0F5509EBDD57
[ThaliCore] Session.startOutputStream(with:) peer:D70C0246-53B9-45DE-9A1F-0F5509EBDD57
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3,5 [2, 23, 24, 25, 26, 27, 28, 29, 30, 32, 35]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A4194BA7-1EB2-4E58-9EE4-605A14B2387A:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:A4194BA7-1EB2-4E58-9EE4-605A14B2387A:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "A4194BA7-1EB2-4E58-9EE4-605A14B2387A", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57500
,2017-07-21 11:00:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5","error":null,"portNumber":57500}'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:35
[ThaliCore] VirtualSocket.closeStreams() vsID:35
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A4194BA7-1EB2,-4E58-9EE4-605A14B2387A:0
[ThaliCore] VirtualSocket exited RunLoop vsID:35
[ThaliCore] VirtualSocket.deinit vsID:35 [2, 23, 24, 25, 26, 27, 28, 29, 30, 32]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[Th,aliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D70C0246-53B9-45DE-9A1F-0F5509EBDD57
[ThaliCore] Session.startOutputStream(with:) peer:D70C0246-53B9-45DE-9A1F-0F5509EBDD57
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:36 [2, 23, 24, 25, 26, 27, 28, 29, 30, 32, 36]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A4194BA7-1EB2-4E58-9EE4-605A14B2387A:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:37 [2, 23, 24, 25, 26, 27, 28, 29, 30, 32, 36, 37]
[ThaliCore] BrowserRelay.didOpenVir,tualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:37
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:37
[ThaliCore] VirtualSocket.deinit vsID:37 [2, 23, 24, 25, 26, 27, 28, 29, 30, 32, 36]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A4194BA7-1EB2-4E58-9EE4-605A14B2387A:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A4194BA7-1EB2-4E58-9EE4-605A14B2387A:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:38 [2, 23, 24, 25, 26, 27, 28, 29, 30, 32, 36, 38]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D70C0246-53B9-45DE-9A1F-0F5509EBDD57
[ThaliCore] Session.startOutputStream(with:) peer:D70C0246-53B9-45DE-9A1F-0F5509EBDD57
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:39 [2, 23, 24, 25, 26, 27, 28, 29, 30, 32, 36, 38, 39]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,2017-07-21 11:00:24 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-21 11:00:24 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:23
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:23
,[ThaliCore] VirtualSocket.deinit vsID:23 [2, 24, 25, 26, 27, 28, 29, 30, 32, 36, 38, 39]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:25
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:27
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:27
,[ThaliCore] VirtualSocket.deinit vsID:27 [2, 24, 25, 26, 28, 29, 30, 32, 36, 38, 39]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:30
,[ThaliCore] VirtualSocket exited RunLoop vsID:30
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:30 [2, 24, 25, 26, 28, 29, 32, 36, 38, 39]
,2017-07-21 11:00:24 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A4194BA7-1EB2-4E58-9EE4-605A14B2387A:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A4194BA7-1EB2-4E58-9EE4-605A14B2387A:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:40 [2, 24, 25, 26, 28, 29, 32, 36, 38, 39, 40]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:24
[ThaliCore] VirtualSocket.closeStreams() vsID:24
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:24
[ThaliCore] VirtualSocket.deinit vsID:24 [2, 25, 26, 28, 29, 32, 36, 38, 39, 40]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDi,dDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:26
[ThaliCore] VirtualSocket.closeStreams() vsID:26
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:26
[ThaliCore] VirtualSocket.deinit vsID:26 [2, 25, 28, 29, 32, 36, 38, 39, 40]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDis,connect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:28
,[ThaliCore] VirtualSocket.closeStreams() vsID:28
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:28
[ThaliCore] VirtualSocket.deinit vsID:28 [2, 25, 29, 32, 36, 38, 39, 40]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:32
[ThaliCore] VirtualSocket.closeStreams() vsID:32
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D70C0246-53B9-45DE-9A1F-0F5509EBDD57
[ThaliCore] Session.startOutputStream(with:) peer:D70C0246-53B9-45DE-9A1F-0F5509EBDD57
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:41 [2, 25, 29, 32, 36, 38, 39, 40, 41]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:32
[ThaliCore] VirtualSocket.deinit vsID:32 [2, 25, 29, 36, 38, 39, 40, 41]
[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A4194BA7-1EB2-4E58-9EE4-605A14B2387A:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A4194BA7-1EB2-4E58-9EE4-605A14B2387A:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:42 [2, 25, 29, 36, 38, 39, 40, 41, 42]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A4194BA7-1EB2-4E58-9EE4-605A14B2387A:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A4194BA7-1EB2-4E58-9EE4-605A14B2387A:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:43 [2, 25, 29, 36, 38, 39, 40, 41, 42, 43]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D70C0246-53B9-45DE-9A1F-0F5509EBDD57
[ThaliCore] Session.startOutputStream(with:) peer:D70C0246-53B9-45DE-9A1F-0F5509EBDD57
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:44 [2, 25, 29, 36, 38, 39, 40, 41, 42, 43, 44]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A4194BA7-1EB2-4E58-9EE4-605A14B2387A:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A4194BA7-1EB2-4E58-9EE4-605A14B2387A:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:45 [2, 25, 29, 36, 38, 39, 40, 41, 42, 43, 44, 45]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:43
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:43
[ThaliCore] VirtualSocket.deinit vsID:43 [2, 25, 29, 36, 38, 39, 40, 41, 42, 44, 45]
,2017-07-21 11:00:25 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:36
[ThaliCore] VirtualSocket.closeStreams() vsID:36
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputSt,ream endEncountered vsID:39
[ThaliCore] VirtualSocket.closeStreams() vsID:39
[ThaliCore] VirtualSocket exited RunLoop vsID:36
[ThaliCore] VirtualSocket.deinit vsID:36 [2, 25, 29, 38, 39, 40, 41, 42, 44, 45]
[ThaliCore] TCPClient.socketDidDisconnect(_:w,ithError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:39
[ThaliCore] VirtualSocket.deinit vsID:39 [2, 25, 29, 38, 40, 41, 42, 44, 45]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDis,connect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:41
[ThaliCore] VirtualSocket.closeStreams() vsID:41
[ThaliCore] ,AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:41
[ThaliCore] VirtualSocket.deinit vsID:41 [2, 25, 29, 38, 40, 42, 44, 45]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) dis,connecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:44
[ThaliCore] VirtualSocket.closeStreams() vsID:44
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,44
[ThaliCore] VirtualSocket.deinit vsID:44 [2, 25, 29, 38, 40, 42, 45]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-21 11:00:27 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-21 11:00:27 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliC,ore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:38
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.,s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription,=Socket closed by remote peer})
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:38
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] TCPListener.socketDidDisconnec,t(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket re,moved, count:1
[ThaliCore] VirtualSocket.deinit vsID:38 [2, 25, 29, 40, 42, 45]
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] TCPListener.socketDidDisconnect,(,_:withError:) socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:40
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket.closeStream,s() vsID:42
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:45
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLo,op vsID:40
[ThaliCore] VirtualSocket.deinit vsID:40 [2, 25, 29, 42, 45]
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:42
[ThaliCore] VirtualSocket.deinit vsID:42 [2, 25, 29, 4,5]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:45
,[ThaliCore] VirtualSocket.deinit vsID:45 [2, 25, 29]
,2017-07-21 11:03:17 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2017-07-21 11:03:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:03:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:03:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:03:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:03:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:03:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-4,1C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:03:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:03:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:03:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:03:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-4,1C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:04:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:04:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:04:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:04:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:04:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:04:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:04:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:04:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-4,1C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:04:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:04:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:04:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:04:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:05:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:05:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:05:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:05:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:05:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:05:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:05:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:05:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:05:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:05:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:05:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:05:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:06:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:06:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:06:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:06:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:06:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:06:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:06:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:06:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:06:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:06:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:06:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:06:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:07:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:07:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:07:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:07:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:07:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:07:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:07:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:07:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:07:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:07:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-4,1C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:07:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:07:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:08:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:08:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:08:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:08:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:08:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:08:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:08:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:08:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:08:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:08:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:08:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:08:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:09:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:09:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:09:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:09:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-4,1C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:09:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:09:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:09:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:09:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:09:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:09:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:09:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:09:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-4,1C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:10:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:10:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-4,1C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:10:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:10:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server that is not listening yet witheatNotRunning set to true'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue and run in order'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiConnect properly fails on legal but non-existent peerID'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with invalid syncValue'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call disconnect with invalid peer id'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - disconnect doesn't fail on plausible but bogus peer ID'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Get same port when trying to connect multiple times on iOS'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - initial peer discovery'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 1'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 2'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - check latest peer discovery'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Set up for no peer discovery test'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - no peer discovery'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits incomingConnectionState'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server connections all up'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can create servers manager'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling stop without start causes error'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can start/stop servers manager'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connection'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single local http request'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single coordinated request ios native'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple local http requests'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple coordinated request ios native'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status before starting'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - error returned with bad router'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are started when we call start'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP Servers Manager should be null when we call start on iOS'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are stopped when we call stop'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateConnection is properly hooked up'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateConnection is return error if we get called on iOS'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateListener is properly hooked up'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateListener is return error if we get called on iOS'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure we actually call kill connections properly'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from multiConnectConnection'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure bad PSK connections fail'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer changes handled from a queue'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - relaying discoveryAdvertisingStateUpdateNonTCP'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - we successfully receive and replay discoveryAdvertisingStateUpdate'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - can do HTTP requests between peers'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - can still do HTTP requests between peers with coordinator'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - calls correct starts when network changes'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test to coordinate connection cut'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests after connections are cut'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - will fail bad PSK connection between peers'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We provide notification when a listener dies and we recreate it'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start - Causing native or wifi to fail will cause a promise reject '
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start should fail if called twice in a row'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not emit duplicate discoveryAdvertisingStateUpdate'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - does not send duplicate availability changes'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (native)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (wifi)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - new peer is cached'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with same port and different generation is cached (BLUETOOTH)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with greater generation is cached (MPCF)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with same or older generation is ignored (MPCF)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - new peer is ignored'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - cached peer is removed'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for wifi peers'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - new peer is ignored (MPCF)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (TCP_NATIVE)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort field (BLUETOOTH)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (MPCF)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - error when peer has not been discovered yet'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached wifi peer'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect fails on wifi peers'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect delegates native peers to the native wrapper'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes emitted correctly'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in started state'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in stopped state'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on Android'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on iOS'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not fire duplicate events after peer listener recreation'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #stop should change peers'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer should be found once after listening and discovery started'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get data from all participants'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - test for data corruption'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - test getters'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start and kill'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - double start'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start after kill'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - make sure ids are unique'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - check that forever agent can be destroyed'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary basic functionality'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary with multiple entries.'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - RESOLVED entries are removed before WAITING state entry.'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - WAITING entries are removed before CONTROLLED_BY_POOL state entry.'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - When CONTROLLED_BY_POOL entry is removed and kill is called.'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - single action'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - multiple actions'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - PSK Pool works'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - stop'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that start verifies queue length'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - bad enqueues'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - do not allow same object type'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure we catch kill and dequeue'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that stop removes all actions'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized connection type'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized action type'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One action on bluetooth'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Two notification actions'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - replicateThroughProblems'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Replication goes first'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows many parallel non-replication actions'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows no more than 2 simultaneous replication actions for same peerID'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Client to server request coordinated'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test BEACONS_RETRIEVED_AND_PARSED locally'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test HTTP_BAD_RESPONSE locally'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test NETWORK_PROBLEM locally'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails when getPeerHostInfo fails'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the start two times'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill before calling the start'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill immediately after the start'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill while waiting a response from the server'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test to exceed the max content size locally'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the server socket while the client is waiting a response from the server. Local test.'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the client socket while the client is waiting a response from the server. Local test.'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons bad args'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons empty keys to notify'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons multiple keys to notify'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid expiration in beaconStreamWithPreAmble'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons no beacons returns null'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback fails decrypt'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #parseBeacons addressBookCallback returns no matches'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns spurious match'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns public key'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskIdentityField'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecret'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecrets'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generateBeaconStreamAndSecrets'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Add two Peers.'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP_NATIVE peer loses DNS'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Received beacons with no values for us'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Notification action killed with a superseded'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally using ThaliPeerPoolDefault'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails because of a bad hostname.'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - hostaddress is removed when the action is running. '
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notificationClient does not retry action with BAD_PEER resolution'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notification client correctly handles peer availability changes of the same peer'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Client to server request locally'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache clean and expiration'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache getSecret and getPublic'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache multiple entries'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start and stop ThaliNotificationServer'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty array to ThaliNotificationServer.start'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass a string to ThaliNotificationServer.start'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty parameter to ThaliNotificationServer.start'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons (no keys)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeaconsbefore calling start'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure peerDictionaryKey is reasonable'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure start works'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure stop works'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Simple peer event'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated pull replication from notification test'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server is not there'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server accepts & closes connection'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 500'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 401'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 403'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with same name as local db'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with different name than local db'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do nothing and make sure we time out'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do something and make sure we time out'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start replicating and then catch error when server goes'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure clone works'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated replication action test - each device has the same local db name'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - Coordinated replication action test - each device has different local db name, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Appl,ication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxc,ore/node_modules/bluebird/js/release/timers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1
''
,2017-07-21 11:10:16 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-07-21 11:10:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:10:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,not ok 867 failed with TimeoutError
  ---
    operator: fail
  ...
,# teardown
,2017-07-21 11:10:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:10:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:10:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:10:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:10:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:10:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:11:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:11:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:11:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:11:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:11:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:11:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:11:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:11:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:11:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:11:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:11:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:11:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:12:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:12:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:12:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:12:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:12:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:12:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:12:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:12:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:12:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:12:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:12:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:12:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:13:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:13:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:13:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:13:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:13:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:13:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:13:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:13:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:13:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:13:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:13:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:13:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:14:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:14:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:14:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C,7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:14:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/748EE95D-BF0B-41C7-A640-B30086CD9F72/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''

```
