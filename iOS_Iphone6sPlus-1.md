#### Test 14182954130f6dc3_iOS_Iphone6sPlus-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/14182954130f6dc3/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/1C99C174-5D9D-4417-9CF2-2061229753A8/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'
,Executing commands in '/tmp/1C99C174-5D9D-4417-9CF2-2061229753A8/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/14182954130f6dc3/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/14182954130f6dc3/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62694"
,(lldb)     command script import "/tmp/1C99C174-5D9D-4417-9CF2-2061229753A8/fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.py"
,(lldb)     command script add -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready
JXcore engine is started
,2017-09-19 12:44:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:44:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:44:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:44:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:44:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-09-19 12:44:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:44:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserMa,nager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7F6A7166-7511-440B-B60E-FCAE6C6ACD56", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:7F6A7166-7511-440B-B60E-FCAE6C6ACD56
,Optional(true)
Optional(false)
AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A50ED34B-4860-411D-B58E-,FF61F4DD4153
[ThaliCore] Browser.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:EEAF6555-686B-45FC-AD4F-F52343EC8400
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8027E18C-D961-47A0-8A45-D3B7BC025D3B", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:8027E18C-D961-47A0-8A45-D3B7BC025D3B
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8027E18C-D961-47A0-8A45-D3B7BC025D3B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8027E18C-D961-47A0-8A45-D3B7BC025D3B", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCorrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-09-19 12:44:22 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.303822934627533
,2017-09-19 12:44:22 - DEBUG UnitTest_app: 'My device name is: 'Apple-Iphone6sPlus-1''
,2017-09-19 12:44:22 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:8027E18C-D961-47A0-8A45-D3B7BC025D3B:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "8027E18C-D961-47A0-8A45-D3B7BC025D3B", generation: 0)
,2017-09-19 12:44:23 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-09-19 12:44:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-09-19 12:44:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-09-19 12:44:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-09-19 12:44:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-09-19 12:44:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-09-19 12:44:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-09-19 12:44:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-09-19 12:44:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-09-19 12:44:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-09-19 12:44:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-09-19 12:44:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-09-19 12:44:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-09-19 12:44:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-09-19 12:44:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-09-19 12:44:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-09-19 12:44:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-09-19 12:44:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-09-19 12:44:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-09-19 12:44:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-09-19 12:44:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-09-19 12:44:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-09-19 12:44:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-09-19 12:44:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-09-19 12:44:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-09-19 12:44:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-09-19 12:44:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-09-19 12:44:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-09-19 12:44:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-09-19 12:44:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-09-19 12:44:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-09-19 12:44:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-09-19 12:44:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-09-19 12:44:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-09-19 12:44:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-09-19 12:44:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-09-19 12:44:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-09-19 12:44:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-09-19 12:44:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-09-19 12:44:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-09-19 12:44:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-09-19 12:44:25 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-09-19 12:44:25 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-09-19 12:44:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:44:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:44:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:44:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:44:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:44:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:44:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:44:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:44:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:45:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:45:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:45:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:45:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:45:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:45:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:45:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:45:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:45:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:45:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:45:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:45:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:46:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:46:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:46:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:46:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:46:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:46:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:46:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:46:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:46:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:46:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:46:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:46:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:47:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:47:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:47:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:47:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:47:22 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-09-19 12:47:22 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-09-19 12:47:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 1 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll with promise
,2017-09-19 12:47:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-09-19 12:47:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-09-19 12:47:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-09-19 12:47:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-09-19 12:47:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-09-19 12:47:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-09-19 12:47:48 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
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
,2017-09-19 12:48:06 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-09-19 12:48:10 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-09-19 12:48:14 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
,2017-09-19 12:48:20 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-09-19 12:48:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:48:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:48:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:48:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-09-19 12:48:20 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-09-19 12:48:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-09-19 12:48:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-09-19 12:48:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-09-19 12:48:21 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-09-19 12:48:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:48:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:48:21 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:48:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:48:21 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:48:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:48:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:48:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E375327B-4D46-4C20-9C64-6747DCB06D0C
[ThaliCore] Browser.startListening
,2017-09-19 12:48:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-09-19 12:48:22 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:48:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-09-19 12:48:22 - DEBUG thaliMobileNativeWrapper: 'disco,veryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:48:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without e,r,ror
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:48:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:48:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:48:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-09-19 12:48:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:48:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:48:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:48:22 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:48:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-09-19 12:48:22 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-09-19 12:48:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-09-19 12:48:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-09-19 12:48:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7011028E-56CE-4108-8AE1-3F1C0EC4FD7E
[ThaliCore] Browser.startListening
,2017-09-19 12:48:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-09-19 12:48:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:48:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 64 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-09-19 12:48:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"di,scoveryActive":true,"advertisingActive":false}'
2017-09-19 12:48:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":",B,OTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:48:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-09-19 12:48:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19, 12:48:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:48:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-09-19 12:48:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:48:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:48:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:48:23 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:48:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-09-19 12:48:23 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-09-19 12:48:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-09-19 12:48:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-09-19 12:48:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:48:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:48:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:48:26 - ,DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:48:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call sto,pListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:48:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:48:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:48:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-09-19 12:48:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:48:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:48:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:48:26 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:48:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-09-19 12:48:26 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-09-19 12:48:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-09-19 12:48:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-09-19 12:48:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8A6CD63F-ACC9-40A6-8EED-B10D7D103E78", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:8A6CD63F-ACC9-40A6-8EED-B10D7D103E78
,2017-09-19 12:48:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 12:48:27 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:48:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:8A6CD63F-ACC9-40A6-8EED-B10D7D103E78
2017-09-19 12:48:27 ,- DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:48:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Can call ,s,topAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:48:28 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-09-19 12:48:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:48:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "61B7FF4C-6F2E-419F-9224-507B124738F5", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:61B7FF4C-6F2E-419F-9224-507B124738F5
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-09-19 12:48:28 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-09-19 12:48:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 70 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "61B7FF4C-6F2E-419F-9224-507B124738F5", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:61B7FF4C-6F2E-419F-9224-507B124738F5
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-09-19 12:48:28 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-09-19 12:48:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-09-19 12:48:28 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-09-19 12:48:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:61B7FF4C-6F2E-419F-9224-507B124738F5
,[ThaliCore] Advertiser.stopAdvertising() peerID:61B7FF4C-6F2E-419F-9224-507B124738F5
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:48:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:48:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:48:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:48:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:48:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 72 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:48:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:48:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 73 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:48:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:48:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:48:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:48:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:48:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:48:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:48:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:48:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:48:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:48:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:48:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:48:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F99EF8B7-1AD6-4A8B-9090-EC705C6AD918", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:F99EF8B7-1AD6-4A8B-9090-EC705C6AD918
,2017-09-19 12:48:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 12:48:30 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:48:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F4BDCAF9-BC6E-4EC1-AB53-20B22B58F,297
[ThaliCore] Browser.startListening
2017-09-19 12:48:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-09-19 12:48:30 - INFO thaliMobile: 'Received state ({"discovery,A,ctive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:48:30 - INFO thaliMobil,e: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F99EF8B7-1AD6-4A8B-9090-EC705C6AD918:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F99EF8B7-1AD6-4A8B-9090-EC705C6AD918", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:90D276E0-9265-451E-B424-F09E6598D6BE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "90D276E0-9265-451E-B424-F09E6598D6BE", generation: 0)
ok 76 peers must be an array,
ok 77 peers must not be zero-length
ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
ok 79 peerIdentifier must be a string
ok 80 generation must be a number
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) f,ound peer:8C630424-8DA2-471A-94E5-D7030EA7C764:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8C630424-8DA2-471A-94E5-D7030EA7C764", generation: 0)
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-09-19 12:48:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 ,12:48:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-09-19 12:48:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:F99EF8B7-1AD6-4A8B-9090-E,C705C6AD918
2017-09-19 12:48:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:48:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
2017-09-19 12:48:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:48:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:48:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:48:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:48:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:48:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:48:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:48:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DF13A8A5-46A4-4EA6-9302-580CEBBE797A", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:DF13A8A5-46A4-4EA6-9302-580CEBBE797A
,2017-09-19 12:48:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 12:48:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:48:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 81 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FB5AF2C2-F5C6-4A74-BC34-07703243569D
[ThaliCore] Browser.startListe,ning
,2017-09-19 12:48:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-09-19 12:48:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:48:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:90D276E0-9265-451E-B424-F09E6598D6BE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "90D276E0-9265-451E-B424-F09E6598D6BE", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8C630424-8DA2-471A-94E5-D7030EA7C764:0
2017-09-19 12:48:33 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"90D276E0-9265-451E-B424-F09E6598D6,BE","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8C630424-8DA2-471A-94E5-D7030EA7C764", generation: 0)
,2017-09-19 12:48:33 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 90D276E0-9265-451E-B424-F09E6598D6BE (syncValue: dCVyEyAHeqRVFy8l3TZOyZs640b5XP6c)'
,2017-09-19 12:48:33 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "90D276E0-9265-451E-B424-F09E6598D6BE", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "90D276E0-9265-451E-B424-F09E6598D6BE", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:90D276E0-9265-451E-B424-F09E6598D6BE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-09-19 12:48:33 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8C630424-8DA2-471A-94E5-D7030EA7C764","generation":0}'
,2017-09-19 12:48:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:48:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:90D276E0-9265-451E-B424-F09E6598D6BE:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "90D276E0-9265-451E-B424-F09E6598D6BE", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:8C630424-8DA2-471A-94E5-D7030EA7C764:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "8C630424-8DA2-471A-94E5-D7030EA7C764", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:396621D0-FC75-4B94-8457-AEC9F0E309BF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "396621D0-FC75-4B94-8457-AEC9F0E309BF", generation: 0)
2017-09-19 12:48:34 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAv,ailable":true,"peerIdentifier":"396621D0-FC75-4B94-8457-AEC9F0E309BF","generation":0}'
2017-09-19 12:48:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DF13A8A5-46A4-4EA6-9302-580CEBBE797A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DF13A8A5-46A4-4EA6-9302-580CEBBE797A", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9FE7713F-E1CA-49E3-8F90-9C5C97270C09:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9FE7713F-E1CA-49E3-8F90-9C5C97270C09", generation: 0)
2017-09-19 12:48:35 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9FE7713F-E1CA-49E3-8F90-9C5C97270C09","generation":0}'
2017-09-19 12:48:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:48:35 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:90D276E0-9265-451E-B424-F09E6598D6BE:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:90,D276E0-9265-451E-B424-F09E6598D6BE:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "90D276E0-9265-451E-B424-F09E6598D6BE", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,0D276E0-9265-451E-B424-F09E6598D6BE", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "90D276E0-9265-451E-B424-F09E6598D6BE", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-09-19 12:48:36 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"dCVyEyAHeqRVFy8l3TZOyZs640b5XP6c","error":"Peer is unavailable",,"portNumber":null}'
2017-09-19 12:48:36 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'dCVyEyAHeqRVFy8l3TZOyZs640b5XP6c', error: 'Peer is unavailable', listeningPort: '%s''
,2017-09-19 12:48:36 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-09-19 12:48:36 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 396621D0-FC75-4B94-8457-AEC9F0E309BF (syncValue: 0cB9mSp04sgjmBSjVUMvR98,3fgKWCxg3)'
2017-09-19 12:48:36 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "396621D0-FC75-4B94-8457-AEC9F0E309BF", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "396621D0-FC75-4B94-8457-AEC9F0E309BF", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:396621D0-FC75-4B94-8457-AEC9F,0E309BF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-09-19 12:48:36 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:90D276E0-9265-451E-B424-F09E6598D6BE:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C6CD6F16-4689-46DE-AC05-B5E6DA0C7DAC
[ThaliCore] Advertiser: session connected Peer(uuid: "DF13A8A5-46A4-4EA6-9302-580CEBBE797A", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:C6CD6F16-4689-46DE-AC05-B5E6DA0C7DAC state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:396621D0-FC75-4B94-8457-AEC9F0E309BF:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:396621D0-FC75-4B94-8457-AEC9F0E309BF:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:396621D0-FC75-4B94-8457-AEC9F0E309BF:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "396621D0-FC75-4B94-8457-AEC9F0E309BF", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62104
,2017-09-19 12:48:39 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0cB9mSp04sgjmBSjVUMvR983fgKWCxg3","error":null,"portNumber":62104}'
,2017-09-19 12:48:39 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '0cB9mSp04sgjmBSjVUMvR983fgKWCxg3', error: 'null', listeningPort: '62104''
,2017-09-19 12:48:39 - INFO testThaliMobileNative: ''
,ok 83 Must have listeningPort
,ok 84 listeningPort must be a number
,ok 85 listening port should not be 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C6CD6F16-4689-46DE-AC05-B5E6DA0C7DAC
,# teardown
,[ThaliCore] Session.session(_:peer:didChange:) peer:C6CD6F16-4689-46DE-AC05-B5E6DA0C7DAC state: connecting -> connected
,2017-09-19 12:48:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-09-19 12:48:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 12:48:40 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:48:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:DF13A8A5-46A4-4EA6-9302-580CEBBE797A
,2017-09-19 12:48:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:48:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.disconnect peer:396621D0-FC75-4B94-8457-AEC9F0E309BF
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:62104
[ThaliCore] Session.disconnect,() peer:396621D0-FC75-4B94-8457-AEC9F0E309BF:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:396621D0-FC75-4B94-8457-AEC9F0E309BF:0
,[ThaliCore] BrowserRelay.deinit
,2017-09-19 12:48:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:48:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:48:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:48:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:48:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:48:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:48:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:48:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:C6CD6F16-4689-46DE-AC05-B5E6DA0C7DAC state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "DF13A8A5-46A4-4EA6-9302-580CEBBE797A", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:C6CD6F16-4689-46DE-AC05-B5E6DA0C7DAC
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] Session.deinit peer:C6CD6F16-4689-46DE-AC05-B5E6DA0C7DAC
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9788CAA8-E98E-4E3D-8BF2-43BDD1B37C3C", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:9788CAA8-E98E-4E3D-8BF2-43BDD1B37C3C
2017-09-19 12:48:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 12:48:41, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-09-19 12:48:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Thal,iCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4BDC289B-F8E1-4389-85C8-925084ABFFE5
[ThaliCore] Browser.startListening
2017-09-19 12:48:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adve,r,tisingActive":true}'
2017-09-19 12:48:41 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"rout,er":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:48:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:396621D0-FC75-4B94-8457-AEC9F0E309BF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "396621D0-FC75-4B94-8457-AEC9F0E309BF", generation: 0)
2017-09-19 12:48:41 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"396621D0-FC75-4B94-8457-AEC9F0E309BF","generation":0}'
2017-09-19 12:48:41 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 396621D0-FC75-4B94-8457-AEC9F0E309BF, (syncValue: fsuQCaFjqEQqxiOAySW8euA8AKeIn3kp)'
2017-09-19 12:48:41 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "396621D0-FC75-4B94-8457-AEC9F0E,309BF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "396621D0-FC75-4B94-8457-AEC9F0E309BF", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:) peer:396621D0-FC75-4B94-8457-AEC9F0E309BF:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9FE7713F-E1CA-49E3-8F90-9C5C97270C09:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9FE7713F-E1CA-49E3-8F90-9C5C97270C09,", generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-09-19 12:48:41 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailabl,e":true,"peerIdentifier":"9FE7713F-E1CA-49E3-8F90-9C5C97270C09","generation":0}'
2017-09-19 12:48:41 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:48:41 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FDB7528A-6D5A-476F-989F-0B13DC545963:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FDB7528A-6D5A-476F-989F-0B13DC545963", generation: 0)
2017-09-19 12:48:42 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FDB7528A-6D5A-476F-989F-0B13DC545963","generation":0}'
2017-09-19 12:48:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:48:42 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-09-19 12:48:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE", generation: 0)
,2017-09-19 12:48:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE","generation":0}'
,2017-09-19 12:48:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:48:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:48:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:48:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9788CAA8-E98E-4E3D-8BF2-43BDD1B37C3C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9788CAA8-E98E-4E3D-8BF2-43BDD1B37C3C", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:396621D0-FC75-4B94-8457-AEC9F0E309BF:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "396621D0-FC75-4B94-8457-AEC9F0E309BF", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:9FE7713F-E1CA-49E3-8F90-9C5C97270C09:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "9FE7713F-E1CA-49E3-8F90-9C5C97270C09", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:396621D0-FC75-4B94-8457-AEC9F0E309BF:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:396621D0-FC75-4B94-8457-AEC9F0E309BF:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "396621D0-FC75-4B94-8457-AEC9F0E309BF", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,96621D0-FC75-4B94-8457-AEC9F0E309BF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "396621D0-FC75-4B94-8457-AEC9F0E309BF", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-09-19 12:48:44 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"fsuQCaFjqEQqxiOAySW8euA8AKeIn3kp","error":"Peer is unavailable",,"portNumber":null}'
2017-09-19 12:48:44 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'fsuQCaFjqEQqxiOAySW8euA8AKeIn3kp', error: 'Peer is unavailable', listeningPort: '%s''
,2017-09-19 12:48:44 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-09-19 12:48:44 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for FDB7528A-6D5A-476F-989F-0B13DC545963 (syncValue: 8oh07UIYarAM5jUyZCWdVva,HoxI8xYv6)'
2017-09-19 12:48:44 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FDB7528A-6D5A-476F-989F-0B13DC545963", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FDB7528A-6D5A-476F-989F-0B13DC545963", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FDB7528A-6D5A-476F-989F-0B13D,C545963:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-09-19 12:48:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:396621D0-FC75-4B94-8457-AEC9F0E309BF:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:FDB7528A-6D5A-476F-989F-0B13DC545963:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FDB7528A-6D5A-476F-989F-0B13DC545963:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:FDB7528A-6D5A-476F-989F-0B13DC545963:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "FDB7528A-6D5A-476F-989F-0B13DC545963", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62110
2017-09-19 12:48:47 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8oh07UIYarAM5jUyZCWdVvaHoxI8xYv6",,"error":null,"portNumber":62110}'
2017-09-19 12:48:47 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '8oh07UIYarAM5jUyZCWdVvaHoxI8xYv6', error: 'null', listeningPort: '62110''
,Connecting to the localhost:62110
,Connected to the localhost:62110
2017-09-19 12:48:47 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
2017-09-19 12:48:47 - DEBUG testThaliMobileNative: 'Client data flushed'
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCor,e] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FDB7528A-6D5A-476F-989F-0B13DC545963:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FDB7528A-6D5A-476F-989F-0B13DC545963:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 88 got the same data back
,# teardown
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:1
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,2017-09-19 12:48:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-09-19 12:48:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 12:48:59 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:48:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:9788CAA8-E98E-4E3D-8BF2-43BDD1B37C3C
,2017-09-19 12:48:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:48:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.disconnect peer:FDB7528A-6D5A-476F-989F-0B13DC545963
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:62110
[ThaliCore] Session.disconnect,() peer:FDB7528A-6D5A-476F-989F-0B13DC545963:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:FDB7528A-6D5A-476F-989F-0B13DC545963:0
,2017-09-19 12:48:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:48:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:48:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:48:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-09-19 12:48:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:48:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:48:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:48:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4FF4D8AD-7583-4E46-A0AE-07975F33B677", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:4FF4D8AD-7583-4E46-A0AE-07975F33B677
,2017-09-19 12:48:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 12:48:59 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:48:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 89 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:251D042D-E8D6-4B26-B41F-5B75FC327420
[ThaliCore] Browser.startListe,ning
2017-09-19 12:48:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-09-19 12:48:59 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":tru,e}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-09-19 12:48:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FDB7528A-6D5A-476F-989F-0B13DC545963:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FDB7528A-6D5A-476F-989F-0B13DC545963", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE", generation: 0)
2017-09-19 12:49:00 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FDB7528A-6D5A-476F-989F-0B13DC545963","generation":0}'
,2017-09-19 12:49:00 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for FDB7528A-6D5A-476F-989F-0B13DC545963 (syncValue: Y4Jor2Yxt8mAH05NpFQ118iMB82mpBHH)'
2017-09-19 12:49:00 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FDB7528A-6D5A-476F-989F-0B13DC545963", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FDB7528A-6D5A-476F-989F-0B13DC545963", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FDB7528A-6D5A-476F-989F-0B13DC545963:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,2017-09-19 12:49:00 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE","generation":0}'
,2017-09-19 12:49:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:49:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "79AF77E4-D3C7-4DFF-9AFD-79675AC9E4DE", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:4FF4D8AD-7583-4E46-A0AE-07975F33B677:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4FF4D8AD-7583-4E46-A0AE-07975F33B677", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FA542401-F573-4621-9DBD-9F1F61CD325C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FA542401-F573-4621-9DBD-9F1F61CD325C", generation: 0)
2017-09-19 12:49:00 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FA542401-F573-4621-9DBD-9F1F61CD325C","generation":0}'
2017-09-19 12:49:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:49:00 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:09FDF337-6845-4807-9835-1630B55E626D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "09FDF337-6845-4807-9835-1630B55E626D", g,eneration: 0)
,2017-09-19 12:49:00 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"09FDF337-6845-4807-9835-1630B55E626D","generation":0}'
2017-09-19 12:49:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:49:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:49:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:FDB7528A-6D5A-476F-989F-0B13DC545963:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FD,B7528A-6D5A-476F-989F-0B13DC545963:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "FDB7528A-6D5A-476F-989F-0B13DC545963", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,DB7528A-6D5A-476F-989F-0B13DC545963", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FDB7528A-6D5A-476F-989F-0B13DC545963", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:FDB7528A-6D5A-476F-989F-0B13DC545963:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:FDB7528A-6D5A-476F-989F-0B13DC545963:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:FDB7528A-6D5A-476F-989F-0B13DC545963:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "FDB7528A-6D5A-476F-989F-0B13DC545963", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:FDB7528A-6D5A-476F-989F-0B13DC545963:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FD,B7528A-6D5A-476F-989F-0B13DC545963:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "FDB7528A-6D5A-476F-989F-0B13DC545963", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,DB7528A-6D5A-476F-989F-0B13DC545963", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FDB7528A-6D5A-476F-989F-0B13DC545963", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-09-19 12:49:06 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Y4Jor2Yxt8mAH05NpFQ118iMB82mpBHH","error":"Peer is unavailable",,"portNumber":null}'
2017-09-19 12:49:06 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Y4Jor2Yxt8mAH05NpFQ118iMB82mpBHH', error: 'Peer is unavailable', listeningPort: '%s''
,2017-09-19 12:49:06 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-09-19 12:49:06 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for FA542401-F573-4621-9DBD-9F1F61CD325C (syncValue: Gc2kz9uqFKIxjLIIbobllg8,tKxHm3GyF)'
2017-09-19 12:49:06 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FA542401-F573-4621-9DBD-9F1F61CD325C", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FA542401-F573-4621-9DBD-9F1F61CD325C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FA542401-F573-4621-9DBD-9F1F6,1CD325C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-09-19 12:49:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:FDB7528A-6D5A-476F-989F-0B13DC545963:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:FA542401-F573-4621-9DBD-9F1F61CD325C:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FA542401-F573-4621-9DBD-9F1F61CD325C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:FA542401-F573-4621-9DBD-9F1F61CD325C:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "FA542401-F573-4621-9DBD-9F1F61CD325C", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62121
2017-09-19 12:49:09 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Gc2kz9uqFKIxjLIIbobllg8tKxHm3GyF",,"error":null,"portNumber":62121}'
2017-09-19 12:49:09 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Gc2kz9uqFKIxjLIIbobllg8tKxHm3GyF', error: 'null', listeningPort: '62121''
,Connecting to the localhost:62121
,Connecting to the localhost:62121
Connecting to the localhost:62121
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] Session.startOutputStream(with:) peer:FA542401-F573-4621-9DBD-9F1F61CD325C:0
,[ThaliCore] Session.startOutputStream(with:) peer:FA542401-F573-4621-9DBD-9F1F61CD325C:0
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FA542401-F573-4621-9DBD-9F1F61CD325C:0
Connected to the localhost:62121
Connected to the localhost:62121
,Connected to the localhost:62121
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FA542401-F573-4621-9DBD-9F1F61CD325C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [1, 2]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FA542401-F573-4621-9DBD-9F1F61CD325C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [1, 2, 3]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FA542401-F573-4621-9DBD-9F1F61CD325C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [1, 2, 3, 4]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 91 correct string length
,2017-09-19 12:49:09 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 92 correct string length
,2017-09-19 12:49:09 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 93 correct string length
,2017-09-19 12:49:09 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-09-19 12:49:09 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-09-19 12:49:09 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-09-19 12:49:09 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:3
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,ok 94 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:2
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:2
,[ThaliCore] VirtualSocket.deinit vsID:2 [1, 3, 4]
,ok 95 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:4
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:4
[ThaliCore] VirtualSocket.deinit vsID:4 [1, 3]
ok 96 got the same data back
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5B320F76-3B18-4F84-8A5E-45B0426BD3B7
[ThaliCore] Advertiser: session connected Peer(uuid: "4FF4D8AD-7583-4E46-A0AE-07975F33B677", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:5B320F76-3B18-4F84-8A5E-45B0426BD3B7 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5B320F76-3B18-4F84-8A5E-45B0426BD3B7
,[ThaliCore] Session.session(_:peer:didChange:) peer:5B320F76-3B18-4F84-8A5E-45B0426BD3B7 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5B320F76-3B18-4F84-8A5E-45B0426BD3B7
[ThaliCore] Session.startOutputStream(with:) peer:5B320F76-3B18-4F84-8A5E-45B0426BD3B7
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5, [1, 3, 5]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5B320F76-3B18-4F84-8A5E-45B0426BD3B7
[ThaliCore] Session.startOutputStream(with:) peer:5B320F76-3B18-4F84-8A5E-45B0426BD3B7
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6, [1, 3, 5, 6]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5B320F76-3B18-4F84-8A5E-45B0426BD3B7
[ThaliCore] Session.startOutputStream(with:) peer:5B320F76-3B18-4F84-8A5E-45B0426BD3B7
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [1, 3, 5, 6, 7]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-09-19 12:49:17 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-09-19 12:49:17 - DEBUG testThaliMobileNative: 'Server received (10808 bytes):'
,2017-09-19 12:49:17 - DEBUG testThaliMobileNative: 'Server received (4481 bytes):'
,2017-09-19 12:49:17 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-09-19 12:49:17 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-09-19 12:49:17 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-09-19 12:49:17 - DEBUG testThaliMobileNative: 'Server received (7452 bytes):'
,2017-09-19 12:49:17 - DEBUG testThaliMobileNative: 'Server received (4593 bytes):'
,2017-09-19 12:49:17 - DEBUG testThaliMobileNative: 'Server received (4339 bytes):'
,2017-09-19 12:49:17 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-09-19 12:49:17 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-09-19 12:49:17 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-09-19 12:49:17 - DEBUG testThaliMobileNative: 'Server received (2048 bytes):'
,2017-09-19 12:49:17 - DEBUG testThaliMobileNative: 'Server received (7807 bytes):'
,2017-09-19 12:49:17 - DEBUG testThaliMobileNative: 'Server received (5475 bytes):'
,2017-09-19 12:49:17 - DEBUG testThaliMobileNative: 'Server received (1054 bytes):'
,2017-09-19 12:49:17 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-09-19 12:49:17 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-09-19 12:49:17 - DEBUG testThaliMobileNative: 'Server data flushed',
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:6
[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:5
[ThaliCore] VirtualSocket.closeStreams() vsID:5
,[ThaliCore] VirtualSocket exited RunLoop vsID:6
[ThaliCore] VirtualSocket.deinit vsID:6 [1, 3, 5, 7]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:5
[ThaliCore] VirtualSocket.deinit vsID:5 [1, 3, 7]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client, disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:7
[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-09-19 12:49:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-09-19 12:49:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 12:49:17 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:49:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:4FF4D8AD-7583-4E46-A0AE-07975F33B677
2017-09-19 12:49:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12,:,49:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:FA542401-F573-4621-9DBD-9F1F61CD325C
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:62121
[ThaliCore] Session.disconnect() p,eer:FA542401-F573-4621-9DBD-9F1F61CD325C:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5B320F76-3B18-4F84-8A5E-45B0426BD3B7 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "4FF4D8AD-7583-4E46-A0AE-07975F33B677", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:5B320F76-3B18-4F84-8A5E-45B0426BD3B7
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:FA542401-F573-4621-9DBD-9F1F61CD325C:0
,2017-09-19 12:49:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:49:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:49:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:49:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-09-19 12:49:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:49:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:49:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:49:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5C58D711-31E1-42BB-A9B7-C41E6294A0FD", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:5C58D711-31E1-42BB-A9B7-C41E6294A0FD
,2017-09-19 12:49:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 12:49:17 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:49:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 97 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3D63136F-81D8-413D-91AA-28D9BAC9F281
[ThaliCore] Browser.startListe,ning
,2017-09-19 12:49:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-09-19 12:49:17 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:49:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Session.deinit peer:5B320F76-3B18-4F84-8A5E-45B0426BD3B7
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:09FDF337-6845-4807-9835-1630B55E626D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "09FDF337-6845-4807-9835-1630B55E626D", generation: 0)
2017-09-19 12:49:18 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"09FDF337-6845-4807-9835-1630B55E626D","generation":0}'
2017-09-19 12:49:18 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 09FDF337-6845-4807-9835-1630B55E626D, (syncValue: KGHErFyv8b4oGMpwv6zeuvX1c3Wh1Aw2)'
2017-09-19 12:49:18 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "09FDF337-6845-4807-9835-1630B55,E626D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "09FDF337-6845-4807-9835-1630B55E626D", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:09FDF337-6845-4807-9835-1630B55E626D:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FA542401-F573-4621-9DBD-9F1F61CD325C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FA542401-F573-4621-9DBD-9F1F61CD325C",, generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-09-19 12:49:18 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable,":true,"peerIdentifier":"FA542401-F573-4621-9DBD-9F1F61CD325C","generation":0}'
2017-09-19 12:49:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:49:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B224C079-0793-4C1D-8FF3-899E71D44BAD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B224C079-0793-4C1D-8FF3-899E71D44BAD", generation: 0)
,2017-09-19 12:49:19 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B224C079-0793-4C1D-8FF3-899E71D44BAD","generation":0}'
,2017-09-19 12:49:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:49:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:49:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:62C3A3CE-D25E-4073-8C66-B8F9673DB39F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "62C3A3CE-D25E-4073-8C66-B8F9673DB39F", generation: 0)
2017-09-19 12:49:19 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"62C3A3CE-D25E-4073-8C66-B8F9673DB39F","generation":0}'
2017-09-19 12:49:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:49:19 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,2017-09-19 12:49:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:49:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5C58D711-31E1-42BB-A9B7-C41E6294A0FD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5C58D711-31E1-42BB-A9B7-C41E6294A0FD", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:09FDF337-6845-4807-9835-1630B55E626D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:09,FDF337-6845-4807-9835-1630B55E626D:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "09FDF337-6845-4807-9835-1630B55E626D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,9FDF337-6845-4807-9835-1630B55E626D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "09FDF337-6845-4807-9835-1630B55E626D", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:09FDF337-6845-4807-9835-1630B55E626D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:09FDF337-6845-4807-9835-1630B55E626D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:09FDF337-6845-4807-9835-1630B55E626D:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "09FDF337-6845-4807-9835-1630B55E626D", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:09FDF337-6845-4807-9835-1630B55E626D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:09FDF337-6845-4807-9835-1630B55E626D:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "09FDF337-6845-4807-9835-1630B55E626D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,9FDF337-6845-4807-9835-1630B55E626D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "09FDF337-6845-4807-9835-1630B55E626D", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-09-19 12:49:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"KGHErFyv8b4oGMpwv6zeuvX1c3Wh1Aw2","error":"Peer is unavailable",,"portNumber":null}'
2017-09-19 12:49:24 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'KGHErFyv8b4oGMpwv6zeuvX1c3Wh1Aw2', error: 'Peer is unavailable', listeningPort: '%s''
,2017-09-19 12:49:24 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-09-19 12:49:24 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for FA542401-F573-4621-9DBD-9F1F61CD325C (syncValue: ebAYSkMaNvuX1jC7Vu5RWBh,vo863bn6c)'
2017-09-19 12:49:24 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FA542401-F573-4621-9DBD-9F1F61CD325C", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FA542401-F573-4621-9DBD-9F1F61CD325C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FA542401-F573-4621-9DBD-9F1F6,1CD325C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-09-19 12:49:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 ,1,2:49:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:09FDF337-6845-4807-9835-1630B55E626D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A6DCB927-B503-4348-B86E-9F8AB59D69D3
[ThaliCore] Advertiser: session connected Peer(uuid: "5C58D711-31E1-42BB-A9B7-C41E6294A0FD", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:A6DCB927-B503-4348-B86E-9F8AB59D69D3 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A6DCB927-B503-4348-B86E-9F8AB59D69D3
,[ThaliCore] Session.session(_:peer:didChange:) peer:FA542401-F573-4621-9DBD-9F1F61CD325C:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FA542401-F573-4621-9DBD-9F1F61CD325C:0
,[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "FA542401-F573-4621-9DBD-9F1F61CD325C", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FA542401-F573-4621-9DBD-9F1F61CD325C", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FA542401-F573-4621-9DBD-9F1F61CD325C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FA542401-F573-4621-9DBD-9F1F61CD325C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:FA542401-F573-4621-9DBD-9F1F61CD325C:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:A6DCB927-B503-4348-B86E-9F8AB59D69D3 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A6DCB927-B503-4348-B86E-9F8AB59D69D3
[ThaliCore] Session.startOutputStream(with:) peer:A6DCB927-B503-4348-B86E-9F8AB59D69D3
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [1, 3, 7, 8]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-09-19 12:49:28 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-09-19 12:49:28 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
2017-09-19 12:49:28 - DEBUG testThaliMobileNative: 'Server sends data bac,k to client (20 bytes): '
2017-09-19 12:49:28 - DEBUG testThaliMobileNative: 'Server data flushed'
2017-09-19 12:49:28 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:8
[ThaliCore] VirtualSocket.closeSt,reams() vsID:8
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:8
[ThaliCore] VirtualSocket.deinit vsID:8 [1, 3, 7]
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:FA542401-F573-4621-9DBD-9F1F61CD325C:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "FA542401-F573-4621-9DBD-9F1F61CD325C", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:FA542401-F573-4621-9DBD-9F1F61CD325C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FA,542401-F573-4621-9DBD-9F1F61CD325C:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "FA542401-F573-4621-9DBD-9F1F61CD325C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,A542401-F573-4621-9DBD-9F1F61CD325C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FA542401-F573-4621-9DBD-9F1F61CD325C", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-09-19 12:49:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ebAYSkMaNvuX1jC7Vu5RWBhvo863bn6c","error":"Peer is unavailable",,"portNumber":null}'
2017-09-19 12:49:29 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ebAYSkMaNvuX1jC7Vu5RWBhvo863bn6c', error: 'Peer is unavailable', listeningPort: '%s''
,2017-09-19 12:49:29 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-09-19 12:49:29 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B224C079-0793-4C1D-8FF3-899E71D44BAD (syncValue: SMLEMmrvj3ZpBlfPXGcrAkM,YWixH6F5l)'
2017-09-19 12:49:29 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B224C079-0793-4C1D-8FF3-899E71D44BAD", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B224C079-0793-4C1D-8FF3-899E71D44BAD", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B224C079-0793-4C1D-8FF3-899E7,1D44BAD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-09-19 12:49:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:FA542401-F573-4621-9DBD-9F1F61CD325C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3A30A677-ED56-47B7-87BD-C04109DE0039
[ThaliCore] Advertiser: session connected Peer(uuid: "5C58D711-31E1-42BB-A9B7-C41E6294A0FD", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:3A30A677-ED56-47B7-87BD-C04109DE0039 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:B224C079-0793-4C1D-8FF3-899E71D44BAD:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3A30A677-ED56-47B7-87BD-C04109DE0039
,[ThaliCore] Session.session(_:peer:didChange:) peer:3A30A677-ED56-47B7-87BD-C04109DE0039 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B224C079-0793-4C1D-8FF3-899E71D44BAD:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B224C079-0793-4C1D-8FF3-899E71D44BAD:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "B224C079-0793-4C1D-8FF3-899E71D44BAD", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62144
2017-09-19 12:49:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"SMLEMmrvj3ZpBlfPXGcrAkMYWixH6F5l",,"error":null,"portNumber":62144}'
2017-09-19 12:49:32 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'SMLEMmrvj3ZpBlfPXGcrAkMYWixH6F5l', error: 'null', listeningPort: '62144''
,Connecting to the localhost:62144
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B224C079-0793-4C1D-8FF3-899E71D44BAD:0
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3A30A677-ED56-47B7-87BD-C04109DE0039
[ThaliCore] Session.startOutputStream(with:) peer:3A30A677-ED56-47B7-87BD-C04109DE0039
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [1, 3, 7, 9]
[ThaliCo,re] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B224C079-0793-4C1D-8FF3-899E71D44BAD:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [1, 3, 7, 9, 1,0]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Server received psk id: psk-id
,Connected to the localhost:62144
,2017-09-19 12:49:32 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-09-19 12:49:32 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-09-19 12:49:32 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-09-19 12:49:32 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-09-19 12:49:32 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-09-19 12:49:32 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-09-19 12:49:32 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:9
[ThaliCore] VirtualSocket.closeStreams() vsID:9
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:9
,[ThaliCore] VirtualSocket.deinit vsID:9 [1, 3, 7, 10]
,ok 99 got the same data back
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:10
[ThaliCore] VirtualSocket.closeStreams() vsID:10
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Cod,e=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserR,elay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:10
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:conn,ected
[ThaliCore] VirtualSocket exited RunLoop vsID:10
[ThaliCore] VirtualSocket.deinit vsID:10 [1, 3, 7]
,# teardown
,2017-09-19 12:49:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-09-19 12:49:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 12:49:33 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:49:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:5C58D711-31E1-42BB-A9B7-C41E6294A0FD
2017-09-19 12:49:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:49:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:B224C079-0793-4C1D-8FF3-899E71D44BAD,
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:62144
[ThaliCore] Session.disconnect() peer:B224C079-0793-4C1D-8FF3-899E71D44BAD:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:3A30A677-ED56-47B7-87BD-C04109DE0039 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "5C58D711-31E1-42BB-A9B7-C41E6294A0FD", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:3A30A677-ED56-47B7-87BD-C04109DE0039
[ThaliCore] Advert,iserRelay.deinit
[ThaliCore] Session.deinit peer:B224C079-0793-4C1D-8FF3-899E71D44BAD:0
[ThaliCore] BrowserRelay.deinit
,2017-09-19 12:49:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:49:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:49:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:49:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:49:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:49:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:49:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:49:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:A6DCB927-B503-4348-B86E-9F8AB59D69D3 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "5C58D711-31E1-42BB-A9B7-C41E6294A0FD", generation: 0)
,[ThaliCore] Session.deinit peer:3A30A677-ED56-47B7-87BD-C04109DE0039
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5B0178B6-A741-4E00-AC62-1F9897244011", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:5B0178B6-A741-4E00-AC62-1F9897244011
,2017-09-19 12:49:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 12:49:34 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:49:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 100 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FAF8EBD4-6611-4629-918B-9346A00412D1
,[ThaliCore] Browser.startListening
2017-09-19 12:49:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-09-19 12:49:34 - INFO thaliMobile: 'Received state ({"discoveryActive,":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:49:34 - INFO thaliMobile: 'F,iltered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:62C3A3CE-D25E-4073-8C66-B8F9673DB39F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "62C3A3CE-D25E-4073-8C66-B8F9673DB39F", generation: 0)
2017-09-19 12:49:34 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"62C3A3CE-D25E-4073-8C66-B8F9673DB39F","generation":0}'
2017-09-19 12:49:34 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 62C3A3CE-D25E-4073-8C66-B8F9673DB39F, (syncValue: kX3sEKkeDami69ln9a0DMSxziUVkdj2D)'
2017-09-19 12:49:34 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "62C3A3CE-D25E-4073-8C66-B8F9673,DB39F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "62C3A3CE-D25E-4073-8C66-B8F9673DB39F", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:,) peer:62C3A3CE-D25E-4073-8C66-B8F9673DB39F:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B224C079-0793-4C1D-8FF3-899E71D44BAD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B224C079-0793-4C1D-8FF3-899E71D44BAD",, generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-09-19 12:49:34 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B224C079-0793-4C1D-8FF3-899E71D44BAD","generation":0}'
2017-09-19 12:49:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:49:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5B0178B6-A741-4E00-AC62-1F9897244011:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5B0178B6-A741-4E00-AC62-1F9897244011", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:49A00F14-0EB2-468A-A004-75D2B5F0AF5F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "49A00F14-0EB2-468A-A004-75D2B5F0AF5F", generation: 0)
2017-09-19 12:49:35 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"49A00F14-0EB2-468A-A004-75D2B5F0AF5F","generation":0}'
2017-09-19 12:49:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:49:35 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-09-19 12:49:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:865FCB1B-7BD8-4406-B2FB-599546BA3E60:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "865FCB1B-7BD8-4406-B2FB-599546BA3E60", generation: 0)
2017-09-19 12:49:36 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"865FCB1B-7BD8-4406-B2FB-599546BA3E60","generation":0}'
2017-09-19 12:49:36 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:49:36 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-09-19 12:49:36 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:49:36 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:62C3A3CE-D25E-4073-8C66-B8F9673DB39F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:62,C3A3CE-D25E-4073-8C66-B8F9673DB39F:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "62C3A3CE-D25E-4073-8C66-B8F9673DB39F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,2C3A3CE-D25E-4073-8C66-B8F9673DB39F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "62C3A3CE-D25E-4073-8C66-B8F9673DB39F", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:62C3A3CE-D25E-4073-8C66-B8F9673DB39F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:62C3A3CE-D25E-4073-8C66-B8F9673DB39F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:62C3A3CE-D25E-4073-8C66-B8F9673DB39F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:62,C3A3CE-D25E-4073-8C66-B8F9673DB39F:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "62C3A3CE-D25E-4073-8C66-B8F9673DB39F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,2C3A3CE-D25E-4073-8C66-B8F9673DB39F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "62C3A3CE-D25E-4073-8C66-B8F9673DB39F", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:62C3A3CE-D25E-4073-8C66-B8F9673DB39F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:62C3A3CE-D25E-4073-8C66-B8F9673DB39F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:62C3A3CE-D25E-4073-8C66-B8F9673DB39F:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "62C3A3CE-D25E-4073-8C66-B8F9673DB39F", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:62C3A3CE-D25E-4073-8C66-B8F9673DB39F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:62,C3A3CE-D25E-4073-8C66-B8F9673DB39F:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "62C3A3CE-D25E-4073-8C66-B8F9673DB39F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,2C3A3CE-D25E-4073-8C66-B8F9673DB39F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "62C3A3CE-D25E-4073-8C66-B8F9673DB39F", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-09-19 12:49:43 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"kX3sEKkeDami69ln9a0DMSxziUVkdj2D","error":"Peer is unavailable",,"portNumber":null}'
2017-09-19 12:49:43 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'kX3sEKkeDami69ln9a0DMSxziUVkdj2D', error: 'Peer is unavailable', listeningPort: '%s''
,2017-09-19 12:49:43 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-09-19 12:49:43 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B224C079-0793-4C1D-8FF3-899E71D44BAD (syncValue: ITtRCyIjtUvuqedjym2vdQn,EQB10tsEc)'
2017-09-19 12:49:43 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B224C079-0793-4C1D-8FF3-899E71D44BAD", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B224C079-0793-4C1D-8FF3-899E71D44BAD", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B224C079-0793-4C1D-8FF3-899E7,1D44BAD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-09-19 12:49:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 ,1,2:49:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:62C3A3CE-D25E-4073-8C66-B8F9673DB39F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B224C079-0793-4C1D-8FF3-899E71D44BAD:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B2,24C079-0793-4C1D-8FF3-899E71D44BAD:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "B224C079-0793-4C1D-8FF3-899E71D44BAD", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,224C079-0793-4C1D-8FF3-899E71D44BAD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B224C079-0793-4C1D-8FF3-899E71D44BAD", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B224C079-0793-4C1D-8FF3-899E71D44BAD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B224C079-0793-4C1D-8FF3-899E71D44BAD:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B224C079-0793-4C1D-8FF3-899E71D44BAD:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B224C079-0793-4C1D-8FF3-899E71D44BAD:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "B224C079-0793-4C1D-8FF3-899E71D44BAD", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,224C079-0793-4C1D-8FF3-899E71D44BAD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B224C079-0793-4C1D-8FF3-899E71D44BAD", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B224C079-0793-4C1D-8FF3-899E71D44BAD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B224C079-0793-4C1D-8FF3-899E71D44BAD:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B224C079-0793-4C1D-8FF3-899E71D44BAD", generation: 0)
,[ThaliCore] Session.deinit peer:B224C079-0793-4C1D-8FF3-899E71D44BAD:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5948F9C4-AC6D-444D-952C-D956A54DAE22
[ThaliCore] Advertiser: session connected Peer(uuid: "5B0178B6-A741-4E00-AC62-1F9897244011", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:5948F9C4-AC6D-444D-952C-D956A54DAE22 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:B224C079-0793-4C1D-8FF3-899E71D44BAD:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B2,24C079-0793-4C1D-8FF3-899E71D44BAD:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "B224C079-0793-4C1D-8FF3-899E71D44BAD", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,224C079-0793-4C1D-8FF3-899E71D44BAD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B224C079-0793-4C1D-8FF3-899E71D44BAD", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-09-19 12:49:51 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ITtRCyIjtUvuqedjym2vdQnEQB10tsEc","error":"Peer is unavailable",,"portNumber":null}'
2017-09-19 12:49:51 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ITtRCyIjtUvuqedjym2vdQnEQB10tsEc', error: 'Peer is unavailable', listeningPort: '%s''
,2017-09-19 12:49:51 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-09-19 12:49:51 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 49A00F14-0EB2-468A-A004-75D2B5F0AF5F (syncValue: RdZOX1QctlGKSNVPIPwKO6K,rEb1RTbqE)'
2017-09-19 12:49:51 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "49A00F14-0EB2-468A-A004-75D2B5F0AF5F", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "49A00F14-0EB2-468A-A004-75D2B5F0AF5F", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:49A00F14-0EB2-468A-A004-75D2B,5F0AF5F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-09-19 12:49:51 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:B224C079-0793-4C1D-8FF3-899E71D44BAD:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5948F9C4-AC6D-444D-952C-D956A54DAE22
,[ThaliCore] Session.session(_:peer:didChange:) peer:49A00F14-0EB2-468A-A004-75D2B5F0AF5F:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:5948F9C4-AC6D-444D-952C-D956A54DAE22 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5948F9C4-AC6D-444D-952C-D956A54DAE22
[ThaliCore] Session.startOutputStream(with:) peer:5948F9C4-AC6D-444D-952C-D956A54DAE22
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [1, 3, 7, 11]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-09-19 12:49:52 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-09-19 12:49:52 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-09-19 12:49:52 - DEBUG testThaliMobileNative: 'Server received (6570 bytes):'
2017-09-19 12:49:52 - DEBUG testThaliMobileNative: 'Server received (6570 bytes):'
,2017-09-19 12:49:52 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-09-19 12:49:52 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-09-19 12:49:52 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-09-19 12:49:52 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-09-19 12:49:52 - DEBUG testThaliMobileNative: 'Server received (5475 bytes):'
,2017-09-19 12:49:52 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-09-19 12:49:52 - DEBUG testThaliMobileNative: 'Server received (3214 bytes):'
,2017-09-19 12:49:52 - DEBUG testThaliMobileNative: 'Server received (3356 bytes):'
,2017-09-19 12:49:52 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-09-19 12:49:52 - DEBUG testThaliMobileNative: 'Server received (5404 bytes):'
,2017-09-19 12:49:52 - DEBUG testThaliMobileNative: 'Server received (4309 bytes):'
,2017-09-19 12:49:52 - DEBUG testThaliMobileNative: 'Server received (1073 bytes):'
,2017-09-19 12:49:52 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-09-19 12:49:52 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-09-19 12:49:52 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:11
[ThaliCore] VirtualSocket.closeStreams() vsID:11
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:11
[ThaliCore] VirtualSocket.deinit vsID:11 [1, 3, 7]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:49A00F14-0EB2-468A-A004-75D2B5F0AF5F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:49A00F14-0EB2-468A-A004-75D2B5F0AF5F:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "49A00F14-0EB2-468A-A004-75D2B5F0AF5F", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62167
2017-09-19 12:49:54 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"RdZOX1QctlGKSNVPIPwKO6KrEb1RTbqE",,"error":null,"portNumber":62167}'
2017-09-19 12:49:54 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'RdZOX1QctlGKSNVPIPwKO6KrEb1RTbqE', error: 'null', listeningPort: '62167''
,Connecting to the localhost:62167
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:49A00F14-0EB2-468A-A004-75D2B5F0AF5F:0
Connected to the localh,ost:62167
2017-09-19 12:49:54 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
2017-09-19 12:49:54 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:49A00F14-0EB2-468A-A004-75D2B5F0AF5F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [1, 3, 7, 12]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 102 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pe,er})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStream,s() vsID:12
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2080B085-BBB4-44BC-862D-B7C7130B2A8B
[ThaliCore] Advertiser: session connected Peer(uuid: "5B0178B6-A741-4E00-AC62-1F9897244011", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:2080B085-BBB4-44BC-862D-B7C7130B2A8B state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2080B085-BBB4-44BC-862D-B7C7130B2A8B
,[ThaliCore] Session.session(_:peer:didChange:) peer:2080B085-BBB4-44BC-862D-B7C7130B2A8B state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2080B085-BBB4-44BC-862D-B7C7130B2A8B
[ThaliCore] Session.startOutputStream(with:) peer:2080B085-BBB4-44BC-862D-B7C7130B2A8B
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,3 [1, 3, 7, 12, 13]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-09-19 12:50:00 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
2017-09-19 12:50:00 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
2017-09-19 12:50:00 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
2017-09-19 12:50:00 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
2017-09-19 12:50:00 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-09-19 12:50:00 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-09-19 12:50:00 - DEBUG testThaliMobileNative: 'Server received (6570 bytes):'
,2017-09-19 12:50:00 - DEBUG testThaliMobileNative: 'Server received (17520 bytes):'
,2017-09-19 12:50:00 - DEBUG testThaliMobileNative: 'Server received (18615 bytes):'
,2017-09-19 12:50:00 - DEBUG testThaliMobileNative: 'Server received (5311 bytes):'
,2017-09-19 12:50:00 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-09-19 12:50:00 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-09-19 12:50:00 - DEBUG testThaliMobileNative: 'Server data flushed',
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:13
[ThaliCore] VirtualSocket.closeStreams() vsID:13
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:13
[ThaliCore] VirtualSocket.deinit vsID:13 [1, 3, 7, 12]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) ,client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-09-19 12:50:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,[ThaliCore] VirtualSocket exited RunLoop vsID:12
[ThaliCore] VirtualSocket.deinit vsID:12 [1, 3, 7]
2017-09-19 12:50:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-09-19 12:50:00 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-09-19 12:50:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:5B0178B6-A741-4E00-AC62-1F9897244011
,2017-09-19 12:50:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:49A00F14-0EB2-468A-A004-75D2B5F0AF5F
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:62167
[ThaliCore] Session.disconnect() p,eer:49A00F14-0EB2-468A-A004-75D2B5F0AF5F:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:2080B085-BBB4-44BC-862D-B7C7130B2A8B state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "5B0178B6-A741-4E00-AC62-1F9897244011", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:2080B085-BBB4-44BC-862D-B7C7130B2A8B
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] Session.deinit peer:49A00F14-0EB2-468A-A004-75D2B5F0AF5F:0
,[ThaliCore] BrowserRelay.deinit
,2017-09-19 12:50:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:50:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:50:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-09-19 12:50:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:50:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:50:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:50:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:5948F9C4-AC6D-444D-952C-D956A54DAE22 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "5B0178B6-A741-4E00-AC62-1F9897244011", generation: 0)
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] Session.deinit peer:2080B085-BBB4-44BC-862D-B7C7130B2A8B
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D9F5A780-2D60-43DA-AF7A-723F621E4876", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:D9F5A780-2D60-43DA-AF7A-723F621E4876
2017-09-19 1,2:50:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 12:50:02 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:50:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 103 Ready to advertise
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:51002F13-A55B-493B-B810-DA32EBE21AC6
[ThaliCore] Browser.startListening
2017-09,-,19 12:50:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-09-19 12:50:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not ma,tch with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:50:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate ,(was in stopped state).'
ok 104 Ready to listen
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5ECB47BE-74E6-45B9-ABDF-F0FFE6321A0B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5ECB47BE-74E6-45B9-ABDF-F0FFE6321A0B", generation: 0)
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:D9F5A780-2D60-43DA-AF7A-723F621E4876
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:06803A25-E8DE-4A6B-8E67-EF7F618CC7F4:0
[ThaliCore,] BrowserManager.foundPeerHandler peer:Peer(uuid: "06803A25-E8DE-4A6B-8E67-EF7F618CC7F4", generation: 0)
2017-09-19 12:50:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
201,7-09-19 12:50:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret",:null,"networkType":null}})'
2017-09-19 12:50:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 105 stop ads worked
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-09-19 12:50:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:50:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 106 test stop worked
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:50:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:06 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:50:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-09-19 12:50:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:50:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:50:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:50:06 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-09-19 12:50:06 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-09-19 12:50:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-09-19 12:50:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-09-19 12:50:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Test updating advertising and parallel data transfer
,2017-09-19 12:50:07 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:50:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:07 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:50:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-09-19 12:50:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:50:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:50:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:50:07 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-09-19 12:50:07 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-09-19 12:50:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-09-19 12:50:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-09-19 12:50:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:72F848D8-F757-440A-8912-E1CD7C0BB81F
[ThaliCore] Browser.startListening
ok 107 discoveryActive should be false
ok 108 advertisingA,ctive should be true
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "00F40755-5F14-42C5-9087-9171EA5CD0CA", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:00F40755-5F14-42C5-9087-9171,EA5CD0CA
ok 109 discoveryActive should be false
ok 110 advertisingActive should be true
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
ok 111 discoveryActive should be false
ok 112 advertisingActive sh,ould be true
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:00F40755-5F14-42C5-9087-9171EA5CD0CA
ok 113 discoveryActive should be false
ok 114 advertisingActive should be true
ok 115 Can call startList,e,ningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:50:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:50:08 - DEBUG thaliMobi,leNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:50:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-09-19 12:50:08 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-09-19 12:50:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-09-19 12:50:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-09-19 12:50:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-09-19 12:50:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:50:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:08 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 116 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:50:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 117 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-09-19 12:50:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:50:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:10 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 118 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:50:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 119 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-09-19 12:50:10 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:50:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:50:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:50:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-09-19 12:50:10 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:50:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:10 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 122 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:50:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:50:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 123 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-09-19 12:50:10 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:11 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 124 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 125 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-09-19 12:50:11 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:50:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 126 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:50:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 127 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 128 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:04db9efc-b172-48be-b7f3-6c5bc5268ae0 error: startListeningNotActive
2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"b74dMrMFUNakEw0dfTzUaKacoCSA8S8g","error":"startListeningForAdvertisements is not active","portNumber":null}'
ok 129 Should only get called after multiConnect returned
ok 130 SyncValue matches
ok 131 Got right error
ok 132 listeningPort ,is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:11 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-09-19 12:50:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:50:11 - DEBUG t,haliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:50:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4FFAC9C7-57CB-411F-8085-A8208A83BC09
[ThaliCore] Browser.startListening
,2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-09-19 12:50:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:50:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 133 No error on starting
,ok 134 Got null as expected
,2017-09-19 12:50:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"z69pOQHgM0NNxqOrVKW26JbAACMrUQJS","error":"Illegal peerID","portNumber":null}'
ok 135 Should only get called after multiConnect returned
,ok 136 SyncValue matches
,ok 137 Got right error
,ok 138 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19, 12:50:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-09-19 12:50:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:50:12 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-09-19 12:50:12 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# multiConnect properly fails on legal but non-existent peerID
,2017-09-19 12:50:12 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:12 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-09-19 12:50:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:50:12 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-09-19 12:50:12 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A0109698-1893-4AE6-96B2-021052033112
[ThaliCore] Browser.startListening
2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-09-19 12:50:12 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:50:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 139 No error on star,ting
ok 140 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19, 12:50:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-09-19 12:50:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:50:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:50:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call disconnect with invalid peer id
,ok 141 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:13 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:50:13 ,- DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-09-19 12:50:13 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:6716865b-face-4683-91db-16fc4e8ae455
ok 142 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-09-19 12:50:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:50:13 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-09-19 12:50:13 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:50:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5
2017-09-19 1,2:50:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 12:50:14 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:50:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 143 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:0ACFC213-8950-4D40-94AC-F4B1F01D6330
[Tha,l,iCore] Browser.startListening
2017-09-19 12:50:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-09-19 12:50:14 - INFO thaliMobile: 'Received state ({"discoveryActive":tru,e,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:50:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 144 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:49A00F14-0EB2-468A-A004-75D2B5F0AF5F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "49A00F14-0EB2-468A-A004-75D2B5F0AF5F", generation: 0)
,2017-09-19 12:50:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"49A00F14-0EB2-468A-A004-75D2B5F0AF5F","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5ECB47BE-74E6-45B9,-ABDF-F0FFE6321A0B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5ECB47BE-74E6-45B9-ABDF-F0FFE6321A0B", generation: 0)
2017-09-19 12:50:14 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 49A00F14-0EB2-468A-A004-75D2B5F0AF5F, (syncValue: lhmrPIzHnLP5bErWRrTXCDVGfN7DewQM)'
2017-09-19 12:50:14 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "49A00F14-0EB2-468A-A004-75D2B5F0AF5F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "49A00F14-0EB2-468A-A004-75D2B5F0AF5F", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:49A00F14-0EB2-468A-A004-75D2B5F0AF5F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-09-19 12:50:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5ECB47BE-74E6-45B9-ABDF-F0FFE6321A0B","generation":0}'
2017-09-19 12:50:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-,19 12:50:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CE085BEC-A868-440D-8066-CAEC5CC0BC19:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CE085BEC-A868-440D-8066-CAEC5CC0BC19", generation: 0)
,2017-09-19 12:50:15 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CE085BEC-A868-440D-8066-CAEC5CC0BC19","generation":0}'
,2017-09-19 12:50:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:50:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:50:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E205BA54-258E-4F38-8E64-D5B41A94C652:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E205BA54-258E-4F38-8E64-D5B41A94C652", generation: 0)
2017-09-19 12:50:16 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E205BA54-258E-4F38-8E64-D5B41A94C652","generation":0}'
2017-09-19 12:50:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:50:16 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-09-19 12:50:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:50:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:49A00F14-0EB2-468A-A004-75D2B5F0AF5F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:49,A00F14-0EB2-468A-A004-75D2B5F0AF5F:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "49A00F14-0EB2-468A-A004-75D2B5F0AF5F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,9A00F14-0EB2-468A-A004-75D2B5F0AF5F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "49A00F14-0EB2-468A-A004-75D2B5F0AF5F", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:49A00F14-0EB2-468A-A004-75D2B5F0AF5F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:49A00F14-0EB2-468A-A004-75D2B5F0AF5F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:49A00F14-0EB2-468A-A004-75D2B5F0AF5F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:49,A00F14-0EB2-468A-A004-75D2B5F0AF5F:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "49A00F14-0EB2-468A-A004-75D2B5F0AF5F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,9A00F14-0EB2-468A-A004-75D2B5F0AF5F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "49A00F14-0EB2-468A-A004-75D2B5F0AF5F", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:49A00F14-0EB2-468A-A004-75D2B5F0AF5F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:49A00F14-0EB2-468A-A004-75D2B5F0AF5F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:77E48F85-45CD-4AEB-91C5-FB154B207EFB
[ThaliCore] Advertiser: session connected Peer(uuid: "ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:77E48F85-45CD-4AEB-91C5-FB154B207EFB state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:49A00F14-0EB2-468A-A004-75D2B5F0AF5F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:49,A00F14-0EB2-468A-A004-75D2B5F0AF5F:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "49A00F14-0EB2-468A-A004-75D2B5F0AF5F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,9A00F14-0EB2-468A-A004-75D2B5F0AF5F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "49A00F14-0EB2-468A-A004-75D2B5F0AF5F", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:49A00F14-0EB2-468A-A004-75D2B5F0AF5F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:49A00F14-0EB2-468A-A004-75D2B5F0AF5F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:77E48F85-45CD-4AEB-91C5-FB154B207EFB
,[ThaliCore] Session.session(_:peer:didChange:) peer:77E48F85-45CD-4AEB-91C5-FB154B207EFB state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:77E48F85-45CD-4AEB-91C5-FB154B207EFB
[ThaliCore] Session.startOutputStream(with:) peer:77E48F85-45CD-4AEB-91C5-FB154B207EFB
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,4 [1, 3, 7, 14]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:49A00F14-0EB2-468A-A004-75D2B5F0AF5F:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "49A00F14-0EB2-468A-A004-75D2B5F0AF5F", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:49A00F14-0EB2-468A-A004-75D2B5F0AF5F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:49,A00F14-0EB2-468A-A004-75D2B5F0AF5F:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "49A00F14-0EB2-468A-A004-75D2B5F0AF5F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:49A00F14,-0EB2-468A-A004-75D2B5F0AF5F error: max retries exceeded
2017-09-19 12:50:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"lhmrPIzHnLP5bErWRrTXCDVGfN7DewQM","error":"Connection could not be established","portNumber":null}'
2017-0,9-19 12:50:24 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'lhmrPIzHnLP5bErWRrTXCDVGfN7DewQM', error: 'Connection could not be established', listeningPort: '%s''
,2017-09-19 12:50:24 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-09-19 12:50:24 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5ECB47BE-74E6-45B9-ABDF-F0FFE6321A0B (syncValue: figrzaj,aHmOhoZQqXtE5uELuXiphNYhe)'
2017-09-19 12:50:24 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5ECB47BE-74E6-45B9-ABDF-F0FFE6321A0B", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5ECB47BE-74E6-45B9-ABDF-F0FFE6321A0B", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5ECB47BE-74E6,-45B9-ABDF-F0FFE6321A0B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-09-19 12:50:24 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-09-19 12:50:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:50:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:49A00F14-0EB2-468A-A004-75D2B5F0AF5F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5ECB47BE-74E6-45B9-ABDF-F0FFE6321A0B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5E,CB47BE-74E6-45B9-ABDF-F0FFE6321A0B:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "5ECB47BE-74E6-45B9-ABDF-F0FFE6321A0B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,ECB47BE-74E6-45B9-ABDF-F0FFE6321A0B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5ECB47BE-74E6-45B9-ABDF-F0FFE6321A0B", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5ECB47BE-74E6-45B9-ABDF-F0FFE6321A0B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5ECB47BE-74E6-45B9-ABDF-F0FFE6321A0B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5ECB47BE-74E6-45B9-ABDF-F0FFE6321A0B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5E,CB47BE-74E6-45B9-ABDF-F0FFE6321A0B:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "5ECB47BE-74E6-45B9-ABDF-F0FFE6321A0B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,ECB47BE-74E6-45B9-ABDF-F0FFE6321A0B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5ECB47BE-74E6-45B9-ABDF-F0FFE6321A0B", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5ECB47BE-74E6-45B9-ABDF-F0FFE6321A0B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5ECB47BE-74E6-45B9-ABDF-F0FFE6321A0B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5ECB47BE-74E6-45B9-ABDF-F0FFE6321A0B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5E,CB47BE-74E6-45B9-ABDF-F0FFE6321A0B:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "5ECB47BE-74E6-45B9-ABDF-F0FFE6321A0B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,ECB47BE-74E6-45B9-ABDF-F0FFE6321A0B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5ECB47BE-74E6-45B9-ABDF-F0FFE6321A0B", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5ECB47BE-74E6-45B9-ABDF-F0FFE6321A0B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5ECB47BE-74E6-45B9-ABDF-F0FFE6321A0B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:5ECB47BE-74E6-45B9-ABDF-F0FFE6321A0B:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "5ECB47BE-74E6-45B9-ABDF-F0FFE6321A0B", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:5ECB47BE-74E6-45B9-ABDF-F0FFE6321A0B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5E,CB47BE-74E6-45B9-ABDF-F0FFE6321A0B:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "5ECB47BE-74E6-45B9-ABDF-F0FFE6321A0B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:5ECB47BE,-74E6-45B9-ABDF-F0FFE6321A0B error: max retries exceeded
2017-09-19 12:50:35 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"figrzajaHmOhoZQqXtE5uELuXiphNYhe","error":"Connection could not be established","portNumber":null}'
2017-0,9-19 12:50:35 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'figrzajaHmOhoZQqXtE5uELuXiphNYhe', error: 'Connection could not be established', listeningPort: '%s''
,2017-09-19 12:50:35 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-09-19 12:50:35 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CE085BEC-A868-440D-8066-CAEC5CC0BC19 (syncValue: 9H5v4oH,w2FTIKtMLcla9eAnjGifwvJer)'
2017-09-19 12:50:35 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CE085BEC-A868-440D-8066-CAEC5CC0BC19", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CE085BEC-A868-440D-8066-CAEC5CC0BC19", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CE085BEC-A868,-440D-8066-CAEC5CC0BC19:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-09-19 12:50:35 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-09-19 12:50:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:50:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:5ECB47BE-74E6-45B9-ABDF-F0FFE6321A0B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:CE085BEC-A868-440D-8066-CAEC5CC0BC19:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CE085BEC-A868-440D-8066-CAEC5CC0BC19:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:CE085BEC-A868-440D-8066-CAEC5CC0BC19:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "CE085BEC-A868-440D-8066-CAEC5CC0BC19", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62193
,2017-09-19 12:50:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9H5v4oHw2FTIKtMLcla9eAnjGifwvJer","error":null,"portNumber":62193}'
,2017-09-19 12:50:38 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '9H5v4oHw2FTIKtMLcla9eAnjGifwvJer', error: 'null', listeningPort: '62193''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:CE085BEC-A868-440D-8066-CAEC5CC0BC19:0
,ok 145 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CE085BEC-A868-440D-8066-CAEC5CC0BC19", generation: 0) found active relay
,2017-09-19 12:50:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"odPNO9UnsASPVboit9SrvQHq0JrZB3Js","error":null,"portNumber":62193}'
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CE085BEC-A868-440D-8066-CAEC5C,C0BC19:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [1, 3, 7, 14, 15]
ok 146 No error
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 147 Ports equal
,ok 148 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CE085BEC-A868-440D-8066-CAEC5CC0BC19", generation: 0) found active relay
,2017-09-19 12:50:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"GBhLythPxIQfZz9ugnHFb7dLRkiL5auJ","error":null,"portNumber":62193}'
,ok 149 No error
,ok 150 Ports equal
,# teardown
,2017-09-19 12:50:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-09-19 12:50:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-09-19 12:50:38 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-09-19 12:50:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5
,2017-09-19 12:50:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:CE085BEC-A868-440D-8066-CAEC5CC0BC19
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:14
[ThaliCore] VirtualSocket.closeStreams() vsID:14
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:15
[ThaliCore] VirtualSocket.closeStreams() vsID:15
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:15
[ThaliCore] VirtualSocket.deinit vsID:15 [1, 3, 7,, 14]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:14
[ThaliCore] VirtualSocket.deinit vsID:14 [1, 3, 7]
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:62193
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:CE085BEC-A868-440D-8066-CAEC5CC0BC19:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:CE085BEC-A868-440D-8066-CAEC5CC0BC19:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "CE085BEC-A868-440D-8066-CAEC5CC0BC19", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:77E48F85-45CD-4AEB-91C5-FB154B207EFB state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "ABA4A2E6-AFBB-41B6-96A9-4F4065A734F5", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:77E48F85-45CD-4AEB-91C5-FB154B207EFB
,2017-09-19 12:50:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:50:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:50:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:50:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:50:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:50:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:50:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-09-19 12:50:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9H5v4oHw2FTIKtMLcla9eAnjGifwvJer","error":"Session disconnected","portNumber":null}'
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:CE085BEC-A868-440D-8066-CAEC5CC0BC19:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.deinit peer:77E48F85-45CD-4AEB-91C5-FB154B207EFB
,# initial peer discovery
,2017-09-19 12:50:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-09-19 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-09-19 12:50:40 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-09-19 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-09-19 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-09-19 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-09-19 12:50:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-09-19 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:50:40 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-09-19 12:50:40 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-09-19 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-09-19 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-09-19 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-09-19 12:50:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:50:41 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-09-19 12:50:41 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-09-19 12:50:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-09-19 12:50:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-09-19 12:50:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:50:41 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:50:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-09-19 12:50:42 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-09-19 12:50:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:50:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:50:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:50:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:50:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:50:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:50:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-09-19 12:50:42 - DEBUG createNativeListener: 'Creating Native Server'
,2017-09-19 12:50:42 - DEBUG createNativeListener: 'listening 62196'
,ok 151 Should throw
,# teardown
,2017-09-19 12:50:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-09-19 12:50:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-09-19 12:50:42 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-09-19 12:50:42 - DEBUG createNativeListener: 'Creating Native Server'
,2017-09-19 12:50:42 - DEBUG createNativeListener: 'listening 62198'
,2017-09-19 12:50:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-09-19 12:50:42 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 152 initial connection state should be CONNECTED
,2017-09-19 12:50:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 153 final connection state should be DISCONNECTED
,# teardown
,2017-09-19 12:50:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-09-19 12:50:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-09-19 12:50:42 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-09-19 12:50:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'Creating Native Server'
2017-09-19 12:50:43 - DEBUG createNativeListener: 'listening 62201'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-09-19 12:50:43 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
ok 154 tried to connect to right port
,ok 155 failed due to refused connection
,ok 156 routerPortConnectionFailed is emitted
,# teardown
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-09-19 12:50:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'Native Server - close'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'Creating Native Server'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'listening 62205'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 157 Send/recvd #1 should be equal length
,ok 158 Send/recvd #1 should be same
,ok 159 Send/recvd #2 should be equal length
,ok 160 Send/recvd #2 should be same
,ok 161 Should be exactly 2 client sockets
,# teardown
,2017-09-19 12:50:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-09-19 12:50:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-09-19 12:50:43 - DEBUG createNativeListener: 'Native Server - close'
2017-09-19 12:50:43, - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
2017-09-19 12:50:43 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close',
2017-09-19 12:50:43 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
2017-09-19 12:50:43 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
2017-09-19 12:50:43 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection, to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'Creating Native Server'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'listening 62210'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-09-19 12:50:43 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 162 socket shouldn't close until after stream
,ok 163 incoming remains open
,# teardown
,2017-09-19 12:50:43 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-09-19 12:50:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-09-19 12:50:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'Native Server - close'
2017-09-19 12:50:44 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-09-19 12:50:44 - DEBUG createNativeListener: 'incoming ,- incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'Creating Native Server'
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'listening 62214'
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 164 we should not have gotten an error
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 165 socket shouldn't close until after incoming
,ok 166 incoming is cleaned up
,# teardown
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-09-19 12:50:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'Creating Native Server'
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'listening 62218'
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-09-19 12:50:44 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 167 stream was closed
,ok 168 incoming should survive
,ok 169 mux should have no streams
,# teardown
,2017-09-19 12:50:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'Native Server - close'
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-09-19 12:50:44 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'Creating Native Server'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'listening 62222'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-09-19 12:50:45 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 170 we should not have gotten an error
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 171 Buffers are identical
2017-09-19 12:50:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-09-19 12:50:45 - DEBUG createNativeListener: 'Native Server - close'
2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream, <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-09-19 12:50:45 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 172 native server is nulled out
ok 173 native server should be cl,osed
ok 174 incoming has been removed
ok 175 Incoming should be done
ok 176 The mux object should be closed
ok 177 The mux stream should be closed
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-09-19 12:50:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'Creating Native Server'
2017-09-19 12:50:45 - DEBUG createNativeListener: 'listening 62226'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-09-19 12:50:45 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
2017-09-19 12:50:45 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
,2017-09-19 12:50:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'Native Server - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 178 native server is nulled out
,ok 179 native server should be closed
,ok 180 incoming has been removed
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-09-19 12:50:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-09-19 12:50:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'Creating Native Server'
2017-09-19 12:50:47 - DEBUG createNativeListener: 'listening 62278'
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-09-19 12:50:47 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 181 we should not have gotten an error
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 182 Buffers are identical
2017-09-19 12:50:47 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-09-19 12:50:47 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client co,nnection <-> Mux - 0 - close'
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 183 server should be fine
ok 184 server should be open
ok 185 incoming has been removed
ok 186 The mux object should be closed
ok 187 The mux stream should be closed
2017-09-19 12:50:47 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-09-19 12:50:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-09-19 12:50:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-09-19 12:50:47 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'Creating Native Server'
2017-09-19 12:50:47 - DEBUG createNativeListener: 'listening 62282'
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-09-19 12:50:47 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 188 we should not have gotten an error
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 189 Buffers are identical
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 190 server should be fine
,ok 191 server should be open
,ok 192 incoming has been removed
,ok 193 The mux object should be closed
,ok 194 The mux stream should be closed
,# teardown
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-09-19 12:50:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:50:47 - DEBUG createNativeListener: 'Native Server - close'
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
,2017-09-19 12:50:48 - DEBUG createNativeListener: 'Creating Native Server'
,2017-09-19 12:50:48 - DEBUG createNativeListener: 'listening 62285'
ok 198 port must be in range
,# teardown
,2017-09-19 12:50:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-09-19 12:50:48 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-09-19 12:50:48 - DEBUG createNativeListener: 'Creating Native Server'
,2017-09-19 12:50:48 - DEBUG createNativeListener: 'listening 62286'
ok 199 second start should return same port
,# teardown
,2017-09-19 12:50:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-09-19 12:50:48 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-09-19 12:50:48 - DEBUG createNativeListener: 'Creating Native Server'
2017-09-19 12:50:48 - DEBUG createNativeListener: 'listening 62288'
,2017-09-19 12:50:48 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-09-19 12:50:48 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 200 we should be connected
2017-09-19 12:50:48 - DEB,UG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 201 now we are disconnected
,2017-09-19 12:50:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-09-19 12:50:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-09-19 12:50:48 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-09-19 12:50:49 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
ok 202 Passed bogus id
2017-09-19 12:50:49 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port, 901'
ok 203 Passed good id but bogus port
2017-09-19 12:50:49 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
ok 204 Passed right context
ok 205 Right server
ok 206 No error should be set
ok 207 Ret,ry should be false
ok 208 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 62290
,ok 209 should be equal
# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:50:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:50:49 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:50:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-09-19 12:50:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:50:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-09-19 12:50:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:50:49 - DEBUG thaliMobileNativeWrapper: 'Method disc,overyAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:50:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:50:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-09-19 12:50:49 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-09-19 12:50:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:50:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:50:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D
,2017-09-19 12:50:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-09-19 12:50:49 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-09-19 12:50:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 210 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BAF145EB-1C51-4367-A988-16E703F33D45
,[ThaliCore] Browser.startListening
,2017-09-19 12:50:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-09-19 12:50:49 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-09-19 12:50:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 211 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CE085BEC-A868-440D-8066-CAEC5CC0BC19:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CE085BEC-A868-440D-8066-CAEC5CC0BC19", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:E205BA54-258E-4F38-8E64-D5B41A94C652:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E205BA54-258E-4F38-8E64-D5B41A94C652", generation: 0)
2017-09-19 12:50:49 - DEBUG thaliMobileNativeTestUtils: 'W,e got a peer {"peerAvailable":true,"peerIdentifier":"CE085BEC-A868-440D-8066-CAEC5CC0BC19","generation":0}'
,2017-09-19 12:50:49 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CE085BEC-A868-440D-8066-CAEC5CC0BC19 (syncValue: 24WsjD4k1QubmpgzocWlGC90pZtk55iS)'
,2017-09-19 12:50:49 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CE085BEC-A868-440D-8066-CAEC5CC0BC19", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CE085BEC-A868-440D-8066-CAEC5CC0BC19", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CE085BEC-A868-440D-8066-CAEC5CC0BC19:0
[T,haliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-09-19 12:50:49 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifi,er":"E205BA54-258E-4F38-8E64-D5B41A94C652","generation":0}'
,2017-09-19 12:50:49 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:50:49 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:39C6DE90-E027-43EA-AFED-DFDEEFC4A256:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "39C6DE90-E027-43EA-AFED-DFDEEFC4A256", generation: 0)
,2017-09-19 12:50:50 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"39C6DE90-E027-43EA-AFED-DFDEEFC4A256","generation":0}'
,2017-09-19 12:50:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:50:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:50:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7", generation: 0)
,2017-09-19 12:50:50 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7","generation":0}'
,2017-09-19 12:50:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:50:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:50:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:50:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:CE085BEC-A868-440D-8066-CAEC5CC0BC19:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:CE,085BEC-A868-440D-8066-CAEC5CC0BC19:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "CE085BEC-A868-440D-8066-CAEC5CC0BC19", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,E085BEC-A868-440D-8066-CAEC5CC0BC19", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CE085BEC-A868-440D-8066-CAEC5CC0BC19", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:CE085BEC-A868-440D-8066-CAEC5CC0BC19:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:CE085BEC-A868-440D-8066-CAEC5CC0BC19:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:E205BA54-258E-4F38-8E64-D5B41A94C652:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "E205BA54-258E-4F38-8E64-D5B41A94C652", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:CE085BEC-A868-440D-8066-CAEC5CC0BC19:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:CE,085BEC-A868-440D-8066-CAEC5CC0BC19:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "CE085BEC-A868-440D-8066-CAEC5CC0BC19", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,E085BEC-A868-440D-8066-CAEC5CC0BC19", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CE085BEC-A868-440D-8066-CAEC5CC0BC19", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:CE085BEC-A868-440D-8066-CAEC5CC0BC19:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:CE085BEC-A868-440D-8066-CAEC5CC0BC19:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:CE085BEC-A868-440D-8066-CAEC5CC0BC19:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:CE,085BEC-A868-440D-8066-CAEC5CC0BC19:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "CE085BEC-A868-440D-8066-CAEC5CC0BC19", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,E085BEC-A868-440D-8066-CAEC5CC0BC19", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CE085BEC-A868-440D-8066-CAEC5CC0BC19", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:CE085BEC-A868-440D-8066-CAEC5CC0BC19:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:CE085BEC-A868-440D-8066-CAEC5CC0BC19:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:CE085BEC-A868-440D-8066-CAEC5CC0BC19:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "CE085BEC-A868-440D-8066-CAEC5CC0BC19", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:51BDAB58-3AAF-4D36-83C2-B413817F7B28
[ThaliCore] Advertiser: session connected Peer(uuid: "D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:51BDAB58-3AAF-4D36-83C2-B413817F7B28 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:CE085BEC-A868-440D-8066-CAEC5CC0BC19:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:CE,085BEC-A868-440D-8066-CAEC5CC0BC19:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "CE085BEC-A868-440D-8066-CAEC5CC0BC19", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:CE085BEC,-A868-440D-8066-CAEC5CC0BC19 error: max retries exceeded
2017-09-19 12:51:00 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"24WsjD4k1QubmpgzocWlGC90pZtk55iS","error":"Connection could not be established","portNumber":null}'
2017-0,9-19 12:51:00 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '24WsjD4k1QubmpgzocWlGC90pZtk55iS', error: 'Connection could not be established', listeningPort: '%s''
2017-09-19 12:51:00 - ERROR thaliMobileNativeTestUtils: 'Fatal ,c,onnect error: 'Connection could not be established''
2017-09-19 12:51:00 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 39C6DE90-E027-43EA-AFED-DFDEEFC4A256 (syncValue: toVb7aXTcq08EvB6Yun2IQuoCZ2m9qn3)'
2017-09-19 12:51:00 - DEBUG thaliMo,bileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "39C6DE90-E027-43EA-AFED-DFDEEFC4A256", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:s,essionConnected:sessionNotConnected:) Peer(uuid: "39C6DE90-E027-43EA-AFED-DFDEEFC4A256", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:39C6DE90-E027-43EA-AFED-DFDEEFC4A256:0
[ThaliCore] BrowserRelay.init(session,:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-09-19 12:51:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:51:00 - DEBUG thaliMobileNativeTestUtils: 'Al,r,eady running test!'
,[ThaliCore] Session.deinit peer:CE085BEC-A868-440D-8066-CAEC5CC0BC19:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:51BDAB58-3AAF-4D36-83C2-B413817F7B28
,[ThaliCore] Session.session(_:peer:didChange:) peer:51BDAB58-3AAF-4D36-83C2-B413817F7B28 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:39C6DE90-E027-43EA-AFED-DFDEEFC4A256:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:351ED129-3C30-4A7C-BD3B-BB068A992D61
[ThaliCore] Advertiser: session connected Peer(uuid: "D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:351ED129-3C30-4A7C-BD3B-BB068A992D61 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:39C6DE90-E027-43EA-AFED-DFDEEFC4A256:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:39C6DE90-E027-43EA-AFED-DFDEEFC4A256:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "39C6DE90-E027-43EA-AFED-DFDEEFC4A256", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62304
2017-09-19 12:51:05 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"toVb7aXTcq08EvB6Yun2IQuoCZ2m9qn3",,"error":null,"portNumber":62304}'
2017-09-19 12:51:05 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'toVb7aXTcq08EvB6Yun2IQuoCZ2m9qn3', error: 'null', listeningPort: '62304''
,ok 212 should be equal
2017-09-19 12:51:05 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7 (syncValue: G6bq77ZWeh2YSGAYae96s36Lvlf3ddeh)'
2017-09-19 12:51:05 - DEBUG thaliMobileNativeTestUtils: 'Got 'mul,tiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConn,ected:) Peer(uuid: "CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocke,tTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-09-19 12:51:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:351ED129-3C30-4A7C-BD3B-BB068A992D61
,[ThaliCore] Session.session(_:peer:didChange:) peer:351ED129-3C30-4A7C-BD3B-BB068A992D61 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62308
2017-09-19 12:51:08 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"G6bq77ZWeh2YSGAYae96s36Lvlf3ddeh",,"error":null,"portNumber":62308}'
2017-09-19 12:51:08 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'G6bq77ZWeh2YSGAYae96s36Lvlf3ddeh', error: 'null', listeningPort: '62308''
,ok 213 should be equal
# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-09-19 12:51:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 ,12:51:08 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-09-19 12:51:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:D77D6C02-7E8C-45AB-8EFC-0,709AD5F2D8D
2017-09-19 12:51:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:39C6DE90-E027-43EA-AFED-DFDEEFC4A256
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCo,re] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:62304
[ThaliCore] Session.disconnect() peer:39C6DE90-E027-43EA-AFED-DFDEEFC4A256:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TC,PListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:51BDAB58-3AAF-4D36-83C2-B413817F7B28 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "D77D6C02-7E8C-45AB-8EFC-0709AD5F2D8D", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:351ED129-3C30-4A7C-BD3B-BB068A992D61
,[ThaliCore] Session.deinit peer:39C6DE90-E027-43EA-AFED-DFDEEFC4A256:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:62308
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7", generation: 0)
,2017-09-19 12:51:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:51:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-09-19 12:51:08 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"G6bq77ZWeh2YSGAYae96s36Lvlf3ddeh","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:351ED129-3C30-4A7C-BD3B-BB068A992D61
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7:0
[ThaliCore] BrowserRelay.deinit
,# Multiple local http requests
,listening on 62310
,ok 214 should be equal
ok 215 should be equal
ok 216 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:51:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:09 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:51:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-09-19 12:51:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-09-19 12:51:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:51:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:51:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "37F90D9D-C502-4429-B6AC-531362636BBF", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:37F90D9D-C502-4429-B6AC-531362636BBF
,2017-09-19 12:51:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 12:51:10 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:51:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 217 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2C6B04F4-9640-46F5-8BD2-F0B52C8,19BA9
[ThaliCore] Browser.startListening
2017-09-19 12:51:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-09-19 12:51:10 - INFO thaliMobile: 'Received state ({"discove,r,yActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:51:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 218 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:39C6DE90-E027-43EA-AFED-DFDEEFC4A256:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "39C6DE90-E027-43EA-AFED-DFDEEFC4A256", generation: 0)
2017-09-19 12:51:10 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"39C6DE90-E027-43EA-AFED-DFDEEFC4A256","generation":0}'
2017-09-19 12:51:10 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 39C6DE90-E027-43EA-AFED-DFDEEFC4A256, (syncValue: bDP99fM0GjxY1P3y5Hs4en7xhgzTT1aq)'
2017-09-19 12:51:10 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "39C6DE90-E027-43EA-AFED-DFDEEFC,4A256", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "39C6DE90-E027-43EA-AFED-DFDEEFC4A256", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:39C6DE90-E027-43EA-AFED-DFDEEFC4A256:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7",, generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-09-19 12:51:10 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable,":true,"peerIdentifier":"CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7","generation":0}'
2017-09-19 12:51:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:51:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:73CFC2FD-1259-4083-9C92-2E89F1043EE6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "73CFC2FD-1259-4083-9C92-2E89F1043EE6", generation: 0)
2017-09-19 12:51:11 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"73CFC2FD-1259-4083-9C92-2E89F1043EE6","generation":0}'
2017-09-19 12:51:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:51:11 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-09-19 12:51:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:37F90D9D-C502-4429-B6AC-531362636BBF:0
[ThaliCore] BrowserM,anager.foundPeerHandler peer:Peer(uuid: "37F90D9D-C502-4429-B6AC-531362636BBF", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:446E2367-C254-4409-9086-F5ED433913DB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "446E2367-C254-4409-9086-F5ED433913DB", generation: 0)
2017-09-19 12:51:11 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"446E2367-C254-4409-9086-F5ED433913DB","generation":0}'
2017-09-19 12:51:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:51:11 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-09-19 12:51:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-09-19 12:51:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:39C6DE90-E027-43EA-AFED-DFDEEFC4A256:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:39,C6DE90-E027-43EA-AFED-DFDEEFC4A256:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "39C6DE90-E027-43EA-AFED-DFDEEFC4A256", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,9C6DE90-E027-43EA-AFED-DFDEEFC4A256", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "39C6DE90-E027-43EA-AFED-DFDEEFC4A256", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:39C6DE90-E027-43EA-AFED-DFDEEFC4A256:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:39C6DE90-E027-43EA-AFED-DFDEEFC4A256:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:39C6DE90-E027-43EA-AFED-DFDEEFC4A256:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:39,C6DE90-E027-43EA-AFED-DFDEEFC4A256:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "39C6DE90-E027-43EA-AFED-DFDEEFC4A256", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,9C6DE90-E027-43EA-AFED-DFDEEFC4A256", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "39C6DE90-E027-43EA-AFED-DFDEEFC4A256", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:39C6DE90-E027-43EA-AFED-DFDEEFC4A256:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:39C6DE90-E027-43EA-AFED-DFDEEFC4A256:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:39C6DE90-E027-43EA-AFED-DFDEEFC4A256:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "39C6DE90-E027-43EA-AFED-DFDEEFC4A256", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:39C6DE90-E027-43EA-AFED-DFDEEFC4A256:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:39,C6DE90-E027-43EA-AFED-DFDEEFC4A256:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "39C6DE90-E027-43EA-AFED-DFDEEFC4A256", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,9C6DE90-E027-43EA-AFED-DFDEEFC4A256", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "39C6DE90-E027-43EA-AFED-DFDEEFC4A256", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-09-19 12:51:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"bDP99fM0GjxY1P3y5Hs4en7xhgzTT1aq","error":"Peer is unavailable","portNumber":null}'
,2017-09-19 12:51:18 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'bDP99fM0GjxY1P3y5Hs4en7xhgzTT1aq', error: 'Peer is unavailable', listeningPort: '%s''
,2017-09-19 12:51:18 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-09-19 12:51:18 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7 (syncValue: YlMsyBMAnMpnMZQwjyHx0OPgC2Py4Rt8)'
,2017-09-19 12:51:18 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-09-19 12:51:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-09-19 12:51:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:39C6DE90-E027-43EA-AFED-DFDEEFC4A256:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:CF,A49C3E-B67B-4D77-BF0D-298E8ACE5DF7:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,FA49C3E-B67B-4D77-BF0D-298E8ACE5DF7", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C48D091A-B372-4B1C-989A-DB4C536041F1
[ThaliCore] Advertiser: session connected Peer(uuid: "37F90D9D-C502-4429-B6AC-531362636BBF", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:C48D091A-B372-4B1C-989A-DB4C536041F1 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,FA49C3E-B67B-4D77-BF0D-298E8ACE5DF7", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-09-19 12:51:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"YlMsyBMAnMpnMZQwjyHx0OPgC2Py4Rt8","error":"Peer is unavailable",,"portNumber":null}'
2017-09-19 12:51:24 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'YlMsyBMAnMpnMZQwjyHx0OPgC2Py4Rt8', error: 'Peer is unavailable', listeningPort: '%s''
,2017-09-19 12:51:24 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-09-19 12:51:24 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 73CFC2FD-1259-4083-9C92-2E89F1043EE6 (syncValue: TqBvC32GXhhWzFpAjfhozQW,4OafVBGWe)'
2017-09-19 12:51:24 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "73CFC2FD-1259-4083-9C92-2E89F1043EE6", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "73CFC2FD-1259-4083-9C92-2E89F1043EE6", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:73CFC2FD-1259-4083-9C92-2E89F,1043EE6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-09-19 12:51:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:CFA49C3E-B67B-4D77-BF0D-298E8ACE5DF7:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C48D091A-B372-4B1C-989A-DB4C536041F1
,[ThaliCore] Session.session(_:peer:didChange:) peer:C48D091A-B372-4B1C-989A-DB4C536041F1 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:73CFC2FD-1259-4083-9C92-2E89F1043EE6:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3AC58BAD-EEDC-4A96-8A1D-7C5867DED9CD
[ThaliCore] Advertiser: session connected Peer(uuid: "37F90D9D-C502-4429-B6AC-531362636BBF", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:3AC58BAD-EEDC-4A96-8A1D-7C5867DED9CD state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:73CFC2FD-1259-4083-9C92-2E89F1043EE6:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:73CFC2FD-1259-4083-9C92-2E89F1043EE6:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "73CFC2FD-1259-4083-9C92-2E89F1043EE6", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62330
2017-09-19 12:51:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"TqBvC32GXhhWzFpAjfhozQW4OafVBGWe",,"error":null,"portNumber":62330}'
2017-09-19 12:51:27 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'TqBvC32GXhhWzFpAjfhozQW4OafVBGWe', error: 'null', listeningPort: '62330''
,ok 219 should be equal
,ok 220 should be equal
,ok 221 should be equal
,2017-09-19 12:51:27 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 446E2367-C254-4409-9086-F5ED433913DB (syncValue: OxNaHO40I6k5i1IqqWF3Copq5FdkzBEG)'
,2017-09-19 12:51:27 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "446E2367-C254-4409-9086-F5ED433913DB", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "446E2367-C254-4409-9086-F5ED433913DB", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:446E2367-C254-4409-9086-F5ED433913DB:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3AC58BAD-EEDC-4A96-8A1D-7C5867DED9CD
,[ThaliCore] Session.session(_:peer:didChange:) peer:3AC58BAD-EEDC-4A96-8A1D-7C5867DED9CD state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:446E2367-C254-4409-9086-F5ED433913DB:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:446E2367-C254-4409-9086-F5ED433913DB:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:446E2367-C254-4409-9086-F5ED433913DB:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "446E2367-C254-4409-9086-F5ED433913DB", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62336
2017-09-19 12:51:30 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"OxNaHO40I6k5i1IqqWF3Copq5FdkzBEG",,"error":null,"portNumber":62336}'
2017-09-19 12:51:30 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'OxNaHO40I6k5i1IqqWF3Copq5FdkzBEG', error: 'null', listeningPort: '62336''
,ok 222 should be equal
ok 223 should be equal
ok 224 should be equal
# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-09-19 12:51:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 ,12:51:30 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-09-19 12:51:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:37F90D9D-C502-4429-B6AC-5,31362636BBF
2017-09-19 12:51:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
[ThaliCore] BrowserManager.disconnect peer:73CFC2FD-1259-4083-9C92-2E89F1043EE6
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:62330
[ThaliCore] Sessi,on.disconnect() peer:73CFC2FD-1259-4083-9C92-2E89F1043EE6:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:3AC58BAD-EEDC-4A96-8A1D-7C5867DED9CD state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "37F90D9D-C502-4429-B6AC-531362636BBF", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:3AC58BAD-EEDC-4A96-8A1D-7C5867DED9CD
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:73CFC2FD-1259-4083-9C92-2E89F1043EE6:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:446E2367-C254-4409-9086-F5ED433913DB
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:62336
[ThaliCore] Session.disconnect() peer:446E2367-C254-4409-9086-F5ED433913DB:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:C48D091A-B372-4B1C-989A-DB4C536041F1 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "37F90D9D-C502-4429-B6AC-531362636BBF", generation: 0)
,[ThaliCore] Session.deinit peer:3AC58BAD-EEDC-4A96-8A1D-7C5867DED9CD
,[ThaliCore] Session.deinit peer:446E2367-C254-4409-9086-F5ED433913DB:0
,[ThaliCore] BrowserRelay.deinit
,2017-09-19 12:51:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startListeningForAdvertisements should fail if start not called
,ok 225 specific error should be returned
,# teardown
,ok 226 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:31 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-09-19 12:51:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 227 specific error should be returned
# teardown
,ok 228 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:51:31 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopListeningForAdvertisements many times
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'listening 62340'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 229 no errors
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 230 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 231 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startListeningForAdvertisements many times
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'listening 62341'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:099C1B75-C333-4F4C-9EB2-70FB66C991B8
[ThaliCore] Browser.st,artListening
2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-09-19 12:51:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:51:32 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
ok 232 no errors
[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-09-19 12:51:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-09-19 12:51:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 233 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-09-19 12:51:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-09-19 12:51:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-09-19 12:51:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 234 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'listening 62342'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C1858E7F-C3CC-4AD4-865C-53B36CE5578C", generation: 0)
[ThaliCore] Advertiser.startA,dvertising with peerID:C1858E7F-C3CC-4AD4-865C-53B36CE5578C
2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 12:51:32 - INFO thaliMobile: 'Receive,d state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:5,1:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 235 no errors
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C1858E7F-C3CC-4AD4-865C-53B36CE5578C", ge,n,eration: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:C1858E7F-C3CC-4AD4-865C-53B36CE5578C
2017-09-19 12:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-0,9-19 12:51:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":nu,ll,"networkType":null}})'
2017-09-19 12:51:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 236 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:C1858E7F-C3CC-4AD4-865C-53B36CE5578C
[ThaliCore] Advertiser.stopAdvertising() peerID:C1858E7F-C3CC-4AD4-865C-53B36CE5578C
2017-09-19 12:51:33 - DEBUG thaliMo,bileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stop,ListeningForAdvertisements()
2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 237 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopAdvertisingAndListening many times
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'listening 62345'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 238 no errors
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 239 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:33 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-09-19 12:51:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 240 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonT,CP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:51:33 - DEBUG thaliMobi,leNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:51:33 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can get the network status before starting
,ok 241 network status should have certain non-empty properties
,# teardown
,ok 242 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:34 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# error returned with bad router
,2017-09-19 12:51:34 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
ok 243 specific error expected
,# teardown
,ok 244 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-09-19 12:51:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:51:34 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-09-19 12:51:34 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are started when we call start
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'listening 62346'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C40E75AE-0625-47D5-AF99-590D4EC42FA3
[ThaliCore] Browser.st,artListening
2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-09-19 12:51:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:51:34 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6365FE4F-EA79-4F6E-BBC9-27231BAF26CE", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,6365FE4F-EA79-4F6E-BBC9-27231BAF26CE
2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-09-19 12:51:34 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:51:34 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 245 all connection succeed
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:6365FE4F-EA79-4F6E-BBC9-27231BAF26CE
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-09-19 12:51:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-09-19 12:51:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 246 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:34 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# TCP Servers Manager should be null when we call start on iOS
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'listening 62349'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:864A61D6-E837-4C47-9847-01AC0ADF5DCB
[ThaliCore] Browser.st,artListening
2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-09-19 12:51:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:51:35 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D248F754-1B73-4199-BBE7-53FA0DF393F8", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,D248F754-1B73-4199-BBE7-53FA0DF393F8
2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-09-19 12:51:35 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:51:35 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 247 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:D248F754-1B73-4199-BBE7-53FA0DF393F8
2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-09-19 12:51:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:51:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-09-19 12:51:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 248 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are stopped when we call stop
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'listening 62351'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:15F56A3A-824B-4DB7-8E97-BC463BB24470
[ThaliCore] Browser.st,artListening
2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-09-19 12:51:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:51:35 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5064FD85-F250-43B5-A227-4F7F6593999A", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,5064FD85-F250-43B5-A227-4F7F6593999A
2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-09-19 12:51:35 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:51:35 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:5064FD85-F250-43B5-A227-4F7F6593999A
2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrap,per: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-09-19 12:51:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"lis,t,ening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:51:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] B,rowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-09-19 12:51:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 249 is stopped after calling stop
,ok 250 connection should fail after stopping
,# teardown
,ok 251 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-09-19 12:51:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:51:36 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-09-19 12:51:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is properly hooked up
,2017-09-19 12:51:36 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
,# teardown
,ok 252 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:36 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-09-19 12:51:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:51:36 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-09-19 12:51:36 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is return error if we get called on iOS
,ok 253 error description matches
,# teardown
,ok 254 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:36 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-09-19 12:51:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:51:36 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-09-19 12:51:36 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-09-19 12:51:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is properly hooked up
,2017-09-19 12:51:36 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 255 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-09-19 12:51:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:51:37 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-09-19 12:51:37 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is return error if we get called on iOS
,ok 256 error description matches
,# teardown
,ok 257 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:51:37 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-09-19 12:51:37 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure we actually call kill connections properly
,ok 258 IMPLEMENT ME!!!!!!
,# teardown
,ok 259 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:37 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-09-19 12:51:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:51:37 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-09-19 12:51:37 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-09-19 12:51:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-09-19 12:51:37 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 260 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:38 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-09-19 12:51:38 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-09-19 12:51:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 261 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-09-19 12:51:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 262 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:38 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-09-19 12:51:38 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-09-19 12:51:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-09-19 12:51:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 263 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-09-19 12:51:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:51:39 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 264 NOT IMPLEMENTED # SKIP
,# teardown
,ok 265 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:39 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-09-19 12:51:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:51:39 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure bad PSK connections fail
,2017-09-19 12:51:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 266 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:39 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-09-19 12:51:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:51:39 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-09-19 12:51:39 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-09-19 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peer changes handled from a queue
,2017-09-19 12:51:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 267 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:40 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:51:40 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-09-19 12:51:40 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-09-19 12:51:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 268 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:40 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-09-19 12:51:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:51:40 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-09-19 12:51:40 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-09-19 12:51:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 269 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:40 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:51:40 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-09-19 12:51:40 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'listening 62354'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1721531A-489D-4BAA-A0DB-14F107279781
[ThaliCore] Browser.startListening
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-09-19 12:51:40 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-09-19 12:51:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 270 discoveryActive matches
ok 271 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-09-19 12:51:40 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-09-19 12:51:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 272 discoveryActive matches
,ok 273 advertisingActive matches
2017-09-19 12:51:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'listening 62355'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DEC536D9-EA3E-431B-9463-702CF52B75E4", generation: 0)
[ThaliCore] Advertiser.startA,dvertising with peerID:DEC536D9-EA3E-431B-9463-702CF52B75E4
2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-09-19 12:51:40 - INFO thaliMobile: 'Receive,d state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:5,1:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 274 discoveryActive matches
ok 275 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() pee,rID:DEC536D9-EA3E-431B-9463-702CF52B75E4
,2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 276 discoveryActive matches
ok 277 advertisingActive matches
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-09-19 12:51:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-09-19 12:51:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'listening 62357'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 278 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-09-19 12:51:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS
,2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'listening 62358'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:58EF66CF-0D2B-435F-B2A5-B9503C2CEBDE
[ThaliCore] Browser.st,artListening
2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-09-19 12:51:41 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:51:41 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BAD17115-B3D7-4616-834B-02D88C9985D3", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,BAD17115-B3D7-4616-834B-02D88C9985D3
2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-09-19 12:51:41 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-09-19 12:51:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:73CFC2FD-1259-4083-9C92-2E89F1043EE6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "73CFC2FD-1259-4083-9C92-2E89F1043EE6", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:446E2367-C254-4409-9086-F5ED433913DB:0
2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdent,ifier":"73CFC2FD-1259-4083-9C92-2E89F1043EE6","generation":0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "446E2367-C254-4409-9086-F5ED433913DB", generation: 0)
2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"73CFC2FD-1259-4083-9C92-2E89F1043EE6","generation":0}'
,2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"446E2367-C254-4409-9086-F5ED433913DB","generation":0}]'
,2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"446E2367-C254-4409-9086-F5ED433913DB","generation":0}'
,2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"73CFC2FD-1259-4083-9C92-2E89F1043EE6","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-09-19 12:51:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"73CFC2FD-1259-4083-9C92-2E89F1043EE6","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 279 portNumber equal null
,2017-09-19 12:51:41 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"446E2367-C254-4409-9086-F5ED433913DB","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-09-19 12:51:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"446E2367-C254-4409-9086-F5ED433913DB","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1EB74B74-2182-4EF8-AB06-C62817FE919E:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1EB74B74-2182-4EF8-AB06-C62817FE919E", generation: 0)
,2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"1EB74B74-2182-4EF8-AB06-C62817FE919E","generation":0}]'
,2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"1EB74B74-2182-4EF8-AB06-C62817FE919E","generation":0}'
,2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1EB74B74-2182-4EF8-AB06-C62817FE919E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-09-19 12:51:42 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1EB74B74-2182-4EF8-AB06-C62817FE919E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BAD17115-B3D7-4616-834B-02D88C9985D3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BAD17115-B3D7-4616-834B-02D88C9985D3", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E", generation: 0)
2017-09-19 12:51:42 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E","generation":0}]'
2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E","generation":0}'
,2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E","peerAvailable":true,"generation":0,"portNumber":null}'
2017-09-19 12:51:42 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:446E2367-C254-4409-9086-F5ED433913DB:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "446E2367-C254-4409-9086-F5ED433913DB", generation: 0)
2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"446E2367-C254-4409-9086-F5ED433913DB","generation":0}]'
2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"446E2367-C254-4409-9086-F5ED433913DB","generation":0}'
,2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"446E2367-C254-4409-9086-F5ED433913DB","peerAvailable":false,"generation":null,"portNumber":null}'
2017-09-19 12:51:42 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"446E2367-C254-4409-9086-F5ED433913DB","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:BAD17115-B3D7-4616-834B-02D88C9985D3
2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-09-19 12:51:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-09-19 12:51:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19, 12:51:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-09-19 12:51:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 280 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvert,isements()
2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in st,opped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-09-19 12:51:42 - INFO thaliMobile: 'F,i,ltered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-09-19 12:51:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-09-19 12:51:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests between peers
,2017-09-19 12:51:43 - DEBUG thaliMobileNativeWrapper: 'listening 62360'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:91937F6F-BD98-4E96-8699-1C9D51983889
,[ThaliCore] Browser.startListening
,2017-09-19 12:51:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-09-19 12:51:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-09-19 12:51:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C1D0148D-6FD3-48E7-B035-B4E113A88E98", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:C1D0148D-6FD3-48E7-B035-B4E113A88E98
,2017-09-19 12:51:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-09-19 12:51:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-09-19 12:51:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:73CFC2FD-1259-4083-9C92-2E89F1043EE6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "73CFC2FD-1259-4083-9C92-2E89F1043EE6", generation: 0)
2017-09-19 12:51:44 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"73CFC2FD-1259-4083-9C92-2E89F1043EE6","generation":0}]'
2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"73CFC2FD-1259-4083-9C92-2E89F1043EE6","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1EB74B74-2182-4EF8-AB06-C62817FE919E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1EB74B74-2182-4EF8-AB06-C62817FE919E", generation: 0)
2017-09-19 12:51:44 - DEBUG t,haliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"73CFC2FD-1259-4083-9C92-2E89F1043EE6","peerAvailable":true,"generation":0,"portNumber":null}'
2017-09-19 12:51:44 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"pe,erIdentifier":"73CFC2FD-1259-4083-9C92-2E89F1043EE6","peerAvailable":true,"generation":0,"portNumber":null}'
2017-09-19 12:51:44 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 73CFC2FD-1259-4083-9C92-2E89F1043EE6 (syncValue: IWBybQAFPMbTYeQ,y2pnArF3bvkOS54I5)'
2017-09-19 12:51:44 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "73CFC2FD-1259-4083-9C92-2E89F1043EE6", generation: 0) crea,t,ing a new relay
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E", generation: 0)
[ThaliCore] ,Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "73CFC2FD-1259-4083-9C92-2E89F1043EE6", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:73CFC2FD-1259-4083-9C92-2E89F1043EE6:0
[ThaliCore,] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{,"peerAvailable":true,"peerIdentifier":"1EB74B74-2182-4EF8-AB06-C62817FE919E","generation":0}]'
2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"1EB74B74-2182-4EF8-,AB06-C62817FE919E","generation":0}'
,2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E","generation":0}]'
2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E","generation":0}'
,2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1EB74B74-2182-4EF8-AB06-C62817FE919E","peerAvailable":true,"generation":0,"portNumber":null}'
2017-09-19 12:51:44 - DEBUG thaliMobileNativeT,estUtils: 'We got a peer {"peerIdentifier":"1EB74B74-2182-4EF8-AB06-C62817FE919E","peerAvailable":true,"generation":0,"portNumber":null}'
2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"0A,6A84DF-CF71-4FBB-A7BE-5C1F6851219E","peerAvailable":true,"generation":0,"portNumber":null}'
2017-09-19 12:51:44 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E","peerAvailable":true,"generation":0,,"portNumber":null}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E", generation: 0)
2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E","generation":0}]'
2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E","generation":0}'
,2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E","peerAvailable":false,"generation":null,"portNumber":null}'
2017-09-19 12:51:44 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:1EB74B74-2182-4EF8-AB06-C62817FE919E:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "1EB74B74-2182-4EF8-AB06-C62817FE919E", generation: 0)
2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"1EB74B74-2182-4EF8-AB06-C62817FE919E","generation":0}]'
2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"1EB74B74-2182-4EF8-AB06-C62817FE919E","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:11F98CCD-AF7B-421E-ACC2-2EBC279ED663:0
[ThaliCore] BrowserManager.foundPeerHandle,r peer:Peer(uuid: "11F98CCD-AF7B-421E-ACC2-2EBC279ED663", generation: 0)
2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"1EB74B74-2182-4EF8-AB06-C62817FE919E","peerAvailable":false,"generation":n,u,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:573C5C14-23ED-405D-B676-0A82D053A509:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "573C5C14-23ED-405D-B676-0A82D053A509", generation: 0)
ll,"portNumber":null}'
2017-,09-19 12:51:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1EB74B74-2182-4EF8-AB06-C62817FE919E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-09-19 12:51:44 - DE,BUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"11F98CCD-AF7B-421E-ACC2-2EBC279ED663","generation":0}]'
2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapper: 'Received peer a,vailability changed event with {"peerAvailable":true,"peerIdentifier":"11F98CCD-AF7B-421E-ACC2-2EBC279ED663","generation":0}'
2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable,"[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C1D0148D-6FD3-48E7-B035-B4E113A88E98:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C1D0148D-6FD3-48E7-B035-B4E113A88E98", generation: 0)
:true,"peerIdentifier":"573C,5C14-23ED-405D-B676-0A82D053A509","generation":0}]'
2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"573C5C14-23ED-405D-B676-0A82D053A509","generation":0}'
,2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"11F98CCD-AF7B-421E-ACC2-2EBC279ED663","peerAvailable":true,"generation":0,"portNumber":null}'
2017-09-19 12:51:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"11F98CCD-AF7B-421E-ACC2-2EBC279ED663","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-09-19 12:51:44 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"11F98CCD-AF7B-421E-ACC2-2EBC279ED663","peerAvailable":true,"generation":0,"portNumber":null}'
2017-09-19 12:51:44 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"573C5C14-23ED-405D-B676-,0A82D053A509","peerAvailable":true,"generation":0,"portNumber":null}'
2017-09-19 12:51:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"573C5C14-23ED-405D-B676-0A82D053A509","connectionType":"MPCF","peerAvailab,le":true,"generation":0,"newAddressPort":false}'
2017-09-19 12:51:44 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"573C5C14-23ED-405D-B676-0A82D053A509","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E", generation: 0)
2017-09-19 12:51:46 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E","generation":0}]'
2017-09-19 12:51:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E","generation":0}'
,2017-09-19 12:51:46 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E","peerAvailable":true,"generation":0,"portNumber":null}'
2017-09-19 12:51:46 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-09-19 12:51:46 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:73CFC2FD-1259-4083-9C92-2E89F1043EE6:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:73,CFC2FD-1259-4083-9C92-2E89F1043EE6:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "73CFC2FD-1259-4083-9C92-2E89F1043EE6", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,3CFC2FD-1259-4083-9C92-2E89F1043EE6", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "73CFC2FD-1259-4083-9C92-2E89F1043EE6", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:73CFC2FD-1259-4083-9C92-2E89F1043EE6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:73CFC2FD-1259-4083-9C92-2E89F1043EE6:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:73CFC2FD-1259-4083-9C92-2E89F1043EE6:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "73CFC2FD-1259-4083-9C92-2E89F1043EE6", generation: 0)
2017-09-19 12:51:47 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"73CFC2FD-1259-4083-9C92-2E89F1043EE6","generation":0}]'
2017-09-19 12:51:47 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"73CFC2FD-1259-4083-9C92-2E89F1043EE6","generation":0}'
,2017-09-19 12:51:47 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"73CFC2FD-1259-4083-9C92-2E89F1043EE6","peerAvailable":false,"generation":null,"portNumber":null}'
2017-09-19 12:51:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"73CFC2FD-1259-4083-9C92-2E89F1043EE6","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E", generation: 0)
2017-09-19 12:51:47 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E","generation":0}]'
2017-09-19 12:51:47 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E","generation":0}'
,2017-09-19 12:51:47 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E","peerAvailable":false,"generation":null,"portNumber":null}'
2017-09-19 12:51:47 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"0A6A84DF-CF71-4FBB-A7BE-5C1F6851219E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:73CFC2FD-1259-4083-9C92-2E89F1043EE6:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:73,CFC2FD-1259-4083-9C92-2E89F1043EE6:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "73CFC2FD-1259-4083-9C92-2E89F1043EE6", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,3CFC2FD-1259-4083-9C92-2E89F1043EE6", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "73CFC2FD-1259-4083-9C92-2E89F1043EE6", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-09-19 12:51:49 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"IWBybQAFPMbTYeQy2pnArF3bvkOS54I5","error":"Peer is unavailable",,"portNumber":null}'
2017-09-19 12:51:49 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'IWBybQAFPMbTYeQy2pnArF3bvkOS54I5', error: 'Peer is unavailable', listeningPort: '%s''
,2017-09-19 12:51:49 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-09-19 12:51:49 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 11F98CCD-AF7B-421E-ACC2-2EBC279ED663 (syncValue: YXAFp7xUBiSAED7Lv3Zfyft,Uui46wbwv)'
2017-09-19 12:51:49 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "11F98CCD-AF7B-421E-ACC2-2EBC279ED663", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "11F98CCD-AF7B-421E-ACC2-2EBC279ED663", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:11F98CCD-AF7B-421E-ACC2-2EBC2,79ED663:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:73CFC2FD-1259-4083-9C92-2E89F1043EE6:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:11F98CCD-AF7B-421E-ACC2-2EBC279ED663:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:11F98CCD-AF7B-421E-ACC2-2EBC279ED663:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:11F98CCD-AF7B-421E-ACC2-2EBC279ED663:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "11F98CCD-AF7B-421E-ACC2-2EBC279ED663", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62368
,2017-09-19 12:51:52 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"YXAFp7xUBiSAED7Lv3ZfyftUui46wbwv","error":null,"portNumber":62368}'
,2017-09-19 12:51:52 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'YXAFp7xUBiSAED7Lv3ZfyftUui46wbwv', error: 'null', listeningPort: '62368''
,2017-09-19 12:51:52 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:11F98CCD-AF7B-421E-ACC2-2EBC279ED663:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:11F98CCD-AF7B-421E-ACC2-2EBC279ED663:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [1, 3, 7, 16]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-09-19 12:51:52 - DEBUG testUtils: 'Got response data'
2017-09-19 12:51:52 - DEBUG testUtils: 'Got end'
ok 281 response body should match testData
ok 282 must be started
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:73CFC2FD-1259-4083-9C92-2E89F1043EE6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "73CFC2FD-1259-4083-9C92-2E89F1043EE6", generation: 0)
2017-09-19 12:52:02 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"73CFC2FD-1259-4083-9C92-2E89F1043EE6","generation":0}]'
2017-09-19 12:52:02 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"73CFC2FD-1259-4083-9C92-2E89F1043EE6","generation":0}'
,2017-09-19 12:52:02 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"73CFC2FD-1259-4083-9C92-2E89F1043EE6","peerAvailable":true,"generation":0,"portNumber":null}'
2017-09-19 12:52:02 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"73CFC2FD-1259-4083-9C92-2E89F1043EE6","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F35E4BF1-0B91-4A8A-A127-D90726FED4AE
[ThaliCore] Advertiser: session connected Peer(uuid: "C1D0148D-6FD3-48E7-B035-B4E113A88E98", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:F35E4BF1-0B91-4A8A-A127-D90726FED4AE state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:73CFC2FD-1259-4083-9C92-2E89F1043EE6:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "73CFC2FD-1259-4083-9C92-2E89F1043EE6", generation: 0)
2017-09-19 12:52:04 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"73CFC2FD-1259-4083-9C92-2E89F1043EE6","generation":0}]'
2017-09-19 12:52:04 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"73CFC2FD-1259-4083-9C92-2E89F1043EE6","generation":0}'
,2017-09-19 12:52:04 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"73CFC2FD-1259-4083-9C92-2E89F1043EE6","peerAvailable":false,"generation":null,"portNumber":null}'
2017-09-19 12:52:04 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"73CFC2FD-1259-4083-9C92-2E89F1043EE6","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F35E4BF1-0B91-4A8A-A127-D90726FED4AE
,[ThaliCore] Session.session(_:peer:didChange:) peer:F35E4BF1-0B91-4A8A-A127-D90726FED4AE state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F35E4BF1-0B91-4A8A-A127-D90726FED4AE
[ThaliCore] Session.startOutputStream(with:) peer:F35E4BF1-0B91-4A8A-A127-D90726FED4AE
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [1, 3, 7, 16, 17]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
2017-09-19 12:52:52 - INFO, CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server ,that is not listening yet witheatNotRunning set to true'
2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOG,GER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoi,n,ts plugin delay interval'
2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-09-19 12:52:52 - INFO Coordin,atedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue, and run in order'
2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
2017-09-19 12:,52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly han,dled'
2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: ski,pped - skip'
2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
2017-09-19 12:52:52 - INFO CoordinatedClien,t: '***TEST_LOGGER result: passed - test sinon sansbox stub'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiConnect properly fails on legal but non-existent peerID'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with invalid syncValue'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call disconnect with invalid peer id'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - disconnect doesn't fail on plausible but bogus peer ID'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Get same port when trying to connect multiple times on iOS'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - initial peer discovery'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 1'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 2'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - check latest peer discovery'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Set up for no peer discovery test'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - no peer discovery'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits incomingConnectionState'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server connections all up'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can create servers manager'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling stop without start causes error'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can start/stop servers manager'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connection'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single local http request'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single coordinated request ios native'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple local http requests'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple coordinated request ios native'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status before starting'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - error returned with bad router'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are started when we call start'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP Servers Manager should be null when we call start on iOS'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are stopped when we call stop'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateConnection is properly hooked up'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateConnection is return error if we get called on iOS'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateListener is properly hooked up'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateListener is return error if we get called on iOS'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure we actually call kill connections properly'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from multiConnectConnection'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure bad PSK connections fail'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer changes handled from a queue'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - relaying discoveryAdvertisingStateUpdateNonTCP'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - we successfully receive and replay discoveryAdvertisingStateUpdate'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS'
,2017-09-19 12:52:52 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - can do HTTP requests between peers, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C2,1/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers,.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1
''
2017-09-19 12:52:52 - ERROR Coordinat,edClient: 'failed to run unit tests, platformName: 'ios''
,2017-09-19 12:56:24 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2017-09-19 12:56:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:56:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:56:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:56:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:56:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:56:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:56:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:56:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:56:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:56:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:57:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:57:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:57:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:57:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:57:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:57:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:57:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:57:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:57:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:57:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:57:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:57:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:58:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:58:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:58:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:58:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:58:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:58:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:58:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:58:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:58:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:58:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:58:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:58:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:59:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:59:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:59:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:59:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:59:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:59:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:59:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:59:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:59:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:59:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 12:59:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 12:59:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:00:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:00:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:00:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:00:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:00:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:00:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:00:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:00:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:00:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:00:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:00:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:00:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:01:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:01:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:01:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:01:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:01:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:01:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:01:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:01:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:01:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:01:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:01:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:01:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:02:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:02:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:02:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:02:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:02:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:02:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:02:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:02:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:02:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:02:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:03:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:03:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:03:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:03:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:03:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:03:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:03:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:03:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:03:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:03:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:03:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:03:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:04:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:04:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:04:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:04:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:04:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:04:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:04:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:04:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:04:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:04:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:04:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:04:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-4,4E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:05:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:05:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:05:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:05:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:05:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:05:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:05:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:05:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:05:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:05:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:05:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:05:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:06:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:06:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:06:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:06:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:06:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:06:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:06:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E,2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:06:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-09-19 13:06:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-09-19 13:06:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/20A5D688-A469-44E2-863D-0E7F6ABB3C21/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''

```
