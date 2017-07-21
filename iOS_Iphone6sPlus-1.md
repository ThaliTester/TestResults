#### Test 113351851b6d8223_iOS_Iphone6sPlus-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/113351851b6d8223/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/6F41D74D-C2E9-41B6-B68A-1039A47EB292/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'
,Executing commands in '/tmp/6F41D74D-C2E9-41B6-B68A-1039A47EB292/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/113351851b6d8223/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/113351851b6d8223/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64095"
,(lldb)     command script import "/tmp/6F41D74D-C2E9-41B6-B68A-1039A47EB292/fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.py"
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
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-07-21 15:17:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:17:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:17:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:17:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:17:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 15:17:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:17:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1019098B-C85D-4D99-98,6C-90670FAF9B0C", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:1019098B-C85D-4D99-986C-90670FAF9B0C
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BF60E18F-79A1-403A-B3CE-BE7B73C49D0E
[ThaliCore] Browser,.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E81E6FF9-DCEB-4C8E-A81D-0624D90AD4FF
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4D4324DD-8038-4B7E-9B52-2AB066F99A2A", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:4D4324DD-8038-4B7E-9B52-2AB066F99A2A
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4D4324DD-8038-4B7E-9B52-2AB066F99A2A:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4D4324DD-8038-4B7E-9B52-2AB066F99A2A", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
,AppContextTests.test_connectReturnValueCorrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-07-21 15:17:27 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  13
Number of passed tests:  13
,Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.637888967990875
,2017-07-21 15:17:27 - DEBUG UnitTest_app: 'My device name is: 'Apple-Iphone6sPlus-1''
,2017-07-21 15:17:27 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:4D4324DD-8038-4B7E-9B52-2AB066F99A2A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "4D4324DD-8038-4B7E-9B52-2AB066F99A2A", generation: 0)
,2017-07-21 15:17:28 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-21 15:17:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-21 15:17:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-21 15:17:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-21 15:17:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-21 15:17:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-21 15:17:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-21 15:17:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-21 15:17:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-21 15:17:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-21 15:17:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-21 15:17:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-21 15:17:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-21 15:17:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-21 15:17:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-21 15:17:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-21 15:17:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-21 15:17:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-21 15:17:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-21 15:17:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-21 15:17:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-21 15:17:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-21 15:17:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-21 15:17:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-21 15:17:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-21 15:17:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-21 15:17:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-21 15:17:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-21 15:17:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-21 15:17:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-21 15:17:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-21 15:17:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-21 15:17:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-21 15:17:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-21 15:17:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-21 15:17:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-21 15:17:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-21 15:17:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-21 15:17:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-21 15:17:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-21 15:17:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-21 15:17:30 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-21 15:17:30 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-21 15:17:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:17:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:17:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:17:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:17:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:17:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:17:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:17:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:17:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:18:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:18:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:18:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:18:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:18:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:18:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:18:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:18:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:18:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:18:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:18:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:18:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:19:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:19:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:19:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:19:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:19:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:19:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:19:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:19:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:19:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:19:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:19:57 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-07-21 15:19:57 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-21 15:20:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 1 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll with promise
,2017-07-21 15:20:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-21 15:20:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-07-21 15:20:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-07-21 15:20:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-07-21 15:20:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-07-21 15:20:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-07-21 15:20:06 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
,# teardown
,# setup
,# test defaultDirectory
,ok 4 should be equal
ok 5 should be equal
ok 6 should be equal
,# teardown
,# setup
,# test defaultAdapter
,ok 7 should be equal
,ok 8 should be equal
,ok 9 should be equal
,ok 10 should be equal
,ok 11 should be equal
,ok 12 should be equal
,ok 13 should be equal
,ok 14 should be equal
,# teardown
,# setup
,# enqueue and run in order
,ok 15 firstPromise setTimeout
,ok 16 firstPromise result
,ok 17 firstPromise testValue
,ok 18 secondPromise setTimeout
,ok 19 secondPromise result
,ok 20 secondPromise testValue
,ok 21 thirdPromise in promise
,ok 22 thirdPromise result
,ok 23 thirdPromise testValue
,# teardown
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
,2017-07-21 15:20:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-07-21 15:20:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-07-21 15:20:13 - DEBUG testTests: 'test spy method for global sinon sansbox'
,ok 46 test sandbox spy works correctly
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
ok 52 test participant has uuid
,ok 53 participant data matches
ok 54 test participant has uuid
ok 55 participant data matches
ok 56 own UUID is found from the participants list
,# teardown
,# setup
,# Correctly parses/stringifies USN
,ok 57 correctly parses USN string
ok 58 throws if usn has invalid prefix
ok 59 throws if usn has invalid identifier format
ok 60 throws if usn has invalid generation
ok 61 correctly stringifies peer
,# teardown
,# setup
,# onPeerLost calls jxcore
,2017-07-21 15:20:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-21 15:20:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:20:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:20:18 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:20:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:20:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:20:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:20:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:20:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-21 15:20:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-21 15:20:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:20:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:20:18 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:20:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 15:20:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:20:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:20:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:20:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:AB1CDDF2-DBC9-4E23-B114-92996C1F2271
[ThaliCore] Browser.startListening
2017-07-21 15:20:18 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 15:20:18 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-21 15:20:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvert,isements()
[ThaliCore] Browser.stopListening()
2017-07-21 15:20:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:20:19 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:20:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:20:19 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:20:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 15:20:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:20:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:20:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:20:19 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:20:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 15:20:19 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 15:20:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 15:20:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 15:20:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:0C9EE40A-5AE4-4CD8-862C-E7BFE21346A2
[ThaliCore] Browser.startListening
,2017-07-21 15:20:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 15:20:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:20:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 64 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-21 15:20:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"di,scoveryActive":true,"advertisingActive":false}'
2017-07-21 15:20:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":",B,OTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:20:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Can call startListeningForAdvertisements twice without e,rror
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 15:20:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21, 15:20:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:20:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-07-21 15:20:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:20:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:20:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:20:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:20:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 15:20:21 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 15:20:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 15:20:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 15:20:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:20:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:20:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:20:22 - ,DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:20:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call sto,pListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:20:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:20:22 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:20:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 15:20:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:20:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:20:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:20:22 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:20:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:20:22 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:20:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:20:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:20:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "625DD6EA-1C7B-455E-86F7-3896D6271F86", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:625DD6EA-1C7B-455E-86F7-3896D6271F86
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 15:20:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:20:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:625DD6EA-1C7B-455E-86F7-3896D6271F86
2017-07-21 15:20:23 ,- DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:20:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Can call ,s,topAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:20:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:20:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:20:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "72E264DA-D5DF-458D-8FC1-2FF25B381662", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:72E264DA-D5DF-458D-8FC1-2FF25B381662
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 15:20:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 15:20:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 70 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "72E264DA-D5DF-458D-8FC1-2FF25B381662", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:72E264DA-D5DF-458D-8FC1-2FF25B381662
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 15:20:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 15:20:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 15:20:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 15:20:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:72E264DA-D5DF-458D-8FC1-2FF25B381662
,[ThaliCore] Advertiser.stopAdvertising() peerID:72E264DA-D5DF-458D-8FC1-2FF25B381662
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:20:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:20:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:20:23 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
,ok 72 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 15:20:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:20:23 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 15:20:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:20:23 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 15:20:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "450B323B-3155-4965-9439-201530AEAD9C", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:450B323B-3155-4965-9439-201530AEAD9C
2017-07-21 1,5:20:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 15:20:24 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:20:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdv,ertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1FD45F94-95DC-425D-89F7-A50B823B8E21
[ThaliCore] Browser.startListening
2017-07-21 15:20:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryA,ctive":true,"advertisingActive":true}'
2017-07-21 15:20:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","sta,r,tArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:20:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:78039CB6-B812-4699-8F37-95A7049BD39D:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "78039CB6-B812-4699-8F37-95A7049BD39D", generation: 0)
,ok 76 peers must be an array
,ok 77 peers must not be zero-length
,ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
,ok 79 peerIdentifier must be a string
,ok 80 generation must be a number
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 15:20:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 15:20:25 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 15:20:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:450B323B-3155-4965-9439-201530AEAD9C
,2017-07-21 15:20:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:20:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:20:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:20:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:20:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:20:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:20:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:20:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:20:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:20:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "914F9D5F-A356-430C-B7C2-D99D373FEB10", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:914F9D5F-A356-430C-B7C2-D99D373FEB10
2017-07-21 15:20:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 15:20:25, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-21 15:20:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 81 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Thal,iCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:ED5C3DD4-01CD-4CFB-886D-EEF305048DB7
[ThaliCore] Browser.startListening
2017-07-21 15:20:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adve,r,tisingActive":true}'
2017-07-21 15:20:25 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"rout,er":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:20:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:78039CB6-B812-4699-8F37-95A7049BD39D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "78039CB6-B812-4699-8F37-95A7049BD39D", generation: 0)
2017-07-21 15:20:26 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"78039CB6-B812-4699-8F37-95A7049BD39D","generation":0}'
2017-07-21 15:20:26 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 78039CB6-B812-4699-8F37-95A7049BD39D (syncValue: VTVvTPqNcEn1RySgYQ7QBmqu7VLaVrty)'
,2017-07-21 15:20:26 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "78039CB6-B812-4699-8F37-95A7049BD39D", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "78039CB6-B812-4699-8F37-95A7049BD39D", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:78039CB6-B812-4699-8F37-95A7049BD39D:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4A9A96FA-DF92-4FD6-A890-D3B343A025FF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4A9A96FA-DF92-4FD6-A890-D3B343A025FF", generation: 0)
,2017-07-21 15:20:26 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4A9A96FA-DF92-4FD6-A890-D3B343A025FF","generation":0}'
,2017-07-21 15:20:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 15:20:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:914F9D5F-A356-430C-B7C2-D99D373FEB10:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "914F9D5F-A356-430C-B7C2-D99D373FEB10", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:313CB512-0B3D-465C-A046-81F763271AF6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "313CB512-0B3D-465C-A046-81F763271AF6", generation: 0)
2017-07-21 15:20:28 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"313CB512-0B3D-465C-A046-81F763271AF6","generation":0}'
2017-07-21 15:20:28 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 15:20:28 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 15:20:28 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:78039CB6-B812-4699-8F37-95A7049BD39D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:78,039CB6-B812-4699-8F37-95A7049BD39D:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "78039CB6-B812-4699-8F37-95A7049BD39D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,8039CB6-B812-4699-8F37-95A7049BD39D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "78039CB6-B812-4699-8F37-95A7049BD39D", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:78039CB6-B812-4699-8F37-95A7049BD39D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
[ThaliCore] Session.deinit, peer:78039CB6-B812-4699-8F37-95A7049BD39D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:78039CB6-B812-4699-8F37-95A7049BD39D:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "78039CB6-B812-4699-8F37-95A7049BD39D", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:78039CB6-B812-4699-8F37-95A7049BD39D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:78,039CB6-B812-4699-8F37-95A7049BD39D:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "78039CB6-B812-4699-8F37-95A7049BD39D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,8039CB6-B812-4699-8F37-95A7049BD39D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "78039CB6-B812-4699-8F37-95A7049BD39D", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 15:20:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"VTVvTPqNcEn1RySgYQ7QBmqu7VLaVrty","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 15:20:31 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'VTVvTPqNcEn1RySgYQ7QBmqu7VLaVrty', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 15:20:31 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"78039CB6-B812-4699-8F37-95A7049BD39D","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 15:20:31 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 15:20:31 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"78039CB6-B812-4699-8F37-95A7049BD39D","peerAvailable":true,"portNumber":null,"recreate,d":true}'
2017-07-21 15:20:31 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 15:20:31 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 15:20:31 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4A9A96FA-DF92-4FD6-A890-D3B343A025FF (syncValue: RGXeMThsRVLja7RVT7TRu5U,P5rqOhG3P)'
2017-07-21 15:20:31 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4A9A96FA-DF92-4FD6-A890-D3B343A025FF", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4A9A96FA-DF92-4FD6-A890-D3B343A025FF", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4A9A96FA-DF92-4FD6-A890-D3B34,3A025FF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 15:20:31 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:78039CB6-B812-4699-8F37-95A7049BD39D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CB938ECC-7A3D-4E9B-A59E-2F356C41B0FC
[ThaliCore] Advertiser: session connected Peer(uuid: "914F9D5F-A356-430C-B7C2-D99D373FEB10", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:CB938ECC-7A3D-4E9B-A59E-2F356C41B0FC state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:4A9A96FA-DF92-4FD6-A890-D3B343A025FF:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CB938ECC-7A3D-4E9B-A59E-2F356C41B0FC
,[ThaliCore] Session.session(_:peer:didChange:) peer:CB938ECC-7A3D-4E9B-A59E-2F356C41B0FC state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4A9A96FA-DF92-4FD6-A890-D3B343A025FF:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:4A9A96FA-DF92-4FD6-A890-D3B343A025FF:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "4A9A96FA-DF92-4FD6-A890-D3B343A025FF", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57747
2017-07-21 15:20:35 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"RGXeMThsRVLja7RVT7TRu5UP5rqOhG3P","error":null,"portN,umber":57747}'
2017-07-21 15:20:35 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'RGXeMThsRVLja7RVT7TRu5UP5rqOhG3P', error: 'null', listeningPort: '57747''
,2017-07-21 15:20:35 - INFO testThaliMobileNative: ''
ok 83 Must have listeningPort
ok 84 listeningPort must be a number
ok 85 listening port should not be 0
,# teardown
,2017-07-21 15:20:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 15:20:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 15:20:35 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:20:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:914F9D5F-A356-430C-B7C2-D99D373FEB10
2017-07-21 15:20:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:,20:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:4A9A96FA-DF92-4FD6-A890-D3B343A025FF
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57747
[ThaliCore] Session.disconnect() p,eer:4A9A96FA-DF92-4FD6-A890-D3B343A025FF:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:CB938ECC-7A3D-4E9B-A59E-2F356C41B0FC state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "914F9D5F-A356-430C-B7C2-D99D373FEB10", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:CB938ECC-7A3D-4E9B-A59E-2F356C41B0FC
[ThaliCore] Advert,iserRelay.deinit
[ThaliCore] Session.deinit peer:4A9A96FA-DF92-4FD6-A890-D3B343A025FF:0
[ThaliCore] BrowserRelay.deinit
,2017-07-21 15:20:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:20:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:20:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:20:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:20:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:20:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:20:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:20:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:CB938ECC-7A3D-4E9B-A59E-2F356C41B0FC
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "54198955-F3AC-47C4-8811-A0C5C9298506", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:54198955-F3AC-47C4-8811-A0C5C9298506
2017-07-21 15:20:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 15:20:36, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-21 15:20:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Thal,iCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:92261867-806B-4694-A3F5-5DC73C50CF70
[ThaliCore] Browser.startListening
2017-07-21 15:20:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adve,r,tisingActive":true}'
2017-07-21 15:20:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"rout,er":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:20:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4A9A96FA-DF92-4FD6-A890-D3B343A025FF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4A9A96FA-DF92-4FD6-A890-D3B343A025FF", generation: 0)
2017-07-21 15:20:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4A9A96FA-DF92-4FD6-A890-D3B343A025FF","generation":0}'
2017-07-21 15:20:37 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4A9A96FA-DF92-4FD6-A890-D3B343A025FF, (syncValue: DVXxMhZPM6xaWLQmExAiILXQXOJapGsj)'
2017-07-21 15:20:37 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4A9A96FA-DF92-4FD6-A890-D3B343A,025FF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4A9A96FA-DF92-4FD6-A890-D3B343A025FF", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:4A9A96FA-DF92-4FD6-A890-D3B343A025FF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5E3634E9-CC73-4960-AE64-6DEBFA30E0E8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5E3634E9-CC73-4960-AE64-6DEBFA30E0E8", generation: 0)
,2017-07-21 15:20:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5E3634E9-CC73-4960-AE64-6DEBFA30E0E8","generation":0}'
,2017-07-21 15:20:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 15:20:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B33DB10A-70F9-4008-843D-2783D939A459:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B33DB10A-70F9-4008-843D-2783D939A459", generation: 0)
2017-07-21 15:20:38 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B33DB10A-70F9-4008-843D-2783D939A459","generation":0}'
2017-07-21 15:20:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 15:20:38 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 15:20:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:54198955-F3AC-47C4-8811-A0C5C9298506:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "54198955-F3AC-47C4-8811-A0C5C9298506", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:4A9A96FA-DF92-4FD6-A890-D3B343A025FF:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4A,9A96FA-DF92-4FD6-A890-D3B343A025FF:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "4A9A96FA-DF92-4FD6-A890-D3B343A025FF", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,A9A96FA-DF92-4FD6-A890-D3B343A025FF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4A9A96FA-DF92-4FD6-A890-D3B343A025FF", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:4A9A96FA-DF92-4FD6-A890-D3B343A025FF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4A9A96FA-DF92-4FD6-A890-D3B343A025FF:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:4A9A96FA-DF92-4FD6-A890-D3B343A025FF:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "4A9A96FA-DF92-4FD6-A890-D3B343A025FF", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:4A9A96FA-DF92-4FD6-A890-D3B343A025FF:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4A9A96FA-DF92-4FD6-A890-D3B343A025FF:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "4A9A96FA-DF92-4FD6-A890-D3B343A025FF", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,A9A96FA-DF92-4FD6-A890-D3B343A025FF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4A9A96FA-DF92-4FD6-A890-D3B343A025FF", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 15:20:42 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"DVXxMhZPM6xaWLQmExAiILXQXOJapGsj","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 15:20:42 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'DVXxMhZPM6xaWLQmExAiILXQXOJapGsj', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 15:20:42 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"4A9A96FA-DF92-4FD6-A890-D3B343A025FF","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 15:20:42 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 15:20:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"4A9A96FA-DF92-4FD6-A890-D3B343A025FF","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-21 15:20:42 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 15:20:42 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 15:20:42 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5E3634E9-CC73-4960-AE64-6DEBFA30E0E8 (syncValue: LcrlDXRnpSyhk8VAzxVkKT8,cYH95LIni)'
2017-07-21 15:20:42 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5E3634E9-CC73-4960-AE64-6DEBFA30E0E8", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5E3634E9-CC73-4960-AE64-6DEBFA30E0E8", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5E3634E9-CC73-4960-AE64-6DEBF,A30E0E8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 15:20:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:4A9A96FA-DF92-4FD6-A890-D3B343A025FF:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5E3634E9-CC73-4960-AE64-6DEBFA30E0E8:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5E3634E9-CC73-4960-AE64-6DEBFA30E0E8:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:5E3634E9-CC73-4960-AE64-6DEBFA30E0E8:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "5E3634E9-CC73-4960-AE64-6DEBFA30E0E8", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57756
2017-07-21 15:20:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"LcrlDXRnpSyhk8VAzxVkKT8cYH95LIni",,"error":null,"portNumber":57756}'
2017-07-21 15:20:45 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'LcrlDXRnpSyhk8VAzxVkKT8cYH95LIni', error: 'null', listeningPort: '57756''
,Connecting to the localhost:57756
,Connected to the localhost:57756
2017-07-21 15:20:45 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
2017-07-21 15:20:45 - DEBUG testThaliMobileNative: 'Client data flushed'
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCor,e] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5E3634E9-CC73-4960-AE64-6DEBFA30E0E8:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5E3634E9-CC73-4960-AE64-6DEBFA30E0E8:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 88 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams,() vsID:1
# teardown
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:1
[ThaliCore] VirtualSocket.deinit vsID:1 []
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2CB92DD4-463F-44F1-A336-C146D21DE2B6
[ThaliCore] Advertiser: session connected Peer(uuid: "54198955-F3AC-47C4-8811-A0C5C9298506", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:2CB92DD4-463F-44F1-A336-C146D21DE2B6 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F2525017-CC9B-47B9-8EF4-3BA6E4C985E9
[ThaliCore] Advertiser: session connected Peer(uuid: "54198955-F3AC-47C4-8811-A0C5C9298506", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:F2525017-CC9B-47B9-8EF4-3BA6E4C985E9 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F2525017-CC9B-47B9-8EF4-3BA6E4C985E9
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2CB92DD4-463F-44F1-A336-C146D21DE2B6
,[ThaliCore] Session.session(_:peer:didChange:) peer:2CB92DD4-463F-44F1-A336-C146D21DE2B6 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2CB92DD4-463F-44F1-A336-C146D21DE2B6
[ThaliCore] Session.startOutputStream(with:) peer:2CB92DD4-463F-44F1-A336-C146D21DE2B6
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2, [2]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-21 15:20:51 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-07-21 15:20:51 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
2017-07-21 15:20:51 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
2017-07-21 15:20:51 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:2
[ThaliCore] VirtualSocket.closeStreams() vsID:2
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:2,
[ThaliCore] VirtualSocket.deinit vsID:2 []
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDis,connectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:F2525017-CC9B-47B9-8EF4-3BA6E4C985E9 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F2525017-CC9B-47B9-8EF4-3BA6E4C985E9
[ThaliCore] Session.startOutputStream(with:) peer:F2525017-CC9B-47B9-8EF4-3BA6E4C985E9
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [3]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-21 15:20:51 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-07-21 15:20:51 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-21 15:20:51 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
2017-07-21 15:20:51 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:3
[ThaliCore] VirtualSocket.closeStreams() vsID:3
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:3
[ThaliCore] VirtualSocket.deinit vsID:3 []
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-21 15:20:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 15:20:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 15:20:52 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:20:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:54198955-F3AC-47C4-8811-A0C5C9298506
2017-07-21 15:20:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15,:20:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:5E3634E9-CC73-4960-AE64-6DEBFA30E0E8
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57756
[ThaliCore] Session.disconnect() p,eer:5E3634E9-CC73-4960-AE64-6DEBFA30E0E8:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:F2525017-CC9B-47B9-8EF4-3BA6E4C985E9 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "54198955-F3AC-47C4-8811-A0C5C9298506", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:F2525017-CC9B-47B9-8EF4-3BA6E4C985E9
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:5E3634E9-CC73-4960-AE64-6DEBFA30E0E8:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-21 15:20:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:20:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:20:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:20:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:20:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:20:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:20:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:20:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:2CB92DD4-463F-44F1-A336-C146D21DE2B6 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "54198955-F3AC-47C4-8811-A0C5C9298506", generation: 0)
,[ThaliCore] Session.deinit peer:F2525017-CC9B-47B9-8EF4-3BA6E4C985E9
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "28724137-54ED-42D2-A1D6-A3FD843CA3AF", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:28724137-54ED-42D2-A1D6-A3FD843CA3AF
2017-07-21 1,5:20:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 15:20:52 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:20:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 89 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E7915C5B-FB68-47C0-8A7E-DB3904E76E6D
[Thal,i,Core] Browser.startListening
2017-07-21 15:20:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 15:20:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:20:52 - INFO thaliMobile: 'Filtere,d out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B33DB10A-70F9-4008-843D-2783D939A459:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B33DB10A-70F9-4008-843D-2783D939A459", generation: 0)
,2017-07-21 15:20:53 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B33DB10A-70F9-4008-843D-2783D939A459","generation":0}'
,2017-07-21 15:20:53 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B33DB10A-70F9-4008-843D-2783D939A459 (syncValue: cRwgGaSdXTVE0G7PX4lDUE5MreJJxpXn)'
,2017-07-21 15:20:53 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B33DB10A-70F9-4008-843D-2783D939A459", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B33DB10A-70F9-4008-843D-2783D939A459", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B33DB10A-70F9-4008-843D-2783D939A459:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:28724137-54ED-42D2-A1D6-A3FD843CA3AF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "28724137-54ED-42D2-A1D6-A3FD843CA3AF", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:417E5300-4185-4168-9885-6C92102C4586:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "417E5300-4185-4168-9885-6C92102C4586", generation: 0)
2017-07-21 15:20:53 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"417E5300-4185-4168-9885-6C92102C4586","generation":0}'
2017-07-21 15:20:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 15:20:53 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4FF6C166-AB5C-4B74-943D-F876A11F6ADE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4FF6C166-AB5C-4B74-943D-F876A11F6ADE", generation: 0)
2017-07-21 15:20:53 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4FF6C166-AB5C-4B74-943D-F876A11F6ADE","generation":0}'
2017-07-21 15:20:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 15:20:53 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 15:20:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:B33DB10A-70F9-4008-843D-2783D939A459:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B3,3DB10A-70F9-4008-843D-2783D939A459:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "B33DB10A-70F9-4008-843D-2783D939A459", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,33DB10A-70F9-4008-843D-2783D939A459", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B33DB10A-70F9-4008-843D-2783D939A459", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B33DB10A-70F9-4008-843D-2783D939A459:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B33DB10A-70F9-4008-843D-2783D939A459:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B33DB10A-70F9-4008-843D-2783D939A459:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B33DB10A-70F9-4008-843D-2783D939A459", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B33DB10A-70F9-4008-843D-2783D939A459:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B3,3DB10A-70F9-4008-843D-2783D939A459:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "B33DB10A-70F9-4008-843D-2783D939A459", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,33DB10A-70F9-4008-843D-2783D939A459", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B33DB10A-70F9-4008-843D-2783D939A459", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 15:20:58 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"cRwgGaSdXTVE0G7PX4lDUE5MreJJxpXn","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 15:20:58 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'cRwgGaSdXTVE0G7PX4lDUE5MreJJxpXn', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 15:20:58 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"B33DB10A-70F9-4008-843D-2783D939A459","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 15:20:58 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 15:20:58 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B33DB10A-70F9-4008-843D-2783D939A459","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-21 15:20:58 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 15:20:58 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 15:20:58 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 417E5300-4185-4168-9885-6C92102C4586 (syncValue: u1XR71WVYUdrID1SzvUAktS,B2OOaZKgg)'
2017-07-21 15:20:58 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "417E5300-4185-4168-9885-6C92102C4586", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "417E5300-4185-4168-9885-6C92102C4586", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:417E5300-4185-4168-9885-6C921,02C4586:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 15:20:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:B33DB10A-70F9-4008-843D-2783D939A459:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:142AB96B-FD73-4D79-990B-FD7020BC717C
[ThaliCore] Advertiser: session connected Peer(uuid: "28724137-54ED-42D2-A1D6-A3FD843CA3AF", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:142AB96B-FD73-4D79-990B-FD7020BC717C state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:417E5300-4185-4168-9885-6C92102C4586:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:142AB96B-FD73-4D79-990B-FD7020BC717C
,[ThaliCore] Session.session(_:peer:didChange:) peer:142AB96B-FD73-4D79-990B-FD7020BC717C state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:142AB96B-FD73-4D79-990B-FD7020BC717C
[ThaliCore] Session.startOutputStream(with:) peer:142AB96B-FD73-4D79-990B-FD7020BC717C
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [4]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:142AB96B-FD73-4D79-990B-FD7020BC717C
[ThaliCore] Session.startOutputStream(with:) peer:142AB96B-FD73-4D79-990B-FD7020BC,717C
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [4, 5]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:142AB96B-FD73-4D79-990B-FD7020BC717C
[ThaliCore] Session.startOutputStream(with:) peer:142AB96B-FD73-4D79-990B-FD7020BC717C
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6, [4, 5, 6]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:417E5300-4185-4168-9885-6C92102C4586:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:417E5300-4185-4168-9885-6C92102C4586:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "417E5300-4185-4168-9885-6C92102C4586", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57773
,2017-07-21 15:21:01 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"u1XR71WVYUdrID1SzvUAktSB2OOaZKgg","error":null,"portNumber":57773}'
,2017-07-21 15:21:01 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'u1XR71WVYUdrID1SzvUAktSB2OOaZKgg', error: 'null', listeningPort: '57773''
,Connecting to the localhost:57773
,Connecting to the localhost:57773
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:417E5300-4185-4168-9885-6C92102C4586:0
Connecting to the localhost:57773
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:417E5300-4185-4168-9885-6C92102C4586:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:417E5300-4185-4168-9885-6C92102C4586:0
Connected to the localhost:57773
,Connected to the localhost:57773
,Connected to the localhost:57773
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:417E5300-4185-4168-9885-6C92102C4586:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [4, 5, 6, 7]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:417E5300-4185-4168-9885-6C92102C4586:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [4, 5, 6, 7, 8]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:417E5300-4185-4168-9885-6C92102C4586:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [4, 5, 6, 7, 8, 9]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 91 correct string length
,2017-07-21 15:21:01 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 92 correct string length
,2017-07-21 15:21:01 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 93 correct string length
,2017-07-21 15:21:02 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-21 15:21:02 - DEBUG testThaliMobileNative: 'Client data flushed'
2017-07-21 15:21:02 - DEBUG testThaliMobileNative: 'Client data flushed'
2017-07-21 15:21:02 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-21 15:21:02 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-21 15:21:02 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-21 15:21:02 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-21 15:21:02 - DEBUG testThaliMobileNative: 'Server data flushed',
,2017-07-21 15:21:02 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 15:21:02 - DEBUG testThaliMobileNative: 'Server received (6570 bytes):'
,2017-07-21 15:21:02 - DEBUG testThaliMobileNative: 'Server received (6570 bytes):'
,2017-07-21 15:21:02 - DEBUG testThaliMobileNative: 'Server received (2149 bytes):'
,2017-07-21 15:21:02 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-21 15:21:02 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-21 15:21:02 - DEBUG testThaliMobileNative: 'Server data flushed',
,2017-07-21 15:21:02 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 15:21:02 - DEBUG testThaliMobileNative: 'Server received (6570 bytes):'
,2017-07-21 15:21:02 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:4
[ThaliCore] VirtualSocket.closeStreams() vsID:4
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:5
[ThaliCore] VirtualSocket.closeStreams() vsID:5
[ThaliCore,] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
2017-07-21 15:21:02 - DEBUG testThaliMobileNative: 'Server received (3072 bytes):'
[ThaliCore] VirtualSocket exited RunLoop vsID:4
[ThaliCore] VirtualSocket.deinit vsID:4 [5, 6, 7,, 8, 9]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
2017-07-21 15:21:02 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket err,o,r:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
2017-07-21 15:21:02 - DEBUG testThaliMobileNative: 'Server received (2433 bytes):'
2017-07-21 1,5:21:02 - DEBUG testThaliMobileNative: 'Server received all data: LoE2szhZaLs2dRWleS3jMY4gLZl6vd1gYuziuaEEJHb9yKVSPP0mKQQjwlfXdLYefGT54KfPXsjsAMu47tirCzVYFuBJJOqOBXCawXg4MeOoHpdxQLM8mfL2qhwltCsyEI2rKCd9p3y5A1IXXk6HUtwfcfLXJX5mxblVBVhHnB9VnGlt3aoVO1QZMAujkQ4znbS3W8M2JpCbjQNH4QSuMKdeW7yQCTYqICx7QtDbiVmTvxJXvtUwHANfFFtgPIyawEDHQGtkbz1DTY5K0SEwCPm0NlZmXyvOEYwfAw5OOoDySTAxBz9ZlB0wl0DnrFLrroTsTak1jLvg0HpFehcOypaWfqT3c1Fa0TLkURTOEP8ObMYqtSAzvs40G8UsopDtZjqSJ0sdzyiQIysUEUYBV1yqVLzb3YG2qKdO5aiOMglMQofQDToZDkFZy14bNggataSRPMx2h2UIIpP9iiCK8xDRV1Tg0xddSlxrvvbQFkuc37zXxHnRUaEttRuEVgV9tkkHm7lDYBHcYbFxKwtiOrgpWEmyCLahO6NVa9d2ONWz0xp7KIFCRdd9K2luOXtmSIN8FmTByw4qINY0haWxhVk33Uqmqwn9IkjXSeI7lpf3HQspXsvGdLinFcyePZIOkIQdhRuaZGNkpMOJzrCnlclYP6DlP0oXTD8UXJ45X8BYHG8mPnaJ2267HMtwy,t,381B6aSlx5dnTuPgu7lmc1RLUiR2Hs2ha2cShrlYYU9gqNVRXA85JGCl4Pvdp49uYEnk5XBcX2XtXuzmfHmaMqx0gY7GzhW7erxvofPYvHLs7MPA3GhpTG61yVVGNlUSLBdLa6v1EEGCzI5QopZBliU5PLFQ1WkolMB8ivUA3MKvqi5eHHcr0TXvfOYHDbXvmukYglBtmepV9Yt1A7dgPhRLnBDM0MtCjOMelt1ffKmUthF8PGaMKBncOQatb9cw,V2lw9fXasjqb59Yl8lJmSOvG1OyrGaE7Ir56je6uAl7XTTU91FPs71E8wy4n6u7nDgY7ep3yGtiVNLBZLEDia1C7IN10EDT8TrfZG2dN2xprn602SAeRzvWtrfNXY9uULsvYjbLGFeasZSLgy6T3ciWOLSbLIjciPEFligg1lK0MeEb4Wr6dhTzmZiVMKwNrkfZbGf2EvvUwAWbZo2gFKMMojRbXNCC69C1XXRHtC67VWNmmEbJw8ez9XeMU2ap1wkIpIwDXOeKD9VLWvCyCxr0c0hYUpZjCDkL5qWIgYyehOO4LkJzUxgzyFqjx5dN89ocP2N2A0soTXxskeUk6yVKpN6rOKMEpQ7NLGSgNM0Ai8RpJpQ5W8uzT9FcfwGHNNGaYvno15ShjoYEdT3uw21c3c8IlYvHQGlm3fi4BVNiWMzrTHHujczIKB1WgyJd0rHzxH2dEGmDOgclJ8bA365UnrszS0Ue9SFhe0gd3OPJcKE3i0tJFYRjug70hE7OL,JKVn48DlOqaWN1HThvpzhRwn6T4wxWdYFIWAIOjZkd0UnPhsob7y5REnA9v044bzHZ6qtlgcEwxyrI8MBg9dFNWO1yY29OuL0iyWNcAMD04HQIicOpDUQAUgopsl8rkKEq1piYSaL6mQQYXXJhgJS1MsMDVBKlbj2uePsqegnQ7mrM2rbrf7pN12dMeCeVDcCGmBqArrqaiGcIozMuV2QFQr0c6kjK28cc0Kx2nEf8mGuAmt2y3484XZLnGSFIY,a,EyQV2XSk4hUnshZbz0zXzZ2KTkgn0q5By4JAJ28sO62MHh7IWN9H3H3vSdCo42MQA3BDuTctOixcOuJCaJ06kl28hvAdu0Hj4On00JNCvLNwOp7iKRbHiVwMZ6OrKqpjJTCX6la4Zh59zDCA0jF4csIi6eqYO8azUZk8oP6R2YBPxJyEpr1FSeNVgQB2VWjRDwfktl5zQJQGsPzSFx3poWWUotI2LNjWmY8E0rICKiQJcHwLURDlHEzveF9GTQnM,NTaj6fHAT3IZ5bpUjebnvA4BYWbXlKUj2gvaAb3jU1APUaOkfg5HLr6qi9JYFuc7kK6bA1MCjPo0ueaEYq6ngwnjzAirYlB1i1HT7YzSnVAEfkuS7hBqDQ7WNd7WH8iuUTBMFJ2rcILHfdNp9eOIzxcgSs6yrDK35VGEWDUrIWj0ZcqCCKpgqjNqTj7nbBNNwmMsiCf9lv9f7RVptEX0zXuK6acYT1ra0gGG5qr3AhXTNkeBxBqm5pU9OD1kXuKP,8g5rdoVTTnEogPxjeN940B85mu1ca8Mmgr0M96LGDvRoChJvAcM8LQq958y43L43IBGbqxYtT0M0lYyWKDXPIpIsSG3AVi6GJO1grtOh8ztrwyHF3LoypboUHTkVIJcpLxchVZPniHwHkgFyFN4s1e2EsOrFs3KHdGJzhXSNDZDESSWn7ZThL3muiN4Y8AAH0fcINngaRKmyMpXIsr3FmhNYydMNbHpyKwawTTet1lHvagN9jmJ8eHqe6U5ramJr,1CsGGFaSnL8ma7CGPRgUNtwaM1mItA1nw0vrYRbxMYPDNJFZtemZsR4j38hENEtuRxHeBhQJXuQnOueqkc0bXRsy5OjlgHakcPcj1JeDAgW86ognjUspUYW3eEIJNzv0uHwVxzz24TC9KJF3tpoUJQWoc3letWVSY23oTIg71QAUQeXYljNIi8EUZiAmAo4xB5ndXmjXqvyTsyGOAdk2uWECOM96DnP6A9hYrlynWmzIsNdWRa1fc012lTcqBx6,W,U0BsKop37H3TWwVhfblyXqHz7A6JWNPEg8vo8b24wPImTWNkOC46M7OPGHeQpQgLSmOAdzFLQuLHfyYyEYBPUdfwmsvUU8DR0FMLl98YZOSOdLVVbO5k3ho6oqt9VOdITfDpNXKadi9Vm6UYdcAVX9zlUZHtcVCohrZzgtigu7ty6n3JOIcTUVmWZ8iDaDyZXIKsjusHDS7u9CNtlt68pFqbiZZbKiTijYWTNxnRVUNdgdUGz2OcGCNPLrFfNb63,STFijZyK5lVlT0SXpIBNVK1OlgWS83LyEdfjuIDUrMuUAoSUFOSutTeItwqwwGte39Kpt8rBGy0hkDDPxFB4m9xjFRyQOJPycPK6auyyKLOZikKzYtJ2WcfcALdZ8RD2D4phBPB29YPtHGa16hQqEPNKEk7DLLqIPmQTRcsFWjjQpclQPOHoQ9hE40t3E3LJefpDDyZRCOGJn3nqGYEun3Uo552OIHTOUrUH0PLedy5UWHsiKhFEWuS33P9ITixk,NEgcIfRvf0h3BHzyPXpGhGR6Pws2zgkSsbxxOD9tpfyschwzJLlm50lkLoCr344ibddMEbccSjKoScjDo0RYYti63Zt6GfxjWQN4UZ3WYwC8WIC2lxnTjrN6PPqZvOyXyGcajzyPK00iXntugXSvQxPoc9jEgbfczl7D7QjkqBtiGiahsSMurlfxLx5o6H3xXLLOLqkWQ3uYKeiKyOXSTSeSgUzsPKF6Ft7zHcHhdoMGvo5e2RxdsjYZOYbKCKav,lYHWn6lJ5oeBjpqIPJXpj8cl6UHF2tJDWJuHnPFmpFuvqCgySw1c1fPLDhA5e9L1bfQCy9YkIZgToEZ2U7bKeLK1FZ2RXcUi1lXcOZQp32DzX2Cg2cQe2iiAnbYPWB1XzrfLeU6BaTJap3dIledVUcRfDXl8Blqq6MdF6qwWD0t9GBlD52VAtiIVydZte537OIUSe45p12tR8JMFWLQt1VTcNmuo691CPKMzgmVFqC5jenaNIpENSWYeCEUaFgT,Z,M67SIAPhzwvhvzdMBaUSPr8kjn4oBndubZmDOdwnI1uNfiHWoCvsxJNVwBf1eoIKFDm4NV1CBCOlwhFVvp6HFrPVYBkt8FtfEKP4yxtwSiClzyZgbMKNDRp5PjPozvLIN219iRMBMrmR41tOqr9VdaeAKfViVra3gXL6W4vBIkvbU3Id42bs9jSx6ET1IDo8aRj36pGspADBQJhLmWCVuzZoy2wThumEaYoOj5SOb6BRBAPflhAzUUlf28OhnXtV,TKYXxacTsiIhbT72MZmG5kPlLNYo9UXtJ4prkh4dosrTPi6tQZXfOkTRc2RVrE35H7144jtsOPQ99GIjav2JwSmpUwfGjJ5ubqf1FWUzYjyiPJEAibQd8x3WGuFXGNphFa7H58cbl5zGyTa0cCsCSFCG3tCKG6Trr1hiJTlwCOtgfAYXOOnMjdBnGlg5nnSfAsjhMw9pObK7QAtJB81jzk2i4m8v4GuPPiXdJH41GGA0oSzzyN2lwi7J0r15i6Lu,dc1xO58QSWgxgwHXo4SCLtsqxtncgd4H0oFvo5aLWmIClTVLU13fdC3rjvOOZjrelilz1OiptQNqlRJLBEEFLGBKe8t9GmAGg3KPPhJElHFSXP1DpKe3Dtlraudng1bgCQbl1ZtdpmIuGchmWCfEKikbyggaC72q5p9OOMq0OZBP092sOKJaGs6t9Q9wFDzbNaoNQhKX4fY6VlkIfJh6nLCO2dGVTtdmpIA1FDD1mfcnPWRUgGdHOYKunATIF2BG,OTjwyxkBSZuJGYLyVn8Id5ts3eY0cPvZ9mQFv3cJruDKaQq5et2FJwpi7iwJ6DXuiigBCoTxtYy21fNetwk4UfExQCpSyPuh0iARVQ7GVr7iqm5oPrtJ48kGJxMTXsax6MAG0xy2rulM2VfWY25ZwuVt3sqTBTuJKBxRYfWd2allnXyJ7hvNCBgQ4KVmvqpmJHVNziv3ieF6DmsRhD7VWIdAgNWVS60Y7HVt8Cvyl2Y8fdIgp3vIW0zypnMjzP8,8,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,o,rM3Cq5UcopMdbpqcAUcclS0yzgpp40i4ZlzhIRxEDis3BOk7LIE6otaAfAILyx0JttkordVg47qyFlosKmkfrPfzmt1R3ntSoO3nbbYm5CPvuWjEH64ekxujkmduY4TkoV9SP3BqdzRXTi84mAlZ6Dg9e76jmTI3bRoQ1K8vBYYqsfWP6dy2EASvhG4akzEZ0NVn67jKohfDJJKpl0c3LGxZWtarXcl2ovMNNcmgKUAgHSOhYajCnUvVL9K0pE5b,cI15TV710Ov4ha9QGKfydk9dJheO2gxiaYsXciCvBcn8benyNcARsDSaRDiYuppWMiZZaxBUQL1QOxQZEa0sZJK3KGHu9gI7jpNRWQpHOGhrL1zSnoEXZMKfO18Z1fwsAIXTLq4vEBRWHS95059hyB4XGJoJL3MefOyqY14A5W0WLrW9CL8c1aioDWu4CaCMrS8ACBqTMnh7B0awzNFoR6xzTCj7P9vhsjB5kZdGi0m2xt4GuQPF8xStev93Dp0j,EQIMOrXpCatFC3YgVaI3603Do9Qd93CBCfoTpC9OCekXKC9w83K0dXVwGQwMk9qlmmEllDZbLWZUmyqffGnQqQA3NzBmaQSNxCp8M0Cag6Msj2sMZgU3lPwVbFtz3Od9HmQjW6s0L1WAXBIp1Z0uMb8f4U1EyAvCf2tdv5BSNCAjlhdRcKKQ83IZGuvhKFHAZcBeHvi165pd5BZATIY3gLF8h1aEIvLMUhiXXWKODVtgqvOIfaP2CfKOxM5R2MXY,U98WdcgeAsgQPNBCMXbI6EaMTHbDSuN4eT4hUJPybFi7iqr2r0wObxymJ1hlImQ7GnltAh1s2CYMDsYsmVSiZZkHVyb6N8ArnTqkZm3NMed09UsIi9K2jNn9jjbGNGFpH4I2Cc1UjyegIZ4tB2DL9zErtyKGQvIPkyFjNRXz0iiTOYS9QGgPdJ1jm42NwIl40Wgvqx8TZiWNlHG31ldlW5simUwkjlVTDFFPwBLqwNbzRQjopGwR7UvJWt0J1CF,s,YTSMYX3XfZS8tkOfDZrqBdqWozabB0dLbOUbskKKa1rWolkJyVvmxkKmLnPv305tro8BYyQFvgOVgJ9gIlGFjZal8sn7CRDCDgUTlpQ8RRGRiIOrUrzAJRPQ1B08gRXcYQxqewW0eDUZpeMynjT8Gow13Mdg0BUtj8nJJzjltYmmOCsmK38OtnlrlZQzvMyKKhpDvU6jSuZ7onnm3UcS65xAnRDG3g5CVB9tpwKNz7tAqcraJDSLJ935nZQrR9op,XgAYdheqBPzLLOmgMPr5mmEm8XD3QjoHTfDAFmyVNKDyr8fypRwQOfqTl26H7aPkjd7mDfVlZIZVg052X1lEPXCm86ISzyxjDklCKgfhKVohcbT2QKMfmtHkmfS2WETsXl0tSv3C7pAMUH4RXjnf7TvZMs2KtQJaXVg7UPh1lgW6q6uxX7h8PcidamacQMHuee6vxCiLDQzufVyNMslZCz4SaK3lPcx0kj9W7aMsLUxusQmo7YHx1SzcgJqnYrKr,TzPIUPqjxicy7IBHuXXeRRtB5j3yOIyWL4wHhzsiaVJCNWO4pKkhv30PIPq7IYVcleAa4MxsZYNuXB7ALFocuO95YMreJPRmEvToUobHqNOkVRDIAF2JTlb614zxPmm6BDLnvS8tjbQ0HEYvyXHtMg25AAzNVyb1fG5Fd1Jo8HX1XSVx38yu4L8JNKSSW866BTkRulA7mhBIAtXWnSIBkGqs9zaHG9i9hM5MsSiakcP7guxU9EDcQAKdm7qfvgct,xURfxbGfZjSjfY9jvRjTL9NIx62T6rMScZAdMMIsJgJyYtl9b5vc3hnfekLfVLyNvqQefo889d6QDL3wav7Spib58eu7xDXZfFqNv8eTsom9XBtWqsa8WOTCWtIDu4gaw6YVq2tb3Y6vWfhLo2woZk9reuxXrmlAihN1GYxjBXdim3u93pAGDEYqRTjGTChUnFOs9cn98IX579cY3q1tf1mks5u4Gek6KU5Ns2QHF1viUPbuVP1GMftHoRjpkKd,X,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,b,T1XBJCWGKfYVxVWhRXvKIYVAzMx49BVY5CP0ORvEN79qz32YqKm594HcDojl30ynzhm1LHtduzhDzDAPZXULkuUkDjkUSzzEz5XDfqXnNjqxA8yfolAu1zp4coq7vRXVHotPq88Wy3ag7b8qKKjTCHPOAtvYH6JWBtuD2RN2WFoIMP3pQ8ncxcop0lH2cMZZgdT549ZrgCZzdYaz5eKKj5MbkrYeviX05k6PxV5xjpOup08ozNBTR41FRdeD8suy,xAakSWxE7Z75N39WuwINhodf7PZrytwZTYdlAk3NWjcKnbsbJQdyAslCHBKFFmVeRYJS5n2ky5zW74O5SVpDfHwBfTB2B7YngzWHY09Hj0MRprJrw0cXCtCW71cYwGFt6GlbuiiHPv3KQke4BI1hYyhYIsufYHVWljOADmTvY5YPetYG1gUO61EmUZiMhKayvNT9EcRD4fIcDFcmwJpSi85kPn5EmyXWWcKtT62Eg5AgsAZDob554GSXopzMm9g6,RAMSupFb8BEiE4Bp1XYqsMkhoPa8Ry5oxSmNdDS4CZqvl3Bm9owoXBBMIlUdRlrCI7Apwpg7eSNYkOdlQ8CEdp5vTq3EvFHisy7M2MIGu9Z3HCpGWiGugYQgC0YmOUGeD0lr1z5Hi4Xrq6eflTLGjCDCjMbidMhmrS4qTizvpTVu3VXBFr9JZ0FMLt3TMDfFRxj4GQnLIlurwUJxdyTXbMlvKs9LghU2F4FI1S6Gsv2WMzgbxX47Y78DRI0FgS7T,6AaX1hsJQea5jicfTxOBMoUftNJVTiDZe7LpmK4RxiZmd5XnVjQSU7v8vT8P54NyU4nyfKHQaxHpiodUqzZ0py9EZkMpv6zA06syzIVfRGt9avd3kXMmlsyzlkPgzDcWTBoal8akWxcWqXPD5QvNHzMPrnjQ0IY1IxpQmzSswbXg4OYtjj7DKlJ1Td345UoG1ow41s69qRlsSYzOoEnM2mHrP6lCZ8NdFyidJXajCYJSNjWpoT1ks1lqWTwnU3c,J,n0jcng4JYQj5noeBafKWv46I8bamQhhrKGJpsa4tLYDCMH4oNxkHZzWgCAAqDv5ekF3AM8hUYfbt8IApW32g90ylgx5dr8Uzl4Fljp3ouKVvJYX3OLnsSP7Jc1ZvzCb40euIETPGNXXYtBvpJkppMyomtVmBW5tgbEzbgZn60d4MLw2fjVuZidgyRyA0k72pW3pKd8lfBuvVqat7DW6NE9BPtpjeU80eYJ4E18Qkgz2jl83eEPzttFPOK4cDXOu4,IsAZiG3pOWoY7fSHQ4iMwfZYgfDw42z1xwmH7crnWRJmpp4Yav2Ifd2Db88fFBFDozrdGOgZbq7igZi9bu13dXUJRUx2OEFkPkxYb2UUdcAl67l8JDfD1NObMOOb2lWHQSuFDwSu2avuhMLDO0QLvGZi3BY6QLfpIo9ayeyKqZKwhzEpGMocR2uXsORbq1jZKYaoLOpfc2vtMMUQWgwflAQJhe07Sih0nDgMKxEm1s9mPUknhffIj7KNvt20NdKQ,bJT7bcFDMv8gBnvP4fS5GB2SCzIQU8VYGZUkGyVBcRDoGlaueI1Fn1MoEump6ilEEYqegWo1ptPRFb89tU2YCkEJHNlFHiYROEK7ewHCZOws5TsJ0MBIuULROCpWkcS0EuH8f72vTk8ECtgOfJIjTabf3DoCONjy1vNUMXAFgHfx9FPe7NWHcYr6vBeh6uvDPFjDhQQROnDigcjLzfUKL5YZsONKM4g4asOUff2zvGgP5cnnbgIaveUdbPF7jyCc,HFit9b7gJxCPx4TI7Zl5EATExKGdvNHqygimXg2chOjwZzwqv5K1DeNg53LtHzRYmU0lLvlOcykN9ctKe3dLlgjHce2Ic09T8ZKKG19nkaBhlrl2KQTdyNJ1B0gR2WPKj2DT2qIL27IqENMZhywZccXsLY5zqgaGplcZ2etF0INZw5e3BsMqekHGpyIqQ3YnMkxcm26M6yOvz2NohEqE6gIsOFPxuGuLQ6gPKi6z3h1LvXgE03TmFw0DFzdwrGl,G,hfszjQ5KMQEII6zj9PCAXry7qlg6ZJ5AULnvrDYiI9OuVQCBAvq2yVDAyC2hnqDmpnLE582cIfkdjH6K7Ow4kOTucaJtvDCxTpIuIIrgCeAB3rO9ppFPtPCpB4myYJxQCiUFdq61dWKjfF7ogu1NVY5tkJPg8vTgeDKoBHK9Jb2m1S7JaFWzMUFTz7eP8SRy3sgoOSeO4cshp8L7RMeZeMI0NmhCUHRoEdypqmJl9rInw4DkzBL8hkPv4BmzpXtu,NmoNIJXLOzEZUzva9hrEeMpJGyBXXFCwlo8fpfmZTeHDYPXGOLi1xY34GBOtr6LwwWsMfIZkvsl1U0cACMtWm6IA5L4MtdhMoocrS0SYazUSSvuAS0JRAiU5Kt66qK4SPzjiE8s3HxWmbsQgLG2o3Myliz4sJ8fyhqZBAexLnGIJDZvvKF1itK9wWSEPatkvLtuZ9InqhTMjAVV0Bdbj3O6tfJI2sp6e9527CbAxSIXDXFL9i6tR31M363avjmVn,4U1TVPA4gVhuHYO2y2VZXMvOhpFOb7ybnlXtFK9DNIMXDAc6pbiYd23CZe5POLVr7WZevzwG93sQzvY9kwVKXWLty96bjx5JgRZITf36UJRcfXfRck7ASRFEog6QgSB8Y11WXTWWbG3XevxOwKj3m54e9iS3Zp9hjyGRRvmFilCOMbTp4H3DguQ6VxURz1fayDf2cmUBm48hufRcJKklNuuK81hY8qkcTseFoMUn2E0KHeOLype3r2zNwLJatgFN,qKVc1yBAJEAzN8f89PZP6yTSZWtBuKnM0DwpmNN6V0s72TorygoYXmT8HgTWaAAnxLDVLpyYtyf4wMLpQg1NmcWCDLgZM66Re8N9sBHGztpVQQWdDd8nGmqdFXgoDRQ8Qw1OcTUDqs6R2d9pi3ejNCt80Vc8Azc1JqCSsJkLxodPzNugMyiJOTcrP8iYbHQqgZht7pYxWBULvdYe6cNu7xVwbrRpdoYZt1s5zaU7ji4YazcEX9sXsgUV3AdYhf6,W,xZaMIPEOn7ABZo5ERqpAKk3mXyi3LOfjoaZzD7E53qfGKTZyx4AtCjrE0yNKitZgJ69ChDVdNUHKqDf4VfsvP2mAl0EUp05e9YH7XGBwHfN6fC99E9EdZJOlc2b4sZugJYqXvXjg3LZ3eWnEnjxnFSpjb39gp46zgwNfz8KYFiE2ktKRbupf16dwyl2wYqdDFbtP4x3hXehaCF7B4syrtKv8V0hwpPz5Otk1j9wrZHMYkTcv0GDvopdysNLWI2ud,3qRMvhYQSOETZ7ymnAX57qcDRcQJWLvTlpajGbk8ZYNNgJ7mUH7uBpe8dGHXALVaKOf3YW3YqFEuI2ylvZkcsdYL8bBvQWk7JzSPnE0G7XpiwaCS9K55SX2SWZ95fESJJKnjxN0p3ejmk86vhowuNgt5pZiE82bVXv0QVwYKDZNOUxwdoxa9yGAnXOzU8fPeFdeXalQRt9ld9itpIyat4CJuwKjTLXCVeUkYp3W6jkHo3SAI01zZwpD8VMdA5DsF,mnUrJLn3mCSVIgIYVk68svis8sl4leRzkXsqQZIMliTw8mxAWMpA8z7LhvzBIdyLdF9qatvA2BJb1Kg6rEP6CYPIFiug0ZpVcq2H9R3g9N3o9ZU8KgGMdn5NqJyJlERx3xdviQHsAb4doL7fe1mua4QwJKB17nVUHQzSYZboD3vDgZguKF5wrOt6OSjHh3LYGJWGiFlaEi62o9uwmJfvUJwdcWywxif7Z0p8rwQfgDVIuO3xaVOJmt1n6j4hDWeM,nq4CER7aHKJNwiWa6ofVAvEKrjp9gejYuQRqjbB6fROWPlz2Zjpm4hMoBOaHfp8USkeCXzMnIBTgn6JN8MtAprY6far2PZfKJaUhyNFTiNLAfa4SKx045zx1q0n5qITXGkfMHHOdhMEgmKzid3i8zZUidFjHlNBVlmtYzOHmAFxtIxvdiBkXihWfXON24LMcbnu9zDjwxvWfk7xbLlkv7ccu1yGLtb786r2W9NXIGwvp9HJBSENWgukcxVs3jYQ,q,INAy0bHB4XkTqo9rKN7hSLy0ME0ZaKWV7ga856Nq6bqEZMfpnCcEowT0po5pZFQIglmKHkG2xEZ4fwVuTKK5bNIdLzXQCIEG8BW5LpHi6q5quYAwVPSKcR1OEYEUnh0kk0BfFYyfM4iEAmlYBT51o4nGdmDykQpM8vVxME6SUutk2yWWM8dpYfd0QWOgLCMhvNR7ELwXFyiL4xQwkSWKFETz3Q6zQTWLmMKe0OwQPLmpNywHNcJVTSM0sHDW8HXe,Vfl5fSeu4tqcKUSk8Rthhjm32cS2VjVnpdKNpewZ1taApoWXQP5OCnNi1bktlDYOsIPQHWhSMs0SepMDhYP0YxvEb4NVaJu6bMdvz0Z3WxaBZICzFpghLKVSJ23okh9j7i5x8nUw59p6HpYhZxX4F1zdK5H5lZxWRqxph5JTJjptmgOdl8NDv6xiNxFMpPXlzhnQ09sJxruw3tq563QO8lIrZrcvpGHlcN8bMFdjdFiYPSpuJoL7JC9gtYywSkiJ,8l9tJzsmFPWz5fpomaKy6LF5xvBVK1WWG31J7h3x11zSg0A0plPv3yeqd7MfeWVjiwYmtX3HmzFlvmXfgiYPNfJLweEy2GQK9V0dm4jUfZssGSrXYmMU9pAas8tnt9Pw9uVwvUtgZpWw8eyw7LZGmbJqSPojg2GA1Xo0xnxqOyzLW6Ex50kJGh5L0PI6E80UWAy5ckCqNWgdAMibZtLuLOVHl3kJtlbRxbYMElz5kAAyNzcDVLfPHDTgm0bzs6RT,vV2P3ZjbgybH6RTZuCVO01Wb9lIEHS2hVJKzjZriCaWSZqpnITUouc1rgbwEo5cfYWI6CLkLh9tvpoQlNFCUXw7kTI0ZHnn3ABQNz4rkyjuQnsTojgSlMD7RXSpzkpruXY4zrgQmn5XNZeJbhV4ofhiwWmx7H3ykH4J0aULzQE1ty7hP0LceWi0hUIiDMdXpdfU8AECdWG7H2Dqo2SXoCJ4omALMa5vS9paQsYq8S5gHG26T5WmYMhLp6Iv87f8,D,HEYYl8XmFuyR3Zv8dtlQqXG6WdJNhV28xtlKelAZqdBvdDcX335a2xljoJyKty8BgDRBMTRf3oNSdOjuQbIEBraMRhehy5nGHu5zVey44Abn7jfBz0fh02C8NVwsXSDXv4vECDLlXu6dkFNB7IDGIm7QKPTgvhFxPkaor8zD7Z0Xi9V0XuIkaAK9UzlYo39Afsn2GBgwo4jGVZnhTGN6lMUPfpHrP6ChR4Pz1wkwu6ZpoWWE4Fj7pMYimE8evHGQ,9CaXgWC6jL94qoPPsbxbgn90crASGJISEYZdFg8eTOSxP7Ebcbz45Sk5h9Cww2q3cZ'
2017-07-21 15:21:02 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-21 15:21:02 - DEBUG testThaliMobileNative: 'Server data flushed'
ok 94 got t,he same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[Thali,Core] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:7
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:7
,[ThaliCore] VirtualSocket.deinit vsID:7 [5, 6, 8, 9]
,ok 95 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
,[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:8
,[ThaliCore] VirtualSocket.deinit vsID:8 [5, 6, 9]
,ok 96 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams,() vsID:9
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:9
[ThaliCore] VirtualSocket.deinit vsID:9 [5, 6]
,# teardown
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:6
[ThaliCore] VirtualSocket.closeStreams() vsID:6
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:with,Error:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-21 15:21:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 15:21:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 15:21:02 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:21:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:28724137-54ED-42D2-A1D6-A3FD843CA3AF
,2017-07-21 15:21:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:21:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.disconnect peer:417E5300-4185-4168-9885-6C92102C4586
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57773
[ThaliCore] Session.disconnect,() peer:417E5300-4185-4168-9885-6C92102C4586:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:417E5300-4185-4168-9885-6C92102C4586:0
[ThaliCore] BrowserRelay.deinit
,2017-07-21 15:21:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:21:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:21:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:142AB96B-FD73-4D79-990B-FD7020BC717C state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "28724137-54ED-42D2-A1D6-A3FD843CA3AF", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:142AB96B-FD73-4D79-990B-FD7020BC717C
[ThaliCore] Advert,iserRelay.deinit
,2017-07-21 15:21:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:21:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:21:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:21:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:21:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:142AB96B-FD73-4D79-990B-FD7020BC717C
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B4BDDD64-4029-4E6B-BE78-E9D242224BD4", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:B4BDDD64-4029-4E6B-BE78-E9D242224BD4
,2017-07-21 15:21:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 15:21:03 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 15:21:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 97 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7A4978E9-A473-4638-9CAD-74E5E30CC324
,[ThaliCore] Browser.startListening
,2017-07-21 15:21:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 15:21:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 15:21:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:417E5300-4185-4168-9885-6C92102C4586:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "417E5300-4185-4168-9885-6C92102C4586", generation: 0)
2017-07-21 15:21:03 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"417E5300-4185-4168-9885-6C92102C4586","generation":0}'
,2017-07-21 15:21:03 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 417E5300-4185-4168-9885-6C92102C4586 (syncValue: 5wFPA1e0CBQawsno5Zq8wdAk1JmMRne5)'
,2017-07-21 15:21:03 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "417E5300-4185-4168-9885-6C92102C4586", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "417E5300-4185-4168-9885-6C92102C4586", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:417E5300-4185-4168-9885-6C92102C4586:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:80E413B1-FE3A-450A-9B20-73B6C55150CC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "80E413B1-FE3A-450A-9B20-73B6C55150CC", generation: 0)
2017-07-21 15:21:04 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"80E413B1-FE3A-450A-9B20-73B6C55150CC","generation":0}'
2017-07-21 15:21:04 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 15:21:04 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:71D06222-295C-4BB8-8A3B-D1FE634FD4DE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "71D06222-295C-4BB8-8A3B-D1FE634FD4DE", generation: 0)
2017-07-21 15:21:04 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"71D06222-295C-4BB8-8A3B-D1FE634FD4DE","generation":0}'
2017-07-21 15:21:04 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 15:21:04 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 15:21:04 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B4BDDD64-4029-4E6B-BE78-E9D242224BD4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B4BDDD64-4029-4E6B-BE78-E9D242224BD4", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:417E5300-4185-4168-9885-6C92102C4586:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:41,7E5300-4185-4168-9885-6C92102C4586:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "417E5300-4185-4168-9885-6C92102C4586", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,17E5300-4185-4168-9885-6C92102C4586", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "417E5300-4185-4168-9885-6C92102C4586", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:417E5300-4185-4168-9885-6C92102C4586:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:417E5300-4185-4168-9885-6C92102C4586:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:417E5300-4185-4168-9885-6C92102C4586:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "417E5300-4185-4168-9885-6C92102C4586", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:417E5300-4185-4168-9885-6C92102C4586:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:41,7E5300-4185-4168-9885-6C92102C4586:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "417E5300-4185-4168-9885-6C92102C4586", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,17E5300-4185-4168-9885-6C92102C4586", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "417E5300-4185-4168-9885-6C92102C4586", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 15:21:09 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5wFPA1e0CBQawsno5Zq8wdAk1JmMRne5","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 15:21:09 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '5wFPA1e0CBQawsno5Zq8wdAk1JmMRne5', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 15:21:09 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"417E5300-4185-4168-9885-6C92102C4586","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 15:21:09 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 15:21:09 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"417E5300-4185-4168-9885-6C92102C4586","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-21 15:21:09 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 15:21:09 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 15:21:09 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 80E413B1-FE3A-450A-9B20-73B6C55150CC (syncValue: 03KpTcrsXxLqg19BewHX3Gj,lSiIgLen7)'
2017-07-21 15:21:09 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "80E413B1-FE3A-450A-9B20-73B6C55150CC", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "80E413B1-FE3A-450A-9B20-73B6C55150CC", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:80E413B1-FE3A-450A-9B20-73B6C,55150CC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 15:21:09 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:417E5300-4185-4168-9885-6C92102C4586:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:80E413B1-FE3A-450A-9B20-73B6C55150CC:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:80E413B1-FE3A-450A-9B20-73B6C55150CC:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:80E413B1-FE3A-450A-9B20-73B6C55150CC:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "80E413B1-FE3A-450A-9B20-73B6C55150CC", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57787
2017-07-21 15:21:12 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"03KpTcrsXxLqg19BewHX3GjlSiIgLen7",,"error":null,"portNumber":57787}'
2017-07-21 15:21:12 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '03KpTcrsXxLqg19BewHX3GjlSiIgLen7', error: 'null', listeningPort: '57787''
,Connecting to the localhost:57787
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:80E413B1-FE3A-450A-9B20-73B6C55150CC:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:80E413B1-FE3A-450A-9B20-73B6C55150CC:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [5, 6, 10]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:57787
,2017-07-21 15:21:12 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-21 15:21:12 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 99 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:10
[ThaliCore] VirtualSocket.deinit vsID:10 [5, 6]
,# teardown
,2017-07-21 15:21:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 15:21:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 15:21:18 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:21:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:B4BDDD64-4029-4E6B-BE78-E9D242224BD4
,2017-07-21 15:21:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:21:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.disconnect peer:80E413B1-FE3A-450A-9B20-73B6C55150CC
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57787
[ThaliCore] Session.disconnect,() peer:80E413B1-FE3A-450A-9B20-73B6C55150CC:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:80E413B1-FE3A-450A-9B20-73B6C55150CC:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-21 15:21:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:21:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:21:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:21:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:21:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:21:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:21:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:21:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F6D29EA3-480A-4F67-9CD5-38A122C3C78F", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:F6D29EA3-480A-4F67-9CD5-38A122C3C78F
,2017-07-21 15:21:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 15:21:19 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-21 15:21:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 100 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:0CA2A5B4-DBC6-4AEC-852E-B12313338F57
,[ThaliCore] Browser.startListening
,2017-07-21 15:21:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 15:21:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-21 15:21:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:80E413B1-FE3A-450A-9B20-73B6C55150CC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "80E413B1-FE3A-450A-9B20-73B6C55150CC", generation: 0)
2017-07-21 15:21:20 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"80E413B1-FE3A-450A-9B20-73B6C55150CC","generation":0}'
2017-07-21 15:21:20 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 80E413B1-FE3A-450A-9B20-73B6C55150CC, (syncValue: w0cokAuGFJz6hqcGz5ZenxFzZdIJ5KXu)'
2017-07-21 15:21:20 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "80E413B1-FE3A-450A-9B20-73B6C55,150CC", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "80E413B1-FE3A-450A-9B20-73B6C55150CC", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:80E413B1-FE3A-450A-9B20-73B6C55150CC:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:71D06222-295C-4BB8-8A3B-D1FE634FD4DE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "71D06222-295C-4BB8-8A3B-D1FE634FD4DE",, generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 15:21:20 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable,":true,"peerIdentifier":"71D06222-295C-4BB8-8A3B-D1FE634FD4DE","generation":0}'
2017-07-21 15:21:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 15:21:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F6D29EA3-480A-4F67-9CD5-38A122C3C78F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F6D29EA3-480A-4F67-9CD5-38A122C3C78F", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1D9A3D8B-3C2F-4998-9257-A991FA5C3FB2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1D9A3D8B-3C2F-4998-9257-A991FA5C3FB2", generation: 0)
2017-07-21 15:21:21 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"1D9A3D8B-3C2F-4998-9257-A991FA5C3FB2","generation":0}'
2017-07-21 15:21:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 15:21:21 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 15:21:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FAD89D0B-CF43-4EB0-8738-6F7DCA10BAAF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FAD89D0B-CF43-4EB0-8738-6F7DCA10BAAF", generation: 0)
2017-07-21 15:21:21 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FAD89D0B-CF43-4EB0-8738-6F7DCA10BAAF","generation":0}'
2017-07-21 15:21:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 15:21:21 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 15:21:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 15:21:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:80E413B1-FE3A-450A-9B20-73B6C55150CC:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:80,E413B1-FE3A-450A-9B20-73B6C55150CC:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "80E413B1-FE3A-450A-9B20-73B6C55150CC", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,0E413B1-FE3A-450A-9B20-73B6C55150CC", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "80E413B1-FE3A-450A-9B20-73B6C55150CC", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:80E413B1-FE3A-450A-9B20-73B6C55150CC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:80E413B1-FE3A-450A-9B20-73B6C55150CC:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:80E413B1-FE3A-450A-9B20-73B6C55150CC:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:80,E413B1-FE3A-450A-9B20-73B6C55150CC:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "80E413B1-FE3A-450A-9B20-73B6C55150CC", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,0E413B1-FE3A-450A-9B20-73B6C55150CC", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "80E413B1-FE3A-450A-9B20-73B6C55150CC", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:80E413B1-FE3A-450A-9B20-73B6C55150CC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:80E413B1-FE3A-450A-9B20-73B6C55150CC:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:80E413B1-FE3A-450A-9B20-73B6C55150CC:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "80E413B1-FE3A-450A-9B20-73B6C55150CC", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:80E413B1-FE3A-450A-9B20-73B6C55150CC:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:80,E413B1-FE3A-450A-9B20-73B6C55150CC:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "80E413B1-FE3A-450A-9B20-73B6C55150CC", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,0E413B1-FE3A-450A-9B20-73B6C55150CC", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "80E413B1-FE3A-450A-9B20-73B6C55150CC", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 15:21:28 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"w0cokAuGFJz6hqcGz5ZenxFzZdIJ5KXu","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 15:21:28 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'w0cokAuGFJz6hqcGz5ZenxFzZdIJ5KXu', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 15:21:28 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"80E413B1-FE3A-450A-9B20-73B6C55150CC","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 15:21:28 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 15:21:28 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"80E413B1-FE3A-450A-9B20-73B6C55150CC","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-21 15:21:28 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 15:21:28 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 15:21:28 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 71D06222-295C-4BB8-8A3B-D1FE634FD4DE (syncValue: mGlShGFVN2C4ky40OB4Yeth,7zpBakSN2)'
2017-07-21 15:21:28 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "71D06222-295C-4BB8-8A3B-D1FE634FD4DE", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "71D06222-295C-4BB8-8A3B-D1FE634FD4DE", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:71D06222-295C-4BB8-8A3B-D1FE6,34FD4DE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 15:21:28 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 ,1,5:21:28 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:80E413B1-FE3A-450A-9B20-73B6C55150CC:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2067DDBF-3618-495B-822C-635FED7DB995
[ThaliCore] Advertiser: session connected Peer(uuid: "F6D29EA3-480A-4F67-9CD5-38A122C3C78F", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:2067DDBF-3618-495B-822C-635FED7DB995 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:71D06222-295C-4BB8-8A3B-D1FE634FD4DE:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:71,D06222-295C-4BB8-8A3B-D1FE634FD4DE:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "71D06222-295C-4BB8-8A3B-D1FE634FD4DE", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,1D06222-295C-4BB8-8A3B-D1FE634FD4DE", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "71D06222-295C-4BB8-8A3B-D1FE634FD4DE", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:71D06222-295C-4BB8-8A3B-D1FE634FD4DE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:71D06222-295C-4BB8-8A3B-D1FE634FD4DE:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D06043C6-7706-4FCE-804D-0BCDE3AF37F0
[ThaliCore] Advertiser: session connected Peer(uuid: "F6D29EA3-480A-4F67-9CD5-38A122C3C78F", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:D06043C6-7706-4FCE-804D-0BCDE3AF37F0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2067DDBF-3618-495B-822C-635FED7DB995
,[ThaliCore] Session.session(_:peer:didChange:) peer:2067DDBF-3618-495B-822C-635FED7DB995 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2067DDBF-3618-495B-822C-635FED7DB995
[ThaliCore] Session.startOutputStream(with:) peer:2067DDBF-3618-495B-822C-635FED7DB995
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,1 [5, 6, 11]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-21 15:21:33 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
2017-07-21 15:21:33 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
2017-07-21 15:21:33 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
2017,-07-21 15:21:33 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 15:21:33 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 15:21:33 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-21 15:21:33 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 15:21:33 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-21 15:21:33 - DEBUG testThaliMobileNative: 'Server received (3143 bytes):'
,2017-07-21 15:21:33 - DEBUG testThaliMobileNative: 'Server received (3427 bytes):'
,2017-07-21 15:21:33 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-21 15:21:33 - DEBUG testThaliMobileNative: 'Server received (4309 bytes):'
,2017-07-21 15:21:33 - DEBUG testThaliMobileNative: 'Server received (71 bytes):'
,2017-07-21 15:21:33 - DEBUG testThaliMobileNative: 'Server received (21788 bytes):'
,2017-07-21 15:21:33 - DEBUG testThaliMobileNative: 'Server received (8708 bytes):'
,2017-07-21 15:21:33 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-21 15:21:33 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-21 15:21:33 - DEBUG testThaliMobileNative: 'Server data flushed',
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:11
[ThaliCore] VirtualSocket.closeStreams() vsID:11
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:11
[ThaliCore] VirtualSocket.deinit vsID:11 [5, 6]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:71D06222-295C-4BB8-8A3B-D1FE634FD4DE:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:71,D06222-295C-4BB8-8A3B-D1FE634FD4DE:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "71D06222-295C-4BB8-8A3B-D1FE634FD4DE", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "71D06222-295C-4BB8-8A3B-D1FE634FD4DE", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "71D06222-295C-4BB8-8A3B-D1FE634FD4DE", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:71D06222-295C-4BB8-8A3B-D1FE634FD4DE:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:71D06222-295C-4BB8-8A3B-D1FE634FD4DE:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D06043C6-7706-4FCE-804D-0BCDE3AF37F0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D06043C6-7706-4FCE-804D-0BCDE3AF37F0 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D06043C6-7706-4FCE-804D-0BCDE3AF37F0
[ThaliCore] Session.startOutputStream(with:) peer:D06043C6-7706-4FCE-804D-0BCDE3AF37F0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,2 [5, 6, 12]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-21 15:21:34 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 15:21:34 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 15:21:34 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-21 15:21:34 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
2017-07-21 15:21:34 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
2017-07-21 15:21:34 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
2017,-07-21 15:21:34 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-21 15:21:34 - DEBUG testThaliMobileNative: 'Server received (7665 bytes):'
,2017-07-21 15:21:34 - DEBUG testThaliMobileNative: 'Server received (12045 bytes):'
,2017-07-21 15:21:34 - DEBUG testThaliMobileNative: 'Server received (7665 bytes):'
,2017-07-21 15:21:34 - DEBUG testThaliMobileNative: 'Server received (7665 bytes):'
,2017-07-21 15:21:34 - DEBUG testThaliMobileNative: 'Server received (8596 bytes):'
,2017-07-21 15:21:34 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-21 15:21:34 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-21 15:21:34 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:12
[ThaliCore] VirtualSocket.closeStreams() vsID:12
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:12
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] VirtualSocket.deinit vsID:12 [5, 6]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:71D06222-295C-4BB8-8A3B-D1FE634FD4DE:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:71,D06222-295C-4BB8-8A3B-D1FE634FD4DE:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "71D06222-295C-4BB8-8A3B-D1FE634FD4DE", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,1D06222-295C-4BB8-8A3B-D1FE634FD4DE", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "71D06222-295C-4BB8-8A3B-D1FE634FD4DE", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:71D06222-295C-4BB8-8A3B-D1FE634FD4DE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:71D06222-295C-4BB8-8A3B-D1FE634FD4DE:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:71D06222-295C-4BB8-8A3B-D1FE634FD4DE:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:71,D06222-295C-4BB8-8A3B-D1FE634FD4DE:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "71D06222-295C-4BB8-8A3B-D1FE634FD4DE", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:71D06222,-295C-4BB8-8A3B-D1FE634FD4DE error: max retries exceeded
2017-07-21 15:21:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"mGlShGFVN2C4ky40OB4Yeth7zpBakSN2","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 15:21:38 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'mGlShGFVN2C4ky40OB4Yeth7zpBakSN2', error: 'Connection could not be established', listeningPort: '%s''
2017-07-21 15:21:38 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"71D06222-295C-4BB8-8A3B-D1FE634FD4DE","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 15:21:38 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-21 15:21:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"71D06222-295C-4BB8-8A3B-D1FE634FD4DE","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-21 15:21:38 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 15:21:38 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-21 15:21:38 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 1D9A3D8B-3C2F-4998-9257-A991FA5C3FB2 (syncValue: e84T71A,TnhAlDt4wPcXGPU3w3C8FToz0)'
2017-07-21 15:21:38 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1D9A3D8B-3C2F-4998-9257-A991FA5C3FB2", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1D9A3D8B-3C2F-4998-9257-A991FA5C3FB2", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1D9A3D8B-3C2F,-4998-9257-A991FA5C3FB2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 15:21:38 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
,2017-07-21 15:21:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:71D06222-295C-4BB8-8A3B-D1FE634FD4DE:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:71D06222-295C-4BB8-8A3B-D1FE634FD4DE:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "71D06222-295C-4BB8-8A3B-D1FE634FD4DE", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:1D9A3D8B-3C2F-4998-9257-A991FA5C3FB2:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1D9A3D8B-3C2F-4998-9257-A991FA5C3FB2:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:1D9A3D8B-3C2F-4998-9257-A991FA5C3FB2:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "1D9A3D8B-3C2F-4998-9257-A991FA5C3FB2", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57811
2017-07-21 15:21:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"e84T71ATnhAlDt4wPcXGPU3w3C8FToz0",,"error":null,"portNumber":57811}'
2017-07-21 15:21:41 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'e84T71ATnhAlDt4wPcXGPU3w3C8FToz0', error: 'null', listeningPort: '57811''
,Connecting to the localhost:57811
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:1D9A3D8B-3C2F-4998-9257-A991FA5C3FB2:0
Connected to the localhost:57811
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1D9A3D8B-3C2F-4998-9257-A991FA5C3FB2:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [5, 6, 13]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 15:21:41 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-21 15:21:41 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:13
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:13
[ThaliCore] VirtualSocket.deinit vsID:13 [5, 6]
,ok 102 got the same data back
,# teardown
,2017-07-21 15:21:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 15:21:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 15:21:41 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:21:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:F6D29EA3-480A-4F67-9CD5-38A122C3C78F
,2017-07-21 15:21:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:21:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:1D9A3D8B-3C2F-4998-9257-A991FA5C3FB2
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57811
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:1D9A3D8B-3C2F-4998-9257-A991FA5C3FB2:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D06043C6-7706-4FCE-804D-0BCDE3AF37F0 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "F6D29EA3-480A-4F67-9CD5-38A122C3C78F", generation: 0)
,[ThaliCore] AdvertiserRelay.closeRelay()
,[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:D06043C6-7706-4FCE-804D-0BCDE3AF37F0
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:2067DDBF-3618-495B-822C-635FED7DB995 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "F6D29EA3-480A-4F67-9CD5-38A122C3C78F", generation: 0)
,[ThaliCore] Session.deinit peer:1D9A3D8B-3C2F-4998-9257-A991FA5C3FB2:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-21 15:21:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:21:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:21:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:21:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 15:21:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:21:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:21:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:21:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:D06043C6-7706-4FCE-804D-0BCDE3AF37F0
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7D10023B-E2E4-4B23-AD5B-CF557B426356
[ThaliCore] Browser.startListening
2017-07-21 15:21:42 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 15:21:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:21:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 103 We should start ,listening fine
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A8356DEC-E68F-4142-8FBA-FE2C3F945A22", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:A8356DEC-E68F-4142-8FBA-FE2C3F945,A,22
2017-07-21 15:21:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 15:21:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true},) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:21:42 - INFO thaliMobile: 'Filtered out discoveryAdvertising,StateUpdate (was in stopped state).'
ok 104 We should start updating fine
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FAD89D0B-CF43-4EB0-8738-6F7DCA10BAAF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FAD89D0B-CF43-4EB0-8738-6F7DCA10BAAF", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1D9A3D8B-3C2F-4998-9257-A991FA5C3FB2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1D9A3D8B-3C2F-4998-9257-A991FA5C3FB2", generation: 0)
2017-07-21 15:21:43 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"FAD89D0B-CF43-4EB0-8738-6F7DCA10BAAF","generation":0}]'
,2017-07-21 15:21:43 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"FAD89D0B-CF43-4EB0-8738-6F7DCA10BAAF","generation":0}'
2017-07-21 15:21:43 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 15:21:43 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"1D9A3D8B-3C2F-4998-9257-A991FA5C3FB2","generation":0}]'
2017-07-21 15:21:43 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"1D9A3D8B-3C2F-4998-9257-A991FA5C3FB2","generation":0}'
,2017-07-21 15:21:43 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A8356DEC-E68F-4142-8FBA-FE2C3F945A22:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A8356DEC-E68F-4142-8FBA-FE2C3F945A22", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:79880EFE-5106-4A10-A98C-DCC560D09CF8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "79880EFE-5106-4A10-A98C-DCC560D09CF8", generation: 0)
2017-07-21 15:21:43 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"79880EFE-5106-4A10-A98C-DCC560D09CF8","generation":0}]'
2017-07-21 15:21:43 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"79880EFE-5106-4A10-A98C-DCC560D09CF8","generation":0}'
2017-07-21 15:21:43 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 15:21:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 ,15:21:48 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-21 15:21:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:A8356DEC-E68F-4142-8FBA-F,E2C3F945A22
,2017-07-21 15:21:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:21:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-21 15:21:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:21:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:21:48 ,- DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:21:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:21:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:21:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:21:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:21:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Test updating advertising and parallel data transfer
,2017-07-21 15:21:48 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:21:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:21:48 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:21:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 15:21:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:21:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:21:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:21:48 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:21:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 15:21:48 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 15:21:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 15:21:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 15:21:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FCF00882-3D9A-42F3-BBFB-3BA4BA063A50
[ThaliCore] Browser.startListening
,ok 105 discoveryActive should be false
ok 106 advertisingActive should be true
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C612B65C-AA40-4795-810B-7549376B1902", generation: 0)
[ThaliCore] Advertise,r.startAdvertising with peerID:C612B65C-AA40-4795-810B-7549376B1902
ok 107 discoveryActive should be false
ok 108 advertisingActive should be true
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
ok 109 d,iscoveryActive should be false
ok 110 advertisingActive should be true
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:C612B65C-AA40-4795-810B-7549376B1902
ok 111 discoveryActive should be false
ok 112 a,dvertisingActive should be true
ok 113 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:21:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:21:49 - DEBUG thaliMobi,leNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:21:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:21:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 15:21:49 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 15:21:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 15:21:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 15:21:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-07-21 15:21:49 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:21:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:21:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 114 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:21:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:21:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 115 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-21 15:21:49 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:21:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:21:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 116 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:21:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:21:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 117 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-21 15:21:50 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:21:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:21:50 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 118 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:21:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:21:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 119 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-21 15:21:50 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:21:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:21:51 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:21:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:21:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-21 15:21:51 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:21:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:21:51 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 122 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:21:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:21:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 123 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-21 15:21:51 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:21:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:21:51 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 124 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:21:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:21:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 125 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 126 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:e2b81414-d8c8-4096-9c68-0fe1949f309e error: startListeningNotActive
,2017-07-21 15:21:51 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"PJCNubykyMkIgbGzreqLlvtiRiWYj4yi","error":"startListeningForAdvertisements is not active","portNumber":null}'
ok 127 Should only get called after multiConnect retur,ned
ok 128 SyncValue matches
ok 129 Got right error
ok 130 listeningPort is null
2017-07-21 15:21:51 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"e2b81414-d8c8-4096-9c68-0fe1949f309e","peerAvailabl,e":false,"portNumber":null,"recreated":true}'
2017-07-21 15:21:51 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-21 15:21:51 - DEBUG thaliMobileNativeWrapper: 'Received peer a,vailability changed event with {"peerIdentifier":"e2b81414-d8c8-4096-9c68-0fe1949f309e","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-21 15:21:51 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due t,o, not being in started state'
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:21:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:21:52 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:21:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
,2017-07-21 15:21:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 15:21:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:21:52 - DEBUG thaliMo,bileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:21:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:21:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 15:21:52 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 15:21:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 15:21:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 15:21:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A7C0F885-ADD5-4FB7-93B3-7B8C8BE36F19
[ThaliCore] Browser.startListening
2017-07-21 15:21:52 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 15:21:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:21:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 131 No error on star,ting
ok 132 Got null as expected
2017-07-21 15:21:52 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"kd84pkpTYsfdDNSSkzpu46V45E9y6FkE","error":"Illegal peerID","portNumber":null}'
ok 133 Should only get called after multiConnect ,r,eturned
ok 134 SyncValue matches
ok 135 Got right error
ok 136 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 15:21:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21, 15:21:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:21:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-07-21 15:21:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 15:21:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to n,ative'
,2017-07-21 15:21:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:21:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:21:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:21:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:21:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:21:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:21:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# multiConnect properly fails on legal but non-existent peerID
,2017-07-21 15:21:53 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:21:55 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 15:21:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:21:55 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 15:21:55 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BBE0F5A2-2438-4F74-85BB-D1AED57F413D
[ThaliCore] Browser.startListening
2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 15:21:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-21 15:21:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 137 No error on starting
ok 138 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21, 15:21:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-07-21 15:21:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:21:55 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:21:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call disconnect with invalid peer id
,ok 139 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:21:55 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 15:21:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:21:55 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 15:21:55 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:c9479994-ac62-419f-8c0e-cc9a3bd1e0a1
ok 140 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:21:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:21:56 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:21:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 15:21:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:21:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:21:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:21:56 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:21:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 15:21:56 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 15:21:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 15:21:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-07-21 15:21:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "EA78C7AA-4E06-4DC5-A977-A2F4BDFF7B20", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:EA78C7AA-4E06-4DC5-A977-A2F4BDFF7B20
2017-07-21 1,5:21:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 15:21:56 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:21:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 141 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C1124706-3E29-4E98-AEEA-6AC836BBE397
[Tha,l,iCore] Browser.startListening
2017-07-21 15:21:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 15:21:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:21:56 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 142 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FAD89D0B-CF43-4EB0-8738-6F7DCA10BAAF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FAD89D0B-CF43-4EB0-8738-6F7DCA10BAAF", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:79880EFE-5106-4A10-A98C-DCC560D09CF8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "79880EFE-5106-4A10-A98C-DCC560D09CF8", generation: 0)
2017-07-21 15:21:56 - DEBUG thaliMobileNativeTestUtils: 'W,e got a peer {"peerAvailable":true,"peerIdentifier":"FAD89D0B-CF43-4EB0-8738-6F7DCA10BAAF","generation":0}'
,2017-07-21 15:21:56 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for FAD89D0B-CF43-4EB0-8738-6F7DCA10BAAF (syncValue: TcDW1RuIEqsOPWRIMADwYtRlzPi28cdw)'
,2017-07-21 15:21:56 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FAD89D0B-CF43-4EB0-8738-6F7DCA10BAAF", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FAD89D0B-CF43-4EB0-8738-6F7DCA10BAAF", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FAD89D0B-CF43-4EB0-8738-6F7DCA10BAAF:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 15:21:56 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"79880EFE-5106-4A10-A98C-DCC560D09CF8","generation":0}'
,2017-07-21 15:21:56 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 15:21:56 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:814704C1-77B8-4718-B0BA-A0A557E53065:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "814704C1-77B8-4718-B0BA-A0A557E53065", generation: 0)
2017-07-21 15:21:57 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"814704C1-77B8-4718-B0BA-A0A557E53065","generation":0}'
2017-07-21 15:21:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 15:21:57 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 15:21:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:21592C4B-4C4F-4572-B106-48B3883ACB80:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "21592C4B-4C4F-4572-B106-48B3883ACB80", generation: 0)
2017-07-21 15:21:57 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"21592C4B-4C4F-4572-B106-48B3883ACB80","generation":0}'
2017-07-21 15:21:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 15:21:57 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 15:21:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 15:21:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EA78C7AA-4E06-4DC5-A977-A2F4BDFF7B20:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EA78C7AA-4E06-4DC5-A977-A2F4BDFF7B20", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:FAD89D0B-CF43-4EB0-8738-6F7DCA10BAAF:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "FAD89D0B-CF43-4EB0-8738-6F7DCA10BAAF", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:FAD89D0B-CF43-4EB0-8738-6F7DCA10BAAF:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FA,D89D0B-CF43-4EB0-8738-6F7DCA10BAAF:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "FAD89D0B-CF43-4EB0-8738-6F7DCA10BAAF", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,AD89D0B-CF43-4EB0-8738-6F7DCA10BAAF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FAD89D0B-CF43-4EB0-8738-6F7DCA10BAAF", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 15:21:59 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"TcDW1RuIEqsOPWRIMADwYtRlzPi28cdw","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 15:21:59 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'TcDW1RuIEqsOPWRIMADwYtRlzPi28cdw', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 15:21:59 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"FAD89D0B-CF43-4EB0-8738-6F7DCA10BAAF","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 15:21:59 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 15:21:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"FAD89D0B-CF43-4EB0-8738-6F7DCA10BAAF","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-21 15:21:59 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 15:21:59 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 15:21:59 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 79880EFE-5106-4A10-A98C-DCC560D09CF8 (syncValue: hIjAQ0Ztti8q9tbRa4mcZrS,bTTVi5F8m)'
2017-07-21 15:21:59 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "79880EFE-5106-4A10-A98C-DCC560D09CF8", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "79880EFE-5106-4A10-A98C-DCC560D09CF8", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:79880EFE-5106-4A10-A98C-DCC56,0D09CF8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 15:21:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 ,1,5:21:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:FAD89D0B-CF43-4EB0-8738-6F7DCA10BAAF:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:79880EFE-5106-4A10-A98C-DCC560D09CF8:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:79,880EFE-5106-4A10-A98C-DCC560D09CF8:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "79880EFE-5106-4A10-A98C-DCC560D09CF8", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,9880EFE-5106-4A10-A98C-DCC560D09CF8", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "79880EFE-5106-4A10-A98C-DCC560D09CF8", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:79880EFE-5106-4A10-A98C-DCC560D09CF8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:79880EFE-5106-4A10-A98C-DCC560D09CF8:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:79880EFE-5106-4A10-A98C-DCC560D09CF8:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:79,880EFE-5106-4A10-A98C-DCC560D09CF8:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "79880EFE-5106-4A10-A98C-DCC560D09CF8", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,9880EFE-5106-4A10-A98C-DCC560D09CF8", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "79880EFE-5106-4A10-A98C-DCC560D09CF8", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:79880EFE-5106-4A10-A98C-DCC560D09CF8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:79880EFE-5106-4A10-A98C-DCC560D09CF8:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:79880EFE-5106-4A10-A98C-DCC560D09CF8:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "79880EFE-5106-4A10-A98C-DCC560D09CF8", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:79880EFE-5106-4A10-A98C-DCC560D09CF8:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:79,880EFE-5106-4A10-A98C-DCC560D09CF8:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "79880EFE-5106-4A10-A98C-DCC560D09CF8", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,9880EFE-5106-4A10-A98C-DCC560D09CF8", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "79880EFE-5106-4A10-A98C-DCC560D09CF8", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 15:22:07 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"hIjAQ0Ztti8q9tbRa4mcZrSbTTVi5F8m","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 15:22:07 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'hIjAQ0Ztti8q9tbRa4mcZrSbTTVi5F8m', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 15:22:07 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"79880EFE-5106-4A10-A98C-DCC560D09CF8","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 15:22:07 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 15:22:07 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"79880EFE-5106-4A10-A98C-DCC560D09CF8","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-21 15:22:07 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 15:22:07 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 15:22:07 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 814704C1-77B8-4718-B0BA-A0A557E53065 (syncValue: TDMwlsnWfapHqO6uL8GHt5z,QSVgMftnq)'
2017-07-21 15:22:07 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "814704C1-77B8-4718-B0BA-A0A557E53065", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "814704C1-77B8-4718-B0BA-A0A557E53065", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:814704C1-77B8-4718-B0BA-A0A55,7E53065:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 15:22:07 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:79880EFE-5106-4A10-A98C-DCC560D09CF8:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:814704C1-77B8-4718-B0BA-A0A557E53065:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:814704C1-77B8-4718-B0BA-A0A557E53065:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:814704C1-77B8-4718-B0BA-A0A557E53065:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "814704C1-77B8-4718-B0BA-A0A557E53065", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57827
2017-07-21 15:22:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"TDMwlsnWfapHqO6uL8GHt5zQSVgMftnq",,"error":null,"portNumber":57827}'
2017-07-21 15:22:11 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'TDMwlsnWfapHqO6uL8GHt5zQSVgMftnq', error: 'null', listeningPort: '57827''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:814704C1-77B8-4718-B0BA-A0A557E53065:0
ok 143 Got null as expected
[ThaliCore] BrowserManager.co,nnectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "814704C1-77B8-4718-B0BA-A0A557E53065", generation: 0) found active relay
2017-07-21 15:22:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"NVL2NXsArfEXKgIwWT3DhvyYfPP1jzR,r","error":null,"portNumber":57827}'
ok 144 No error
ok 145 Ports equal
ok 146 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "814704C1-77B8-4718-B0BA-A0A557E53065", generation: 0) found active relay
,2017-07-21 15:22:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"c3VySaGfiaAlMYj1EfUfQNc1JZ7pkRL3","error":null,"portNumber":57827}'
,ok 147 No error
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:814704C1-77B8-4718-B0BA-A0A557E53065:0
ok 148 Ports equal
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [5, 6, 14]
[ThaliCore] BrowserRelay.didOpenVir,tualSocketStreamsHandler
,# teardown
,2017-07-21 15:22:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 15:22:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 15:22:11 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:22:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:EA78C7AA-4E06-4DC5-A977-A2F4BDFF7B20
,2017-07-21 15:22:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:22:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:814704C1-77B8-4718-B0BA-A0A557E53065
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57827
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] VirtualSocket.closeStreams() vsID:14
,[ThaliCore] VirtualSocket exited RunLoop vsID:14
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] VirtualSocket.deinit vsID:14 [5, 6]
,[ThaliCore] Session.disconnect() peer:814704C1-77B8-4718-B0BA-A0A557E53065:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:814704C1-77B8-4718-B0BA-A0A557E53065:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "814704C1-77B8-4718-B0BA-A0A557E53065", generation: 0)
,2017-07-21 15:22:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:22:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:22:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:22:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:22:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:22:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:22:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:22:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-21 15:22:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"TDMwlsnWfapHqO6uL8GHt5zQSVgMftnq","error":"Session disconnected","portNumber":null}'
,2017-07-21 15:22:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"814704C1-77B8-4718-B0BA-A0A557E53065","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 15:22:11 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 15:22:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"814704C1-77B8-4718-B0BA-A0A557E53065","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 15:22:11 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:814704C1-77B8-4718-B0BA-A0A557E53065:0
[ThaliCore] BrowserRelay.deinit
,# initial peer discovery
,2017-07-21 15:22:12 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-07-21 15:22:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:22:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:22:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:22:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 15:22:12 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 15:22:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 15:22:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 15:22:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-07-21 15:22:12 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-07-21 15:22:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:22:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:22:13 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:22:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 15:22:13 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 15:22:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 15:22:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 15:22:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-07-21 15:22:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-07-21 15:22:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:22:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:22:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:22:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 15:22:13 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 15:22:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 15:22:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 15:22:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-07-21 15:22:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-07-21 15:22:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:22:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:22:13 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:22:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 15:22:13 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 15:22:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 15:22:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 15:22:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-07-21 15:22:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-07-21 15:22:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:22:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:22:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:22:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 15:22:14 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 15:22:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 15:22:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 15:22:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-07-21 15:22:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-07-21 15:22:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:22:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:22:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:22:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 15:22:14 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 15:22:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 15:22:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 15:22:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-21 15:22:14 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 15:22:14 - DEBUG createNativeListener: 'listening 57830'
ok 149 Should throw
,# teardown
,2017-07-21 15:22:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 15:22:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 15:22:15 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-21 15:22:15 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 15:22:15 - DEBUG createNativeListener: 'listening 57832'
,2017-07-21 15:22:15 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 15:22:15 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 150 initial connection state should be CONNECTED
,2017-07-21 15:22:15 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 151 final connection state should be DISCONNECTED
,# teardown
,2017-07-21 15:22:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 15:22:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 15:22:15 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-07-21 15:22:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 15:22:15 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 15:22:15 - DEBUG createNativeListener: 'listening 57835'
,2017-07-21 15:22:15 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 15:22:15 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 15:22:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 15:22:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 152 tried to connect to right port
,ok 153 failed due to refused connection
,ok 154 routerPortConnectionFailed is emitted
,# teardown
,2017-07-21 15:22:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 15:22:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 15:22:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 15:22:16 - DEBUG createNativeListener: 'Native Server - close'
2017-07-21 15:22:16 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <,-> Mux - 0 - close'
,2017-07-21 15:22:16 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-07-21 15:22:16 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 15:22:16 - DEBUG createNativeListener: 'listening 57839'
,2017-07-21 15:22:16 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 15:22:16 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 15:22:16 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2017-07-21 15:22:16 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - ,0 - 1 - created'
,ok 155 Send/recvd #1 should be equal length
,ok 156 Send/recvd #1 should be same
,ok 157 Send/recvd #2 should be equal length
,ok 158 Send/recvd #2 should be same
,ok 159 Should be exactly 2 client sockets
,# teardown
,2017-07-21 15:22:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 15:22:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 15:22:16 - DEBUG createNativeListener: 'Native Server - close'
2017-07-21 15:22:16 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 15:22:16 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-21 15:22:16 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 15:22:16 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,2017-07-21 15:22:16 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-21 15:22:16 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-07-21 15:22:16 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 15:22:16 - DEBUG createNativeListener: 'listening 57844'
,2017-07-21 15:22:16 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 15:22:16 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 15:22:16 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 15:22:16 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2017-07-21 15:22:16 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node -, 0 - 0 - closed'
,ok 160 socket shouldn't close until after stream
ok 161 incoming remains open
# teardown
,2017-07-21 15:22:16 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 15:22:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 15:22:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 15:22:17 - DEBUG createNativeListener: 'Native Server - close'
2017-07-21 15:22:17, - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 15:22:17 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-07-21 15:22:17 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 15:22:17 - DEBUG createNativeListener: 'listening 57848'
,2017-07-21 15:22:17 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 15:22:17 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 162 we should not have gotten an error
,2017-07-21 15:22:17 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 15:22:17 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-07-21 15:22:17 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - cl,ose'
,ok 163 socket shouldn't close until after incoming
ok 164 incoming is cleaned up
# teardown
,2017-07-21 15:22:17 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 15:22:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 15:22:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 15:22:17 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-21 15:22:17 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 15:22:17 - DEBUG createNativeListener: 'listening 57852'
,2017-07-21 15:22:17 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 15:22:17 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 15:22:17 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 15:22:17 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2017-07-21 15:22:17 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node -, 0 - 0 - closed'
2017-07-21 15:22:17 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 165 stream was closed
ok 166 incoming should survive
ok 167 mux should have no streams
,# teardown
,2017-07-21 15:22:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 15:22:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 15:22:18 - DEBUG createNativeListener: 'Native Server - close'
2017-07-21 15:22:18 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 15:22:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-21 15:22:18 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 15:22:18 - DEBUG createNativeListener: 'listening 57856'
,2017-07-21 15:22:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 15:22:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 168 we should not have gotten an error
,2017-07-21 15:22:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 169 Buffers are identical
,2017-07-21 15:22:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 15:22:18 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-21 15:22:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 15:22:18 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 170 native server is nulled out
,ok 171 native server should be closed
,ok 172 incoming has been removed
,ok 173 Incoming should be done
,ok 174 The mux object should be closed
,ok 175 The mux stream should be closed
,2017-07-21 15:22:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
,2017-07-21 15:22:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 15:22:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-07-21 15:22:18 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 15:22:18 - DEBUG createNativeListener: 'listening 57860'
,2017-07-21 15:22:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 15:22:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-07-21 15:22:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
,2017-07-21 15:22:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 15:22:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
,2017-07-21 15:22:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 15:22:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
,2017-07-21 15:22:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 15:22:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
,2017-07-21 15:22:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 15:22:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
,2017-07-21 15:22:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 176 native server is nulled out
,ok 177 native server should be closed
,ok 178 incoming has been removed
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-21 15:22:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-07-21 15:22:20 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 15:22:20 - DEBUG createNativeListener: 'listening 57912'
,2017-07-21 15:22:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 15:22:20 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 179 we should not have gotten an error
,2017-07-21 15:22:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 180 Buffers are identical
2017-07-21 15:22:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-07-21 15:22:20 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client co,nnection <-> Mux - 0 - close'
,2017-07-21 15:22:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 181 server should be fine
ok 182 server should be open
ok 183 incoming has been removed
ok 184 The mux object should be clos,ed
ok 185 The mux stream should be closed
2017-07-21 15:22:20 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-21 15:22:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 15:22:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 15:22:20 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-21 15:22:21 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 15:22:21 - DEBUG createNativeListener: 'listening 57916'
,2017-07-21 15:22:21 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 15:22:21 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 186 we should not have gotten an error
,2017-07-21 15:22:21 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 187 Buffers are identical
,2017-07-21 15:22:21 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
2017-07-21 15:22:21 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to ,node - 0 - 0 - closed'
2017-07-21 15:22:21 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-07-21 15:22:21 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux, - 0 - close'
ok 188 server should be fine
ok 189 server should be open
ok 190 incoming has been removed
ok 191 The mux object should be closed
ok 192 The mux stream should be closed
,# teardown
,2017-07-21 15:22:21 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 15:22:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 15:22:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 15:22:21 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# can create servers manager
,ok 193 serversManager must not be null
ok 194 serversManager must be an object
,# teardown
,# setup
,# calling stop without start causes error
,ok 195 We need to call start first
,# teardown
,# setup
,# can start/stop servers manager
,2017-07-21 15:22:21 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 15:22:21 - DEBUG createNativeListener: 'listening 57919'
,ok 196 port must be in range
,# teardown
,2017-07-21 15:22:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 15:22:21 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-21 15:22:22 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 15:22:22 - DEBUG createNativeListener: 'listening 57920'
ok 197 second start should return same port
,# teardown
,2017-07-21 15:22:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 15:22:22 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-21 15:22:22 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 15:22:22 - DEBUG createNativeListener: 'listening 57922'
,2017-07-21 15:22:22 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 15:22:22 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 198 we should be connected
2017-07-21 15:22:22 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 199 now we are disconnected
,2017-07-21 15:22:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-21 15:22:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 15:22:22 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-07-21 15:22:22 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
ok 200 Passed bogus id
2017-07-21 15:22:22 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port, 901'
ok 201 Passed good id but bogus port
2017-07-21 15:22:22 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
ok 202 Passed right context
ok 203 Right server
ok 204 No error should be set
ok 205 Retry should be false
ok 206 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 57924
,ok 207 should be equal
# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:22:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:22:22 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:22:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 15:22:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 15:22:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 15:22:22 - DEBUG thaliMobileNativeWrapper: 'Me,thod peerAvailabilityChanged registered to native'
2017-07-21 15:22:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:22:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolv,e,d registered to native'
,2017-07-21 15:22:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 15:22:22 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 15:22:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 15:22:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 15:22:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "40621967-7A54-466D-8CBB-4245C86531C6", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:40621967-7A54-466D-8CBB-4245C86531C6
,2017-07-21 15:22:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 15:22:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:22:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 208 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7875D863-3C23-4520-81CA-072A2B8,2D404
[ThaliCore] Browser.startListening
2017-07-21 15:22:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 15:22:23 - INFO thaliMobile: 'Received state ({"discove,r,yActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:22:23 - INFO thaliMob,ile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 209 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:814704C1-77B8-4718-B0BA-A0A557E53065:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "814704C1-77B8-4718-B0BA-A0A557E53065", generation: 0)
,2017-07-21 15:22:23 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"814704C1-77B8-4718-B0BA-A0A557E53065","generation":0}'
,2017-07-21 15:22:23 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 814704C1-77B8-4718-B0BA-A0A557E53065 (syncValue: Ht7syvbwGvF6ItJZ5r3BUmkJLxAvh001)'
,2017-07-21 15:22:23 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "814704C1-77B8-4718-B0BA-A0A557E53065", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "814704C1-77B8-4718-B0BA-A0A557E53065", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:814704C1-77B8-4718-B0BA-A0A557E53065:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:40457155-87AB-4CFC-92D7-0BAAB9373290:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "40457155-87AB-4CFC-92D7-0BAAB9373290", generation: 0)
2017-07-21 15:22:24 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"40457155-87AB-4CFC-92D7-0BAAB9373290","generation":0}'
2017-07-21 15:22:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 15:22:24 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:390152AE-1CFD-4486-955C-D5418FB4972F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "390152AE-1CFD-4486-955C-D5418FB4972F", generation: 0)
2017-07-21 15:22:24 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"390152AE-1CFD-4486-955C-D5418FB4972F","generation":0}'
2017-07-21 15:22:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 15:22:24 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 15:22:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:40621967-7A54-466D-8CBB-4245C86531C6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "40621967-7A54-466D-8CBB-4245C86531C6", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:814704C1-77B8-4718-B0BA-A0A557E53065:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:81,4704C1-77B8-4718-B0BA-A0A557E53065:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "814704C1-77B8-4718-B0BA-A0A557E53065", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,14704C1-77B8-4718-B0BA-A0A557E53065", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "814704C1-77B8-4718-B0BA-A0A557E53065", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:814704C1-77B8-4718-B0BA-A0A557E53065:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:814704C1-77B8-4718-B0BA-A0A557E53065:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:814704C1-77B8-4718-B0BA-A0A557E53065:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "814704C1-77B8-4718-B0BA-A0A557E53065", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:814704C1-77B8-4718-B0BA-A0A557E53065:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:81,4704C1-77B8-4718-B0BA-A0A557E53065:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "814704C1-77B8-4718-B0BA-A0A557E53065", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,14704C1-77B8-4718-B0BA-A0A557E53065", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "814704C1-77B8-4718-B0BA-A0A557E53065", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 15:22:28 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Ht7syvbwGvF6ItJZ5r3BUmkJLxAvh001","error":"Peer is unavailable","portNumber":null}'
2017-07-21 15:22:28 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Ht7syvbwGvF6ItJZ5r3BUmkJLxAvh001', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 15:22:28 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"814704C1-77B8-4718-B0BA-A0A557E53065","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 15:22:28 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 15:22:28 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"814704C1-77B8-4718-B0BA-A0A557E53065","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-21 15:22:28 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 15:22:28 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 15:22:28 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 40457155-87AB-4CFC-92D7-0BAAB9373290 (syncValue: GWwTGNhkLjGsZ14V3U3gNR8,Co04tJn83)'
2017-07-21 15:22:28 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "40457155-87AB-4CFC-92D7-0BAAB9373290", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "40457155-87AB-4CFC-92D7-0BAAB9373290", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:40457155-87AB-4CFC-92D7-0BAAB,9373290:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 15:22:28 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:814704C1-77B8-4718-B0BA-A0A557E53065:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:40457155-87AB-4CFC-92D7-0BAAB9373290:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:40457155-87AB-4CFC-92D7-0BAAB9373290:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:40457155-87AB-4CFC-92D7-0BAAB9373290:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "40457155-87AB-4CFC-92D7-0BAAB9373290", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57934
2017-07-21 15:22:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"GWwTGNhkLjGsZ14V3U3gNR8Co04tJn83",,"error":null,"portNumber":57934}'
2017-07-21 15:22:31 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'GWwTGNhkLjGsZ14V3U3gNR8Co04tJn83', error: 'null', listeningPort: '57934''
,ok 210 should be equal
2017-07-21 15:22:31 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 390152AE-1CFD-4486-955C-D5418FB4972F (syncValue: QFTL2F1l95bhnskhqol4b5LJ06h55GCu)'
2017-07-21 15:22:31 - DEBUG thaliMobileNativeTestUtils: 'Got 'mul,tiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "390152AE-1CFD-4486-955C-D5418FB4972F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConn,ected:) Peer(uuid: "390152AE-1CFD-4486-955C-D5418FB4972F", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:390152AE-1CFD-4486-955C-D5418FB4972F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocke,tTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:390152AE-1CFD-4486-955C-D5418FB4972F:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C1E75C3C-DC4C-47DD-AB32-A516A3FEC5A9
[ThaliCore] Advertiser: session connected Peer(uuid: "40621967-7A54-466D-8CBB-4245C86531C6", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:C1E75C3C-DC4C-47DD-AB32-A516A3FEC5A9 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:390152AE-1CFD-4486-955C-D5418FB4972F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:390152AE-1CFD-4486-955C-D5418FB4972F:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "390152AE-1CFD-4486-955C-D5418FB4972F", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57938
2017-07-21 15:22:36 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"QFTL2F1l95bhnskhqol4b5LJ06h55GCu",,"error":null,"portNumber":57938}'
2017-07-21 15:22:36 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'QFTL2F1l95bhnskhqol4b5LJ06h55GCu', error: 'null', listeningPort: '57938''
,ok 211 should be equal
# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0AD041BE-FF06-4505-ADBA-DA2D5A02760B
[ThaliCore] Advertiser: session connected Peer(uuid: "40621967-7A54-466D-8CBB-4245C86531C6", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:0AD041BE-FF06-4505-ADBA-DA2D5A02760B state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C1E75C3C-DC4C-47DD-AB32-A516A3FEC5A9
,[ThaliCore] Session.session(_:peer:didChange:) peer:C1E75C3C-DC4C-47DD-AB32-A516A3FEC5A9 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0AD041BE-FF06-4505-ADBA-DA2D5A02760B
,[ThaliCore] Session.session(_:peer:didChange:) peer:0AD041BE-FF06-4505-ADBA-DA2D5A02760B state: connecting -> connected
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 15:22:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 ,15:22:40 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-21 15:22:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:40621967-7A54-466D-8CBB-4,245C86531C6
2017-07-21 15:22:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:22:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
[ThaliCore] BrowserManager.disconnect peer:40457155-87AB-4CFC-92D7-0BAAB9373290
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57934
[ThaliCore] Sessi,on.disconnect() peer:40457155-87AB-4CFC-92D7-0BAAB9373290:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:40457155-87AB-4CFC-92D7-0BAAB9373290:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:390152AE-1CFD-4486-955C-D5418FB4972F
[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57938
[ThaliCore] Session.disconnect() peer:390152AE-1CFD-4486-955C-D5418FB4972F:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:0AD041BE-FF06-4505-ADBA-DA2D5A02760B state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "40621967-7A54-466D-8CBB-4245C86531C6", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:0AD041BE-FF06-4505-ADBA-DA2D5A02760B
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:C1E75C3C-DC4C-47DD-AB32-A516A3FEC5A9 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "40621967-7A54-466D-8CBB-4245C86531C6", generation: 0)
,[ThaliCore] Session.deinit peer:390152AE-1CFD-4486-955C-D5418FB4972F:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-21 15:22:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 15:22:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:22:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:22:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:22:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 15:22:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:22:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:22:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:22:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple local http requests
,listening on 57940
,ok 212 should be equal
ok 213 should be equal
ok 214 should be equal
# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:22:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:22:41 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:22:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 15:22:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:22:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 15:22:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:22:41 - DEBUG thaliMobileNativeWrapper: 'Method disc,overyAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:22:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:22:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:22:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:22:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:22:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:22:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] Session.deinit peer:0AD041BE-FF06-4505-ADBA-DA2D5A02760B
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5FC4BDB3-3269-4B54-85E8-376E58D2C986", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:5FC4BDB3-3269-4B54-85E8-376E58D2C986
2017-07-21 1,5:22:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 15:22:41 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:22:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 215 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7266E187-C51E-4CA9-874C-AF6B3BA7F377
[Tha,l,iCore] Browser.startListening
2017-07-21 15:22:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 15:22:41 - INFO thaliMobile: 'Received state ({"discoveryActive":tru,e,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:22:41 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 216 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:40457155-87AB-4CFC-92D7-0BAAB9373290:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "40457155-87AB-4CFC-92D7-0BAAB9373290", generation: 0)
2017-07-21 15:22:43 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"40457155-87AB-4CFC-92D7-0BAAB9373290","generation":0}'
2017-07-21 15:22:43 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 40457155-87AB-4CFC-92D7-0BAAB9373290, (syncValue: glPgIHBW8GtXrOHvRXPNkEg74ShwTkYU)'
2017-07-21 15:22:43 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "40457155-87AB-4CFC-92D7-0BAAB93,73290", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "40457155-87AB-4CFC-92D7-0BAAB9373290", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:40457155-87AB-4CFC-92D7-0BAAB9373290:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:390152AE-1CFD-4486-955C-D5418FB4972F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "390152AE-1CFD-4486-955C-D5418FB4972F", generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 15:22:43 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable,":true,"peerIdentifier":"390152AE-1CFD-4486-955C-D5418FB4972F","generation":0}'
2017-07-21 15:22:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 15:22:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4F61844C-075A-49BC-ACFA-4CF243EFC76D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4F61844C-075A-49BC-ACFA-4CF243EFC76D", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B884C051-2B35-4187-B508-14FE33F8367A:0
2017-07-21 15:22:43 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4F61844C-075A-49BC-ACFA-4CF243EFC7,6D","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B884C051-2B35-4187-B508-14FE33F8367A", generation: 0)
,2017-07-21 15:22:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 15:22:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 15:22:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 15:22:43 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B884C051-2B35-4187-B508-14FE33F8367A","generation":0}'
,2017-07-21 15:22:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 15:22:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5FC4BDB3-3269-4B54-85E8-376E58D2C986:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5FC,4BDB3-3269-4B54-85E8-376E58D2C986", generation: 0)
,2017-07-21 15:22:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 15:22:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:40457155-87AB-4CFC-92D7-0BAAB9373290:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:40,457155-87AB-4CFC-92D7-0BAAB9373290:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "40457155-87AB-4CFC-92D7-0BAAB9373290", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,0457155-87AB-4CFC-92D7-0BAAB9373290", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "40457155-87AB-4CFC-92D7-0BAAB9373290", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:40457155-87AB-4CFC-92D7-0BAAB9373290:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:40457155-87AB-4CFC-92D7-0BAAB9373290:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:40457155-87AB-4CFC-92D7-0BAAB9373290:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:40,457155-87AB-4CFC-92D7-0BAAB9373290:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "40457155-87AB-4CFC-92D7-0BAAB9373290", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,0457155-87AB-4CFC-92D7-0BAAB9373290", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "40457155-87AB-4CFC-92D7-0BAAB9373290", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:40457155-87AB-4CFC-92D7-0BAAB9373290:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:40457155-87AB-4CFC-92D7-0BAAB9373290:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:390152AE-1CFD-4486-955C-D5418FB4972F:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "390152AE-1CFD-4486-955C-D5418FB4972F", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:40457155-87AB-4CFC-92D7-0BAAB9373290:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:40,457155-87AB-4CFC-92D7-0BAAB9373290:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "40457155-87AB-4CFC-92D7-0BAAB9373290", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,0457155-87AB-4CFC-92D7-0BAAB9373290", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "40457155-87AB-4CFC-92D7-0BAAB9373290", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:40457155-87AB-4CFC-92D7-0BAAB9373290:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:40457155-87AB-4CFC-92D7-0BAAB9373290:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:13D1E1AC-66F1-4749-BFE1-2D82B6AC3D12
[ThaliCore] Advertiser: session connected Peer(uuid: "5FC4BDB3-3269-4B54-85E8-376E58D2C986", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:13D1E1AC-66F1-4749-BFE1-2D82B6AC3D12 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:40457155-87AB-4CFC-92D7-0BAAB9373290:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:40,457155-87AB-4CFC-92D7-0BAAB9373290:0
,[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "40457155-87AB-4CFC-92D7-0BAAB9373290", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:40457155-87AB-4CFC-92D7-0BAAB9373290 error: ma,x retries exceeded
,2017-07-21 15:22:53 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"glPgIHBW8GtXrOHvRXPNkEg74ShwTkYU","error":"Connection could not be established","portNumber":null}'
,2017-07-21 15:22:53 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'glPgIHBW8GtXrOHvRXPNkEg74ShwTkYU', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-21 15:22:53 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"40457155-87AB-4CFC-92D7-0BAAB9373290","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 15:22:53 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 15:22:53 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"40457155-87AB-4CFC-92D7-0BAAB9373290","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 15:22:53 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 15:22:53 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-21 15:22:53 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4F61844C-075A-49BC-ACFA-4CF243EFC76D (syncValue: 17LXKvwLU7FUeInG1qJkiwViHTSiOi1V)'
,2017-07-21 15:22:53 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4F61844C-075A-49BC-ACFA-4CF243EFC76D", generation: 0) creating a new relay
[Tha,liCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4F61844C-075A-49BC-ACFA-4CF243EFC76D", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4F61844C-075A-49BC-ACFA-4CF243EFC76D:0
[T,haliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 15:22:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 15:22:53 - DEB,UG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:40457155-87AB-4CFC-92D7-0BAAB9373290:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:4F61844C-075A-49BC-ACFA-4CF243EFC76D:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:40457155-87AB-4CFC-92D7-0BAAB9373290:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "40457155-87AB-4CFC-92D7-0BAAB9373290", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:13D1E1AC-66F1-4749-BFE1-2D82B6AC3D12
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4F61844C-075A-49BC-ACFA-4CF243EFC76D:0
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BC0799A4-7E47-446E-BC6F-7D9DFC5701E5
[ThaliCore] Advertiser: session connected Peer(uuid: "5FC4BDB3-3269-4B54-85E8-376E58D2C986", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:BC0799A4-7E47-446E-BC6F-7D9DFC5701E5 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:13D1E1AC-66F1-4749-BFE1-2D82B6AC3D12 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:4F61844C-075A-49BC-ACFA-4CF243EFC76D:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "4F61844C-075A-49BC-ACFA-4CF243EFC76D", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57957
,2017-07-21 15:22:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"17LXKvwLU7FUeInG1qJkiwViHTSiOi1V","error":null,"portNumber":57957}'
,2017-07-21 15:22:57 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '17LXKvwLU7FUeInG1qJkiwViHTSiOi1V', error: 'null', listeningPort: '57957''
,ok 217 should be equal
ok 218 should be equal
ok 219 should be equal
,2017-07-21 15:22:57 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B884C051-2B35-4187-B508-14FE33F8367A (syncValue: zjfe1whfDQSG1D8APKXQ3u4clH5X1ZF0)'
,2017-07-21 15:22:57 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B884C051-2B35-4187-B508-14FE33F8367A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B8,84C051-2B35-4187-B508-14FE33F8367A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B884C051-2B35-4187-B508-14FE33F8367A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B884C051-2B35-4187-B508-14FE33F8367A:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BC0799A4-7E47-446E-BC6F-7D9DFC5701E5
,[ThaliCore] Session.session(_:peer:didChange:) peer:BC0799A4-7E47-446E-BC6F-7D9DFC5701E5 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B884C051-2B35-4187-B508-14FE33F8367A:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B884C051-2B35-4187-B508-14FE33F8367A:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "B884C051-2B35-4187-B508-14FE33F8367A", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57963
2017-07-21 15:23:00 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"zjfe1whfDQSG1D8APKXQ3u4clH5X1ZF0",,"error":null,"portNumber":57963}'
2017-07-21 15:23:00 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'zjfe1whfDQSG1D8APKXQ3u4clH5X1ZF0', error: 'null', listeningPort: '57963''
,ok 220 should be equal
ok 221 should be equal
ok 222 should be equal
# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-21 15:23:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 15:23:00 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:23:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:5FC4BDB3-3269-4B54-85E8-376E58D2C986
,2017-07-21 15:23:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:4F61844C-075A-49BC-ACFA-4CF243EFC76D
[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57957
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:4F61844C-075A-49BC-ACFA-4CF243EFC76D:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:4F61844C-075A-49BC-ACFA-4CF243EFC76D:0 state: connected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "4F61844C-075A-49BC-ACFA-4CF243EFC76D", generation: 0)
,[ThaliCore] BrowserManager.disconnect peer:B884C051-2B35-4187-B508-14FE33F8367A
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57963
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:B884C051-2B35-4187-B508-14FE33F8367A:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:13D1E1AC-66F1-4749-BFE1-2D82B6AC3D12 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "5FC4BDB3-3269-4B54-85E8-376E58D2C986", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:BC0799A4-7E47-446E-BC6F-7D9DFC5701E5
,[ThaliCore] Session.deinit peer:B884C051-2B35-4187-B508-14FE33F8367A:0
[ThaliCore] BrowserRelay.deinit
2017-07-21 15:23:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 15:23:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvai,labilityChanged registered to native'
2017-07-21 15:23:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:23:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 15:23:00 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 15:23:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 15:23:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 15:23:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-21 15:23:00 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"17LXKvwLU7FUeInG1qJkiwViHTSiOi1V","error":"Session disconnected","portNumber":null}'
2017-07-21 15:23:00 - DEBUG thaliMobileNativeWrapper: 'Received peer availabili,ty changed event with {"peerIdentifier":"4F61844C-075A-49BC-ACFA-4CF243EFC76D","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 15:23:00 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not bei,ng in started state'
2017-07-21 15:23:00 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"4F61844C-075A-49BC-ACFA-4CF243EFC76D","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 15:23:00 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:BC0799A4-7E47-446E-BC6F-7D9DFC5701E5
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:4F61844C-075A-49BC-ACFA-4CF243EFC76D:0
[ThaliCore] BrowserRelay.deinit
,# #startListeningForAdvertisements should fail if start not called
,ok 223 specific error should be returned
,# teardown
,ok 224 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:01 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:23:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:23:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:23:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 15:23:01 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 15:23:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 15:23:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 15:23:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 225 specific error should be returned
,# teardown
,ok 226 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:02 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 15:23:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:23:02 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 15:23:02 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-21 15:23:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'should be able to call #stopListeningForAdvertisements many times''
,# teardown
,ok 227 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:23:02 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 15:23:02 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startListeningForAdvertisements many times
,2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'listening 57967'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A6A884B1-FDFC-44E0-8D5A-BD8A9086F25E
,[ThaliCore] Browser.startListening
,2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 15:23:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 15:23:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 228 no errors
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 15:23:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 15:23:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 229 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 15:23:02 - INFO thaliMobile: 'Received state ({"d,iscoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:23:02 - INFO ,thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisi,ngStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 15:23:02 - DEBUG makeIntoCloseAllServer: 'closeAll called, ,on server'
ok 230 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 ,15:23:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryA,ctive":false,"advertisingActive":false}'
2017-07-21 15:23:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'listening 57968'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5989A9A1-56F9-4BF0-9361-0753090EC34E", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:5989A9A1-56F9-4BF0-9361-0753090EC34E
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 15:23:03 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 15:23:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 231 no errors
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5989A9A1-56F9-4BF0-9361-0753090EC34E", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:5989A9A1-56F9-4BF0-9361-0753090EC34E
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 15:23:03 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 15:23:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 232 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:5989A9A1-56F9-4BF0-9361-0753090EC34E
[ThaliCore] Advertiser.stopAdvertising() peerID:5989A9A1-56F9-4BF0-9361-0753090EC34E
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 15:23:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 233 must be stopped
[ThaliCore] BrowserManager.stopListenin,gForAdvertisements()
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'listening 57971'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 234 no errors
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 235 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 236 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can get the network status before starting
,ok 237 network status should have certain non-empty properties
,# teardown
,ok 238 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:04 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 15:23:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:23:04 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 15:23:04 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# error returned with bad router
,2017-07-21 15:23:04 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
ok 239 specific error expected
,# teardown
,ok 240 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:04 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 15:23:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 15:23:04 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are started when we call start
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'listening 57972'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D5E5964D-4800-4A8F-BA96-D809E98F78C0
[ThaliCore] Browser.st,artListening
2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 15:23:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:23:04 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8DA0C237-3EA4-4A50-BB5B-C909868E50BA", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,8DA0C237-3EA4-4A50-BB5B-C909868E50BA
2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 15:23:04 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:23:04 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 241 all connection succeed
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B884C051-2B35-4187-B508-14FE33F8367A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B884C051-2B35-4187-B508-14FE33F8367A", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4F61844C-075A-49BC-ACFA-4CF243EFC76D:0
2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdent,ifier":"B884C051-2B35-4187-B508-14FE33F8367A","generation":0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4F61844C-075A-49BC-ACFA-4CF243EFC76D", generation: 0)
2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"B884C051-2B35-4187-B508-14FE33F8367A","generation":0}'
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"4F61844C-075A-49BC-ACFA-4CF243EFC76D","generation":0}]'
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"4F61844C-075A-49BC-ACFA-4CF243EFC76D","generation":0}'
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B884C051-2B35-4187-B508-14FE33F8367A","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 15:23:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B884C051-2B35-4187-B508-14FE33F8367A","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"4F61844C-075A-49BC-ACFA-4CF243EFC76D","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 15:23:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4F61844C-075A-49BC-ACFA-4CF243EFC76D","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:8DA0C237-3EA4-4A50-BB5B-C909868E50BA
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 15:23:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:23:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 15:23:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 242 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# TCP Servers Manager should be null when we call start on iOS
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'listening 57975'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A05566FE-F1DF-4005-8CE0-ED1DA95806AA
[ThaliCore] Browser.startListening
2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 15:23:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:23:05 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6BA3F3FA-3087-411C-9D80-E637068F4286", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,6BA3F3FA-3087-411C-9D80-E637068F4286
2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 15:23:05 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:23:05 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 243 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B884C051-2B35-4187-B508-14FE33F8367A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B884C051-2B35-4187-B508-14FE33F8367A", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:4F61844C-075A-49BC-ACFA-4CF243EFC76D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4F61844C-075A-49BC-ACFA-4CF243EFC76D", generation: 0)
2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B884C051-2B35-4187-B508-14FE33F8367A","generation":0}]'
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"B884C051-2B35-4187-B508-14FE33F8367A","generation":0}'
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"4F61844C-075A-49BC-ACFA-4CF243EFC76D","generation":0}]'
2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"4F61844C-075A-49BC-ACFA-4CF243EFC76D","generation":0}'
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B884C051-2B35-4187-B508-14FE33F8367A","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"4F61844C-075A-49BC-ACFA-4CF243EFC76D","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:6BA3F3FA-3087-411C-9D80-E637068F4286
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 15:23:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 15:23:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 15:23:05 - DEBUG thaliMobileNativeW,rapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 15:23:05 - DEBUG makeIntoCloseA,llServer: 'closeAll called on server'
,ok 244 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:05 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:05 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are stopped when we call stop
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'listening 57977'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3B5FE0EF-7B91-400A-A4B1-E7ED61431B03
[ThaliCore] Browser.startListening
2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 15:23:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:23:05 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4383225F-4329-4C89-B332-111933558EC2", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:4383225F-4329-4C89-B332-111933558EC2
2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 15:23:05 - INFO thaliMobile: 'Received state ({"discoveryAct,ive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:23:05 - INFO thaliMobile:, 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:4383225F-4329-4C89-B332-111933558EC2
2017-07-21 15:23:05 - DEBUG thaliMobileNativeWra,pper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 15:23:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"li,s,tening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:23:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] ,BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:05 - ,INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 245 is stopped after calling stop
,ok 246 connection should fail after stopping
,# teardown
,ok 247 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:05 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is properly hooked up
,2017-07-21 15:23:05 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
,# teardown
,ok 248 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:05 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is return error if we get called on iOS
,ok 249 error description matches
,# teardown
,ok 250 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:06 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 15:23:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:23:06 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 15:23:06 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is properly hooked up
,2017-07-21 15:23:06 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 251 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is return error if we get called on iOS
,ok 252 error description matches
,# teardown
,ok 253 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:06 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 15:23:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:23:06 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure we actually call kill connections properly
,ok 254 IMPLEMENT ME!!!!!!
,# teardown
,ok 255 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:07 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 15:23:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:23:07 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 15:23:07 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-07-21 15:23:07 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 256 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:07 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:23:07 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 15:23:07 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-07-21 15:23:07 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 257 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:23:07 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 15:23:07 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-07-21 15:23:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 258 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:08 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:23:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:23:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 15:23:08 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 15:23:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 15:23:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 15:23:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-07-21 15:23:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 259 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:08 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:23:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:23:08 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 15:23:08 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 15:23:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 15:23:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 15:23:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 260 NOT IMPLEMENTED # SKIP
,# teardown
,ok 261 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:23:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:23:08 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 15:23:08 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 15:23:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 15:23:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 15:23:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure bad PSK connections fail
,2017-07-21 15:23:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 262 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:09 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-21 15:23:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:23:09 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 15:23:09 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peer changes handled from a queue
,2017-07-21 15:23:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 263 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:09 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-21 15:23:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:23:09 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 15:23:09 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-07-21 15:23:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 264 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 15:23:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:23:09 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 15:23:09 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-07-21 15:23:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 265 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:23:10 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 15:23:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'listening 57980'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F4EEC177-C214-4A80-A0BD-5D54BE20E81D
[ThaliCore] Browser.startListening
2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 15:23:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:23:10 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
ok 266 discoveryActive matches
ok 267 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonT,C,P: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 15:23:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkT,ype":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:23:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisemen,ts()
[ThaliCore] Browser.stopListening()
2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:10 - INFO thaliMobile: 'Filtered out discoveryAd,vertisingStateUpdate (was in stopped state).'
ok 268 discoveryActive matches
ok 269 advertisingActive matches
2017-07-21 15:23:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'listening 57981'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "22F6070A-9DD4-42B5-87A3-6B812C9C5426", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:22F6070A-9DD4-42B5-87A3-6B812C9C5426
2017-07-21 1,5:23:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 15:23:10 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 15:23:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 270 discoveryActive matches
,ok 271 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:22F6070A-9DD4-42B5-87A3-6B812C9C5426
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 272 discoveryActive matches
,ok 273 advertisingActive matches
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'listening 57983'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 274 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'listening 57984'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A4C65F48-2231-4ED8-91CB-7E66224AD2BE
[ThaliCore] Browser.st,artListening
2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 15:23:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:23:10 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E654FCCA-C321-4945-90A1-B8669EEFD8C6", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,E654FCCA-C321-4945-90A1-B8669EEFD8C6
2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 15:23:10 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:23:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B884C051-2B35-4187-B508-14FE33F8367A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B884C051-2B35-4187-B508-14FE33F8367A", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:4F61844C-075A-49BC-ACFA-4CF243EFC76D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4F61844C-075A-49BC-ACFA-4CF243EFC76D", generation: 0)
2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B884C051-2B35-4187-B508-14FE33F8367A","generation":0}]'
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"B884C051-2B35-4187-B508-14FE33F8367A","generation":0}'
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"4F61844C-075A-49BC-ACFA-4CF243EFC76D","generation":0}]'
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"4F61844C-075A-49BC-ACFA-4CF243EFC76D","generation":0}'
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B884C051-2B35-4187-B508-14FE33F8367A","peerAvailable":true,"generation":0,"portNumber":null}'
,ok 275 portNumber equal null
,2017-07-21 15:23:11 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"4F61844C-075A-49BC-ACFA-4CF243EFC76D","peerAvailable":true,"generation":0,"portNumber":null}'
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EA8A7B76-B267-42CD-A158-6F7EABA79077:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EA8A7B76-B267-42CD-A158-6F7EABA79077", generation: 0)
2017-07-21 15:23:12 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"EA8A7B76-B267-42CD-A158-6F7EABA79077","generation":0}]'
2017-07-21 15:23:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"EA8A7B76-B267-42CD-A158-6F7EABA79077","generation":0}'
,2017-07-21 15:23:12 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"EA8A7B76-B267-42CD-A158-6F7EABA79077","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 15:23:12 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"EA8A7B76-B267-42CD-A158-6F7EABA79077","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found pe,er:320DCC94-FF97-4760-9C97-FD4AA1A8CD8E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "320DCC94-FF97-4760-9C97-FD4AA1A8CD8E", generation: 0)
2017-07-21 15:23:12 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event fro,m native layer [{"peerAvailable":true,"peerIdentifier":"320DCC94-FF97-4760-9C97-FD4AA1A8CD8E","generation":0}]'
2017-07-21 15:23:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"3,2,0DCC94-FF97-4760-9C97-FD4AA1A8CD8E","generation":0}'
,2017-07-21 15:23:12 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"320DCC94-FF97-4760-9C97-FD4AA1A8CD8E","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 15:23:12 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"320DCC94-FF97-4760-9C97-FD4AA1A8CD8E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:E654FCCA-C321-4945-90A1-B8669EEFD8C6
2017-07-21 15:23:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-21 15:23:12 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:23:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
,2017-07-21 15:23:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-21 15:23:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 276 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdate,NonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:23:12 - DEBUG thali,MobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 15:23:12 - DEBUG ,t,haliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:23:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:23:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:23:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests between peers
,2017-07-21 15:23:12 - DEBUG CoordinatedClient: 'test was skipped, name: 'can do HTTP requests between peers''
,# teardown
,ok 277 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:12 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:23:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-21 15:23:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:23:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:23:12 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 15:23:12 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 15:23:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 15:23:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 15:23:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can still do HTTP requests between peers with coordinator
,2017-07-21 15:23:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'can still do HTTP requests between peers with coordinator''
,# teardown
,ok 278 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:13 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:23:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:23:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:23:13 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:23:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calls correct starts when network changes
,2017-07-21 15:23:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'calls correct starts when network changes''
,# teardown
,ok 279 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:13 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:23:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-21 15:23:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:23:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:23:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:23:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# test to coordinate connection cut
,# teardown
,ok 280 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:14 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:23:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 15:23:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:23:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:23:14 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 15:23:14 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 15:23:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 15:23:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 15:23:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests after connections are cut
,2017-07-21 15:23:14 - DEBUG thaliMobileNativeWrapper: 'listening 57986'
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9AC8F16C-04DD-440E-9786-F1E296C3BFF4
[ThaliCore] Browser.startListening
,2017-07-21 15:23:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 15:23:14 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:23:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "AB581EA5-29D9-4172-88A7-F007CDB0BF6E", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:AB581EA5-29D9-4172-88A7-F007CDB0BF6E
2017-07-21 1,5:23:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 15:23:14 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-21 15:23:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B884C051-2B35-4187-B508-14FE33F8367A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B884C051-2B35-4187-B508-14FE33F8367A", generation: 0)
2017-07-21 15:23:14 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B884C051-2B35-4187-B508-14FE33F8367A","generation":0}]'
2017-07-21 15:23:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"B884C051-2B35-4187-B508-14FE33F8367A","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4F61844C-075A-49BC-ACFA-4CF243EFC76D:0
[ThaliCore] BrowserMana,ger.foundPeerHandler peer:Peer(uuid: "4F61844C-075A-49BC-ACFA-4CF243EFC76D", generation: 0)
2017-07-21 15:23:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B884C051-2B35-4187-B508-14FE33F8367A","peerAvai,l,able":true,"generation":0,"portNumber":null}'
,2017-07-21 15:23:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"B884C051-2B35-4187-B508-14FE33F8367A","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 15:23:14 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B884C051-2B35-4187-B508-14FE33F8367A (syncValue: LsVT7itp9Bzo3JiW75tS1nBF2zwKx7da)'
,2017-07-21 15:23:14 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B884C051-2B35-4187-B508-14FE33F8367A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B884C051-2B35-4187-B508-14FE33F8367A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B884C051-2B35-4187-B508-14FE33F8367A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 15:23:14 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"4F61844C-075A-49BC-ACFA-4CF243EFC76D","generation":0}]'
,2017-07-21 15:23:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"4F61844C-075A-49BC-ACFA-4CF243EFC76D","generation":0}'
,2017-07-21 15:23:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"4F61844C-075A-49BC-ACFA-4CF243EFC76D","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 15:23:14 - DEBUG thaliMobileNativeT,estUtils: 'We got a peer {"peerIdentifier":"4F61844C-075A-49BC-ACFA-4CF243EFC76D","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:186D2D79-0D19-4D5A-BBBA-6C8566980B6E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "186D2D79-0D19-4D5A-BBBA-6C8566980B6E", generation: 0)
2017-07-21 15:23:15 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"186D2D79-0D19-4D5A-BBBA-6C8566980B6E","generation":0}]'
2017-07-21 15:23:15 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"186D2D79-0D19-4D5A-BBBA-6C8566980B6E","generation":0}'
,2017-07-21 15:23:15 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"186D2D79-0D19-4D5A-BBBA-6C8566980B6E","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 15:23:15 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"186D2D79-0D19-4D5A-BBBA-6C8566980B6E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-21 15:23:15 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"186D2D79-0D19-4D5A-BBBA-6C8566980B6E","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:AB581EA5-29D9-4172-88A7-F007CDB0BF6E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "AB581EA5-29D9-4172-88A7-F007CDB0BF6E", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5C453656-3299-4A28-98BE-D7BAD2ED7E26:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5C453656-3299-4A28-98BE-D7BAD2ED7E26", generation: 0)
2017-07-21 15:23:15 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5C453656-3299-4A28-98BE-D7BAD2ED7E26","generation":0}]'
2017-07-21 15:23:15 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"5C453656-3299-4A28-98BE-D7BAD2ED7E26","generation":0}'
,2017-07-21 15:23:15 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5C453656-3299-4A28-98BE-D7BAD2ED7E26","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 15:23:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5C453656-3299-4A28-98BE-D7BAD2ED7E26","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 15:23:15 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"5C453656-3299-4A28-98BE-D7BAD2ED7E26","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B884C051-2B35-4187-B508-14FE33F8367A:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B884C051-2B35-4187-B508-14FE33F8367A", generation: 0)
,2017-07-21 15:23:15 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"B884C051-2B35-4187-B508-14FE33F8367A","generation":0}]'
,2017-07-21 15:23:15 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"B884C051-2B35-4187-B508-14FE33F8367A","generation":0}'
,2017-07-21 15:23:15 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"B884C051-2B35-4187-B508-14FE33F8367A","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-21 15:23:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B884C051-2B35-4187-B508-14FE33F8367A","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:B884C051-2B35-4187-B508-14FE33F8367A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B8,84C051-2B35-4187-B508-14FE33F8367A:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "B884C051-2B35-4187-B508-14FE33F8367A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,884C051-2B35-4187-B508-14FE33F8367A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B884C051-2B35-4187-B508-14FE33F8367A", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 15:23:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"LsVT7itp9Bzo3JiW75tS1nBF2zwKx7da","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 15:23:17 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'LsVT7itp9Bzo3JiW75tS1nBF2zwKx7da', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 15:23:17 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"B884C051-2B35-4187-B508-14FE33F8367A","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 15:23:17 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed ,event with {"peerIdentifier":"B884C051-2B35-4187-B508-14FE33F8367A","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 15:23:17 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"B884C051-2B35-4187-B508-14FE33F8367A","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-21 15:23:17 - DEBUG thali,MobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B884C051-2B35-4187-B508-14FE33F8367A","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-21 15:23:17 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peer,Identifier":"B884C051-2B35-4187-B508-14FE33F8367A","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] BrowserManager.disconnect peer:B884C051-2B35-4187-B508-14FE33F8367A
2017-07-21 15:23:17 - ERROR thaliMobileNativeTestUtils: 'Fatal co,nnect error: 'Peer is unavailable''
2017-07-21 15:23:17 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4F61844C-075A-49BC-ACFA-4CF243EFC76D (syncValue: EOSrSUB3FObZaL3bk0k3q6E2SFuyzEjw)'
2017-07-21 15:23:17 - DEBUG thaliMobileNativeTestUt,i,ls: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4F61844C-075A-49BC-ACFA-4CF243EFC76D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:s,essionNotConnected:) Peer(uuid: "4F61844C-075A-49BC-ACFA-4CF243EFC76D", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4F61844C-075A-49BC-ACFA-4CF243EFC76D:0
[ThaliCore] BrowserRelay.init(session:generation:creat,eVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B884C051-2B35-4187-B508-14FE33F8367A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:4F61844C-075A-49BC-ACFA-4CF243EFC76D:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "4F61844C-075A-49BC-ACFA-4CF243EFC76D", generation: 0)
2017-07-21 15:23:19 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"4F61844C-075A-49BC-ACFA-4CF243EFC76D","generation":0}]'
2017-07-21 15:23:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"4F61844C-075A-49BC-ACFA-4CF243EFC76D","generation":0}'
,2017-07-21 15:23:19 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"4F61844C-075A-49BC-ACFA-4CF243EFC76D","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-21 15:23:19 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"4F61844C-075A-49BC-ACFA-4CF243EFC76D","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:4F61844C-075A-49BC-ACFA-4CF243EFC76D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4F,61844C-075A-49BC-ACFA-4CF243EFC76D:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "4F61844C-075A-49BC-ACFA-4CF243EFC76D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,F61844C-075A-49BC-ACFA-4CF243EFC76D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4F61844C-075A-49BC-ACFA-4CF243EFC76D", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 15:23:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"EOSrSUB3FObZaL3bk0k3q6E2SFuyzEjw","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 15:23:19 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'EOSrSUB3FObZaL3bk0k3q6E2SFuyzEjw', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 15:23:19 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"4F61844C-075A-49BC-ACFA-4CF243EFC76D","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 15:23:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed ,event with {"peerIdentifier":"4F61844C-075A-49BC-ACFA-4CF243EFC76D","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 15:23:19 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"4F61844C-075A-49BC-ACFA-4CF243EFC76D","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-21 15:23:19 - DEBUG thali,MobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"4F61844C-075A-49BC-ACFA-4CF243EFC76D","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-21 15:23:19 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peer,Identifier":"4F61844C-075A-49BC-ACFA-4CF243EFC76D","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] BrowserManager.disconnect peer:4F61844C-075A-49BC-ACFA-4CF243EFC76D
2017-07-21 15:23:19 - ERROR thaliMobileNativeTestUtils: 'Fatal co,nnect error: 'Peer is unavailable''
2017-07-21 15:23:19 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 186D2D79-0D19-4D5A-BBBA-6C8566980B6E (syncValue: 6LbBpduI3OWg5zoQJV0OE700PA3wD7s1)'
2017-07-21 15:23:19 - DEBUG thaliMobileNativeTestUt,i,ls: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "186D2D79-0D19-4D5A-BBBA-6C8566980B6E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "186D2D79-0D19-4D5A-BBBA-6C8566980B6E", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:186D2D79-0D19-4D5A-BBBA-6C8566980B6E:0
[ThaliCore] BrowserRelay.init(session:generation:creat,eVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4F61844C-075A-49BC-ACFA-4CF243EFC76D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:186D2D79-0D19-4D5A-BBBA-6C8566980B6E:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:186D2D79-0D19-4D5A-BBBA-6C8566980B6E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:186D2D79-0D19-4D5A-BBBA-6C8566980B6E:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "186D2D79-0D19-4D5A-BBBA-6C8566980B6E", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57994
2017-07-21 15:23:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6LbBpduI3OWg5zoQJV0OE700PA3wD7s1",,"error":null,"portNumber":57994}'
2017-07-21 15:23:22 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '6LbBpduI3OWg5zoQJV0OE700PA3wD7s1', error: 'null', listeningPort: '57994''
,2017-07-21 15:23:22 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:186D2D79-0D19-4D5A-BBBA-6C8566980B6E:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:186D2D79-0D19-4D5A-BBBA-6C8566980B6E:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [5, 6, 15]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 15:23:23 - DEBUG testUtils: 'Got response data'
2017-07-21 15:23:23 - DEBUG testUtils: 'Got end'
ok 281 response body should match testData
ok 282 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:AB581EA5-29D9-4172-88A7-F007CDB0BF6E
2017-07-21 15:23:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-21 15:23:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:23:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
,2017-07-21 15:23:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-21 15:23:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 283 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdate,NonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:23:28 - DEBUG thali,MobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.d,i,sconnect peer:186D2D79-0D19-4D5A-BBBA-6C8566980B6E
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57994
[ThaliCore] VirtualSocket.closeStreams() vsID:15
[ThaliCore] T,CPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] Bro,wserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket exited RunLoop vsID:15
[ThaliCore] Session.disconnect() peer:186D2D79-0D19-4D5A-BBBA-6C8566980B6E:0
[ThaliCo,re] VirtualSocket.closeStreams() vsID:15
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:15 [5, 6]
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.deinit peer:186D2D79-0D19-4D5A-,BBBA-6C8566980B6E:0
[ThaliCore] BrowserRelay.deinit
2017-07-21 15:23:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:23:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:23:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:23:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# will fail bad PSK connection between peers
,ok 284 FIX ME, PLEASE!!!
,# teardown
,ok 285 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:23:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:23:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:23:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:23:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We provide notification when a listener dies and we recreate it
,2017-07-21 15:23:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'We provide notification when a listener dies and we recreate it''
,# teardown
,ok 286 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:29 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:23:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-21 15:23:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:23:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:23:29 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 15:23:29 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 15:23:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 15:23:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 15:23:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated
,2017-07-21 15:23:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''
,# teardown
,ok 287 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:23:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:23:30 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 15:23:30 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 15:23:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 15:23:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 15:23:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,ok 288 ThaliMobile should be stopped
,# #startListeningForAdvertisements should fail if start not called
,ok 289 specific error should be returned
,# teardown
,2017-07-21 15:23:30 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"EA8A7B76-B267-42CD-A158-6F7EABA79077","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21, 15:23:30 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"320DCC94-FF97-4760-9C97-FD4AA1A8CD8E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21 15:23:30 ,- DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"186D2D79-0D19-4D5A-BBBA-6C8566980B6E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21 15:23:30 - DEBUG th,aliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5C453656-3299-4A28-98BE-D7BAD2ED7E26","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 290 error should be null
,ok 291 error should be null
,# setup
,ok 292 ThaliMobile should be stopped
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 293 specific error should be returned
,# teardown
,ok 294 error should be null
ok 295 error should be null
,# setup
,ok 296 ThaliMobile should be stopped
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-21 15:23:31 - DEBUG thaliMobileNativeWrapper: 'listening 57996'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"ad,vertisingActive":false}'
ok 297 error should be null
ok 298 error should be null
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive,":false,"advertisingActive":false}'
ok 299 error should be null
ok 300 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:23:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 301 error should be null
,ok 302 error should be null
,# setup
,ok 303 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-07-21 15:23:32 - DEBUG thaliMobileNativeWrapper: 'listening 57997'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FE91C0B4-CBCA-4F38-B2B5-AF6B03947F24
,[ThaliCore] Browser.startListening
,2017-07-21 15:23:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 304 error should be null
,ok 305 error should be null
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-21 15:23:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 306 error should be null
,ok 307 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5C453656-3299-4A28-98BE-D7BAD2ED7E26:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5C453656-3299-4A28-98BE-D7BAD2ED7E26", generation: 0)
# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:186D2D79-0D19-4D5A-BBBA-6C8566980B6E:0
2017-07-21 15:23:32 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdent,ifier":"5C453656-3299-4A28-98BE-D7BAD2ED7E26","generation":0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "186D2D79-0D19-4D5A-BBBA-6C8566980B6E", generation: 0)
2017-07-21 15:23:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"5C453656-3299-4A28-98BE-D7BAD2ED7E26","generation":0}'
2017-07-21 15:23:32 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,,"peerIdentifier":"186D2D79-0D19-4D5A-BBBA-6C8566980B6E","generation":0}]'
2017-07-21 15:23:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"186D2D79-0D19-4D5A-BBBA-6C8566980B6E",",generation":0}'
,2017-07-21 15:23:32 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5C453656-3299-4A28-98BE-D7BAD2ED7E26","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 15:23:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5C453656-3299-4A28-98BE-D7BAD2ED7E26","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 15:23:32 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"186D2D79-0D19-4D5A-BBBA-6C8566980B6E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 15:23:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"186D2D79-0D19-4D5A-BBBA-6C8566980B6E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 15:23:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5C453656-3299-4A28-98BE-D7BAD2ED7E26","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 15:23:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"186D2D79-0D19-4D5A-BBBA-6C8566980B6E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 15:23:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-21 15:23:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 15:23:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-21 15:23:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 308 error should be null
,ok 309 error should be null
,# setup
,ok 310 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-21 15:23:32 - DEBUG thaliMobileNativeWrapper: 'listening 57998'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "260B2022-9C5C-4795-9382-B592B2D52C19", generation: 0)
[ThaliCore] Advertiser.startA,dvertising with peerID:260B2022-9C5C-4795-9382-B592B2D52C19
2017-07-21 15:23:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 311 error should be null
ok 312 error should, be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "260B2022-9C5C-4795-9382-B592B2D52C19", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:260B2022-9C5C-4795-9382-B592B2D52C19
20,17-07-21 15:23:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 313 error should be null
ok 314 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:260B2022-9C5C-4795-9382-B592B2D52C19
[ThaliCore] Advertiser.stopAdvertising() peerID:260B2022-9C5C-4795-9382-B592B2D52C19
2017-07-21 15:23:32 - DEBUG thaliMo,bileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:32 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 15:23:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 315 error should be null
ok 316 error should be null
,# setup
,ok 317 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-21 15:23:33 - DEBUG thaliMobileNativeWrapper: 'listening 58001'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:23:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingAct,ive":false}'
,ok 318 error should be null
,ok 319 error should be null
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 320 error should be null
,ok 321 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:23:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:33 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 15:23:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 322 error should be null
ok 323 error should be null
,# setup
,ok 324 ThaliMobile should be stopped
,# #start - Causing native or wifi to fail will cause a promise reject 
,2017-07-21 15:23:33 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
,ok 325 This should not cause wifi to fail
ok 326 native router should be bad
,# teardown
,ok 327 error should be null
ok 328 error should be null
,# setup
,ok 329 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-07-21 15:23:33 - DEBUG thaliMobileNativeWrapper: 'listening 58002'
ok 330 first call should succeed
ok 331 first call should succeed
ok 332 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:23:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:23:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 15:23:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 333 error should be null
ok 334 error should be null
,# setup
,ok 335 ThaliMobile should be stopped
,# #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)
,2017-07-21 15:23:33 - DEBUG CoordinatedClient: 'test was skipped, name: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''
,# teardown
,ok 336 error should be null
ok 337 error should be null
,# setup
,ok 338 ThaliMobile should be stopped
,# does not emit duplicate discoveryAdvertisingStateUpdate
,2017-07-21 15:23:34 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
,# teardown
,ok 339 error should be null
ok 340 error should be null
,# setup
,ok 341 ThaliMobile should be stopped
,# does not send duplicate availability changes
,2017-07-21 15:23:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3f2129fe-45e7-4017-9d9f-82dab716d0be","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 342 should be called once
,ok 343 should not have been called more than once
,# teardown
,2017-07-21 15:23:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"3f2129fe-45e7-4017-9d9f-82dab716d0be","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 344 error should be null
,ok 345 error should be null
,# setup
,ok 346 ThaliMobile should be stopped
,# can get the network status
,ok 347 network status should have certain non-empty properties
,# teardown
,ok 348 error should be null
ok 349 error should be null
,# setup
,ok 350 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (native)
,ok 351 we have not added peer to the cache yet
,2017-07-21 15:23:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"53f91374-0f34-475d-a4aa-0f6774d4e981","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 352 peer should be available
,ok 353 cache contains native peer
,2017-07-21 15:23:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"53f91374-0f34-475d-a4aa-0f6774d4e981","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 354 peer should be unavailable
,ok 355 peer has been removed from cache
,# teardown
,ok 356 error should be null
,ok 357 error should be null
,# setup
,ok 358 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 359 we have not added peer to the cache yet
2017-07-21 15:23:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"48a53839-a131-4358-b4e9-bcd6d413fad6","connectionType":"tcp","peerAvailable":true,"generation":0,",newAddressPort":false}'
ok 360 peer should be available
ok 361 cache contains wifi peer
2017-07-21 15:23:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"48a53839-a131-4358-b4e9-bcd6d413fad6","connectionType":,"tcp","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 362 peer should be unavailable
ok 363 peer has been removed from cache
,# teardown
,ok 364 error should be null
ok 365 error should be null
,# setup
,ok 366 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-07-21 15:23:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5580d0d3-1021-4a96-a66e-ebabf120498d","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 367 first peer is available
2017-07-21 15:23:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ac295c41-7e2d-4700-af37-267c9be8ec80","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":,false}'
ok 368 second peer is available
ok 369 first and second peers are different
,# teardown
,2017-07-21 15:23:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5580d0d3-1021-4a96-a66e-ebabf120498d","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21 15:23:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"ac295c41-7e2d-4700-af37-267c9be8ec80","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 370 error should be null
ok 371 error should be null
,# setup
,ok 372 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 373 should not be in cache at start
2017-07-21 15:23:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ae5b66b1-3b61-49ad-8fe8-00496cfd172d","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 374 peer is available
,# teardown
,2017-07-21 15:23:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"ae5b66b1-3b61-49ad-8fe8-00496cfd172d","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 375 error should be null
ok 376 error should be null
,# setup
,ok 377 ThaliMobile should be stopped
,# native available - peer with same port and different generation is cached (BLUETOOTH)
,2017-07-21 15:23:36 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with same port and different generation is cached (BLUETOOTH)''
,# teardown
,ok 378 error should be null
ok 379 error should be null
,# setup
,ok 380 ThaliMobile should be stopped
,# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
,2017-07-21 15:23:36 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''
,# teardown
,ok 381 error should be null
ok 382 error should be null
,# setup
,ok 383 ThaliMobile should be stopped
,# native available - peer with greater generation is cached (MPCF)
,2017-07-21 15:23:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"370a1719-b000-4886-b6fa-cb67c5205c20","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
ok 384 peer should be ,available
,2017-07-21 15:23:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"370a1719-b000-4886-b6fa-cb67c5205c20","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 385 peer should be available
ok 386 should store correct generation
,# teardown
,2017-07-21 15:23:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"370a1719-b000-4886-b6fa-cb67c5205c20","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 387 error should be null
ok 388 error should be null
,# setup
,ok 389 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-07-21 15:23:37 - DEBUG thaliMobileNativeWrapper: 'listening 58003'
2017-07-21 15:23:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"afb98073-037d-4488-ab89-96d2b95d7300","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
ok 390 discovered correct peer
ok 391 got correct generation
,2017-07-21 15:23:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"afb98073-037d-4488-ab89-96d2b95d7300","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 392 discovered correct peer
ok 393 got correct generation
,# teardown
,2017-07-21 15:23:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"afb98073-037d-4488-ab89-96d2b95d7300","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-21 15:23:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpd,ateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 15:23:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server',
,ok 394 error should be null
ok 395 error should be null
,# setup
,ok 396 ThaliMobile should be stopped
,# native unavailable - new peer is ignored
,2017-07-21 15:23:38 - DEBUG thaliMobileNativeWrapper: 'listening 58004'
,2017-07-21 15:23:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"79f055b3-0260-4c12-95b4-f038c60af8f8","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 397 discovered avai,lable peer
ok 398 peer is available
,# teardown
,2017-07-21 15:23:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"79f055b3-0260-4c12-95b4-f038c60af8f8","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-21 15:23:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:38 - INFO thaliMobile: 'Filtered out discoveryAdvert,isingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:38 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 15:23:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 399 error should be null
ok 400 error should be null
,# setup
,ok 401 ThaliMobile should be stopped
,# native unavailable - cached peer is removed
,2017-07-21 15:23:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9c4b72ed-b287-4f20-96d5-dd3b620eae16","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 402 peer should be available
2017-07-21 15:23:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9c4b72ed-b287-4f20-96d5-dd3b620eae16","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 403 peer should be unavailable
ok 404 should be removed from cache
,# teardown
,ok 405 error should be null
ok 406 error should be null
,# setup
,ok 407 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-07-21 15:23:38 - DEBUG thaliMobileNativeWrapper: 'listening 58005'
2017-07-21 15:23:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"02e6351e-0426-4fdd-9815-565d1f046980","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 408 first peer is expected to be available
2017-07-21 15:23:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1afb865e-9020-443e-a54c-8a9ef8f87970","connectio,nType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 409 second peer is expected to be available
2017-07-21 15:23:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1afb865e-9020-,443e-a54c-8a9ef8f87970","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 410 peer became unavailable
ok 411 it was wifi peer
,2017-07-21 15:23:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1afb865e-9020-443e-a54c-8a9ef8f87970","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 412 we found peer ag,ain
ok 413 it was wifi peer
2017-07-21 15:23:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1afb865e-9020-443e-a54c-8a9ef8f87970","connectionType":"tcp","peerAvailable":false,"generation":null,"newAd,dressPort":null}'
ok 414 peer became unavailable
ok 415 it was wifi peer
,# teardown
,2017-07-21 15:23:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"02e6351e-0426-4fdd-9815-565d1f046980","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-21 15:23:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpd,ateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 15:23:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 416 error should be null
ok 417 error should be null
,# setup
,ok 418 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
,2017-07-21 15:23:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''
,# teardown
,ok 419 error should be null
ok 420 error should be null
,# setup
,ok 421 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
,2017-07-21 15:23:39 - DEBUG thaliMobileNativeWrapper: 'listening 58006'
2017-07-21 15:23:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c57966b0-9cfa-4919-9315-6411af4fc922","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 422 first peer is expected to be available
2017-07-21 15:23:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"31c68801-7369-4ca3-bcb1-1a9fe9cbfea1","connectio,nType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 423 second peer is expected to be available
,2017-07-21 15:23:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c57966b0-9cfa-4919-9315-6411af4fc922","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 424 pee,r became unavailable
2017-07-21 15:23:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"31c68801-7369-4ca3-bcb1-1a9fe9cbfea1","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPor,t":null}'
ok 425 peer became unavailable
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:23:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:39 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:39 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 15:23:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 426 error should be null
,ok 427 error should be null
,# setup
,ok 428 ThaliMobile should be stopped
,# multiconnect failure - new peer is ignored (MPCF)
,2017-07-21 15:23:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
,# teardown
,ok 429 error should be null
ok 430 error should be null
,# setup
,ok 431 ThaliMobile should be stopped
,# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
,2017-07-21 15:23:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
,# teardown
,ok 432 error should be null
ok 433 error should be null
,# setup
,ok 434 ThaliMobile should be stopped
,# newAddressPort field (TCP_NATIVE)
,2017-07-21 15:23:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"06c33a17-6092-4909-9ee9-1df0b80e560d","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 435 peer discovered first time does not have new address
2017-07-21 15:23:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"06c33a17-6092-4909-9ee9-1df0b80e560d","connectionType":"tcp","peerAvailable":true,"ge,neration":20,"newAddressPort":false}'
ok 436 address has not been changed
2017-07-21 15:23:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"06c33a17-6092-4909-9ee9-1df0b80e560d","connectionType":"tcp","peerAvai,lable":true,"generation":20,"newAddressPort":true}'
ok 437 new port handled correctly
2017-07-21 15:23:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"06c33a17-6092-4909-9ee9-1df0b80e560d","connectionType":"tc,p","peerAvailable":true,"generation":20,"newAddressPort":true}'
ok 438 new host handled correctly
2017-07-21 15:23:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"06c33a17-6092-4909-9ee9-1df0b80e560d","connec,t,ionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}'
ok 439 newAddressPort is null for unavailable peers
,# teardown
,ok 440 error should be null
ok 441 error should be null
,# setup
,ok 442 ThaliMobile should be stopped
,# newAddressPort field (BLUETOOTH)
,2017-07-21 15:23:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort field (BLUETOOTH)''
,# teardown
,ok 443 error should be null
ok 444 error should be null
,# setup
,ok 445 ThaliMobile should be stopped
,# newAddressPort field (MPCF)
,ok 446 NOT IMPLEMENTED # SKIP
,# teardown
,ok 447 error should be null
ok 448 error should be null
,# setup
,ok 449 ThaliMobile should be stopped
,# newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)
,2017-07-21 15:23:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''
,# teardown
,ok 450 error should be null
,ok 451 error should be null
,# setup
,ok 452 ThaliMobile should be stopped
,# #getPeerHostInfo - error when peer has not been discovered yet
,ok 453 should be equal
,# teardown
,ok 454 error should be null
ok 455 error should be null
,# setup
,ok 456 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)
,2017-07-21 15:23:41 - DEBUG CoordinatedClient: 'test was skipped, name: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''
,# teardown
,ok 457 error should be null
ok 458 error should be null
,# setup
,ok 459 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)
,2017-07-21 15:23:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 460 contains expected properties
ok 461 the same ho,stAddress
ok 462 the same portNumber
,# teardown
,2017-07-21 15:23:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 463 error should be null
ok 464 error should be null
,# setup
,ok 465 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached wifi peer
,2017-07-21 15:23:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 466 contains expected properties
ok 467 the same hostAddress
ok 468 the same portNumber
,# teardown
,2017-07-21 15:23:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 469 error should be null
ok 470 error should be null
,# setup
,ok 471 ThaliMobile should be stopped
,# #disconnect fails on wifi peers
,2017-07-21 15:23:42 - DEBUG thaliMobileNativeWrapper: 'listening 58007'
2017-07-21 15:23:42 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f150143e-fcab-44be-821b-94b844d4d1d4","connectionType":"tcp","peerAvailab,le":true,"generation":0,"newAddressPort":false}'
ok 472 Got specific error message
,# teardown
,2017-07-21 15:23:42 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"f150143e-fcab-44be-821b-94b844d4d1d4","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:23:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:42 - INFO thaliMobile: 'Filtered out discoveryAdverti,singStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:42 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 15:23:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 473 error should be null
ok 474 error should be null
,# setup
,ok 475 ThaliMobile should be stopped
,# #disconnect delegates native peers to the native wrapper
,2017-07-21 15:23:42 - DEBUG thaliMobileNativeWrapper: 'listening 58008'
2017-07-21 15:23:42 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b2990863-3afc-4c3b-998d-3f717a166229","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
[ThaliCore] BrowserManager.disconnect peer:b2990863-3afc-4c3b-998d-3f717a166229
,ok 476 native wrapper `disconnect` called once
ok 477 native wrapper `disconnect` called with peer data
,# teardown
,2017-07-21 15:23:42 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"b2990863-3afc-4c3b-998d-3f717a166229","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-21 15:23:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:42 - INFO thaliMobile: 'Filtered out discoveryAdvert,isingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:42 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 15:23:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 478 error should be null
,ok 479 error should be null
,# setup
,ok 480 ThaliMobile should be stopped
,# network changes emitted correctly
,2017-07-21 15:23:42 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes emitted correctly''
,# teardown
,ok 481 error should be null
ok 482 error should be null
,# setup
,ok 483 ThaliMobile should be stopped
,# network changes not emitted in started state
,2017-07-21 15:23:42 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in started state''
,# teardown
,ok 484 error should be null
ok 485 error should be null
,# setup
,ok 486 ThaliMobile should be stopped
,# network changes not emitted in stopped state
,2017-07-21 15:23:43 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in stopped state''
,# teardown
,ok 487 error should be null
ok 488 error should be null
,# setup
,ok 489 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on Android
,2017-07-21 15:23:43 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on Android''
,# teardown
,ok 490 error should be null
ok 491 error should be null
,# setup
,ok 492 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on iOS
,2017-07-21 15:23:43 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on iOS''
,# teardown
,ok 493 error should be null
ok 494 error should be null
,# setup
,ok 495 ThaliMobile should be stopped
,# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
,2017-07-21 15:23:43 - DEBUG CoordinatedClient: 'test was skipped, name: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''
,# teardown
,ok 496 error should be null
ok 497 error should be null
,# setup
,ok 498 ThaliMobile should be stopped
,# does not fire duplicate events after peer listener recreation
,2017-07-21 15:23:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not fire duplicate events after peer listener recreation''
,# teardown
,ok 499 error should be null
ok 500 error should be null
,# setup
,ok 501 ThaliMobile should be stopped
,# #stop should change peers
,2017-07-21 15:23:44 - DEBUG thaliMobileNativeWrapper: 'listening 58009'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:679174E3-95EC-49CB-9513-CF7FB9F15B12
[ThaliCore] Browser.startListening
2017-07-21 15:23:44 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 15:23:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"52ac54dd-e32e-4aad-9182-814f336f47bb","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 502 Peer availabilities has one entry for our connection type
,2017-07-21 15:23:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b47abe87-dd8e-4b75-8d73-e749d593c56c","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:186D2D79-0D19-4D5A-BBBA-6C8566980B6E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "186D2D79-0D19-4D5A-BBBA-6C8566980B6E", generation: 0)
ok 503 Peer availabilities ha,s one entry for our connection type
2017-07-21 15:23:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"52ac54dd-e32e-4aad-9182-814f336f47bb","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 15:23:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"b47abe87-dd8e-4b75-8d73-e749d593c56c","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 15:23:44 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,1,11],"networkType":"BOTH"}})'
,2017-07-21 15:23:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 15:23:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 15:23:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:44 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"186D2D79-0D19-4D5A-BBBA-6C8566980B6E","generation":0}]'
,2017-07-21 15:23:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"186D2D79-0D19-4D5A-BBBA-6C8566980B6E","generation":0}'
,2017-07-21 15:23:44 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,ok 504 No peers
,ok 505 No peers
,ok 506 No peers
,# teardown
,ok 507 error should be null
,ok 508 error should be null
,# setup
,ok 509 ThaliMobile should be stopped
,# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
,2017-07-21 15:23:45 - DEBUG thaliMobileNativeWrapper: 'listening 58010'
2017-07-21 15:23:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b430fcff-2da8-4840-a1ca-5ae26527958b","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 510 1
ok 511 2
,2017-07-21 15:23:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9fe7cd87-f8e9-4991-b9ae-c0f73e5bd0de","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-07-21 15:23:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"b430fcff-2da8-4840-a1ca-5ae26527958b","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21, 15:23:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9fe7cd87-f8e9-4991-b9ae-c0f73e5bd0de","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:45 - INFO thaliMobile: 'Fi,ltered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 15:23:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 512 error should be null
,ok 513 error should be null
,# setup
,ok 514 ThaliMobile should be stopped
,# peer should be found once after listening and discovery started
,2017-07-21 15:23:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer should be found once after listening and discovery started''
,# teardown
,ok 515 error should be null
ok 516 error should be null
,# setup
,ok 517 ThaliMobile should be stopped
,# can get data from all participants
,2017-07-21 15:23:46 - DEBUG thaliMobileNativeWrapper: 'listening 58011'
ok 518 error should be null
ok 519 error should be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7288E5EA-A0B8-451F-BBDD-C5,15A1449811", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:7288E5EA-A0B8-451F-BBDD-C515A1449811
2017-07-21 15:23:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive,":true}'
ok 520 error should be null
ok 521 error should be null
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BBACF90A-F04A-4A13-84BF-DBAA1E5BD1D7
[ThaliCore] Browser.startLi,stening
2017-07-21 15:23:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,ok 522 error should be null
ok 523 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:186D2D79-0D19-4D5A-BBBA-6C8566980B6E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "186D2D79-0D19-4D5A-BBBA-6C8566980B6E", generation: 0)
,2017-07-21 15:23:46 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"186D2D79-0D19-4D5A-BBBA-6C8566980B6E","generation":0}]'
2017-07-21 15:23:46 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"186D2D79-0D19-4D5A-BBBA-6C8566980B6E","generation":0}'
,2017-07-21 15:23:46 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"186D2D79-0D19-4D5A-BBBA-6C8566980B6E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 15:23:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"186D2D79-0D19-4D5A-BBBA-6C8566980B6E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 15:23:46 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 186D2D79-0D19-4D5A-BBBA-6C8566980B6E (syncValue: 0)'
,2017-07-21 15:23:46 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "186D2D79-0D19-4D5A-BBBA-6C8566980B6E", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "186D2D79-0D19-4D5A-BBBA-6C8566980B6E", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:186D2D79-0D19-4D5A-BBBA-6C8566980B6E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:044D28D1-9079-492D-8757-2C17B15E076F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "044D28D1-9079-492D-8757-2C17B15E076F", generation: 0)
2017-07-21 15:23:47 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"044D28D1-9079-492D-8757-2C17B15E076F","generation":0}]'
2017-07-21 15:23:47 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"044D28D1-9079-492D-8757-2C17B15E076F","generation":0}'
,2017-07-21 15:23:47 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"044D28D1-9079-492D-8757-2C17B15E076F","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 15:23:47 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"044D28D1-9079-492D-8757-2C17B15E076F","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:82D3C558-DEEF-4A44-BF81-75C7818BF561:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "82D3C558-DEEF-4A44-BF81-75C7818BF561", generation: 0)
2017-07-21 15:23:47 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"82D3C558-DEEF-4A44-BF81-75C7818BF561","generation":0}]'
2017-07-21 15:23:47 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"82D3C558-DEEF-4A44-BF81-75C7818BF561","generation":0}'
,2017-07-21 15:23:47 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"82D3C558-DEEF-4A44-BF81-75C7818BF561","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 15:23:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"82D3C558-DEEF-4A44-BF81-75C7818BF561","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7288E5EA-A0B8-451F-BBDD-C515A1449811:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7288E5EA-A0B8-451F-BBDD-C515A1449811", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:186D2D79-0D19-4D5A-BBBA-6C8566980B6E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:18,6D2D79-0D19-4D5A-BBBA-6C8566980B6E:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "186D2D79-0D19-4D5A-BBBA-6C8566980B6E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,86D2D79-0D19-4D5A-BBBA-6C8566980B6E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "186D2D79-0D19-4D5A-BBBA-6C8566980B6E", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:186D2D79-0D19-4D5A-BBBA-6C8566980B6E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:186D2D79-0D19-4D5A-BBBA-6C8566980B6E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:186D2D79-0D19-4D5A-BBBA-6C8566980B6E:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "186D2D79-0D19-4D5A-BBBA-6C8566980B6E", generation: 0)
2017-07-21 15:23:49 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"186D2D79-0D19-4D5A-BBBA-6C8566980B6E","generation":0}]'
2017-07-21 15:23:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"186D2D79-0D19-4D5A-BBBA-6C8566980B6E","generation":0}'
,2017-07-21 15:23:49 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"186D2D79-0D19-4D5A-BBBA-6C8566980B6E","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-21 15:23:49 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"186D2D79-0D19-4D5A-BBBA-6C8566980B6E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:186D2D79-0D19-4D5A-BBBA-6C8566980B6E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:18,6D2D79-0D19-4D5A-BBBA-6C8566980B6E:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "186D2D79-0D19-4D5A-BBBA-6C8566980B6E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,86D2D79-0D19-4D5A-BBBA-6C8566980B6E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "186D2D79-0D19-4D5A-BBBA-6C8566980B6E", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 15:23:51 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":"Peer is unavailable","portNumber":null}'
2017-07-2,1 15:23:51 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"186D2D79-0D19-4D5A-BBBA-6C8566980B6E","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 15:23:51 - DEBUG thaliMobileNativeWr,apper: 'Received peer availability changed event with {"peerIdentifier":"186D2D79-0D19-4D5A-BBBA-6C8566980B6E","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 15:23:51 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 044D28D1-9079-492D-8757-2C17B15E076F (syncValue: 1)'
2017-07-21 15:23:51 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "044D28D1-9079-492D-8757-2C17B15E076F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "044D28D1-9079-492D-8757-2C17B15E076F", ge,neration: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:044D28D1-9079-492D-8757-2C17B15E076F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnec,ted:stoppedListening:)
2017-07-21 15:23:51 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"186D2D79-0D19-4D5A-BBBA-6C8566980B6E","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-,2,1 15:23:51 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"186D2D79-0D19-4D5A-BBBA-6C8566980B6E","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] Session.deinit peer:186D2D79-0D19-4D5A-BBBA-6C8566980B6E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:044D28D1-9079-492D-8757-2C17B15E076F:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:277C36C6-434A-4F0B-944D-ACB584A4C2BE
[ThaliCore] Advertiser: session connected Peer(uuid: "7288E5EA-A0B8-451F-BBDD-C515A1449811", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:277C36C6-434A-4F0B-944D-ACB584A4C2BE state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:044D28D1-9079-492D-8757-2C17B15E076F:0
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D9F0D619-4A48-4FF4-B8DB-5D8EE532AD34
[ThaliCore] Advertiser: session connected Peer(uuid: "7288E5EA-A0B8-451F-BBDD-C515A1449811", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:D9F0D619-4A48-4FF4-B8DB-5D8EE532AD34 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:044D28D1-9079-492D-8757-2C17B15E076F:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "044D28D1-9079-492D-8757-2C17B15E076F", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:58019
2017-07-21 15:23:54 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":null,"portNumber":58019}'
,2017-07-21 15:23:54 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 82D3C558-DEEF-4A44-BF81-75C7818BF561 (syncValue: 2)'
2017-07-21 15:23:54 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "82D3C558-DEEF-4A44-BF81-75C7818BF561", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "82D3C558-DEEF-4A44-BF81-75C7818BF561", ge,neration: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:82D3C558-DEEF-4A44-BF81-75C7818BF561:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnec,ted:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:044D28D1-9079-492D-8757-2C17B15E076F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:044D28D1-9079-492D-8757-2C17B15E076F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [5, 6, 16]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 15:23:54 - DEBUG testUtils: 'Got response data'
,2017-07-21 15:23:54 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.session(_:peer:didChange:) peer:82D3C558-DEEF-4A44-BF81-75C7818BF561:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:277C36C6-434A-4F0B-944D-ACB584A4C2BE
,[ThaliCore] Session.session(_:peer:didChange:) peer:277C36C6-434A-4F0B-944D-ACB584A4C2BE state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:277C36C6-434A-4F0B-944D-ACB584A4C2BE
[ThaliCore] Session.startOutputStream(with:) peer:277C36C6-434A-4F0B-944D-ACB584A4C2BE
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,7 [5, 6, 16, 17]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D9F0D619-4A48-4FF4-B8DB-5D8EE532AD34
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:82D3C558-DEEF-4A44-BF81-75C7818BF561:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D9F0D619-4A48-4FF4-B8DB-5D8EE532AD34 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:82D3C558-DEEF-4A44-BF81-75C7818BF561:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "82D3C558-DEEF-4A44-BF81-75C7818BF561", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:58024
2017-07-21 15:23:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":null,"portNumber":58024,}'
,[ThaliCore] BrowserManager.disconnect peer:186D2D79-0D19-4D5A-BBBA-6C8566980B6E
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:82D3C558-DEEF-4A44-BF81-75C7818BF561:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:82D3C558-DEEF-4A44-BF81-75C7818BF561:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:18 [5, 6, 16, 17, 18]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D9F0D619-4A48-4FF4-B8DB-5D8EE532AD34
[ThaliCore] Session.startOutputStream(with:) peer:D9F0D619-4A48-4FF4-B8DB-5D8EE532AD34
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [5, 6, 16, 17, 18, 19]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-21 15:23:57 - DEBUG testUtils: 'Got response data'
,2017-07-21 15:23:57 - DEBUG testUtils: 'Got end'
,ok 524 received all uuids
,# teardown
,2017-07-21 15:23:57 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"044D28D1-9079-492D-8757-2C17B15E076F","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21, 15:23:57 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"82D3C558-DEEF-4A44-BF81-75C7818BF561","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Advertis,erManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:7288E5EA-A0B8-451F-BBDD-C515A1449811
2017-07-21 15:23:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":fal,se}'
2017-07-21 15:23:57 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-21 15,:,23:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 15:23:57 - DEBUG thaliMobileNativeWrapper: 'disco,veryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 15:23:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:17
[ThaliCore] VirtualSocket.closeStreams() vsID:17
ok 525 error should be null
ok 526 error should be null
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:19
[ThaliCore] VirtualSocket.closeS,treams() vsID:19
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
# setup
[ThaliCore] VirtualSocket exited RunLoop vsID:17
[ThaliCore] VirtualSocket.deinit vsID:17 [5, 6, 16, 18, 19]
[ThaliCore] AdvertiserRelay.didCl,oseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:19
[ThaliCore] VirtualSocket.deinit vsID:19 [5, 6, 16, 18]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:18
[ThaliCore] VirtualSocket.closeStreams() vsID:18
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:18
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:18 [5, 6, 16]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:82D3C558-DEEF-4A44-BF81-75C7818BF561:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() po,rt:58024
[ThaliCore] Session.disconnect() peer:82D3C558-DEEF-4A44-BF81-75C7818BF561:0
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "82D3C558-DEEF-4A44-BF81-75C7818BF561", generation: 0)
[ThaliCore] TCPListener.socketDidDisc,onnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
2017-07-21 15:24:02 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":"Session disconnected","portNumber":null}'
2017-07-21 15:24:02 - DEBUG t,haliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"82D3C558-DEEF-4A44-BF81-75C7818BF561","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 15:24:02 - DEBUG thaliMobileNativeWrapper: 'Filtered ou,t nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-21 15:24:02 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"82D3C558-DEEF-4A44-BF81-75C7818BF561","peerAvailable":true,"gen,eration":0,"portNumber":null,"recreated":true}'
2017-07-21 15:24:02 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:82D3C558-DEEF-4A44-BF81-75C7818BF561:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:16
[ThaliCore] VirtualSocket.closeStreams() vsID:16
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:16
[Th,aliCore] VirtualSocket.deinit vsID:16 [5, 6]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconne,ctHandler
,ok 527 ThaliMobile should be stopped
,# test for data corruption
,2017-07-21 15:24:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'test for data corruption''
,# teardown
,ok 528 error should be null
,ok 529 error should be null
,# setup
,# #testThaliPeerAction - test getters
,ok 530 getPeerIdentifier
ok 531 getConnectionType
ok 532 getActionType
,ok 533 getActionState
ok 534 getPskIdentity
ok 535 getPskKey
,# teardown
,# setup
,# #testThaliPeerAction - start and kill
,ok 536 initial state
ok 537 after start
2017-07-21 15:24:09 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 538 after kill
,# teardown
,# setup
,# #testThaliPeerAction - double start
,ok 539 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - start after kill
,2017-07-21 15:24:09 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 540 clean kill
ok 541 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - make sure ids are unique
,ok 542 should not be equal
,# teardown
,# setup
,# #testThaliPeerAction - check that forever agent can be destroyed
,ok 543 forever agent should have it's own destroy method
,ok 544 agent's destroy should be called
ok 545 agent's destroy should not be called again
ok 546 agent is destroyed
,# teardown
,# setup
,# Test PeerDictionary basic functionality
,ok 547 Entry counter must be 1
,ok 548 Entry exists
,ok 549 Size must be 1
,ok 550 Entry counter must be 2
,ok 551 Entry exists
,ok 552 Size must be 2
,ok 553 Entry counter must be 1
,ok 554 Entry exists
,ok 555 Size must be 3
,ok 556 Entry counter must be 2
,ok 557 Entry exists
,ok 558 Size must be 4
,ok 559 Entry 1_1 should not be found
,ok 560 Entry 1_1 does not exist
,ok 561 Size must be 3
,ok 562 Entry 1_2 should not be found
,ok 563 Entry 1_2 does not exist
,ok 564 Size must be 2
,ok 565 should be equal
,ok 566 Entry 2_1 should not be found
,ok 567 Entry 2_2 should not be found
,ok 568 Entry 2_1 does not exist
,ok 569 Entry 2_2 does not exist
,ok 570 Size must be 0
,# teardown
,# setup
,# Test PeerDictionary with multiple entries.
,ok 571 Size must be100
,ok 572 Entries between 20 and MAXSIZE + 20 should exist
,ok 573 WAITING state entry should not be removed
,# teardown
,# setup
,# RESOLVED entries are removed before WAITING state entry.
,ok 574 Entries between 6 and MAXSIZE + 4 should exist
,ok 575 Size should be MAXSIZE
ok 576 Size should be MAXSIZE+6
,# teardown
,# setup
,# WAITING entries are removed before CONTROLLED_BY_POOL state entry.
,ok 577 WAITING state entry should not be removed
,ok 578 Waiting entries between 6 and MAXSIZE + 4 should exist
ok 579 Size should be MAXSIZE
,ok 580 entryCounter should be MAXSIZE+6
,# teardown
,# setup
,# When CONTROLLED_BY_POOL entry is removed and kill is called.
,ok 581 Kill should be called once
ok 582 Size should be MAXSIZE
,# teardown
,# setup
,# #ThaliPeerPoolDefault - single action
,ok 583 is an agent
ok 584 enqueue is fine
ok 585 Everything should be off the queue
,# teardown
,# setup
,# #ThaliPeerPoolDefault - multiple actions
,ok 586 is an agent
ok 587 first enqueue is fine
ok 588 is an agent
ok 589 second enqueue is fine
ok 590 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 591 Queue is empty
,# teardown
,# setup
,# #ThaliPeerPoolDefault - PSK Pool works
,ok 592 is an agent
ok 593 good enqueue
,ok 594 Identity should match
,2017-07-21 15:24:14 - DEBUG testUtils: 'Got response data'
,2017-07-21 15:24:14 - DEBUG testUtils: 'Got end'
,ok 595 Got expected response
,ok 596 Got psk call back
,# teardown
,2017-07-21 15:24:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #ThaliPeerPoolDefault - stop
,ok 597 is an agent
,ok 598 enqueue worked
,ok 599 is an agent
,ok 600 enqueue 2 worked
,ok 601 enqueue is not available when stopped
,ok 602 start action is killed
,ok 603 killed action is still killed
,ok 604 enqueued action when stopped is killed
,ok 605 inQueue is empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that start verifies queue length
,ok 606 good start
ok 607 good enqueue
ok 608 queue is not empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - bad enqueues
,ok 609 null arg
,ok 610 wrong arg type
ok 611 wrong arg type
,# teardown
,# setup
,# #ThaliPeerPoolInterface - do not allow same object type
,ok 612 good enqueue
ok 613 already enqueued
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
,ok 614 good enqueue
ok 615 2nd good enqueue
ok 616 we are in the pool
ok 617 We are out of the pool
ok 618 Action was killed
ok 619 The original kill was called too
ok 620 second item is still in queue
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
,ok 621 good enqueue
ok 622 first kill
ok 623 second NOOP kill
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that stop removes all actions
,ok 624 1st good enqueue
,ok 625 2nd good enqueue
,ok 626 1st action is in the pool
,ok 627 2nd action is in the pool
,ok 628 1st action is out of the pool
,ok 629 2st action is out of the pool
,ok 630 pool is empty
,# teardown
,# setup
,# We reject unrecognized connection type
,2017-07-21 15:24:17 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 631 Got right error
,ok 632 Start should not be called
,ok 633 Kill should have been called at least once
,# teardown
,# setup
,# We reject unrecognized action type
,2017-07-21 15:24:18 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-21 15:24:18 - ERROR thaliPeerPoolOneAtATime: 'Got unsupported action type: blah'
,ok 634 Got right error
,ok 635 Start should not be called
,ok 636 Kill should have been called at least once
,# teardown
,# setup
,# One action on bluetooth
,2017-07-21 15:24:18 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 637 Got null
,2017-07-21 15:24:18 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
ok 638 is an agent
,2017-07-21 15:24:18 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 639 Got killed at least once
,# teardown
,# setup
,# Two notification actions
,2017-07-21 15:24:18 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 640 Got Null
,ok 641 Got another null
,2017-07-21 15:24:18 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,ok 642 is an agent
,2017-07-21 15:24:18 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,2017-07-21 15:24:18 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 643 is an agent
,2017-07-21 15:24:18 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 644 Action 1 killed at least once
,ok 645 Action 1 went first
,ok 646 Action 2 killed at least once
,# teardown
,# setup
,# replicateThroughProblems
,2017-07-21 15:24:19 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
,2017-07-21 15:24:19 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
,2017-07-21 15:24:19 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 647 should have gotten null
,2017-07-21 15:24:19 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
,2017-07-21 15:24:19 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activity time out - noActivityTimeOut'
,ok 648 Should have stopped nicely
,2017-07-21 15:24:19 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
,2017-07-21 15:24:19 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButNotAvailable'
,ok 649 Still looking for null
,2017-07-21 15:24:19 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
,2017-07-21 15:24:19 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
,2017-07-21 15:24:19 - DEBUG thaliPeerPoolOneAtATime: 'Replication action failed badly so we are going to retry'
,2017-07-21 15:24:19 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
,2017-07-21 15:24:19 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
,2017-07-21 15:24:19 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 650 Yup, another null
,ok 651 We cloned!
,# teardown
,# setup
,# Replication goes first
,2017-07-21 15:24:19 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 652 Null 1
ok 653 (unnamed assert)
2017-07-21 15:24:19 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBlu,etooth, Peer Identifier: notificationAction'
ok 654 is an agent
ok 655 Null 3
ok 656 Replication not yet called
ok 657 Notification 2 not yet called
2017-07-21 15:24:19 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action, ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
2017-07-21 15:24:19 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidB,luetooth, Peer Identifier: replicationAction'
ok 658 is an agent
ok 659 Notification went first
ok 660 Notification 2 not called yet
2017-07-21 15:24:19 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 591, Action, ,Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,2017-07-21 15:24:19 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-21 15:24:19 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 661 is an agent
,ok 662 Notification finished
,ok 663 Replication finished
,2017-07-21 15:24:19 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,# teardown
,# setup
,# wifi allows many parallel non-replication actions
,2017-07-21 15:24:20 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2017-07-21 15:24:20 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
ok 664 is an agent
ok 665 First does, not throw
2017-07-21 15:24:20 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
ok 666 is an agent
ok 667 Second does not throw
2017-07-21 15:24:20 - DEBUG thaliPeerPoolOneAtAT,ime: 'action returned successfully from start - Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
truetruefalsetrue
,2017-07-21 15:24:20 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
truetruetruetrue
,# teardown
,# setup
,# wifi allows no more than 2 simultaneous replication actions for same peerID
,2017-07-21 15:24:20 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-21 15:24:20 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 668 is an agent
,ok 669 first ok
,2017-07-21 15:24:20 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 670 is an agent
,ok 671 second ok
,ok 672 third ok
,2017-07-21 15:24:20 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-07-21 15:24:20 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-07-21 15:24:20 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-21 15:24:20 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,# teardown
,# setup
,# Client to server request coordinated
,2017-07-21 15:24:21 - DEBUG CoordinatedClient: 'test was skipped, name: 'Client to server request coordinated''
,# teardown
,2017-07-21 15:24:21 - INFO testThaliNotification: 'Participants:0 Peers Replied to us:0 Peers requested to:0'
,# setup
,# Test BEACONS_RETRIEVED_AND_PARSED locally
,ok 673 peerIdentifier should match
,ok 674 generation should match
,ok 675 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 676 good beacon
,ok 677 good preAmble
,ok 678 public keys match!
,ok 679 must return null after successful call
,ok 680 Once start returns the action should be in KILLED state
,# teardown
,2017-07-21 15:24:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test HTTP_BAD_RESPONSE locally
,2017-07-21 15:24:21 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test HTTP_BAD_RESPONSE locally''
,# teardown
,2017-07-21 15:24:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test NETWORK_PROBLEM locally
,ok 681 Response should be NETWORK_PROBLEM
,ok 682 reject reason should be: Could not establish TCP connection
,# teardown
,2017-07-21 15:24:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails when getPeerHostInfo fails
,ok 683 Resolution should be BAD_PEER
ok 684 correct error message
,# teardown
,2017-07-21 15:24:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the start two times
,ok 685 Call start once
,ok 686 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 687 must return null after successful call.
,# teardown
,2017-07-21 15:24:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill before calling the start
,ok 688 Should be Killed
ok 689 Start after killed
,# teardown
,2017-07-21 15:24:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill immediately after the start
,ok 690 Should be KILLED
,ok 691 must return null after successful kill
,# teardown
,2017-07-21 15:24:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill while waiting a response from the server
,ok 692 Should be KILLED
ok 693 must return null after successful kill
,# teardown
,2017-07-21 15:24:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test to exceed the max content size locally
,ok 694 HTTP_BAD_RESPONSE should be response when content size is exceeded
,ok 695 must return null after successful call
,# teardown
,2017-07-21 15:24:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Close the server socket while the client is waiting a response from the server. Local test.
,2017-07-21 15:24:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 696 Should be NETWORK_PROBLEM caused closing server socket
ok 697 Should be Could not establish TCP connection
,# teardown
,# setup
,# Close the client socket while the client is waiting a response from the server. Local test.
,ok 698 Should be NETWORK_PROBLEM caused closing client socket
ok 699 Should be Could not establish TCP connection
,# teardown
,2017-07-21 15:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #generatePreambleAndBeacons bad args
,ok 700 publicKeysToNotify cannot be null
ok 701 ecdh for local device cannot be null
ok 702 milliseconds cannot be less than 0
ok 703 milliseconds cannot be 0
ok 704 milliseconds cannot be greater than one_day
,# teardown
,# setup
,# #generatePreambleAndBeacons empty keys to notify
,ok 705 should be equal
,# teardown
,# setup
,# #generatePreambleAndBeacons multiple keys to notify
,ok 706 should be equal
,ok 707 should be equal
,ok 708 (unnamed assert)
,ok 709 should be equal
,# teardown
,# setup
,# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
,ok 710 should throw
,# teardown
,# setup
,# #parseBeacons invalid expiration in beaconStreamWithPreAmble
,ok 711 Preamble expiration must be a 64 bit integer
,# teardown
,# setup
,# #parseBeacons expiration out of range lower
,ok 712 Expiration out of range
,# teardown
,# setup
,# #parseBeacons expiration out of range lower
,ok 713 Expiration out of range
,# teardown
,# setup
,# #parseBeacons no beacons returns null
,ok 714 should be equal
,# teardown
,# setup
,# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
,ok 715 Malformed encrypted beacon key ID
,# teardown
,# setup
,# #parseBeacons addressBookCallback fails decrypt
,ok 716 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns no matches
,2017-07-21 15:24:35 - DEBUG CoordinatedClient: 'test was skipped, name: '#parseBeacons addressBookCallback returns no matches''
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns spurious match
,ok 717 should be equal
,ok 718 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns public key
,ok 719 right number of calls to address book
,ok 720 good preAmble
ok 721 good unencryptedKeyId
ok 722 good beacon
,# teardown
,# setup
,# validate generatePskIdentityField
,ok 723 decoded buffers match
,# teardown
,# setup
,# validate generatePskSecret
,ok 724 secrets match
,# teardown
,# setup
,# validate generatePskSecrets
,ok 725 Matching numbers
,ok 726 We have an entry!
ok 727 keys match
,ok 728 secrets match
,ok 729 We have an entry!
,ok 730 keys match
ok 731 secrets match
,ok 732 We have an entry!
,ok 733 keys match
,ok 734 secrets match
,# teardown
,# setup
,# validate generateBeaconStreamAndSecrets
,ok 735 Streams have same length
,ok 736 matching size
,ok 737 keys match
,ok 738 secrets match
,# teardown
,# setup
,# Add two Peers.
,ok 739 should be equal
,ok 740 peerDictionalty contains 2 peers
ok 741 bluetooth peer's notification has correct connection type
ok 742 tcp peer's notification has correct connection type
2017-07-21 15:24:38 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
2017-07-21 15:24:38 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-21 15:24:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# TCP_NATIVE peer loses DNS
,ok 743 notification peer dictionary contains exactly 1 peer
,2017-07-21 15:24:39 - WARN thaliNotificationClient: 'peer is not available'
,ok 744 notification peer dictionary does not contain any peers
,2017-07-21 15:24:39 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-21 15:24:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Received beacons with no values for us
,ok 745 entry exists
ok 746 entry is resolved
,# teardown
,2017-07-21 15:24:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Notification action killed with a superseded
,ok 747 Action should be KILLED
,ok 748 Peer state should be RESOLVED
,# teardown
,2017-07-21 15:24:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally
,ok 749 hostAddress must match
,ok 750 portNumber must match
,ok 751 suggestedTCPTimeout must match
ok 752 connectionType must match
,ok 753 peerIDs must match
,# teardown
,2017-07-21 15:24:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 754 Correct error
,# teardown
,2017-07-21 15:24:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally using ThaliPeerPoolDefault
,ok 755 hostAddress must match
ok 756 portNumber must match
,ok 757 suggestedTCPTimeout must match
ok 758 connectionType must match
,ok 759 peerIds must match
,# teardown
,2017-07-21 15:24:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails because of a bad hostname.
,2017-07-21 15:24:41 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 760 action should be resolved with NETWORK_PROBLEM error
,2017-07-21 15:24:41 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 761 action should be resolved with NETWORK_PROBLEM error
,2017-07-21 15:24:42 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 762 action should be resolved with NETWORK_PROBLEM error
,2017-07-21 15:24:42 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 763 action should be resolved with NETWORK_PROBLEM error
,ok 764 correct number of requests
,ok 765 correct number of failures
,ok 766 correct final peer state
,# teardown
,2017-07-21 15:24:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# hostaddress is removed when the action is running. 
,2017-07-21 15:24:45 - WARN thaliNotificationClient: 'peer is not available'
2017-07-21 15:24:45 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 767 peerDictionary should become empty
,# teardown
,2017-07-21 15:24:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notificationClient does not retry action with BAD_PEER resolution
,2017-07-21 15:24:45 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 768 failed with expected error
,ok 769 peer state should be RESOLVED
,# teardown
,2017-07-21 15:24:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notification client correctly handles peer availability changes of the same peer
,2017-07-21 15:24:46 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 770 First action failed
,ok 771 second action killed
# teardown
,2017-07-21 15:24:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Client to server request locally
,ok 772 secrets are equal
,ok 773 Public key matches with the server key
,ok 774 hostAddress must match
ok 775 portNumber must match
,ok 776 suggestedTCPTimeout must match
,ok 777 connectionType must match
,# teardown
,2017-07-21 15:24:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache clean and expiration
,ok 778 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
,ok 779 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
,ok 780 All entries should be expired after 1 second
# teardown
,2017-07-21 15:24:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache getSecret and getPublic
,ok 781 All keys need to be available in the cache
,ok 782 All entries should be expired after 1 second
# teardown
,2017-07-21 15:24:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache multiple entries
,ok 783 Size of the cache should be 2
ok 784 Cache doesn't contain dictionary1
,ok 785 Size of the cache should be 1
ok 786 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
,2017-07-21 15:24:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start and stop ThaliNotificationServer
,ok 787 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
,ok 788 ThaliMobile.StopAdvertisingAndListeningshould be called once
,# teardown
,2017-07-21 15:24:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty array to ThaliNotificationServer.start
,ok 789 StartUpdateAdvertisingAndListening should not be called
,ok 790 ThaliMobile.StopAdvertisingAndListening should be called once
,ok 791 no error
,ok 792 should be 204
,# teardown
,2017-07-21 15:24:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass a string to ThaliNotificationServer.start
,ok 793 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-21 15:24:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty parameter to ThaliNotificationServer.start
,ok 794 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-21 15:24:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons
,ok 795 no error
,ok 796 should be 200
,ok 797 should be equal
,ok 798 should be equal
,ok 799 (unnamed assert)
,ok 800 no error
,ok 801 should be 204
,# teardown
,2017-07-21 15:24:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons (no keys)
,ok 802 error should be null
,ok 803 should be 204
,# teardown
,2017-07-21 15:24:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeaconsbefore calling start
,ok 804 should be 404
# teardown
,2017-07-21 15:24:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure peerDictionaryKey is reasonable
,ok 805 equal keys
ok 806 not equal connection type
ok 807 same connection type, different buffer
,# teardown
,# setup
,# Make sure start works
,2017-07-21 15:24:58 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 808 First start and on called correctly
,# teardown
,# setup
,# Make sure stop works
,ok 809 second cleared dictionary
2017-07-21 15:24:58 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 810 First start and on called correctly
,ok 811 First stop and removeListener called correctly
ok 812 first action kill called
ok 813 second action kill called
ok 814 first cleared dictionary
,ok 815 first cleared pool
,ok 816 second cleared dictionary
,ok 817 second cleared pool
,# teardown
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 818 Correct error
,# teardown
,# setup
,# Simple peer event
,2017-07-21 15:24:59 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 819 listener has been set
,ok 820 peer dictionary has expected number of entries
,ok 821 Dictionary and pool have same action
,ok 822 ads match
,ok 823 PouchDB matches
,ok 824 DB Names match
,ok 825 public keys match
,ok 826 peer dictionary has expected number of entries
,ok 827 Dictionary and pool have same action
,ok 828 ads match
,ok 829 PouchDB matches
,ok 830 DB Names match
,ok 831 public keys match
,2017-07-21 15:24:59 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
,ok 832 start called once
,ok 833 One entry left
,ok 834 Dictionary and pool have same action
,ok 835 Start never called
,ok 836 Kill called once
,ok 837 no entries left
,ok 838 Third action is dead
,ok 839 peer dictionary has expected number of entries
,ok 840 Dictionary and pool have same action
,ok 841 ads match
,ok 842 PouchDB matches
,ok 843 DB Names match
,ok 844 public keys match
,# teardown
,# setup
,# Coordinated pull replication from notification test
,2017-07-21 15:25:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated pull replication from notification test''
,# teardown
,# setup
,# Server is not there
,2017-07-21 15:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 15:25:01 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
,2017-07-21 15:25:01 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: connect ECONNREFUSED  and it caused us to complete'
,ok 845 right error
,# teardown
,2017-07-21 15:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server accepts & closes connection
,2017-07-21 15:25:01 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
,2017-07-21 15:25:01 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up  and it caused us to complete'
,ok 846 right error
,# teardown
,2017-07-21 15:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 500
,2017-07-21 15:25:02 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
,2017-07-21 15:25:02 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 847 Got error as expected
,# teardown
,2017-07-21 15:25:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 401
,2017-07-21 15:25:02 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
,2017-07-21 15:25:02 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 848 Got error as expected
,# teardown
,2017-07-21 15:25:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 403
,2017-07-21 15:25:03 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
,2017-07-21 15:25:03 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 849 Got error as expected
,# teardown
,2017-07-21 15:25:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with same name as local db
,2017-07-21 15:25:04 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-21 15:25:04 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-21 15:25:07 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 850 should be equal
ok 851 All tests passed!
,# teardown
,2017-07-21 15:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with different name than local db
,2017-07-21 15:25:09 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-21 15:25:09 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-21 15:25:12 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 852 should be equal
ok 853 All tests passed!
,# teardown
,2017-07-21 15:25:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do nothing and make sure we time out
,2017-07-21 15:25:14 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-21 15:25:15 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-21 15:25:15 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
ok 854 action should be killed
ok 855 Error should be timed out
,ok 856 No doc found
,# teardown
,2017-07-21 15:25:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do something and make sure we time out
,2017-07-21 15:25:17 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-21 15:25:17 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,ok 857 should be equal
,2017-07-21 15:25:19 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-21 15:25:19 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
,ok 858 action should be killed
ok 859 Error should be timed out
,# teardown
,2017-07-21 15:25:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start replicating and then catch error when server goes
,ok 860 socket hung up
,# teardown
,2017-07-21 15:25:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure clone works
,ok 861 same getPeerAdvertisesDataForUs
,ok 862 Same pouchdB
ok 863 same localDbName
ok 864 Same public key
,# teardown
,# setup
,# Coordinated replication action test - each device has the same local db name
,2017-07-21 15:25:21 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated replication action test - each device has the same local db name''
,# teardown
,# setup
,# Coordinated replication action test - each device has different local db name
,2017-07-21 15:25:22 - DEBUG thaliMobileNativeWrapper: 'listening 58152'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:90B0F54E-A9CF-4A42-8EB7-CF997B76E24E
[ThaliCore] Browser.startListening
,2017-07-21 15:25:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CFC2E601-CFC0-41DB-95DA-3DCDEE3E3CC2", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:CFC2E601-CFC0-41DB-95DA-3DCDEE3E3CC2
,2017-07-21 15:25:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C8077C07-B78C-4B70-A159-5DD76B16A0C5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C8077C07-B78C-4B70-A159-5DD76B16A0C5", generation: 0)
2017-07-21 15:25:23 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"C8077C07-B78C-4B70-A159-5DD76B16A0C5","generation":0}]'
2017-07-21 15:25:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"C8077C07-B78C-4B70-A159-5DD76B16A0C5","generation":0}'
,2017-07-21 15:25:23 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"C8077C07-B78C-4B70-A159-5DD76B16A0C5","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 15:25:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"C8077C07-B78C-4B70-A159-5DD76B16A0C5","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 15:25:23 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for C8077C07-B78C-4B70-A159-5DD76B16A0C5 (syncValue: 3)'
,2017-07-21 15:25:23 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C8077C07-B78C-4B70-A159-5DD76B16A0C5", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C8077C07-B78C-4B70-A159-5DD76B16A0C5", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C8077C07-B78C-4B70-A159-5DD76B16A0C5:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:75F3DD46-7D76-46AE-8D28-4484695DBABB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "75F3DD46-7D76-46AE-8D28-4484695DBABB", generation: 0)
,2017-07-21 15:25:23 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"75F3DD46-7D76-46AE-8D28-4484695DBABB","generation":0}]'
,2017-07-21 15:25:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"75F3DD46-7D76-46AE-8D28-4484695DBABB","generation":0}'
,2017-07-21 15:25:23 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"75F3DD46-7D76-46AE-8D28-4484695DBABB","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 15:25:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"75F3DD46-7D76-46AE-8D28-4484695DBABB","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DB9C9F31-15F5-478D-946F-E24232546104
[ThaliCore] Advertiser: session connected Peer(uuid: "CFC2E601-CFC0-41DB-95DA-3DCDEE3E3CC2", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:DB9C9F31-15F5-478D-946F-E24232546104 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:C8077C07-B78C-4B70-A159-5DD76B16A0C5:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CFC2E601-CFC0-41DB-95DA-3DCDEE3E3CC2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CFC2E601-CFC0-41DB-95DA-3DCDEE3E3CC2", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:DB9C9F31-15F5-478D-946F-E24232546104
,[ThaliCore] Session.session(_:peer:didChange:) peer:DB9C9F31-15F5-478D-946F-E24232546104 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C8077C07-B78C-4B70-A159-5DD76B16A0C5:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:C8077C07-B78C-4B70-A159-5DD76B16A0C5:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "C8077C07-B78C-4B70-A159-5DD76B16A0C5", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:58155
,2017-07-21 15:25:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":null,"portNumber":58155}'
,2017-07-21 15:25:26 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 75F3DD46-7D76-46AE-8D28-4484695DBABB (syncValue: 4)'
,2017-07-21 15:25:26 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "75F3DD46-7D76-46AE-8D28-4484695DBABB", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "75F3DD46-7D76-46AE-8D28-4484695DBABB", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:75F3DD46-7D76-46AE-8D28-4484695DBABB:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DB9C9F31-15F5-478D-946F-E24232546104
[ThaliCore] Session.startOutputStream(with:) peer:DB9C9F31-15F5-478D-946F-E24232546104
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [5, 6, 20]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:C8077C07-B78C-4B70-A159-5DD76B16A0C5:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C8077C07-B78C-4B70-A159-5DD76B16A0C5:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:21 [5, 6, 20, 21]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:20
[ThaliCore] VirtualSocket.closeStreams() vsID:20
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DB9C9F31-15F5-478D-946F-E24232546104
[ThaliCore] Session.startOutputStream(with:) peer:DB9C9F31-15F5-478D-946F-E24232546104
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:22 [5, 6, 20, 21, 22]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] VirtualSocket exited RunLoop vsID:20
[ThaliCore] VirtualSocket.deinit vsID:20 [5, 6, 21, 22]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:), client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:21
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:21
[ThaliCore] VirtualSocket.deinit vsID:21 [5, 6, 22]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:C8077C07-B78C-4B70-A159-5DD76B16A0C5:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C8077C07-B78C-4B70-A159-5DD76B16A0C5:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:23 [5, 6, 22, 23]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DB9C9F31-15F5-478D-946F-E24232546104
[ThaliCore] Session.startOutputStream(with:) peer:DB9C9F31-15F5-478D-946F-E24232546104
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:24 [5, 6, 22, 23, 24]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2477A8C1-DDB3-4A71-A912-296BF0E07EAB
[ThaliCore] Advertiser: session connected Peer(uuid: "CFC2E601-CFC0-41DB-95DA-3DCDEE3E3CC2", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:2477A8C1-DDB3-4A71-A912-296BF0E07EAB state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:75F3DD46-7D76-46AE-8D28-4484695DBABB:0 state: notConnected -> connecting
,2017-07-21 15:25:27 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:C8077C07-B78C-4B70-A159-5DD76B16A0C5:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C8077C07-B78C-4B70-A159-5DD76B16A0C5:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:25 [5, 6, 22, 23, 24, 25]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DB9C9F31-15F5-478D-946F-E24232546104
[ThaliCore] Session.startOutputStream(with:) peer:DB9C9F31-15F5-478D-946F-E24232546104
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:26 [5, 6, 22, 23, 24, 25, 26]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DB9C9F31-15F5-478D-946F-E24232546104
[ThaliCore] Session.startOutputStream(with:) peer:DB9C9F31-15F5-478D-946F-E24232546104
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:27 [5, 6, 22, 23, 24, 25, 26, 27]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:C8077C07-B78C-4B70-A159-5DD76B16A0C5:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C8077C07-B78C-4B70-A159-5DD76B16A0C5:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:28 [5, 6, 22, 23, 24, 25, 26, 27, 28]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 15:25:27 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 6146551808:error:1408F119:SSL routines:SSL3_GET_RECORD:decryption failed or bad record mac:../deps/openssl/openssl/ssl/s3_pkt.c:518:
'
,2017-07-21 15:25:27 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: 6146551808:error:1408F119:SSL routines:SSL3_GET_RECORD:decryption failed or bad record mac:../deps/openssl/openssl/ssl/s3_pkt.c:518:
  and it caused us to complete'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:23
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vs,ID:25
,[ThaliCore] VirtualSocket exited RunLoop vsID:25
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:25 [5, 6, 22, 23, 24, 26, 27, 28]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:C8077C07-B78C-4B70-A159-5DD76B16A0C5:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:28
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:28
,[ThaliCore] VirtualSocket.deinit vsID:28 [5, 6, 22, 23, 24, 26, 27]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C8077C07-B78C-4B70-A159-5DD76B16A0C5:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:29 [5, 6, 22, 23, 24, 26, 27, 29]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DB9C9F31-15F5-478D-946F-E24232546104
[ThaliCore] Session.startOutputStream(with:) peer:DB9C9F31-15F5-478D-946F-E24232546104
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:30 [5, 6, 22, 23, 24, 26, 27, 29, 30]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,2017-07-21 15:25:27 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
,2017-07-21 15:25:27 - DEBUG thaliReplicationPeerAction: 'Got error in update:  Stop Called, but we are already killed and so we ignored it'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:30
[ThaliCore] VirtualSocket.closeStreams() vsID:30
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:30
[ThaliCore] VirtualSocket.deinit vsID:30 [5, 6, 22, 23, 24, 26, 27, 29]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:75F3DD46-7D76-46AE-8D28-4484695DBABB:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2477A8C1-DDB3-4A71-A912-296BF0E07EAB
,[ThaliCore] Session.session(_:peer:didChange:) peer:2477A8C1-DDB3-4A71-A912-296BF0E07EAB state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2477A8C1-DDB3-4A71-A912-296BF0E07EAB
[ThaliCore] Session.startOutputStream(with:) peer:2477A8C1-DDB3-4A71-A912-296BF0E07EAB
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:31 [5, 6, 22, 23, 24, 26, 27, 29, 31]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:75F3DD46-7D76-46AE-8D28-4484695DBABB:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "75F3DD46-7D76-46AE-8D28-4484695DBABB", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:58170
,2017-07-21 15:25:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":null,"portNumber":58170}'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:31
[ThaliCore] VirtualSocket.closeStreams() vsID:31
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,31
[ThaliCore] VirtualSocket.deinit vsID:31 [5, 6, 22, 23, 24, 26, 27, 29]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCo,re] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:75F3DD46-7D76-46AE-8D28-448469,5DBABB:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2477A8C1-DDB3-4A71-A912-296BF0E07EAB
,[ThaliCore] Session.startOutputStream(with:) peer:2477A8C1-DDB3-4A71-A912-296BF0E07EAB
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:32 [5, 6, 22, 23, 24, 26, 27, 29, 32]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:75F3DD46-7D76-46AE-8D28-4484695DBABB:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:33 [5, 6, 22, 23, 24, 26, 27, 29, 32, 33]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:33
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:33
[ThaliCore] VirtualSocket.deinit vsID:33 [5, 6, 22, 23, 24, 26, 27, 29, 32]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:75F3DD46-7D76-46AE-8D28-4484695DBABB:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:75F3DD46-7D76-46AE-8D28-4484695DBABB:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:34 [5, 6, 22, 23, 24, 26, 27, 29, 32, 34]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2477A8C1-DDB3-4A71-A912-296BF0E07EAB
[ThaliCore] Session.startOutputStream(with:) peer:2477A8C1-DDB3-4A71-A912-296BF0E07EAB
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:35 [5, 6, 22, 23, 24, 26, 27, 29, 32, 34, 35]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,2017-07-21 15:25:30 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:75F3DD46-7D76-46AE-8D28-4484695DBABB:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:75F3DD46-7D76-46AE-8D28-4484695DBABB:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:36 [5, 6, 22, 23, 24, 26, 27, 29, 32, 34, 35, 36]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2477A8C1-DDB3-4A71-A912-296BF0E07EAB
[ThaliCore] Session.startOutputStream(with:) peer:2477A8C1-DDB3-4A71-A912-296BF0E07EAB
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:37 [5, 6, 22, 23, 24, 26, 27, 29, 32, 34, 35, 36, 37]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:22
,[ThaliCore] VirtualSocket.closeStreams() vsID:22
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:22
[ThaliCore] VirtualSocket.deinit vsID:22 [5, 6, 23, 24, 26, 27, 29, 32, 34, 35, 36, 37]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:24
[ThaliCore] VirtualSocket.closeStreams() vsID:24
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:24
[ThaliCore] VirtualSocket.deinit vsID:24 [5, 6, 23, 26, 27, 29, 32, 34, 35, 36, 37]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socke,tDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:26
[ThaliCore] VirtualSocket.closeStreams() vsID:26
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:26
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] VirtualSocket.deinit vs,ID:26 [5, 6, 23, 27, 29, 32, 34, 35, 36, 37]
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:27
,[ThaliCore] VirtualSocket.closeStreams() vsID:27
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:27
[ThaliCore] VirtualSocket.deinit vsID:27 [5, 6, 23, 29, 32, 34, 35, 36, 37]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:75F3DD46-7D76-46AE-8D28-4484695DBABB:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:75F3DD46-7D76-46AE-8D28-4484695DBABB:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:38 [5, 6, 23, 29, 32, 34, 35, 36, 37, 38]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:75F3DD46-7D76-46AE-8D28-4484695DBABB:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:75F3DD46-7D76-46AE-8D28-4484695DBABB:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:39 [5, 6, 23, 29, 32, 34, 35, 36, 37, 38, 39]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2477A8C1-DDB3-4A71-A912-296BF0E07EAB
[ThaliCore] Session.startOutputStream(with:) peer:2477A8C1-DDB3-4A71-A912-296BF0E07EAB
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:40 [5, 6, 23, 29, 32, 34, 35, 36, 37, 38, 39, 40]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:75F3DD46-7D76-46AE-8D28-4484695DBABB:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:75F3DD46-7D76-46AE-8D28-4484695DBABB:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:41 [5, 6, 23, 29, 32, 34, 35, 36, 37, 38, 39, 40, 41]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:39
,[ThaliCore] VirtualSocket exited RunLoop vsID:39
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:39 [5, 6, 23, 29, 32, 34, 35, 36, 37, 38, 40, 41]
,2017-07-21 15:25:30 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:32
[ThaliCore] VirtualSocket.closeStreams() vsID:32
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,32
[ThaliCore] VirtualSocket.deinit vsID:32 [5, 6, 23, 29, 34, 35, 36, 37, 38, 40, 41]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnect,ed
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:35
[ThaliCore] VirtualSocket.closeStreams() vsID:35
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:35
[ThaliCore] VirtualSocket.deinit vsID:35 [5, 6, 23, 29, 34, 36, 37, 38, 40, 41]
[ThaliCore] TCPClient.socketDidDisconnec,t(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStrea,m endEncountered vsID:40
[ThaliCore] VirtualSocket.closeStreams() vsID:40
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:37
[ThaliCore] VirtualSocket.closeStreams() vsID:37
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:40
[ThaliCore] VirtualSocket.deinit vsID:40 [5, 6, 23, 29, 34, 36, 37, 38, 41]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisc,onnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:37
[ThaliCore] VirtualSocket.deinit vsID:37 [5, 6, 23, 29, 34, 36, 38, 41]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconne,ct(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-21 15:25:33 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-21 15:25:33 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliC,ore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:34
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:36
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:38
[ThaliCore] TCPLis,tener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect,(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:41
[ThaliCore] BrowserRelay.didCloseVi,rtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:34
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:36
[ThaliCore] BrowserRelay.didCloseVi,rtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket.deinit vsID:34 [5, 6, 23, 29, 36, 38, 41]
[ThaliCore] VirtualSocket exited RunLoop vsID:38
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] Virt,ualSocket exited RunLoop vsID:41
[ThaliCore] VirtualSocket.deinit vsID:36 [5, 6, 23, 29, 38, 41]
[ThaliCore] VirtualSocket.deinit vsID:38 [5, 6, 23, 29, 41]
[ThaliCore] VirtualSocket.deinit vsID:41 [5, 6, 23, 29]
,2017-07-21 15:28:22 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2017-07-21 15:28:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:28:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:28:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:28:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:28:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:28:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:28:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:28:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:28:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:28:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:29:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:29:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:29:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:29:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:29:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:29:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:29:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:29:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:29:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:29:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4,C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:29:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:29:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:30:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:30:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4,C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:30:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:30:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:30:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:30:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:30:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:30:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:30:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:30:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:30:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:30:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:31:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:31:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:31:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:31:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:31:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:31:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:31:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:31:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:31:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:31:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:32:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:32:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:32:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:32:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:32:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:32:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:32:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:32:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:32:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:32:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:32:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:32:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:33:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:33:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:33:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:33:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:33:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:33:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:33:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:33:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:33:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:33:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:33:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:33:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:34:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:34:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4,C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:34:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:34:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:34:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:34:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:34:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:34:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:34:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:34:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:34:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:34:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:35:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:35:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:35:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:35:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:35:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:35:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
2017-07-21 15:35:22 - INFO, CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server ,that is not listening yet witheatNotRunning set to true'
2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOG,GER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoi,n,ts plugin delay interval'
2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-07-21 15:35:22 - INFO Coordin,atedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue, and run in order'
2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
2017-07-21 15:,35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
2017-07-21 15:35:22 - INF,O, CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER resu,lt: passed - another'
2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
2017-07-21 15:35:22 - INFO CoordinatedClient: '***T,EST_LOGGER result: passed - test sinon sansbox spy'
2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox ,stub override'
2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
2017-07-21 ,1,5:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
2017-07-21 15:35:22 - INFO CoordinatedClient: '***,TEST_LOGGER result: skipped - onPeerLost calls jxcore'
2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call ,start/stopListeningForAdvertisements'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiConnect properly fails on legal but non-existent peerID'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with invalid syncValue'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call disconnect with invalid peer id'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - disconnect doesn't fail on plausible but bogus peer ID'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Get same port when trying to connect multiple times on iOS'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - initial peer discovery'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 1'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 2'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - check latest peer discovery'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Set up for no peer discovery test'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - no peer discovery'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits incomingConnectionState'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server connections all up'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can create servers manager'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling stop without start causes error'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can start/stop servers manager'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connection'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single local http request'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single coordinated request ios native'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple local http requests'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple coordinated request ios native'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - should be able to call #stopListeningForAdvertisements many times'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status before starting'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - error returned with bad router'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are started when we call start'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP Servers Manager should be null when we call start on iOS'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are stopped when we call stop'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateConnection is properly hooked up'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateConnection is return error if we get called on iOS'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateListener is properly hooked up'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateListener is return error if we get called on iOS'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure we actually call kill connections properly'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from multiConnectConnection'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure bad PSK connections fail'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer changes handled from a queue'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - relaying discoveryAdvertisingStateUpdateNonTCP'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - we successfully receive and replay discoveryAdvertisingStateUpdate'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - can do HTTP requests between peers'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - can still do HTTP requests between peers with coordinator'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - calls correct starts when network changes'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test to coordinate connection cut'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests after connections are cut'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - will fail bad PSK connection between peers'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We provide notification when a listener dies and we recreate it'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start - Causing native or wifi to fail will cause a promise reject '
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start should fail if called twice in a row'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not emit duplicate discoveryAdvertisingStateUpdate'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - does not send duplicate availability changes'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (native)'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (wifi)'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - new peer is cached'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with same port and different generation is cached (BLUETOOTH)'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with greater generation is cached (MPCF)'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with same or older generation is ignored (MPCF)'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - new peer is ignored'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - cached peer is removed'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for wifi peers'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - new peer is ignored (MPCF)'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (TCP_NATIVE)'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort field (BLUETOOTH)'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (MPCF)'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - error when peer has not been discovered yet'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached wifi peer'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect fails on wifi peers'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect delegates native peers to the native wrapper'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes emitted correctly'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in started state'
2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in stopped state'
20,17-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on Android'
2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properl,y fire peer unavailable and then available when connection fails on iOS'
2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying t,o connect make sure recreate does not happen'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not fire duplicate events after peer listener recreation'
2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #stop should change peers'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer should be found once after listening and discovery started'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get data from all participants'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - test for data corruption'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - test getters'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start and kill'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - double start'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start after kill'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - make sure ids are unique'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - check that forever agent can be destroyed'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary basic functionality'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary with multiple entries.'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - RESOLVED entries are removed before WAITING state entry.'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - WAITING entries are removed before CONTROLLED_BY_POOL state entry.'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - When CONTROLLED_BY_POOL entry is removed and kill is called.'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - single action'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - multiple actions'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - PSK Pool works'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - stop'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that start verifies queue length'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - bad enqueues'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - do not allow same object type'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure we catch kill and dequeue'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that stop removes all actions'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized connection type'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized action type'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One action on bluetooth'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Two notification actions'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - replicateThroughProblems'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Replication goes first'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows many parallel non-replication actions'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows no more than 2 simultaneous replication actions for same peerID'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Client to server request coordinated'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test BEACONS_RETRIEVED_AND_PARSED locally'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test HTTP_BAD_RESPONSE locally'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test NETWORK_PROBLEM locally'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails when getPeerHostInfo fails'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the start two times'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill before calling the start'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill immediately after the start'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill while waiting a response from the server'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test to exceed the max content size locally'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the server socket while the client is waiting a response from the server. Local test.'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the client socket while the client is waiting a response from the server. Local test.'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons bad args'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons empty keys to notify'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons multiple keys to notify'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid expiration in beaconStreamWithPreAmble'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons no beacons returns null'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback fails decrypt'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #parseBeacons addressBookCallback returns no matches'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns spurious match'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns public key'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskIdentityField'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecret'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecrets'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generateBeaconStreamAndSecrets'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Add two Peers.'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP_NATIVE peer loses DNS'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Received beacons with no values for us'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Notification action killed with a superseded'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally using ThaliPeerPoolDefault'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails because of a bad hostname.'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - hostaddress is removed when the action is running. '
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notificationClient does not retry action with BAD_PEER resolution'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notification client correctly handles peer availability changes of the same peer'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Client to server request locally'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache clean and expiration'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache getSecret and getPublic'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache multiple entries'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start and stop ThaliNotificationServer'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty array to ThaliNotificationServer.start'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass a string to ThaliNotificationServer.start'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty parameter to ThaliNotificationServer.start'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons (no keys)'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeaconsbefore calling start'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure peerDictionaryKey is reasonable'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure start works'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure stop works'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Simple peer event'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated pull replication from notification test'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server is not there'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server accepts & closes connection'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 500'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 401'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 403'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with same name as local db'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with different name than local db'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do nothing and make sure we time out'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do something and make sure we time out'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start replicating and then catch error when server goes'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure clone works'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated replication action test - each device has the same local db name'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - Coordinated replication action test - each device has different local db name, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Appl,ication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxc,ore/node_modules/bluebird/js/release/timers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1,
''
,2017-07-21 15:35:22 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,not ok 865 failed with TimeoutError
  ---
    operator: fail
  ...
,# teardown
,2017-07-21 15:35:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:35:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:35:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:35:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:35:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:35:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4,C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:36:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:36:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:36:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:36:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:36:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:36:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:36:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:36:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:36:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:36:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:36:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:36:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4,C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:37:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:37:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:37:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:37:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:37:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:37:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:37:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:37:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:37:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:37:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:37:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:37:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:38:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:38:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:38:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:38:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:38:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:38:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:38:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:38:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:38:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:38:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:38:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:38:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4,C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:39:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:39:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:39:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:39:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:39:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:39:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:39:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:39:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:39:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C5,6-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:39:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/47845A61-57A0-4C56-9B30-40591C74D47E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''

```
