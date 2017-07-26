#### Test 1322832571374948_iOS_Iphone6sPlus-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/1322832571374948/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/5A10D57D-6189-4B26-BD90-7CE0B69BA7ED/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'
,Executing commands in '/tmp/5A10D57D-6189-4B26-BD90-7CE0B69BA7ED/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/1322832571374948/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/1322832571374948/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62464"
,(lldb)     command script import "/tmp/5A10D57D-6189-4B26-BD90-7CE0B69BA7ED/fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.py"
,(lldb)     command script add -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-07-26 15:22:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-26 15:22:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-26 15:22:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:22:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-26 15:22:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-26 15:22:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:22:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "569C3A3C-FC08-43AA-AFC3-7C5BE1272599", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:569C3A3C-FC08-43AA-AFC3-7C5BE1272599
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:729365A0-1BED-4499-A8B5-832E9E3145C5
[ThaliCore] Browser,.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F89B09EE-C1CA-4836-8A99-ECC41852061F
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "003A74BA-A28F-4341-9FBB-47C1F18A2150", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:003A74BA-A28F-4341-9FBB-47C1F18A2150
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:003A74BA-A28F-4341-9FBB-47C1F18A2150:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "003A74BA-A28F-4341-9FBB-47C1F18A2150", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo,rrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-07-26 15:22:41 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.419655919075012
,2017-07-26 15:22:41 - DEBUG UnitTest_app: 'My device name is: 'Apple-Iphone6sPlus-1''
,2017-07-26 15:22:41 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:003A74BA-A28F-4341-9FBB-47C1F18A2150:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "003A74BA-A28F-4341-9FBB-47C1F18A2150", generation: 0)
,2017-07-26 15:22:43 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-26 15:22:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-26 15:22:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-26 15:22:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-26 15:22:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-26 15:22:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-26 15:22:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-26 15:22:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-26 15:22:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-26 15:22:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-26 15:22:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-26 15:22:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-26 15:22:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-26 15:22:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-26 15:22:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-26 15:22:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-26 15:22:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-26 15:22:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-26 15:22:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-26 15:22:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-26 15:22:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-26 15:22:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-26 15:22:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-26 15:22:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-26 15:22:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-26 15:22:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-26 15:22:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-26 15:22:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-26 15:22:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-26 15:22:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-26 15:22:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-26 15:22:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-26 15:22:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-26 15:22:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-26 15:22:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-26 15:22:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-26 15:22:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-26 15:22:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-26 15:22:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-26 15:22:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-26 15:22:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-26 15:22:45 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-26 15:22:45 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-26 15:22:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:22:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:22:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:22:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:22:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:23:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:23:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:23:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:23:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:23:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:23:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:23:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:23:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:23:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:23:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:23:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:23:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:24:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:24:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:24:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:24:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:24:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:24:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:24:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:24:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:24:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:24:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:24:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:24:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:25:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:25:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:25:12 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-07-26 15:25:12 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-26 15:25:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 1 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll with promise
,2017-07-26 15:25:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-26 15:25:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-07-26 15:25:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-07-26 15:25:17 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-07-26 15:25:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-07-26 15:25:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-07-26 15:25:19 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
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
ok 8 should be equal
,ok 9 should be equal
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
,ok 25 thirdPromise - in resolve
ok 26 secondPromise - second to run
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
,ok 42 executors is called
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
,2017-07-26 15:25:36 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-07-26 15:25:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-07-26 15:25:42 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
,2017-07-26 15:25:49 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-26 15:25:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-26 15:25:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-26 15:25:49 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:25:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:25:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:25:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:25:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:25:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-26 15:25:49 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-26 15:25:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-26 15:25:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-26 15:25:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:25:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-26 15:25:50 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-26 15:25:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-26 15:25:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-26 15:25:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A1E7870F-6A88-4181-8511-282713822442
[ThaliCore] Browser.startListening
,2017-07-26 15:25:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-26 15:25:50 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:25:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-26 15:25:50 - DEBUG thaliMobileNativeWrapper: 'disco,veryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:25:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without e,r,ror
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-26 15:25:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:25:51 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-26 15:25:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-26 15:25:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-26 15:25:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-26 15:25:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-26 15:25:51 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:25:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-26 15:25:51 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-26 15:25:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-26 15:25:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-26 15:25:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8038FEC1-A654-43E6-915F-1566F508999B
[ThaliCore] Browser.startListening
2017-07-26 15:25:51 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-26 15:25:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-26 15:25:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.startListeningForAdver,tisements
2017-07-26 15:25:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-26 15:25:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActiv,e":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:25:51 - INFO thaliMobile: 'Filtered out discoveryA,d,vertisingStateUpdate (was in stopped state).'
ok 65 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-26 15:25:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26, 15:25:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-26 15:25:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-07-26 15:25:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-26 15:25:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-26 15:25:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-26 15:25:52 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:25:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-26 15:25:52 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-26 15:25:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-26 15:25:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-26 15:25:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-26 15:25:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:25:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-26 15:25:52 - ,DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:25:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call sto,pListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-26 15:25:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:25:53 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-26 15:25:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-26 15:25:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-26 15:25:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-26 15:25:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-26 15:25:53 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:25:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-26 15:25:53 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-26 15:25:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-26 15:25:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-26 15:25:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F76ED100-4811-47DE-8CCC-F61861D0C86D", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:F76ED100-4811-47DE-8CCC-F61861D0C86D
2017-07-26 1,5:25:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-26 15:25:53 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:25:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising(,)
[ThaliCore] Advertiser.stopAdvertising() peerID:F76ED100-4811-47DE-8CCC-F61861D0C86D
2017-07-26 15:25:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:25:53, - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-26 15:25:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:25:53 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-26 15:25:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-26 15:25:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-26 15:25:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-26 15:25:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-26 15:25:53 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:25:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:25:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:25:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:25:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:25:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E3F6536C-DABA-4149-8ABC-A89E4A37D50B", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:E3F6536C-DABA-4149-8ABC-A89E4A37D50B
,2017-07-26 15:25:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-26 15:25:53 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:25:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 70 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E3F6536C-DABA-4149-8ABC-A89E4A37D50B", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:E3F6536C-DABA-4149-8ABC-A89E4A37D50B
,2017-07-26 15:25:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-26 15:25:53 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-26 15:25:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-26 15:25:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-26 15:25:54 - INFO thaliMobile: 'Receive,d state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:2,5:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:E3F6536C-DABA-4149-8ABC-A89E4A37D50B
[ThaliCore] Advertiser.s,topAdvertising() peerID:E3F6536C-DABA-4149-8ABC-A89E4A37D50B
2017-07-26 15:25:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:25:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-26 15:25:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-26 15:25:54 - DEBUG thaliMo,bileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-26 15:25:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:25:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-26 15:25:54 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-26 15:25:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:25:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:25:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-26 15:25:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:25:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 72 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-26 15:25:54 - DEBUG th,aliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:25:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 73 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-26 15:25:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:25:54 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-26 15:25:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-26 15:25:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-26 15:25:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-26 15:25:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-26 15:25:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:25:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-26 15:25:54 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-26 15:25:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-26 15:25:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-26 15:25:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7E0E1C65-B1BC-4465-8138-E2F4FF7F1002", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:7E0E1C65-B1BC-4465-8138-E2F4FF7F1002
2017-07-26 1,5:25:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-26 15:25:55 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-26 15:25:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdv,ertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:507840E6-293E-49BE-8BD6-629CCA438ED5
[ThaliCore] Browser.startListening
2017-07-26 15:25:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryA,ctive":true,"advertisingActive":true}'
2017-07-26 15:25:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","sta,r,tArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:25:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7E0E1C65-B1BC-4465-8138-E2F4FF7F1002:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7E0E1C65-B1BC-4465-8138-E2F4FF7F1002", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:65BB0631-4C8E-48D5-9C63-E15CC7BCBCC0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "65BB0631-4C8E-48D5-9C63-E15CC7BCBCC0", generation: 0)
ok 76 peers must be an array,
ok 77 peers must not be zero-length
ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
ok 79 peerIdentifier must be a string
ok 80 generation must be a number
,# teardown
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7045561F-3AC7-42B2-AAA8-794CD97CD393:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7045561F-3AC7-42B2-AAA8-794CD97CD393", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-26 15:25:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-26 ,15:25:56 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-26 15:25:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:7E0E1C65-B1BC-4465-8138-E,2F4FF7F1002
2017-07-26 15:25:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:25:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
2017-07-26 15:25:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-26 15:25:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07,-26 15:25:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:25:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:25:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:25:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:25:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:25:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1972DBD3-7860-483F-83A6-386F04A64800", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:1972DBD3-7860-483F-83A6-386F04A64800
2017-07-26 1,5:26:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-26 15:26:03 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:26:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 81 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:961C12C5-E0D8-4DB9-9E5B-2FF9B952B065
[Thal,i,Core] Browser.startListening
2017-07-26 15:26:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-26 15:26:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:26:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1972DBD3-7860-483F-83A6-386F04A64800:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1972DBD3-7860-483F-83A6-386F04A64800", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C6CA495E-2E99-4FCC-AD24-3DAD01AF2F76
[ThaliCore] Advertiser: session connected Peer(uuid: "1972DBD3-7860-483F-83A6-386F04A64800", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:C6CA495E-2E99-4FCC-AD24-3DAD01AF2F76 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:233EEF45-D37B-4C1F-B455-6684C2646D24:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "233EEF45-D37B-4C1F-B455-6684C2646D24", generation: 0)
2017-07-26 15:26:04 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"233EEF45-D37B-4C1F-B455-6684C2646D24","generation":0}'
2017-07-26 15:26:04 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 233EEF45-D37B-4C1F-B455-6684C2646D24, (syncValue: RBdlwv41Xc3iTaJJi6SvanYJ3aAUNy0C)'
2017-07-26 15:26:04 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "233EEF45-D37B-4C1F-B455-6684C26,46D24", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "233EEF45-D37B-4C1F-B455-6684C2646D24", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:233EEF45-D37B-4C1F-B455-6684C2646D24:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D145E406-7804-4762-BB2C-5DCF327D3263
[ThaliCore] Advertiser: session connected Peer(uuid: "1972DBD3-7860-483F-83A6-386F04A64800", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:D145E406-7804-4762-BB2C-5DCF327D3263 state: notConnected -> connecting
[ThaliCore] Session.session(_:peer:didChange:) peer:233EEF45-D37B-4C1F-B455-6684C2646D24:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:81834FD2-2B19-4DA1-8940-C11D8697ADB7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "81834FD2-2B19-4DA1-8940-C11D8697ADB7", generation: 0)
2017-07-26 15:26:05 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"81834FD2-2B19-4DA1-8940-C11D8697ADB7","generation":0}'
2017-07-26 15:26:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 15:26:05 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C6CA495E-2E99-4FCC-AD24-3DAD01AF2F76
,[ThaliCore] Session.session(_:peer:didChange:) peer:C6CA495E-2E99-4FCC-AD24-3DAD01AF2F76 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:233EEF45-D37B-4C1F-B455-6684C2646D24:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:233EEF45-D37B-4C1F-B455-6684C2646D24:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "233EEF45-D37B-4C1F-B455-6684C2646D24", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61592
,2017-07-26 15:26:07 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"RBdlwv41Xc3iTaJJi6SvanYJ3aAUNy0C","error":null,"portNumber":61592}'
,2017-07-26 15:26:07 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'RBdlwv41Xc3iTaJJi6SvanYJ3aAUNy0C', error: 'null', listeningPort: '61592''
,2017-07-26 15:26:07 - INFO testThaliMobileNative: ''
ok 83 Must have listeningPort
ok 84 listeningPort must be a number
,ok 85 listening port should not be 0
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D145E406-7804-4762-BB2C-5DCF327D3263
,[ThaliCore] Session.session(_:peer:didChange:) peer:D145E406-7804-4762-BB2C-5DCF327D3263 state: connecting -> connected
,2017-07-26 15:26:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-26 15:26:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-26 15:26:08 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:26:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:1972DBD3-7860-483F-83A6-386F04A64800
,2017-07-26 15:26:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:26:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.disconnect peer:233EEF45-D37B-4C1F-B455-6684C2646D24
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61592
[ThaliCore] Session.disconnect,() peer:233EEF45-D37B-4C1F-B455-6684C2646D24:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:D145E406-7804-4762-BB2C-5DCF327D3263 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "1972DBD3-7860-483F-83A6-386F04A64800", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:D145E406-7804-4762-BB2C-5DCF327D3263
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:D145E406-7804-4762-BB2C-5DCF327D3263
,[ThaliCore] Session.deinit peer:233EEF45-D37B-4C1F-B455-6684C2646D24:0
[ThaliCore] BrowserRelay.deinit
,2017-07-26 15:26:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-26 15:26:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-26 15:26:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:26:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:26:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:26:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:26:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:26:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:C6CA495E-2E99-4FCC-AD24-3DAD01AF2F76 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "1972DBD3-7860-483F-83A6-386F04A64800", generation: 0)
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "96F9B2E1-4E94-4042-B264-425C9D00CBDB", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:96F9B2E1-4E94-4042-B264-425C9D00CBDB
,2017-07-26 15:26:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-26 15:26:09 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:26:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:68DB431D-089D-4A20-87E4-881769AE,E578
[ThaliCore] Browser.startListening
2017-07-26 15:26:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-26 15:26:09 - INFO thaliMobile: 'Received state ({"discover,y,Active":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:26:09 - INFO thaliMobi,le: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:81834FD2-2B19-4DA1-8940-C11D8697ADB7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "81834FD2-2B19-4DA1-8940-C11D8697ADB7", generation: 0)
2017-07-26 15:26:09 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"81834FD2-2B19-4DA1-8940-C11D8697ADB7","generation":0}'
2017-07-26 15:26:09 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 81834FD2-2B19-4DA1-8940-C11D8697ADB7, (syncValue: PtWHuSu9MXDsIgl29hJtJ5Zn2OArs3c7)'
2017-07-26 15:26:09 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "81834FD2-2B19-4DA1-8940-C11D869,7ADB7", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "81834FD2-2B19-4DA1-8940-C11D8697ADB7", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:) peer:81834FD2-2B19-4DA1-8940-C11D8697ADB7:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:233EEF45-D37B-4C1F-B455-6684C2646D24:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "233EEF45-D37B-4C1F-B455-6684C2646D24,", generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-26 15:26:09 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"233EEF45-D37B-4C1F-B455-6684C2646D24","generation":0}'
,2017-07-26 15:26:09 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-26 15:26:09 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:233EEF45-D37B-4C1F-B455-6684C2646D24:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "233EEF45-D37B-4C1F-B455-6684C2646D24", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CC3FF4E7-6553-4363-AEA7-645E14A53DDD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CC3FF4E7-6553-4363-AEA7-645E14A53DDD", generation: 0)
,2017-07-26 15:26:10 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A","generation":0}'
2017-07-26 15:26:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-26 15:26:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-26 15:26:10 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CC3FF4E7-6553-4363-AEA7-645E14A53DDD","generation":0}'
,2017-07-26 15:26:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-26 15:26:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-26 15:26:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:96F9B2E1-4E94-4042-B264-425C9D00CBDB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "96F9B2E1-4E94-4042-B264-425C9D00CBDB", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:81834FD2-2B19-4DA1-8940-C11D8697ADB7:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:81,834FD2-2B19-4DA1-8940-C11D8697ADB7:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "81834FD2-2B19-4DA1-8940-C11D8697ADB7", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "81834FD2-2B19-4DA1-8940-C11D8697ADB7", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "81834FD2-2B19-4DA1-8940-C11D8697ADB7", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:81834FD2-2B19-4DA1-8940-C11D8697ADB7:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:81834FD2-2B19-4DA1-8940-C11D8697ADB7:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:81834FD2-2B19-4DA1-8940-C11D8697ADB7:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:81,834FD2-2B19-4DA1-8940-C11D8697ADB7:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "81834FD2-2B19-4DA1-8940-C11D8697ADB7", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,1834FD2-2B19-4DA1-8940-C11D8697ADB7", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "81834FD2-2B19-4DA1-8940-C11D8697ADB7", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:81834FD2-2B19-4DA1-8940-C11D8697ADB7:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:81834FD2-2B19-4DA1-8940-C11D8697ADB7:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:81834FD2-2B19-4DA1-8940-C11D8697ADB7:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:81,834FD2-2B19-4DA1-8940-C11D8697ADB7:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "81834FD2-2B19-4DA1-8940-C11D8697ADB7", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,1834FD2-2B19-4DA1-8940-C11D8697ADB7", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "81834FD2-2B19-4DA1-8940-C11D8697ADB7", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:81834FD2-2B19-4DA1-8940-C11D8697ADB7:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:81834FD2-2B19-4DA1-8940-C11D8697ADB7:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:81834FD2-2B19-4DA1-8940-C11D8697ADB7:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "81834FD2-2B19-4DA1-8940-C11D8697ADB7", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:81834FD2-2B19-4DA1-8940-C11D8697ADB7:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:81,834FD2-2B19-4DA1-8940-C11D8697ADB7:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "81834FD2-2B19-4DA1-8940-C11D8697ADB7", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:81834FD2,-2B19-4DA1-8940-C11D8697ADB7 error: max retries exceeded
2017-07-26 15:26:20 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"PtWHuSu9MXDsIgl29hJtJ5Zn2OArs3c7","error":"Connection could not be established","portNumber":null}'
2017-0,7-26 15:26:20 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'PtWHuSu9MXDsIgl29hJtJ5Zn2OArs3c7', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-26 15:26:20 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-26 15:26:20 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A (syncValue: IMSJDab,rD2Lw5BFjrew3sYGAWhLAwNME)'
2017-07-26 15:26:20 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:ADEF5EDA-671B,-4553-A56D-9B5DA5C16E3A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-26 15:26:20 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
,2017-07-26 15:26:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:81834FD2-2B19-4DA1-8940-C11D8697ADB7:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61598
,2017-07-26 15:26:23 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"IMSJDabrD2Lw5BFjrew3sYGAWhLAwNME","error":null,"portNumber":61598}'
,2017-07-26 15:26:23 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'IMSJDabrD2Lw5BFjrew3sYGAWhLAwNME', error: 'null', listeningPort: '61598''
,Connecting to the localhost:61598
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A:0
,Connected to the localhost:61598
,2017-07-26 15:26:23 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-26 15:26:23 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 88 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams,() vsID:1
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,# teardown
,2017-07-26 15:26:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-26 15:26:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-26 15:26:24 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:26:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:96F9B2E1-4E94-4042-B264-425C9D00CBDB
,2017-07-26 15:26:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:26:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.disconnect peer:ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61598
[ThaliCore] Session.disconnect,() peer:ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A:0
,2017-07-26 15:26:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-26 15:26:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-26 15:26:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:26:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:26:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:26:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:26:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:26:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CEA74DD1-9E19-42C5-827A-AEC245524BBC", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:CEA74DD1-9E19-42C5-827A-AEC245524BBC
2017-07-26 1,5:26:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-26 15:26:25 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:26:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 89 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:175CA0F1-BEE4-40B3-9CB6-10773B8C40AD
[Thal,i,Core] Browser.startListening
2017-07-26 15:26:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-26 15:26:25 - INFO thaliMobile: 'Received state ({"discoveryActive":true,,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:26:25 - INFO thaliMobile: 'Filtere,d out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:426C00EC-1CE1-4DA1-851F-9CDEFAD2043E:0
2017-07-26 15:26:26 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "426C00EC-1CE1-4DA1-851F-9CDEFAD2043E", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CC3FF4E7-6553-4363-AEA7-645E14A53DDD:0
[ThaliC,ore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CC3FF4E7-6553-4363-AEA7-645E14A53DDD", generation: 0)
2017-07-26 15:26:26 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A (syncValue: THtJD9JuGinaUjii,U7N1gcGI3V46qzT9)'
2017-07-26 15:26:26 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A", generation: 0) creati,ng a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:ADEF5EDA-671B-4553-A56,D-9B5DA5C16E3A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-26 15:26:26 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"426C00EC-1CE1-4DA1-851F-9CDEFAD2043E","generation":0}'
2017-07-26 15:26:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-26 15:26:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-26 15:26:26 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CC3FF4E7-6553-4363-AEA7-645E14A53DDD","generation":0}'
,2017-07-26 15:26:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 15:26:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 15:26:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CEA74DD1-9E19-42C5-827A-AEC245524BBC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CEA74DD1-9E19-42C5-827A-AEC245524BBC", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:CC3FF4E7-6553-4363-AEA7-645E14A53DDD:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "CC3FF4E7-6553-4363-AEA7-645E14A53DDD", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:4E65AFCB-31AE-4C2A-AB9E-05D327D66222:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4E65AFCB-31AE-4C2A-AB9E-05D327D66222", generation: 0)
2017-07-26 15:26:27 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAv,ailable":true,"peerIdentifier":"4E65AFCB-31AE-4C2A-AB9E-05D327D66222","generation":0}'
2017-07-26 15:26:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 15:26:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-0,7-26 15:26:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:AD,EF5EDA-671B-4553-A56D-9B5DA5C16E3A:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,DEF5EDA-671B-4553-A56D-9B5DA5C16E3A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:AD,EF5EDA-671B-4553-A56D-9B5DA5C16E3A:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,DEF5EDA-671B-4553-A56D-9B5DA5C16E3A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:AD,EF5EDA-671B-4553-A56D-9B5DA5C16E3A:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,DEF5EDA-671B-4553-A56D-9B5DA5C16E3A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:AD,EF5EDA-671B-4553-A56D-9B5DA5C16E3A:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:ADEF5EDA,-671B-4553-A56D-9B5DA5C16E3A error: max retries exceeded
2017-07-26 15:26:37 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"THtJD9JuGinaUjiiU7N1gcGI3V46qzT9","error":"Connection could not be established","portNumber":null}'
2017-0,7-26 15:26:37 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'THtJD9JuGinaUjiiU7N1gcGI3V46qzT9', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-26 15:26:37 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-26 15:26:37 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 426C00EC-1CE1-4DA1-851F-9CDEFAD2043E (syncValue: Tcq4Gti,bpZ5sc3sC2lTJZJzscMvkowBm)'
2017-07-26 15:26:37 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "426C00EC-1CE1-4DA1-851F-9CDEFAD2043E", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "426C00EC-1CE1-4DA1-851F-9CDEFAD2043E", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:426C00EC-1CE1,-4DA1-851F-9CDEFAD2043E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-26 15:26:37 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-07-26 15:26:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:ADEF5EDA-671B-4553-A56D-9B5DA5C16E3A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:426C00EC-1CE1-4DA1-851F-9CDEFAD2043E:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:AC695C71-4915-470A-B373-90291BEF1320
[ThaliCore] Advertiser: session connected Peer(uuid: "CEA74DD1-9E19-42C5-827A-AEC245524BBC", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:AC695C71-4915-470A-B373-90291BEF1320 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:426C00EC-1CE1-4DA1-851F-9CDEFAD2043E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:426C00EC-1CE1-4DA1-851F-9CDEFAD2043E:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "426C00EC-1CE1-4DA1-851F-9CDEFAD2043E", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61614
2017-07-26 15:26:40 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Tcq4GtibpZ5sc3sC2lTJZJzscMvkowBm",,"error":null,"portNumber":61614}'
2017-07-26 15:26:40 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Tcq4GtibpZ5sc3sC2lTJZJzscMvkowBm', error: 'null', listeningPort: '61614''
,Connecting to the localhost:61614
Connecting to the localhost:61614
Connecting to the localhost:61614
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:426C00EC-1CE1-4DA1-851F-9CDEFAD2043E:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:426C00EC-1CE1-4DA1-851F-9CDEFAD2043E:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:426C00EC-1CE1-4DA1-851F-9CDEFAD2043E:0
Connected to the localhost:61614
Connected to the localhost:61614
Connected to the localhost:61614
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:426C00EC-1CE1-4DA1-851F-9CDEFAD2043E:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [1, 2]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:426C00EC-1CE1-4DA1-851F-9CDEFAD2043E:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [1, 2, 3]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:426C00EC-1CE1-4DA1-851F-9CDEFAD2043E:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [1, 2, 3, 4]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 91 correct string length
,2017-07-26 15:26:40 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 92 correct string length
,2017-07-26 15:26:40 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 93 correct string length
,2017-07-26 15:26:40 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-26 15:26:40 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-26 15:26:40 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-26 15:26:40 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:2
[ThaliCore] VirtualSocket exited RunLoop vsID:2
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,ok 94 got the same data back
[ThaliCore] VirtualSocket.deinit vsID:2 [1, 3, 4]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:3
,[ThaliCore] VirtualSocket exited RunLoop vsID:3
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:3 [1, 4]
ok 95 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:4
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,ok 96 got the same data back
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:AC695C71-4915-470A-B373-90291BEF1320
,[ThaliCore] Session.session(_:peer:didChange:) peer:AC695C71-4915-470A-B373-90291BEF1320 state: connecting -> connected
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C0524482-9D20-4396-9724-B784620F79E6
[ThaliCore] Advertiser: session connected Peer(uuid: "CEA74DD1-9E19-42C5-827A-AEC245524BBC", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:C0524482-9D20-4396-9724-B784620F79E6 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:AC695C71-4915-470A-B373-90291BEF1320
,[ThaliCore] Session.startOutputStream(with:) peer:AC695C71-4915-470A-B373-90291BEF1320
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [1, 4, 5]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:AC695C71-4915-470A-B373-90291BEF1320
,[ThaliCore] Session.startOutputStream(with:) peer:AC695C71-4915-470A-B373-90291BEF1320
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [1, 4, 5, 6]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:AC695C71-4915-470A-B373-90291BEF1320
,[ThaliCore] Session.startOutputStream(with:) peer:AC695C71-4915-470A-B373-90291BEF1320
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [1, 4, 5, 6, 7]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-26 15:26:43 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-26 15:26:43 - DEBUG testThaliMobileNative: 'Server received (2048 bytes):'
,2017-07-26 15:26:43 - DEBUG testThaliMobileNative: 'Server received (2048 bytes):'
,2017-07-26 15:26:43 - DEBUG testThaliMobileNative: 'Server received (2048 bytes):'
,2017-07-26 15:26:43 - DEBUG testThaliMobileNative: 'Server received (2048 bytes):'
,2017-07-26 15:26:43 - DEBUG testThaliMobileNative: 'Server received (2048 bytes):'
,2017-07-26 15:26:43 - DEBUG testThaliMobileNative: 'Server received (4096 bytes):'
,2017-07-26 15:26:43 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-26 15:26:43 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-26 15:26:43 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-26 15:26:43 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-26 15:26:43 - DEBUG testThaliMobileNative: 'Server received (6144 bytes):'
,2017-07-26 15:26:43 - DEBUG testThaliMobileNative: 'Server received (10240 bytes):'
,2017-07-26 15:26:43 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-26 15:26:43 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-26 15:26:43 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-26 15:26:43 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-26 15:26:43 - DEBUG testThaliMobileNative: 'Server received (9855 bytes):'
,2017-07-26 15:26:43 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-26 15:26:43 - DEBUG testThaliMobileNative: 'Server received (2149 bytes):'
,2017-07-26 15:26:43 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-26 15:26:43 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-26 15:26:43 - DEBUG testThaliMobileNative: 'Server data flushed',
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:5
[ThaliCore] VirtualSocket.closeStreams() vsID:5
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:5
[ThaliCore] VirtualSocket.deinit vsID:5 [1, 4, 6, 7]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:6
,[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:6
,[ThaliCore] VirtualSocket.deinit vsID:6 [1, 4, 7]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:7
[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C0524482-9D20-4396-9724-B784620F79E6
,[ThaliCore] Session.session(_:peer:didChange:) peer:C0524482-9D20-4396-9724-B784620F79E6 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C0524482-9D20-4396-9724-B784620F79E6
[ThaliCore] Session.startOutputStream(with:) peer:C0524482-9D20-4396-9724-B784620F79E6
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8, [1, 4, 7, 8]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C0524482-9D20-4396-9724-B784620F79E6
[ThaliCore] Session.startOutputStream(with:) peer:C0524482-9D20-4396-9724-B784620F79E6
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9, [1, 4, 7, 8, 9]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C0524482-9D20-4396-9724-B784620F79E6
[ThaliCore] Session.startOutputStream(with:) peer:C0524482-9D20-4396-9724-B784620F79E6
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [1, 4, 7, 8, 9, 10]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-26 15:26:46 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-26 15:26:46 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-26 15:26:46 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-26 15:26:46 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-26 15:26:46 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-26 15:26:47 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-26 15:26:47 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-26 15:26:47 - DEBUG testThaliMobileNative: 'Server received (5475 bytes):'
2017-07-26 15:26:47 - DEBUG testThaliMobileNative: 'Server received (3244 bytes):'
2017-07-26 15:26:47 - DEBUG testThaliMobileNative: 'Server received all data: Z9MvUOvuO9,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,Z,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'
2017-07,-26 15:26:47 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-26 15:26:47 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-26 15:26:47 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
2017-07-26 15:26:47 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-26 15:26:47 - DEBUG testThaliMobileNative: 'Server sends data back to client (1638,4 bytes):'
2017-07-26 15:26:47 - DEBUG testThaliMobileNative: 'Server data flushed'
2017-07-26 15:26:47 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-26 15:26:47 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-26 15:26:47 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-26 15:26:47 - DEBUG testThaliMobileNative: 'Server data flushe,d'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:8
[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:8
[ThaliCore] VirtualSocket.deinit vsID:8 [1, 4, 7, 9, 10]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:9
[ThaliCore] VirtualSocket.closeStreams() vsID:9
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:9
,[ThaliCore] VirtualSocket.deinit vsID:9 [1, 4, 7, 10]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.di,dSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:10
[ThaliCore] VirtualSocket.closeStreams() vsID:10
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:10
[ThaliCore] VirtualSocket.deinit vsID:10 [1, 4, 7]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-26 15:26:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-26 15:26:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
[ThaliCore] VirtualSocket exited RunLoop vsID:4
[ThaliCore] VirtualSocket.deinit vsID:4 [1, 7]
2017-07-26 1,5:26:48 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:26:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:CEA74DD1-9E19-42C5-827A-AEC245524BBC
,2017-07-26 15:26:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:26:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:426C00EC-1CE1-4DA1-851F-9CDEFAD2043E
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61614
[ThaliCore] Session.disconnect() p,eer:426C00EC-1CE1-4DA1-851F-9CDEFAD2043E:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:C0524482-9D20-4396-9724-B784620F79E6 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "CEA74DD1-9E19-42C5-827A-AEC245524BBC", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:C0524482-9D20-4396-9724-B784620F79E6
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:AC695C71-4915-470A-B373-90291BEF1320 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "CEA74DD1-9E19-42C5-827A-AEC245524BBC", generation: 0)
,[ThaliCore] Session.deinit peer:C0524482-9D20-4396-9724-B784620F79E6
,[ThaliCore] Session.deinit peer:426C00EC-1CE1-4DA1-851F-9CDEFAD2043E:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-26 15:26:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-26 15:26:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-26 15:26:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:26:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:26:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:26:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:26:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:26:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "ACCCCDA0-56FC-4073-BDCB-B144AD313CF5", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:ACCCCDA0-56FC-4073-BDCB-B144AD313CF5
,2017-07-26 15:26:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-26 15:26:48 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:26:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 97 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3620668C-D9C3-430F-B6B7-3FBA900A,10BE
[ThaliCore] Browser.startListening
,2017-07-26 15:26:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-26 15:26:48 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-26 15:26:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:426C00EC-1CE1-4DA1-851F-9CDEFAD2043E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "426C00EC-1CE1-4DA1-851F-9CDEFAD2043E", generation: 0)
2017-07-26 15:26:49 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"426C00EC-1CE1-4DA1-851F-9CDEFAD2043E","generation":0}'
2017-07-26 15:26:49 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 426C00EC-1CE1-4DA1-851F-9CDEFAD2043E, (syncValue: GONqUkpPrJzQYWhH2e2i7K8os0zEt5ys)'
2017-07-26 15:26:49 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "426C00EC-1CE1-4DA1-851F-9CDEFAD,2043E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "426C00EC-1CE1-4DA1-851F-9CDEFAD2043E", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:426C00EC-1CE1-4DA1-851F-9CDEFAD2043E:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4E65AFCB-31AE-4C2A-AB9E-05D327D66222:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4E65AFCB-31AE-4C2A-AB9E-05D327D66222",, generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-26 15:26:49 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable,":true,"peerIdentifier":"4E65AFCB-31AE-4C2A-AB9E-05D327D66222","generation":0}'
2017-07-26 15:26:49 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 15:26:49 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1", generation: 0)
2017-07-26 15:26:50 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1","generation":0}'
2017-07-26 15:26:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 15:26:50 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-26 15:26:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ACCCCDA0-56FC-4073-BDCB-B144AD313CF5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ACCCCDA0-56FC-4073-BDCB-B144AD313CF5", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1F9CF035-7C79-49E4-8780-3D74C1CE7552:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1F9CF035-7C79-49E4-8780-3D74C1CE7552", generation: 0)
2017-07-26 15:26:50 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"1F9CF035-7C79-49E4-8780-3D74C1CE7552","generation":0}'
2017-07-26 15:26:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 15:26:50 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-26 15:26:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 15:26:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:426C00EC-1CE1-4DA1-851F-9CDEFAD2043E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:42,6C00EC-1CE1-4DA1-851F-9CDEFAD2043E:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "426C00EC-1CE1-4DA1-851F-9CDEFAD2043E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,26C00EC-1CE1-4DA1-851F-9CDEFAD2043E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "426C00EC-1CE1-4DA1-851F-9CDEFAD2043E", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:426C00EC-1CE1-4DA1-851F-9CDEFAD2043E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:426C00EC-1CE1-4DA1-851F-9CDEFAD2043E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:426C00EC-1CE1-4DA1-851F-9CDEFAD2043E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:426C00EC-1CE1-4DA1-851F-9CDEFAD2043E:0
,[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "426C00EC-1CE1-4DA1-851F-9CDEFAD2043E", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "426C00EC-1CE1-4DA1-851F-9CDEFAD2043E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "42,6C00EC-1CE1-4DA1-851F-9CDEFAD2043E", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:426C00EC-1CE1-4DA1-851F-9CDEFAD2043E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:426C00EC-1CE1-4DA1-851F-9CDEFAD2043E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:426C00EC-1CE1-4DA1-851F-9CDEFAD2043E:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "426C00EC-1CE1-4DA1-851F-9CDEFAD2043E", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:426C00EC-1CE1-4DA1-851F-9CDEFAD2043E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:42,6C00EC-1CE1-4DA1-851F-9CDEFAD2043E:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "426C00EC-1CE1-4DA1-851F-9CDEFAD2043E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,26C00EC-1CE1-4DA1-851F-9CDEFAD2043E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "426C00EC-1CE1-4DA1-851F-9CDEFAD2043E", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-26 15:26:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"GONqUkpPrJzQYWhH2e2i7K8os0zEt5ys","error":"Peer is unavailable",,"portNumber":null}'
2017-07-26 15:26:57 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'GONqUkpPrJzQYWhH2e2i7K8os0zEt5ys', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-26 15:26:57 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-26 15:26:57 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4E65AFCB-31AE-4C2A-AB9E-05D327D66222 (syncValue: SYD64cXOaqQMIP7VHgUmLsE,DfeGaaIGW)'
2017-07-26 15:26:57 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4E65AFCB-31AE-4C2A-AB9E-05D327D66222", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4E65AFCB-31AE-4C2A-AB9E-05D327D66222", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4E65AFCB-31AE-4C2A-AB9E-05D32,7D66222:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-26 15:26:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 ,1,5:26:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:426C00EC-1CE1-4DA1-851F-9CDEFAD2043E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:4E65AFCB-31AE-4C2A-AB9E-05D327D66222:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4E,65AFCB-31AE-4C2A-AB9E-05D327D66222:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "4E65AFCB-31AE-4C2A-AB9E-05D327D66222", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,E65AFCB-31AE-4C2A-AB9E-05D327D66222", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4E65AFCB-31AE-4C2A-AB9E-05D327D66222", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:4E65AFCB-31AE-4C2A-AB9E-05D327D66222:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4E65AFCB-31AE-4C2A-AB9E-05D327D66222:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:909C9F79-A6F9-4BE4-8694-3AE62B5FD28A
[ThaliCore] Advertiser: session connected Peer(uuid: "ACCCCDA0-56FC-4073-BDCB-B144AD313CF5", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:909C9F79-A6F9-4BE4-8694-3AE62B5FD28A state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:4E65AFCB-31AE-4C2A-AB9E-05D327D66222:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4E,65AFCB-31AE-4C2A-AB9E-05D327D66222:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "4E65AFCB-31AE-4C2A-AB9E-05D327D66222", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,E65AFCB-31AE-4C2A-AB9E-05D327D66222", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4E65AFCB-31AE-4C2A-AB9E-05D327D66222", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:4E65AFCB-31AE-4C2A-AB9E-05D327D66222:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4E65AFCB-31AE-4C2A-AB9E-05D327D66222:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:909C9F79-A6F9-4BE4-8694-3AE62B5FD28A
,[ThaliCore] Session.session(_:peer:didChange:) peer:909C9F79-A6F9-4BE4-8694-3AE62B5FD28A state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:909C9F79-A6F9-4BE4-8694-3AE62B5FD28A
[ThaliCore] Session.startOutputStream(with:) peer:909C9F79-A6F9-4BE4-8694-3AE62B5FD28A
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [1, 7, 11]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-07-26 15:27:05 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-26 15:27:05 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-26 15:27:05 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-26 15:27:05 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-26 15:27:05 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:11
[ThaliCore] VirtualSocket.closeS,treams() vsID:11
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:11
,[ThaliCore] VirtualSocket.deinit vsID:11 [1, 7]
,[ThaliCore] Session.session(_:peer:didChange:) peer:4E65AFCB-31AE-4C2A-AB9E-05D327D66222:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4E,65AFCB-31AE-4C2A-AB9E-05D327D66222:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "4E65AFCB-31AE-4C2A-AB9E-05D327D66222", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,E65AFCB-31AE-4C2A-AB9E-05D327D66222", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4E65AFCB-31AE-4C2A-AB9E-05D327D66222", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:4E65AFCB-31AE-4C2A-AB9E-05D327D66222:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4E65AFCB-31AE-4C2A-AB9E-05D327D66222:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:4E65AFCB-31AE-4C2A-AB9E-05D327D66222:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "4E65AFCB-31AE-4C2A-AB9E-05D327D66222", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:4E65AFCB-31AE-4C2A-AB9E-05D327D66222:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4E,65AFCB-31AE-4C2A-AB9E-05D327D66222:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "4E65AFCB-31AE-4C2A-AB9E-05D327D66222", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:4E65AFCB,-31AE-4C2A-AB9E-05D327D66222 error: max retries exceeded
2017-07-26 15:27:08 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"SYD64cXOaqQMIP7VHgUmLsEDfeGaaIGW","error":"Connection could not be established","portNumber":null}'
2017-0,7-26 15:27:08 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'SYD64cXOaqQMIP7VHgUmLsEDfeGaaIGW', error: 'Connection could not be established', listeningPort: '%s''
2017-07-26 15:27:08 - ERROR thaliMobileNativeTestUtils: 'Fatal ,c,onnect error: 'Connection could not be established''
2017-07-26 15:27:08 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1 (syncValue: cs2c2MxW63JDwnpcYb3P19A5eRljI2PE)'
2017-07-26 15:27:08 - DEBUG thaliMo,bileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:s,essionConnected:sessionNotConnected:) Peer(uuid: "46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0
[ThaliCore] BrowserRelay.init(session,:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-26 15:27:08 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 15:27:08 - DEBUG thaliMobileNativeTestUtils: 'Al,r,eady running test!'
,[ThaliCore] Session.deinit peer:4E65AFCB-31AE-4C2A-AB9E-05D327D66222:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61645
2017-07-26 15:27:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"cs2c2MxW63JDwnpcYb3P19A5eRljI2PE",,"error":null,"portNumber":61645}'
2017-07-26 15:27:11 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'cs2c2MxW63JDwnpcYb3P19A5eRljI2PE', error: 'null', listeningPort: '61645''
,Connecting to the localhost:61645
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [1, 7, 12]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:61645
,2017-07-26 15:27:11 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-26 15:27:11 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 99 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:12
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:12
[ThaliCore] VirtualSocket.deinit vsID:12 [1, 7]
,# teardown
,2017-07-26 15:27:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-26 15:27:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-26 15:27:11 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-26 15:27:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:ACCCCDA0-56FC-4073-BDCB-B144AD313CF5
,2017-07-26 15:27:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:27:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61645
[ThaliCore] Session.disconnect() peer:46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-26 15:27:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-26 15:27:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-26 15:27:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:27:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:27:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:27:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-26 15:27:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:27:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:909C9F79-A6F9-4BE4-8694-3AE62B5FD28A state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "ACCCCDA0-56FC-4073-BDCB-B144AD313CF5", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:909C9F79-A6F9-4BE4-8694-3AE62B5FD28A
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:909C9F79-A6F9-4BE4-8694-3AE62B5FD28A
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8FBD35BB-A103-436A-9CB9-3B7507AA53AB", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:8FBD35BB-A103-436A-9CB9-3B7507AA53AB
,2017-07-26 15:27:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-26 15:27:13 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:27:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 100 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F884C464-2B85-430E-A2D4-FB4175AE796B
[ThaliCore] Browser.startListening
,2017-07-26 15:27:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-26 15:27:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-26 15:27:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1", generation: 0)
2017-07-26 15:27:13 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1","generation":0}'
2017-07-26 15:27:13 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1, (syncValue: w2v7fLHFerRp0DGelvD0N22Y5z5QX1e5)'
2017-07-26 15:27:13 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "46249FE6-A2BF-4D4C-9A03-DFBFF28,38CA1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1F9CF035-7C79-49E4-8780-3D74C1CE7552:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1F9CF035-7C79-49E4-8780-3D74C1CE7552",, generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-26 15:27:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable,":true,"peerIdentifier":"1F9CF035-7C79-49E4-8780-3D74C1CE7552","generation":0}'
2017-07-26 15:27:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 15:27:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8FBD35BB-A103-436A-9CB9-3B7507AA53AB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8FBD35BB-A103-436A-9CB9-3B7507AA53AB", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:83EC259A-93F4-41CE-9EE5-01F8A89A9E61:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "83EC259A-93F4-41CE-9EE5-01F8A89A9E61", generation: 0)
2017-07-26 15:27:14 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"83EC259A-93F4-41CE-9EE5-01F8A89A9E61","generation":0}'
2017-07-26 15:27:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 15:27:14 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-26 15:27:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BF9402D3-086D-4F63-9EE4-355E475E1C1F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BF9402D3-086D-4F63-9EE4-355E475E1C1F", generation: 0)
2017-07-26 15:27:14 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BF9402D3-086D-4F63-9EE4-355E475E1C1F","generation":0}'
2017-07-26 15:27:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 15:27:14 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-26 15:27:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 15:27:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4E65AFCB-31AE-4C2A-AB9E-05D327D66222:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4E65AFCB-31AE-4C2A-AB9E-05D327D66222", generation: 0)
2017-07-26 15:27:15 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4E65AFCB-31AE-4C2A-AB9E-05D327D66222","generation":0}'
2017-07-26 15:27:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 15:27:15 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-26 15:27:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 15:27:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 15:27:15 - DEBUG thaliMobileNativeTestU,tils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:1F9CF035-7C79-49E4-8780-3D74C1CE7552:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "1F9CF035-7C79-49E4-8780-3D74C1CE7552", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:46,249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,6249FE6-A2BF-4D4C-9A03-DFBFF2838CA1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:46,249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,6249FE6-A2BF-4D4C-9A03-DFBFF2838CA1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:46,249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,6249FE6-A2BF-4D4C-9A03-DFBFF2838CA1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:46,249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:46249FE6,-A2BF-4D4C-9A03-DFBFF2838CA1 error: max retries exceeded
2017-07-26 15:27:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"w2v7fLHFerRp0DGelvD0N22Y5z5QX1e5","error":"Connection could not be established","portNumber":null}'
2017-0,7-26 15:27:24 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'w2v7fLHFerRp0DGelvD0N22Y5z5QX1e5', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-26 15:27:24 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-26 15:27:24 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 83EC259A-93F4-41CE-9EE5-01F8A89A9E61 (syncValue: uQmhP4o,USILToGIjQpOlGWZcVKH7lNOO)'
2017-07-26 15:27:24 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "83EC259A-93F4-41CE-9EE5-01F8A89A9E61", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "83EC259A-93F4-41CE-9EE5-01F8A89A9E61", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:83EC259A-93F4,-41CE-9EE5-01F8A89A9E61:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-26 15:27:24 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-07-26 15:27:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 15:27:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:46249FE6-A2BF-4D4C-9A03-DFBFF2838CA1:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3EA1D45F-6560-40AE-83BD-505FC26AB9D4
[ThaliCore] Advertiser: session connected Peer(uuid: "8FBD35BB-A103-436A-9CB9-3B7507AA53AB", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:3EA1D45F-6560-40AE-83BD-505FC26AB9D4 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2D69FF67-E20B-4C6E-B51F-63271D0691E5
[ThaliCore] Advertiser: session connected Peer(uuid: "8FBD35BB-A103-436A-9CB9-3B7507AA53AB", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:2D69FF67-E20B-4C6E-B51F-63271D0691E5 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:83EC259A-93F4-41CE-9EE5-01F8A89A9E61:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2D69FF67-E20B-4C6E-B51F-63271D0691E5
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:83EC259A-93F4-41CE-9EE5-01F8A89A9E61:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:83EC259A-93F4-41CE-9EE5-01F8A89A9E61:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "83EC259A-93F4-41CE-9EE5-01F8A89A9E61", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61661
,2017-07-26 15:27:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"uQmhP4oUSILToGIjQpOlGWZcVKH7lNOO","error":null,"portNumber":61661}'
2017-07-26 15:27:27 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'uQmhP4oUSILToGIjQpOlGWZcVKH7lNOO', error: 'null', listeningPort: '61661''
,Connecting to the localhost:61661
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:83EC259A-93F4-41CE-9EE5-01F8A89A9E61:0
,Connected to the localhost:61661
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3EA1D45F-6560-40AE-83BD-505FC26AB9D4
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:83EC259A-93F4-41CE-9EE5-01F8A89A9E61:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [1, 7, 13]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:peer:didChange:) peer:3EA1D45F-6560-40AE-83BD-505FC26AB9D4 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3EA1D45F-6560-40AE-83BD-505FC26AB9D4
[ThaliCore] Session.startOutputStream(with:) peer:3EA1D45F-6560-40AE-83BD-505FC26AB9D4
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [1, 7, 13, 14]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (6570 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (5475 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (3214 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (4451 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (931 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:14
[ThaliCore] VirtualSocket.closeStreams() vsID:14
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:14
,[ThaliCore] VirtualSocket.deinit vsID:14 [1, 7, 13]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didS,ocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:2D69FF67-E20B-4C6E-B51F-63271D0691E5 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2D69FF67-E20B-4C6E-B51F-63271D0691E5
[ThaliCore] Session.startOutputStream(with:) peer:2D69FF67-E20B-4C6E-B51F-63271D0691E5
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [1, 7, 13, 15]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (3072 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (2048 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (2048 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (3072 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (5120 bytes):'
,ok 102 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pe,er})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:13
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (6611 bytes):'
[ThaliCore] VirtualSocket exited RunLoop vsID:13
# teardown
[ThaliCore] VirtualSocket.deinit, vsID:13 [1, 7, 15]
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (8760 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (16425 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received (17356 bytes):'
,2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-26 15:27:27 - DEBUG testThaliMobileNative: 'Server data flushed',
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:15
[ThaliCore] VirtualSocket.closeStreams() vsID:15
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-26 15:27:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-26 15:27:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-26 15:27:28 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:27:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:8FBD35BB-A103-436A-9CB9-3B7507AA53AB
,2017-07-26 15:27:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:27:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:83EC259A-93F4-41CE-9EE5-01F8A89A9E61
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61661
[ThaliCore] Session.disconnect,() peer:83EC259A-93F4-41CE-9EE5-01F8A89A9E61:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:2D69FF67-E20B-4C6E-B51F-63271D0691E5 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "8FBD35BB-A103-436A-9CB9-3B7507AA53AB", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:2D69FF67-E20B-4C6E-B51F-63271D0691E5
,[ThaliCore] Session.deinit peer:83EC259A-93F4-41CE-9EE5-01F8A89A9E61:0
[ThaliCore] BrowserRelay.deinit
2017-07-26 15:27:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-26 15:27:28 - DEBUG thaliMobileNat,iveWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-26 15:27:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:3EA1D45F-6560-40AE-83BD-505FC26AB9D4 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "8FBD35BB-A103-436A-9CB9-3B7507AA53AB", generation: 0)
,2017-07-26 15:27:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-26 15:27:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:27:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:27:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-07-26 15:27:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
[ThaliCore] AdvertiserRelay.deinit
,# setup
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:980BAB1C-BB2C-4850-96C3-461FC0F9CF3C
[ThaliCore] Browser.startListening
2017-07-26 15:27:28 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-26 15:27:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:27:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 103 We should start ,listening fine
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6EF2B7C6-F5B1-4B26-8675-94DED121B6CD", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:6EF2B7C6-F5B1-4B26-8675-94DED121B,6,CD
2017-07-26 15:27:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-26 15:27:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true},) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:27:28 - INFO thaliMobile: 'Filtered out discoveryAdvertising,StateUpdate (was in stopped state).'
ok 104 We should start updating fine
,# teardown
,[ThaliCore] Session.deinit peer:2D69FF67-E20B-4C6E-B51F-63271D0691E5
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4E65AFCB-31AE-4C2A-AB9E-05D327D66222:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4E65AFCB-31AE-4C2A-AB9E-05D327D66222", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:83EC259A-93F4-41CE-9EE5-01F8A89A9E61:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "83EC259A-93F4-41CE-9EE5-01F8A89A9E61", generation: 0)
,2017-07-26 15:27:29 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"4E65AFCB-31AE-4C2A-AB9E-05D327D66222","generation":0}]'
2017-07-26 15:27:29 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"4E65AFCB-31AE-4C2A-AB9E-05D327D66222","generation":0}'
2017-07-26 15:27:29 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-26 15:27:29 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"83EC259A-93F4-41CE-9EE5-01F8A89A9E61","generation":0}]'
,2017-07-26 15:27:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"83EC259A-93F4-41CE-9EE5-01F8A89A9E61","generation":0}'
,2017-07-26 15:27:29 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F5E673DA-CC95-4DE6-A149-C189F65599D6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F5E673DA-CC95-4DE6-A149-C189F65599D6", generation: 0)
2017-07-26 15:27:29 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F5E673DA-CC95-4DE6-A149-C189F65599D6","generation":0}]'
2017-07-26 15:27:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"F5E673DA-CC95-4DE6-A149-C189F65599D6","generation":0}'
2017-07-26 15:27:29 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6EF2B7C6-F5B1-4B26-8675-94DED121B6CD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6EF2B7C6-F5B1-4B26-8675-94DED121B6CD", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:83EC259A-93F4-41CE-9EE5-01F8A89A9E61:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "83EC259A-93F4-41CE-9EE5-01F8A89A9E61", generation: 0)
2017-07-26 15:27:32 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"83EC259A-93F4-41CE-9EE5-01F8A89A9E61","generation":0}]'
2017-07-26 15:27:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"83EC259A-93F4-41CE-9EE5-01F8A89A9E61","generation":0}'
2017-07-26 15:27:32 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-26 15:27:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-26 ,15:27:33 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-26 15:27:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:6EF2B7C6-F5B1-4B26-8675-9,4DED121B6CD
2017-07-26 15:27:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:27:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
2017-07-26 15:27:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-26 15:27:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07,-26 15:27:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:27:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:27:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:27:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:27:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:27:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Test updating advertising and parallel data transfer
,2017-07-26 15:27:33 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-26 15:27:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:27:34 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-26 15:27:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-26 15:27:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-26 15:27:34 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-26 15:27:34 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-26 15:27:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:27:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-26 15:27:34 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-26 15:27:34 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-26 15:27:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-26 15:27:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:67DBBED1-E236-4FE7-B03D-C2478E11FB76
[ThaliCore] Browser.startListening
,ok 105 discoveryActive should be false
ok 106 advertisingActive should be true
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5B6F88C2-0B7C-4834-813F-00E53BBC94AD", generation: 0)
[ThaliCore] Advertise,r.startAdvertising with peerID:5B6F88C2-0B7C-4834-813F-00E53BBC94AD
ok 107 discoveryActive should be false
ok 108 advertisingActive should be true
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
ok 109 d,iscoveryActive should be false
ok 110 advertisingActive should be true
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:5B6F88C2-0B7C-4834-813F-00E53BBC94AD
ok 111 discoveryActive should be false
ok 112 a,dvertisingActive should be true
ok 113 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-26 15:27:34 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-26 15:27:34 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-26 15:27:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:27:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-26 15:27:34 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-26 15:27:34 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-26 15:27:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-26 15:27:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-07-26 15:27:34 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-26 15:27:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:27:34 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 114 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-26 15:27:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:27:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 115 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-26 15:27:34 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-26 15:27:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:27:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 116 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-26 15:27:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:27:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 117 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-26 15:27:35 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-26 15:27:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:27:35 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 118 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-26 15:27:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:27:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 119 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-26 15:27:35 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-26 15:27:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:27:35 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-26 15:27:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:27:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-26 15:27:35 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 122 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 123 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-26 15:27:36 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:27:36 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 124 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 125 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 126 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:cfa895f1-3746-4c95-ac0a-a2836a0c62a3 error: startListeningNotActive
2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1bKbBUtWfCxiP3,CNaU9CeROyNuHOgvis","error":"startListeningForAdvertisements is not active","portNumber":null}'
ok 127 Should only get called after multiConnect returned
ok 128 SyncValue matches
ok 129 Got right error
ok 130 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:27:36 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-26 15:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:27:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:37357929-2B4F-4277-80F3-BCBA97CC7F39
[ThaliCore] Browser.startListening
,2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-26 15:27:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 131 No error on starting
ok 132 Got null as expected
2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"UyoDXmspKGVF21ag7CfykazNdsi0cWu9","error":"Illegal peerID","portNumber",:null}'
ok 133 Should only get called after multiConnect returned
ok 134 SyncValue matches
ok 135 Got right error
ok 136 listeningPort is null
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4E65AFCB-31AE-4C2A-AB9E-05D327D66222:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4E65AFCB-31AE-4C2A-AB9E-05D327D66222", generation: 0)
,2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"4E65AFCB-31AE-4C2A-AB9E-05D327D66222","generation":0}]'
,2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"4E65AFCB-31AE-4C2A-AB9E-05D327D66222","generation":0}'
,2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-26 15:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:27:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:27:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# multiConnect properly fails on legal but non-existent peerID
,2017-07-26 15:27:37 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-26 15:27:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:27:37 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-26 15:27:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-26 15:27:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-26 15:27:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-26 15:27:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-26 15:27:37 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:27:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-26 15:27:37 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-26 15:27:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-26 15:27:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-26 15:27:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:95068E28-9557-4F38-849F-6577CAA9B961
[ThaliCore] Browser.startListening
2017-07-26 15:27:37 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-26 15:27:37 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-26 15:27:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 137 No error on starting
ok 138 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-26 15:27:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26, 15:27:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-26 15:27:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-07-26 15:27:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-26 15:27:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-26 15:27:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-26 15:27:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:27:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:27:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:27:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:27:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:27:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call disconnect with invalid peer id
,ok 139 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-26 15:27:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:27:38 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-26 15:27:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-26 15:27:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-26 15:27:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-26 15:27:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-26 15:27:38 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:27:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-26 15:27:38 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-26 15:27:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-26 15:27:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-26 15:27:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:3c67ba37-809a-4416-8e44-161130327dca
ok 140 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-26 15:27:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:27:39 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-26 15:27:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-26 15:27:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-26 15:27:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-26 15:27:39 - DEBUG t,haliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-26 15:27:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:27:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-26 15:27:39 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-26 15:27:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-26 15:27:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-26 15:27:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "85616D03-A4E2-454E-A6D7-D1E511D69A3B", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:85616D03-A4E2-454E-A6D7-D1E511D69A3B
2017-07-26 1,5:27:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-26 15:27:39 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:27:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 141 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:807C7783-98F3-4BE0-A1E7-0746FC108957
[Tha,l,iCore] Browser.startListening
2017-07-26 15:27:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-26 15:27:39 - INFO thaliMobile: 'Received state ({"discoveryActive":tru,e,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:27:39 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 142 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6C4BE094-B690-45C8-8D11-640C8096028F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6C4BE094-B690-45C8-8D11-640C8096028F", generation: 0)
2017-07-26 15:27:40 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6C4BE094-B690-45C8-8D11-640C8096028F","generation":0}'
2017-07-26 15:27:40 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 6C4BE094-B690-45C8-8D11-640C8096028F, (syncValue: 9rqe8h7oIDFc9XGKD6KcDaa4yylfrGaC)'
2017-07-26 15:27:40 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6C4BE094-B690-45C8-8D11-640C809,6028F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6C4BE094-B690-45C8-8D11-640C8096028F", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:6C4BE094-B690-45C8-8D11-640C8096028F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4DF3451B-80F3-4259-BEC0-33FC5EE7ACE2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4DF3451B-80F3-4259-BEC0-33FC5EE7ACE2", generation: 0)
,2017-07-26 15:27:40 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4DF3451B-80F3-4259-BEC0-33FC5EE7ACE2","generation":0}'
,2017-07-26 15:27:40 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-26 15:27:40 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:6C4BE094-B690-45C8-8D11-640C8096028F:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:85616D03-A4E2-454E-A6D7-D1E511D69A3B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "85616D03-A4E2-454E-A6D7-D1E511D69A3B", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6C4BE094-B690-45C8-8D11-640C8096028F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:6C4BE094-B690-45C8-8D11-640C8096028F:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "6C4BE094-B690-45C8-8D11-640C8096028F", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61670
,2017-07-26 15:27:43 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9rqe8h7oIDFc9XGKD6KcDaa4yylfrGaC","error":null,"portNumber":61670}'
,2017-07-26 15:27:43 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '9rqe8h7oIDFc9XGKD6KcDaa4yylfrGaC', error: 'null', listeningPort: '61670''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:6C4BE094-B690-45C8-8D11-640C8096028F:0
,ok 143 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6C4BE094-B690-45C8-8D11-640C8096028F", generation: 0) found active relay
,2017-07-26 15:27:43 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"723h7XCsWewxJ9fG8Y70Vm0rNojtZeGo","error":null,"portNumber":61670}'
,ok 144 No error
,ok 145 Ports equal
,ok 146 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6C4BE094-B690-45C8-8D11-640C8096028F", generation: 0) found active relay
,2017-07-26 15:27:43 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"b54S8tPBvp1YMgYLlsvAaDrhVRfT7siF","error":null,"portNumber":61670}'
,ok 147 No error
,ok 148 Ports equal
,# teardown
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6C4BE094-B690-45C8-8D11-640C8096028F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [1, 7, 15, 16]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:16
[ThaliCore] VirtualSocket.closeStreams() vsID:16
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] TCPListener.socketDidDisconnect(_:withErr,or:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-26 15:27:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-26 15:27:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-26 15:27:49 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:27:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:85616D03-A4E2-454E-A6D7-D1E511D69A3B
2017-07-26 15:27:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"a,dvertisingActive":false}'
2017-07-26 15:27:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:6C4BE094-B690-45C8-8D11-640C8096028F
[ThaliCore] BrowserRelay.closeRelay(,) state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61670
[ThaliCore] Session.disconnect() peer:6C4BE094-B690-45C8-8D11-640C8096028F:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socke,t error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:6C4BE094-B690-45C8-8D11-640C8096028F:0
,2017-07-26 15:27:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-26 15:27:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-26 15:27:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:27:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:27:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:27:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:27:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:27:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# initial peer discovery
,2017-07-26 15:27:50 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-07-26 15:27:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-26 15:27:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-26 15:27:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:27:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-26 15:27:50 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-26 15:27:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-26 15:27:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-26 15:27:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-07-26 15:27:50 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-07-26 15:27:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-26 15:27:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-26 15:27:50 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:27:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-26 15:27:50 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-26 15:27:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-26 15:27:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-26 15:27:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-07-26 15:27:51 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-07-26 15:27:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-26 15:27:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-26 15:27:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:27:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-26 15:27:51 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-26 15:27:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-26 15:27:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-26 15:27:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-07-26 15:27:51 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-07-26 15:27:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-26 15:27:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-26 15:27:51 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:27:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-26 15:27:51 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-26 15:27:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-26 15:27:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-26 15:27:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-07-26 15:27:51 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-07-26 15:27:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-26 15:27:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-26 15:27:51 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:27:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-26 15:27:51 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-26 15:27:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-26 15:27:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-26 15:27:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-07-26 15:27:52 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-07-26 15:27:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-26 15:27:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-26 15:27:52 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-26 15:27:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-26 15:27:52 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-26 15:27:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-26 15:27:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-26 15:27:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-26 15:27:52 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-26 15:27:52 - DEBUG createNativeListener: 'listening 61673'
ok 149 Should throw
,# teardown
,2017-07-26 15:27:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-26 15:27:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-26 15:27:52 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-26 15:27:52 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-26 15:27:52 - DEBUG createNativeListener: 'listening 61675'
,2017-07-26 15:27:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-26 15:27:52 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 150 initial connection state should be CONNECTED
,2017-07-26 15:27:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 151 final connection state should be DISCONNECTED
,# teardown
,2017-07-26 15:27:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-26 15:27:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-26 15:27:53 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-07-26 15:27:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-26 15:27:53 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'listening 61678'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-26 15:27:53 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
ok 152 tried to connect to right port
ok 153 failed due to refused connection
ok 154 routerPortConnectionFailed is emitted
,# teardown
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-26 15:27:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-26 15:27:53 - DEBUG createNativeListener: 'Native Server - close'
2017-07-26 15:27:53 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <,-> Mux - 0 - close'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'listening 61682'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-26 15:27:53 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2017-07-26 15:27:53 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 155 Send/recvd #1 should be equal length
,ok 156 Send/recvd #1 should be same
,ok 157 Send/recvd #2 should be equal length
,ok 158 Send/recvd #2 should be same
,ok 159 Should be exactly 2 client sockets
,# teardown
,2017-07-26 15:27:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-26 15:27:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-26 15:27:53 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-07-26 15:27:54 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-26 15:27:54 - DEBUG createNativeListener: 'listening 61687'
,2017-07-26 15:27:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-26 15:27:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-26 15:27:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-26 15:27:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2017-07-26 15:27:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 160 socket shouldn't close until after stream
ok 161 incoming remains open
# teardown
,2017-07-26 15:27:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-26 15:27:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-26 15:27:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-26 15:27:54 - DEBUG createNativeListener: 'Native Server - close'
2017-07-26 15:27:54, - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-26 15:27:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-07-26 15:27:54 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-26 15:27:54 - DEBUG createNativeListener: 'listening 61691'
,2017-07-26 15:27:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-26 15:27:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 162 we should not have gotten an error
,2017-07-26 15:27:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-26 15:27:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-07-26 15:27:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - cl,ose'
,ok 163 socket shouldn't close until after incoming
ok 164 incoming is cleaned up
# teardown
,2017-07-26 15:27:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-26 15:27:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-26 15:27:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-26 15:27:54 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-26 15:27:54 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-26 15:27:54 - DEBUG createNativeListener: 'listening 61695'
,2017-07-26 15:27:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-26 15:27:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-26 15:27:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-26 15:27:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2017-07-26 15:27:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-07-26 15:27:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 165 stream was closed
ok 166 incoming should survive
ok 167 mux should have no streams
,# teardown
,2017-07-26 15:27:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-26 15:27:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-26 15:27:55 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-07-26 15:27:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'listening 61699'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-26 15:27:55 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 168 we should not have gotten an error
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 169 Buffers are identical
2017-07-26 15:27:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-26 15:27:55 - DEBUG createNativeListener: 'Native Server - close'
2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream, <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-07-26 15:27:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 170 native server is nulled out
ok 171 native server should be cl,osed
ok 172 incoming has been removed
ok 173 Incoming should be done
ok 174 The mux object should be closed
ok 175 The mux stream should be closed
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
2017-07-26 15:27:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-26 15:27:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'listening 61703'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-26 15:27:55 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-07-26 15:27:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
2017-07-26 15:27:55 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
,2017-07-26 15:27:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-26 15:27:55 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 176 native server is nulled out
,ok 177 native server should be closed
,ok 178 incoming has been removed
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-26 15:27:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-26 15:27:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-07-26 15:27:57 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-26 15:27:57 - DEBUG createNativeListener: 'listening 61755'
,2017-07-26 15:27:57 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-26 15:27:57 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 179 we should not have gotten an error
,2017-07-26 15:27:57 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 180 Buffers are identical
2017-07-26 15:27:57 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-07-26 15:27:57 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client co,nnection <-> Mux - 0 - close'
,2017-07-26 15:27:57 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 181 server should be fine
ok 182 server should be open
ok 183 incoming has been removed
ok 184 The mux object should be clos,ed
ok 185 The mux stream should be closed
2017-07-26 15:27:57 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-26 15:27:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-26 15:27:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-26 15:27:57 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-26 15:27:57 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-26 15:27:57 - DEBUG createNativeListener: 'listening 61759'
,2017-07-26 15:27:57 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-26 15:27:57 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 186 we should not have gotten an error
,2017-07-26 15:27:57 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 187 Buffers are identical
,2017-07-26 15:27:57 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
,2017-07-26 15:27:57 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-26 15:27:57 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-26 15:27:57 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 188 server should be fine
,ok 189 server should be open
,ok 190 incoming has been removed
,ok 191 The mux object should be closed
,ok 192 The mux stream should be closed
,# teardown
,2017-07-26 15:27:57 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-26 15:27:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-26 15:27:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-26 15:27:58 - DEBUG createNativeListener: 'Native Server - close'
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
,2017-07-26 15:27:58 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-26 15:27:58 - DEBUG createNativeListener: 'listening 61762'
ok 196 port must be in range
,# teardown
,2017-07-26 15:27:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-26 15:27:58 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-26 15:27:58 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-26 15:27:58 - DEBUG createNativeListener: 'listening 61763'
ok 197 second start should return same port
,# teardown
,2017-07-26 15:27:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-26 15:27:58 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-26 15:27:59 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-26 15:27:59 - DEBUG createNativeListener: 'listening 61765'
,2017-07-26 15:27:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-26 15:27:59 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 198 we should be connected
2017-07-26 15:27:59 - DEB,UG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 199 now we are disconnected
,2017-07-26 15:27:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-26 15:27:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-26 15:27:59 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-07-26 15:27:59 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
,ok 200 Passed bogus id
2017-07-26 15:27:59 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
ok 201 Passed good id but bogus port
2017-07-26 15:27:59 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
ok 202 Passed right context
ok 203 Right server
ok 204 No error should be set
ok 205 Retry should be false
ok 206 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 61767
,ok 207 should be equal
# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-26 15:27:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-26 15:27:59 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-26 15:27:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-26 15:27:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-26 15:27:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-26 15:27:59 - DEBUG thaliMobileNativeWrapper: 'Me,thod peerAvailabilityChanged registered to native'
2017-07-26 15:27:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-26 15:27:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolv,e,d registered to native'
,2017-07-26 15:27:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-26 15:27:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-26 15:27:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-26 15:27:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-26 15:27:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "34B62C2A-F0EA-47B5-919A-775C72B2336C", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:34B62C2A-F0EA-47B5-919A-775C72B2336C
2017-07-26 1,5:28:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-26 15:28:00 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:28:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 208 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:918FA0EB-D427-4759-8534-4F28BA1762FA
[Tha,liCore] Browser.startListening
2017-07-26 15:28:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-26 15:28:00 - INFO thaliMobile: 'Received state ({"discoveryActive":tr,ue,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-26 15:28:00 - INFO thaliMobile: 'Filte,red out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 209 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4DF3451B-80F3-4259-BEC0-33FC5EE7ACE2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4DF3451B-80F3-4259-BEC0-33FC5EE7ACE2", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6C4BE094-B690-45C8-8D11-640C8096028F:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6C4BE094-B690-45C8-8D11-640C8096028F", generation: 0)
,2017-07-26 15:28:00 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4DF3451B-80F3-4259-BEC0-33FC5EE7ACE2","generation":0}'
,2017-07-26 15:28:00 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4DF3451B-80F3-4259-BEC0-33FC5EE7ACE2 (syncValue: jtzdIZOxaOmVqgpbvXLqH4Fv0VPV3fzt)'
,2017-07-26 15:28:00 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4DF3451B-80F3-4259-BEC0-33FC5EE7ACE2", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4DF3451B-80F3-4259-BEC0-33FC5EE7ACE2", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4DF3451B-80F3-4259-BEC0-33FC5EE7ACE2:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-26 15:28:00 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6C4BE094-B690-45C8-8D11-640C8096028F","generation":0}'
,2017-07-26 15:28:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-26 15:28:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:85E620C7-FC44-4A79-A50E-96D2E16AC7DB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "85E620C7-FC44-4A79-A50E-96D2E16AC7DB", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E937297E-E1AB-49DC-8BCB-38DF5390140B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E937297E-E1AB-49DC-8BCB-38DF5390140B", generation: 0)
,2017-07-26 15:28:01 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"85E620C7-FC44-4A79-A50E-96D2E16AC7DB","generation":0}'
,2017-07-26 15:28:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 15:28:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 15:28:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 15,:28:01 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E937297E-E1AB-49DC-8BCB-38DF5390140B","generation":0}'
2017-07-26 15:28:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 15:28:01 -, DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 15:28:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-26 15:28:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:34B62C2A-F0EA-47B5-919A-775C72B2336C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "34B62C2A-F0EA-47B5-919A-775C72B2336C", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:4DF3451B-80F3-4259-BEC0-33FC5EE7ACE2:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4D,F3451B-80F3-4259-BEC0-33FC5EE7ACE2:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "4DF3451B-80F3-4259-BEC0-33FC5EE7ACE2", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,DF3451B-80F3-4259-BEC0-33FC5EE7ACE2", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4DF3451B-80F3-4259-BEC0-33FC5EE7ACE2", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:4DF3451B-80F3-4259-BEC0-33FC5EE7ACE2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4DF3451B-80F3-4259-BEC0-33FC5EE7ACE2:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:4DF3451B-80F3-4259-BEC0-33FC5EE7ACE2:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4D,F3451B-80F3-4259-BEC0-33FC5EE7ACE2:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "4DF3451B-80F3-4259-BEC0-33FC5EE7ACE2", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,DF3451B-80F3-4259-BEC0-33FC5EE7ACE2", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4DF3451B-80F3-4259-BEC0-33FC5EE7ACE2", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:4DF3451B-80F3-4259-BEC0-33FC5EE7ACE2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4DF3451B-80F3-4259-BEC0-33FC5EE7ACE2:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:6C4BE094-B690-45C8-8D11-640C8096028F:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "6C4BE094-B690-45C8-8D11-640C8096028F", generation: 0)
[ThaliCore] Browser.browser(_:lostPeer:) lost peer,:4DF3451B-80F3-4259-BEC0-33FC5EE7ACE2:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "4DF3451B-80F3-4259-BEC0-33FC5EE7ACE2", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:4DF3451B-80F3-4259-BEC0-33FC5EE7ACE2:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4D,F3451B-80F3-4259-BEC0-33FC5EE7ACE2:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "4DF3451B-80F3-4259-BEC0-33FC5EE7ACE2", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,DF3451B-80F3-4259-BEC0-33FC5EE7ACE2", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4DF3451B-80F3-4259-BEC0-33FC5EE7ACE2", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-26 15:28:08 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"jtzdIZOxaOmVqgpbvXLqH4Fv0VPV3fzt","error":"Peer is unavailable",,"portNumber":null}'
2017-07-26 15:28:08 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'jtzdIZOxaOmVqgpbvXLqH4Fv0VPV3fzt', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-26 15:28:08 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-26 15:28:08 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 85E620C7-FC44-4A79-A50E-96D2E16AC7DB (syncValue: AdvJ99GfKDaLG16b6qOijub,JOg8k8dYu)'
2017-07-26 15:28:08 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "85E620C7-FC44-4A79-A50E-96D2E16AC7DB", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "85E620C7-FC44-4A79-A50E-96D2E16AC7DB", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:85E620C7-FC44-4A79-A50E-96D2E,16AC7DB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-26 15:28:08 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:4DF3451B-80F3-4259-BEC0-33FC5EE7ACE2:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:85E620C7-FC44-4A79-A50E-96D2E16AC7DB:0 state: notConnected -> connecting
,2017-07-26 15:28:10 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:85E620C7-FC44-4A79-A50E-96D2E16AC7DB:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:85E620C7-FC44-4A79-A50E-96D2E16AC7DB:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "85E620C7-FC44-4A79-A50E-96D2E16AC7DB", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61779
2017-07-26 15:28:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"AdvJ99GfKDaLG16b6qOijubJOg8k8dYu",,"error":null,"portNumber":61779}'
2017-07-26 15:28:11 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'AdvJ99GfKDaLG16b6qOijubJOg8k8dYu', error: 'null', listeningPort: '61779''
,ok 210 should be equal
2017-07-26 15:28:11 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for E937297E-E1AB-49DC-8BCB-38DF5390140B (syncValue: EdMeUC2X4iCmpmYlHOVMhosx18g68H6s)'
2017-07-26 15:28:11 - DEBUG thaliMobileNativeTestUtils: 'Got 'mul,tiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E937297E-E1AB-49DC-8BCB-38DF5390140B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConn,ected:) Peer(uuid: "E937297E-E1AB-49DC-8BCB-38DF5390140B", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E937297E-E1AB-49DC-8BCB-38DF5390140B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocke,tTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CD2D2900-859F-4060-B1A1-93BBF790160E
[ThaliCore] Advertiser: session connected Peer(uuid: "34B62C2A-F0EA-47B5-919A-775C72B2336C", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:CD2D2900-859F-4060-B1A1-93BBF790160E state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:E937297E-E1AB-49DC-8BCB-38DF5390140B:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:ADD585A6-B453-4207-A436-7E31657DF966
[ThaliCore] Advertiser: session connected Peer(uuid: "34B62C2A-F0EA-47B5-919A-775C72B2336C", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:ADD585A6-B453-4207-A436-7E31657DF966 state: notConnected -> connecting
,2017-07-26 15:28:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:28:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4,FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E937297E-E1AB-49DC-8BCB-38DF5390140B:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:E937297E-E1AB-49DC-8BCB-38DF5390140B:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "E937297E-E1AB-49DC-8BCB-38DF5390140B", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61784
2017-07-26 15:28:14 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"EdMeUC2X4iCmpmYlHOVMhosx18g68H6s",,"error":null,"portNumber":61784}'
2017-07-26 15:28:14 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'EdMeUC2X4iCmpmYlHOVMhosx18g68H6s', error: 'null', listeningPort: '61784''
,ok 211 should be equal
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CD2D2900-859F-4060-B1A1-93BBF790160E
,[ThaliCore] Session.session(_:peer:didChange:) peer:CD2D2900-859F-4060-B1A1-93BBF790160E state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:ADD585A6-B453-4207-A436-7E31657DF966
,[ThaliCore] Session.session(_:peer:didChange:) peer:ADD585A6-B453-4207-A436-7E31657DF966 state: connecting -> connected
,2017-07-26 15:28:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:28:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4,FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:28:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:28:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:28:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:28:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:28:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:28:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:28:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:28:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:29:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:29:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
2017-07-26 15:29:14 - INFO, CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server ,that is not listening yet witheatNotRunning set to true'
2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOG,GER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoi,n,ts plugin delay interval'
2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-07-26 15:29:14 - INFO Coordin,atedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue, and run in order'
2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
2017-07-26 15:,29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
2017-07-26 15:29:14 - INF,O, CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER resu,lt: passed - another'
2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
2017-07-26 15:29:14 - INFO CoordinatedClient: '***T,EST_LOGGER result: passed - test sinon sansbox spy'
2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox ,stub override'
2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
2017-07-26 ,1,5:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiConnect properly fails on legal but non-existent peerID'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with invalid syncValue'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call disconnect with invalid peer id'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - disconnect doesn't fail on plausible but bogus peer ID'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Get same port when trying to connect multiple times on iOS'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - initial peer discovery'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 1'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 2'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - check latest peer discovery'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Set up for no peer discovery test'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - no peer discovery'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits incomingConnectionState'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server connections all up'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can create servers manager'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling stop without start causes error'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can start/stop servers manager'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connection'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single local http request'
,2017-07-26 15:29:14 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - Single coordinated request ios native, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/tim,ers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1
''
,2017-07-26 15:29:14 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-07-26 15:29:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:29:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:29:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:29:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:29:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:29:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:29:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:29:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:29:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:29:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:30:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:30:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4,FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:30:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:30:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:30:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:30:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:30:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:30:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:30:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:30:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:30:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:30:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:31:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:31:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:31:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:31:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:31:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:31:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:31:34 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:350:16
$9@timers.,js:120:1
''
,2017-07-26 15:31:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:31:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:31:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:31:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:31:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:31:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:32:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:32:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:32:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:32:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:32:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:32:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:32:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:32:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:32:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:32:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:32:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:32:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:33:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:33:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:33:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:33:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:33:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:33:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:33:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:33:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:33:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:33:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:33:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:33:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:34:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:34:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:34:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:34:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:34:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:34:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:34:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:34:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:34:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:34:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:34:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:34:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:35:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:35:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:35:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:35:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:35:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:35:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:35:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:35:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:35:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:35:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:35:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:35:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:36:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:36:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:36:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:36:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:36:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:36:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:36:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:36:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:36:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:36:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:36:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:36:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:37:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:37:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:37:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:37:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:37:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:37:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:37:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:37:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:37:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:37:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:38:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:38:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4,FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:38:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:38:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:38:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:38:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:38:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:38:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:38:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:38:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:38:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:38:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:39:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:39:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4,FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:39:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:39:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:39:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:39:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:39:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:39:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:39:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:39:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:39:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:39:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:40:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:40:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:40:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:40:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:40:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:40:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:40:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:40:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:40:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:40:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:40:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:40:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:41:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:41:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:41:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:41:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:41:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:41:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:41:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:41:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:41:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:41:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:41:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:41:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:42:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:42:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:42:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:42:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:42:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:42:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:42:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:42:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:42:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:42:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:42:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:42:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:43:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:43:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:43:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:43:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:43:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:43:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:43:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:43:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:43:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:43:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:43:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:43:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:44:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:44:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:44:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:44:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:44:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:44:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:44:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:44:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-26 15:44:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD,4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:44:43 - ERROR CoordinatedClient: 'reconnect_failed error: 'undefined', description: '%s,',, stack: '%s''
2017-07-26 15:44:43 - DEBUG CoordinatedClient: 'test client failed'
2017-07-26 15:44:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'T,ransport.prototype.onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers,/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxc,ore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7FDF5448-9FED-4FD4-A095-2376EFA355E0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-26 15:,4,4:43 - DEBUG CoordinatedThaliTape: 'all tests succeed'
2017-07-26 15:44:43 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****'

```
