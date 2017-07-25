#### Test 13228325722939a4_iOS_Iphone6sPlus-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/13228325722939a4/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/C7E01A18-336D-42F9-8A6B-BFABF7FCB569/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'
,Executing commands in '/tmp/C7E01A18-336D-42F9-8A6B-BFABF7FCB569/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/13228325722939a4/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/13228325722939a4/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60705"
,(lldb)     command script import "/tmp/C7E01A18-336D-42F9-8A6B-BFABF7FCB569/fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.py"
,(lldb)     command script add -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.safequit_command safequit
(lldb)     connect
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
,2017-07-25 16:21:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-25 16:21:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-25 16:21:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:21:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-25 16:21:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:21:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:21:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F548EADB-2570-4F02-904F-EAD6EAAFD927", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:F548EADB-2570-4F02-904F-EAD6EAAFD927
,Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D116909F-5B83-4C35-8654-AE39C5C59C2E
[ThaliCore] Browser,.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B269531C-18C3-471B-B352-42F5F448A0F5
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C44874BF-B4BD-4362-907B-FA06F0BED5A5", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:C44874BF-B4BD-4362-907B-FA06F0BED5A5
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C44874BF-B4BD-4362-907B-FA06F0BED5A5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C44874BF-B4BD-4362-907B-FA06F0BED5A5", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo,rrect finished
AppContextTests finished
All tests finished
All tests finished
2017-07-25 16:21:45 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of fail,ed tests:  0
Number of ignored tests:  0
Total duration:  1.366419017314911
,2017-07-25 16:21:45 - DEBUG UnitTest_app: 'My device name is: 'Apple-Iphone6sPlus-1''
,2017-07-25 16:21:45 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:C44874BF-B4BD-4362-907B-FA06F0BED5A5:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "C44874BF-B4BD-4362-907B-FA06F0BED5A5", generation: 0)
,2017-07-25 16:21:47 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-25 16:21:47 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-25 16:21:47 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-25 16:21:47 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-25 16:21:47 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-25 16:21:47 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-25 16:21:47 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-25 16:21:47 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-25 16:21:47 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-25 16:21:47 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-25 16:21:47 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-25 16:21:47 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-25 16:21:47 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-25 16:21:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-25 16:21:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-25 16:21:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-25 16:21:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-25 16:21:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-25 16:21:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-25 16:21:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-25 16:21:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-25 16:21:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-25 16:21:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-25 16:21:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-25 16:21:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-25 16:21:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-25 16:21:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-25 16:21:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-25 16:21:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-25 16:21:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-25 16:21:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-25 16:21:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-25 16:21:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-25 16:21:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-25 16:21:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-25 16:21:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-25 16:21:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-25 16:21:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-25 16:21:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-25 16:21:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-25 16:21:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-25 16:21:49 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-25 16:21:49 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-25 16:21:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:21:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:21:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:21:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:21:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:22:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:22:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:22:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:22:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:22:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:22:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:22:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:22:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:22:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:22:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:22:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:22:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:23:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:23:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:23:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:23:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:23:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:23:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:23:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:23:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:23:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:23:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:23:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:23:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:24:03 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-07-25 16:24:03 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-25 16:24:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 1 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll with promise
,2017-07-25 16:24:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-25 16:24:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-07-25 16:24:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-07-25 16:24:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-07-25 16:24:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-07-25 16:24:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-07-25 16:24:10 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
,# teardown
,# setup
,# test defaultDirectory
,ok 4 should be equal
,ok 5 should be equal
ok 6 should be equal
# teardown
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
ok 33 second
,ok 34 secondPromise - in then
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
,2017-07-25 16:24:17 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-07-25 16:24:17 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-07-25 16:24:18 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
,ok 52 test participant has uuid
ok 53 participant data matches
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
,2017-07-25 16:24:21 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-25 16:24:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-25 16:24:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-25 16:24:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:24:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-25 16:24:21 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-25 16:24:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-25 16:24:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-25 16:24:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-25 16:24:21 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-25 16:24:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-25 16:24:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-25 16:24:21 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:24:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-25 16:24:21 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-25 16:24:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-25 16:24:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-25 16:24:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FF199321-94BC-4B37-823F-820AF43824C9
[ThaliCore] Browser.startListening
,2017-07-25 16:24:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-25 16:24:22 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-25 16:24:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-25 16:24:22 - DEBUG thaliMobileNativeWrapper: 'disco,veryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:24:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without e,r,ror
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-25 16:24:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:24:22 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-25 16:24:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-25 16:24:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-25 16:24:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-25 16:24:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-25 16:24:22 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:24:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-25 16:24:22 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-25 16:24:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-25 16:24:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-25 16:24:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C9B3EF5C-8727-4699-91A8-85528A04A401
[ThaliCore] Browser.startListening
,2017-07-25 16:24:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-25 16:24:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-25 16:24:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 64 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-25 16:24:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"di,scoveryActive":true,"advertisingActive":false}'
2017-07-25 16:24:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":",B,OTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-25 16:24:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Can call startListeningForAdvertisements twice without e,rror
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-25 16:24:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25, 16:24:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-25 16:24:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-07-25 16:24:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-25 16:24:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-25 16:24:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-25 16:24:24 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:24:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:24:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:24:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:24:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:24:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-25 16:24:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:24:24 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 66 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-25 16:24:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:24:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-25 16:24:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:24:25 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-25 16:24:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-25 16:24:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-25 16:24:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-25 16:24:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-25 16:24:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:24:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-25 16:24:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-25 16:24:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-25 16:24:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-25 16:24:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E8689646-76DD-4420-8BC9-B83D8F1BA6E1", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:E8689646-76DD-4420-8BC9-B83D8F1BA6E1
2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-25 16:24:26 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-25 16:24:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising(,)
[ThaliCore] Advertiser.stopAdvertising() peerID:E8689646-76DD-4420-8BC9-B83D8F1BA6E1
2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:24:26, - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:24:26 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-25 16:24:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:24:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "119181F7-31E8-492A-A4EE-859BE39CC453", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:119181F7-31E8-492A-A4EE-859BE39CC453
2017-07-25 1,6:24:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-25 16:24:26 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-25 16:24:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 70 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "119181F7-31E8-492A-A4EE-859BE39CC453", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:119181F7-31E8-492A-A4EE-859BE39CC453
2017-07-25 1,6:24:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-25 16:24:26 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-25 16:24:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-25 16:24:26 - INFO thaliMobile: 'Receive,d state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-25 16:2,4:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:119181F7-31E8-492A-A4EE-859BE39CC453
[ThaliCore] Advertiser.s,topAdvertising() peerID:119181F7-31E8-492A-A4EE-859BE39CC453
2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-25 16:24:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-25 16:24:26 - DEBUG thaliMo,bileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:24:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:24:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-25 16:24:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-25 16:24:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 72 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-25 16:24:27 - DEBUG th,aliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:24:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Can call stopAdverti,singAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-25 16:24:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:24:30 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-25 16:24:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-25 16:24:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-25 16:24:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-25 16:24:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-25 16:24:30 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:24:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-25 16:24:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-25 16:24:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:24:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:24:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C1584D9F-F535-451B-BC16-C39558E5F073", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:C1584D9F-F535-451B-BC16-C39558E5F073
2017-07-25 1,6:24:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-25 16:24:31 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-25 16:24:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdv,ertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DC23841D-044A-4F2F-8533-5E7259428DBD
[ThaliCore] Browser.startListening
2017-07-25 16:24:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryA,ctive":true,"advertisingActive":true}'
2017-07-25 16:24:31 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","sta,r,tArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-25 16:24:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0793BEDD-38B1-4AB4-A184-0B8B6241AD5C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0793BEDD-38B1-4AB4-A184-0B8B6241AD5C", generation: 0)
ok 76 peers must be an array,
ok 77 peers must not be zero-length
ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
ok 79 peerIdentifier must be a string
ok 80 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C1584D9F-F535-451B-BC16-C39558E5F073:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C1584D9F-F535-451B-BC16-C39558E5F073", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7B282771-861D-4DFE-84EC-9BD1796CBBD6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7B282771-861D-4DFE-84EC-9BD1796CBBD6", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-25 16:24:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-25 ,16:24:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-25 16:24:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:C1584D9F-F535-451B-BC16-C,39558E5F073
2017-07-25 16:24:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:24:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
2017-07-25 16:24:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-25 16:24:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07,-25 16:24:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:24:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:24:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:24:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:24:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:24:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "58D6DF15-0B01-44D3-B565-43125AB2A311", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:58D6DF15-0B01-44D3-B565-43125AB2A311
,2017-07-25 16:24:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-25 16:24:44 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-25 16:24:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 81 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:21A3C260-F346-4981-BED5-324227116BB4
,[ThaliCore] Browser.startListening
,2017-07-25 16:24:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-25 16:24:44 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-25 16:24:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FABBB17E-2F2C-4F1E-8192-036793CA1965:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FABBB17E-2F2C-4F1E-8192-036793CA1965", generation: 0)
2017-07-25 16:24:45 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FABBB17E-2F2C-4F1E-8192-036793CA1965","generation":0}'
2017-07-25 16:24:45 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for FABBB17E-2F2C-4F1E-8192-036793CA1965, (syncValue: xtKrjXLVEl6vlM13Z5tVLRI8iR8sgPBv)'
2017-07-25 16:24:45 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FABBB17E-2F2C-4F1E-8192-036793C,A1965", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FABBB17E-2F2C-4F1E-8192-036793CA1965", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:FABBB17E-2F2C-4F1E-8192-036793CA1965:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:FABBB17E-2F2C-4F1E-8192-036793CA1965:0 state: notConnected -> connecting
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DC8C7BD9-C2BA-4F08-B470-D87E25646211
[ThaliCore] Advert,iser: session connected Peer(uuid: "58D6DF15-0B01-44D3-B565-43125AB2A311", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:DC8C7BD9-C2BA,-4F08-B470-D87E25646211 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:58D6DF15-0B01-44D3-B565-43125AB2A311:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "58D6DF15-0B01-44D3-B565-43125AB2A311", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D2D0A921-E533-432A-9587-695A643E972C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D2D0A921-E533-432A-9587-695A643E972C", generation: 0)
2017-07-25 16:24:46 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D2D0A921-E533-432A-9587-695A643E972C","generation":0}'
2017-07-25 16:24:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-25 16:24:46 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FABBB17E-2F2C-4F1E-8192-036793CA1965:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:FABBB17E-2F2C-4F1E-8192-036793CA1965:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "FABBB17E-2F2C-4F1E-8192-036793CA1965", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60995
2017-07-25 16:24:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"xtKrjXLVEl6vlM13Z5tVLRI8iR8sgPBv","error":null,"portN,umber":60995}'
2017-07-25 16:24:48 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'xtKrjXLVEl6vlM13Z5tVLRI8iR8sgPBv', error: 'null', listeningPort: '60995''
2017-07-25 16:24:48 - INFO testThaliMobileNative: ''
ok 83 Must have ,listeningPort
ok 84 listeningPort must be a number
ok 85 listening port should not be 0
# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:DC8C7BD9-C2BA-4F08-B470-D87E25646211
,[ThaliCore] Session.session(_:peer:didChange:) peer:DC8C7BD9-C2BA-4F08-B470-D87E25646211 state: connecting -> connected
,2017-07-25 16:24:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-25 16:24:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-25 16:24:50 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-25 16:24:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:58D6DF15-0B01-44D3-B565-43125AB2A311
,2017-07-25 16:24:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-25 16:24:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:FABBB17E-2F2C-4F1E-8192-036793CA1965
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:60995
,[ThaliCore] Session.disconnect() peer:FABBB17E-2F2C-4F1E-8192-036793CA1965:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:DC8C7BD9-C2BA-4F08-B470-D87E25646211 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "58D6DF15-0B01-44D3-B565-43125AB2A311", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
,[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:DC8C7BD9-C2BA-4F08-B470-D87E25646211
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:FABBB17E-2F2C-4F1E-8192-036793CA1965:0
[ThaliCore] BrowserRelay.deinit
,2017-07-25 16:24:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,[ThaliCore] Session.deinit peer:DC8C7BD9-C2BA-4F08-B470-D87E25646211
,2017-07-25 16:24:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-25 16:24:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:24:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:24:50 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:24:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:24:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:24:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DA0E2C5F-B8AB-424C-989C-BDF114DA1928", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:DA0E2C5F-B8AB-424C-989C-BDF114DA1928
,2017-07-25 16:24:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-25 16:24:52 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-25 16:24:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 86 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3DAFDFB3-FFED-447E-8BA5-267430214F0E
,[ThaliCore] Browser.startListening
,2017-07-25 16:24:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-25 16:24:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-25 16:24:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D2D0A921-E533-432A-9587-695A643E972C:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D2D0A921-E533-432A-9587-695A643E972C", generation: 0)
,ok 87 Can call startListeningForAdvertisements without error
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FABBB17E-2F2C-4F1E-8192-036793CA1965:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FABBB17E-2F2C-4F1E-8192-036793CA1965", generation: 0)
2017-07-25 16:24:52 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D2D0A921-E533-432A-9587-695A643E972C","generation":0}'
,2017-07-25 16:24:52 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D2D0A921-E533-432A-9587-695A643E972C (syncValue: VoJZ9L6A6KpPrB6CEMfdwgAJrzaPF0Ok)'
,2017-07-25 16:24:52 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D2D0A921-E533-432A-9587-695A643E972C", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D2D0A921-E533-432A-9587-695A643E972C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D2D0A921-E533-432A-9587-695A643E972C:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-25 16:24:52 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FABBB17E-2F2C-4F1E-8192-036793CA1965","generation":0}'
,2017-07-25 16:24:52 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:24:52 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B7B955AE-E51A-415A-B1E2-A27D544FD210:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B7B955AE-E51A-415A-B1E2-A27D544FD210", generation: 0)
2017-07-25 16:24:54 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B7B955AE-E51A-415A-B1E2-A27D544FD210","generation":0}'
2017-07-25 16:24:54 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-25 16:24:54 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-25 16:24:54 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A", generation: 0)
,2017-07-25 16:24:54 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A","generation":0}'
,2017-07-25 16:24:54 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:24:54 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:24:54 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:24:54 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DA0E2C5F-B8AB-424C-989C-BDF114DA1928:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DA0E2C5F-B8AB-424C-989C-BDF114DA1928", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:FABBB17E-2F2C-4F1E-8192-036793CA1965:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "FABBB17E-2F2C-4F1E-8192-036793CA1965", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:D2D0A921-E533-432A-9587-695A643E972C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D2D0A921-E533-432A-9587-695A643E972C:0
,[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "D2D0A921-E533-432A-9587-695A643E972C", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D2D0A921-E533-432A-9587-695A643E972C", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D2D0A921-E533-432A-9587-695A643E972C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D2D0A921-E533-432A-9587-695A643E972C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.deinit peer:D2D0A921-E533-432A-9587-695A643E972C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:D2D0A921-E533-432A-9587-695A643E972C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D2,D0A921-E533-432A-9587-695A643E972C:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "D2D0A921-E533-432A-9587-695A643E972C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,2D0A921-E533-432A-9587-695A643E972C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D2D0A921-E533-432A-9587-695A643E972C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:D2D0A921-E533-432A-9587-695A643E972C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:D2D0A921-E533-432A-9587-695A643E972C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:D2D0A921-E533-432A-9587-695A643E972C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D2D0A921-E533-432A-9587-695A643E972C:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "D2D0A921-E533-432A-9587-695A643E972C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,2D0A921-E533-432A-9587-695A643E972C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D2D0A921-E533-432A-9587-695A643E972C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:D2D0A921-E533-432A-9587-695A643E972C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:D2D0A921-E533-432A-9587-695A643E972C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:D2D0A921-E533-432A-9587-695A643E972C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D2,D0A921-E533-432A-9587-695A643E972C:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "D2D0A921-E533-432A-9587-695A643E972C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:D2D0A921,-E533-432A-9587-695A643E972C error: max retries exceeded
2017-07-25 16:25:03 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"VoJZ9L6A6KpPrB6CEMfdwgAJrzaPF0Ok","error":"Connection could not be established","portNumber":null}'
2017-0,7-25 16:25:03 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'VoJZ9L6A6KpPrB6CEMfdwgAJrzaPF0Ok', error: 'Connection could not be established', listeningPort: '%s''
2017-07-25 16:25:03 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"D2D0A921-E533-432A-9587-695A643E972C","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-25 16:25:03 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-25 16:25:03 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"D2D0A921-E533-432A-9587-695A643E972C","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-25 16:25:03 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-25 16:25:03 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-25 16:25:03 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B7B955AE-E51A-415A-B1E2-A27D544FD210 (syncValue: BgNsyn5,5NxWJK6hdalLUOpuLQ00dNLAm)'
2017-07-25 16:25:03 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B7B955AE-E51A-415A-B1E2-A27D544FD210", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B7B955AE-E51A-415A-B1E2-A27D544FD210", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B7B955AE-E51A,-415A-B1E2-A27D544FD210:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-25 16:25:03 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-07-25 16:25:03 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:D2D0A921-E533-432A-9587-695A643E972C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B7B955AE-E51A-415A-B1E2-A27D544FD210:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BA32C405-89E2-44A4-BB9D-6FD7F5A71D82
[ThaliCore] Advertiser: session connected Peer(uuid: "DA0E2C5F-B8AB-424C-989C-BDF114DA1928", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:BA32C405-89E2-44A4-BB9D-6FD7F5A71D82 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B7B955AE-E51A-415A-B1E2-A27D544FD210:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BA32C405-89E2-44A4-BB9D-6FD7F5A71D82
,[ThaliCore] Session.session(_:peer:didChange:) peer:B7B955AE-E51A-415A-B1E2-A27D544FD210:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "B7B955AE-E51A-415A-B1E2-A27D544FD210", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61002
2017-07-25 16:25:05 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"BgNsyn55NxWJK6hdalLUOpuLQ00dNLAm","error":null,"portNumber":61002}'
2017-07-25 16:25:05 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'BgNsyn55NxWJK6hdalLUOpuLQ00dNLAm', error: 'null', listeningPort: '61002''
,Connecting to the localhost:61002
,Connected to the localhost:61002
2017-07-25 16:25:05 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
2017-07-25 16:25:05 - DEBUG testThaliMobileNative: 'Client data flushed'
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B7B955AE-E51A-415A-B1E2-A27D544FD210:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:BA32C405-89E2-44A4-BB9D-6FD7F5A71D82 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:BA32C405-89E2-44A4-BB9D-6FD7F5A71D82
[ThaliCore] Session.startOutputStream(with:) peer:BA32C405-89E2-44A4-BB9D-6FD7F5A71D82
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B7B955AE-E51A-415A-B1E2-A27D544FD210:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [1, 2]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-25 16:25:06 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-07-25 16:25:07 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
2017-07-25 16:25:07 - DEBUG testThaliMobileNative: 'Server sends data bac,k to client (20 bytes):'
2017-07-25 16:25:07 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:1
[ThaliCore] VirtualSocket.closeStreams() vsID:1
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:1,
[ThaliCore] VirtualSocket.deinit vsID:1 [2]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDi,sconnectHandler disconnecting:false
,ok 88 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams,() vsID:2
# teardown
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:2
[ThaliCore] VirtualSocket.deinit vsID:2 []
,2017-07-25 16:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-25 16:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-25 16:25:08 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-25 16:25:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:DA0E2C5F-B8AB-424C-989C-BDF114DA1928
,2017-07-25 16:25:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:25:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.disconnect peer:B7B955AE-E51A-415A-B1E2-A27D544FD210
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61002
[ThaliCore] Session.disconnect,() peer:B7B955AE-E51A-415A-B1E2-A27D544FD210:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:BA32C405-89E2-44A4-BB9D-6FD7F5A71D82 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "DA0E2C5F-B8AB-424C-989C-BDF114DA1928", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:BA32C405-89E2-44A4-BB9D-6FD7F5A71D82
,[ThaliCore] Session.deinit peer:B7B955AE-E51A-415A-B1E2-A27D544FD210:0
[ThaliCore] BrowserRelay.deinit
2017-07-25 16:25:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-25 16:25:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-25 16:25:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:25:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-25 16:25:08 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-25 16:25:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-25 16:25:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-25 16:25:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,[ThaliCore] AdvertiserRelay.deinit
,# setup
,[ThaliCore] Session.deinit peer:BA32C405-89E2-44A4-BB9D-6FD7F5A71D82
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "82E20146-F4E8-4EC3-B45C-563776045682", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:82E20146-F4E8-4EC3-B45C-563776045682
2017-07-25 16:25:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-25 16:25:09, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-25 16:25:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 89 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Thal,iCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B595C820-9E49-4285-8113-1FE66F87E3A8
[ThaliCore] Browser.startListening
2017-07-25 16:25:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adve,r,tisingActive":true}'
2017-07-25 16:25:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"rout,er":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-25 16:25:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5A615210-A54A-4ECF-9E75-112BFEB948A6:0
2017-07-25 16:25:10 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5A615210-A54A-4ECF-9E75-112BFEB948A6", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B7B955AE-E51A-415A-B1E2-A27D544FD210:0
[ThaliC,ore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B7B955AE-E51A-415A-B1E2-A27D544FD210", generation: 0)
2017-07-25 16:25:10 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A (syncValue: 8TYMegBEzs8ryO41,e1MfgtuZ8HOC0Y9r)'
,2017-07-25 16:25:10 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DB,38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,2017-07-25 16:25:10 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5A615210-A54A-4ECF-9E75-112BFEB948A6","generation":0}'
2017-07-25 16:25:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-25 16:25:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:25:10 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B7B955AE-E51A-415A-B1E2-A27D544FD210","generation":0}'
,2017-07-25 16:25:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:25:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:25:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:45CBB222-33C6-4C7F-9C48-5051955F679C:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "45CBB222-33C6-4C7F-9C48-5051955F679C", generation: 0)
,2017-07-25 16:25:10 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"45CBB222-33C6-4C7F-9C48-5051955F679C","generation":0}'
,2017-07-25 16:25:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-25 16:25:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:25:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:25:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:82E20146-F4E8-4EC3-B45C-563776045682:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "82E20146-F4E8-4EC3-B45C-563776045682", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B7B955AE-E51A-415A-B1E2-A27D544FD210:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B7B955AE-E51A-415A-B1E2-A27D544FD210", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:DB,38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,B38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:DB,38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,B38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:DB,38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,B38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:DB,38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:DB38B4FE,-1E0F-4F45-9FAA-A91B54DC6C1A error: max retries exceeded
2017-07-25 16:25:20 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8TYMegBEzs8ryO41e1MfgtuZ8HOC0Y9r","error":"Connection could not be established","portNumber":null}'
2017-0,7-25 16:25:20 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '8TYMegBEzs8ryO41e1MfgtuZ8HOC0Y9r', error: 'Connection could not be established', listeningPort: '%s''
2017-07-25 16:25:20 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-25 16:25:20 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-25 16:25:20 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-25 16:25:20 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-25 16:25:20 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-25 16:25:20 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5A615210-A54A-4ECF-9E75-112BFEB948A6 (syncValue: HQ0xVmk,Eb5aM3assnVvoTw7LJeR9Blir)'
2017-07-25 16:25:20 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5A615210-A54A-4ECF-9E75-112BFEB948A6", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5A615210-A54A-4ECF-9E75-112BFEB948A6", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5A615210-A54A,-4ECF-9E75-112BFEB948A6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-25 16:25:20 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
,2017-07-25 16:25:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:DB38B4FE-1E0F-4F45-9FAA-A91B54DC6C1A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5A615210-A54A-4ECF-9E75-112BFEB948A6:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5A615210-A54A-4ECF-9E75-112BFEB948A6:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:5A615210-A54A-4ECF-9E75-112BFEB948A6:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "5A615210-A54A-4ECF-9E75-112BFEB948A6", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61020
2017-07-25 16:25:23 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"HQ0xVmkEb5aM3assnVvoTw7LJeR9Blir",,"error":null,"portNumber":61020}'
2017-07-25 16:25:23 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'HQ0xVmkEb5aM3assnVvoTw7LJeR9Blir', error: 'null', listeningPort: '61020''
,Connecting to the localhost:61020
Connecting to the localhost:61020
Connecting to the localhost:61020
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:,) peer:5A615210-A54A-4ECF-9E75-112BFEB948A6:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5A615210-A54A-4ECF-9E75-112BFEB948A6:0
[ThaliCore], TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5A615210-A54A-4ECF-9E75-112BFEB948A6:0
Connected to the localhost:61020
Connected to the localhost:61020
C,onnected to the localhost:61020
,ok 91 correct string length
,2017-07-25 16:25:23 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 92 correct string length
,2017-07-25 16:25:23 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 93 correct string length
,2017-07-25 16:25:23 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-25 16:25:23 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-25 16:25:23 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-25 16:25:23 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5A615210-A54A-4ECF-9E75-112BFEB948A6:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [3]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5A615210-A54A-4ECF-9E75-112BFEB948A6:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [3, 4]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5A615210-A54A-4ECF-9E75-112BFEB948A6:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [3, 4, 5]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:5
ok 94 got the same data back
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
ok 95 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "S,ocket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.d,idSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket exited RunLoop vsID:5
[ThaliCore] VirtualSocket.closeStreams() vsID:3
[ThaliCore] VirtualSocket.deinit vsID:5 [3, 4]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:3
,[ThaliCore] VirtualSocket.deinit vsID:3 [4]
,ok 96 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams,() vsID:4
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:4
,[ThaliCore] VirtualSocket.deinit vsID:4 []
,# teardown
,2017-07-25 16:25:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-25 16:25:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-25 16:25:27 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-25 16:25:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:82E20146-F4E8-4EC3-B45C-563776045682
,2017-07-25 16:25:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-25 16:25:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:5A615210-A54A-4ECF-9E75-112BFEB948A6
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61020
,[ThaliCore] Session.disconnect() peer:5A615210-A54A-4ECF-9E75-112BFEB948A6:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:5A615210-A54A-4ECF-9E75-112BFEB948A6:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-25 16:25:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-25 16:25:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-25 16:25:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:25:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-25 16:25:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:25:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-25 16:25:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:25:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "891E67C8-0FC1-47E5-93ED-81CAFB5D34F9", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:891E67C8-0FC1-47E5-93ED-81CAFB5D34F9
,2017-07-25 16:25:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-25 16:25:28 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-25 16:25:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 97 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:0BDE0016-0455-46FA-A315-6C05595FA621
[ThaliCore] Browser.startListening
2017-07-25 16:25:28 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-25 16:25:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-25 16:25:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:45CBB222-33C6-4C7F-9C48-5051955F679C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "45CBB222-33C6-4C7F-9C48-5051955F679C", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5A615210-A54A-4ECF-9E75-112BFEB948A6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5A615210-A54A-4ECF-9E75-112BFEB948A6", generation: 0)
2017-07-25 16:25:29 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"45CBB222-33C6-4C7F-9C48-5051955F679C","generation":0}'
,2017-07-25 16:25:29 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 45CBB222-33C6-4C7F-9C48-5051955F679C (syncValue: HkmRdqMLmP4yc1LCuh4SJakhotsMtmzx)'
,2017-07-25 16:25:29 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "45CBB222-33C6-4C7F-9C48-5051955F679C", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "45CBB222-33C6-4C7F-9C48-5051955F679C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:45CBB222-33C6-4C7F-9C48-5051955F679C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-07-25 16:25:29 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5A615210-A54A-4ECF-9E75-112BFEB948A6","generation":0}'
,2017-07-25 16:25:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-25 16:25:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:891E67C8-0FC1-47E5-93ED-81CAFB5D34F9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "891E67C8-0FC1-47E5-93ED-81CAFB5D34F9", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BA8A39C9-4FC3-4403-9F86-8EC579378B0C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BA8A39C9-4FC3-4403-9F86-8EC579378B0C", generation: 0)
2017-07-25 16:25:29 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BA8A39C9-4FC3-4403-9F86-8EC579378B0C","generation":0}'
2017-07-25 16:25:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-25 16:25:29 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-25 16:25:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:02A53CE0-2039-4785-8EFB-491EDF350756:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "02A53CE0-2039-4785-8EFB-491EDF350756", generation: 0)
2017-07-25 16:25:29 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"02A53CE0-2039-4785-8EFB-491EDF350756","generation":0}'
2017-07-25 16:25:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-25 16:25:29 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-25 16:25:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-25 16:25:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:45CBB222-33C6-4C7F-9C48-5051955F679C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:45,CBB222-33C6-4C7F-9C48-5051955F679C:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "45CBB222-33C6-4C7F-9C48-5051955F679C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,5CBB222-33C6-4C7F-9C48-5051955F679C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "45CBB222-33C6-4C7F-9C48-5051955F679C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:45CBB222-33C6-4C7F-9C48-5051955F679C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:45CBB222-33C6-4C7F-9C48-5051955F679C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:5A615210-A54A-4ECF-9E75-112BFEB948A6:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "5A615210-A54A-4ECF-9E75-112BFEB948A6", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:45CBB222-33C6-4C7F-9C48-5051955F679C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "45CBB222-33C6-4C7F-9C48-5051955F679C", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:45CBB222-33C6-4C7F-9C48-5051955F679C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:45,CBB222-33C6-4C7F-9C48-5051955F679C:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "45CBB222-33C6-4C7F-9C48-5051955F679C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,5CBB222-33C6-4C7F-9C48-5051955F679C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "45CBB222-33C6-4C7F-9C48-5051955F679C", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-25 16:25:34 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"HkmRdqMLmP4yc1LCuh4SJakhotsMtmzx","error":"Peer is unavailable",,"portNumber":null}'
2017-07-25 16:25:34 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'HkmRdqMLmP4yc1LCuh4SJakhotsMtmzx', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-25 16:25:34 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"45CBB222-33C6-4C7F-9C48-5051955F679C","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-25 16:25:34 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-25 16:25:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"45CBB222-33C6-4C7F-9C48-5051955F679C","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-25 16:25:34 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-25 16:25:34 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-25 16:25:34 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BA8A39C9-4FC3-4403-9F86-8EC579378B0C (syncValue: in0WxF2kZ8KuUnnE6BDPg8b,YFO64LYjd)'
2017-07-25 16:25:34 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BA8A39C9-4FC3-4403-9F86-8EC579378B0C", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BA8A39C9-4FC3-4403-9F86-8EC579378B0C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BA8A39C9-4FC3-4403-9F86-8EC57,9378B0C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-25 16:25:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:45CBB222-33C6-4C7F-9C48-5051955F679C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:BA8A39C9-4FC3-4403-9F86-8EC579378B0C:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BA8A39C9-4FC3-4403-9F86-8EC579378B0C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:BA8A39C9-4FC3-4403-9F86-8EC579378B0C:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "BA8A39C9-4FC3-4403-9F86-8EC579378B0C", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61035
,2017-07-25 16:25:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"in0WxF2kZ8KuUnnE6BDPg8bYFO64LYjd","error":null,"portNumber":61035}'
,2017-07-25 16:25:38 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'in0WxF2kZ8KuUnnE6BDPg8bYFO64LYjd', error: 'null', listeningPort: '61035''
,Connecting to the localhost:61035
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:BA8A39C9-4FC3-4403-9F86-8EC579378B0C:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:BA8A39C9-4FC3-4403-9F86-8EC579378B0C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [6]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:61035
2017-07-25 16:25:38 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
2017-07-25 16:25:38 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 99 got the same data back
# teardown
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed b,y remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.,closeStreams() vsID:6
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:BA8A39C9-4FC3-4403-9F86-8EC579378B0C:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61035
[ThaliCore] Session.disconnect() peer:BA8A39C9-4FC3-4403-9F86-8EC579378B0C:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "BA8A39C9-4FC3-4403-9F86-8EC579378B0C", generation: 0)
,2017-07-25 16:25:52 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"in0WxF2kZ8KuUnnE6BDPg8bYFO64LYjd","error":"Session disconnected","portNumber":null}'
,2017-07-25 16:25:52 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"BA8A39C9-4FC3-4403-9F86-8EC579378B0C","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-25 16:25:52 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-25 16:25:52 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"BA8A39C9-4FC3-4403-9F86-8EC579378B0C","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-25 16:25:52 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:BA8A39C9-4FC3-4403-9F86-8EC579378B0C:0
,2017-07-25 16:25:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-25 16:25:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-25 16:25:53 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-25 16:25:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:891E67C8-0FC1-47E5-93ED-81CAFB5D34F9
,2017-07-25 16:25:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:25:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.disconnect peer:BA8A39C9-4FC3-4403-9F86-8EC579378B0C
2017-07-25 16:25:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-25 16:25:53 - DEBUG thaliMobileNativeWrapper: 'Method ,discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-25 16:25:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:25:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:25:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:25:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:25:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:25:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "41B683AE-0F9D-4E22-8D46-1F9101EFBDED", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:41B683AE-0F9D-4E22-8D46-1F9101EFBDED
,2017-07-25 16:25:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-25 16:25:54 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-25 16:25:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 100 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C532E667-106D-472C-ABF0-5903344AB907
[ThaliCore] Browser.startListening
2017-07-25 16:25:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-25 16:25:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":tr,ue}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-25 16:25:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BA8A39C9-4FC3-4403-9F86-8EC579378B0C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BA8A39C9-4FC3-4403-9F86-8EC579378B0C", generation: 0)
2017-07-25 16:25:54 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BA8A39C9-4FC3-4403-9F86-8EC579378B0C","generation":0}'
2017-07-25 16:25:54 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BA8A39C9-4FC3-4403-9F86-8EC579378B0C, (syncValue: 9D5tUWTM3RgFT6D17hFhSJpgqYfl7zZW)'
2017-07-25 16:25:54 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BA8A39C9-4FC3-4403-9F86-8EC5793,78B0C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BA8A39C9-4FC3-4403-9F86-8EC579378B0C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:BA8A39C9-4FC3-4403-9F86-8EC579378B0C:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:02A53CE0-2039-4785-8EFB-491EDF350756:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "02A53CE0-2039-4785-8EFB-491EDF350756",, generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-25 16:25:54 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable,":true,"peerIdentifier":"02A53CE0-2039-4785-8EFB-491EDF350756","generation":0}'
2017-07-25 16:25:54 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-25 16:25:54 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1633D717-BAB5-409E-9E10-582EE947BE7C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1633D717-BAB5-409E-9E10-582EE947BE7C", generation: 0)
2017-07-25 16:25:55 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"1633D717-BAB5-409E-9E10-582EE947BE7C","generation":0}'
2017-07-25 16:25:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-25 16:25:55 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-25 16:25:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:41B683AE-0F9D-4E22-8D46-1F9101EFBDED:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "41B683AE-0F9D-4E22-8D46-1F9101EFBDED", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D6DB2262-D0D6-4B7B-B142-443CB29EFA5D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D6DB2262-D0D6-4B7B-B142-443CB29EFA5D", generation: 0)
2017-07-25 16:25:55 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D6DB2262-D0D6-4B7B-B142-443CB29EFA5D","generation":0}'
2017-07-25 16:25:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-25 16:25:55 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-25 16:25:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-25 16:25:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:BA8A39C9-4FC3-4403-9F86-8EC579378B0C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BA,8A39C9-4FC3-4403-9F86-8EC579378B0C:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "BA8A39C9-4FC3-4403-9F86-8EC579378B0C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,A8A39C9-4FC3-4403-9F86-8EC579378B0C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BA8A39C9-4FC3-4403-9F86-8EC579378B0C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:BA8A39C9-4FC3-4403-9F86-8EC579378B0C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:BA8A39C9-4FC3-4403-9F86-8EC579378B0C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:02A53CE0-2039-4785-8EFB-491EDF350756:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "02A53CE0-2039-4785-8EFB-491EDF350756", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:BA8A39C9-4FC3-4403-9F86-8EC579378B0C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BA,8A39C9-4FC3-4403-9F86-8EC579378B0C:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "BA8A39C9-4FC3-4403-9F86-8EC579378B0C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,A8A39C9-4FC3-4403-9F86-8EC579378B0C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BA8A39C9-4FC3-4403-9F86-8EC579378B0C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:BA8A39C9-4FC3-4403-9F86-8EC579378B0C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:BA8A39C9-4FC3-4403-9F86-8EC579378B0C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:BA8A39C9-4FC3-4403-9F86-8EC579378B0C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BA,8A39C9-4FC3-4403-9F86-8EC579378B0C:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "BA8A39C9-4FC3-4403-9F86-8EC579378B0C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,A8A39C9-4FC3-4403-9F86-8EC579378B0C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BA8A39C9-4FC3-4403-9F86-8EC579378B0C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:BA8A39C9-4FC3-4403-9F86-8EC579378B0C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:BA8A39C9-4FC3-4403-9F86-8EC579378B0C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:BA8A39C9-4FC3-4403-9F86-8EC579378B0C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "BA8A39C9-4FC3-4403-9F86-8EC579378B0C", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:BA8A39C9-4FC3-4403-9F86-8EC579378B0C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BA,8A39C9-4FC3-4403-9F86-8EC579378B0C:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "BA8A39C9-4FC3-4403-9F86-8EC579378B0C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:BA8A39C9,-4FC3-4403-9F86-8EC579378B0C error: max retries exceeded
2017-07-25 16:26:05 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9D5tUWTM3RgFT6D17hFhSJpgqYfl7zZW","error":"Connection could not be established","portNumber":null}'
2017-0,7-25 16:26:05 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '9D5tUWTM3RgFT6D17hFhSJpgqYfl7zZW', error: 'Connection could not be established', listeningPort: '%s''
2017-07-25 16:26:05 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"BA8A39C9-4FC3-4403-9F86-8EC579378B0C","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-25 16:26:05 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-25 16:26:05 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"BA8A39C9-4FC3-4403-9F86-8EC579378B0C","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-25 16:26:05 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-25 16:26:05 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-25 16:26:05 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 1633D717-BAB5-409E-9E10-582EE947BE7C (syncValue: 70Wsrpz,hOMzZOyH4lvSCY1kHWZAgRxAi)'
2017-07-25 16:26:05 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1633D717-BAB5-409E-9E10-582EE947BE7C", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1633D717-BAB5-409E-9E10-582EE947BE7C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1633D717-BAB5,-409E-9E10-582EE947BE7C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-25 16:26:05 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-07-25 16:26:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:BA8A39C9-4FC3-4403-9F86-8EC579378B0C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1633D717-BAB5-409E-9E10-582EE947BE7C:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1633D717-BAB5-409E-9E10-582EE947BE7C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:1633D717-BAB5-409E-9E10-582EE947BE7C:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "1633D717-BAB5-409E-9E10-582EE947BE7C", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61051
2017-07-25 16:26:08 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"70WsrpzhOMzZOyH4lvSCY1kHWZAgRxAi",,"error":null,"portNumber":61051}'
2017-07-25 16:26:08 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '70WsrpzhOMzZOyH4lvSCY1kHWZAgRxAi', error: 'null', listeningPort: '61051''
,Connecting to the localhost:61051
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:1633D717-BAB5-409E-9E10-582EE947BE7C:0
Connected to the localh,ost:61051
,2017-07-25 16:26:08 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-25 16:26:08 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1633D717-BAB5-409E-9E10-582EE947BE7C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [6, 7]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C7911950-5717-4E61-A056-1DDAA02CF1CB
[ThaliCore] Advertiser: session connected Peer(uuid: "41B683AE-0F9D-4E22-8D46-1F9101EFBDED", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:C7911950-5717-4E61-A056-1DDAA02CF1CB state: notConnected -> connecting
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:7
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
ok 102 got the same data back
,[ThaliCore] VirtualSocket exited RunLoop vsID:7
,[ThaliCore] VirtualSocket.deinit vsID:7 [6]
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B34F3865-6E0C-4368-AE3B-DD68B33C0E37
[ThaliCore] Advertiser: session connected Peer(uuid: "41B683AE-0F9D-4E22-8D46-1F9101EFBDED", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:B34F3865-6E0C-4368-AE3B-DD68B33C0E37 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C7911950-5717-4E61-A056-1DDAA02CF1CB
,[ThaliCore] Session.session(_:peer:didChange:) peer:C7911950-5717-4E61-A056-1DDAA02CF1CB state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C7911950-5717-4E61-A056-1DDAA02CF1CB
[ThaliCore] Session.startOutputStream(with:) peer:C7911950-5717-4E61-A056-1DDAA02CF1CB
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [6, 8]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-25 16:26:11 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
2017-07-25 16:26:11 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
2017-07-25 16:26:11 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
2017,-07-25 16:26:11 - DEBUG testThaliMobileNative: 'Server received (3072 bytes):'
2017-07-25 16:26:11 - DEBUG testThaliMobileNative: 'Server received (1308 bytes):'
2017-07-25 16:26:11 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
2017-07-,25 16:26:11 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
2017-07-25 16:26:11 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
2017-07-25 16:26:11 - DEBUG testThaliMobileNative: 'Server received (3356 bytes):'
2017-07-25 16:26:11 - DEBUG testThaliMobileNative: 'Server received (7665 bytes):'
2017-07-25 16:26:11 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
2017-07-25 16:26:11 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
2017-07-25 16:26,:11 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
2017-07-25 16:26:11 - DEBUG testThaliMobileNative: 'Server received (10950 bytes):'
2017-07-25 16:26:11 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-25 16:26:11 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-25 16:26:11 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-25 16:26:11 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
2017-07-25 16:26:11 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
2017-07-25 16:26:11 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
2017-07-25 16:26:11 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-25 16:26:11 - DEBUG testThaliMobileNative: 'Server received (3121 bytes):'
,2017-07-25 16:26:11 - DEBUG testThaliMobileNative: 'Server received all data: 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,z,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,L,BpIaySGpuRupapMVg0KkUqu3FeEfPuGLup5VLftlRapP6dLJYlw22EjivXOvLLvNk3xjhk4Y44ZyCd3IjF0Wc17Q7S82T58u2mTDTfphieugd2eyMGhUwXRQq87x1essmh6D5h3Rr8Oic3ZxbMgR4sbbV6NOK5309JO4J5icQTffcvq59sB4yzUKiBfoMEJ5PT9Jx52YHsQBCbhW57L154IY3l81TuM2dUq6c2tAWXRgtRY2j0wpM1TPM4r8Lk7s,phObyD3dqVvVNuhIyDr60ebKUedMhSKyfbOSxW4lA043iSINY61ICwc6xHKjNSciMhNzLhbUqtbchRzoPIkazsL7QPjzRXshzhHEnvrucfhb9W5TlY7SEBsN4CULiZMLQIEzxMwLdjHL8StSEWAXxW6Ft5kFlMU7MBFrS9QAFHAownsJUshfFCtJsGTVVM8eJm2s2QyyGPtyuu0fOIa5O8EoFmZYvc0pwa0i08ZG8A29NDFd4S4SV6cw26qOXWdn,byrSAhGnUGkcGJAmvZqqpR2StUUZP4HiafpBok5TxE5jbAKQ1as33eA577P34HefmwCkpZHpnsv8KzlL9P8DRDmjWr0JpVgNqQpv3zTkUfo270d9FqdSWiLZcBjrh1XkZZFPdnm73nLjEAYOKDTXLHH80SrgoaAdnHW1vYlmzsI2Xwb0YlfVVRyiBxT7l0io0uopnfWZilYl8D5siSRmSYzQPAT33qX5rXyxLfLXFmCWPQPbVdYxBcJYBP5poyV8,hlmfgrSR4B5OasTUxCvghIGemmJ2h1cItiy8Jt7O2G4A6DpbpkCR5V9ESADBi5H9avm8FUu1CCkPd6uucxOtp0mZbwSF7Y3OEIPaT0QLvyGZFYYHG2vGH6AZEinL8Ltkcw4Qv2ze6Ri0pA3D2vJiwbGWWgn4jj6BthWmfk0X1j6DUvA9i4BxPRNsi8bnX9ZQRFbclkog4smmLaDtLq7h8kEYMzN7kF9lV7k98SjZtLH7xzn6c44SafvrYO29SPK,U,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,j,VVAr8kT56zI0ev0bQPtvFwZvay0ZxSM4jaJpSNsIedwQSPX1sf6MnIYd90CowMRvnf3c9jQ96Zfyu7gQj2gogIEVBYcTXjCAPDGA9837Su7FKnraamddNbqo6TJsPy6NvoVZPlf3I1R08XDyjnG2hTs0Tv05QFOM0UVhPMpO0bvoS8wNbmgkuBmqbepTyS24IzpRBsnd58RUJHuoTgBoNvXU0X3Oy2jFRgEdGkSr3szYIIFmKD4BFeIaPSBSQSsD,hwMuMQyX2EOTmu7PkgIH8yhYI5Cg0GARKCUFgyjBDibHWX69R0JHnBKNxH5ieuATLU4m3iu2ZpHfcgZsNlXaC6wKRcvAo0XWLTIAxtqEsFofis8E6cM1FjDTQlts4kh5hR9dtRPBL2WXCGiyX0fmWLvRZ0ptjh8iCp5X3hQNeACJFTs1NzRG60N65KsJREwNMfMuxFsvN7EwX7TDTX4OKTCzqM24TT6QpXj44RejhCShJyuqBbnXvawNjGBgcLxb,esiztFKCbSP7gdGKyP29RgoyR92YpiRfZFNnUUI6ZCPhd0ArKJszyCvb0zcQC47VYAIxGEuWXUsuX6xzHWLDtjV46vIGjvn73qecMM3n1oANQa1ICN4ew801H5FQyztMgXhv7nfwddyiDEVBWE7ed4sTUzNT5F5z5ZXega8ENS9sFlXzIwgMJlnMSXtpD5AmeobHVYAYfUbO2xJs2bX95uQ3rmMFkme9ic5wg2R5hBIRVKcIY09VZgE9bYHO0v2I,cci1SeJwXbawawFTYrH5fjannpg9llyY54w2ehS3v3mPVVBtiaV4hktFJU502xQIRd66Mw1D3sYaYLkambafveGC9007Gfsh5WCNq22W80eKOP4znFjodmlyMFIyBv9dBqCAcHY5SO4zSoXovPVbQXJSnSuTnlkb8nDHcauH0vquIsRo7K7Oiu8MmydX4L0oYhzMY5Rk8rs8rr85jkMwakdAnNIgif4UbSDoFlWSAf8ktJCVB0x01QLEgUQGqQM,x,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'
2017-07-25 16:26:11 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-25 16:26:11 - DEBUG testThaliMobileNative: 'Serve,r data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:8
[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:8
[ThaliCore] VirtualSocket.deinit vsID:8 [6]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B34F3865-6E0C-4368-AE3B-DD68B33C0E37
,[ThaliCore] Session.session(_:peer:didChange:) peer:B34F3865-6E0C-4368-AE3B-DD68B33C0E37 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B34F3865-6E0C-4368-AE3B-DD68B33C0E37
[ThaliCore] Session.startOutputStream(with:) peer:B34F3865-6E0C-4368-AE3B-DD68B33C0E37
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [6, 9]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-25 16:26:14 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
2017-07-25 16:26:14 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
2017-07-25 16:26:14 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-25 16:26:14 - DEBUG testThaliMobileNative: 'Server received (2048 bytes):'
,2017-07-25 16:26:14 - DEBUG testThaliMobileNative: 'Server received (6641 bytes):'
,2017-07-25 16:26:14 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-25 16:26:14 - DEBUG testThaliMobileNative: 'Server received (11021 bytes):'
,2017-07-25 16:26:14 - DEBUG testThaliMobileNative: 'Server received (9855 bytes):'
,2017-07-25 16:26:14 - DEBUG testThaliMobileNative: 'Server received (16425 bytes):'
,2017-07-25 16:26:14 - DEBUG testThaliMobileNative: 'Server received (8596 bytes):'
,2017-07-25 16:26:14 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-25 16:26:14 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-25 16:26:15 - DEBUG testThaliMobileNative: 'Server data flushed',
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:9
[ThaliCore] VirtualSocket.closeStreams() vsID:9
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:9
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:9 [6]
,2017-07-25 16:26:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-25 16:26:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-25 16:26:15 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-25 16:26:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:41B683AE-0F9D-4E22-8D46-1F9101EFBDED
,2017-07-25 16:26:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-25 16:26:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:1633D717-BAB5-409E-9E10-582EE947BE7C
[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61051
,[ThaliCore] Session.disconnect() peer:1633D717-BAB5-409E-9E10-582EE947BE7C:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:1633D717-BAB5-409E-9E10-582EE947BE7C:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-25 16:26:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-25 16:26:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-25 16:26:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:26:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:26:15 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,[ThaliCore] Session.session(_:peer:didChange:) peer:B34F3865-6E0C-4368-AE3B-DD68B33C0E37 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "41B683AE-0F9D-4E22-8D46-1F9101EFBDED", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
2017-07-25 16:26:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to nat,ive'
[ThaliCore] Session.disconnect() peer:B34F3865-6E0C-4368-AE3B-DD68B33C0E37
[ThaliCore] AdvertiserRelay.deinit
,2017-07-25 16:26:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:26:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:C7911950-5717-4E61-A056-1DDAA02CF1CB state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "41B683AE-0F9D-4E22-8D46-1F9101EFBDED", generation: 0)
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] Session.deinit peer:B34F3865-6E0C-4368-AE3B-DD68B33C0E37
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CB480888-EC48-42DA-95D1-2592106A88F8", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:CB480888-EC48-42DA-95D1-2592106A88F8
2017-07-25 1,6:26:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-25 16:26:17 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-25 16:26:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 103 Ready to advertise
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:0B1D8873-5E37-4B4E-AC30-60C0C5BC2CAB
[ThaliCore] Browser.startListening
2017-07,-,25 16:26:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-25 16:26:17 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not ma,tch with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-25 16:26:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate ,(was in stopped state).'
ok 104 Ready to listen
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2934D003-1200-4C9E-AB23-8F76E83DCD2A:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2934D003-1200-4C9E-AB23-8F76E83DCD2A", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1633D717-BAB5-409E-9E10-582EE947BE7C:0
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:CB480888-EC48-42DA-95D1-2592106A88F8
[ThaliCore,] BrowserManager.foundPeerHandler peer:Peer(uuid: "1633D717-BAB5-409E-9E10-582EE947BE7C", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D6DB2262-D0D6-4B7B-B142-443CB29EFA5D:0
[ThaliCore] BrowserManager.foundPeerHan,dler peer:Peer(uuid: "D6DB2262-D0D6-4B7B-B142-443CB29EFA5D", generation: 0)
2017-07-25 16:26:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
[ThaliCore] Browser.browser(_:fo,undPeer:withDiscoveryInfo:) found peer:7C11DC55-1A5C-4DA6-9974-2913C4B3F7ED:0
2017-07-25 16:26:17 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"adver,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7C11DC55-1A5C-4DA6-9974-2913C4B3F7ED", generation: 0)
tising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-25 16:26:17 - INFO t,haliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 105 stop ads worked
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-25 16:26:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:26:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 106 test stop worked
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-25 16:26:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:26:20 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-25 16:26:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-25 16:26:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-25 16:26:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-25 16:26:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-25 16:26:20 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:26:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-25 16:26:20 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-25 16:26:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-25 16:26:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-25 16:26:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Test updating advertising and parallel data transfer
,2017-07-25 16:26:20 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-25 16:26:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:26:21 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-25 16:26:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-25 16:26:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-25 16:26:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-25 16:26:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-25 16:26:21 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:26:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-25 16:26:21 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-25 16:26:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-25 16:26:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
,2017-07-25 16:26:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:198926A6-2E75-402E-BF4D-163FEFBF66A9
[ThaliCore] Browser.startListening
,ok 107 discoveryActive should be false
ok 108 advertisingActive should be true
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "EC528BEA-BFE3-4826-8C04-E3B27340B7EC", generation: 0)
[ThaliCore] Advertise,r.startAdvertising with peerID:EC528BEA-BFE3-4826-8C04-E3B27340B7EC
ok 109 discoveryActive should be false
ok 110 advertisingActive should be true
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
ok 111 d,iscoveryActive should be false
ok 112 advertisingActive should be true
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:EC528BEA-BFE3-4826-8C04-E3B27340B7EC
ok 113 discoveryActive should be false
ok 114 a,dvertisingActive should be true
ok 115 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-25 16:26:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-25 16:26:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-25 16:26:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:26:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:26:21 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:26:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:26:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:26:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-07-25 16:26:21 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-25 16:26:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:26:21 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 116 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-25 16:26:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-25 16:26:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 117 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-25 16:26:21 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-25 16:26:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:26:22 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 118 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-25 16:26:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-25 16:26:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 119 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-25 16:26:22 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-25 16:26:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:26:22 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-25 16:26:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-25 16:26:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-25 16:26:22 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-25 16:26:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-25 16:26:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 122 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-25 16:26:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-25 16:26:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 123 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-25 16:26:22 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-25 16:26:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:26:23 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 124 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-25 16:26:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:26:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 125 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-25 16:26:23 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-25 16:26:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:26:23 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 126 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-25 16:26:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-25 16:26:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 127 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 128 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:6f22e233-6b55-41cf-a34d-72e351779da1 error: startListeningNotActive
2017-07-25 16:26:23 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved:, {"syncValue":"qNyNvP40KQadiOApPpFZSSs8VxJQ5kAb","error":"startListeningForAdvertisements is not active","portNumber":null}'
ok 129 Should only get called after multiConnect returned
ok 130 SyncValue matches
ok 131 Got right error
ok 132 listeningPort ,is null
2017-07-25 16:26:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"6f22e233-6b55-41cf-a34d-72e351779da1","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-25 16:26:23 - DEBUG t,haliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-25 16:26:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"6f22e233-6b55-41cf-a34d-7,2,e351779da1","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-25 16:26:23 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-25 16:26:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:26:23 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-25 16:26:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-25 16:26:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-25 16:26:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-25 16:26:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-25 16:26:23 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:26:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-25 16:26:23 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-25 16:26:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-25 16:26:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-25 16:26:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:47BEF287-4320-491C-BA3F-F0DA0370896E
[ThaliCore] Browser.startListening
2017-07-25 16:26:24 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-25 16:26:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-25 16:26:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 133 No error on star,ting
ok 134 Got null as expected
2017-07-25 16:26:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"OthhRw3Sqe8ZqiTahOyrkGofr8ufVfzv","error":"Illegal peerID","portNumber":null}'
ok 135 Should only get called after multiConnect ,r,eturned
ok 136 SyncValue matches
ok 137 Got right error
ok 138 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-25 16:26:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25, 16:26:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-25 16:26:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-07-25 16:26:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-25 16:26:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-25 16:26:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-25 16:26:24 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:26:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:26:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:26:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:26:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:26:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# multiConnect properly fails on legal but non-existent peerID
,2017-07-25 16:26:24 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-25 16:26:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:26:24 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-25 16:26:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-25 16:26:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-25 16:26:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-25 16:26:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-25 16:26:24 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:26:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-25 16:26:24 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-25 16:26:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-25 16:26:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
,2017-07-25 16:26:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E8684D1B-AD85-4B57-A3D0-BA4BFD952C42
[ThaliCore] Browser.startListening
2017-07-25 16:26:25 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-25 16:26:25 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-25 16:26:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 139 No error on starting
ok 140 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-25 16:26:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25, 16:26:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-25 16:26:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-07-25 16:26:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-25 16:26:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-25 16:26:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-25 16:26:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:26:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-25 16:26:25 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-25 16:26:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-25 16:26:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
,2017-07-25 16:26:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call disconnect with invalid peer id
,ok 141 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:26:26 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-25 16:26:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-25 16:26:26 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-25 16:26:26 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:5b11eaf7-c6df-4910-a245-322c59391d26
ok 142 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:26:26 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-25 16:26:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-25 16:26:26 - DEBUG t,haliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-25 16:26:26 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "45A0ED46-6443-4763-9D77-FD1894FD6FB9", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:45A0ED46-6443-4763-9D77-FD1894FD6FB9
2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-25 16:26:26, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-25 16:26:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 143 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Tha,liCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A36A438A-627C-41D5-A9D7-AE7EC38215C2
[ThaliCore] Browser.startListening
2017-07-25 16:26:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adv,e,rtisingActive":true}'
2017-07-25 16:26:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-25 16:26:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 144 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1633D717-BAB5-409E-9E10-582EE947BE7C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1633D717-BAB5-409E-9E10-582EE947BE7C", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D6DB2262-D0D6-4B7B-B142-443CB29EFA5D:0
2017-07-25 16:26:26 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"1633D717-BAB5-409E-9E10-582EE947BE7C","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D6DB2262-D0D6-4B7B-B142-443CB29EFA5D", generation: 0)
2017-07-25 16:26:26 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 1633D717-BAB5-409E-9E10-582EE947BE7C, (syncValue: UChS00xFpYtKnbDJfe2XhYJOsptf9Vqf)'
2017-07-25 16:26:26 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1633D717-BAB5-409E-9E10-582EE94,7BE7C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1633D717-BAB5-409E-9E10-582EE947BE7C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:,) peer:1633D717-BAB5-409E-9E10-582EE947BE7C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-25 16:26:26 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D6DB2262-D0D6-4B7B-B142-443CB29EFA5D","generation":0}'
2017-07-25 16:26:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-25 16:26:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8B6F3729-5EF7-4FD4-95BD-D867B9E218E4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8B6F3729-5EF7-4FD4-95BD-D867B9E218E4", generation: 0)
2017-07-25 16:26:27 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8B6F3729-5EF7-4FD4-95BD-D867B9E218E4","generation":0}'
2017-07-25 16:26:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-25 16:26:27 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-25 16:26:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3638CC74-F640-40BF-A15A-F9FFB9A8E833:0
[ThaliCore] BrowserM,anager.foundPeerHandler peer:Peer(uuid: "3638CC74-F640-40BF-A15A-F9FFB9A8E833", generation: 0)
2017-07-25 16:26:27 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3638CC74-F640-40BF-A15A-F9FFB9A8E833","generatio,n,":0}'
2017-07-25 16:26:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-25 16:26:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-25 16:26:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-25 16:26:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:45A0ED46-6443-4763-9D77-FD1894FD6FB9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "45A0ED46-6443-4763-9D77-FD1894FD6FB9", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:1633D717-BAB5-409E-9E10-582EE947BE7C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:16,33D717-BAB5-409E-9E10-582EE947BE7C:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "1633D717-BAB5-409E-9E10-582EE947BE7C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,633D717-BAB5-409E-9E10-582EE947BE7C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1633D717-BAB5-409E-9E10-582EE947BE7C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:1633D717-BAB5-409E-9E10-582EE947BE7C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:1633D717-BAB5-409E-9E10-582EE947BE7C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:D6DB2262-D0D6-4B7B-B142-443CB29EFA5D:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "D6DB2262-D0D6-4B7B-B142-443CB29EFA5D", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:1633D717-BAB5-409E-9E10-582EE947BE7C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:16,33D717-BAB5-409E-9E10-582EE947BE7C:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "1633D717-BAB5-409E-9E10-582EE947BE7C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,633D717-BAB5-409E-9E10-582EE947BE7C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1633D717-BAB5-409E-9E10-582EE947BE7C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:1633D717-BAB5-409E-9E10-582EE947BE7C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:1633D717-BAB5-409E-9E10-582EE947BE7C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1633D717-BAB5-409E-9E10-582EE947BE7C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:16,33D717-BAB5-409E-9E10-582EE947BE7C:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "1633D717-BAB5-409E-9E10-582EE947BE7C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,633D717-BAB5-409E-9E10-582EE947BE7C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1633D717-BAB5-409E-9E10-582EE947BE7C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:1633D717-BAB5-409E-9E10-582EE947BE7C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:1633D717-BAB5-409E-9E10-582EE947BE7C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:1633D717-BAB5-409E-9E10-582EE947BE7C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "1633D717-BAB5-409E-9E10-582EE947BE7C", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:1633D717-BAB5-409E-9E10-582EE947BE7C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:16,33D717-BAB5-409E-9E10-582EE947BE7C:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "1633D717-BAB5-409E-9E10-582EE947BE7C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:1633D717,-BAB5-409E-9E10-582EE947BE7C error: max retries exceeded
2017-07-25 16:26:37 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"UChS00xFpYtKnbDJfe2XhYJOsptf9Vqf","error":"Connection could not be established","portNumber":null}'
2017-0,7-25 16:26:37 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'UChS00xFpYtKnbDJfe2XhYJOsptf9Vqf', error: 'Connection could not be established', listeningPort: '%s''
2017-07-25 16:26:37 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"1633D717-BAB5-409E-9E10-582EE947BE7C","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-25 16:26:37 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-25 16:26:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"1633D717-BAB5-409E-9E10-582EE947BE7C","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-25 16:26:37 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-25 16:26:37 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-25 16:26:37 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 8B6F3729-5EF7-4FD4-95BD-D867B9E218E4 (syncValue: Q34RkZcD3mvXDlj287fj1NZ6GHPr96gg)'
2017-07-25 16:26:37 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8B6F3729-5EF7-4FD4-95BD-D867B9E218E4", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8B6F3729-5EF7-4FD4-95BD-D867B9E218E4", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8B6F3729-5EF7,-4FD4-95BD-D867B9E218E4:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-25 16:26:37 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-07-25 16:26:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:1633D717-BAB5-409E-9E10-582EE947BE7C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:8B6F3729-5EF7-4FD4-95BD-D867B9E218E4:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8B6F3729-5EF7-4FD4-95BD-D867B9E218E4:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:8B6F3729-5EF7-4FD4-95BD-D867B9E218E4:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "8B6F3729-5EF7-4FD4-95BD-D867B9E218E4", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61069
2017-07-25 16:26:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Q34RkZcD3mvXDlj287fj1NZ6GHPr96gg",,"error":null,"portNumber":61069}'
2017-07-25 16:26:41 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Q34RkZcD3mvXDlj287fj1NZ6GHPr96gg', error: 'null', listeningPort: '61069''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:8B6F3729-5EF7-4FD4-95BD-D867B9E218E4:0
,ok 145 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8B6F3729-5EF7-4FD4-95BD-D867B9E218E4", generation: 0) found active relay
,2017-07-25 16:26:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ZNprl1l2vTXPiKe2vKhsSwH9cUc1Otvq","error":null,"portNumber":61069}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8B6F3729-5EF7-4FD4-95BD-D867B9E218E4:0
ok 146 No error
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [6, 10]
ok 147 Ports equal
[ThaliCore] BrowserRelay.didOpenVirtua,lSocketStreamsHandler
,ok 148 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8B6F3729-5EF7-4FD4-95BD-D867B9E218E4", generation: 0) found active relay
,2017-07-25 16:26:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"C4z4QjAJYBgxk5rlWiYRbRGsltooUnPX","error":null,"portNumber":61069}'
,ok 149 No error
,ok 150 Ports equal
,# teardown
,2017-07-25 16:26:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-25 16:26:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-25 16:26:41 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-25 16:26:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:45A0ED46-6443-4763-9D77-FD1894FD6FB9
2017-07-25 16:26:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:26:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdat,e (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:8B6F3729-5EF7-4FD4-95BD-D867B9E218E4
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61069
[Thali,Core] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket exited RunLoop vsID:10
[ThaliCore] Session.disconnect() peer:8B6F3729-5EF7-4FD4-95BD-D867B9E218E4:0
[ThaliCore] VirtualSocket.closeStreams() vsID:,10
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:10 [6]
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:8B6F3729-5EF7-4FD4-95BD-D867B9E218E4:0
[ThaliCore] BrowserRelay.deinit
2017-07-25 16:26:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-25 16:26:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-25 16:26:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:26:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:26:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:26:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:26:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:26:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# initial peer discovery
,2017-07-25 16:26:42 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-07-25 16:26:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-25 16:26:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-25 16:26:43 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:26:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-25 16:26:43 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-25 16:26:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-25 16:26:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-25 16:26:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-07-25 16:26:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-07-25 16:26:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-25 16:26:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-25 16:26:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:26:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-25 16:26:44 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-25 16:26:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-25 16:26:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-25 16:26:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-07-25 16:26:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-07-25 16:26:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-25 16:26:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-25 16:26:45 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:26:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-25 16:26:45 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-25 16:26:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-25 16:26:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-25 16:26:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-07-25 16:26:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-07-25 16:26:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-25 16:26:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-25 16:26:45 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:26:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:26:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:26:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:26:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:26:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-07-25 16:26:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-07-25 16:26:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-25 16:26:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-25 16:26:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:26:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-25 16:26:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-25 16:26:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-25 16:26:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-25 16:26:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-07-25 16:26:46 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-07-25 16:26:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-25 16:26:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-25 16:26:46 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:26:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-25 16:26:46 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-25 16:26:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-25 16:26:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-25 16:26:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-25 16:26:49 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-25 16:26:49 - DEBUG createNativeListener: 'listening 61072'
ok 151 Should throw
,# teardown
,2017-07-25 16:26:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-25 16:26:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-25 16:26:49 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'listening 61074'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-25 16:26:50 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 152 initial connection state should be CONNECTED
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 153 final connection state should be DISCONNECTED
,# teardown
,2017-07-25 16:26:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-25 16:26:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-25 16:26:50 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-07-25 16:26:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-25 16:26:50 - DEBUG createNativeListener: 'listening 61077'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-25 16:26:50 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 154 tried to connect to right port
,ok 155 failed due to refused connection
,ok 156 routerPortConnectionFailed is emitted
,# teardown
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-25 16:26:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'listening 61081'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 157 Send/recvd #1 should be equal length
,ok 158 Send/recvd #1 should be same
,ok 159 Send/recvd #2 should be equal length
,ok 160 Send/recvd #2 should be same
,ok 161 Should be exactly 2 client sockets
,# teardown
,2017-07-25 16:26:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-25 16:26:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-25 16:26:50 - DEBUG createNativeListener: 'Native Server - close'
2017-07-25 16:26:50, - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
2017-07-25 16:26:50 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close',
2017-07-25 16:26:50 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
2017-07-25 16:26:50 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
2017-07-25 16:26:50 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection, to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'listening 61086'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-25 16:26:50 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2017-07-25 16:26:50 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node -, 0 - 0 - closed'
,ok 162 socket shouldn't close until after stream
ok 163 incoming remains open
# teardown
,2017-07-25 16:26:50 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-25 16:26:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-25 16:26:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-25 16:26:51 - DEBUG createNativeListener: 'Native Server - close'
2017-07-25 16:26:51, - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-25 16:26:51 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-07-25 16:26:51 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-25 16:26:51 - DEBUG createNativeListener: 'listening 61090'
,2017-07-25 16:26:51 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-25 16:26:51 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 164 we should not have gotten an error
,2017-07-25 16:26:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-25 16:26:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-07-25 16:26:51 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 165 socket shouldn't close until after incoming
ok 166 incoming is cleaned up
# teardown
,2017-07-25 16:26:51 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-25 16:26:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-25 16:26:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-25 16:26:51 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-25 16:26:51 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-25 16:26:51 - DEBUG createNativeListener: 'listening 61094'
,2017-07-25 16:26:51 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-25 16:26:51 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-25 16:26:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-25 16:26:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2017-07-25 16:26:51 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node -, 0 - 0 - closed'
2017-07-25 16:26:51 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 167 stream was closed
ok 168 incoming should survive
ok 169 mux should have no streams
,# teardown
,2017-07-25 16:26:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-25 16:26:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-25 16:26:51 - DEBUG createNativeListener: 'Native Server - close'
2017-07-25 16:26:51, - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-25 16:26:51 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'listening 61098'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-25 16:26:52 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 170 we should not have gotten an error
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 171 Buffers are identical
2017-07-25 16:26:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-25 16:26:52 - DEBUG createNativeListener: 'Native Server - close'
2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream, <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-07-25 16:26:52 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 172 native server is nulled out
ok 173 native server should be cl,osed
ok 174 incoming has been removed
ok 175 Incoming should be done
ok 176 The mux object should be closed
ok 177 The mux stream should be closed
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-25 16:26:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'listening 61102'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
,2017-07-25 16:26:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 178 native server is nulled out
,ok 179 native server should be closed
,ok 180 incoming has been removed
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-25 16:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-25 16:26:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-07-25 16:26:54 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-25 16:26:54 - DEBUG createNativeListener: 'listening 61154'
,2017-07-25 16:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-25 16:26:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 181 we should not have gotten an error
,2017-07-25 16:26:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 182 Buffers are identical
2017-07-25 16:26:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-07-25 16:26:54 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-25 16:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 183 server should be fine
ok 184 server should be open
ok 185 incoming has been removed
ok 186 The mux object should be clos,ed
ok 187 The mux stream should be closed
2017-07-25 16:26:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-25 16:26:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-25 16:26:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-25 16:26:55 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-25 16:26:55 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-25 16:26:55 - DEBUG createNativeListener: 'listening 61158'
,2017-07-25 16:26:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-25 16:26:55 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 188 we should not have gotten an error
,2017-07-25 16:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 189 Buffers are identical
,2017-07-25 16:26:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
,2017-07-25 16:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-25 16:26:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-25 16:26:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 190 server should be fine
,ok 191 server should be open
,ok 192 incoming has been removed
,ok 193 The mux object should be closed
,ok 194 The mux stream should be closed
,# teardown
,2017-07-25 16:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-25 16:26:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-25 16:26:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-25 16:26:55 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# can create servers manager
,ok 195 serversManager must not be null
ok 196 serversManager must be an object
,# teardown
,# setup
,# calling stop without start causes error
,ok 197 We need to call start first
,# teardown
,# setup
,# can start/stop servers manager
,2017-07-25 16:26:56 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-25 16:26:56 - DEBUG createNativeListener: 'listening 61161'
ok 198 port must be in range
,# teardown
,2017-07-25 16:26:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-25 16:26:56 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-25 16:26:56 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-25 16:26:56 - DEBUG createNativeListener: 'listening 61162'
ok 199 second start should return same port
,# teardown
,2017-07-25 16:26:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-25 16:26:56 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-25 16:26:56 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-25 16:26:56 - DEBUG createNativeListener: 'listening 61164'
,2017-07-25 16:26:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-25 16:26:56 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 200 we should be connected
2017-07-25 16:26:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 201 now we are disconnected
,2017-07-25 16:26:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-25 16:26:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-25 16:26:56 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-07-25 16:26:56 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
ok 202 Passed bogus id
2017-07-25 16:26:56 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
ok 203 Passed good id but bogus port
2017-07-25 16:26:56 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
ok 204 Passed right context
ok 205 Right server
ok 206 No error should be set
ok 207 Ret,ry should be false
ok 208 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 61166
,ok 209 should be equal
# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-25 16:26:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-25 16:26:57 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-25 16:26:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-25 16:26:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-25 16:26:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-25 16:26:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-25 16:26:57 - DEBUG thaliMobileNativeWrapper: 'Method disc,overyAdvertisingStateUpdateNonTCP registered to native'
2017-07-25 16:26:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-25 16:26:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-25 16:26:57 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-25 16:26:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-25 16:26:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-25 16:26:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B037CFD3-4481-4DF6-9B8E-99CE54716E19", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:B037CFD3-4481-4DF6-9B8E-99CE54716E19
,2017-07-25 16:26:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-25 16:26:57 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-25 16:26:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 210 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:19C99E7C-5CB4-47FC-985C-860D669,DEBF5
[ThaliCore] Browser.startListening
2017-07-25 16:26:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-25 16:26:57 - INFO thaliMobile: 'Received state ({"discover,yActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-25 16:26:57 - INFO thaliMob,ile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 211 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3638CC74-F640-40BF-A15A-F9FFB9A8E833:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3638CC74-F640-40BF-A15A-F9FFB9A8E833", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8B6F3729-5EF7-4FD4-95BD-D867B9E218E4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8B6F3729-5EF7-4FD4-95BD-D867B9E218E4", generation: 0)
2017-07-25 16:26:57 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3638CC74-F640-40BF-A15A-F9FFB9A8E833","generation":0}'
,2017-07-25 16:26:57 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3638CC74-F640-40BF-A15A-F9FFB9A8E833 (syncValue: dnVH9OR3PCPan5ecOOiySLF9DT7O6Nyt)'
,2017-07-25 16:26:57 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3638CC74-F640-40BF-A15A-F9FFB9A8E833", generation: 0) creating a new relay
[Tha,liCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3638CC74-F640-40BF-A15A-F9FFB9A8E833", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3638CC74-F640-40BF-A15A-F9FFB9A8E833:0
[T,haliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-25 16:26:57 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8B6F3729-5EF7-4FD4-95BD-D867B9E218E4","generation":0}'
[ThaliCore] Browser.browser(_:lostPeer:) lost peer:3638CC74-F640-40BF-A15A-F9FFB9A8E833:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "3638CC74-F640-40BF-A15A-F9FFB9A8E833", generation: 0)
2017-07-25 16:26:57 - DEBUG thaliMobileNativeTestUtils: 'Already r,unning test!'
2017-07-25 16:26:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A3E339D2-70CF-4D85-BCE6-50D4FB63BF85:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A3E339D2-70CF-4D85-BCE6-50D4FB63BF85", generation: 0)
2017-07-25 16:26:58 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"A3E339D2-70CF-4D85-BCE6-50D4FB63BF85","generation":0}'
2017-07-25 16:26:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-25 16:26:58 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:56E48F0C-5C40-4592-82B8-A52B84B2813F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "56E48F0C-5C40-4592-82B8-A52B84B2813F", generation: 0)
2017-07-25 16:26:58 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"56E48F0C-5C40-4592-82B8-A52B84B2813F","generation":0}'
2017-07-25 16:26:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-25 16:26:58 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-25 16:26:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B037CFD3-4481-4DF6-9B8E-99CE54716E19:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B037CFD3-4481-4DF6-9B8E-99CE54716E19", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:3638CC74-F640-40BF-A15A-F9FFB9A8E833:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:36,38CC74-F640-40BF-A15A-F9FFB9A8E833:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "3638CC74-F640-40BF-A15A-F9FFB9A8E833", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,638CC74-F640-40BF-A15A-F9FFB9A8E833", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3638CC74-F640-40BF-A15A-F9FFB9A8E833", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-25 16:27:00 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"dnVH9OR3PCPan5ecOOiySLF9DT7O6Nyt","error":"Peer is unavailable",,"portNumber":null}'
2017-07-25 16:27:00 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'dnVH9OR3PCPan5ecOOiySLF9DT7O6Nyt', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-25 16:27:00 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"3638CC74-F640-40BF-A15A-F9FFB9A8E833","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-25 16:27:00 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-25 16:27:00 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3638CC74-F640-40BF-A15A-F9FFB9A8E833","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-25 16:27:00 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-25 16:27:00 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-25 16:27:00 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 8B6F3729-5EF7-4FD4-95BD-D867B9E218E4 (syncValue: Z9BcoQJ0F9xUzb9TSJ5G4Zr,Ed8hQ1Nyf)'
2017-07-25 16:27:00 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8B6F3729-5EF7-4FD4-95BD-D867B9E218E4", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8B6F3729-5EF7-4FD4-95BD-D867B9E218E4", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8B6F3729-5EF7-4FD4-95BD-D867B9E218E4:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-25 16:27:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-25 16:27:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:3638CC74-F640-40BF-A15A-F9FFB9A8E833:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:8B6F3729-5EF7-4FD4-95BD-D867B9E218E4:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "8B6F3729-5EF7-4FD4-95BD-D867B9E218E4", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:117E516B-B78F-493E-A3A5-2C5D5138CE0D
[ThaliCore] Advertiser: session connected Peer(uuid: "B037CFD3-4481-4DF6-9B8E-99CE54716E19", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:117E516B-B78F-493E-A3A5-2C5D5138CE0D state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:8B6F3729-5EF7-4FD4-95BD-D867B9E218E4:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:8B,6F3729-5EF7-4FD4-95BD-D867B9E218E4:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "8B6F3729-5EF7-4FD4-95BD-D867B9E218E4", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,B6F3729-5EF7-4FD4-95BD-D867B9E218E4", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8B6F3729-5EF7-4FD4-95BD-D867B9E218E4", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-25 16:27:02 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Z9BcoQJ0F9xUzb9TSJ5G4ZrEd8hQ1Nyf","error":"Peer is unavailable",,"portNumber":null}'
2017-07-25 16:27:02 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Z9BcoQJ0F9xUzb9TSJ5G4ZrEd8hQ1Nyf', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-25 16:27:02 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"8B6F3729-5EF7-4FD4-95BD-D867B9E218E4","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-25 16:27:02 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-25 16:27:02 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"8B6F3729-5EF7-4FD4-95BD-D867B9E218E4","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-25 16:27:02 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-25 16:27:02 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-25 16:27:02 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for A3E339D2-70CF-4D85-BCE6-50D4FB63BF85 (syncValue: cLB1ByWjooulJWZnG8afXpQfwRPa53NC)'
2017-07-25 16:27:02 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A3E339D2-70CF-4D85-BCE6-50D4FB63BF85", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A3E339D2-70CF-4D85-BCE6-50D4FB63BF85", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A3E339D2-70CF-4D85-BCE6-50D4F,B63BF85:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-25 16:27:02 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:8B6F3729-5EF7-4FD4-95BD-D867B9E218E4:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:A3E339D2-70CF-4D85-BCE6-50D4FB63BF85:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0EA925B4-0B46-484F-8B3B-75C44871A9AD
[ThaliCore] Advertiser: session connected Peer(uuid: "B037CFD3-4481-4DF6-9B8E-99CE54716E19", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:0EA925B4-0B46-484F-8B3B-75C44871A9AD state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:117E516B-B78F-493E-A3A5-2C5D5138CE0D
,2017-07-25 16:27:04 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,[ThaliCore] Session.session(_:peer:didChange:) peer:117E516B-B78F-493E-A3A5-2C5D5138CE0D state: connecting -> connected
,2017-07-25 16:27:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:27:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A3E339D2-70CF-4D85-BCE6-50D4FB63BF85:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:A3E339D2-70CF-4D85-BCE6-50D4FB63BF85:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "A3E339D2-70CF-4D85-BCE6-50D4FB63BF85", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61177
,2017-07-25 16:27:06 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"cLB1ByWjooulJWZnG8afXpQfwRPa53NC","error":null,"portNumber":61177}'
,2017-07-25 16:27:06 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'cLB1ByWjooulJWZnG8afXpQfwRPa53NC', error: 'null', listeningPort: '61177''
,ok 212 should be equal
,2017-07-25 16:27:06 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 56E48F0C-5C40-4592-82B8-A52B84B2813F (syncValue: CMFBTosIZDOdSf6l7UtZViNJqfGHTkOq)'
,2017-07-25 16:27:06 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "56E48F0C-5C40-4592-82B8-A52B84B2813F", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "56E48F0C-5C40-4592-82B8-A52B84B2813F", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:56E48F0C-5C40-4592-82B8-A52B84B2813F:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:56E48F0C-5C40-4592-82B8-A52B84B2813F:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0EA925B4-0B46-484F-8B3B-75C44871A9AD
,[ThaliCore] Session.session(_:peer:didChange:) peer:0EA925B4-0B46-484F-8B3B-75C44871A9AD state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:56E48F0C-5C40-4592-82B8-A52B84B2813F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:56E48F0C-5C40-4592-82B8-A52B84B2813F:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "56E48F0C-5C40-4592-82B8-A52B84B2813F", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61181
2017-07-25 16:27:09 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"CMFBTosIZDOdSf6l7UtZViNJqfGHTkOq",,"error":null,"portNumber":61181}'
2017-07-25 16:27:09 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'CMFBTosIZDOdSf6l7UtZViNJqfGHTkOq', error: 'null', listeningPort: '61181''
,ok 213 should be equal
# teardown
,2017-07-25 16:27:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:27:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:27:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:27:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:27:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:27:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:27:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:27:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:27:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:27:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:27:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:27:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:28:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:28:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
2017-07-25 16:28:09 - INFO, CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server ,that is not listening yet witheatNotRunning set to true'
2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOG,GER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoi,n,ts plugin delay interval'
2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-07-25 16:28:09 - INFO Coordin,atedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue, and run in order'
2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
2017-07-25 16:,28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
2017-07-25 16:28:09 - INF,O, CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER resu,lt: passed - another'
2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
2017-07-25 16:28:09 - INFO CoordinatedClient: '***T,EST_LOGGER result: passed - test sinon sansbox spy'
2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox ,stub override'
2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
2017-07-25 ,1,6:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
2017-07-25 16:28:09 - INFO CoordinatedClient: '***,TEST_LOGGER result: skipped - onPeerLost calls jxcore'
2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call ,start/stopListeningForAdvertisements'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiConnect properly fails on legal but non-existent peerID'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with invalid syncValue'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call disconnect with invalid peer id'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - disconnect doesn't fail on plausible but bogus peer ID'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Get same port when trying to connect multiple times on iOS'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - initial peer discovery'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 1'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 2'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - check latest peer discovery'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Set up for no peer discovery test'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - no peer discovery'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits incomingConnectionState'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server connections all up'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can create servers manager'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling stop without start causes error'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can start/stop servers manager'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connection'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single local http request'
,2017-07-25 16:28:09 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - Single coordinated request ios native, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE,5910/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/tim,ers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1
''
2017-07-25 16:28:09 - ERROR Coordi,natedClient: 'failed to run unit tests, platformName: 'ios''
,2017-07-25 16:28:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:28:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:28:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:28:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:28:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:28:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:28:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:28:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:28:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:28:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:29:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:29:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:29:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:29:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:29:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:29:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:29:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:29:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:29:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:29:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:29:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:29:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:30:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:30:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:30:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:30:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:30:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:30:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:30:29 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:350:16
$9@timers.js:120:1
''
,2017-07-25 16:30:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:30:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:30:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:30:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:30:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:30:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:31:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:31:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:31:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:31:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:31:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:31:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:31:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:31:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:31:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:31:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:31:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:31:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:32:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:32:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:32:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:32:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:32:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:32:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:32:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:32:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:32:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:32:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:32:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:32:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:33:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:33:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:33:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:33:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:33:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:33:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:33:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:33:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:33:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:33:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:33:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:33:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:34:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:34:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:34:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:34:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:34:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:34:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:34:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:34:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:34:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:34:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:34:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:34:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:35:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:35:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:35:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:35:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:35:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:35:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:35:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:35:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:35:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:35:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:36:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:36:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:36:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:36:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:36:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:36:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:36:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:36:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4,DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:36:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:36:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:36:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:36:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:37:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:37:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:37:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:37:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:37:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:37:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:37:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:37:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:37:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:37:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:37:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:37:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:38:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:38:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:38:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:38:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:38:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:38:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:38:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:38:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:38:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:38:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:38:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:38:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:39:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:39:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:39:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:39:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:39:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:39:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:39:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:39:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:39:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:39:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:39:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:39:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:40:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:40:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:40:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:40:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:40:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:40:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4,DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:40:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:40:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:40:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:40:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:40:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:40:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:41:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:41:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:41:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:41:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:41:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:41:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4,DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:41:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:41:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:41:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:41:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:41:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:41:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4,DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:42:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:42:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:42:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:42:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:42:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:42:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:42:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:42:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:42:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:42:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:42:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:42:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:43:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:43:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:43:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:43:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:43:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:43:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-25 16:43:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC,3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:43:35 - ERROR CoordinatedClient: 'reconnect_failed error: 'undefined', description: '%s,',, stack: '%s''
2017-07-25 16:43:35 - DEBUG CoordinatedClient: 'test client failed'
2017-07-25 16:43:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers,/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxc,ore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88CA3AA5-8AE6-4DC3-82BB-A3738BEE5910/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-25 16:,4,3:35 - DEBUG CoordinatedThaliTape: 'all tests succeed'
2017-07-25 16:43:35 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****'

```
