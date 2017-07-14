#### Test 1133518510faaea9_iOS_Iphone6sPlus-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/1133518510faaea9/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/942CCDFA-57F0-4C82-8767-08437FEC8D41/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'
,Executing commands in '/tmp/942CCDFA-57F0-4C82-8767-08437FEC8D41/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/1133518510faaea9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/1133518510faaea9/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59511"
,(lldb)     command script import "/tmp/942CCDFA-57F0-4C82-8767-08437FEC8D41/fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.py"
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
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-07-14 11:25:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:25:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:25:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:25:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 11:25:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:25:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:25:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserMa,nager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "971FD3F5-1A1B-47FF-B552-57356EF038BB", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:971FD3F5-1A1B-47FF-B552-57356EF038BB
,Optional(true)
Optional(false)
AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:CC5B1CBC-17BD-489D-A7BC-FD3F6DE809C7
[ThaliCore] Browser.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:fo,undPeer:lostPeer:) peer:E52A2617-AF73-4638-B552-E3819881BD58
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "26E8E1E4-39A2-477C-A849-68A8B88EE3C4", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:26E8E1E4-39A2-477C-A849-68A8B88EE3C4
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:26E8E1E4-39A2-477C-A849-68A8B88EE3C4:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "26E8E1E4-39A2-477C-A849-68A8B88EE3C4", generation: 0)
AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvaila,bilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCorrect finished
AppContextTests finished
All tests finished
All tests finished
2017-07-14 11:25:29 - DEBUG UnitTest_app: 'Running unit te,sts'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.478999972343445
2017-07-14 11:25:29 - DEBUG UnitTest_app: 'My device name is:, 'Apple-Iphone6sPlus-1''
,2017-07-14 11:25:29 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:26E8E1E4-39A2-477C-A849-68A8B88EE3C4:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "26E8E1E4-39A2-477C-A849-68A8B88EE3C4", generation: 0)
,2017-07-14 11:25:30 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-14 11:25:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-14 11:25:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-14 11:25:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-14 11:25:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-14 11:25:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-14 11:25:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-14 11:25:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-14 11:25:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-14 11:25:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-14 11:25:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-14 11:25:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-14 11:25:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-14 11:25:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-14 11:25:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-14 11:25:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-14 11:25:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-14 11:25:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-14 11:25:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-14 11:25:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-14 11:25:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-14 11:25:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-14 11:25:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-14 11:25:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-14 11:25:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-14 11:25:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-14 11:25:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-14 11:25:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-14 11:25:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-14 11:25:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-14 11:25:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-14 11:25:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-14 11:25:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-14 11:25:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-14 11:25:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-14 11:25:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-14 11:25:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-14 11:25:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-14 11:25:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-14 11:25:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-14 11:25:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-14 11:25:32 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-14 11:25:32 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-14 11:25:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:25:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:25:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:25:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:25:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:25:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:25:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:25:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:25:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:26:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:26:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:26:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:26:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:26:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:26:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:26:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:26:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:26:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:26:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:26:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:26:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:27:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:27:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:27:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:27:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:27:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:27:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-4,06D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:27:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:27:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:27:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:27:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:27:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:27:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:28:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:28:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:28:16 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-07-14 11:28:16 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-14 11:28:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll with promise
,2017-07-14 11:28:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-14 11:28:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-07-14 11:28:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-07-14 11:28:27 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-07-14 11:28:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-07-14 11:28:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-07-14 11:28:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
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
,2017-07-14 11:28:50 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-07-14 11:28:50 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-07-14 11:28:51 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
ok 58 throws if usn has invalid prefix
ok 59 throws if usn has invalid identifier format
ok 60 throws if usn has invalid generation
ok 61 correctly stringifies peer
,# teardown
,# setup
,# onPeerLost calls jxcore
,2017-07-14 11:28:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-14 11:28:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:28:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:28:55 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:28:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 11:28:55 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 11:28:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 11:28:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 11:28:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-14 11:28:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-14 11:28:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:28:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:28:55 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:28:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 11:28:55 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 11:28:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 11:28:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 11:28:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:28:56 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:28:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8F2D1155-BFB8-4991-AB35-2311C7A8A4A1
,[ThaliCore] Browser.startListening
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:28:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-14 11:28:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 62 Can call startListeningForAdvertisements without error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:28:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:28:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 64 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:28:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 65 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:28:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4786C68E-1DB3-4596-8D29-580F700EB557
,[ThaliCore] Browser.startListening
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:28:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 11:28:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 66 Can call startListeningForAdvertisements without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:28:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 11:28:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 67 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:28:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 68 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:28:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 69 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:28:57 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 11:28:57 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:28:57 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 70 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingAct,ive":false}'
2017-07-14 11:28:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 71 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:28:57 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 72 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdver,tisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:28:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:28:57 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 11:28:57 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F3509F75-2AED-4B84-8D4E-C4BCB1610F82", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:F3509F75-2AED-4B84-8D4E-C4BCB1610F82
2017-07-14 11:28:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-14 11:28:58 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-14 11:28:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising(,)
[ThaliCore] Advertiser.stopAdvertising()
2017-07-14 11:28:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:28:58 - INFO thaliMobile: 'Filtered out discovery,AdvertisingStateUpdate (was in stopped state).'
ok 75 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 11:28:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:28:58 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 76 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 11:28:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdver,tisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:28:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 77 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 11:28:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:28:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:28:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:28:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 11:28:58 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 11:28:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 11:28:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 11:28:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8C4B9AF1-F699-450E-AAC2-802D500308B7", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:8C4B9AF1-F699-450E-AAC2-802D500308B7
,2017-07-14 11:28:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 11:28:58 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:28:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 78 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8C4B9AF1-F699-450E-AAC2-802D500308B7", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:8C4B9AF1-F699-450E-AAC2-802D500308B7
2017-07-14 1,1:28:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-14 11:28:58 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-14 11:28:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 79 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 11:28:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 11:28:59 - INFO thaliMobile: 'Receive,d state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:2,8:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 80 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertisin,g()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 11:28:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:28:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 81 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 11:28:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:28:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:28:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:28:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 11:28:59 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 11:28:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:28:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:28:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 11:28:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:28:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 82 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 11:28:59 - DEBUG th,aliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:28:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 83 Can call stopAdverti,singAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 11:29:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:29:00 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 84 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:29:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:29:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 85 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 11:29:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:29:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:29:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:29:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 11:29:00 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 11:29:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 11:29:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 11:29:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "28E6A239-B69C-4274-A411-DD9E8D1E94BB", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:28E6A239-B69C-4274-A411-DD9E8D1E94BB
2017-07-14 11:29:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-14 11:29:00 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-14 11:29:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 86 Can call startUpdateAdvertisingAndListeningwithout error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8F9E8DFE-15F5-4311-90E0-F99D9AC17FDC
,[ThaliCore] Browser.startListening
2017-07-14 11:29:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 11:29:00 - INFO thaliMobile: 'Received state ({"discoveryActive,":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 11:29:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CFDB3600-5C66-4F43-8D70-1D53F58FC5A4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CFDB3600-5C66-4F43-8D70-1D53F58FC5A4", generation: 0)
ok 88 peers must be an array,
ok 89 peers must not be zero-length
ok 90 peer must have only peerIdentifier, peerAvailable and generation properties
ok 91 peerIdentifier must be a string
ok 92 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:80DF8A94-63B2-4251-838F-96CD4A4899AA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "80DF8A94-63B2-4251-838F-96CD4A4899AA", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-14 11:29:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 ,11:29:01 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-14 11:29:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 93 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
2017-07-14 11:29:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:29:01 - INFO thaliMobile: 'Filtered out discoveryAd,v,ertisingStateUpdate (was in stopped state).'
ok 94 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 11:29:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:29:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:29:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:29:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:29:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:29:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:29:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:29:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3F6B5DBB-1C61-4809-A491-89BBC874CDFD", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:3F6B5DBB-1C61-4809-A491-89BBC874CDFD
2017-07-14 11:29:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 11:29:02, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-14 11:29:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 95 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Thal,iCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:0AD29B33-51CE-4502-8298-1BF0AFC9D459
[ThaliCore] Browser.startListening
2017-07-14 11:29:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adve,r,tisingActive":true}'
2017-07-14 11:29:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"rout,er":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:29:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 96 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CFDB3600-5C66-4F43-8D70-1D53F58FC5A4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CFDB3600-5C66-4F43-8D70-1D53F58FC5A4", generation: 0)
2017-07-14 11:29:03 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CFDB3600-5C66-4F43-8D70-1D53F58FC5A4","generation":0}'
2017-07-14 11:29:03 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CFDB3600-5C66-4F43-8D70-1D53F58FC5A4, (syncValue: c0MmhFkI2qOnktJJAf6sHAN4nIBiNbJ5)'
2017-07-14 11:29:03 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "CFDB3600-5C66-4F43-8D70-1D53F58FC5A4", gen,eration: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CFDB3600-5C66-4F43-8D70-1D53F58FC5A4", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CFDB3600-5C66-,4F43-8D70-1D53F58FC5A4:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:80DF8A94-63B2-4251-838F-96CD4A4899AA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "80DF8A94-63B2-4251-838F-96CD4A4899AA", generation: 0)
[Th,aliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-14 11:29:03 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"80DF8A94-63B2-4251-838F-96CD4A4899AA","generation":0}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:80DF8A94-63B2-4251-838F-96CD4A4899AA:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "80DF8A94-63B2-4251-838F-96CD4A4899AA", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:7B90ADCE-E704-407C-9CE8-7BB8430AD315:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7B90ADCE-E704-407C-9CE8-7BB8430AD315", generation: 0)
2017-07-14 11:29:03 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAv,ailable":true,"peerIdentifier":"7B90ADCE-E704-407C-9CE8-7BB8430AD315","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B8364F78-AFB6-40C3-9EF2-9D0689F5A8DD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B8364F78-AFB6-40C3-9EF2-9D0689F5A8DD", generation: 0)
2017-07-14 11:29:03 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B8364F78-AFB6-40C3-9EF2-9D0689F5A8DD","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3F6B5DBB-1C61-4809-A491-89BBC874CDFD:0
[ThaliC,ore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3F6B5DBB-1C61-4809-A491-89BBC874CDFD", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:CFDB3600-5C66-4F43-8D70-1D53F58FC5A4:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "CFDB3600-5C66-4F43-8D70-1D53F58FC5A4", generation: 0)
,[ThaliCore] Session.disconnect() peer:CFDB3600-5C66-4F43-8D70-1D53F58FC5A4:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:CFDB3600-5C66-4F43-8D70-1D53F58FC5A4:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "CFDB3600-5C66-4F43-8D70-1D53F58FC5A4", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:CFDB3600-5C66-4F43-8D70-1D53F58FC5A4:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "CFDB3600-5C66-4F43-8D70-1D53F58FC5A4", genera,tion: 0)
2017-07-14 11:29:08 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"c0MmhFkI2qOnktJJAf6sHAN4nIBiNbJ5","error":"Connection could not be established","portNumber":null}'
2017-07-14 11:29:08 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'c0MmhFkI2qOnktJJAf6sHAN4nIBiNbJ5', error: 'Connection could not be established', listeningPort: '%s''
2017-07-14 11:29:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"CFDB3600-5C66-4F43-8D70-1D53F58FC5A4","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 11:29:08 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-14 ,11:29:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"CFDB3600-5C66-4F43-8D70-1D53F58FC5A4","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-14 11:29:08 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 11:29:08 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-14 11:29:08 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 7B90ADCE-E704-407C-9CE8-7BB8430AD315 (syncValue: bGRBJoT,gTjbLZ5vb2Q3hLkraB1e8uQM6)'
2017-07-14 11:29:08 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "7B90ADCE-E704-407C-9CE8-7BB8430AD315", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7B90ADCE-E704-407C-9CE8-7BB8430AD315", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7B90ADCE-E704-407C-9CE8-7BB8430AD31,5:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E45E358F-33A0-407C-85A7-5D1F4057AA9A
[ThaliCore] Advertiser: session connected Peer(uuid: "3F6B5DBB-1C61-4809-A491-89BBC874CDFD", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:E45E358F-33A0-407C-85A7-5D1F4057AA9A state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:7B90ADCE-E704-407C-9CE8-7BB8430AD315:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E45E358F-33A0-407C-85A7-5D1F4057AA9A
,[ThaliCore] Session.session(_:peer:didChange:) peer:E45E358F-33A0-407C-85A7-5D1F4057AA9A state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7B90ADCE-E704-407C-9CE8-7BB8430AD315:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:7B90ADCE-E704-407C-9CE8-7BB8430AD315:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "7B90ADCE-E704-407C-9CE8-7BB8430AD315", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49977
2017-07-14 11:29:12 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"bGRBJoTgTjbLZ5vb2Q3hLkraB1e8uQM6","error":null,"portN,umber":49977}'
2017-07-14 11:29:12 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'bGRBJoTgTjbLZ5vb2Q3hLkraB1e8uQM6', error: 'null', listeningPort: '49977''
,2017-07-14 11:29:12 - INFO testThaliMobileNative: ''
ok 97 Must have listeningPort
ok 98 listeningPort must be a number
ok 99 listening port should not be 0
,# teardown
,2017-07-14 11:29:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-14 11:29:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 11:29:12 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:29:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 100 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-14 11:29:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTC,P: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:29:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 101 Should be able to call stopAdvertisingAndListening in teardown
[ThaliCore] Brow,serManager.disconnect peer:7B90ADCE-E704-407C-9CE8-7BB8430AD315
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49977
[ThaliCore] Session.disconnect() peer:7B90ADCE,-E704-407C-9CE8-7BB8430AD315:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] Session.session(_:peer:didChange:) peer:7B90ADCE-E704-407C-9CE8-7BB8430AD315:0 state: connected -> notConnected
[ThaliCore] ,B,rowser: session notConnected Peer(uuid: "7B90ADCE-E704-407C-9CE8-7BB8430AD315", generation: 0)
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "7B90ADCE-E704-407C-9CE8-7BB8430AD315", generation: 0)
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:E45E358F-33A0-407C-85A7-5D1F4057AA9A state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "3F6B5DBB-1C61-4809-A491-89BBC874CDFD", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:E45E358F-33A0-407C-85A7-5D1F4057AA9A
[ThaliCore] Advert,iserRelay.deinit
[ThaliCore] Session.deinit peer:E45E358F-33A0-407C-85A7-5D1F4057AA9A
,2017-07-14 11:29:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:29:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:29:12 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:29:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 11:29:12 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 11:29:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 11:29:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 11:29:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3EF12D56-06E7-4BD7-B33A-43FCA5D374FE", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:3EF12D56-06E7-4BD7-B33A-43FCA5D374FE
2017-07-14 1,1:29:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 11:29:12 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:29:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 102 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:38A4A1D1-D0AB-482D-85EE-4022A956DB3C
[Tha,l,iCore] Browser.startListening
2017-07-14 11:29:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 11:29:12 - INFO thaliMobile: 'Received state ({"discoveryActive":tru,e,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:29:12 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 103 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B8364F78-AFB6-40C3-9EF2-9D0689F5A8DD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B8364F78-AFB6-40C3-9EF2-9D0689F5A8DD", generation: 0)
2017-07-14 11:29:13 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B8364F78-AFB6-40C3-9EF2-9D0689F5A8DD","generation":0}'
2017-07-14 11:29:13 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B8364F78-AFB6-40C3-9EF2-9D0689F5A8DD, (syncValue: 8f3lDOkW9J582PYcKFdAUXoL7RQgLKr6)'
2017-07-14 11:29:13 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "B8364F78-AFB6-40C3-9EF2-9D0689F5A8DD", gen,eration: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B8364F78-AFB6-40C3-9EF2-9D0689F5A8DD", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B8364F78-AFB6-,40C3-9EF2-9D0689F5A8DD:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7B90ADCE-E704-407C-9CE8-7BB8430AD315:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7B90ADCE-E704-407C-9CE8-7BB8430AD315", generation: 0)
[Th,aliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-14 11:29:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifie,r":"7B90ADCE-E704-407C-9CE8-7BB8430AD315","generation":0}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:7B90ADCE-E704-407C-9CE8-7BB8430AD315:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "7B90ADCE-E704-407C-9CE8-7BB8430AD315", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:630D69F0-7B0D-4353-B1D3-72041CE8B2A3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "630D69F0-7B0D-4353-B1D3-72041CE8B2A3", generation: 0)
2017-07-14 11:29:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAv,ailable":true,"peerIdentifier":"630D69F0-7B0D-4353-B1D3-72041CE8B2A3","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:14DF6D47-0838-4CD4-8191-E53A4CB3D543:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "14DF6D47-0838-4CD4-8191-E53A4CB3D543", generation: 0)
2017-07-14 11:29:14 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"14DF6D47-0838-4CD4-8191-E53A4CB3D543","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3EF12D56-06E7-4BD7-B33A-43FCA5D374FE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3EF12D56-06E7-4BD7-B33A-43FCA5D374FE", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B8364F78-AFB6-40C3-9EF2-9D0689F5A8DD:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "B8364F78-AFB6-40C3-9EF2-9D0689F5A8DD", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:B8364F78-AFB6-40C3-9EF2-9D0689F5A8DD:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "B8364F78-AFB6-40C3-9EF2-9D0689F5A8DD", genera,tion: 0)
2017-07-14 11:29:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8f3lDOkW9J582PYcKFdAUXoL7RQgLKr6","error":"Connection could not be established","portNumber":null}'
2017-07-14 11:29:19 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: '8f3lDOkW9J582PYcKFdAUXoL7RQgLKr6', error: 'Connection could not be established', listeningPort: '%s''
2017-07-14 11:29:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"B8364F78-AFB6-40C3-9EF2-9D0689F5A8DD","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 11:29:19 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-14 11:29:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B8364F78-AFB6-40C3-9EF2-9D0689F5A8DD","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-14 11:29:19 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 11:29:19 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-14 11:29:19 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 630D69F0-7B0D-4353-B1D3-72041CE8B2A3 (syncValue: 8XgHxJI,7viDLQOTsaEpw2SUCX2rxveT4)'
2017-07-14 11:29:19 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "630D69F0-7B0D-4353-B1D3-72041CE8B2A3", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "630D69F0-7B0D-4353-B1D3-72041CE8B2A3", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:630D69F0-7B0D-4353-B1D3-72041CE8B2A,3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FDA7BE12-20BF-4092-8157-C88DE6F4E901
[ThaliCore] Advertiser: session connected Peer(uuid: "3EF12D56-06E7-4BD7-B33A-43FCA5D374FE", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:FDA7BE12-20BF-4092-8157-C88DE6F4E901 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:630D69F0-7B0D-4353-B1D3-72041CE8B2A3:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:630D69F0-7B0D-4353-B1D3-72041CE8B2A3:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FDA7BE12-20BF-4092-8157-C88DE6F4E901
,[ThaliCore] Session.session(_:peer:didChange:) peer:FDA7BE12-20BF-4092-8157-C88DE6F4E901 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FDA7BE12-20BF-4092-8157-C88DE6F4E901
[ThaliCore] Session.startOutputStream(with:) peer:FDA7BE12-20BF-4092-8157-C88DE6F4E901
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-14 11:29:22 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-14 11:29:22 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-14 11:29:22 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-07-14 11:29:22 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:1
[ThaliCore] VirtualSocket.closeStreams() vsID:1
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:1
[ThaliCore] VirtualSocket.deinit vsID:1 []
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:630D69F0-7B0D-4353-B1D3-72041CE8B2A3:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "630D69F0-7B0D-4353-B1D3-72041CE8B2A3", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49984
2017-07-14 11:29:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8XgHxJI7viDLQOTsaEpw2SUCX2rxveT4",,"error":null,"portNumber":49984}'
2017-07-14 11:29:22 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '8XgHxJI7viDLQOTsaEpw2SUCX2rxveT4', error: 'null', listeningPort: '49984''
,Connecting to the localhost:49984
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:630D69F0-7B0D-4353-B1D3-72041CE8B2A3:0
,Connected to the localhost:49984
2017-07-14 11:29:22 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
2017-07-14 11:29:22 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:630D69F0-7B0D-4353-B1D3-72041CE8B2A3:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [2]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 104 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pe,er})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStream,s() vsID:2
# teardown
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:2
[ThaliCore] VirtualSocket.deinit vsID:2 []
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:02328334-95F8-4265-8DF2-5DAB01C83275
[ThaliCore] Advertiser: session connected Peer(uuid: "3EF12D56-06E7-4BD7-B33A-43FCA5D374FE", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:02328334-95F8-4265-8DF2-5DAB01C83275 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:02328334-95F8-4265-8DF2-5DAB01C83275
,[ThaliCore] Session.session(_:peer:didChange:) peer:02328334-95F8-4265-8DF2-5DAB01C83275 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:02328334-95F8-4265-8DF2-5DAB01C83275
[ThaliCore] Session.startOutputStream(with:) peer:02328334-95F8-4265-8DF2-5DAB01C83275
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3, [3]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-14 11:29:27 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-07-14 11:29:27 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
2017-07-14 11:29:27 - DEBUG testThaliMobileNative: 'Server sends data bac,k to client (20 bytes):'
2017-07-14 11:29:27 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:3
[ThaliCore] VirtualSocket.closeStreams() vsID:3
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:3,
[ThaliCore] VirtualSocket.deinit vsID:3 []
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDis,connectHandler disconnecting:false
,2017-07-14 11:29:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-14 11:29:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 11:29:28 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:29:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 105 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-14 11:29:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTC,P: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:29:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 106 Should be able to call stopAdvertisingAndListening in teardown
[ThaliCore] Brow,serManager.disconnect peer:630D69F0-7B0D-4353-B1D3-72041CE8B2A3
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49984
[ThaliCore] Session.disconnect() peer:630D69F0,-7B0D-4353-B1D3-72041CE8B2A3:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] Session.session(_:peer:didChange:) peer:630D69F0-7B0D-4353-B1D3-72041CE8B2A3:0 state: connected -> notConnected
[ThaliCore] ,B,rowser: session notConnected Peer(uuid: "630D69F0-7B0D-4353-B1D3-72041CE8B2A3", generation: 0)
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "630D69F0-7B0D-4353-B1D3-72041CE8B2A3", generation: 0)
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:02328334-95F8-4265-8DF2-5DAB01C83275 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "3EF12D56-06E7-4BD7-B33A-43FCA5D374FE", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:02328334-95F8-4265-8DF2-5DAB01C83275
[ThaliCore] Advert,iserRelay.deinit
[ThaliCore] Session.deinit peer:02328334-95F8-4265-8DF2-5DAB01C83275
,2017-07-14 11:29:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:29:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:29:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:FDA7BE12-20BF-4092-8157-C88DE6F4E901 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "3EF12D56-06E7-4BD7-B33A-43FCA5D374FE", generation: 0)
,2017-07-14 11:29:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 11:29:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-14 11:29:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 11:29:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 11:29:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F12BAB81-3393-4AA2-9828-2D573BD80FEA", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:F12BAB81-3393-4AA2-9828-2D573BD80FEA
2017-07-14 1,1:29:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 11:29:28 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:29:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 107 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7765DE71-9DF4-416D-9138-EBDD851164D3
[Tha,l,iCore] Browser.startListening
2017-07-14 11:29:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 11:29:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:29:28 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 108 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:630D69F0-7B0D-4353-B1D3-72041CE8B2A3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "630D69F0-7B0D-4353-B1D3-72041CE8B2A3", generation: 0)
2017-07-14 11:29:29 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"630D69F0-7B0D-4353-B1D3-72041CE8B2A3","generation":0}'
2017-07-14 11:29:29 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 630D69F0-7B0D-4353-B1D3-72041CE8B2A3, (syncValue: HSdeg2qboqspQf5xc17Ofh6vqGVN4hKI)'
2017-07-14 11:29:29 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "630D69F0-7B0D-4353-B1D3-72041CE8B2A3", gen,eration: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "630D69F0-7B0D-4353-B1D3-72041CE8B2A3", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:630D69F0-7B0D-,4,353-B1D3-72041CE8B2A3:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:14DF6D47-0838-4CD4-8191-E53A4CB3D543:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "14DF6D47-0838-4CD4-8191-E53A4CB3D543", generation: 0)
[Tha,liCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-14 11:29:29 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"14DF6D47-0838-4CD4-8191-E53A4CB3D543","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FFF4B219-CD64-4984-A16E-09A0AC4255C5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FFF4B219-CD64-4984-A16E-09A0AC4255C5", generation: 0)
2017-07-14 11:29:29 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FFF4B219-CD64-4984-A16E-09A0AC4255C5","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:278B96CA-1D44-46A9-9D5A-17875731F8E8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "278B96CA-1D44-46A9-9D5A-17875731F8E8", generation: 0)
,2017-07-14 11:29:29 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"278B96CA-1D44-46A9-9D5A-17875731F8E8","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F12BAB81-3393-4AA2-9828-2D573BD80FEA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F12BAB81-3393-4AA2-9828-2D573BD80FEA", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:630D69F0-7B0D-4353-B1D3-72041CE8B2A3:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "630D69F0-7B0D-4353-B1D3-72041CE8B2A3", generation: 0)
[ThaliCore] Session.disconnect() peer:630D69F0-7B0D-4353-B1D3-72041CE8B2A3:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:630D69F0-7B0D-4353-B1D3-72041CE8B2A3:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "630D69F0-7B0D-4353-B1D3-72041CE8B2A3", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:630D69F0-7B0D-4353-B1D3-72041CE8B2A3:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "630D69F0-7B0D-4353-B1D3-72041CE8B2A3", genera,tion: 0)
2017-07-14 11:29:34 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"HSdeg2qboqspQf5xc17Ofh6vqGVN4hKI","error":"Connection could not be established","portNumber":null}'
2017-07-14 11:29:34 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'HSdeg2qboqspQf5xc17Ofh6vqGVN4hKI', error: 'Connection could not be established', listeningPort: '%s''
2017-07-14 11:29:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"630D69F0-7B0D-4353-B1D3-72041CE8B2A3","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 11:29:34 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-14 ,11:29:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"630D69F0-7B0D-4353-B1D3-72041CE8B2A3","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-14 11:29:34 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 11:29:34 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-14 11:29:34 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 14DF6D47-0838-4CD4-8191-E53A4CB3D543 (syncValue: l89ULcD,4pFaI7c2FaM8IuQcBdclOwHPs)'
2017-07-14 11:29:34 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "14DF6D47-0838-4CD4-8191-E53A4CB3D543", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "14DF6D47-0838-4CD4-8191-E53A4CB3D543", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:14DF6D47-0838-4CD4-8191-E53A4CB3D54,3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7AA0CCB5-DB1B-4C44-818E-1FEE65C0EC37
[ThaliCore] Advertiser: session connected Peer(uuid: "F12BAB81-3393-4AA2-9828-2D573BD80FEA", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:7AA0CCB5-DB1B-4C44-818E-1FEE65C0EC37 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7AA0CCB5-DB1B-4C44-818E-1FEE65C0EC37
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:14DF6D47-0838-4CD4-8191-E53A4CB3D543:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "14DF6D47-0838-4CD4-8191-E53A4CB3D543", generation: 0)
[ThaliCore] Session.disconnect() peer:14DF6D47-083,8-4CD4-8191-E53A4CB3D543:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:7AA0CCB5-DB1B-4C44-818E-1FEE65C0EC37 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7AA0CCB5-DB1B-4C44-818E-1FEE65C0EC37
[ThaliCore] Session.startOutputStream(with:) peer:7AA0CCB5-DB1B-4C44-818E-1FEE65C0EC37
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [4]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7AA0CCB5-DB1B-4C44-818E-1FEE65C0EC37
[ThaliCore] Session.startOutputStream(with:) peer:7AA0CCB5-DB1B-4C44-818E-1FEE65C0,EC37
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [4, 5]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7AA0CCB5-DB1B-4C44-818E-1FEE65C0EC37
[ThaliCore] Session.st,artOutputStream(with:) peer:7AA0CCB5-DB1B-4C44-818E-1FEE65C0EC37
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [4, 5, 6]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-14 11:29:39 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-14 11:29:39 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-14 11:29:39 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-14 11:29:39 - DEBUG testThaliMobileNative: 'Server received (71 bytes):'
,2017-07-14 11:29:39 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-14 11:29:39 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-14 11:29:39 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-14 11:29:39 - DEBUG testThaliMobileNative: 'Server received (2261 bytes):'
,2017-07-14 11:29:39 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-14 11:29:39 - DEBUG testThaliMobileNative: 'Server received (2119 bytes):'
,2017-07-14 11:29:39 - DEBUG testThaliMobileNative: 'Server received (1125 bytes):'
,2017-07-14 11:29:39 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-14 11:29:39 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-14 11:29:39 - DEBUG testThaliMobileNative: 'Server data flushed',
2017-07-14 11:29:39 - DEBUG testThaliMobileNative: 'Server received (6570 bytes):'
,2017-07-14 11:29:39 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-14 11:29:39 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-14 11:29:39 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-14 11:29:39 - DEBUG testThaliMobileNative: 'Server received (2119 bytes):'
,2017-07-14 11:29:39 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-14 11:29:39 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
2017-07-14 11:29:39 - DEBUG testThaliMobileNative: 'Server received (3072 bytes):'
,2017-07-14 11:29:39 - DEBUG testThaliMobileNative: 'Server received (30 bytes):'
,2017-07-14 11:29:39 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-14 11:29:39 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-14 11:29:39 - DEBUG testThaliMobileNative: 'Server data flushed',
2017-07-14 11:29:39 - DEBUG testThaliMobileNative: 'Server received (13312 bytes):'
2017-07-14 11:29:39 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-14 11:29:39 - DEBUG testThaliMobileNative: 'Server sends data back to client, (16384 bytes):'
2017-07-14 11:29:39 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:4
[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:6
[ThaliCore] VirtualSocket.closeStreams() vsID:6
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:5
[ThaliCore] VirtualSocket.closeStreams() vsID:5
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:6
[ThaliCore] VirtualSocket.deinit vsID:6 [4, 5]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:5
[ThaliCore] VirtualSocket.deinit vsID:5 [4]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:14DF6D47-0838-4CD4-8191-E53A4CB3D543:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "14DF6D47-0838-4CD4-8191-E53A4CB3D543", generation: 0)
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:14DF6D47-0838-4CD4-8191-E53A4CB3D543:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "14DF6D47-0838-4CD4-8191-E53A4CB3D543", genera,tion: 0)
2017-07-14 11:29:40 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"l89ULcD4pFaI7c2FaM8IuQcBdclOwHPs","error":"Connection could not be established","portNumber":null}'
2017-07-14 11:29:40 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'l89ULcD4pFaI7c2FaM8IuQcBdclOwHPs', error: 'Connection could not be established', listeningPort: '%s''
2017-07-14 11:29:40 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"14DF6D47-0838-4CD4-8191-E53A4CB3D543","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 11:29:40 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-14 ,11:29:40 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"14DF6D47-0838-4CD4-8191-E53A4CB3D543","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-14 11:29:40 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 11:29:40 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-14 11:29:40 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for FFF4B219-CD64-4984-A16E-09A0AC4255C5 (syncValue: 3Bz8HgI,gVxS8j6tPc7l07H3j3Q17ZyzJ)'
2017-07-14 11:29:40 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "FFF4B219-CD64-4984-A16E-09A0AC4255C5", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FFF4B219-CD64-4984-A16E-09A0AC4255C5", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FFF4B219-CD64-4984-A16E-09A0AC4255C,5:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2D430EE3-11E3-4AD8-A3CF-F9466273717C
[ThaliCore] Advertiser: session connected Peer(uuid: "F12BAB81-3393-4AA2-9828-2D573BD80FEA", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:2D430EE3-11E3-4AD8-A3CF-F9466273717C state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:FFF4B219-CD64-4984-A16E-09A0AC4255C5:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FFF4B219-CD64-4984-A16E-09A0AC4255C5:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2D430EE3-11E3-4AD8-A3CF-F9466273717C
,[ThaliCore] Session.session(_:peer:didChange:) peer:FFF4B219-CD64-4984-A16E-09A0AC4255C5:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "FFF4B219-CD64-4984-A16E-09A0AC4255C5", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49999
,2017-07-14 11:29:42 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3Bz8HgIgVxS8j6tPc7l07H3j3Q17ZyzJ","error":null,"portNumber":49999}'
,2017-07-14 11:29:42 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '3Bz8HgIgVxS8j6tPc7l07H3j3Q17ZyzJ', error: 'null', listeningPort: '49999''
,Connecting to the localhost:49999
,Connecting to the localhost:49999
Connecting to the localhost:49999
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FFF4B219-CD64-4984-A16E-09A0,AC4255C5:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FFF4B219-CD64-4984-A16E-09A0AC4255C5:0
[ThaliCore] TCPListener.socket(_:didAcceptNewS,ocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FFF4B219-CD64-4984-A16E-09A0AC4255C5:0
Connected to the localhost:49999
,Connected to the localhost:49999
,Connected to the localhost:49999
,ok 109 correct string length
,2017-07-14 11:29:42 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 110 correct string length
,2017-07-14 11:29:42 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 111 correct string length
,2017-07-14 11:29:42 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-14 11:29:42 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-14 11:29:42 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-14 11:29:42 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FFF4B219-CD64-4984-A16E-09A0AC4255C5:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [4, 7]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FFF4B219-CD64-4984-A16E-09A0AC4255C5:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [4, 7, 8]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FFF4B219-CD64-4984-A16E-09A0AC4255C5:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [4, 7, 8, 9]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 112 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:7
[ThaliCore] Browser,Relay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:7
[ThaliCore] VirtualSocket.deinit vsID:7 [4, 8, 9]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:8
ok 113 got the same data back
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:8
,[ThaliCore] VirtualSocket.deinit vsID:8 [4, 9]
,[ThaliCore] Session.session(_:peer:didChange:) peer:2D430EE3-11E3-4AD8-A3CF-F9466273717C state: connecting -> connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
ok 114 got the same data back
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStream,s() vsID:9
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,# teardown
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2D430EE3-11E3-4AD8-A3CF-F9466273717C
[ThaliCore] Session.startOutputStream(with:) peer:2D430EE3-11E3-4AD8-A3CF-F9466273717C
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [4, 9, 10]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2D430EE3-11E3-4AD8-A3CF-F9466273717C
,[ThaliCore] Session.startOutputStream(with:) peer:2D430EE3-11E3-4AD8-A3CF-F9466273717C
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [4, 9, 10, 11]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2D430EE3-11E3-4AD8-A3CF-F9466273717C
[ThaliCore] Session.startOutputStream(with:) peer:2D430EE3-11E3-4AD8-A3CF-F9466273717C
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [4, 9, 10, 11, 12]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-14 11:29:43 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-14 11:29:43 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-14 11:29:43 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-14 11:29:43 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-14 11:29:43 - DEBUG testThaliMobileNative: 'Server received (2149 bytes):'
,2017-07-14 11:29:43 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-14 11:29:43 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-14 11:29:43 - DEBUG testThaliMobileNative: 'Server data flushed',
,2017-07-14 11:29:43 - DEBUG testThaliMobileNative: 'Server received (4238 bytes):'
,2017-07-14 11:29:43 - DEBUG testThaliMobileNative: 'Server received (3427 bytes):'
,2017-07-14 11:29:43 - DEBUG testThaliMobileNative: 'Server received (4309 bytes):'
,2017-07-14 11:29:43 - DEBUG testThaliMobileNative: 'Server received (4410 bytes):'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:10
,[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:10
[ThaliCore] VirtualSocket.deinit vsID:10 [4, 9, 11, 12]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-14 11:29:43 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-14 11:29:44 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-14 11:29:44 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-14 11:29:44 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-14 11:29:44 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-14 11:29:44 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-14 11:29:44 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:11
[ThaliCore] VirtualSocket.closeStreams() vsID:11
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:11
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.deinit vsID:11 [4, 9, 12]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:12
[ThaliCore] VirtualSocket.closeStreams() vsID:12
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:12
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] VirtualSocket.deinit vsID:12 [4, 9]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-14 11:29:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-14 11:29:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-14 11:29:44 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 11:29:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 115 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 11:29:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:29:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 116 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:FFF4B219-CD64-4984-A16E-09A0AC4255C5
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49999
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.disconnect() peer:FFF4B219-CD64-4984-A16E-09A0AC4255C5:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:FFF4B219-CD64-4984-A16E-09A0AC4255C5:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "FFF4B219-CD64-4984-A16E-09A0AC4255C5", generation: 0)
[ThaliCore] BrowserRel,ay.closeRelay() disconnecting:true
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "FFF4B219-CD64-4984-A16E-09A0AC4255C5", generation: 0)
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:2D430EE3-11E3-4AD8-A3CF-F9466273717C state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "F12BAB81-3393-4AA2-9828-2D573BD80FEA", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:2D430EE3-11E3-4AD8-A3CF-F9466273717C
,[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.deinit peer:2D430EE3-11E3-4AD8-A3CF-F9466273717C
,[ThaliCore] Session.session(_:peer:didChange:) peer:7AA0CCB5-DB1B-4C44-818E-1FEE65C0EC37 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "F12BAB81-3393-4AA2-9828-2D573BD80FEA", generation: 0)
,2017-07-14 11:29:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:29:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:29:44 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:29:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 11:29:44 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 11:29:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 11:29:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 11:29:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "0E8F36F6-99AE-405C-9D86-AFF2583B9FB5", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:0E8F36F6-99AE-405C-9D86-AFF2583B9FB5
,2017-07-14 11:29:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-14 11:29:45 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 11:29:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 117 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9A3F0BDA-1A8E-48C4-BB6C-57D36F8E777E
,[ThaliCore] Browser.startListening
,2017-07-14 11:29:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 11:29:45 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 11:29:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 118 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FFF4B219-CD64-4984-A16E-09A0AC4255C5:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FFF4B219-CD64-4984-A16E-09A0AC4255C5", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:278B96CA-1D44-46A9-9D5A-17875731F8E8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "278B96CA-1D44-46A9-9D5A-17875731F8E8", generation: 0)
,2017-07-14 11:29:45 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FFF4B219-CD64-4984-A16E-09A0AC4255C5","generation":0}'
,2017-07-14 11:29:45 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for FFF4B219-CD64-4984-A16E-09A0AC4255C5 (syncValue: Aq11waPeaopbgA7QSK3NAvvzZD4qRr8C)'
,2017-07-14 11:29:45 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "FFF4B219-CD64-4984-A16E-09A0AC4255C5", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FFF4B219-CD64-4984-A16E-09A0AC4255C5", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FFF4B219-CD64-4984-A16E-09A0AC4255C5:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-14 11:29:45 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"278B96CA-1D44-46A9-9D5A-17875731F8E8","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5C412DB4-3630-41E3-B6E7-1228683AFE89:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5C412DB4-3630-41E3-B6E7-1228683AFE89", generation: 0)
,2017-07-14 11:29:46 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5C412DB4-3630-41E3-B6E7-1228683AFE89","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C8951314-1504-4B26-B452-4EE45DC1E5BE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C8951314-1504-4B26-B452-4EE45DC1E5BE", generation: 0)
2017-07-14 11:29:46 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C8951314-1504-4B26-B452-4EE45DC1E5BE","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0E8F36F6-99AE-405C-9D86-AFF2583B9FB5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0E8F36F6-99AE-405C-9D86-AFF2583B9FB5", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:FFF4B219-CD64-4984-A16E-09A0AC4255C5:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "FFF4B219-CD64-4984-A16E-09A0AC4255C5", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:FFF4B219-CD64-4984-A16E-09A0AC4255C5:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "FFF4B219-CD64-4984-A16E-09A0AC4255C5", genera,tion: 0)
2017-07-14 11:29:51 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Aq11waPeaopbgA7QSK3NAvvzZD4qRr8C","error":"Connection could not be established","portNumber":null}'
2017-07-14 11:29:51 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'Aq11waPeaopbgA7QSK3NAvvzZD4qRr8C', error: 'Connection could not be established', listeningPort: '%s''
2017-07-14 11:29:51 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"FFF4B219-CD64-4984-A16E-09A0AC4255C5","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 11:29:51 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-14 ,11:29:51 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"FFF4B219-CD64-4984-A16E-09A0AC4255C5","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-14 11:29:51 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 11:29:51 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-14 11:29:51 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 278B96CA-1D44-46A9-9D5A-17875731F8E8 (syncValue: NDn6XMh,avdnnekTx6VRJMXbPQMUnlMn2)'
2017-07-14 11:29:51 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "278B96CA-1D44-46A9-9D5A-17875731F8E8", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "278B96CA-1D44-46A9-9D5A-17875731F8E8", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:278B96CA-1D44-46A9-9D5A-17875731F8E,8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:278B96CA-1D44-46A9-9D5A-17875731F8E8:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "278B96CA-1D44-46A9-9D5A-17875731F8E8", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:278B96CA-1D44-46A9-9D5A-17875731F8E8:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "278B96CA-1D44-46A9-9D5A-17875731F8E8", genera,tion: 0)
2017-07-14 11:29:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"NDn6XMhavdnnekTx6VRJMXbPQMUnlMn2","error":"Connection could not be established","portNumber":null}'
2017-07-14 11:29:56 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'NDn6XMhavdnnekTx6VRJMXbPQMUnlMn2', error: 'Connection could not be established', listeningPort: '%s''
2017-07-14 11:29:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"278B96CA-1D44-46A9-9D5A-17875731F8E8","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 11:29:56 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-14 ,11:29:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"278B96CA-1D44-46A9-9D5A-17875731F8E8","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-14 11:29:56 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 11:29:56 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-14 11:29:56 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5C412DB4-3630-41E3-B6E7-1228683AFE89 (syncValue: EemP075,OVQgqdPa7ZaeEmvlpw1GHcMtp)'
2017-07-14 11:29:56 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "5C412DB4-3630-41E3-B6E7-1228683AFE89", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5C412DB4-3630-41E3-B6E7-1228683AFE89", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5C412DB4-3630-41E3-B6E7-1228683AFE8,9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DE656F0B-E661-47B6-9F44-012BDA801F49
[ThaliCore] Advertiser: session connected Peer(uuid: "0E8F36F6-99AE-405C-9D86-AFF2583B9FB5", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:DE656F0B-E661-47B6-9F44-012BDA801F49 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:39134FA1-97AB-4820-914B-6C6D3356CA8D
[ThaliCore] Advertiser: session connected Peer(uuid: "0E8F36F6-99AE-405C-9D86-AFF2583B9FB5", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:39134FA1-97AB-4820-914B-6C6D3356CA8D state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:5C412DB4-3630-41E3-B6E7-1228683AFE89:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:39134FA1-97AB-4820-914B-6C6D3356CA8D
,[ThaliCore] Session.session(_:peer:didChange:) peer:39134FA1-97AB-4820-914B-6C6D3356CA8D state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:39134FA1-97AB-4820-914B-6C6D3356CA8D
[ThaliCore] Session.startOutputStream(with:) peer:39134FA1-97AB-4820-914B-6C6D3356CA8D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,3 [4, 9, 13]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-07-14 11:29:59 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-14 11:29:59 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-14 11:29:59 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-14 11:29:59 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-14 11:29:59 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:13
[ThaliCore] VirtualSocket.closeStreams() vsID:13
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:13
,[ThaliCore] VirtualSocket.deinit vsID:13 [4, 9]
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:DE656F0B-E661-47B6-9F44-012BDA801F49
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5C412DB4-3630-41E3-B6E7-1228683AFE89:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:DE656F0B-E661-47B6-9F44-012BDA801F49 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DE656F0B-E661-47B6-9F44-012BDA801F49
[ThaliCore] Session.startOutputStream(with:) peer:DE656F0B-E661-47B6-9F44-012BDA801F49
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [4, 9, 14]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:5C412DB4-3630-41E3-B6E7-1228683AFE89:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "5C412DB4-3630-41E3-B6E7-1228683AFE89", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50017
,2017-07-14 11:30:00 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"EemP075OVQgqdPa7ZaeEmvlpw1GHcMtp","error":null,"portNumber":50017}'
,2017-07-14 11:30:00 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'EemP075OVQgqdPa7ZaeEmvlpw1GHcMtp', error: 'null', listeningPort: '50017''
,Connecting to the localhost:50017
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5C412DB4-3630-41E3-B6E7-1228683AFE89:0
,Server received psk id: psk-id
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5C412DB4-3630-41E3-B6E7-1228683AFE89:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [4, 9, 14, 15]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 11:30:00 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-14 11:30:00 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-14 11:30:00 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-14 11:30:00 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-14 11:30:00 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:14
[ThaliCore] VirtualSocket.closeStreams() vsID:14
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:14
,[ThaliCore] VirtualSocket.deinit vsID:14 [4, 9, 15]
,Connected to the localhost:50017
,2017-07-14 11:30:00 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-14 11:30:00 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 119 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:15
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,# teardown
,2017-07-14 11:30:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-14 11:30:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 11:30:00 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:30:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-14 11:30:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTC,P: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:30:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in teardown
[ThaliCore] Brow,serManager.disconnect peer:5C412DB4-3630-41E3-B6E7-1228683AFE89
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50017
[ThaliCore] Session.disconnect() peer:5C412DB4-3630-41E3-B6E7-1228683AFE89:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] Session.session(_:peer:didChange:) peer:5C412DB4-3630-41E3-B6E7-1228683AFE89:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "5C412DB4-3630-41E3-B6E7-1228683AFE89", generation: 0)
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "5C412DB4-3630-41E3-B6E7-1228683AFE89", generation: 0)
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:39134FA1-97AB-4820-914B-6C6D3356CA8D state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "0E8F36F6-99AE-405C-9D86-AFF2583B9FB5", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:39134FA1-97AB-4820-914B-6C6D3356CA8D
[ThaliCore] Advert,iserRelay.deinit
[ThaliCore] Session.deinit peer:39134FA1-97AB-4820-914B-6C6D3356CA8D
,[ThaliCore] Session.session(_:peer:didChange:) peer:DE656F0B-E661-47B6-9F44-012BDA801F49 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "0E8F36F6-99AE-405C-9D86-AFF2583B9FB5", generation: 0)
,2017-07-14 11:30:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:30:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:30:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 11:30:01 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 11:30:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 11:30:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 11:30:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3203DACF-B417-4CCC-94E9-26751E12B3CC", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:3203DACF-B417-4CCC-94E9-26751E12B3CC
,2017-07-14 11:30:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-14 11:30:01 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 11:30:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 122 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B7417788-2AEE-41A9-B2CD-891949FE3532
[ThaliCore] Browser.startListening
,2017-07-14 11:30:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 11:30:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-14 11:30:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 123 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5C412DB4-3630-41E3-B6E7-1228683AFE89:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5C412DB4-3630-41E3-B6E7-1228683AFE89", generation: 0)
2017-07-14 11:30:01 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5C412DB4-3630-41E3-B6E7-1228683AFE89","generation":0}'
2017-07-14 11:30:01 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5C412DB4-3630-41E3-B6E7-1228683AFE89, (syncValue: lej4USV3wbFkRX7VxiPtB3FPhH5RDEsh)'
2017-07-14 11:30:01 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "5C412DB4-3630-41E3-B6E7-1228683AFE89", gen,eration: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5C412DB4-3630-41E3-B6E7-1228683AFE89", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:278B96CA-1D44-46A9-9D5A-17875731F8E8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "278B96CA-1D44-46A9-9D5A-17875731F8E8", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5C412DB4-3630-41E3-B6E7-1228683AFE89:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-14 11:30:01 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"278B96CA-1D44-46A9-9D5A-17875731F8E8","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3203DACF-B417-4CCC-94E9-26751E12B3CC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3203DACF-B417-4CCC-94E9-26751E12B3CC", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A4101E0A-2D4F-4307-AF8E-D44CB4B5801D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A4101E0A-2D4F-4307-AF8E-D44CB4B5801D", generation: 0)
2017-07-14 11:30:02 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"A4101E0A-2D4F-4307-AF8E-D44CB4B5801D","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4C30EC80-858C-4E61-957C-3AAAD5A8369E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4C30EC80-858C-4E61-957C-3AAAD5A8369E", generation: 0)
2017-07-14 11:30:03 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4C30EC80-858C-4E61-957C-3AAAD5A8369E","generation":0}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:278B96CA-1D44-46A9-9D5A-17875731F8E8:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "278B96CA-1D44-46A9-9D5A-17875731F8E8", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:5C412DB4-3630-41E3-B6E7-1228683AFE89:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "5C412DB4-3630-41E3-B6E7-1228683AFE89", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:5C412DB4-3630-41E3-B6E7-1228683AFE89:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "5C412DB4-3630-41E3-B6E7-1228683AFE89", genera,tion: 0)
2017-07-14 11:30:07 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"lej4USV3wbFkRX7VxiPtB3FPhH5RDEsh","error":"Connection could not be established","portNumber":null}'
2017-07-14 11:30:07 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'lej4USV3wbFkRX7VxiPtB3FPhH5RDEsh', error: 'Connection could not be established', listeningPort: '%s''
2017-07-14 11:30:07 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"5C412DB4-3630-41E3-B6E7-1228683AFE89","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 11:30:07 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-14 ,11:30:07 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"5C412DB4-3630-41E3-B6E7-1228683AFE89","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-14 11:30:07 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 11:30:07 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-14 11:30:07 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for A4101E0A-2D4F-4307-AF8E-D44CB4B5801D (syncValue: gYfjgyr,f0eJRcVEeDRfWdN8extQSiGIB)'
2017-07-14 11:30:07 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "A4101E0A-2D4F-4307-AF8E-D44CB4B5801D", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A4101E0A-2D4F-4307-AF8E-D44CB4B5801D", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A4101E0A-2D4F-4307-AF8E-D44CB4B5801,D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:A4101E0A-2D4F-4307-AF8E-D44CB4B5801D:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A4101E0A-2D4F-4307-AF8E-D44CB4B5801D:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:A4101E0A-2D4F-4307-AF8E-D44CB4B5801D:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "A4101E0A-2D4F-4307-AF8E-D44CB4B5801D", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50026
2017-07-14 11:30:10 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"gYfjgyrf0eJRcVEeDRfWdN8extQSiGIB",,"error":null,"portNumber":50026}'
2017-07-14 11:30:10 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'gYfjgyrf0eJRcVEeDRfWdN8extQSiGIB', error: 'null', listeningPort: '50026''
,Connecting to the localhost:50026
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A4101E0A-2D4F-4307-AF8E-D44CB4B5801D:0
Connected to the localh,ost:50026
,2017-07-14 11:30:10 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-14 11:30:10 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A4101E0A-2D4F-4307-AF8E-D44CB4B5801D:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [4, 9, 15, 16]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:16
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:16
,[ThaliCore] VirtualSocket.deinit vsID:16 [4, 9, 15]
,ok 124 got the same data back
,# teardown
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:5C412DB4-3630-41E3-B6E7-1228683AFE89:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "5C412DB4-3630-41E3-B6E7-1228683AFE89", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:AA379747-01A1-4A4B-8F7B-CD076EE4D8A4
[ThaliCore] Advertiser: session connected Peer(uuid: "3203DACF-B417-4CCC-94E9-26751E12B3CC", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:11B1710A-4AC0-48A7-A91D-941826AA5C81
[ThaliCore] Advertiser: session connected Peer(uuid: "3203DACF-B417-4CCC-94E9-26751E12B3CC", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:AA379747-01A1-4A4B-8F7B-CD076EE4D8A4 state: notConnected -> connecting
[T,haliCore] Session.session(_:peer:didChange:) peer:11B1710A-4AC0-48A7-A91D-941826AA5C81 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:11B1710A-4AC0-48A7-A91D-941826AA5C81
,[ThaliCore] Session.session(_:peer:didChange:) peer:11B1710A-4AC0-48A7-A91D-941826AA5C81 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:AA379747-01A1-4A4B-8F7B-CD076EE4D8A4
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:11B1710A-4AC0-48A7-A91D-941826AA5C81
[ThaliCore] Session.startOutputStream(with:) peer:11B1710A-4AC0-48A7-A91D-941826AA5C81
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [4, 9, 15, 17]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:AA379747-01A1-4A4B-8F7B-CD076EE4D8A4 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:AA379747-01A1-4A4B-8F7B-CD076EE4D8A4
[ThaliCore] Session.startOutputStream(with:) peer:AA379747-01A1-4A4B-8F7B-CD076EE4D8A4
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:18 [4, 9, 15, 17, 18]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,2017-07-14 11:30:16 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-14 11:30:16 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-14 11:30:16 - DEBUG testThaliMobileNative: 'Server received (1166 bytes):'
,2017-07-14 11:30:16 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-14 11:30:16 - DEBUG testThaliMobileNative: 'Server received (2119 bytes):'
,2017-07-14 11:30:16 - DEBUG testThaliMobileNative: 'Server received (1166 bytes):'
,2017-07-14 11:30:16 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-14 11:30:16 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-14 11:30:16 - DEBUG testThaliMobileNative: 'Server received (2119 bytes):'
,2017-07-14 11:30:16 - DEBUG testThaliMobileNative: 'Server received (1166 bytes):'
,2017-07-14 11:30:16 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-14 11:30:16 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-14 11:30:16 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-14 11:30:16 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-14 11:30:16 - DEBUG testThaliMobileNative: 'Server received (6570 bytes):'
,2017-07-14 11:30:16 - DEBUG testThaliMobileNative: 'Server received (5120 bytes):'
,2017-07-14 11:30:16 - DEBUG testThaliMobileNative: 'Server received (3640 bytes):'
,2017-07-14 11:30:16 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-14 11:30:16 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
2017-07-14 11:30:16 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-14 11:30:16 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-14 11:30:16 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-14 11:30:16 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-14 11:30:16 - DEBUG testThaliMobileNative: 'Server received (46921 bytes):'
,2017-07-14 11:30:16 - DEBUG testThaliMobileNative: 'Server received all data: yIZGCzrWkTU7n43nHME5yiEE6rOLFZLb5Ql7YMUoWuLf5a7D2OvzqrSUhCARWKqEh9cew3n6bcH24CHEtQ2YEaFhNa6sT5KUmIkyqjlEGWypXYNCPx5u9n1ahQJcZWfe8FGvilh7ezKGEFE5ciak4XmC9DtFcxzCUWP922sgZxF51joIav,h0WQBtRavIy0IiWW1reZa7PHbZRZRmHfYpgZQ8WdQJaGdE0lOntrAGsaTosxyJZ6gnQ6vYy7WUHVxByU679NnBCQJ9rrnsB5kpeCLmU5xWWuzF3EEDQvH59aNeXicL2X3XBSmPZx1feaUX66PxBbtlN5rB2P2abqZHtXX3oOcBycRiZWEpyBGO22If6PH8hOcWaT0EvWNNLug94ojvXLyzjeF9iNkIcuViE3Xo2BlYHJ4t6PtyQNRJK1qOaoHSH2,scv9yZKjkEyzP22Ky5wBhdUszV8JRgGd4shd2w2Mthlv3v2kBZm0FI1J7ncsvbW9QMV1lC9VQc6Sr3l5D3PGGnP7NkvI6T42a5k5UjcKDkqW0qE6buzNyjqYvgVUke9WdzHLDQODt2dsQVnxcWzSLc1awkev7XjD1lacpKlQbN8s2EdPJAKjbjrL9IAaKK9xh3W5Qdyqo8qIL7TWhwfD7hR9vw0zDk0lRChWkLPJr8lKiXYxkRCa7ekmsEkCJ0JY,ThhfxRJhts8Jcdi2LIwctAv8iDAn1pkn7vJRAfLQrE3unx2P071SEvcCX7CHKFlsWbSZlTu5gD9Mvi5H0mzH40jdBhOtmLpd7oxp0BoKb0HSfa98ruGUccS5IO5MyxW9pqxFgxKBVZFYUI39aW2E2lEPXultgOsFpub5WV7t53bd6B6i9SY4GptCBfhTLerKbptFycBPUgAYqf3GtI6j2WGqVfS7Cbx2vc0kdAY8ma7mx8D0gG2cCI60li9l6kJB,8iXjyy4Dpm9hrdxnjaZY1JNNGhSWGqJhApN0XCgmg0WFfmTAFuY9kOUkftk9EvPUlH88yxgZcW8wNMBXvEFje3pEb8ja0YrignRUTr3Qykc23ygiHotJzJrDt64nnwpv3AMVHC4GKygllQiBsTVBtHOj6FkeR4MB0WJlDTmTyJAPp5u3C5Ca3iLJDg07lMtJogTkKLAELEsBGECISmChJITlWjvAGCttkeASRrfX8eLIIDvEyJWhqj9Zx6dQ8yhu,mX69rkioumDjJY8yxXu0W09aaoQwfxVeoTIiUeSxh2ErjgBI0agAMeY4dI0iWiJzfVIpo1lyQieP9H5RG6i0xoDeP9vFiyNgB4A6Sn0gqyBSLYtcy4FhoCpv513RrbNaLgyPu6VmXVFlWF1n26fLV0eLD4ypcVIjSGBl7ubAZJpkbQhZJBwa8lqVLCIfISfaEtzQM4CtbvfbK0DmLP83Y6s9Nqlnyw0KN9CmGHB1cdZ1BD7eBKeAiJLkRnFJQSBJ,jh1dKtKHmfSaRRUOURm2tn02lBJDhMPBww2q5P9sDtEdzZmp2SBWrETUrbS0hvH3cDGz0vIwo0UXMfYqBKZde6mVsz6sUAwAVt8XbaLVPYEhBKJdziOv5tRVWFx0fck16Alvu2pehawoSzJXVYrJBr5TObpLD3xEbF4JjBbZtWk6In2cjO55qIkTaLS7dEeFShvjMuD0xwsjIzTlsE4D77pO2rF45dOkwmcZNCHu7fmK1tJZBtFCHuTjn0wA0yfH,wYERvdZ4EscpbsOCwYrAiC1lSTBuY3T0PYZsF6EyUkshD16RnMRKXBkOWpOvP5OgJA4981NljUUGmEGvBQv4dmgVOIV29ryXL0f5hVv25BKDmbdGFrjGRcmcjVj4rBEUZjTwCSdgQnmXJpHOze3lBN0JiNy1C8E4fGQHlvbcyk38mZq21t9jXO05nVQwjh5QlGW23ECAxTDdXiGRTXi4tf4JrKZE4ZsxnA4DfT2xWK6KG6UKYxZGipZrwp4XrPTT,YtinvsQuzr8slnQjiilUsNYvEAGswH9oZeTLL2f3EEzOTnWQIJa2A62r1BoI05yiCvqj4KjrjWstg3fz6ZCT0AVQrqauVmdsxo1JHOliwat22eixeasB5LurA4LSxxf5yGPttkcLWF8V7D8RdqlicOoqJrxHQxbC1Uev8pZB7j70USnzno7zEH1O5RAumEYrvWem3ZNySTGVQKxrp3fa5gsX4G4BUrbY65xqhjqo7cBKslgxqm2MXmrY9hEIg3gN,nCQpvna0y3gcaInXxTyAWCLda48bYK7fSUjCykumj0cfb0DyYzH4F4DhmV8rawrUNMWVZpHIowo7LqytzPara1hUms3SLCtkmlQ3dpsIA7xIFH7UkHrIynwIeS5ALSq9zIwakLShCgDGUadPXG7cCISl8TG6oPd5rqLR2bh22bj99DW0oIjRPy4lqcNjBLTTN9SHzUZK0NgVqOnhwKgdqiLkxZyROYrIPf88BEsoPnffIUPXarVlVehJcyGr7jMe,JJNL3pQ64ytlCSogiPamtCxOysSf5m5QGQpR4eskTCqcv9gi624XLeH1tUMV9BrpoFTWWBCZ3c9UYjF8GAVMCLml8vYNzEIbzw9oHjSFN3K9kO1h6T91jR608b2CwBBOeNrUCfthNkzfKv0Ekp5IUATAHouunUGlDkdsCagse15gUbek164yQ7RuGAvcfCYWT6R2saRkpFYKuCPTHM3s55gTyrdcIFSpFY9eFCGcbORuUlO5P2x8t0tbdA2WTydi,H3NcTrz6WXLR4UI2A3WAsqOwXXFpcT5eKpT77oLjE2UJFV5L1ms60jErkUFmaVcl0JKblIWFPhH8BIcnudjxATmz2S7Nfx1KWHMc7Ps2ZwyQ5rXiTJy34vVS2i1rsqaTehhz66jgR2CbvKu7RbIY1Lhqve36EHYobyhWdb5nfl301FAPMRzao7THS4aQgTTbYse2HVrecdk9M9z1NwHFgoY9mMndLUpi2uX5fm6fAD8BlFm1rfD3eWg47hC8q8Eq,DEl00fcPhDDHsXPg4ggWbX7k18pmVxvZsMTjOsKb282o4rwIUi6gPvR81bs1E086oCuL4qOEVK3eN9sK2Q45DJLJA0rHPlYBPcDvQ71Um8wztKC8s4pE8PyTzv9mUwePPGIDtTbTgS6YU2QQBCHtmaIzinoAa49is06vNMM2tr95R1yuSDbiHpEsjxXMJl1nzoBnfPPN8uvyqLHsq7I8I2XT1JQWTDfzWowTJeZw32I4EbPS67AaUzviqOJ6SBhB,EQaY8aQeMmg1MayWkfDgoHbh4pEClT6l8z7uTie9Vv8L0oMD3k5eZijYp4iKFmlLWzdIF3c8BBYwwNe6reneDvTZIPIELZyO55Miz8QjAJS523kL93WzTL8FGxa2lHGPML3ZKh58uSvzwg8vE0VfQX7zTotqMFJ9xqlUPM2iIvSXQnb2mLVo9YsVVB7BVxbo4MnZybyC3DOctfIdSKgibG43PlwJxGoTxS2NYkblIm3vLHzaUCGM0gmbLRFxxIwj,3JMqIQ8Q16szMG3FjqUy0LZL6ktYPoZQ0yJOEU3fQwyilusspQzsab5lYs0s2IcoSqfoEE9kfyaWH5VME50OzIZPDdudj3ofWlwvs6cASfP8qpWktK9JzfwoGAevaQTFlC2IFKsX8xMYObAgPEHp3shFjTSzdphJb4XysasmbmjnW5fgYMjKXmHzEgzeBUiVX4NxtOIOCa91OiZXRcKXOOhSgommJmgJ9lADCQ2D9ttINJheNrbwc7xLvMBx8bNh,Ad5BJ0hQPlK8PwesIOPTMJ59RERTERbaCMadKl0pF5vdXhTGZYRMX1pmMdoGPpn4rMOE8oIpkVbseVoTMGr1lWzYLsjUnh4CrV8y2FiHgtTznmyJPzQY9xOuvrRNVgqtBm9dlMEuO6ADIIkFxKxakAeh9NcVszLivBBxDlmURGcRQJsvHrlwMJ7I33EdF4lnUeHPHdFxr9g470I4pjVgkSzoVzSmeT6Az8eB9MFSbjD9pCaz7RfzBmcIUrIYYiYb,B4IaZFxOLj1KzOTgBWeNsLxdsRShCvZT11ytrXMx5k7KotOXNnnJyOM0WrR35riz5yj2HrFGQRhqPjRVLLoUgIoNF9NgAHYpooqKmaUajKhkvA0Uz0tMTrK80qGjEfTOrwr8ESjnLOabZM8bSPRZMdYzSmZbLzQTE97mTd2sd8wocYfWNb4L1rLa3c3j61rmgDHQhC1zO4SOcPtEJdYMIdZqIUZ9S8r50UNQFdYaymRoL6iY5QhJcVrEyWXK4jdX,ASwKCQNHSdDN59JdtX03Zku2F0pIAJEBLX5s8plJHGUCjEgzFLCPrwQ73FVfExxi3DRXJybwG770BU1xCDSjDgh0eK4vjVDcHCgwX9A2nKov4JAevNecPVOzaG82I34pE9ifZiQj4bCvJ0N6DlB2WQNlamaZujWsOHsxsJ7ZJnkRdR5LHO11MGtEpf6cXH6VE6CAVUe9nB5p53qSJcn6HTAhxUxup2rz7sD03tIxKCHq3GgyD2mkWcM9mjEBynb9,QjQdnNGyzDtizc0iWPk5NMtP9cxWzwtK5S1CrfVj4oiGIOo4oTaXNhUul32A74S348Cqlo0qmwZepZD5n9OeB3BckvEP00JVoGZzNube5eaZ6CpaNFbmmhI3nr69WKEWRhRC3tN6DU93Uyb0QsA3uToyzqGzMN3GmGFJbVJZjEXQ0evgvcolwd3carnCXRtrMS4GwxrPcwKrfGDcYf3uB4CQGPqqp1zivtwFmZ5lzWtHFYEkPstk5mn75hXsWqXA,RA2jGdXg4akrNGbUnLErM5ZEq7efRMdJxGSAQYQPIj9DxRAicnfFIHdh7XcCAal7DWjGJxxHcxZ1vI9x2rd8q56IIA3DgavJBYtPy2aMsf5Ud3ALA9KpMs06fnoJ3skVADSDGK2OznZP9J890vsmcIpVqeJJiba7smJvZz4fUjuLRvuHFTunanr6AseZMv63XDM0TpxFfHoBJcmM3VSal0JXFwjUSzIYeFfoIumbsq3WtgbbobeYMaG0tgpRsad6,lVzsJIsItTg0qNZefwCXkeVmKTZjZG1azvlYvDHOT6cVbOvAoTmgOqdAp10FGwzzg6ugf1al7KuOqUCFc94yCo5zxI7B7STqq95iXZWJOPz4ThU73OYYxBcMn6ENiRCRC8kjPjIc2TkqesiCdejkyJ6DVCnLAciBhGz8hfdQXvNHDqIYrvdHXLqYqavo88Vh1hHcaXIyPzd9mFPiHIJfJMgjyw82kttJCvZlsa9IeLdzNfO97FsCpAbPrli3xlaZ,3jBUsEFzfNsWK1fhuUkl76fKR3lr3BDVu6Kz4VmR1sOkLbWfKpRIjWTFktjpqfmIXXnI0JyHwN2TUjtC1yzy8eYZ4b6f804Yju7LNf0hIXd29pAPsvU5906teCaJcajDx1NkKtPOzxTM7VszIyIvtstX7Hczt6V4FR0gzsWKKRrAUG6CHVINkTZSOGtICMkbVnJb9EXMdQd0iX3c0rbPviCrvDuUwNswC7NYzEZJulZTI0lMXEhYSRO72yTTc9bw,RShwsRqrRYfsH6GGVqO1EhyITkEdPp71VbMHI0PsMDT2FuqlvR4RxU85jS2w3BvedJY3Nm56j3pvWwdAM0MCStmMxa89IXoOtPc9OI8lDqj9gAttbCVWpQqPS6Q2VH3l1ypNHf2blUSMzq6sTRqRpt52aDWNFaUs9XFjNjRckiCUQ92aL8jb0u6eM4PMNmqoPhTzqhh4zS5iQKn9bnplwzSga6j2RPo70LzjkYE2HuT25SlbCawYOcHPk0QTlIiJ,TsB1xrbYid6LQrKLP3PYctKYxKJQ3oLWUoGEo3ot1uBXE8JCPHxixUQNqptCmpJiAVGY1V6sLgEmifR1BcgkMBawwtHxFmVivr9yZhSF2PXdNwUYOPmTyOONiHVDmdcRMZnu8M4dMjfoQFEnX1BwUeCfrYNVsnvbN5uXg4En6zUWOnS9zkRh1dQlEjiPy30eD7ajsWOGKN3hVHzkA3JKTAJcv3yXqsVOA96Hk4IYJ7z0xIjLKoYklGg6QfnSCpHn,kR2kYMkX1BhfURli1FgOuNuGItL1ya4bgAo2nAFPjngfVY9dOKe3HXmUr9O6dPa7toYm7AF285A7qZ6Ttwt1LGQTm15tGPzVYZZQ5x6C98YT3fkrnL5da1czjNdTSRhZlRBGiSKM7jVb14YgyCC5sJHjRMRTOW7eTAXKOSdZl2AqWqSSNrcCWxpPKbZ2KzM7S2ZaplvL5DhZm5d5zc34LnVgsN4Se74DZJIa8ioZpHLxTP7YrxCER9mV9QhTxttX,8O4mKWvR9hOaA4RxgBHDNF5XDIHI33DAfogm2qOpjFEJD4gBjx9il9rXl0JxUjSejxaNnfdAKAJNYM5rLHnO7JHGmzsvrWAfzfW2i0cCAfZWAIj0qlAGCHZkgvTTa0CwdXIv1G1U5IDYZ8iiaH0dcdEgGjRiSKtZYQPDptG8ueX1Kx4CwX8cs6OVPP2eAEMcynvBvt17iyCNgcHnmgnZgtXxthuwyfdMzmult1Bp6jE4PL7df5dltldq52c0bZPP,bCXd0AubsCO9NqJfkoIta98BNuaOiJWDX04pCv7M1klj6AxOlyNb7A8oIWnsyanSqteZTB2S54QC4rWpkAmzHdbDk8IMDAVT4tF8aqknjXYAF7RIteRVAFPn1sNIpDapYdWzEvKZEsGk9FMxKKtLaXMFhdUNozQQFwr1kHUgIv0LTYmm7Kd4L2lnYd7EKrOONvsgWgo2s97avcZdh4U02MRq67TSMFDosVQlGDieRjSYDHrMaND4M57RfSOri6zh,WWNxct2BTdWPamTX7FlI5Ok4P3r7QOZ0OSw3Jwf9zodhfiiB07fGJjnBTVK9RsBDx4YDqyyXhq4ApORyMDpa35ddT4Y9uk91GdSYp8DFe9jjyhsd7Dz1dD10Ywcuas5TR65Ka9UOOQlFn5cBG3DH6YBeTzsZmNKeS4Gk9kipzJcqz8zYyvhXSAGvbZUJ1FHanPXgGno2wAFeAR1I7SKpdbHxvKALBqOA4lnKNvD6zYs2XIWSRNG60jdHzKSW9Su8,bFP5iVu3tk48IMbBSpN19HJ9wL5BIl9V80PmWNJ3oh0oHGACOgrtxoX4nkB79mDe6AgeZlhXDrh07QQLm4gEtdyMU97E9yMZZTmY0rmJshYv5qEInVzgpVbeeGzkMrp7JrEelXI3cH8jkAtZydpwNUqqXu85VnOTBSFWiAltRwmVNSPlTANQmEQZ22BhLugkXT33FnhobxZKeNo8WdPibLd2EoohINwhf0UHZgwKuiIHcSOeBec4SFlJtREQYNDC,lqZQws6xstxSdArLYtM2e56D1QXHbxI0sA94yLyxrHCPjlhksmbrRqs0n8Ajt2MSukNqdz9KgJw6O8smK4QAGGUXB8D8ITRZ5XmYrwPP6a76ISzYGsaiIg9JjgmP8jaNu0xWkBOroWnIN55pUyh6eWO8tZbp3zJSfKPVJJLpebPAUIvVSeL7hNERiCPPXAtMTyR2GduP1C39pnIyC1NrzBq2E0d8V6ljKQaxT3TAUkWH6HpbS13vGsXKvazaZoqb,tiQxa00zPA6qq6HuvpmDDQBtov29ubMWCnR1TS8zKhlvKhsYsL23y5FJH6Po3lEFXyCi3Lj8fO7eMJWPUQzvVeIYyLTqIplR3S7YuqB3faf5kYJpMKFhbfYBXhMryB1MqOb2ps8VEmpNSHMn9H3pgCXLNbrtBI9j0FEBi3wQbTxSd3B5z4MpYrZUff9u8GZNphmyXa6pJC7LxjU7PDCQTAibxj0z6VEDlp51o3VhRomtAlo20mfNOySvtmInpehm,Mectj51bxMEi7SRH3i3rX29liDgMgxj000REP187tjvY9bN8LcrMN2iCv4wQjdt8Ye2Vrs4ldTQAJBzaNWeYPYSAqVcId0olz1AMHWh95zzAKBWvxLn9SObxbmZ37I8BrJ9nwvS1mEWynCSrWFv56XfLqSWNfxEWHPVfNAkv2ijat3RYwIoGaITAGxvDycFsondt113z9A96X7GApsoshZhISvx26OHp1JpV03kDgBZvIW7tpeDYKymBJXryQNvO,oMyNw2z7pf4DQMqz0oYZMCmdVSuna2KsvItG694VMjWMokGiT9VcTucm9f3gxRKZw2kV7kTf1ac8PCT6f1w8XrzUcekbtRloUHtYAMmrJ00wGxR4P7Rpk8YwNSyBhdBH3gvcIXbh07wSE4Mczs4MIV0QZNOYcqX7mhkfmaY9gBfXavAMxUUgUlCRQtYa5TGqLnqRQoYROIveajp68LnXJzfGLQJ0Qal71pQBRdxkqr56mllNHVlj8aVnroJG7Iwf,pjxxen90yGP06Zudp33j3dGLVLo5xRPhvmupFi7QlmxCjUS1GlcS1doEs9Iafl69xzCrphHu4ARDhTISJxotL9dWDQTlPIM8ZPvpQ4rqm6DjUVOLijsbCBhHKJvng8uhbegg5hMqzuiWANKeCiQHaWW7PTDIpWEWx4nUgW6wNgD0V7ckcrkVJDc8ejaA2Sznba9CjxFB6OJFaL3JYSoTSqYatsRykc7EO2aWPptdLIbC1vGXAjBFsFkyX4MOIxPM,SPqUDLOWvzJH9H0XjerUj2A1lFI1iH3wEGiHREtvnJnmci8iiCFIsoZIwalYHBA1aZTiAShd5XTONRwc79scB1IVWffjnuduHPifFcKQGCW2xgm7alVPFh0S3XYODR2oyizazo31ZLOxklQBtEm4wCZ0q3szfWDxRuprB4F1WRWa4cCTQIFNFjJOu42vRdtCk2EKwX8ibp4Zgt3pjypZ7IVwjumLWsOyTyWTu2zfwGixetzykbxs4iuNacjsFmA2,O3fpZjWsnyZCucXotMchKVzu46wFMWEUbrlAm0EPa0h503HswsaFxNJtfMdcIxe0Q8ueTMaCzOVczHM64cjQhGOvRxQH3d126ANWa9PcyA8sLsCFsyzuw33JAgOKYQ58hMLWC1VOPMl1fTXQuWux07Mt0Rcq9T3aDL41AzVVvhYfqUJM4L8RVsDyflmJZ8U98tmyNCMjwtSoVj7mCQrDbG36sAjZG88JMv0MC3b4V4oKxtXNchhsEPUQXBYsdcgi,kodhoOhG1b9txrpEodEd019tL3anKUoH7qIWlod8uhhTiaxLdlyLIw6bmnfEEZGOTCDcxliPjMSbaIwsgjwqOHLvuBtakOVBOkXktddzBdeFmx6Bp5HZpwxgFJJnf1qQRyl31clT24XaVxZGy5EcRv0TpEzGojsKzEdXIwhIW1ajGPXj3BD0uzCpiBHvls2zlPUt4tnyfwk4TbvZj9rbyJkPHjVl7JeZfCZP1m9qlOYCsOwJ9rTnwtixbCEJvwOJ,bUyWXHOQCy7xHIQxzS8QqaA4Ypc0OZzErqVk2s77vTWxXrHLa6i8fpotu4oEDSMqcen6ASO4NtLJYIm0guPPCB5VbNKrezwDCF1IjKLAKw1dJkrQq4CyKjZFL5kvCKGrKSDY9feCKCeThLXf7haUlf1KS9LRAAJgXVfFoornpj8Yi0UKBgpIGa37HBe23Qb3C3855O36zhz6Y9AT1b2kL2dUNiCxhob5D2qE9Eex0PSz1dyrNrU7x4ewUS5PzIaI,Apu0euMZvwPR5AOd1jqKQLxmwaBaG1n2NU2deFOQdex9RVcOfRT5sBjZTyP1b92Rimd1yXEvNduwq4TSqfnzOkvcskUSQld56878PAwR5khtOlCoRjKxdHq4q4E6iuCDz8v65TYdkSY04nU3j9UJEqO8V5YYrwAoSq4BuWl5zOsqwKmbzcLLvRK4V601hIypd2YWSZbjdjy61p6piVUXoao1c8nkycNkxOMvmTDddgrFQjmGAf2Ica3dWzqDAxzp,CND0P8QiGVTmD6tqYJRX1AZ81iIJPK4ZKm3VF5zymjsENmdDEhFPHTGZtZ7nBXb4BeNdcd7cshbqCzPESKXz15jKWIXJ5KFix505O18OcrKziLJd2Mx6C2Y0bGgzR8SRXxEA6nYKThVmL0PG9UX3srD21a32RIXz5FM0nMMtCUXBqcUkFAORdGti9ghWEYzRbhfBHEMPkgjXOnUfOcGAoe3JfVD1N0BF87j6YQGq88dulMrkfEA4biZRJUw6JE6k,f9cIR7936ZtVAF1Al8ZIauQa54DEY7pReeDWjf7L4w2z5FhVaDLdEMXygLWhQNhyPxyO6JQUI9xkodmoJ3sSziePljrZZtVukUXqDfHkTOyBsXyruN0sGxfJsGhrFkvgoLRwOYZ1YHIzHprFMumbPNzIWQxsAxePgDKD7E5sZBr83A9b0wd6fWugMPrgOZOIANWqnOiaMMd4gHObF0SyFUCPkswFyHdjwuLxnu3DH1v3Gepn04E9boQHrcBDIxdA,y1bYG3Zucm8kIVOJ5VIAn9tkzol1n69vleRtwKNj6Qdf9aAhxEyiKZi3dEkX245PmFxNlhz3IwRyzqAuD1s6ViA7UnH9RDEgoEOfHG00NA6mY7yrttob9QvwEd6ADO0inSEQCA2JQ4iT0hzaRWM20ieWBEKLbNiLOOxlPlS4BfuFRQTmGrH9p1FJlYBxBuQ2oxyAya5JAukkZIxFRKiPuAGblYTTMDbu3QLDnvjImIiqiYh82WTtj2zwYCCNLCVm,FISBIoQFgMP9nsoG3MWNwjs0jI0oAXWjuiskda9l1wooMgpgMiuFZmR72VGDIxQrowjbfsQghGtmL5xgeCHNDdgbeKQiU0c2goRkfZORdVqc362sMviDaJsgDwPyBRd9MGoU8mGJcUKeyzEBlnMxJRuwtsLgql7WsbdnXXTzmSj4CFWRtn8rnmaNCNd3rsCt9DYXh01C4vFXPEJXahTa1nPJ4Wa3L0ZXlsywOS1PkkeALZkFYPKd5CARAKK9Tygt,v6yHrrl9dfDrnc4DKXKNCHBOgu5l0zwCA9v1XG4sjJXSIH5bOLNWmMOykzOGsH1cmiAUHdtHAKDvLtILgoOmJxvubK7zlmDuBSBCBFwqBSQL7nEdT8C7YqCx6MqgYrwLBJxF4vzSwgEL3jOm58rGWiM63i8jV3cUr6Y4PHuwy8P9y0IuZHVRDg0RJjEtmNTqJjDnJDWzkYY6oHcSJNWS1jWLtfSDQCgDaPoOlVnFoD7USJJh3UrVl0Dc8ndTQNxQ,x91sIeRipcqTzfmWCyRR4VLjNkWk4sotkcecc61vdqgUObKLP9qZPfALiYPxq0aLlu4eU5vyDETUsITSXwBGOjknIXkMq29xYM4FoRe29qpd3WBUZrXF4zLUlnF920aE7QALHrDb5PM4zbcLgMvXTDjk3AQmPl002dca1ftjYaRpgpLDjeop2v328spSYXhiyR2DkPI8avKcKLtcm4UOekdCKz4Q6OiXVB6ewEDHXVOSQ3LyorhD7fBhgntcEqmb,HJIVyLKBl1Z6X3I0FilFNjOGtHcRhuhbTvZykVsHSdjtDKtZEmgw1r6jLq0SP1RPC3NVqNRqEn9uPoIkWy5Qbigyj0v8uGZjHJTLwupZCJkT3hOEmxI23o252wSx8iNRa6sKSfpzgnBZUJNaFfdx83uiXHI0gbuQaM9BZzNIqwvryGuyTJU58BSIT0OVTq5J4ZfojeUlkG09wm7FUcoPVetCPfWSK3YzR5IseyF5SWERXMlnvPtCjjgvu8gulG8O,BDkrMXdrePVH0rDOMQ5Znte5rscqe0VlL6B0Z8y2Tfg1SPGhbbSa12S57BKonf96wRSexCgpyZwigU77tpDrq8etul0pSf2Tww30Wy3NUh5qpbbhQxdTYUivpLlTM0fdn62Enq5E9ksM9XvbSdUDQOc1mJ7CGgqRpFH4Z77j1iPgcyrSMrTRK406wP9OhaAbw7Dr7qYCQDSHDJ0kAhUcNaXAjau94py5CAIoR7THn9nuCT8pMGQFvAvDzcrOWvp0,VNDxQVU1lA6rcBNMv2fMMJe32w1fO08u4mnUxm55tBNiQFMozqe6SwoWDVGCX0eZuRUYGHHhGbFOQklPoX5GaOtAFeY6nx23GbVoGhd9oRCPoWkBkO5jAml2vllWnWb4maycop18pYOghgT7VgPaYFvmOWMCFmLRBqDHtbxbYSEHJEBBPhghxfhQiKNl1FG1y7utthIL7u08tz7UruCCqU6jVXUM5Nl2dGCpZZkSETTBZpxOvycJGMK4bEpKebUd,mGvcU4dblIgazUZC2Ah8744KTAoGpw78MKAiyaRCOVgp4tOLBa44qBLX7aFF29JbB04l1WuFIM3mbyiuEMHKEQWf4sy9ctmRQpcuQH7J7NJ804RzGdUMgdEiwiOlF2cRa3uoFD5FsgWJH2GigIAEfgFO7dQIAOLHNR5Tdteze57BCDHeT3EbQ8NIMNmWTNgO0aFaxMwE2F7va8qrmc2duiae58u7MyANCTCCobkUBqIrs195dFq3R7Fk9WbqKIrS,5HSbmfCYK20r4SpAVCcb5OqFZV5GGt2rV69vi7cFcUYPCmIfJLFrA15tABCZyEm6UT1KjMcUbHrF5KjI3oLualXjNmEQ5jE1Tys5h8S4iYN1Svrh4jbqRukrQPT5WVua2PXwuqsn4Mj99jI4vrw6OJzMupWcy8M0B9UUMVlbY1lfwEh6Qbmtn9qYNs9LOXigLKt7pcft0YOegOqN4lzu0QksTC6AFlirWZ3zxtfn32JstwBQDn4C2wVVxXZgGgzb,1cwSUPNE7I8QRMOs8nR7PQRgYifO95UJpJKETXx0r5KAtdNOHW7XQab6UK51Tri46cBY2HjYRgSTguUEf0RdiBVbth0EvWr2ZCvsZYUbCix2hK53UAI3LYyUtQ49qA25rbMcirwjPt1N2XQB87zayLo8Ih027bC3BJRFkHTuydHxhCGM2VGkl9PNalQpJYybDDBETA4gnjGlgTs3e5LD6Ly5ktrMWD8Kcbw9ll5KgHGEM5E39EeNMyiZXUhmgT4f,O5XLNfmyypuDYNGnLkQxMYp2mi76GC4FLmjLCxWJshJRpU6OxtRHCc3Ht13KyRbRs3DV4m7EOLhT2sfhWgLxh55Aeu7X201Rw1T0axVqqB9JrhBwNadJRHbD3hYuOLurd1xVXLwlajjXgKIJW0gzwtU2P84csapBqXRkWTNXZWFqkXfeCSWQqRHL9wWkHqcvI5qXIEglx9gyDFcPiDlQenHH7ydgqzCW7zC2bqq6ZipOvkmFXgD54tdPTYxRN6O5,xp8aQkvxH3f61H0FLJYQBTd1NWVTJPl4Zp3mgpkCCK5F7wREM4PZpSKbhROf2A366pA8W2J7fy9JrcjIeTE07IjMruasefaqgQRgoXzINCXwW8UUjKt1X3I3zWFtjmloeqjWxzbj0cTFuz0XvIhYpfyRmk0djPi7aMmHctgwNu8BBlQIj9iEVGVNDwW1e1dJRIKWOb9rSc14VsJgyyn08yHLqCgXyXNzPppHl6fm8hfyB6fFDlQqzhXGi53bRgbT,xTAxjfXTO6o7dJEcTV02gxZFg28raGl58X5p643cT13a3u78cHHE53DzRFtsrSmIWj91aXYFtNCOB39yDaX0l1Y45xWWduDh0g5UnlILfxBZtnktjYgryaGl2bg0tqF06VF5empNTYeOarWXZ0YU3oWdDAk4SyJtO34BEata9y923HQeFW2Ot8XNWupEl8HZ8gQTn39WJMUAsd9T68P8lywbEybkj3V5xJy3HI3SK82901KExHJQbskgsBKDs2b1,3THF3iT6V4ZKZX4AVTxEja6GyZJWa39P69bH0vG6y7xE78XTj4wHj7hs0Hqv3q1vf1OfbYKkjZr8O5d4JvNyNhulTn4awfYBq7r2Dkr8sujZxw9tIBOF0UZdOYqsD2M7cvz0SqJzRpQ9XiVlJoGSOtB9CrskPKgmiPcbDUthA5hEnY4wT3WPeueGWyh1Xp5ic6lpegtVWpopx5pK3xynvOkNh2uzIWjqOROJQZzNKwDs4CBrsvyd5lK6YY0jV6v2,f3UZ4IuaYjOEJ0Hh6jCaLrHRFWqAZZXU1qQUBtkFs6fLiGZhljrZH5ULUAnaoYSeAa0fUXg7aRf1V7KcvmcZeRojXhteKoi2H26Eq8xzpQKhhQjdFHckicoitMoRRZNBBCRJgYmD1bTrY8XL3DO0o6X3jV0LcesWoHoOGKfc8VSQBpvtq0lgFEZj91SGshbbGy6PZT7732Nyvop4iZy79q4cZ9eCJUIkujq27D2XwOgL7MVp4EyZTv2cy3xN7BCh,VJWt1ypZPo3GJu3Sc8UaIUF7TsRNyrsZeLhnkZIcb9aWtMEKGtSS0zDyXWRssg8R1aNn5hNOUaj7hvH7wikDSju5XJj6sDNEBZ0jbEyBWqB3XZ1JOtmcyrbDEdeM6bTnJ94K8dh1KTz02dzpN7rAvH0f0AkzCxLGz6ZKGKsmHCRBjcmZ9bNseLrTONnaj1FuyOEqipb4X6mGnF0nnbHn8TpbuElJg2JD5jwFY33wLslx3zx3EhkvyA67ohX6MtIv,Ieg6z4Jqx2eJBkMZECh61Rh7l8hmlWF92ZOZqnHFx3PM1istYbRXdV2oxTxP92cB2TAhP8WGJ1esxgbF24aaJquAiJLsRMEisK6PbzvQykkLpC3Bcu9gykmF0wB2SRuZwWkd8kbXnubQA6v8gbgnn9aLLzvMUevcN3dgVfhnPMdFo17u5wqIxffpy6BlukDQZhMT164wH9Wb64REYjEmT0sImH9GmLyRtIdnE5PJDzJBWZrLMhwLYmoLyNyRkCPD,k4pmiDySpOszpHpZiOlAImBafLhviYTurOigGlhL7JSkxT9bf0MjFLf0ZGU7ENIwyMJrDqM1cKY4vRTiudaZglGOoMl4eJ56wQRqHv5rLVpetaAyYI0X7s3OnSCypM1wZIIR4lHSuDihB9smWXWiVzrNjqFEBcG25UII5aq11ZPz509DMLxkw2rMExFMnLhNDTvDbOp3Iowiq3LuRxHtbO4TueNENBfBerx2jbRblWnMQ9WcNbehxaJ0ZsvW8fiO,fpEaUUVgsfzJyXC9PXMFgoB6i8ka5Pz3OK7WmIWU6KLQ8qN277l78VEaqjHYcHfrSkNY8X1MPOB50XrpF10aYqtghGEk07JMOg0lbnPaUzFq43ZWITTZYaO1dcXsuvHLVfSQdZGugVBkQ6S8V6C4TK6rCQYo8FS0vpMHETnLIZq7wOwkANOZi7I5IQ7iHNCQNdsr1D6PDlmgkPiHPalkIsrXtpKfAId1gSnXTPqxVqI79DHqItg1zIZEqPlCvq2f,z0NZYDg2hrGN0UkG1zH8zvHeWQIgiHrU1mMs0s89xXMp3ycIenxSQ69LJd5vbe2ZOJ3baaJvFGVYROdS0qjbTprhRj9ur4jLv0AD7NQEzFFPq3SX8d0ewWdpph8yrpwQpqTFcD4SHMwgArRfifxJgvtynoNy9QLhFonz8tJsDVs0tiym8bqBF5uuVP5oyuAYSXfoIYwiGqoaECfrBxPVd3sfvavPGY4xH42j99eTmagm0JnQ2q7y1vt8kp5NCbdg,PfODw58KUYLNvMSM6YepUIQyoJbbrv03aJctXJZpSZZdeTl74wpNveSBLlSbXjrnAw1rC8hZ1lyuO16zzQ7fHGsywjeTOud0R8FuZEnuUHRRzBPOsmv0jFZfDno6YHGdKd8OXU2xwNJCF3auf65Vw4aFhYJWC41av5lUdTYUvdkOiIGtPQypmrvcaPLqedBfcsjaIZ1ZXf81cSpXEARnNKC5GsvWmmlK6KnUiASA91ymBnMZbxmo36GZDWBP9P9N,Izpl9dMBeYd685e1vBBOp8tkETU5HZI90pSH8hKgOTEldWS2QBIqMTitU2BXpsdS4arbjq6PvIAc4igrjTkqZicWT47csYWFACCaCqPLiY8UWyaEPgi6BAq9Hd90ZBldmk81l5LfoB8yJBX8Dk2kK47aiJkwbXeYUaHu0TvBYh6hiSMqgZUvu5MvCFv2yaRy4azFBwPheCURyNVNIKqKzTogCy6gtDVXofdF1xSizXdOuZXM3cMtza9Dv1e998YD,Ayc2xhxwRU7Uq4UUoLypVd0SSsgGZZyXhKGAmXhQf8i2Yq8zG8ftSZATOleBO6UH78AmK57dFODWgViugdGZ7mhQsTIg1Lnv6GZz5AwnBF1imEQQQkUnLK9laQuWnPXqyu0t4x9s0DaVCptyl1nOA2fM8b0plqZh7tQjel6YAwu3ilZu7ak1utGzE772JGS7U1P6cX0VSkGaHkWEgBWBIDWtz4wXHjTw3DUoHJIZZIYYU0UXjSZRVdleQl2L8Qd9,Ck7jI7oBZ82pkHRURFLdMKnE0le2AauXGIV887fK9qJVbu5FaojpwyAHTeLLwEmOWJotefzm6YGZdMPZphWM0GUT4K0KXqdBbD86Tbzv2PJyyI0Welm2y1Pm2GTTi43HewsvKKQECaWOOtn5uFsoqUmTqauqNk7YDSZ47oiNfyvhWbwLjj6ORk5yGNTzA23Hu4phU70jAXyNSJjUJfK4kLMZTZev3BgQ1yfiI24FIN3gpPLCsU85Bnw3NhqtW7Jq,8CC4qd1nKqjfj8P7x2bLijHCveDTft3asJHWpvC6oCgutvZqJ4DshzLIvWo6RDnrj4tbbuNXo9vd4OgTotfYwnP0fJxlQuT8kSP44rdiMrAZGqso7cfoO9JUbfLvjUpftgncOhR5NkZySmPsEYuPAlqWmlmGSEAoFkk9D5Flz167vV3nwRxAxrvfUYFALOClUa78tzoy3YKPlRP2HDucw3UcoRQgRQw5qSCHQHvnz8l5eTwLiViHJSOusS2MGlYE,27ldYd26GNjZCIrPlkGmiiuINjR0Ieir658114PLgH4DyVfvSlsJE5H9ihK1Hxu2KKL6XJNDSNyZ8BU0OCc0o4HswxeiUHRY5gYZ3Z9E6mZiSBeV0tyI4YGBiXmX6ruzZZ1Iyp3U0pSVaS0XU45AmhIkEMvW00RGP4IFesP6oamwS67JNybRpZYmGJNYfqhJ39oTzMZAVvOj98dMG9cU9xDnjh5VzSjIzZzRCIMPQ7geAKJKy36ssi6F9AaKGIw8,E6j3UEDOvjApq9LNwXyW9ICbGskt8Tm6uo3uorzQ9sQ7WEETF5U8NIKbhA1RFDqjR7EvP8XVRNPSz1ph99K8KqtvSibYhvJUAu790T7XyUrWMxrn5H5wq5PiHt3RzAacHtT4nUKTfyT2FM1JbExQjaEXXxEKI2eK35ct0INntlpEGpheXs6HJiRPNytdYAAMWbY5K1pH5bXAosXyAKWrBtvb9nofRQFMrT6tOWrBY7CqJm25yJ74slMwE7tQRXV7,weChD3yJnYSr7Hp0b9xNm8COhJHZCU2dcRKas0m2G3kFDOpsgFX2Wn7EhsgbhP8PTG7qE3j3zEYZqh4IsITbEFVXhb6LpgX6gfHCB2g0ftsPtiAHYc9DqWN6vgwjwPPn9x9vQtUIlA2L8QNLYNPlicX7po95Bd3QiuFtiG5z5GlL6JSbFMnLdCdXjaHDBWeCxkPQos35GlaBOU2cvEYthHtbUWDWGu2fHR2pB0UfLuDYLpk0W4m6WCKfsr23AK0A,aaSncj0OQmCBtlQIGewUuh2Pn7TCpgnqHZyNBGWeJa8FkkqFENcmW8pCVvR6jCfV1RnHXnZwFC4HUog2yVSLKsz1dS28KcKP4o4xTUgz5YQoq4q1nMXf2g4T4nOENwPPpnSYEiollAV1MoDUbn8KEiGEM3tGyjswp7hH8Fu2T0ozFDWtit3bhiTLGx1wWL2gDI92MHVWDB1ftaiN211FiY2wFzoP0YFKqVmrhnDoSV9IyuUPJMHLjMqIdHfPr9SP,vlpknUQFH0ACN9UUR0jCtJxWPPj8BJOeplhmalLfmhwQ9koWAxLWxc9hhFyiWwOWZVRionWcC0cIGXzTSBrN59SUn6m1tXmjzkxZ0RS7jNQU3Vc82GDRq75IxhErCKjTKg1uz9k1yO9SlgqGNExtZfG5qDmmR15YXD9wRO5d2POleK8ZyZfaOPylRKlwcj6ibh6hB5xrxuf0T7QxEybvm8YqE5XPL0xstYvdPrREED2JpCWcSZPUbnGtWt5t8JQ1,KJVlNu6qmehIaWIRLFG58oMEciTjKhnS8YawF1V5AbE6nk00GjUHV8h6cd9yrM0TSIfs5KIeOByPTSlFQyDvaU4rogWsTmtEN5so1PoOgsEqT6kbMLbe1s8UxmgvkNnW0GneFGFdpjG4cSB9qh1TzTWYDV4p3NjgB5aXIUpvhCzKfzZYtf0RZVUpVKKNcmHTbF0OJo1tkh9cNYRr60cXwlOgmC3pSeFJogO2PNJRg53mLMOoirEem09a2AaLm6eY,wwpqY8oLLBWs7q3siPMWkXjw6p09FRzb0QJ67alRSQGVYtAIBIpsUwtEs3rRyHq8Sb7r5i9HFmMKe3f83Gh2JVL6dELHTHlccso8miCAfU2BWqjlAOrLJiQtLGOBBCSz74KHsWN3RYVvfqYAbNiLHK2qEyAP2ZifOgXQcmB4C63OF5PiQNyK3XREzNSfN9MtKp1so6GSqlq84b6RKngdSlfpYF02Tgb4EcQ9vqSw0D8n1qtaiTOMuM5qk9DYG0Kt,gcbH87Fvzvofpr4Gavu0a08yYM5tnVyJQNCMooipeGn4VpBt0cQL32leps7vrtBNVk9a3FrRovGPT0VCkYNADeGRiAIc0JSuO0G1vLMHI76nq5l4tIPMMkwmTRZx7MzEVGnBMUoSFQgQvtNsdWmdZIm8pbxezUIxCg6BlyumjJjubJ5leQjt8v3q9XGlbkNRMPBMw2tvZJOwC6wzMD2HeYxakPSMR82xsd0oPoh659tdQBNiiefZAJ7cVVhD37WJ,uyVJYKkLIHuhMzSpbj59vMmW5GuhSG5spccuPep0iejnhHGZypVmQzaHVhPSy7QAZdkZBCxG5GffM7wGHMaSIl8teNjTMUshDK1aZMWND0JtcTc3XYa2w5kWwgjoTL13YzFYvkQckm8pgwfp4aN3te3Ls49hNGFbszlRN7dNRGU8AuyqxeeaRFCGfViTbw4nAGnbH6KoSOqtCVa3dv50II1iBjRH8dFh9nJAiudMHbrI261cFQWYAMtNR4ec7lkm,MCfZ6k6heNXjg5SsMo9c5SeYklyFISDdAwuvJPe1DBGihOrPR9jRGFe9BN1RAGSHU2OrHxJXK5pyX7N1eNcJtl2zpxasxWMNZ0psN3zPw821UzKJkxoTOdIEqAMQIGMOJqUCJkjWbiQrVKPGki3XDbCxfpvwknzt3ChcB4JmCDniXrU8q1ayfqktkRUq65nVyuHxV9a4pjAmXOU1L87mWImRyHonmpyxnFZjUvratK0h5kAgi4fSv4JXc254xE9Y,nwx8nFHXNFUTT6wnFGoZddll6FViZ6rzfEx1hytrdM82GTJ95M1Eem8s5JGR83uCTrCIflZx17amT6XGrZzRqDBtaFs2cGjxwN05nkyTpTSPzj8p54xRBcqc6khsSDcuLaVv3hdRyJZPAk4aOh7vshg0UfTmMPJfD7fHbU93MTVz186atFTRbmV4GI0040EXzt8QXX222EhYRZdzozaie0qzB59M3gFOFY3VqyP0UPnAVNxS4lMoLdhkVKFXTlYS,bkUu4d6nDAeY2Azng8w6kMSwHtlbhYcLSXUDePHeC8vQKGC10TCVyeaXF8UFfSMzLvKhmECM942YBPaHkm9SbgWpyLZDwOtqYTG1gQJxCAaPwTshoZ0hqgJtjFbcVJgb5mKyJXQpjFV6B9cRZHwafI84zQ5rflDm3XG788Vsa41Ik5si6LRSmNfkPxXGlvvhaMqb9OV5IL2YN4HTXGuTU4TPdm3Fx5ZtAryeqDAFK2LJl18cqvyHqeE9eYn0MZ3h,2VOdV415cMI4iZR30Q0Dg14x8r1tCWwsgP9IX4AgMHsViRzSC1fiBNUr7Xbbd4p444BC5rC3grqgWRvTFynM26TtVu99eLpIdRxNNUL8NPOSqbMmYTu8ByhrMTHO1VBcEVSKktIjyvE6Xe3zIcjuXY6aeIWHMFrdsOnPOt29uUdmakQE8AvkWpIf1H6saKBbuqWo2qK9NBLjAHHnNCdGOjMuRSK9eWzyXClE1E9usFXQPiBeqcn4XP8qdMZOZsyV,sSGZmPw1oXPb9G9f4Es0wW4o1ACx6pqhERiUfPaFh9oeZ2VFWtttp9xCtCuXNzexIJruoLHATP56IiVt8GRIUdaXorMHwhrjqVc5CkEg1KMRHCfCthHeHdQgFq7LX7dda6TstfvV4zgSe6ZrWF7PDDQT4ajaInh5x6rhOP9QvgxnlwysujFUBswsSJscligzDi5AxOs7ZrfP9h6t1pf0k1fugV39Xz5c0EYJJ95Ny6qFcOtLOcaIeDQqgdpHNBts,M3OA1YmxS6vIMlyU4gBsMHxWWjnOWwyGTXP0TxE2AodUHGuh6YssAhReXidG9ygXxJUv9LkFkre6fq7xUrEiRuMGkylKBj8mN3mq4ZKOlaxtcLYk48lQD4vqSojD1PmRSJRyYxlpYBGtX4zYqm6vCbm7VwcK7X0OYhDKHhscnLXiCJjd8Z9PtyQxJleiZ8GG4QzDxKZfHZlM5QVhYKUzR3CGFEt7WmEWDpHUXQOx6zHoDylQoy8f40tvshl7Qw0X,JEyDWaQY91A7RzTVEy1BiogTHPgs97ydmfJ5aqRZeZoX1GSL4HaxAPRERQ2eZ60DXPO1kHLcpq8YobPSE1vdukWkhiTvdmRaVxiNnbvS3b12cfZFtJwaBsCHftCIpBGSkiZtaoXvjmTSvpsyi2ZCAvDCGQqYpf89MRGrulNWEN7XLDbA0f6YpjEVii5Etu1RzEfzaWCsogd1OAmXxKC92a1rDSdpyROjLRXMayUJQxnAk4Cu93yjx0ywCdFUjhy4,5qSdIB2aMrXK5mkdyvTYMOPeP7azF4qFrQyBwUcgF20VR8IJTpc2rooXfZGKWc1jk1BbN28qkJ56F3Pb4UidiUYVZpEmBOAWEH0zA8A2EBczrhKJZ6M7zZI6VXimKDu1SKjkquFdSFwXebt1yc4QRp0kRwYGsN2nZFjUCeVghbguDVJPD4NaIJ3r7jXhWC6iNqzxGNOIBtzvdlNjZym8TnAio00WB07iH3tqj91YLgl5ACVTBo12IZNRvERHp1x1,xAeF5Rts5zQ2bGNMSK9gfBq8eBpWbQ8FAAfLdZ41beYPF6Z7ADb8IqB8BxFCwKFzEP7VR0CR7nQBnlfnUoJaRqvD8PENOMW9WUlbqpAKIhDvnA8BZPfej94DktJPC0v3LFb3jMsOhiAg27G3GiggCWx3FAXaQjnyIjmwnScKrA8LfguBQQ6bAnYkqsPkXQmqXIyyzstHvjWeojjgqFSr3aCtcek4QvxEIxtfmsWJ6fmgszyHVsB9ZRPGedUR22q0,MsHgoAFvaAl3pqrogzuVMvHFLS2nokkoDHdAcdc6OB6qf084l5DlB4t0IXLgR0RRcHRdlANNKvy470lsIBn3EPGgRyP5aBr9jF8V4rwXUwAZ7k9kprhGX0Ee3wcemiChkcJz6Sz4wpVcOtGJzGaTV28AvwJGAMm3N7dJERHuG1ShPtR3UBdxpdBBXyS1ubIrGYkJk5yfsHK1IJO58XDhuomWUgfacynDCseb9wN2Y4TOsPl1EHAfD6Y8PInijDse,s6ljLAJiyNv79FAtogf8jBPdzX4iwMnNo5cgUrBb4eC9qrHA1Kf1iFNlWjAULIzCCDAOwkVZ0IYLPtsQEiUZf92JqTxYxY7cQsfQHHZEz6mvK6UT83oc62yyeqOXvWTjsUK8znt1JI6GqEuG7AP5w0kZedWyp1eREfM5rCVzbeKQNyAk8c5UsJ3SN9CCULOhUTuFG9VjfGDh98o9aJ9rxi4GxHaddvLpwYSxn5X0hMcGBwgf6EYcvn6HN76QQ2Zy,2qMKDofiFB9JUoWRFHC5kBsVi4g1J0uwG5Sg0rp59Y1sMJg5ZO0Rzq4zoRWNzUQ78OhzrluButebOUnx2BV33xUW0x3VDRDDTueE4d1E4InEwg3atnn71oxWywckwaYb6WoQngVUUbBzEzxTWZO7fqojQDBTxcgA4Re7Sr1rKec1YTeiqYgqXkS7yZfHaXsfjbqaX5GT7WrFRYv8baRIincIieYsCkQ0V0IjYqmhUnjcSUlvYkhgJjdgovg4E2ZB,8fyx7QgYfqfLjAjLk0UJ5j0JK9PsjqxL5V3EUnpakFJ1ciEyHSSEGM5AEPAy3mS5OW7ishDlTxmTJxXnxwSdP97QXxg7IVy4jxkdvw2tag5MXdkRPLVQYLvITZuLXqgKUVOKqPlLeVZNGwMwvwVPBBoJyGHF7w7nvapb7bfScVYBTRGzAxy4NElolHOWHa8gs5D7FRCLmpwvtv41gZWxIhg8wUuHXa0stKr0UlbHiORGXh79fy8ukDphsYgNZuC4,Et107M3chVrlSxLXMJroLjwCzi58NwzzYj5YFnKccesEJvpPutecDdkBwACX48pEyqBju9nj01xCMcmOhWhlchI3MGxd9DS2yhkY6ah7PW7KQ7TjBQQcKK4K7vCJreLhTs7HpClEuvgZ3ED7LP1nusFJBVYJK6x6nytcnxPXO3EGekTBQtgwRc7jPIKh7Lh2refc8v9QzJX9z6q37GrDJdPzvl3BC3iEZVv5vb1KJrSEA9kH8x3CcoI9z34iNJSa,opzJtqww8FYk6V28D6YCJ9TcAMFr16W71oPPWgCpfaHkOOVtUkX5zyYIft9mUZ6nXiOF4ayitQdQpkJA03OIayX7XqOThiVjoedPmxnVOT7MjOWWGzRq2k01AxCqdyQv2xoaV2pefG4JFLERkwBixCTA1iC2GxEXGpr3ZbfvzIcsAPCoqMxrPe0GILZFxUbCsO5mvZM71BpiNlrwruRUOBwF2efwTrTc83zXnU3JpC6XspBr7iyi0pJUDzi0Qlkl,SxycjwkV4FElz7sRf8fB5EbYmQdTPAlncCHdfrZqRtgSggotHr4QikB1IAKDWCNSoblR4nqDz38u0PwaH8mD4gCwJVid27xJ0mjs6sojZZitMTkoFxRiMREI8IN0fvXblrsh6YX8tnfDt8S27BCr6v52bKHLytiN79Hgz1vwhM0jMO0mqxc1Kj6WlgmOdavR8UbzRRrtAykiBfrSinrtzmAJCsxn6hzyQkcNECMWqn85xiaizr5LoM1GuCGKWiq7,GGf1JFgC3lvOP4RNMcbpJjrwEUxa6dRDmeJK5Ds1MwBnaYu6UHtbZQl3qM1WZxY2ihd6w8l2iTYCSF2pvZHuumGucp5rNdjMbtStVKTAuPfhLKbgdVBZOWdFUAGbVjKj96G0w1bzV4lH62mLBDyNIozavpJQ53Jbj0FIIX5FIBhT9N9R75LMX1fKeDousNlqE6I7JJVxUHjZ4ABXN5zimvfaqdDwNuWcuHNMnaqEOTYerOsA4MaaJqY5JL4eI02q,5z3fG6yGyl438bFhzVJzGoMcfRwNmBJ7yiowuMPJmtJDmsEJWYsxmhOubbCbovxemDOmkjbMdvjVirwEMyz1DQM9Gz4YofSomB2qcFu64JecVzj2jsOGSxdA0mJ0zefkKV6eJtXQdS78Sn9CJ1VQ5jdoX3CYaDIE6XrO4OlVlm3GCd3i4tRBf4vZAIINsrkXTvnDrPzP2fxLYxZhzST9NMHQ9LwnydBhX5y8pWKbHMXiCp4On8D9Zn1Wa9jTRAf1,FKxwNumHjL3Cb7CYVH0QNZFdsjyrjnRVakJhPuFW9VdpI2GYS0h98ys4Q7okibqrKOw9bn7lx20k7lzgxyWRK2YxLTRABzAlxO9au7C97JxFDkDN1LKNJa0GfQT7JSQjBd2Ton52BS0ZwslyuIjRKFcHQgITXQyKenAfZCyROpcRRXl8KBwVcXdUmPtrOhMMCWYLidDfzBCFdZj60vMcyQR2N1BXLvgKKemFGTey5iBOhKHUcot6wuQOu7LmbyHm,KmdZgE0OXifHiX94AMcBjQLBizr9ZH7eSX9ISc4cTuqwG7GCyLHOZZbheaykC9rbO11rqOl14AsiMSLqGVnfJXfnBcV3sAzjRW2Jo4oG6rNuVYAbRsUMaMjJODVbv2WUJ0EeT1odCu4T7sl9dfcswFrDdps1nzRh5w6kZF1ruEfD2lWCleTmKiDWKYQ4xoNBdKQg1D6e8qLRX4zlDOOSXFx7eKlRq5ejqttE0FvBws8gQ32cKwiV2gqR1YtnCHmz,5aIWNOuxfVHwhkhmITSsiVERaRyMkssmF8QaJ1LZu2IUAgP33eZbwI9SHgttKWsp50bY1zcenGIQPSJVwcjXvDDR2V1cucyoYCD0J3irOtCcMiSbCq1rW9bF5FeQukFwNxhv0XqLQ66DBXGJEEjsAly9IlBdMYrAJiMD8PbrT9Hljc6GdjfSLvLrYATJ0A48WvhmI31xkrO1BuKHpj5N81wXuIp8Kdxtx8nrK99gKgZRw7vL0dHBGFfftUujBdJ4,v35aSoCrHxegQo9KkH2ZmLNDz3TQDno9OjL3EbkOmKydQVOKRZTMmq5wOI7W2od8eQQSzynM491yA1ZIXeBXOYfiwHYrxKxr6G4esXvErZSBWdCcJb8hLMPvtTku6jIcg65XtTKdjtHiTBuyIL8lsBcuxpFsQ7wa4AWOwCM84D4h0GbkYYGuZnUS9FgP1GEfI0umPZOBpl3hi51EnHwSzrJCXRfFCrdxGL6QyxFC5hI71PIorp3JSkAqz89qKsbr,2AenMFtx0lgkQs4Jfd5EWf3Tf6991DQOAi0iG3r55CpAbRBXbSk9LvSBPMiFf5d2fU85cyPaprY0SK3L3QJQPuTn7WY8qP3MMJGzcJ3BASN7lqFDdu0fNwRXwUYh1856mUeQHDnBLcKte5INNffIAIuA4uZw2X7btvbuLmQ6w1S3k3t1VvM2Y2LTsoWhghB4uOihZGbr6oF39VLorJdeiILXEbTAnVUx0LTa3EUynlfcl25sbFXPjTzChNPas6aN,M9LZf2VDko2J049GtlFMI55tq1s6d8MxvhLE5uhBFsJpnegRAmNzQipAWqtHA8slop8wNJtui49izHycR4qymvuD68Le0m5wtIRfAZ6kgK2V7w5Nk2fFkKIjPD2652hP6jTCFgrFg2SlCEkvqP5epTfU6tngjF4Hu5WtDnEkSKz0w3xNtM0Z2gwFjVwOCngSanqGCVm62To1hBHClQN80ebZDt8L7kSX35kGLfZeaNOPgocVKQE0Vp65GDfPWVJq,XHWhQF1W3NgPJmm3n4OLuj8cAf0HltpnrxV9sHGjlVdyyA56zA861QmGP289cIcTtlPPgTNbw0kkxa2jajj28LUgNuQwbrAXQcwbtAynyRDseiRp08i7TJBjVsG98WBvVgpBriGWrR784PILvYTq6YQp1aNgy9OE8zHscWiJoFQi705S2MK8MwVkrRJA2U14ZDheaURipVfD6atwAIxi8dFkqieWilu4hHdGB9CAZAMWZY5vIPVeUhKUFqtEkolO,jruwHKlFdo6EirhpyruLgb2loq1TD9NCEUThPrtjVzDT64APIaDR99G4NhfgL3Ffe7o6OaDkz23lSnith7X3HZLyJFPgtKtGRhnozTg7gI5QEDOCd38SGiHU6wR7w622TfwMXZZcztT0x7mmfSysoXKkd5h6schAJwLjPPIGdMJUW0tc01notLsbqDuImCWrK9PBA2vyrHEWcVarsRbCq4V1z0naogPq7DNT3JgnSop9RFzd9FobvRYC4xV7IEHV,EBZoNhkfjNQSj2W23NQd5sjBHHzz3l9xqw4c1ASZiVSdRzIJBoupg4vz8NCFYgL6Q4VGj9V53F3k9WGbdrOHzQh9AHlvq0JuYqa9l1plREgBNFrNDTkaQzZ875o8f2mgS66Dvv6fzbFnTsEdXn9NIacrVq71XYRFXmanwW01DOcGUAGuYL4d56qI9A1T6xVxJbjA4uiUVbj6VZkM1lh3uOUuZAYidVFRlxQaMxnoyBdK7DvUrtvshLERMubUWE5C,TwgE7X1N9zfqWRkMmQriznhU8ppznmSdLroGXgaMwZBpbZD4v3Rk3qYM6OB1U6tdmgEbZjP6Jc7T4QAXCJHAnh9EpsWV9X7bVXI52OItsdfHr7LxA7zGyLX16xRwKCeiMkAQgFPCqZfX4FztjLEOFGdadOqY4S2hVJRujA7gBvKmCijh5jNyoXMmnW4SrKMynPGU6o5BJ98teBefJdoVGQpSRmlov4jB4bTrLuvxPMFXYwMtCuida9cjjogLbJmx,B0LgWlKCNasaTa8enpyilTyFrnRCG23aLaIgnbwvYZu4Lg78omIBCfVDkRf6SSS91SGNb3WKF9eHy5t5SooGvmhdaNNiZSYWdMbmb7CgXR7SUfRIincMUpJ9h3y3FlPHcL1aloQ8IwIiaa8eb92wlHGE86LltJRmHJeaRVhjDS9nvbgHeWuJlaj1kJCn8DX943asQCi1lQB4idCuPGltE5zd6xtmJ2urk8xODTeKW8liaXP4SSgRuci5e8JfPspH,LAQ0lwdX7fSAoszmeBnq02bMEf4IU2FX35p8mjZWKJR0kXYlqvLEaZVdqqWuTK14b8lKGn2II6bTHtDAfKY0kIIt4cz4b7iFytHlmpVJYxFCQUTQ8LTuNXQGin79EeoZ0sbbXHWPBJKLukvL4qnR3MXplZhWCfiMdi2dutkzD220qiRk61H3zlnP825txr1kGZ9ddn2Y1Qse7Al9pVvX2HoMvOtbZp4K4lLc3AIeVDx1Zm6bDIsB1bUjaV3eC0vr,xAiP6WrS5lTAB90gS34lhU2eMvyrYnhktliMBgZxhxbYBsWyxxTugUpx5IWfcOidJn8eHGIjmk1bWYOY3wydlZP6ITn1qg3AppT88pOTyLCavVqqb8RPP7V4gDd9NF7oJjDJ7A0QEvm2Y8tX5bDf3xVZFzYYSdazx26s374AwSZXSmUBRJTXwjMok9VRMo6aYUO7qZakODioCGX8xYezwwWzEhigLb0ep31VmWBgBZOWmC8Y7tol2XZqCYU2xwq5,HrWXynZNhapNTMtqk582SNhi9dpDVxP74PSNC7PgY5RNVi0EFAvxTkoKsdsoY8zSxfceHR3zsq4MoAjylfNdiK0u9PvALKgUBUxDa5SaXr5rGz6x3whRHPaTcYSoyiBnfvwfhovquMNvqQn0ZKNfRVWBSNdH7NxDz9ewl5rfbHOsuw065mlyvnTCixm9Rnhs1i6Mvo6DMV1w9fpOtWEXqRTZXDXYE58f7vftbjQCNdlB74vZgzorHa9dELyjt8Lx,IyFrpvPPDwQyTqtmyHinjuBOF1VAQRvi5ZwZkT2eqA1tmp6FTRiBn7mJPvK395158DkwRWOXlOiJcCFHSd0CFHe6aqdYDfIYrba21YQQTfSqaHwiJYIGoWog9dp7pUxad3MoWH1K7xeFSYtj6hddOJO4aIYGjaG7rZC8rLf9ckSZWtyCuy7jPnYWGHFioiJeoUqe36QPI6TmNqzOpjhqDBBMzbOJQLTAVCHKebITOJeP1o0oHDV4YNSGHYWUKvqx,l2R4K1kBrTnPfZtdEwBBlSXkPUym7dR43KNv1BcGqoyU5JoZpGdhc4vbhqMls1TfnyyU0JlduGqSZgKyj6y3jD1sFAjIeyyBNa8onzzyPw2PQFIhaGLiOd49N7py7KfNfN9vqgsthTbJX5MxxL9pjPOK7gVfDgq3BLnj4oYvMfIlRzZS5OSFtENezNBj2t16cfRnYLhTSBVXNE3DamE7B408CIoEOVCuqHHgzt03dEn6AUYJc7xp5jpmyWIm9cxW,sELCtziGLOi9wbbRmNugPK2Wsd08mx4724v4PI6OXknQJ7C7lk9blMC7USibHNKtOuVRykvLHXnpwcs0VPp7OpRBDtQwUcRLgkUr5CrvFIDT7fqCl5jy60XNP4pvOWhqJP360m9htiZ4ew3KlQuVw9ysNo1GtGHDz1onb9ZOieSqiZIvxBszO4125nwFA5vaPxYSC2g6ASFLa3NeuD0EKBISnhLOsLbEpR8KokOeVT35iA7K1rKxAN1qOLhTufg0,eNVp4M0SIJEllBV44VuUciHX66Fu3HsoNJMznm42mGCpf6hROGsHHoeIi0OYJpvBlwoIRGXljLCcLVAM7qZ7c3Cx8bwH8qNC7ukmuf71hlSUZ8GmzLXh4RQ19Pbe9GmfXuTyakkgc7VTXijqFh80P812nJnVJnPH2K0Uj4TRJ781A2jWrkEppN7kUuuXrYhoeqRoNXrS8rc3Yzak1P6EcRn1SaYChDhj8fM9k3mHG6xfPvaRKsKxNePa6Kz46WMV,a7WPexykZ0BC0dM6BdqMJbxFdGVi10JqmpF86H6OyxVV9TjuyIPOjUL3lq5u8yxf0h3lwFX47EQNhY6j3S0sZRgBlEyY3zVmqeu4khBUY1sjxFiTEZaWLL1BH0xXTIdD4Uc3tJfJSD2oVOiortxxVCUDA7nCzep7dyqYZe0wR7Xj7dYNcxukQUXQ7ktnTrssniZYoFkHc8rRjHv0c4OskiK6FiWn7vKJEwGfPaXGTXewAkOJi9lgVdTIY1OAsh6d,wxWMppyosfhv0BXSyjpGi5UbPdcGiEvfeUkgUgc9MZKnoyKUvwiidaMXmPDoR2nQUP3aoUG2HNIGGTCNMrNKwWhxnt8go1ZuOI7HX7PWos8FNXsp80tawa03DGSCz1DmoYjCP6HY2qZqk5eFR8RrpKvSMZydJfTeyh24yH0UdruHzZr5k94l3UyycNU0UMEwH1bp8lOI7Wpa0qCUePCheEBr3qQRAMNtlv56pxiObWUxXYxEFk1AsUugxYt36RFt,wL7LBLO0l4OPhs6ZZoaE0i61uJvbmsAq6HeH6d0QPMH6iuaixBjhfKeuWDsJjIMwFpaRrTtApF7eLDPn7FXHD691zDwP50Pwf8CVGTKiMV9BlVLWoNz4vq2b2QfylS1SSK6E3Mw5irhFHvJPciu9dFf3R3jkqMHXQtHbJKgEj6bNK6nKG0EHGUGSvtXMU96IEx64UuxJ5fN2QAdjjdQbqToGs5YoHrenXBgPQacN6QdOBg5NT87zq53AuOzcwehr,q9Y2I9RifgoUgexrS1cPr1PskZSwBGN1ekNVVF8AplgFSxHvi6t5sHXqLO77jhH8ORam4Kn3z361abTOfN4NVIiQA2GG1KPDQKrJclwjpHco4f4khaFUlR3Ur0V79Qdq19dho1J24XqvvcWtvGCiIa7chDN1bcdLqYpvW8vomiuVVhsXCGjOyL0FjPmJhlvN5o1BLl8GLnj7hRQhLgNkHCrfXSkPCL6tFJogstL1R4odmUnwuALOacvoXIXHvNzQ,FaqUK3ozEraiU4jhGqvR8KX4Pq8SYyxKCa5qnFubTSsEwRsIhBosrJQDOW6cqYyUCuWBNd56ePvMiIGZXBskM8nyBDzyoCUdqjHI1Svkv7RgFXrh583DPPbJmHKy3FTy0m7G6diFIp7EiEPkml6pZviLm0RUq8DND6lK3M5PcYtizdlFAomVjsVSMzk65pHJAOmeV6xKVojdQqWrsZw3PfkBGO454D65XUenQ6DGgVqQzOhoMGzpXKH8Ed2G94sI,peFzEKOTOHqXQKCbzxPS4zeHWKNmHAIMR1iAcKdEDvxmvJtk5tqsVwnyuXZfsSRo67BZKQBVF40caeiLOxBW3G1GPpX6Ac4r03pMghyAE3c2G5M5Lj67FepjDVPKqnXwNqXBwaQzSThwsZktTq9qh1GkW4v3qKjMcpzps2XepjBDt4Q9DeE7kz1EHeez2Bq77LNq72dhjYiLKrBTQQTUUiJ2UE0JkBK9fM5UkfFWZSq3u3fol278eSgEBpzjNxdl,QX6fZ7rx47mBKqVxp2vU3CN3KLXPQjPuZ07GDJL6hNdZkxYUEbg8oslAN2wMhCSUHINHNhOFIbZxmyZAbsFgm9O0GvVfy2rQItItEun25HsbYcG1PQTNqXfzxBJqhCfLrGqUwliP1kAACYN61jJeKsWQlMWNmatL1JbmJIm5CGqwalAgEBe56F1z5EJ9yFst97Y4eatQCNBBAv67hVXbGBv9C1csqsHHnZYmDQweEciKTWHC9A0Md2wymmgTPmzV,KpoqEsf9o5eazPVmyxln3ZvkHXCnPcNyJCwQm0z2F9Sy4YqNgO2MmRIQhsQ65P35ZViDGuZOfjYFZXvN3Ledlxt4bsPI12AoDaV0ynPOWKU8ch1873nbN6DNmcr3u5jMhmqcmOkokQPCx1S787GQyiDkUQj1r4T4h8QuDARtak6QsTxWkM3GoqJdNJCGkuNErUTF0myBAKlkfb9sE8gpsVoBjjsAtCnDktrBMVP2hc7UiJkbACdtAZNtUgZu88Pr,3Hw5IuugIDS97eiuaO0UmXWMFELbLjy0aJ3omPSyMs6UOJ8IEOr1zQbIVvCHV45NZJCfzviWq5NS3OWI5lFfgR0E0VPOMxgYXYm01e73gAINcpopWaFTK6S8lsr3QkWnEL7VSQO0KCqH99RVNnX7WH9ZlPPrx0ZO7pOWEZW0jG1Sg2dL2E3pny1WVNerx06KMP0M57r0JdbWRxLc9DrMruhIh7zEbX3G94DddDblHACraEdn8H4QB10NBUCi4sJp,1gA9t32pjPa5cNStoZU7rc7EZ861vGKqDgh7BSGZ2bqhz6eGKwtvnd1IwHaPjK6x6hhdK3WApjfAvfmjQZ5jOcVAqXSL6mNtWFzsFITDsFTZtZLgwVoM98pz8Iqj7gd3gETW6mgPgvhrHsKaZet1aCWbbq7f5dELFwQKy3Kp8APCNSKOlaU7p9PgG6C1F9ikcDx6Ftu0rwZQIlJldRhuSCjNRl2Y25sSMDcitqfqUny1HZJUuCJJsgtNNWzVQnri,62CAygiNUGRZZoVOkxbOnKx4Uv64vNhNcS8RhRvY2BpnfF2fagOGAq6LrwtUExNx5KqlrPX7Wy5izxmCdknIbVRwgkfCulKyyZzgfGgBoXn9fz6YiHvIlDlJwtojH7VmI0oIA78c4F2IuqXyDUy2RkNb9X1cQFizccXRXCZYmWUxYRiW9n5OzoiOWL7i4QlSfLsfpPG9mDnwZrHluJpAoTUw1zCYonE34wD41Tr3n2smqMffmjuPx3mD4FrIq25m,MNwxvqEDIulylxmBv9ckxJyclOMj1AbecdXx85r4hR8WGj4Xv2hURCHZACRpo1RPtJQNckkgq381i7BjciKrSSMYuVLD1GHuxqKcImJq71nMea2Rj52Tng8dYByX8eaosn31rQo7exVBtRwl4lrGjgRlAtsK7tfX4pTG5urD9AUwKHBpwQ5OgDJb7kHlLQUTfukAawL9p3MM3OPWJFePOFVbkzOjxXudaZR3fbrFdFYzxQg8SkRe7txCU2RBEKAF,H5EkdjhrAzzVGW1qf9OQCr5ErAf9Ycisv5eHzkQPdbPi3HTTdO0Ntksv4PZbFfrELTWnia33HHbdCa4Zw0u9lMA3hUf63QDg6pfWrhyDv4VkfK2ntaKcZ9gKFnD3swwlzQeMhSDEtCx4a9spb9NtV8zlvdoiJltCNKXJBz3X4sfMSME4iUZqlGnydWVh3PJqXVB3o2DKuxPHSBde852SgGwwky2VHNK0CzvDGYc1jWaToUxrBR33JKCga9jT5pxn,BetjiZf7fL2FeAG6svETvHiSKCfvxzrS0X04JH5kd92Cy4oTfBIKeZRkXCZ1iYyioebqbQpR9ha17Jk86uqn0eeBO1Pbe9QWSEeMXT4WTbng6L9kdOFXsJs5IjtaDPGRhgtP1P8TzhP65eha7D0pJ4I63SkAiyaafNWo06LZYEuUgKJHV4lUVK2UosMpxLq2dcbfHi3T8vzXxEYQ8mSwJROrG4RqPNFS86TF5ECVSPK55oAAJJR765bWCY5jwZPz,9DFXK7xFwt79y18fj04zBZcRNwovX5I68dRtXOrfzFC2FQPY0YIMYit3QsKbPdNPKIF1VtnUD4eZicxgaybjFdv3gHswwOacwAXeZWw4mSPW17gd9OolO1bLwxEmSVPVXt7S5tuFKyGaKuqF0wF6k1bUCc1x4cJnd89U9KZ79AIfsraZmYkxE6LhJc2HET7V0Qv17n9rwFP2o5GcCRuAHUfTZINXO52pW2IJN2NCVxIoWrTKkiWD7N20jUu0ycVz,RRsFyRU2W5XVffCNQvUFuaZqqCj8wMGDU5zJWKvwEmHXQGknGrvIUTrZxljg4BlPSLTlsWD7UsY05QPdOmTqhPQR3KtsttQmswpuHvnLi8gujglPnUdSqc6plyXvbAUVbyXwUI300DqL8VQhGkZNbLLiM3SvLWKp6WumVlpZGOO21Mb9RapwXvxck4LStDFdqJOhEXEK94THx2WnHeZADWElMB6p8MputYxdZZbPKvHimJK3HoCWk8jNOiEZyhFA,0JdSoOjtbh92KZlVu1KfMnKoIv3dofahDJaO5QE9wuH0tsQsr61IXqp41pbu7Hn8kSyFczDsq0aaL9tZU57YlIvtUYa2UcUI0cZLCh4nh0ia1FcWwiGlXn6wAf8EFkxdCJlNxw10SJTy2DYxQB3eKdaKPadxXZTAUpPkbPITHLDdHtThZmyhzaHbRIDxarlmvjIvFWWkuXL1IDDI9cIXM6j69QSbb5yFVqvnlWwt6dhSGXGrAqCPkogskE6nuQIc,3NVmEWpFoTYa3AAGZZLwyxzZlsn5wpYH61Qb6BGdKpEgHE4BKfKVUJKyOKfC7UDWGjF5UvJpTwB1lcdz4ctCUuW3Naxuu9t73P5FOsqH86FxOez9fKxxHoqQFe5HbEebBgzr2K2UEq7o34dSGxdxqxJSAjdM7REtDrB65DeyQO967AyT9LuC9GqAxRCAtmu4CMMnrw4dFsiD9CPuT5wouddw12AOOx6jkzc3pcjqOLZe4740UKZiqTU5O5I5FZEg,huGCCW7dLzsgQSyD2kDJLSFNF0hHQCxSNbYCnJhZACesEnA2vkLI6jFxZ23DwoAjFzPUiEULBw6tS5aC6qSMxtXWpKDad3WTt2sgDXANPlyuVTSXw5LHgXevzDp1pajRNA6t7hgVyo1NFbsPb1EyWUR0oBIkJEyevqdzB52fzuhnBK9ufhrCP5JWb1sGtE3hB47HxKigzWI9xGUM8Vm4xm48ChsbtFGamqajFXURNvfP39RmbYLpcwQODUTTLnSL,vrSSXYNGNat26PtkU8oT47MFwm7Uj9mPXQtbInQ6VZFK4EoCTL7CBqRFbhJE73rttOEUoZKrvmc2fGZIjcPC9h1U9SnVIUJ76TCczkH0fOOr9RFYRl2HU2sV9kmuynNuuuhUG4ZoRGPW07lkQWVJZom0IZwikqeagWyYs6nc1Xez4RRN95djhcygSC9KE6W0vIuVt2j8XFJwzEAeKH8SWuditCffUQI2Ewjz2Fc70bw86W19qJxdcfdmtLgkkef2,uuPwMXbM0pmrjyQcQorXSauv1hoj7EE1PpntRwC4ZidR60omshfH8TMWUy30zYkBjnOnSLc6cALurMdHiWwaFmQtjsfi1RgFcaiLp3Sx06YVavEtUBgpZxFgxH7Lv9APkKxIfpXgeKb2TUAC3nu29LTSfrjOtnCGZipkRUBxlEfaTo3aJhipgsMXu64MUyO7cM6L37zzxdWJdMUS7DIQnZe1jfShK9lBHVDt2PpFASn2kdC6zhTsH3s1uqLJ0FuC,IYdowO5etjO9S3X9HBFu6BHALEKnB4ZRLaA8v9FLy9OXkYymvehX7N8GzrapLuuuaSy77YwSIcb1HC1i1koGwuCpMX5RTf3DqmbUe9oNLrFQvH5IAyA3EzIHzl8h4GczKbfYHNX1ZSNNddfHFUESdrmDYvwmQL7ZmGrWG55EXUlvbEOdfexCdBTNGhiFRvDoPV0Ujp9OpZmSxujq2KG9wyyWm18aT7Bg69PCG2nyCmCpX7uwexcM57nJWJ7jMXsW,Ypb3mDVGkrzwCuGZ8Mt9rU8eDcD4P8bnPKNGdiVoS2cBsG8mRaHnskh3azjE50SIgsIaUZKJB0uskxzHVuBfJHINTrR0hk95rmzaEhaTyQo5g1zOaJ1DoOEWvix2zv8mXr22LlhSh0oV6Plyk5gkLgiO8dK3dp8NF88nNO76JMyw8QlpTeJH2rd46XFsnXa2gLQrTBMn13g5xAmEFZE14ZuHPofTLgxDiwj3zGcjrY4K2CQgKjCx2lRxVqzBejb2,wp3CFio6eWV7KjXP64heFwpABWriICGgyHUJ71WZDZ3ObgIYfHWUKBcrB3OuHNerlVkyfQszWQrS6KJLyGX57106aShIQnCB9tThXnh0akd7w5eSK6VAqHTou5FEtcDr1pHNEDgLdokwYgrC8vRqoJfgOsqybPhtxSvmLrvsiYs98DeOFwSlw3UF4hYuEdCANXAqcCQB2hLhBvyQyCJ9b4HCfQTbeAUbtwZS56UM18JomowWpF90Iq7n0Z1v8226,9XPBaJXP0Pe6wX4Pl8cTSHBzdui2wIF20Zitr97T48aL5L4L0Igdvgh0C8wqoo4xIxcUNrGSnCXuNcnsu8FaI084SGzVmQnPUjiAgBYtLS1B3pzWKOvqSyiT4013QKLEXDEgCJa2o2u3cAZLhQ9jGXpYes5Vo8ePRG2yxbwpLmzQM0uUACIypRxRSyi8YprhIkq0LyZTborSY8sNhorUXp4m3svs1POjYQObYIXCR2RpXoNH83LQzGovWDm9PvdN,Eu30ByniMud2yHhixA1rIdNRtroJFSlkY6AwQG2mDW3nzf9rGrgAXR5imuStxkjxAJ88kfmhSKmRDyvz3LagpxnSqSTVnG0QvXJMG2sxtMCwP3T2wgaUbDmkrNrkdkiQFn0LVCtlrhXoalJIuaiNoDmAjvjdKO1DTe3WO3W7IK468bWwDcqMydFXcrfLvgqBs5B7WQpVy1q30KqHTo24JZSAYTKm21QNT9stGhti0zRHZpgcJK7JJzgcbw2f0cFM,5P18uN1ml3SLOmO4NmhIzZIUseKY4edVfeXRmAx1wnndAtHTUdzvajB4ky0VAhPfg0Trf7nHNETIUZoCLGNLeUYTMs1CltStQiXvoev9Qu6N9pAKGw1MfnUqpiSkWRX80BLbxgdD5RiOmmijpTveyBme5x8fW4kr1687b5Mxs0ZnX0BUh1s4rFkAhtbYOvuyKCeF6Z64tbLZMc8S88AlGoJ9zWjrC3OuRFiobCY4oGdGQ6y3tFJKyPNgxA65mMXh,EgEknUrCMBMJODLyRpzBThAuoGhHb4kwLPnPRp2R5c0kg0Njxm5SWbUnCkoN09nDKa3vai8D0eTl7WUKnoAalC2yHYaXmh2RAS3kS7TAZFCYABTwzWoj6L1VZVaJuRr1ZFRyY742gv1ZFcqUj3MyTwVpNSB4PZDNLDlouz6E7EhYha6vb5MxIfrThSHutrEdRCh9qiVqR45Z5bW6jxnbcRFdmeZk6oOf56JqC8ErSq11KUzvVm6nvKdGdIlYJGzQ,IrbRfjFv2b98d1Fo7QrcxwrJLckIUiz00qPsOpS45JkaEXhMtnaK2NNy09FPy0JG1cgNv827viDW1Eg90PIGNmLBHE6LcGQMnrc6JHPMdiqn5mdHOukrWyLKRIafNKwHGlP3gqciWccO0gFoKSbg8kCVtuznjUkx4NTcSzbglYQtOKmtJWYpizVAFaS8xWLn5XE79bd8sc51oUE2Th79fr0ZdAmnMWTwHezDjuTtIVwjfR03xRgA73lg24bwDfCm,lXqfmBRK0k2O90EmbhA1FdTW75eFSXLcF1rBanJdEEailmxW0GCkPa7dEApdA5o2PEud2wCvifiTORAIGOtp1oGvGPKcBqbBqgU0dKclirJi4JEfg5H8Cid74WLh0o6ESv86Ph7kxdx3bhrr0Bu7LyuddKUegEl3fwOg7WKBdHUSB2V66hoJmb7ukALdsk8puggBTZsUfmqiJDCpqAuJfhxownxApAXPBEIUtniR09Z2keAkHmPLnjOe12j38Rgb,ADwsIJvX4FqFbUOy9zXzXGPMrQc0ARjot8QIqmCkPFa5glJT0OSUB0YbL5dScuR8TfiM3cMmCUttyR12uE6g2rVY0Nz0gGSymBGRjpRMwR7B4o4tW41IJb9AZTfXYvhgxuNUVBLz5zyPuDL6S9BrXzOOqUO7xqh3Iai67ZAKkdDGSKouftI3rGWCa1b7274URH52hUi6DWEKAWtV8WKRkKqc16xO4g71FLGRc9Qe8Q9Y1VAXkTHjLAE0WYCg5fCu,WxJSCuVGrXVOHhuqyihteCbF6oQevSR7CFF4Z4TKybM6BfcP9zeItfrOtHSGxuKocuZmiPyPgsQi3VR41HRDsPRQbwCBrcgdSStjUnmVyrkmxXtdjWfvCbcFaVuDErdiOxslCg2DSzED0GyPZX1TKGszrLtBvblLLqtJkh5fxaFp43MPQVvb3jPRYNn9fJh6FET5oXRQMe4m6UAhJlXSV7jP2mYVlYkSeRZ21SvAdr8aARQwBGfFzXMKh2Pfc85D,KwKSbjzrTZyuXOanEMsDXghTlAl3LElJEk9GaEHpUY4CNzY0NjpLVQOxg5qrD4U2dy23zMVxAZOo1vToUPglpx9Fa7U29nStj5QR4yoTF79fCYVSJpcgu30D1UXMp0Cz1oISONwRv42e0KR9rG02bbpRJhHwpQOjtjjcqFPeDovImfAHdMsnHypdQa7kFTHTxaaFy4pIvfw5k9B6O9nM4xWM5ktpOtNTToMyNv3bZa3bZKSKYaYJl3gbi5KFwCAz,Gg6cKNbfJtV89yhnA6g9Uq5QA9BJL0gKUhWbtl4l38spQ7xyUaXDtRsa2ui20JaQMLEeEOKHMwuWiPIL8LGGjALm8BkijfGqA6PyBWPTVFN4lXEnW0XoWCro1QMcGiPqRkvm2CcH3covI7y1ePSXgNkYD9Jg6fIgCx57FBmpNXsPMSKcxp2w5sBkbXn4GA9WWFKptGfmOGrmkRPfdwpLdJfpQOkLSRDc3tDTSeKvNuFsQ4gve1Hnb3INfi2pFqLr,GsumsGelgRiLRxgqOKSqpMxbGyWrJdfQZ6h36kUu5BB6UODRZ1AjnkcAjDAEs4u9kEmg7yldicLgJG4m5rl5fH1PDJs2RGYhOFC5vUiQSRS0ABcfY1GmdMPam3u3kEVE8H77tVnM4ZooKvIFZX6Nh9GGqaWyVuqLlXu3j1Ct7RyXiLD07xrusQOWWbLrf59KuNXjXHpUGSfUrEB9bAat3ITPUytbc2jrMkak4uA0eFY5IpUcVQOoNaiE3qOn1IIZ,Uo3pv8VUJpEWH9KuX1bjddmc3hAwTjs6CWt96v8p5pel1wz9gXucYHQZlSUwX3IAeAN89RoGnmjGPrJPH1ai3RH4lpoxcG8WJ3jpNZIinGoP64IA46suAba7NFFcOgqgNC6ohrwxo3SXq0C0eU9Ct0JJQnDUems6AQ8qpJeXiBC2hhzevka2k9QaYztTO9u5VNqH7651KKIn5ziIttfXhLsqecTVy7NOF7DnQi2NyvLcuojcRMzknsHVHF8KPXh1,31VajqNQ2a29Q7HEvEXRpd1MY6X1UTQiAJwGxdfyq8wLqgykdBlRWIpskzsLGGKnil23agEq5tGJTbjbG6rPoNQko29Qc5ougzeL0G3llhOIiKCZVBjvUHVfq5khYr3XxohpqdGqVCrtR12O7m3FLRsQlVeX6mQN1JXel8hwt5s1wy7NDPZzslc1MNnmqsllFJlD4REYhh84MAmC7aJvrObxBTMmpiMeWE8LNu5hwmbwVDTP5KQ5whcERU6gAZsZ,JKB2DwJAi9rCIK8ZbUPGhMq8RtTpudtJOjVukk4cXle340cTGwyjZNNAa7djjrm3zEgSfDucgvuDeJUpwNGMpb5om5yztTEqHlYKRaw3lAZZbLxlOPy5RQJB9tBQaWsFHocBNwe4guSffjODfFlQFNXvCQOOk2pUZcmokBlZ0WVQtObM7jHtVrVDgXNbworJhQJb1pSHZQpoVtXhL4x65FRtJZjK52bKm8FM7akFicHTzwVXsAZKIex2sliIfMNp,C5vgHa5jzXWvlLQozXRcSpFPmuw4prNiuHbUFCAEARSb6MCjgjP1ILaeIjpnqEmfZYhVcGyCHBdDGHiW6xFyNcWilpDvs0z1A6GtJJnlCgkixToVzpoYRKDsSZvFjCBFxZsbB1wNfmxvTEoz6sCNMBhWnn9OqwVSewysKQ8u63IKO98yJDwuQg2A8A0X9h0yvJpBJmMeIBDpzs3q2ROskMJHZiYjPiUOYZ95ew9veJG3MezFTmmOwYBATn2Z9oxG,F5CdLfuunyYuTzBCHPNn19MCMX29C0Gh4rR4GUffSnLFOCOCdO4G3n0qgeiZ5oE3k0F4RN3ztAFINBnIsgwJtEiNIC8sLEXMFvLv2ZVs6S0IvRl8KF2YldePAPtzBT1OaIq2RUaVpP0Jeu8jDM2DX9aRhYGOcMtkREZ9O6vQgRbTl6Vvhzau9ELeDbASaVS5dpFjRvGo2WQOAfqqgqd0Gv0I4ttwAaxWJoWPdsT59JHVdpcoEGPm8GZIfpemWccB,gr60Tx1reNSaCANlFwxp2Sj1P5oWZZJyD9j4RgMnyXrh0jBD7CQMAetN002Y1yBOwe4N77x8Hq4nSAYYMITHtRLgy8wDQJzVJ1rxZVGy1FvV9oslD1mHc47pYBOacDCAEaJieqJiINZcG9nV1NGNT8xsgxL9JqGYfC3LsmUuAOMBa8rsF4WkmJfQpR3PErMEXKUL6m8N4vqLL7h9asbAeScs9yDJGUg8TkcWEqm2BkVzqBF5i14ATViEKbVqOLp4,bjEr2NuRWqRAV3QHJKD4TeQPldH36G60MqfCQiTIWQqfyXKPuKf0WA278eYeUYgv7cAqAgI3jieoIUdnPC6V8fc62q4fiNXGJLmZ8MiVOyVqvVWAqubzOaRzXle1qwJZ2jmEqiUXPNBkvlNoC3F6C4cUOKFhQrB0osbbKznVs3isUtVwODbA5P1aKVThrOLkpAxuVphLxfZu4BhULu1a8Uv6pcVcnP1MJ0ik2qXj4YOIbzrDy90erb1O1xzGSZmV,vU7UUUXWKHIq03ujnMw7dnHJmBYlOmQO7IHvREZD8ZRLfJ6eB4mhmohqCdQW1BlTTRuH32KbR4PgQ1CTcfbaaXnSdEmeLg5jaSsoW7oqKZyRwJ0ecUPP2jDXJX8EXDPsMQbFQXbbE1qwgzZvtXvlCsMJISweoMynjer0BI7qc4L2dEwfIOGn2DyKo5g0JbPJmYNHWNc253CgUVIb15bYTwaDSzxORXFgoqsjNHpNkjK4TmKiamoUa1YZfDO1Bgdd,DoayBX9zkv53n0ilcyqapsgYGaqAZVTvKl3nxmoggAiNLk7arRQYNwlLnqqO7IhFszwqaaoBkhCCmznSjwqzuKRPh5GeEkj15OrqbRkpVzMPoHRzg36fSG7JfB8958YKq3f55H2qj1H9To3wDeSh8Xf7Q3jRNAMtzZOeYYurL7LtDW99fLiCeqhxdxRnTUQhZxNNMe0TlK6TfPvIFBYFpwHbjAPClMQd5Xx6vSBb9suVx6uCEQqxU069Q2LD0q1B,5n0M5vm8zVRmCE3wR8yFSsfDOraaXTdFcSky0jk36TkOfLCQINiC7idyq2f8pCFAg2S6ZjEfQGZbMAeKMpKkVkjFZksYj2JoC4xyU6LpakDiPFmwCJuxI2qbeNvdcGb56Xj1aaOmlS2Ll4SmmnrBchF74boz6ygUJuSDIzxOBIkLlcX8L1stEbdZh1WBpZr3JSFv4AY18fUj4XFtvBnow2LIR0EJPYNvrpS1NquSNvmEoOClwH1cSDlJSbnHFCKz,ODfVE4uozu490iuEHt7Az2iecB7YQV4L4A1OldoBmQxHebSvPhFzc5JtUqFqfe9LM82MW17MJI5PnMFA8ejqnmGAACU6SedrbcouYSKorSZxlZ7eVGs0my6ZPiMEg38esdnxVq0aerzLn1i417OD2CwZ3ImEf281wuBAjcC6oFrk2acLu85JSLjjrawwD6GilYQFYe5rIfS5guwScUBlOZERnMyrMwYlCt8o6L3WTj3kQhbQ42fzTg6SI6H2MJUN,EkuVwteMnTPYBfUQkrGnAL8b3nr7jwzzbH5NNAoixqegFWjZtTM5ckJlaoiABdZB2OScA2z2TmvJNPpNnHxJsrkHW85BDD4UKc4dwv8oS33yQxCPXF7WFjDPtpoMMrcwPB4Pzv1ooiaeT6jYgZLKhPJT518YEN2mThBcrHHP4kzuriQ3i0TPZvgrrkljYWNv6PlTEmqYVboxtxrL5ReZ0I0ls62pWnA6KRG7B7omL9rtZLybtU60rR7fOpNxEwtd,PAHPUCXLlznjTLVP0M0dafOOKOsTWU6SKuAOT7Ed6nXMZgMgJCzqTqYtcgMOUUvbInXsdABXd5yqpkyQbDnnBadYuPCOFI6ZF08yJ4eLBIfTpOiNJk5YHpB48sVL9sd9BRnW4xfjzqISjy0CmusAOPS4RJCSVMsDzZsJtBuidqyTDp8XpDBABOyqmVEoqamACDjrTxxTt7TeMGjrhJm1T697KMgMONDvF6kRK0rnaLV6pgvlzi4mHwP3LBdRfwlo,5PTZxKf4pkL4XFCe7nmHaiz1rwbGDiaSzQSciHqVnNZpO73R9fUNNva1l97gvVOPOi6QY5QfczcJ7J3FKHybdWjDkrs04H2LAthPQMZgwPpKqV2WC7mw3DPFOC23jnXpPFlABoVM30jkPBLZRsRorekCYJIrQwCDLhGZgiW15qPAbiBN9wT15jBJEWNoHEtkYVjAJdlhjI4NiLNoH33CpeOedZtVoBOGDNn98Z3vMPAKuBSWyiCvByvZ8joBdBQ5,2RCQvRj2NifZMNp9ZbaDs37lJV3QyY9E03MytGsdlSDnwsjrVN0XZB6IuKHDDZDgjnIutMPe4kz0jQdGJjW1icq65TrOHi3r3Wg8VZmT7ygjmIcF8KgSvdrZT7u9P7Dc3W00oxtsqhOJct1SRz8NtsJJtr9CD7jkz2AU2nq8EZ9kCgEDR6rM9LU1b4AeIvMlWvENuj2tTzeUUEUyaxytS5S5w1JYpMs7OHtcUao8T2jU2PdWYeWblMPI3gLy1sNF,QqAC6q0AfHExzhyzwi3jYepqyXBVIcaBI5LFzK7dSCDnWnCpjLiYIXfaaGg4IpXEMPHzRLSilY8dauXBTOGZheLiiFqTK9TR9sDJInEgp8k98WiJoGUMxEw1w9HBOFi7O6wCAFomHLHzW1WLxN2GC9EeLKyfDutu4FHSEfJ5spA607AtTTy1klWYIIVZLJ3mqqyI8qZCdRLQAGesBhtXTCXKO44ny5K4Qpa6vNFTLRxOuTTIxH1yyaUONPamBT6b,XClWWlGfeckAHfpjWnNhTO5ItW7x3BFOAbRMcRLBWkpHUPt25S2cxU0pCivcG7WIGXimdXVX016DPBP2RDzQ1FfOqLGavwKkyWVyp1etLwdXCG0InQLdhdb15HtDvAc5iA3rGNUBMxUo1WtuAvPrlNcO9xLQN36HLShjECDS4zeyceanbIc4GhACjkfVe3mveGV8ZjbDHSCskRdU3eYFQqyYMbdrNZRU3xCCS7AJoWdaZbDva9Ry28rq87horgup,ldwSBt6bRiDKUXnRp2zqmvlEi0Kj7F6bknFcdkxDcr6phjO0BVSQRfUpgKVLC5NynvbQBwRYDgjlh0J8KeNlYrE6woI5XfJeAaG72Q2nivBlAzn0kMB3dBBMD8k5iqpFIaRgBuQO8SF4S4aTyHaEcESKja4WN2P4IUwJYA7BJrdrS2qVdt7x1SQsDiipO1BOFkqCH3NiqOMsIwW2ev1PffJZfeQls1piZJa358Z1wIDOEyvZsJQrDTnnMjIQIG5X,TiZJ0Ea2Ldj21KOLrVbQP6dtdS4EC5N3jlWUDYfoMz1iYqTlNhpqO5yn48yjQWVyip4syZ2ECM2lUwppx6BakOEYC3UYrOA6vx5AJ5LShalYLYDvmvq5RCYIrV5xFZs9hnINFLFm969NBqtQ20YFlthjz8P5e8sJeeNV5OcHGH8HXHbby9woagOjEFqNwzdC0SzZwT5Jr1XPszkRHnCD19OdFku0dEMD8E7eL04eJPwwRTtzk6hOnjeUFUxyJ4hv,h4o3cbDVXTAD0jO0A9SUz3jhK4C5obAwsRSblodDkPcw2XhUyhop9imr7olO7gzqC9HotnC99vY0rh0DVuzETuS5fW4pxrMyAU5dTJ5VyKIfCLQkSd0O93J5yXWXtHqln8zzY0mzJnzigC67SszkbHEPr3NTbQMD6enGd2qQIQmZ9X4mZkP3TG5E1OTwLXCWIY8h8lLX01PtAdeHy2FdgpdiKF5G2iE7BICtdqYXg3ZZ0fr6KCfK3MU2qJAH4PMf,C0XqpvN69kmElbIuyP6mIstuf01pv0XSSLmN6uYOuNI5oT9XjUfEfKBscRCQGR7K3RPVdeBvBAjDLiKKsytUKofhB5uHTHZwLfMQ7Tr72qysRHYWYK1NBeLeuEsymEOzXNDkPNNHI8UBc5S5kiUH2uAAD1qf0teQ1Q935BlhGNdwuCNVoZM7QtR9cj0USyF0Jn7JMSpfT8sD0QIImU63nl3zUjJBlVu1IO0UWKubThe4NTyhr7vmLHJX9cDfsVN9,AZxY7EOvUHWVJZARHW2Q3yJznQnTK7dGYQmFBIAFrNydTmTPvXpKowf6zORK4bnXWD0IclinuzooZOppmycTjw1IEvWgSuvjDlb4mczE5mcZeEgPEC5QUyVcvaq3Sx6OdAjBHiomnxe53k4KuOlBf9igIlOchy45KSSASHGhPyrMxbPeFIgXAetDvtNzCvvBfs5hiPkVfZWnAtP4hstCzm0hFqBqPiNzzLu9us6MhxrBbYRBSm9gaJsEuqlLzOJB,ncbMYJ2ZbbDL2pZ3YgjPNa1VMoO3Oe6c2oOlQxqSk7CuQMYJijGUJNWUfakm0D7iB2DntSbFttWfmjBjoNslYlr1XWRKAIuAGP8631ks2NOjf0U99KKtwxzTySXmTiQW2DJWEwb5QWr1S25kdrtCX3Ix16sQYZaxgMT0XCAl4azyAsIdxMnjQWoRQzt4CVGUcrXPrTFo5s5I74q54DmDfA1NTEd29ssU2E2RmNtNHswTDliu4a4ChphWNmWcxIC7,LbtrTdWdMLmQ7B53H68E4jNfv3Rfmmys3djIMaqpYJ5HJ7wPpMhgPU5JuGW34lhSsNMUWbW0BnEQtLHOhGkydzuxiChjNZMY0IP7xjxTW7ew6ifLBrcaYmJvId6aYUrFITOfaHsl23kNeoI6FXK6XONLIZtGua9b0xhsxfOjhdNficUlpwYIhJ5GpNLWmXgcPctQSVCafaXYQQbcwnTZgTlFNqUnGocLgoL661UsoIP3gKnnrRSdRjt8kPsytUxY,1IPcN3WQW50siQb7BLdY7Le54pe0jAxoGgjBEBv7NZjJKvjPnLEQbXjrvOOIFttRVkm4wg5O71LHXe9yLn6rPhFR4AlU54ILj10HkkkeqxlXDs3QfPYKaNjsCZVh5gTU89xfDr3igibVCOgVvYPAZUQwYvfpJA70BXr4jqe2ailNUZd2aU8L4wgskk3QhAGbYxy3QpLe3VeHmjGVHjC1d9HlUfjozc69jUFJmocwPOBZWWd1inKROusp2dvfp28E,GMDsUIZgmo6TXRjxBPVYWyXwO74ndQeN9emGciZjfohOtuTke6LI8D5jtkdWk7hRdgEKL8QmfTwTzeTgxBI3Uj36Cj02raWawsZpgrqkcE7oIcpk7shIsuw7IXIx18uwFS31QNgc2FBt3M86TkKgRM1OkYRXpt7PGb09TVLeVzroUXxgE98GXsRjN7y3KvaVuJ4jsp33gGWFbgn8mACsehl5e5FPgcksVQfqadtBfCmfQEYnPdjWQzbYfr7AoydB,jouWJ4GdlKjItGOTqYZSWQxPgjPUZADqAj3Mr5GLrlpL1CkLnyFdWznNPDr83aBu5piaqyDSnsWzGfUjPBKgXYF9XNiWvN9reU6NRPvNxjMx0F6JgxNTOuCdl512ZfpWp7XgE2oD6W5zn4IJETWTw5ZQRW7QpevnwXgOBtAsJL4T1c1xrboABVENEEBYtqlmhIa6XfUiulY4Cxh4HhcDuSmrsvf1O543ZHFSF2C0WqVF5pWUnwmZ2c9ChTGjvdhw,QT3MTf7a0kCZhfEUxwFW1opWkXKCEkTfDeemSBwQ9yaDjKojZ2uLIImCSmApyesphWRveEEyxZxqK6zvU0aFF8mnRWLiHxTevGLWw1skt8OtsfV8iBlWUsCQMnGtdAMU62uPA5kAZnNpqLlB1QJzr9wPRAZqXJ45RTOPqupwVrbkYeBykvAxZbfzcn8gplDCVjZVnGnLdUI3n60LwzWGLhFraYMWBrqjGNq7eLSvvVrtEpdFZlEpOl50i6nsteT5,mGbUGYOMOuVjC8hMjDaGTutqhikUuXg7DmXcjyCzhACDGyiAe5LVLMoxaysSzZphGBejnsQ7IfLNAHL6QE0th9QiBIet8hjMN0RNT2bRrPApG6YhRo4uXNFBUyfwYxLUkGBqDkzzR6jt2oCtuRoVDtJogv3dMEtizjyHKgqZC3bEGpWUy46hcoAOu8VZGrZwefDW5wNue3J69rzZr0DCSGgnVgNtYAfmowrrhUGWGOyoniyQ5A5BmSkaXbGMJEEu,AaaWi1UAOTNn2doXXjJRtWoq2L02lTjrGDdYoMMeS1eI4EmuELTLAhCPpOHJn6xOprlwFGyDNkzl2eCdFdenem58iWl65RCfb9juJ3LpumRF9OwoO9lbrQ1vv04rmUf923C0DhlhLomPDyuBblnY2Or3rooBgn67AuvQGMqKhzCjFpZb2l2VG8gtrdd5iQq22hhTiPXsQqpevS3s94uFssN6Q1y8A3djRSuXomuNnpwounHe4zy8YmdEF1H6jSiT,gkCcxWflnTw72Z71VYA0nDnSIi7Tf6QS1jHVc4dVQUE7TTM4s4I8CbkBII6BpgSIEBQ9kwMmogXmfvE8CC5h57iuOZgOmYCTKMIQUeztT9PLIv8PIUzzmrzwqjbsoksJZnIrXUXOAo1qG5oxkkIsivay6XE3bMQxpuBGIB60cVnaOx18mnMCHT6k5KoncOgesOOENeE7Ew4q7mFrldzlfcRYCAVq2tUXQB1vHfyOOi1VHmSfvZ8uw7XblbkdNAgR,eLtdM1qdiRJZG3aqxMUhgm60VIqPtrKgU5Hi2Zv8UKDJ7qnIGPrCShPZu7GUT0EgQ5zjZgU0x4cKHJ20Orhmnf6Fxi6PiEieqKSlfmez0YG49NnmeNpfyzH5kr9WSS53PRrSsPGjWioBst4V1mvv4ZNWwOJyM8nlEa9HdKMchtTmshg0GKD6ZbOUH9c3mGMPlLb5AyMLZjFYCP7UpPqi8zfw3DxxBGScBNpvQHs7m4beAA49eXeAnPeprLI1bBlV,migExmY9ag8zfhCXvERWwkJna2LpsLIGbRuGWkZ7IkVSE0nm8a7PM6ApFu2BRpzXgSyNus0N55iBs0FHa2LwdfoEHHvdxNibtFQy5BAZCFHLDZ6BwPDFdIuWFxfSWc0FngHOTMabQiekUCtZrkOKnbfbd3jjdHG91hFqclRItYbxiaBROS9Uckflw8aTnWNFDPHu0UloP0bvORmNVsSnr3nR3RCe7uh0RppsLEgJDKphgHT3SDG5lzBIqJLxWDnQ,ok0cr3zryUEnalLIm0FIPrVcOgBU69SEm0XfTlaguzUMfx2cqUG7KoadjrzLNzE3zyx2OAmxQv6Df7Snw3QBbV6Rw3RlXG8GzJoezb7PUknSfUqa5wsF3bzSQsGNhrTzBqLX3fCg2zOtKlP4Ntvx47LV0nLSsPYlsQOie1872OoiGjS8CfI4cxTgXnbwSB6b9wLQg4Y3X0UPF3Ows83uuZ2Ok6vjEQiwbvjJMFBAwkldqH1uwXeEbjkwpJR254Sy,lldEWBGKuJODUiMA9CEqfkJDqTDC9cHuxluVmotsBA3RWHixGEzOXM1FwtZGHe17YdkvIrWlVrxFuyDWWByK7mDH3itVKnNiZcBPE95v7WGIT4vgfanMgxRh6dACOTghT5lqxzqEAKzmmbPu7vFBJZOe4ufVZ6FpIiIvQiPdzn6pRr81WrWpjq7WuQK7qKlvmvfwBQkWje8MOwDUQhVULj1eMQ2z0nJwIEcEhMK1ZYNUasjpdnig5IchyXgKZJIn,D5bPVOUY8gezC7j84XuPCNgWjp5zAZiYrKXiT1MtTof9cjLGMMjat9NTYODNcROOPRE7uEz9HCb4KubwDUWFqX8H4ypJkNrufYef3TYjpUBCls2h01xBnaCqkbl7kQh4mCbQlqlhefI8wTKjcC48yVlXPz3nBX2seTKw6oJwBpDjSbP7oBZNiJ3ONSThegQAUDSFKskpwSLDlotnQjcvkcjIgb1BBk4iv4uZO8JRNCe7P33kXH2Mqkep8hIH1CSi,rajL7ZoraHAzjwxcky6JY5xscPY7gIgylAQJoR54G7BVOnpQoTyLvNInA5RX7QY0re9NRdDDt2WMa9rkzf0iKOXahVzGLIewkMVD4RIOlOXPF1dWqbK3vChC2aIeQu2qU0roM0xYRhgKXq74nYD6IyCGQ3ctBYj46EUcqIIagLwCyNecRJUsD7lXq3DHM1kUMSEo1htmqJA1mxqgdkpvw93WmJa3yjG6vVS7L4qCVEpBxuRRbecLVwiXfixxY0fM,HtrBAyYWsDb7bksRiD0gmoN9au8cmDHAigi2xbuWtMpA7BAn1Lxc7BJb50H4YxdHXbuxJBlZ5emqWDUaLnfuD6b0PA6ZmK2acjv1fFcuQlnKV1wc9DymqNFArKsFNkhlNNvb8L6lmrUio8vPrPHEiXLMdZxnoINLYbcDKMMN1ZjOv8kX7KpKejXPBNhZdTjqhl6w10J2I1KRN4Sng4ahZbQBiw16uufE55gJ7RfKdPdosvSNIk8JKuCRGggmy5pX,lPipmJDvWJWYYCXJ2fMY6rcNbLVNCyLOVQMByMhjiLIms5aiLl8FaCVy3FgMtmlL71NTTFc5dmL0CmFxxB1VP4hYnhG5DfkGEJzlvm5ny6AVX52zhGGrLnpgBGJpNOINyNtsKDNaAQVnMmdH483QXMvxAQkBfdAOmJcYk1ag3xAIBN8L9eDuePDy29iBovOerrmg459mll2R7gWhhdGaADVLyUIBLrByz5psBt3w6Jmt6D9i8GDmgUfpbbPFrWrT,uhgbCP8YvjL7mGOdpcGrw1dFnIOnUZJjCan5yTxXfjefgFJICqvxsPWeBebUerBJy0hoNkDoZHawc8txWMFUZsnGHVsiZuUgjnjJYTSjUkL6p2wojMCgMVtFq2sD2rsHEjQj0ndatFzQ2MDZSZXdixj53lvbXly75mH1spyC1Mp6PBk3IeRL9nVCx0WLmtdJ3ouZqHn3aEwtVuCoiEBYkYk4Gevp9bqCnm8gjRbzW7dxlXyDzfHScZi8fbeglNeV,RB0KzhKiurPcwa0B3fa2TjqMluShBFgElPx0wkCjMP5JqRABWFEcXOssxWofaQtFE2RhERPIHgzQKm01wH9biGCbxrJoBblxh34NjpkViXPpCGz5SS1eDRLuycgbJqL29E50UkXwh115Dm8OViLrZfQsdY3XT02yg8W9aj5CbEDBzajnmSTMJReC2tfxG7zR5x9N77m4U0M5pyg4lZc18wGibUlH7o8W8QQEHL8PHnrD9BwufFXygs8468vb1EHM,FUwSpI7UFwgMC2zWUT7nJAuNeGUJBMppZm078K7BPPo1Pami4rZFvOqqtKFcFP1251co3brGIekLgl4UOdQjnHCee8poIW8BhkBIi5fmzfOXSzWKT0VM0FsOhr2lf5wt7twrZpKukVVdRW6JZJH7FmfbywQ14QOcD4PSf8MqB0WKdqNNUrYkLQHJlDvfXEBgKcx8nueK1f6UGnTOIm5vz8WfV319IJTD32ccnbhEdr26aPSJLNU1VQKjmLHp20tn,mg11fdEsDaWLXraMGRE1rh1ygLcTzqnfJE8zlJ9YrjVeeWYlNG7YZYYJZbSPmuzdE88DTnJdc1Yw6MCNWgMorolyOLkymZldFMvE78hFLPVIfCbyk6ia18FSz6Q1d4OJ3jdUQFDlIGYvZkX30gl7l67IezKSzeT90FZCWREqCgSZdaRlSMMG3yVW3MF2lAaB03q4lZ1aFpUGAyNThdEHATqS2jNyrNXntjbaubXa5XIZ0BGsMpusRwLbxHpVhlSQ,Jh8mNOh3TADdMNDrE3tLLHCgOeE3WXW6l7Ng3O8YqVAtXOSnHvzcufXyKVTWvc7DlDlS7pqShcd8cMNRRfLKbUP3GWAgm0Gmvx9tHQMpw1Afm7mS2ByDKSDPh7OIfZZTyy8d2tFBGbEhmlamp5S3cdiFLt01YoYzrPmugipymKRubaqRNXFL6qvtGF1Hikzrr6T87KYrqlBNJ1fwtKR6nz6bg7S056XzKrLdqc2mA8t347f5gAoGCnaXxM7LOCqW,P7W3YTHhVItw6OE9Y96QhomvwmyQtbR3w9sg5gqhhAHJgyLStUsikfmKPf3FsD0aZGclOE1sS7yYMBfgd4qICi9BbYcME0wlblOb9PJAo1EfzFOCSWBPH3x7sgIATByvO7EIugFIvIJPLlOpL61qVGsz78pm0YLTaYQv8kbka7sQhTA3NjfjtXNu9TbcL6QUjHXNbhdihqPXreIk6ld9uNbgEaCGS6jnDz4tcFZ7hFzgOx0y1edBIIExRPcBDgaZ,mbpucnXM8haabltSPBI7ovBzCezXaOHV7JQ9rEx8r4xxANiWgEsVy0G2MX8kIhbxiWHfEb9CLVwUy5MWehIuKhcHjpi2htWBjmexrSx4u1Cww4a05e6vsLzKrYUtAUOJVjEGPB9Q3PKehpyewr6UbszQzgDVjYlygFskYiEPdAhfcA2yJbgZciCfxO074YG7YEg5d1CNP0djB5y7Nvy4JK17rRXcsRa9mYvUFV7tnUIuBmQ71AazWha1t1hJ8pdf,4Ks6dseJLCYPfAA3T4ASAG731pxJ1gXwH8fzdRUW5TrvKSsqoYVmwurNNDpYjBEexGcRV1nHWJmzLN9bXdHUT3xS8S7nsxOe7ewX6sobXCpqlHTDp0BiXPtNY7LWV0z6w9h1SdBhLlXNg4zAJeoi1cj1X3C2GiFFT45T1nkl3RAvd5RDOwypJLue1GI3OtSYj3hxuTYIJwOatYBJju2N5ypFGXJU5wpOYNklI9G5uzMq0TyZsXXvThS5yHZp9ASb,IQbuUT2ZKLtGPCmYUstdU8gQvbbTS2RgO9IJvKnxh8pkVJIvQAzv4MHEnPDVEOBnLRDEohi3OU5cvpBWL3nMoJaSXuP4qMjfPZc144MMdLaoTWogzjoSyxJd3U9lJAwwCJgijpuySHqPgISEhTavkumWvMPDIJKnC6K0UB9VR7tvvkmfKIKV3MrPAUdBI4LKOkEmEm6vj3LYWbc1SmfxrO4S3i8Y50HaNvtQNTxTfgTbTJhgUygHWMLExCtA3xEt,lH0bdmV1hfC825DDIf415GpqeKV1utKGBbUs7jKGPPyV94uszfpmjMmboOGLzrEkMPZcB5buqqjtZYJxIwN3HD1oGsZEpCXhBxbvwDLQzMyOnEQR1Rw437tLje7hE0j1ghgCJ5Hsdw5BeyrcGVUbA3IMLCOEpz2rdFclLeCffzwVUMeJefK4MAy2wPcR8hds5OMb07JS1UtKVIjk1GpdZ7m53cpK0YipEvFkZpjSsbhAW0kNbSxTzYyS6G9PHMIO,nXQoOexaHbf51xHTgKbsCWrM6CvcndA8IB6rSVxRSubX4Gr9F4TGnQ38CEXnRowYpvqmOIl36nHzjYybfVP0Fizk3OUix4N0k5LEJQa3xBtizGRUNOf3zTa7moj5AvvNbbcm5VOjLk3k72teU7dDgT4eDpvFT0iJXDrh2EIpA5yomJZiOiamYXuuI7efcUPSOgwPJuGb01h3TaNJyBkZo5Awt5h3SLtIFaNLhXdfKvg2MCn5ndmWd3kiAhkqtEeY,fE1a2ls1L5dRR6AXbX6fLq6JL8lyAtfoym5srwQuvqwB6CrBPqdjrBgBMV6RE0VyPiNju7UZPIwdiY3nAeye5D4C3O3myzJf0LvIOJYWH065PZHlLT43PpzROf7ZrjCanMCjjw7hS4LftEQnU9ADzgI6hCrTKoqVk7MalvaxTKQG8rLwMuhIICVbh3MG32kYswNKGB5LZnnyIBFy5rGZLTfP8H3opCmmtk5roNhmuklxM6NFYlqdNuBNmutfPhE4,rxiq8wXkANPtN1PAS4txYu3WH0Yh8Z3wMNfPeFvaUjuS2pF6HY9eGwBOXmeNrhhymxCPPBvEeWRWuawsQ4RSWy8e45pbcR2rpk0Hht0p0zHSlmkax0dGnlAVHrtIltWu9bVu05zxFN5s1dZk6Vx4yF76jgaIXjBx9GhDhP4RuvybG0n02T83zrZDw0IoHZxmEoRWGwniKk9qmH0lSiktInJs8osCB7jwgflc6Sx3sxPQxlabphB7Jz4P6qx2QCEG,8WO2s4U6KIsnHM1iLwRW2XUXVoVo6VN77nULVgvrvuwHKd0wxQSYYA1SIALhi35bGLs0W17JqwrvDsrSTQ6TZMjfRMxmXCnLuxk7loMO3kRYEdTEfo2YPBNpf6GsxZtsevPvYTGpbnTpTOuwpqZkw4k6JFr9j1YNYtzjQnB9a7P8R6ocftkoUvrJCGZ8IvsXWlb14S1UnE522MeQPVuqnql09HxjOZIErAJZcBrS8zEy9Jmrl6j9q9jl9j9PCNMX,1eBO5uSTzE1B03YwytO7ATfzrJ9PxcT6FELU3sQt7PKq0cPZKnyitxi8uocJvKM9OwXL93fkI0h8tgAY3BWOH5R3cuOCnk2kly3POklaUfRMLEl0BRPyiu1y1IvTSBZd0YsmPsGek3l96hHILpjIwWc4Ulcg1i6fm1VhkorCo1PoYHvVaMbIGtL9I71mdPrWGKUAzBYSHlLzKswY3nD1RXqeOKRjrtp8p3dEdwbVRy4KxS7AanLrkma5QHh4V0iE,091QIkhqYvkfwGvVVk2KgHiGnMUGw7KP8bkXIzGl891vGFSJSYUoHkdCGvV3u9Pt2SPXMxdMOzJFiHoPcOdKG3PBB2IYb7SE3gY0pXakr0z7DL7un2v5V2pHWxIS6A55OU5ujsHQfbFvoa6ZAa6VELRTPCJCSw1XNecF4XqZymUNv94DYqOkTBnqAV3gPmO1boaWSQHLirzc2d57P2N3LzdSeOaJ9betqEJpBp0AwOBoqHuuvYcSsK8f19hFirjO,XOUMFmIXG3pLhFwjhl7kkfPyvxH1minSdIcSRnQUInqKysDTJ62tdvfSm9798C4ZUwUrH8lWVa9pIymzCiKLeM1axaLSuGfkqM8u6Cj1uDqxuZQCNPZStydMJ3MC9USB7TFICU5GxYFTtv6kCOUTwmY9JGq9Y8ebiY5atkrRgckHTLKM9uR8cI8LXxMJiEUGgjGgmJc2oIWBNuFNsVOG9QsBQGblb2dHhXjRHHv2thRqtQSu3LO5xD4kKTyk8yuI,CR4OXFoi1uxcRk4oIYryAIAYd9yOBYCHLcl1rnoB16sKIKX5PDsr55aTQ7OOGWEFED48iaDjhFbLbRWwmEI2Ebh8BdHPxpUvYM5IpN2kY1sNoNsyJf24Z0Ciy6LUZYC2dTSod4BEE84ds8II9A5ikMWAhNtRmTgtyXOGx8ozCcnRLOPT6zBwNm4o4rP8XZ8sIeTDW1P0Uz1zTzpCs7SYrxmr1lxwU3hyoMuNA4MtTPpKkYmc5N9O8VMDKGehwrvH,56MO6rppFPo7icyBcWbrj1WslIEObKI1O65c1Z9A2SI8HdG4tsPHp0WvuENtlMco9rRuh8gk4AuPk4O8kHCoBEoaUrutBR6U1mrSMe2w0xTyVBs3o4IFAtl1aTvsuUAxWlBuM3d1QJqFzjOX8fkUFEkySTs8i2I3voCtu8ZCmdb1FLphGPJeZrm9dRpcSq0cjNl9fSxbh2Tqzpkb9HfvSNiUApZz9YClgSVJiTlgOyDFcRi3BbuxWztGmBxOdQYN,gMcBeYpxzS8gfq6Bh7VhOTFGsIiG9JrT48LZBAUoHEl7xagwoMdIDiXraxkfLbISNwTBby8IPac5gpapWXE5CPHxYGpYobnfsw0KsFu2Cz8Ee9T1s69r0WzxFEz1szlIcuHRw568CjTZuBJdaM79ckGDxwGqA58A34f8DQSSGdcJndk0fnQLvpcK3Lm9vNGr6coIIBXLbaPkG65ngV4sBYbAOnR7Yp2llcLRQkH2chcEqEK41d10qWiXy8CNXlpQ,NcXNK8OkZe34Knhooge51c1CfBTM5IKwcZ6Y0N1q7aGyOsUNsfp4du7bXAIzoMUVLRtN1fhmZSauvPkn6cBhStf26yZNQq81XGsQW64VOOPiJy2zyeyuknkNTXErVLUToE9vaSm7u34Y7BLvAMwMmIC93JvY6uUifu7fdGEpvW3dXMOBzRwQUWgLszfX9qT8S6N7BS9FINtli688y6d1OLVUtRKneQ0Kh4Y41AbnIef78DKReQNNUEdS9AbD5JCB,n2MP2xUkcgaSgfdKGAgLhT9HyYA5vgWh9lVWfKrk4b1XVPByIhP9Nnkvfa1G57cyzPr8kN3v6xNIS0ziTUSmLEAOx1LvGbgN50mbyrqCHjCizn6TiPUbpRPbDUAj1ebJa9cV6doyp9AWHGQtNlXIeTYMzR1YYfL5xJIWhoD5K4Db9iwbeF7WOGPnLNMMDLoXIGPoLawjXfLzq26QDBgLUaOEAhGJf3tuF3GeAHK1qQWAhX8CCTIS4c8GVZPiitNu,tQHO4DCAaMmNIXNSWQlETZyqxeuRh4HQsRzexmCguGQfcZG02bDf8T0NkhGVu1NjR78UGZ34PXmAZXLk8Vl7gOFYA42g2SruhrRPsDVUMPnyJdyJoEkws38rzh5VfzeZGJBqpOBVuh33fKwKtjyRDWce282bYMLEaK0G5EEVw9Tv8o1t0JH8VpsdCSnFENQlE3ydlqfCqHEBg40c7igTa2o0I4BmBca3ie1faBOR8casG9y2fIxdSP9ZUtoFEZgr,9aCb8piqHzjF8lHbIncKwflJA83n6f5cUrO6WgNW0JwDS9Cl6qbtwbSieQJUQ4Gh4q3mQc8j4UJMH0U1k3h94KOoJB3uPciMBs406g6cKTS5gqoVbnibW3jgA80oqOBaToIQVmrlMRRu2sfQN1NrZXq6bSIKwbbz7IhKKGBNvOxQfIDXBD5EZddkTT1geOokhcenkz5gEnsrfAUaSZAgc6TtATxy6AerhXh7djekCla4dVWwuD2mjSPaxcvvsTrL,KBYmB8e0IKm8fal8OS2Qs1cfUONTi6pi05Ispag7hmS51PaWmiujZoQnHbh5a8Is8T96mYxqUArnXJdOyPSchxtcCn8KIQpijiKTBMLBshVwjBy5HSPQl9qFAzz8fWKrUNjxJnQZzFGQ4O744ws6icZ7cY8ugXuQY1Cql4fJdYxDlW8hJigTtdtiF88GtS7GFTtlvIcfHxtrW7uUTcqwsGzbMm0dtt2pX7wP6pxd5ZnTJL9JrVvL7ywivEduonIS,6AkCFDbhyBzmQAV8F7Ou8Dw6oh3LWhUUwSauTGBbOZmOydhow0eTgQo0YoeEYFHLAdQYtamF3TE6YVwR2dt2Swd7UNGMLuZTOSB2gSd89qtn5Jyf8yNcaZ3ilrM1Ge6K7pYh9bu8bFeEdtC7VL9jAG1bWXmwFRIJdcJ502X4AKfvFcLVjj3VXDwPPkMiuY4TcgfnjEkgsUpsQvuihEFMir65DxplRwycSsVsLxaSNOpHDSdXYGowYjAO28gZyIuo,LOXlWqBZ4deRK99lAxGDcgRL2qUX7Pp3nh4u1QR5XBWZVKY2SgcrsjgqzL2CAZEvmurjyWsWPNikiEVqVbE6Zpi2ron9ryxIvxZgz0DwLpCKffMhIoICXG3VfpkHkhkV1QVm5pHu2Lsa49w9kbHBc8p17AFvP9SeXIe6eDH8jTwketxgjI4cnrkKHbnBi7usuLfHBkSztP2lollUjASyc3SGbPW7QCcELhAPiEehQzjNhCNOVGaFYCh1XfnEG8ol,kwYxCGTREHERnajB6OxkJitrUIoRMB79qrYPRt5plZX1ExH279ExnCHwgT83FURphWCRMy0EyemvRB8dlnEckqXhv3fd90R9Yuh9tldTZBfHrla6viJ9pi1CYdkyBldCza8FAujwNMHQVJv7kJB90QdSLWLxZIvPxj2GyB3FyfbyotqLZiqemR1KcQ7WjGui37WqqTUjLlXbeGntLkCAEEsPgsgewjy4JftzHMQiU17FwEN0UCpIVY1gn5tTPLem,eENwZeLNkFjZ49ribzz0mYmVIIf2UacovTAKvWDQzrmHTSbgq9ku2qjQwMnjr9wfP2uV3nBFG9WXp3LpjqmK8eDv3kcislhmvtZHNyCR9dGlOmtkzNlKrgdSX1mgxA4eEMBt1ZsZupuncflKzI8TB5xxPNjBIw8wwl90FpaSv1CxfAofEYIlPQeJSUzgg3k8vQm9OAuVZnMFHgnc3W55gYHYI0FBP8HdGVURRLgq3XcfqhPDTsWWe5U31FKuKDGV,mRgeW5jwXnZQNQfasoWpvLRzc5BvAsF0UKQXbuJQi5KyBjiZuCtirBjJsbzqhXL8VpYdwUueaBHplzZ4deUYcxDTacSrbJEXgvUY7kQjElRL2yaOK0YDhHENudb7SbMfyUfn2m9MkaE2vXtG86KyIPAnt7MxWObaQyAD1VghNRSzbLi7iYFftW1VkichTxIyeoFzTDVNaVL5OH2e2TmC8Kl2xIkEPUgoURalB0zal5TxKgzWJcmtPY7mgotHUzeV,SXMpoMlTQaXWApGdVCPkDdE5v29QDSnEdX6kz0duhxLSVaeKPQN2A7LglyFM8ydO1wqL5inNrIe6vEY1CjxofuPRiBgausNDXCGA71nthFDN3hIgYhYK5EAVUQqSrOi3g76iG5YlbFOleX3XUxaRiKjh7dH2guQ5g91o2tPXu4TuMKFAPVX8xO0TAE1d22xqQ2HBOcGrGFOlxIjC0bFXygPruHg3aiyEIZl5xCUaYm8ewM2qT9TxrRtMJCZmTgFo,PcBhHFVmV33ccXzczr065yqJf6TvK4jb91lOA9s0SJHKI4UGJxJTjujguxuH0i8VZ5Rbp9zU8jrumiwZ1EEJFhDuWXgcJ0WCpQpF7U6AHoO8v7nnVSlKAzoZ0B6r6uQu33ulBoiR9bMFVjAn9CtNgCjVwvebqVOxqRID8E0VfaRTLWWFMm4o1KQMZAgSSdqveM3eAdmTMI3ZbWjq4vf7qZNLWQB7KNqMQ7Ui7ktOFDcHsvf3aUKgGQAQjNpckCgE,ROBsp73mMHsG5WwITTMVv8hL6GyUUaTmb8w4ixaiRjTn6C23z5tdKrSEo46r0Aso4RbsY39DFVEbW5Gy04Fek3ZtR5MQlXsQJKE9Z8iMVEYSnFRdDRr7o6TbOCMmX5lkGHvot9pK2RvyLZnMezKJIM4SyHeKzFqSzIn7fhyFrbA9nrvECawgyUFbuHiu1o0H8SkDaAJjZdG1IlMWdxqtr3q5AGdoFLqzjg4wlWvI7XGOucWJgO1KqatloGaonJs0,WhE9B2KAwnptjuq30oOauMsSMKlJ4lsmbAzI3nZnIOfFb6vQZME1jSTp8zohVWuHtuJzNfPyyPpUO6LluDr4Ptx14ziulJ5RoTTKfsZxrd1AVWK2XnSBfVOg1kuRQwjnHeiGNk5AxW2OaKxIAuVR9a3KkV7XoPYzZxVSfzz6FgJTUEKafInfZMs0pGG09NAysIbOVjUSrC3vNRWHaFCa5fXh6U0eo4UG7PEAXW8HGkeb5HT02uHDtZFJUTqnmtcc,1zo7IrlLka8fZGxYQYbcvWqFLr0l4UKB0Rq3sh4ggwsT12MzWerMRbRxLfppV5obwj1EZ4U7WzCJj4gNgCZIPVo3RRLiCi1oZbWlkJOl3MNAXM86QQ9ptmnQrwZvOKp3qJobuc1xmG4HjuMAFHr20voNCRwiuBK4UtivKu6p3dpxsZd3qdqQhpzmXkM8jiMTi2dgUuE5v2OZ9tRYHoNlbxYcreIzjrhulbAV4VhjfXACir9SH0NEfxGBoHB5zFvD,ysK0ArRQynJEf1X4FtyC0b21WOtuSvkk6iomvfDcVO0iQyIDwkYNOghJmid53aWEJWsfkbhl49WXZdp4YYG2onRcIm0FbccRP0rub0J9BB8Xs9V1ZQlScSey2QpaNIIU2RW6h9xMn3B5S6CuHL9Zn5Jzr4JthCqGgBLmRdiQBUDHCsBdE6PcYRd6hjKj9tRkYHk4d5iOmuFjzV9f6EU2fEaMLqGrIY6jET2X4gTd7FJTxYhgwfpHbfSUURzF1sVy,wAqVV1wG34L7lhy12w3T9fWXJTwRQuxki9Bdn8IGm3DvKD0FuBkznoUtsK9iLtMvUgmNoSpe7ZWYe5PyjvX7s1QGLJxNxLJMDIsHUEHIrhDBuOKQ2pNiIEaha2ZnEdbQAuW2DYlFHbpwlyzBhPtP3BcgKH9YJ31GgCw8jQ9D8YrGFwUTohRnp4uYVNjL2yWGouwoqE8NtrCl6Z38zscu4avn6fcFjjufnYd7gDaISviW94GjrmV9KhD2q7KRD9JD,BpC9ZqJwdXNmCRpPYNrnTl6yTzOg4O8F2wobhmDRfmkoyAiw45HbrcV1YVdnrAcRmpIcjy4sz3HbJkfs6UhsjYlQaKr3KIMy2HzCN3HUULkDBUuHbJWtpga2WuB6EQ7qoTVZBOXMUGBZVOunLIjBKElE3b59G6C24BRsSkzsWnkjpcr2vlvyPA09ZsNM74mRO5RITRaQp3BQMQBSgicJxhBEeWT7tqQktbZrkdKG1it8TLF5yVW9crqRcDXhIsST,wbE4erZaWqiIwevEWaPw5cR2xUSKVjoF8syIu5aHDtylrXghMXFEeS2dJh1n93OwUr8BiAkdAPeIWwkqeNUJJwTfq5q8gkK8sZmklF3bMuhe0zbWqVdYKeZgyBnU7WHeNtYmIpzSnl85ln8dCORxpqLOh13rTi4PahOypLOe3zAiUFEgtzZANkhuV96NxqONtgc5o637Ses4QKUz5tVporBKPF9Xygz2GPBqOVkMd87nbVglem7ZhSlttqQC7Pii,W0GClUMosQycv5ToFPf7Tw9abGBplYvOFMut0d1sXGP7GmTxEtqCKk2QVsDSWpvu0qbC6uLDjAjcdIFjpCtndsnQHr2KAJHMBU9kmnPylfVDopCNwmRXxzxdwkVtgYoNDtwcim5bdDfC0SHHUkcjTuO3JuT5378lZ900zt0JyDSLZkKNSz5n8oikHQSEIoOA84o06UQFjxxQU7Ii2qbbql5U3uSeOhfYW1IZU8O33vsegHUi5WgDz3qdvjxTagV6,WLMJtD6Icorh86jxo2pwC2ZQmmwNtZYD6lssjgGQdtKprepnukoD11732w638rk1VsHtKCgwZS9tyLnRK84vaHMbLPY9BSljGnGhXsyyfT3WDCJk8SDBYUXmQqrKbjpiSQnGysAEWyiGbyyre6XxdlSv60MBOswnzDgPCDGvqULJJk94bBQ5vBUpjbrBPgLlW9u3UXJF9JZU30OWcytj3m7BOWhKJGhhCjO3cShVEPG6O4SV4mJrlV5hXUIE3POe,hHFMLenMsUr1SOgd57O3yDTrOuGbFlPwyOp76uvOHLXZcyCBHwMvsCeeqqzhEOuD9WZBxdAOaD9GuEYN3OKUyBWzUPYUJlEHxmn0RjHPKMvbVgPypfDwHfNWOpb3rP7OwxGiceygd1AWgEIoKJT1643mX73BgS27uBJLxRIj6gLsjrSQzk5ll1e77cWN9FobkiC8627Xx2OVznOpqfjX7iIi0cShXflMbOcx8blQNFlmnY4F3X0mCfJi3XtLUK6w,RQZBrQHCEq3l64xo0s9U9zUhJq2LdnFk8YfAxOx2rtUWgAmAPQmANwy9KedWHE7tHbDyth703mKkR67LxGs5XEeI0sWQ8U5wmGiCVDCQuCyhFMUc36vn2yYF8hm0fIES13QyUqlXoKHv1KePPQUj3WW7fSOknWAziDClW9M6yjVQBKQmnNo0AV4WAoPjH9vna17FKVCc7SdQpTPPTjCcOuthe9zZAWlE4HDE5XA8sbr2UifNEYVEcGCrIincOZlN,C8Vs8wTwBLRkTw8xd8NAOLrsCk0v9NhRkBMW4UTM46W9XqklCHX2jd0sUa1ZfgBYtrbAFKRgbdOp4LIMy15MaRzE22PPXAV9OF0rs28YekRNAmK8qmb9RZFnLgm1UoPkDRt6xjYTsma5LF7ExAmUSSNfrhL8O3wIh31AXY39oSgrnAYezPKuX8zMkmvYwsLmIxvOotuYNQhcaTxLYnP7Pcl8bVgLXnzDGRH7antkRXwyqFMLWaAB9GPkoNMS5f0o,0cybYALwWfMqxGv5IqJg8gfUdpSMWQMVLBOqx5pj0NYITOZVahjZxuydHo1jBgBDUcaZpdhTi15N4TjFuW4KEVHdxjZ8s2cLRqbynLqSa8RM8b7ZVKKJzvml6LXmeQjExCX0S2T1M1ONdcliLAipiHFTZsuNecx5jPlVp6cLwAmB3gSO8zoGJxksuhC8MIH7c4OHUReMrCcFWpcv8mMf9MXkR6yqIjUZehB05Ll8T9VYNxo3xmqv0yRpLaUplboD,Y8JX4ZKbItoZNu4Ywdc3fNAAoQ1oR87eosAHciRYxVt9ytVLOIUOpyTEMRK0H2sjSOTTLb0BzdByKHtV3AT7MfmyMQYcaZinaQbk4W5wPLnFYzgVpG7rmdex0l7IinsWaPYSg1yvEepMcJGDSO2NZtln0cD8VvSI460EOEra4vclueFq1ltPId5Xcy3k32seobEG3V1fF6Hkxp5P2pXjfDbwhtVLY6X6L9V6ER1jR8k0XHQADqjJHALfvjhux7RA,XSmfngDb1SPAWUxNDDV6TOSs6774fjJgYAlbIhCiS3sE9FUeGUidXeawWbvlf9C5mWoWCGigjqE0EsB97eH0MTxc4O63gP6uTYbnu7m4SEC7SKTa6BPjtbXtDQtdpqwmDoFHnMPBJgDTJCvveg9MalQxXtGpJUH1qYMIl5rqtJLdLPyXyPEOp1Y8dCgpTuqmXdfORmzLRCTbypcWCbOQdbmQ022tYBTCNn49jGbzV91BVlDR2TG7OZXYeVanIh6y,ecTThEmnadPkfGGhdRQUwaYFJycjeKDFqaL6924vG7wh8SqZV05trQeayuTMlVfbookJGBfxyHzaTuPDCZ4epHkjTaKKvKAjlVi28aB0dJRWSN6aKwSsM37c6f0dvwUuFr7do8WgwgSFZL51OSRqConsJfqs5Is6OcKWOA8sOOd7UrNRerXYHcQJRVWBKd2QEo5rIJpiuINPhpqOXjwsCwfLN67y5NXyxskccsomFG2dj4yivKX8dc47k9afK14y,9HB7fhaDr7DRFcTaxaupC60Hk3YkgWWcqeAiO9iWCZzFXosDwzE9kkYJqCNuPHkhl5V9k58gaxlX3lxPnQ1VhqTiLcIOVkZMLnZ6d18sNN9qhXtwaRdb8hbeX6aeIpzT0kc4GoY617uY1VSvhw4V8TzLussIDuWMjsLunBYhpWDefsfJesnnEpZRUNSKFKCDACJfLeV99otK8jFAusDrN5vvquLE5trvAikKcngyrf3yOoeCLXVCMFc6XXS92f4d,7KFgn8IlTkRy5Fa8j8MOfIVIzaKDJEb0TDfHal1ZnDK8rHyB0ZE8pkmOfF8zcB7O43E7Igm41jpmPqyxzMte1dyfwtpXWz3TebUMwzJtqwwLnE2GReGiqSx3p0uZhS6TLrDHbMpyVKWSSq6txyG8cvx9JQNZ2sggL37BSUelBRTGAvosEIcDWYzWSgefs2ZyK5zhWrGRvf1anoJxTqWQrWhUJ4ZWq5FhisqEgeRrTRGU5qXavmE5eYmoRMn083Yl,t7UuZ1azzcfjp9SZz07ZpS1LTODAPQkl8S1N9BHOAxENimqtJNxxA59fnfoeDbL6dQ3jKegby6CHs4luUAXxEOKCehJa7yrqtuEL5kfeYKNxlX1W97ZdRCOKQa2X85hsYPrsSbDREfWVsV5b1jAinrPKZSgjD6rJR7bMS2VwlRa564b9yhoiZk1NZdzo2z2ZNCmlBSU8xhv4QdXc4Owq1au4zVK5zEHAD4Dr3Dker1APWT0mXxvIlJk8Egkykq9G,gr0aElZ9a3jJnCqrsGqXZUNme0xRd6nBgPnwc8xyfIM53aKwfBkTLftljb1go2UReolxq2R8eXKKOyejljnlTO9GDDZroJymUO9Sg5z6SeobYmD3l9gzkxVgFgePtyCrGpfs7eVQ6DfrHHBeRHQACEbfdjVMrQVA7KmSVGJ9zhgylPCh4dDVnqqX6CSbjsyhlpQJQFSVvO1iXcygwkGYuvCFEQqRMAcM3b8QQ1bZA8SE8rfRXQ5nRPofVeCfsfTB,Vau53wlEvRLyqbkH1FeE00WRelxZ9LeJAkGjyxXBcFuASIDuFzqMtZaMRE3tyK9vYgSNKQvvofr9TbeVSGejSmGN3bYJi1ZoSxdDi19Soy6hTTEArYMZLXwO3YDzbC6Dr9AaiUyR9cyzF2t1i9YP29MFzXYmxd4aBTrmRuejER0EWVsnchBs8EchMpViDOSmA2NufDpUubgXHJqKNvBff8pxDNuX47OpuP4a3ZKJMEKXzYBqllIIVpgmmFqovnQb,VW1Vg8xmIAexK2DrZSxd4D7dvEViBIyWx4BwTrxPb3z5abwDBqYs5Knnm52CLrnzUp1jdX03ctVWwj01bswyNHi4zHNyMrXapoMMiVKrEBuOPX7G995kPIhiG563m8UDOgxkOXBIhu0wm91R50aOU6ECxQzJ2Cxr7e7B3GVkSOMlRv9s8AnVg4nSXlnOjUuIgGNsh96E8VBEer8HVu2LcPKVAh4oxGjv2WwcD9srhyc65FjgED0oJNman0zfg2xs,Cao3cHslsLeIxglxDNMvMgLv4Tg9ao00hFCPGL1pMdMJEOfQJX1dcfhI9Iy6beYCJxgsqBsdOoeQVrK9xaZkT5lGwOFFCFgqLSvOxB8HTOm502hqGssIIeGGQpfl9jOcFfw4CzDSHdcLZKVy7E7Xd8oiH90L7uThSXZrej56mwD8IuVX4HcRh0JSxzULaHF2JV2Y4HKPw0juXoCE33UxR1m9vwWZ6OUGjXXNHOfuygropzdOFZPLE5dZUMtaRsCJ,cUCktbt2ZhtQNJ6J7fiC04SkuTKCS9NRv32Qw3p10VXfxsDg1ByidNgFyjhwOS7Gp2OP2qHQTPtcTSRlYPdHDjDalNcjvhOxasW93CBM2A0Xnl8dcpvuJSqnKNMO70E7DNrF4ew45RO5b99nM3Gvud8tyLuPfCI4WSs4CXcmDqoaDidlCgumXcyv2sghuRCOZJv0Mo8Ey7t0BExJcH0NKtHgiyTOx0gXCbBSLuEDpcKe4NlO8pVhNF1z1u78OXKi,8Vy3LnIe4VLDvSxKiT0pusAL5N5UajXkYEuVMYdVlgJcAsaFbC3sSR9PkmFi48oDEiSmeikcDKUtL8R2E11Bpo2HEUKnLkZ7GuHh2pWiZFxqKnhHqwr7m2p2Lg6lscv1B0x5wx2MQ0S8wrD7xRcoNYHxd3e9kaIBHP5oHiVlSkWFr49LYxgoSGh1DS4pJfYeLmgGUhQJb7oEaXNWQYarhsB2DwvxemfjRRC28t0yBWoUPdVt942SN5gOUOUQ069E,26wKMSddRTKKj4czjq1FkmFlAsEUuLOalvUIcXenRKw61chk0zfJXViKiIAsBI0n4XsuUcP4BplxKyNsbTlrmyAYg7PSzXH8jq7wyF6GG44J3gk410MdWeqE8GQyt0QxaTJx4hc3BmfkxdJRn71Yrvq3ciV0zjifxKJqavxqFuab3R3WlUFcQZLViGMwwFS7VgEq0picAf6V1RCvarCKjv4Kxm5TQO9Zr3PnV3fhGHkDqTal8jCjMAeY8yPqDxus,3rqkfYZnzF1YbKClOcfUb5Uu7HshBnJZKhB2JlL2elPuWz7cj7dW6C55EM01UiJntvFxmFUhGFe7kQ0va73etd0s3TSnrFMlAJ879eoddtDjnMRF1vzrqIIscu1qUdJL3EUeDHyzKEZd3JmSGdlqL7uvLWTO5GevmTq5wTzI7bBM8tbJ1A2oMlYCYoG9s3v3ADwmD8gd3pkb8SDZpMb5Bnn42rCDTU7LSkBZGcj1cMpnpV9r5iNDbWmSgpIoaL08,VNgVzMNf0KG4pU1NvxvvG4fkCQiwzgrQC1kdBUAtNut0nNqOlVEKrDsX8MJG6THyNucLHfuUSq9vJbNx0OEM4q51wbu1xBLXmG1wTWXvs7OdStOZUnDkxiT6hoPBvkda0xXnKueZHFH0NRYwfYLAzAtyv7ypH9ccHuey5yIBIfxK6OjkY9XTlBxCebqkQSxiprUmM9RXuKs94ZOGmGA4fIN9h2lq9IYDyXRceWNj1s8bl6qvhwr8QKz1haaSx5Sv,0aZNoKtTKX8PaM5FqZlxr5Gm2PiUNK1jDuPeRaAqvPHTD8lN6DBaWFGU2mn5QBT3mO7X2J0S5Kk5UqDsh8WhePf74yIfsvBgRFiUB3B4YvcCciiqij10bi7JItRLS9fbiz8Zos6VqNp7OokP4cT3BTHXLaZu3JkfUnLPoXfvQgkVujvtgUhqhynk2IgG940Yq8Jqu3P2thpXOMKXAuIOWZDsjkDssXYMC8nEEj3KxG8DMUIWEmlNOvdUQLrjJsfg,ObJIPfWJkjtSWfvsqTJCmBPadJEDhs1houBPoFMMgND7WDua2mQm0INBz57IWvRhSSuJY4dz4i13IkM7WAcGuoXhM6Td17iKd4JeJOIBh4zgdVHIGOhsRhvhhD2EhCMuy2ZPooorRtIgTbtDu6vfIAhNphhLXYMquEu72QW0AFvjmZI3MfLyN2GWM15o0Xi46oRIpPNvgzMm6JWqpjVNdBZqDj9CcLtll5W4MW2W80PuY2M0kBjPug2pmG3bFjUZ,ByRMa9rftvmwhggCjfSrByKILCVzexRoDhPuEZ6inqFu3B4c37W0EsSs0Fdii6231okxPDNTi7fDNYFkXPZd3xHmBQV2IteJtzWiR5fKJnWfEQXpgJjLXzEYCCJpSvwrwxS2Av1GJm7r6Jf33bwSZKzdX6LyKOrpGhJXCMuVBQu3hTyfibat4qBEn7nyIP1M3C0AZjIY9GeYSzBRriFHltwQb3GlLU0O834QRBBJkRBEZvjQCBqJPUSazVBVDlwv,g5fyyuygg0FZIMDhqT2FvpPOvQqEC5bThQmiZxBYk7E0t36hJs0bN9xpLauxvHD9Xrt7fIvxBuXbWHEfmMDZf3EBcNyHCYyEroGlzJI6R0U6phrph4BLdXbKkEEAnnc665stmVnE1Ab9QlWHXi4lGifORSxVh0CpksQjeXBf5yMtweRggZpeSBc5qtJWJo3K3P6dtOs9BFTD3D0X7SU54BwE6zdyfeIoHAZZ3CJ6MoZoBD30jCfEykEYGmjqaG5i,dHv60aZBqsBWECnDaEso2b9vC4pcoDKAZudsVdaqLFKMwuTJiUdh5h4Cl775zuQPNhnPqhfqDm8OJeU49EG7Z6ITsQT9tBCXaze7G5p8hd66ISMHan5DOhswI7RGsNWRRhCmePksk3c8dF4Ku7dIyPNZicGS9p9HPfAYRAZzEK2zyQI0ITQvo4ONhYu5cyOfJj8cyKOBMb3FnKznE024LV4xjHh22sZtHpaBixVYf3ZnrVVu6rWOA0bC8DekXCw7,kXnYEaOhG9vdE4aJpf5cjVngaecCrEumhcgsfJcSqGU5y817gasDTONdUh5Zrj3ZEtTkTA9k2SJknr1gtJ8d4oW8SqpF7otWZ52kqxmfqcGr4eH2oIeT7e998lKx4Mhi1Z5s9JIOpeATqgoR2vMjiwBwB8d5m2Bx5p83gnOvdNXF0dTaSTA5n1cm6acLCNwMK1Lvgqy8dM8wqGIeeLJApkaNvagYx9cY8yvppEPk0BUcxh6EtZIw4qzHpDlIRGhV,j253omWui7ASlWhlB63IVsF2D7CAlF9gpqer1j8Q56PhWDjqYn3Ts431sHQNaSOXoPIwvK3jPsYL0cx7nsxm6TloAzQ01l2GQVEKKFqoztcc4NYSIqqzZ1t86r1Lcfny99hHifXynwTDIIiT7NBP6ahFZeDGVH9B0cKUUyqNE7fZ5dW5aq4jlTW0pf1kKLz9q2gv0cHiBYQVw7tWb6UUByGoDmmCLaDsffBZYyGm93ONpoy0lC7cAGbZQiMV56p6,PFfEiPYkdMVkM3J2m2gTSwEMh0d1gmgrjMet9IqYBrDrHGegxYnjxqn8cx8CNVm73PxeAIWy0hdGPMUt2ToV2yUxlhvyPhLgiRVYzvfjTvLujsHFCzoTPxn5FGVveXg3KIpMqc6ygrc97dHSMzutoM70RqJw40c9ORigxCk0sJZlc9Jl0kcryQwogq7Dl2a2v67ahKuv6MXolfkSfGFahCuKCC4oeL2ytNZXwmMYW1ce0qOiZrYRHvV9UGghnWUu,nB0caTkrizQPVM4kXSwrwbW1vw4FvIpwUMDLMOn4JEukel6yyknPYQSaos6TXDGck6BK0y3M30EfM98NA6T9QDec22J8vWnJtySsvIonewyjPYefXFBSMWwvIDsHmW3FbxgTxKZryc7alJ9Z4JtlfXfxmai4HOMykYdisjgq5b5cs0fo8N3Ptqhm8RgIBft1QhHmD4lTBaqzi6a5xTD2o8RZrlErmDnNJJlx1SeeO8ZAFd4Uvm4eJRxNJDFwH15k,5zQmBxpSUTz8doNG4LYvynMaCj1bSF23RL1Ql7UeWBRzu7xcSQnXGhVrOvjI4i22CQumRk0AXVojcdtfYxYo7q9RV4Ws2K9GfheW8SxGwlAonvXfFdmNpVKZiJSJvtDjPqMYMm35wDBxo2OMpKfcJkEfkslrdNYULm3yvU3i6iO6h8ZFjHeNm0ONqg5K1R5JpVpeLIBZ9GOm1nV6XFObHRahC9OjoM1RcV9NvacwQ0jna5UI6vNVm8UN3qqhodhu,PZSywNeNRfYXfgbZh3XhMNsAU4Ugh3Xg1rB4I9UQs7qHPT0fQJVmUnjNWPOhi2TZidMx0dhuJ8xSGMF1fwz1hf3iRZd0Tqu5G0zExbczuJAJZl50fCasQ67OQuKhUNvVwtX2KYHiSvY6n9OOfUNWKgNFCQUCUjH23AJf6bI1ICLoJcxcffosOgFA3mJ4qHcPoxKbVPkfRpfGn0AB9ZYDf9URBe6jBhv0s2x9V9MmKWF89Y3RE0uQQHpNxpMaEDWb,jx5g0mcEYVmFCMsbxyC3NqfwkwQjbKNNwRmUEwL6SywqvDpyNAhgU0aChdtni3g2yrC7GaoSfMSdj1'
2017-07-14 11:30:16 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-14 11:30:16 - DEBUG testThaliMobileNative: 'Server data flushed',
2017-07-14 11:30:16 - DEBUG testThaliMobileNative: 'Server received (27211 bytes):'
,2017-07-14 11:30:16 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-14 11:30:16 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-14 11:30:16 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:17
[ThaliCore] VirtualSocket.closeStreams() vsID:17
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:17
[ThaliCore] VirtualSocket.deinit vsID:17 [4, 9, 15, 18]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:18
[ThaliCore] VirtualSocket.closeStreams() vsID:18
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:18
,[ThaliCore] VirtualSocket.deinit vsID:18 [4, 9, 15]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-14 11:30:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-14 11:30:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 11:30:16 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:30:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 125 Should be able to call stopListeni,ngForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-14 11:30:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertising,Active":false}'
,2017-07-14 11:30:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 126 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:A4101E0A-2D4F-4307-AF8E-D44CB4B5801D
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50026
[ThaliCore] Session.disconnect() peer:A4101E0A-2D4F-4307-AF8E-D44CB4B5801D:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.session(_:peer:didChange:) peer:A4101E0A-2D4F-4307-AF8E-D44CB4B5801D:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "A4101E0A-2D4F-4307-AF8E-D44CB4B5801D", generation: 0)
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "A4101E0A-2D4F-4307-AF8E-D44CB4B5801D", generation: 0)
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:11B1710A-4AC0-48A7-A91D-941826AA5C81 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "3203DACF-B417-4CCC-94E9-26751E12B3CC", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:11B1710A-4AC0-48A7-A91D-941826AA5C81
[ThaliCore] Advert,iserRelay.deinit
[ThaliCore] Session.deinit peer:11B1710A-4AC0-48A7-A91D-941826AA5C81
,[ThaliCore] Session.session(_:peer:didChange:) peer:AA379747-01A1-4A4B-8F7B-CD076EE4D8A4 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "3203DACF-B417-4CCC-94E9-26751E12B3CC", generation: 0)
,2017-07-14 11:30:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:16 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A5FCA449-BF08-41E6-8E88-CE06C57DB851
[ThaliCore] Browser.startListening
2017-07-14 11:30:17 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 11:30:17 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:30:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 127 We should start ,listening fine
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "364E65AB-A73B-46E1-BB05-C330DF77328F", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:364E65AB-A73B-46E1-BB05-C330DF773,28F
2017-07-14 11:30:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 11:30:17 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true,}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:30:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisin,gStateUpdate (was in stopped state).'
ok 128 We should start updating fine
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4C30EC80-858C-4E61-957C-3AAAD5A8369E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4C30EC80-858C-4E61-957C-3AAAD5A8369E", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A4101E0A-2D4F-4307-AF8E-D44CB4B5801D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A4101E0A-2D4F-4307-AF8E-D44CB4B5801D", generation: 0)
2017-07-14 11:30:18 - DEBUG thaliMobileNativeWrapper: 'Rec,eived peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"4C30EC80-858C-4E61-957C-3AAAD5A8369E","generation":0}]'
,2017-07-14 11:30:18 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"4C30EC80-858C-4E61-957C-3AAAD5A8369E","generation":0}'
,2017-07-14 11:30:18 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 11:30:18 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"A4101E0A-2D4F-4307-AF8E-D44CB4B5801D","generation":0}]'
2017-07-14 11:30:18 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"A4101E0A-2D4F-4307-AF8E-D44CB4B5801D","generation":0}'
,2017-07-14 11:30:18 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:364E65AB-A73B-46E1-BB05-C330DF77328F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "364E65AB-A73B-46E1-BB05-C330DF77328F", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C176BE14-FC26-4A57-A85E-77356D3F97EA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C176BE14-FC26-4A57-A85E-77356D3F97EA", generation: 0)
2017-07-14 11:30:18 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"C176BE14-FC26-4A57-A85E-77356D3F97EA","generation":0}]'
2017-07-14 11:30:18 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"C176BE14-FC26-4A57-A85E-77356D3F97EA","generation":0}'
2017-07-14 11:30:18 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-14 11:30:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 ,11:30:22 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-14 11:30:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 129 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising(),
[ThaliCore] Advertiser.stopAdvertising()
2017-07-14 11:30:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:30:22 - INFO thaliMobile: 'Filtered out discoveryA,d,vertisingStateUpdate (was in stopped state).'
ok 130 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 11:30:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:22 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Test updating advertising and parallel data transfer
,2017-07-14 11:30:22 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:30:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 131 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:30:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 132 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 11:30:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:30:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:30:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8F15DF92-D29D-452F-932A-AF337CAC8C30
,[ThaliCore] Browser.startListening
,ok 133 discoveryActive should be false
,ok 134 advertisingActive should be true
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5021F2D1-F350-42F4-8C24-35ABBEFE5A17", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:5021F2D1-F350-42F4-8C24-35ABBEFE5A17
,ok 135 discoveryActive should be false
,ok 136 advertisingActive should be true
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,ok 137 discoveryActive should be false
ok 138 advertisingActive should be true
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,ok 139 discoveryActive should be false
ok 140 advertisingActive should be true
ok 141 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
ok 142 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 143 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-07-14 11:30:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
ok 144 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 145 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-14 11:30:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
ok 146 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 147 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-14 11:30:25 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
ok 148 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 149 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-14 11:30:26 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
ok 150 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 151 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-14 11:30:26 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
ok 152 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 153 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-14 11:30:26 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
ok 154 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 155 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 11:30:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:30:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:30:26 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 11:30:26 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 11:30:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 11:30:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 11:30:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# cannot call multiConnect when start listening for advertisements is not active
,ok 156 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) peer:4604d862-78dc-48ce-878e-9b9fbf9c46e2 error: startListeningNotActive
,2017-07-14 11:30:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"qf4pbc8GxT8KWaUpzZnZdp2n7yejhJYm","error":"startListeningForAdvertisements is not active","portNumber":null}'
,ok 157 Should only get called after multiConnect returned
,ok 158 SyncValue matches
,ok 159 Got right error
,ok 160 listeningPort is null
,2017-07-14 11:30:26 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"4604d862-78dc-48ce-878e-9b9fbf9c46e2","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-14 11:30:26 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 11:30:26 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"4604d862-78dc-48ce-878e-9b9fbf9c46e2","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 11:30:26 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:30:27 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 161 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:30:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 162 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:30:27 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 11:30:27 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
,2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:55BA8FC0-0842-4464-BBE5-A3E6B3F53AFC
[ThaliCore] Browser.startListening
,2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 11:30:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:30:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 163 No error on starting
ok 164 Got null as expected
2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"o6Gd6s6tSNo6u7soz1R1yVVp0hcC6nh3","error":"Illegal peerID","portNumber",:null}'
ok 165 Should only get called after multiConnect returned
ok 166 SyncValue matches
ok 167 Got right error
ok 168 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:30:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 169 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 170 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 11:30:27 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# multiConnect properly fails on legal but non-existent peerID
,2017-07-14 11:30:27 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 171 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 172 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:30:28 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 11:30:28 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:89752C01-A2AC-4E82-A01A-FC09C8BD37E4
[ThaliCore] Browser.startListening
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 11:30:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:30:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 173 No error on starting
ok 174 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14, 11:30:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 175 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 11:30:28 - DEBUG tha,liMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:30:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 176 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:30:28 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 11:30:28 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# cannot call disconnect with invalid peer id
,ok 177 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:30:28 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 178 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:30:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 179 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:380b8941-0251-4225-8811-46b12da86c2a
ok 180 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 11:30:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:30:29 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 181 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 11:30:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 182 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 11:30:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:30:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:30:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 11:30:29 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 11:30:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 11:30:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 11:30:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Get same port when trying to connect multiple times on iOS
,2017-07-14 11:30:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get same port when trying to connect multiple times on iOS''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 11:30:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:30:29 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 183 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 11:30:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:30:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 184 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# initial peer discovery
,2017-07-14 11:30:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-07-14 11:30:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:30:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:30:30 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 11:30:30 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 11:30:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 11:30:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 11:30:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-07-14 11:30:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-07-14 11:30:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:30:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:30:30 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 11:30:30 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 11:30:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 11:30:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 11:30:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-07-14 11:30:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-07-14 11:30:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-07-14 11:30:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:30:31 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 11:30:31 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-07-14 11:30:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-07-14 11:30:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 11:30:32 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 11:30:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 11:30:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 11:30:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-14 11:30:32 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-14 11:30:32 - DEBUG createNativeListener: 'listening 50033'
ok 185 Should throw
,# teardown
,2017-07-14 11:30:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-14 11:30:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-14 11:30:32 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-14 11:30:32 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-14 11:30:32 - DEBUG createNativeListener: 'listening 50035'
,2017-07-14 11:30:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-14 11:30:32 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 186 initial connection state should be CONNECTED
,2017-07-14 11:30:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 187 final connection state should be DISCONNECTED
,# teardown
,2017-07-14 11:30:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-14 11:30:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-14 11:30:32 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-07-14 11:30:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:30:32 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-14 11:30:32 - DEBUG createNativeListener: 'listening 50038'
,2017-07-14 11:30:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-14 11:30:32 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 11:30:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-14 11:30:32 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 188 tried to connect to right port
,ok 189 failed due to refused connection
,ok 190 routerPortConnectionFailed is emitted
,# teardown
,2017-07-14 11:30:32 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-14 11:30:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-14 11:30:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-14 11:30:33 - DEBUG createNativeListener: 'Native Server - close'
2017-07-14 11:30:33 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <,-> Mux - 0 - close'
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-14 11:30:33 - DEBUG createNativeListener: 'listening 50042'
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-14 11:30:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 191 Send/recvd #1 should be equal length
,ok 192 Send/recvd #1 should be same
,ok 193 Send/recvd #2 should be equal length
,ok 194 Send/recvd #2 should be same
,ok 195 Should be exactly 2 client sockets
,# teardown
,2017-07-14 11:30:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:30:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-14 11:30:33 - DEBUG createNativeListener: 'Native Server - close'
2017-07-14 11:30:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client co,nnection to node - 0 - 0 - closed'
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
2017-07-14 11:30:33 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close',
2017-07-14 11:30:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'listening 50047'
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-14 11:30:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 196 socket shouldn't close until after stream
,ok 197 incoming remains open
,# teardown
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-14 11:30:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-14 11:30:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-14 11:30:33 - DEBUG createNativeListener: 'Native Server - close'
2017-07-14 11:30:33, - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-07-14 11:30:34 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-14 11:30:34 - DEBUG createNativeListener: 'listening 50051'
,2017-07-14 11:30:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-14 11:30:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 198 we should not have gotten an error
,2017-07-14 11:30:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-14 11:30:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-07-14 11:30:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 199 socket shouldn't close until after incoming
ok 200 incoming is cleaned up
# teardown
,2017-07-14 11:30:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-14 11:30:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-14 11:30:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-14 11:30:34 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-14 11:30:34 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-14 11:30:34 - DEBUG createNativeListener: 'listening 50055'
,2017-07-14 11:30:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-14 11:30:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 11:30:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-14 11:30:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2017-07-14 11:30:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node -, 0 - 0 - closed'
2017-07-14 11:30:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 201 stream was closed
ok 202 incoming should survive
ok 203 mux should have no streams
,# teardown
,2017-07-14 11:30:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-14 11:30:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:30:34 - DEBUG createNativeListener: 'Native Server - close'
2017-07-14 11:30:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-07-14 11:30:34 - DEBUG createNativeListener: 'incoming ,- incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'listening 50059'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-14 11:30:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 204 we should not have gotten an error
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 205 Buffers are identical
,2017-07-14 11:30:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 206 native server is nulled out
,ok 207 native server should be closed
,ok 208 incoming has been removed
,ok 209 Incoming should be done
,ok 210 The mux object should be closed
,ok 211 The mux stream should be closed
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-14 11:30:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'listening 50063'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-14 11:30:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
,2017-07-14 11:30:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 212 native server is nulled out
ok 213 native server should be closed
,ok 214 incoming has been removed
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-14 11:30:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-14 11:30:37 - DEBUG createNativeListener: 'listening 50115'
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-14 11:30:37 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 215 we should not have gotten an error
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 216 Buffers are identical
2017-07-14 11:30:37 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-07-14 11:30:37 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client co,nnection <-> Mux - 0 - close'
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 217 server should be fine
ok 218 server should be open
ok 219 incoming has been removed
ok 220 The mux object should be clos,ed
ok 221 The mux stream should be closed
2017-07-14 11:30:37 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-14 11:30:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-14 11:30:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-14 11:30:37 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'listening 50119'
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 222 we should not have gotten an error
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 223 Buffers are identical
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 224 server should be fine
,ok 225 server should be open
,ok 226 incoming has been removed
,ok 227 The mux object should be closed
,ok 228 The mux stream should be closed
,# teardown
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-14 11:30:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:30:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# can create servers manager
,ok 229 serversManager must not be null
ok 230 serversManager must be an object
,# teardown
,# setup
,# calling stop without start causes error
,ok 231 We need to call start first
,# teardown
,# setup
,# can start/stop servers manager
,2017-07-14 11:30:38 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-14 11:30:38 - DEBUG createNativeListener: 'listening 50122'
ok 232 port must be in range
,# teardown
,2017-07-14 11:30:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-14 11:30:38 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-14 11:30:39 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-14 11:30:39 - DEBUG createNativeListener: 'listening 50123'
ok 233 second start should return same port
,# teardown
,2017-07-14 11:30:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-14 11:30:39 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-14 11:30:39 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-14 11:30:39 - DEBUG createNativeListener: 'listening 50125'
,2017-07-14 11:30:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-14 11:30:39 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 234 we should be connected
2017-07-14 11:30:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 235 now we are disconnected
,2017-07-14 11:30:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-14 11:30:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-14 11:30:39 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-07-14 11:30:40 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
ok 236 Passed bogus id
2017-07-14 11:30:40 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port, 901'
ok 237 Passed good id but bogus port
2017-07-14 11:30:40 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
ok 238 Passed right context
ok 239 Right server
ok 240 No error should be set
ok 241 Ret,ry should be false
ok 242 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 50127
,ok 243 should be equal
# teardown
,2017-07-14 11:30:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8A025A44-AD9A-48D7-A59F-2F0C9E83D78C", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:8A025A44-AD9A-48D7-A59F-2F0C9E83D78C
,2017-07-14 11:30:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-14 11:30:40 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 11:30:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 244 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:30A869D0-4B7C-4223-BAC5-91263E4AAD46
,[ThaliCore] Browser.startListening
,2017-07-14 11:30:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 11:30:40 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-14 11:30:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 245 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2DAB5366-D8ED-405B-840D-3F714804033E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2DAB5366-D8ED-405B-840D-3F714804033E", generation: 0)
2017-07-14 11:30:41 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2DAB5366-D8ED-405B-840D-3F714804033E","generation":0}'
2017-07-14 11:30:41 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2DAB5366-D8ED-405B-840D-3F714804033E, (syncValue: qVwXG85a0vy9bpI6OX77f89BB3HL8Ff4)'
2017-07-14 11:30:41 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "2DAB5366-D8ED-405B-840D-3F714804033E", gen,eration: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2DAB5366-D8ED-405B-840D-3F714804033E", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2DAB5366-D8ED-,4,05B-840D-3F714804033E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:910AB337-4ECA-404D-A728-DA5FDCBE0C94:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 0)
,2017-07-14 11:30:41 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","generation":0}'
,2017-07-14 11:30:41 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 910AB337-4ECA-404D-A728-DA5FDCBE0C94 (syncValue: E0uU9EvTtQDOsxC0MWZqLkmGhSvijMtl)'
,2017-07-14 11:30:41 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:910AB337-4ECA-404D-A728-DA5FDCBE0C94:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:910AB337-4ECA-404D-A728-DA5FDCBE0C94:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:550B4816-A411-482D-84EA-FCB63D5B8EB9
[ThaliCore] Advertiser: session connected Peer(uuid: "8A025A44-AD9A-48D7-A59F-2F0C9E83D78C", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:550B4816-A411-482D-84EA-FCB63D5B8EB9 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BFCFC0A1-B402-43F6-83FD-40A42DC67E29
[ThaliCore] Advertiser: session connected Peer(uuid: "8A025A44-AD9A-48D7-A59F-2F0C9E83D78C", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:BFCFC0A1-B402-43F6-83FD-40A42DC67E29 state: notConnected -> connecting
[ThaliCore] Session.session(_:peer:didChange:) peer:2DAB5366-D8ED-4,05B-840D-3F714804033E:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8A025A44-AD9A-48D7-A59F-2F0C9E83D78C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8A025A44-AD9A-48D7-A59F-2F0C9E83D78C", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:910AB337-4ECA-404D-A728-DA5FDCBE0C94:0
[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BFCFC0A1-B402-43F6-83FD-40A42DC67E29
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:550B4816-A411-482D-84EA-FCB63D5B8EB9
,[ThaliCore] Session.session(_:peer:didChange:) peer:BFCFC0A1-B402-43F6-83FD-40A42DC67E29 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:550B4816-A411-482D-84EA-FCB63D5B8EB9 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:910AB337-4ECA-404D-A728-DA5FDCBE0C94:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50133
,2017-07-14 11:30:44 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"E0uU9EvTtQDOsxC0MWZqLkmGhSvijMtl","error":null,"portNumber":50133}'
,2017-07-14 11:30:44 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'E0uU9EvTtQDOsxC0MWZqLkmGhSvijMtl', error: 'null', listeningPort: '50133''
,2017-07-14 11:30:44 - WARN thaliMobileNativeTestUtils: 'multiConnectResolved received invalid syncValue: 'E0uU9EvTtQDOsxC0MWZqLkmGhSvijMtl', originalSyncValue: 'qVwXG85a0vy9bpI6OX77f89BB3HL8Ff4''
,2017-07-14 11:30:44 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'E0uU9EvTtQDOsxC0MWZqLkmGhSvijMtl', error: 'null', listeningPort: '50133''
,ok 246 should be equal
,ok 247 (unnamed assert)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2DAB5366-D8ED-405B-840D-3F714804033E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:2DAB5366-D8ED-405B-840D-3F714804033E:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "2DAB5366-D8ED-405B-840D-3F714804033E", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50135
,2017-07-14 11:30:44 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"qVwXG85a0vy9bpI6OX77f89BB3HL8Ff4","error":null,"portNumber":50135}'
,2017-07-14 11:30:44 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'qVwXG85a0vy9bpI6OX77f89BB3HL8Ff4', error: 'null', listeningPort: '50135''
,ok 248 should be equal
,# teardown
,[ThaliCore] BrowserManager.disconnect peer:910AB337-4ECA-404D-A728-DA5FDCBE0C94
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50133
[ThaliCore] Session.disconnect,() peer:910AB337-4ECA-404D-A728-DA5FDCBE0C94:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] BrowserManager.disconnect peer:2DAB5366-D8ED-405B-840D-3F714804033E
[ThaliCore] BrowserRelay.closeRelay() dis,connecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50135
[ThaliCore] Session.disconnect() peer:2DAB5366-D8ED-405B-840D-3F714804033E:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket, error:nil
[ThaliCore] Session.session(_:peer:didChange:) peer:910AB337-4ECA-404D-A728-DA5FDCBE0C94:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 0)
[ThaliCor,e,] Browser: session notConnected removed relay for Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 0)
[ThaliCore] Session.session(_:peer:didChange:) peer:2DAB5366-D8ED-405B-840D-3F714804033E:0 state: connected -> notConnected
[ThaliCore] Br,owser: session notConnected Peer(uuid: "2DAB5366-D8ED-405B-840D-3F714804033E", generation: 0)
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "2DAB5366-D8ED-405B-840D-3F714804033E", generation: 0)
2017-07-14 11:30:45 - DEBUG makeIn,toCloseAllServer: 'closeAll called on server'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:550B4816-A411-482D-84EA-FCB63D5B8EB9 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "8A025A44-AD9A-48D7-A59F-2F0C9E83D78C", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:BFCFC0A1-B402-43F6-83FD-40A42DC67E29
,[ThaliCore] Session.deinit peer:BFCFC0A1-B402-43F6-83FD-40A42DC67E29
,# Multiple local http requests
,[ThaliCore] AdvertiserRelay.deinit
,listening on 50137
,ok 249 should be equal
,ok 250 should be equal
,ok 251 should be equal
,# teardown
,2017-07-14 11:30:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8A025A44-AD9A-48D7-A59F-2F0C9E83D78C", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:8A025A44-AD9A-48D7-A59F-2F0C9E83D78C
,2017-07-14 11:30:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 11:30:46 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-14 11:30:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 252 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-14 11:30:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 11:30:46 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 11:30:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 253 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:910AB337-4ECA-404D-A728-DA5FDCBE0C94:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 1)
2017-07-14 11:30:46 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","generation":1}'
2017-07-14 11:30:46 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 910AB337-4ECA-404D-A728-DA5FDCBE0C94, (syncValue: U4IObPNYOh3DfK2ae3U6V9c2LJ83gUxm)'
2017-07-14 11:30:47 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", gen,eration: 1) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 1)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:910AB337-4ECA-,4,04D-A728-DA5FDCBE0C94:1
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8A025A44-AD9A-48D7-A59F-2F0C9E83D78C:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8A025A44-AD9A-48D7-A59F-2F0C9E83D78C", generation: 1)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2DAB5366-D8ED-405B-840D-3F714804033E:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2DAB5366-D8ED-405B-840D-3F714804033E", generation: 1)
2017-07-14 11:30:47 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2DAB5366-D8ED-405B-840D-3F714804033E","generation":1}'
2017-07-14 11:30:47 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2DAB5366-D8ED-405B-840D-3F714804033E, (syncValue: VmeDcE6PA6TtN4XCR3cTAPfIzSHIufQI)'
2017-07-14 11:30:47 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "2DAB5366-D8ED-405B-840D-3F714804033E", gen,eration: 1) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2DAB5366-D8ED-405B-840D-3F714804033E", generation: 1)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2DAB5366-D8ED-,405B-840D-3F714804033E:1
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BFCFC0A1-B402-43F6-83FD-40A42DC67E29
[ThaliCore] Advertiser: session connected Peer(uuid: "8A025A44-AD9A-48D7-A59F-2F0C9E83D78C", generation: 1)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] S,ession.session(_:peer:didChange:) peer:BFCFC0A1-B402-43F6-83FD-40A42DC67E29 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:550B4816-A411-482D-84EA-FCB63D5B8EB9
[ThaliCore] Advertiser: session connected Peer(uuid: "8A025A44-AD9A-48D7-A59F-2F0C9E83D78C", generation: 1)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:550B4816-A411-482D-84EA-FCB63D5B8EB9 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:910AB337-4ECA-404D-A728-DA5FDCBE0C94:1 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:2DAB5366-D8ED-405B-840D-3F714804033E:1 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:550B4816-A411-482D-84EA-FCB63D5B8EB9
,[ThaliCore] Session.session(_:peer:didChange:) peer:550B4816-A411-482D-84EA-FCB63D5B8EB9 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:910AB337-4ECA-404D-A728-DA5FDCBE0C94:1
,[ThaliCore] Session.session(_:peer:didChange:) peer:910AB337-4ECA-404D-A728-DA5FDCBE0C94:1 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 1)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50147
2017-07-14 11:30:50 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"U4IObPNYOh3DfK2ae3U6V9c2LJ83gUxm",,"error":null,"portNumber":50147}'
2017-07-14 11:30:50 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'U4IObPNYOh3DfK2ae3U6V9c2LJ83gUxm', error: 'null', listeningPort: '50147''
2017-07-14 11:30:50 - DEBUG thaliMobileNativeTestUt,ils: 'Got multiConnectResolved -syncValue: 'U4IObPNYOh3DfK2ae3U6V9c2LJ83gUxm', error: 'null', listeningPort: '50147''
2017-07-14 11:30:50 - WARN thaliMobileNativeTestUtils: 'multiConnectResolved received invalid syncValue: 'U4IObPNYOh3DfK2ae3U6V9c2LJ83gU,x,m', originalSyncValue: 'VmeDcE6PA6TtN4XCR3cTAPfIzSHIufQI''
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2DAB5366-D8ED-405B-840D-3F714804033E:1
,ok 254 should be equal
,ok 255 (unnamed assert)
,[ThaliCore] Session.session(_:peer:didChange:) peer:2DAB5366-D8ED-405B-840D-3F714804033E:1 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "2DAB5366-D8ED-405B-840D-3F714804033E", generation: 1)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50149
,2017-07-14 11:30:50 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"VmeDcE6PA6TtN4XCR3cTAPfIzSHIufQI","error":null,"portNumber":50149}'
,2017-07-14 11:30:50 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'VmeDcE6PA6TtN4XCR3cTAPfIzSHIufQI', error: 'null', listeningPort: '50149''
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BFCFC0A1-B402-43F6-83FD-40A42DC67E29
,ok 256 should be equal
,# teardown
,[ThaliCore] Session.session(_:peer:didChange:) peer:BFCFC0A1-B402-43F6-83FD-40A42DC67E29 state: connecting -> connected
,[ThaliCore] BrowserManager.disconnect peer:910AB337-4ECA-404D-A728-DA5FDCBE0C94
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50147
[ThaliCore] Session.disconnect() peer:910AB337-4ECA-404D-A728-DA5FDCBE0C94:1
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] BrowserManager.disconnect peer:2DAB5366-D8ED-405B-840D-3F714804033E
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50149
[ThaliCore] Session.disconnect,() peer:2DAB5366-D8ED-405B-840D-3F714804033E:1
,[ThaliCore] Session.session(_:peer:didChange:) peer:910AB337-4ECA-404D-A728-DA5FDCBE0C94:1 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 1)
[ThaliCore] Browser: s,ession notConnected removed relay for Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 1)
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] Session.session(_:peer:didChange:) peer:2DAB5366-D8ED,-405B-840D-3F714804033E:1 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "2DAB5366-D8ED-405B-840D-3F714804033E", generation: 1)
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "2DAB5366-D8ED-4,05B-840D-3F714804033E", generation: 1)
2017-07-14 11:30:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:550B4816-A411-482D-84EA-FCB63D5B8EB9 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "8A025A44-AD9A-48D7-A59F-2F0C9E83D78C", generation: 1)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:550B4816-A411-482D-84EA-FCB63D5B8EB9
[ThaliCore] Advert,iserRelay.deinit
[ThaliCore] Session.deinit peer:550B4816-A411-482D-84EA-FCB63D5B8EB9
,[ThaliCore] Session.session(_:peer:didChange:) peer:BFCFC0A1-B402-43F6-83FD-40A42DC67E29 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "8A025A44-AD9A-48D7-A59F-2F0C9E83D78C", generation: 1)
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# #startListeningForAdvertisements should fail if start not called
,ok 257 specific error should be returned
,# teardown
,ok 258 must be stopped
,# setup
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 259 specific error should be returned
,# teardown
,ok 260 must be stopped
,# setup
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'listening 50151'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-14 11:30:52 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 11:30:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 261 no errors
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-14 11:30:52 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 11:30:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 262 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:30:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 263 must be stopped
,# setup
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# should be able to call #startListeningForAdvertisements many times
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'listening 50152'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A1E43C3E-58F3-4073-B9F0-E7B748ECC146
,[ThaliCore] Browser.startListening
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:30:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 11:30:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 264 no errors
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:30:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 11:30:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 265 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 11:30:52 - INFO thaliMobile: 'Received state ({"d,iscoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:30:52 - INFO ,thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:30:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-14 11:30:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 266 must be stopped
,# setup
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:30:52 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'listening 50153'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "830F058B-B2E4-4A02-8070-6A5BA8667458", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:830F058B-B2E4-4A02-8070-6A5BA8667458
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-14 11:30:53 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 11:30:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 267 no errors
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "830F058B-B2E4-4A02-8070-6A5BA8667458", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:830F058B-B2E4-4A02-8070-6A5BA8667458
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-14 11:30:53 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 11:30:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 268 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:30:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 269 must be stopped
,# setup
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'listening 50156'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 270 no errors
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 271 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:30:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 272 must be stopped
,# setup
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# can get the network status before starting
,ok 273 network status should have certain non-empty properties
,# teardown
,ok 274 must be stopped
,# setup
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 11:30:53 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# error returned with bad router
,2017-07-14 11:30:53 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
ok 275 specific error expected
,# teardown
,ok 276 must be stopped
,# setup
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 11:30:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# all services are started when we call start
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'listening 50157'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:060905D2-8696-48C0-B378-B27DB6B3019C
[ThaliCore] Browser.st,artListening
2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 11:30:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:30:54 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "35983C28-0CB4-4811-A600-3B46F13681C2", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,35983C28-0CB4-4811-A600-3B46F13681C2
2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 11:30:54 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:30:54 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2DAB5366-D8ED-405B-840D-3F714804033E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2DAB5366-D8ED-405B-840D-3F714804033E", generation: 0)
,ok 277 all connection succeed
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2DAB5366-D8ED-405B-840D-3F714804033E:1
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2DAB5366-D8ED-405B-840D-3F714804033E", generation: 1)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:910AB337-4ECA-404D-A728-DA5FDCBE0C94:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 0)
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2DAB5366-D8ED-405B-840D-3F714804033E","generation":0}]'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"2DAB5366-D8ED-405B-840D-3F714804033E","generation":0}'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2DAB5366-D8ED-405B-840D-3F714804033E","generation":1}]'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"2DAB5366-D8ED-405B-840D-3F714804033E","generation":1}'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","generation":0}]'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","generation":0}'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2DAB5366-D8ED-405B-840D-3F714804033E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 11:30:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2DAB5366-D8ED-405B-840D-3F714804033E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2DAB5366-D8ED-405B-840D-3F714804033E","peerAvailable":true,"generation":1,"portNumber":null}'
,2017-07-14 11:30:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2DAB5366-D8ED-405B-840D-3F714804033E","connectionType":"MPCF","peerAvailable":true,"generation":1,"newAddressPort":false}'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 11:30:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:30:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 11:30:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:30:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 278 must be stopped
,# setup
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# TCP Servers Manager should be null when we call start on iOS
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'listening 50160'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3D2BAE5B-E844-462D-B9CA-E1B8B3FBE444
,[ThaliCore] Browser.startListening
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:30:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 11:30:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B5DEBD25-5CDC-4571-B654-F84DF897386B", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:B5DEBD25-5CDC-4571-B654-F84DF897386B
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 11:30:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-14 11:30:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 279 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:30:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 11:30:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:30:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 280 must be stopped
,# setup
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# all services are stopped when we call stop
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'listening 50162'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:EC253843-F9BC-42C0-8023-94401DFD7534
[ThaliCore] Browser.startListening
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:30:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 11:30:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F0E644FD-95D1-4DFF-8B3E-8EE35347461D", genera,tion: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:F0E644FD-95D1-4DFF-8B3E-8EE35347461D
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 11:30:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-14 11:30:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 11:30:5,5 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkT,ype":null}})'
,2017-07-14 11:30:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14, 11:30:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:30:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 281 is stopped after calling stop
,ok 282 connection should fail after stopping
,# teardown
,ok 283 must be stopped
,# setup
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# make sure terminateConnection is properly hooked up
,2017-07-14 11:30:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
,# teardown
,ok 284 must be stopped
,# setup
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# make sure terminateConnection is return error if we get called on iOS
,ok 285 error description matches
,# teardown
,ok 286 must be stopped
,# setup
,2017-07-14 11:30:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:30:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:30:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 11:30:56 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 11:30:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 11:30:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 11:30:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# make sure terminateListener is properly hooked up
,2017-07-14 11:30:56 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 287 must be stopped
,# setup
,2017-07-14 11:30:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# make sure terminateListener is return error if we get called on iOS
,ok 288 error description matches
,# teardown
,ok 289 must be stopped
,# setup
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# make sure we actually call kill connections properly
,ok 290 IMPLEMENT ME!!!!!!
,# teardown
,ok 291 must be stopped
,# setup
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-07-14 11:30:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 292 must be stopped
,# setup
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:30:57 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 11:30:57 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-07-14 11:30:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 293 must be stopped
,# setup
,2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 11:30:58 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-07-14 11:30:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 294 must be stopped
,# setup
,2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:30:58 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 11:30:58 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-07-14 11:30:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 295 must be stopped
,# setup
,2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:30:58 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 11:30:58 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 296 NOT IMPLEMENTED # SKIP
,# teardown
,ok 297 must be stopped
,# setup
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 11:30:59 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# make sure bad PSK connections fail
,2017-07-14 11:30:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 298 must be stopped
,# setup
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:30:59 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 11:30:59 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# peer changes handled from a queue
,2017-07-14 11:30:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 299 must be stopped
,# setup
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-07-14 11:30:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 300 must be stopped
,# setup
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:30:59 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 11:30:59 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-07-14 11:30:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 301 must be stopped
,# setup
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'listening 50165'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A0F93348-55CD-4A11-941D-265BD389A4FC
,[ThaliCore] Browser.startListening
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:31:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 11:31:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 302 discoveryActive matches
,ok 303 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:31:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 11:31:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 304 discoveryActive matches
,ok 305 advertisingActive matches
,2017-07-14 11:31:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'listening 50166'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D037C6D6-379A-4DBB-AD30-F8DF21F1D565", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:D037C6D6-379A-4DBB-AD30-F8DF21F1D565
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-14 11:31:00 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 11:31:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 306 discoveryActive matches
,ok 307 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 308 discoveryActive matches
,ok 309 advertisingActive matches
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:31:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'listening 50168'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:31:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 310 must be stopped
,# setup
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:31:00 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 11:31:00 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'listening 50169'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D77C4688-CE8B-4D4E-99D6-C5A8EEAD3BBE
[ThaliCore] Browser.st,artListening
2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 11:31:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:31:00 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F399F98B-FAC2-426D-8484-6C982AFD447C", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:,F399F98B-FAC2-426D-8484-6C982AFD447C
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 11:31:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:31:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:910AB337-4ECA-404D-A728-DA5FDCBE0C94:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 0)
2017-07-14 11:31:01 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","generation":0}]'
2017-07-14 11:31:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47:0
[ThaliCore] BrowserMana,ger.foundPeerHandler peer:Peer(uuid: "8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47", generation: 0)
,2017-07-14 11:31:01 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","peerAvailable":true,"generation":0,"portNumber":null}'
ok 311 portNumber equal null
,# teardown
,2017-07-14 11:31:01 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47","generation":0}]'
,2017-07-14 11:31:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47","generation":0}'
,2017-07-14 11:31:01 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 11:31:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 11:31:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:31:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 11:31:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 11:31:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:31:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 312 must be stopped
,# setup
,2017-07-14 11:31:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:31:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:31:02 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:31:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 11:31:02 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 11:31:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 11:31:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 11:31:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# can do HTTP requests between peers
,2017-07-14 11:31:02 - DEBUG thaliMobileNativeWrapper: 'listening 50171'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4DBF6215-1DC7-4E8A-956F-2B203C76E46B
,[ThaliCore] Browser.startListening
,2017-07-14 11:31:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:31:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47:0
2017-07-14 11:31:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.foundP,eerHandler peer:Peer(uuid: "8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47", generation: 0)
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D08813FF-67B9-418D-ADC2-3A899BCA976D", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:D08813FF-67B9-418D-ADC2-3A899BCA976D
,2017-07-14 11:31:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 11:31:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:31:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:910AB337-4ECA-404D-A728-DA5FDCBE0C94:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation:, 0)
2017-07-14 11:31:02 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47","generation":0}]'
,2017-07-14 11:31:02 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47","generation":0}'
,2017-07-14 11:31:02 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","generation":0}]'
,2017-07-14 11:31:02 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","generation":0}'
,2017-07-14 11:31:02 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 11:31:02 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 11:31:02 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47 (syncValue: 9VdZaZ47WENgWLK453o4RdrhkrWdmE3E)'
,2017-07-14 11:31:02 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-14 11:31:02 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 11:31:02 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D08813FF-67B9-418D-ADC2-3A899BCA976D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D08813FF-67B9-418D-ADC2-3A899BCA976D", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:30EEEF58-6F93-47A9-AFF1-D262152011B0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "30EEEF58-6F93-47A9-AFF1-D262152011B0", generation: 0)
,2017-07-14 11:31:03 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"30EEEF58-6F93-47A9-AFF1-D262152011B0","generation":0}]'
,2017-07-14 11:31:03 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"30EEEF58-6F93-47A9-AFF1-D262152011B0","generation":0}'
,2017-07-14 11:31:03 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"30EEEF58-6F93-47A9-AFF1-D262152011B0","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 11:31:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"30EEEF58-6F93-47A9-AFF1-D262152011B0","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 11:31:03 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"30EEEF58-6F93-47A9-AFF1-D262152011B0","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:117A1A18-8269-454A-B098-B1D2BC0CA557:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "117A1A18-8269-454A-B098-B1D2BC0CA557", generation: 0)
2017-07-14 11:31:03 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"117A1A18-8269-454A-B098-B1D2BC0CA557","generation":0}]'
2017-07-14 11:31:03 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"117A1A18-8269-454A-B098-B1D2BC0CA557","generation":0}'
,2017-07-14 11:31:03 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"117A1A18-8269-454A-B098-B1D2BC0CA557","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-14 11:31:03 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"117A1A18-8269-454A-B098-B1D2BC0CA557","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-14 11:31:03 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"117A1A18-8269-454A-B098-B1D2BC0CA557","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:910AB337-4ECA-404D-A728-DA5FDCBE0C94:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47", generation: 0)
[ThaliCore] Session.disconnect() peer:8EFC9B37-2EB,6-44D0-BD7D-7C8AC4629A47:0
2017-07-14 11:31:07 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47","generation":0}]'
2017-07-14 11:31:,07 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47","generation":0}'
,2017-07-14 11:31:07 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-14 11:31:07 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47", genera,tion: 0)
2017-07-14 11:31:08 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9VdZaZ47WENgWLK453o4RdrhkrWdmE3E","error":"Connection could not be established","portNumber":null}'
2017-07-14 11:31:08 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: '9VdZaZ47WENgWLK453o4RdrhkrWdmE3E', error: 'Connection could not be established', listeningPort: '%s''
2017-07-14 11:31:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 11:31:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"8EFC9B37-2EB6-44D0-BD7D-7C8AC4,629A47","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 11:31:08 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-14 11:31:08 - DEBUG thali,MobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-14 11:31:08 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peer,Identifier":"8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] BrowserManager.disconnect peer:8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47
2017-07-14 11:31:08 - ERROR thaliMobileNativeTestUtils: 'Fatal co,nnect error: 'Connection could not be established''
2017-07-14 11:31:08 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 910AB337-4ECA-404D-A728-DA5FDCBE0C94 (syncValue: jGBKW9VS84IC0m3kN1BKJqOBtHgysmWU)'
2017-07-14 11:31:08 - DEBUG thaliMo,b,ileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 1) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:session,NotConnected:) Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 1)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) error:unavailablePeer
,2017-07-14 11:31:08 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"jGBKW9VS84IC0m3kN1BKJqOBtHgysmWU","error":"Peer is unavailable","portNumber":null}'
,2017-07-14 11:31:08 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'jGBKW9VS84IC0m3kN1BKJqOBtHgysmWU', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-14 11:31:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-14 11:31:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-14 11:31:08 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-14 11:31:08 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 30EEEF58-6F93-47A9-AFF1-D262152011B0 (syncValue: oHBTZtKoTMEJ17HKbSdl5GqlwXPe7wNy)'
,2017-07-14 11:31:08 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "30EEEF58-6F93-47A9-AFF1-D262152011B0", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "30EEEF58-6F93-47A9-AFF1-D262152011B0", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:30EEEF58-6F93-47A9-AFF1-D262152011B0:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-14 11:31:08 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-14 11:31:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 11:31:08 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-14 11:31:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 11:31:08 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E535493C-3400-4063-8945-B413DD99AE3B
[ThaliCore] Advertiser: session connected Peer(uuid: "D08813FF-67B9-418D-ADC2-3A899BCA976D", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:E535493C-3400-4063-8945-B413DD99AE3B state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B79ED0FF-746F-4619-8CC2-79625CF85DCD
[ThaliCore] Advertiser: session connected Peer(uuid: "D08813FF-67B9-418D-ADC2-3A899BCA976D", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:B79ED0FF-746F-4619-8CC2-79625CF85DCD state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:30EEEF58-6F93-47A9-AFF1-D262152011B0:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E535493C-3400-4063-8945-B413DD99AE3B
,[ThaliCore] Session.session(_:peer:didChange:) peer:E535493C-3400-4063-8945-B413DD99AE3B state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:30EEEF58-6F93-47A9-AFF1-D262152011B0:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:30EEEF58-6F93-47A9-AFF1-D262152011B0:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "30EEEF58-6F93-47A9-AFF1-D262152011B0", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50176
,2017-07-14 11:31:12 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"oHBTZtKoTMEJ17HKbSdl5GqlwXPe7wNy","error":null,"portNumber":50176}'
,2017-07-14 11:31:12 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'oHBTZtKoTMEJ17HKbSdl5GqlwXPe7wNy', error: 'null', listeningPort: '50176''
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E535493C-3400-4063-8945-B413DD99AE3B
[ThaliCore] Session.startOutputStream(with:) peer:E535493C-3400-4063-8945-B413DD99AE3B
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,9 [4, 9, 15, 19]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-14 11:31:12 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:30EEEF58-6F93-47A9-AFF1-D262152011B0:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:30EEEF58-6F93-47A9-AFF1-D262152011B0:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [4, 9, 15, 19, 20]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B79ED0FF-746F-4619-8CC2-79625CF85DCD
,[ThaliCore] Session.session(_:peer:didChange:) peer:B79ED0FF-746F-4619-8CC2-79625CF85DCD state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B79ED0FF-746F-4619-8CC2-79625CF85DCD
[ThaliCore] Session.startOutputStream(with:) peer:B79ED0FF-746F-4619-8CC2-79625CF85DCD
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:21 [4, 9, 15, 19, 20, 21]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-14 11:31:12 - DEBUG testUtils: 'Got response data'
,2017-07-14 11:31:12 - DEBUG testUtils: 'Got end'
,ok 313 response body should match testData
,ok 314 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 11:31:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:31:12 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 11:31:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 11:31:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:31:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:21
[ThaliCore] VirtualSocket.closeStreams() vsID:21
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:21
[ThaliCore] VirtualSocket.deinit vsID:21 [4, 9, 15, 19, 20]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:19
[ThaliCore] VirtualSocket.closeStreams() vsID:19
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:19
[ThaliCore] VirtualSocket.deinit vsID:19 [4, 9, 15, 20]
,ok 315 must be stopped
,[ThaliCore] BrowserManager.disconnect peer:30EEEF58-6F93-47A9-AFF1-D262152011B0
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50176
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] VirtualSocket.closeStreams() vsID:20
,[ThaliCore] VirtualSocket exited RunLoop vsID:20
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:true
,[ThaliCore] VirtualSocket.deinit vsID:20 [4, 9, 15]
,[ThaliCore] Session.disconnect() peer:30EEEF58-6F93-47A9-AFF1-D262152011B0:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:30EEEF58-6F93-47A9-AFF1-D262152011B0:0 state: connected -> notConnected
,[ThaliCore] Browser: session notConnected Peer(uuid: "30EEEF58-6F93-47A9-AFF1-D262152011B0", generation: 0)
,[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "30EEEF58-6F93-47A9-AFF1-D262152011B0", generation: 0)
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:B79ED0FF-746F-4619-8CC2-79625CF85DCD state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "D08813FF-67B9-418D-ADC2-3A899BCA976D", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:B79ED0FF-746F-4619-8CC2-79625CF85DCD
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:B79ED0FF-746F-4619-8CC2-79625CF85DCD
,[ThaliCore] Session.session(_:peer:didChange:) peer:E535493C-3400-4063-8945-B413DD99AE3B state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "D08813FF-67B9-418D-ADC2-3A899BCA976D", generation: 0)
,2017-07-14 11:31:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:31:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:31:12 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:31:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 11:31:12 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 11:31:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 11:31:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 11:31:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# can still do HTTP requests between peers with coordinator
,2017-07-14 11:31:13 - DEBUG thaliMobileNativeWrapper: 'listening 50180'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:00AD4566-99CB-40F7-8BED-6FACD03A9D0E
[ThaliCore] Browser.st,artListening
2017-07-14 11:31:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 11:31:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:31:13 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "49D2AE96-57F9-4114-BFBB-AC26386E4157", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,49D2AE96-57F9-4114-BFBB-AC26386E4157
,2017-07-14 11:31:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 11:31:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:31:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:30EEEF58-6F93-47A9-AFF1-D262152011B0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "30EEEF58-6F93-47A9-AFF1-D262152011B0", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:117A1A18-8269-454A-B098-B1D2BC0CA557:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "117A1A18-8269-454A-B098-B1D2BC0CA557", generation: 0)
2017-07-14 11:31:13 - DEBUG thaliMobileNativeWrapper: 'Rec,eived peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"30EEEF58-6F93-47A9-AFF1-D262152011B0","generation":0}]'
,2017-07-14 11:31:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"30EEEF58-6F93-47A9-AFF1-D262152011B0","generation":0}'
,2017-07-14 11:31:13 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"117A1A18-8269-454A-B098-B1D2BC0CA557","generation":0}]'
2017-07-14 11:31:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"117A1A18-8269-454A-B098-B1D2BC0CA557","generation":0}'
,2017-07-14 11:31:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"30EEEF58-6F93-47A9-AFF1-D262152011B0","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 11:31:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"30EEEF58-6F93-47A9-AFF1-D262152011B0","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 11:31:13 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 30EEEF58-6F93-47A9-AFF1-D262152011B0 (syncValue: 07Rv4ArET7Co9A3ANBBKOpYdKJI8SoVs)'
,2017-07-14 11:31:13 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "30EEEF58-6F93-47A9-AFF1-D262152011B0", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "30EEEF58-6F93-47A9-AFF1-D262152011B0", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:30EEEF58-6F93-47A9-AFF1-D262152011B0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-14 11:31:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"117A1A18-8269-454A-B098-B1D2BC0CA557","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 11:31:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"117A1A18-8269-454A-B098-B1D2BC0CA557","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4058EBCF-2389-4A80-8739-3BC964E93946:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4058EBCF-2389-4A80-8739-3BC964E93946", generation: 0)
2017-07-14 11:31:14 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"4058EBCF-2389-4A80-8739-3BC964E93946","generation":0}]'
2017-07-14 11:31:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"4058EBCF-2389-4A80-8739-3BC964E93946","generation":0}'
,2017-07-14 11:31:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"4058EBCF-2389-4A80-8739-3BC964E93946","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-14 11:31:14 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4058EBCF-2389-4A80-8739-3BC964E93946","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-14 11:31:14 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"4058EBCF-2389-4A80-8739-3BC964E93946","peerAvailable":true,"generation":0,"portNumber":null}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:75A74F2C-36D7-4F68-A621-7E4E5356421E:0
[ThaliCore] BrowserManager.f,oundPeerHandler peer:Peer(uuid: "75A74F2C-36D7-4F68-A621-7E4E5356421E", generation: 0)
,2017-07-14 11:31:14 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"75A74F2C-36D7-4F68-A621-7E4E5356421E","generation":0}]'
,2017-07-14 11:31:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"75A74F2C-36D7-4F68-A621-7E4E5356421E","generation":0}'
,2017-07-14 11:31:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"75A74F2C-36D7-4F68-A621-7E4E5356421E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 11:31:14 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"75A74F2C-36D7-4F68-A621-7E4E5356421E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 11:31:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"75A74F2C-36D7-4F68-A621-7E4E5356421E","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:49D2AE96-57F9-4114-BFBB-AC26386E4157:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "49D2AE96-57F9-4114-BFBB-AC26386E4157", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:30EEEF58-6F93-47A9-AFF1-D262152011B0:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "30EEEF58-6F93-47A9-AFF1-D262152011B0", generation: 0)
[ThaliCore] Session.disconnect() peer:30EEEF58-6F9,3-47A9-AFF1-D262152011B0:0
2017-07-14 11:31:16 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"30EEEF58-6F93-47A9-AFF1-D262152011B0","generation":0}]'
2017-07-14 11:31:,16 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"30EEEF58-6F93-47A9-AFF1-D262152011B0","generation":0}'
,2017-07-14 11:31:16 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"30EEEF58-6F93-47A9-AFF1-D262152011B0","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-14 11:31:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"30EEEF58-6F93-47A9-AFF1-D262152011B0","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:30EEEF58-6F93-47A9-AFF1-D262152011B0:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "30EEEF58-6F93-47A9-AFF1-D262152011B0", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:30EEEF58-6F93-47A9-AFF1-D262152011B0:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "30EEEF58-6F93-47A9-AFF1-D262152011B0", genera,tion: 0)
2017-07-14 11:31:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"07Rv4ArET7Co9A3ANBBKOpYdKJI8SoVs","error":"Connection could not be established","portNumber":null}'
2017-07-14 11:31:19 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: '07Rv4ArET7Co9A3ANBBKOpYdKJI8SoVs', error: 'Connection could not be established', listeningPort: '%s''
2017-07-14 11:31:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"30EEEF58-6F93-47A9-AFF1-D262152011B0","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 11:31:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"30EEEF58-6F93-47A9-AFF1-D26215,2011B0","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 11:31:19 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"30EEEF58-6F93-47A9-AFF1-D262152011B0","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-14 11:31:19 - DEBUG thali,MobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"30EEEF58-6F93-47A9-AFF1-D262152011B0","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-14 11:31:19 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peer,Identifier":"30EEEF58-6F93-47A9-AFF1-D262152011B0","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] BrowserManager.disconnect peer:30EEEF58-6F93-47A9-AFF1-D262152011B0
2017-07-14 11:31:19 - ERROR thaliMobileNativeTestUtils: 'Fatal co,nnect error: 'Connection could not be established''
2017-07-14 11:31:19 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 117A1A18-8269-454A-B098-B1D2BC0CA557 (syncValue: cbWoeYqEg4lmxorXc33uk7G9iGF7DVVK)'
2017-07-14 11:31:19 - DEBUG thaliMo,b,ileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "117A1A18-8269-454A-B098-B1D2BC0CA557", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:session,NotConnected:) Peer(uuid: "117A1A18-8269-454A-B098-B1D2BC0CA557", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:117A1A18-8269-454A-B098-B1D2BC0CA557:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtu,alSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:117A1A18-8269-454A-B098-B1D2BC0CA557:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "117A1A18-8269-454A-B098-B1D2BC0CA557", generation: 0)
[ThaliCore] Session.disconnect() peer:117A1A18-826,9-454A-B098-B1D2BC0CA557:0
2017-07-14 11:31:22 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"117A1A18-8269-454A-B098-B1D2BC0CA557","generation":0}]'
2017-07-14 11:31:,22 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"117A1A18-8269-454A-B098-B1D2BC0CA557","generation":0}'
,2017-07-14 11:31:22 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"117A1A18-8269-454A-B098-B1D2BC0CA557","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-14 11:31:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"117A1A18-8269-454A-B098-B1D2BC0CA557","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:117A1A18-8269-454A-B098-B1D2BC0CA557:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "117A1A18-8269-454A-B098-B1D2BC0CA557", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:117A1A18-8269-454A-B098-B1D2BC0CA557:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "117A1A18-8269-454A-B098-B1D2BC0CA557", genera,tion: 0)
2017-07-14 11:31:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"cbWoeYqEg4lmxorXc33uk7G9iGF7DVVK","error":"Connection could not be established","portNumber":null}'
2017-07-14 11:31:24 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'cbWoeYqEg4lmxorXc33uk7G9iGF7DVVK', error: 'Connection could not be established', listeningPort: '%s''
2017-07-14 11:31:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"117A1A18-8269-454A-B098-B1D2BC0CA557","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 11:31:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"117A1A18-8269-454A-B098-B1D2BC,0CA557","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 11:31:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"117A1A18-8269-454A-B098-B1D2BC0CA557","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-14 11:31:24 - DEBUG thali,MobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"117A1A18-8269-454A-B098-B1D2BC0CA557","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-14 11:31:24 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peer,Identifier":"117A1A18-8269-454A-B098-B1D2BC0CA557","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] BrowserManager.disconnect peer:117A1A18-8269-454A-B098-B1D2BC0CA557
2017-07-14 11:31:24 - ERROR thaliMobileNativeTestUtils: 'Fatal co,nnect error: 'Connection could not be established''
2017-07-14 11:31:24 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4058EBCF-2389-4A80-8739-3BC964E93946 (syncValue: Oy4RfqPNSXT6iRHNyRARzq75nY6cKt6c)'
2017-07-14 11:31:24 - DEBUG thaliMo,b,ileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "4058EBCF-2389-4A80-8739-3BC964E93946", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:session,NotConnected:) Peer(uuid: "4058EBCF-2389-4A80-8739-3BC964E93946", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4058EBCF-2389-4A80-8739-3BC964E93946:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtu,alSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:4058EBCF-2389-4A80-8739-3BC964E93946:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4058EBCF-2389-4A80-8739-3BC964E93946:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:4058EBCF-2389-4A80-8739-3BC964E93946:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "4058EBCF-2389-4A80-8739-3BC964E93946", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50187
2017-07-14 11:31:28 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Oy4RfqPNSXT6iRHNyRARzq75nY6cKt6c",,"error":null,"portNumber":50187}'
2017-07-14 11:31:28 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Oy4RfqPNSXT6iRHNyRARzq75nY6cKt6c', error: 'null', listeningPort: '50187''
,2017-07-14 11:31:28 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:4058EBCF-2389-4A80-8739-3BC964E93946:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4058EBCF-2389-4A80-8739-3BC964E93946:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:22 [4, 9, 15, 22]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 11:31:28 - DEBUG testUtils: 'Got response data'
2017-07-14 11:31:28 - DEBUG testUtils: 'Got end'
ok 316 response body should match testData
ok 317 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-14 11:31:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 11:31:2,9 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkT,ype":null}})'
2017-07-14 11:31:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 11:31:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:31:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-14 11:31:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 318 must be stopped
[ThaliCore] BrowserManager.disconnect peer:4058EBCF-2389-4A80-8739-3BC964E93946
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliC,ore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50187
[ThaliCore] VirtualSocket.closeStreams() vsID:22
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] BrowserRelay.didCloseVirtualS,ocketStreamsHandler disconnecting:true
[ThaliCore] Session.disconnect() peer:4058EBCF-2389-4A80-8739-3BC964E93946:0
[ThaliCore] VirtualSocket exited RunLoop vsID:22
[ThaliCore] VirtualSocket.deinit vsID:22 [4, 9, 15]
[ThaliCore] Session.session(_:peer,:,didChange:) peer:4058EBCF-2389-4A80-8739-3BC964E93946:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "4058EBCF-2389-4A80-8739-3BC964E93946", generation: 0)
[ThaliCore] Browser: session notConnected removed relay f,or Peer(uuid: "4058EBCF-2389-4A80-8739-3BC964E93946", generation: 0)
,# setup
,2017-07-14 11:31:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:31:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:31:29 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:31:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 11:31:29 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 11:31:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 11:31:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 11:31:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# calls correct starts when network changes
,2017-07-14 11:31:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'calls correct starts when network changes''
,# teardown
,ok 319 must be stopped
,# setup
,2017-07-14 11:31:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:31:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:31:30 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:31:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 11:31:30 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 11:31:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 11:31:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 11:31:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# test to coordinate connection cut
,# teardown
,ok 320 must be stopped
,# setup
,2017-07-14 11:31:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:31:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:31:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:31:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 11:31:31 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 11:31:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 11:31:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 11:31:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# can do HTTP requests after connections are cut
,2017-07-14 11:31:31 - DEBUG thaliMobileNativeWrapper: 'listening 50189'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:EFCB72AE-302D-4AF9-B318-135AFB3418A3
,[ThaliCore] Browser.startListening
,2017-07-14 11:31:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:31:31 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 11:31:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D5043C6C-65B0-4F29-8A29-F635EBFE335E", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:D5043C6C-65B0-4F29-8A29-F635EBFE335E
,2017-07-14 11:31:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 11:31:31 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-14 11:31:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4058EBCF-2389-4A80-8739-3BC964E93946:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4058EBCF-2389-4A80-8739-3BC964E93946", generation: 0)
2017-07-14 11:31:31 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"4058EBCF-2389-4A80-8739-3BC964E93946","generation":0}]'
2017-07-14 11:31:31 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"4058EBCF-2389-4A80-8739-3BC964E93946","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:75A74F2C-36D7-4F68-A621-7E4E5356421E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "75A74F2C-36D7-4F68-A621-7E4E5356421E", generation: 0)
2017-07-14 11:31:31 - DEBUG t,haliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"4058EBCF-2389-4A80-8739-3BC964E93946","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-14 11:31:31 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"pe,erIdentifier":"4058EBCF-2389-4A80-8739-3BC964E93946","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-14 11:31:31 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4058EBCF-2389-4A80-8739-3BC964E93946 (syncValue: JS9bdM6t2QjZ3mS,y6HGdDV7WXkZHPf0z)'
2017-07-14 11:31:31 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "4058EBCF-2389-4A80-8739-3BC964E93946", generation: 0) new relay
[Thal,iCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4058EBCF-2389-4A80-8739-3BC964E93946", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4058EBCF-2389-4A80-8739-3BC964E93946:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-14 11:31:31 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"75A74F2C-36D7-4F68-A621-7E4E5356421E","generation":0}]'
2017-07-14 11:31:31 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"75A74F2C-36D7-4F68-A621-7E4E5356421E","generation":0}'
,2017-07-14 11:31:31 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"75A74F2C-36D7-4F68-A621-7E4E5356421E","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-14 11:31:31 - DEBUG thaliMobileNativeT,estUtils: 'We got a peer {"peerIdentifier":"75A74F2C-36D7-4F68-A621-7E4E5356421E","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E89525DA-D2AA-454F-878F-E377A11FB974:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E89525DA-D2AA-454F-878F-E377A11FB974", generation: 0)
,2017-07-14 11:31:32 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"E89525DA-D2AA-454F-878F-E377A11FB974","generation":0}]'
,2017-07-14 11:31:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"E89525DA-D2AA-454F-878F-E377A11FB974","generation":0}'
,2017-07-14 11:31:32 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"E89525DA-D2AA-454F-878F-E377A11FB974","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 11:31:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"E89525DA-D2AA-454F-878F-E377A11FB974","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 11:31:32 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"E89525DA-D2AA-454F-878F-E377A11FB974","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E", generation: 0)
2017-07-14 11:31:32 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E","generation":0}]'
2017-07-14 11:31:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E","generation":0}'
,2017-07-14 11:31:32 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 11:31:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 11:31:32 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D5043C6C-65B0-4F29-8A29-F635EBFE335E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D5043C6C-65B0-4F29-8A29-F635EBFE335E", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:4058EBCF-2389-4A80-8739-3BC964E93946:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "4058EBCF-2389-4A80-8739-3BC964E93946", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:4058EBCF-2389-4A80-8739-3BC964E93946:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "4058EBCF-2389-4A80-8739-3BC964E93946", genera,tion: 0)
2017-07-14 11:31:37 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"JS9bdM6t2QjZ3mSy6HGdDV7WXkZHPf0z","error":"Connection could not be established","portNumber":null}'
2017-07-14 11:31:37 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'JS9bdM6t2QjZ3mSy6HGdDV7WXkZHPf0z', error: 'Connection could not be established', listeningPort: '%s''
2017-07-14 11:31:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"4058EBCF-2389-4A80-8739-3BC964E93946","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 11:31:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"4058EBCF-2389-4A80-8739-3BC964E93946","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-14 11:31:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"4058EBCF-2389-4A80-8739-3BC964E93946","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-14 11:31:37 - DEBUG thali,Mobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"4058EBCF-2389-4A80-8739-3BC964E93946","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-14 11:31:37 - DEBUG thaliMobileNati,veWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"4058EBCF-2389-4A80-8739-3BC964E93946","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-14 11:31:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChang,ed from handleRecreatedPeer {"peerIdentifier":"4058EBCF-2389-4A80-8739-3BC964E93946","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-14 11:31:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentif,i,er":"4058EBCF-2389-4A80-8739-3BC964E93946","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-14 11:31:37 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-14 11:31:37 -, DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 75A74F2C-36D7-4F68-A621-7E4E5356421E (syncValue: NJtrxEkdYWQMB6bJdYffwOfuYcs1US93)'
2017-07-14 11:31:37 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserMana,ger.connectToPeer(_:syncValue:completion:) Peer(uuid: "75A74F2C-36D7-4F68-A621-7E4E5356421E", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "75A74F2C-36D7-4F68-A621-7E4E5356421E", generati,on: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:75A74F2C-36D7-4F68-A621-7E4E5356421E:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:4058EBCF-2389-4A80-8739-3BC964E93946:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "4058EBCF-2389-4A80-8739-3BC964E93946", generation: 0)
2017-07-14 11:31:38 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"4058EBCF-2389-4A80-8739-3BC964E93946","generation":0}]'
2017-07-14 11:31:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"4058EBCF-2389-4A80-8739-3BC964E93946","generation":0}'
,2017-07-14 11:31:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"4058EBCF-2389-4A80-8739-3BC964E93946","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-14 11:31:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4058EBCF-2389-4A80-8739-3BC964E93946","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:75A74F2C-36D7-4F68-A621-7E4E5356421E:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "75A74F2C-36D7-4F68-A621-7E4E5356421E", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:75A74F2C-36D7-4F68-A621-7E4E5356421E:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "75A74F2C-36D7-4F68-A621-7E4E5356421E", genera,tion: 0)
2017-07-14 11:31:42 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"NJtrxEkdYWQMB6bJdYffwOfuYcs1US93","error":"Connection could not be established","portNumber":null}'
2017-07-14 11:31:42 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'NJtrxEkdYWQMB6bJdYffwOfuYcs1US93', error: 'Connection could not be established', listeningPort: '%s''
2017-07-14 11:31:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"75A74F2C-36D7-4F68-A621-7E4E5356421E","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 11:31:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"75A74F2C-36D7-4F68-A621-7E4E53,56421E","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-14 11:31:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"75A74F2C-36D7-4F68-A621-7E4E5356421E","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-14 11:31:42 - DEBUG thali,Mobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"75A74F2C-36D7-4F68-A621-7E4E5356421E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-14 11:31:42 - DEBUG thaliMobileNati,veWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"75A74F2C-36D7-4F68-A621-7E4E5356421E","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-14 11:31:42 - DEBUG thaliMobile: 'Emitting peerAvailabilityChang,ed from handleRecreatedPeer {"peerIdentifier":"75A74F2C-36D7-4F68-A621-7E4E5356421E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-14 11:31:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentif,i,er":"75A74F2C-36D7-4F68-A621-7E4E5356421E","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-14 11:31:42 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-14 11:31:42 -, DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for E89525DA-D2AA-454F-878F-E377A11FB974 (syncValue: i22t71dkTERLayS0a2mIDvn8RdjlU8HX)'
2017-07-14 11:31:42 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserMana,ger.connectToPeer(_:syncValue:completion:) Peer(uuid: "E89525DA-D2AA-454F-878F-E377A11FB974", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E89525DA-D2AA-454F-878F-E377A11FB974", generati,on: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E89525DA-D2AA-454F-878F-E377A11FB974:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:s,t,oppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:E89525DA-D2AA-454F-878F-E377A11FB974:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:75A74F2C-36D7-4F68-A621-7E4E5356421E:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "75A74F2C-36D7-4F68-A621-7E4E5356421E", generation: 0)
2017-07-14 11:31:42 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"75A74F2C-36D7-4F68-A621-7E4E5356421E","generation":0}]'
2017-07-14 11:31:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"75A74F2C-36D7-4F68-A621-7E4E5356421E","generation":0}'
2017-07-14 11:31:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"75A74F2C-36D7-4F68-A621-7E4E5356421E","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-14 11:31:42 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"75A74F2C-36D7-4F68-A621-7E4E5356421E","connectionType":"MPCF","peerAvailable":false,"generati,on":null,"newAddressPort":null}'
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FC9BE05F-AFF6-433D-9CB7-76BD6CCEBD78
[ThaliCore] Advertiser: session connected Peer(uuid: "D5043C6C-65B0-4F29-8A29-F635EBFE335E", generation: 0)
[,ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:FC9BE05F-AFF6-433D-9CB7-76BD6CCEBD78 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FC9BE05F-AFF6-433D-9CB7-76BD6CCEBD78
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E89525DA-D2AA-454F-878F-E377A11FB974:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:FC9BE05F-AFF6-433D-9CB7-76BD6CCEBD78 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:E89525DA-D2AA-454F-878F-E377A11FB974:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "E89525DA-D2AA-454F-878F-E377A11FB974", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50198
,2017-07-14 11:31:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"i22t71dkTERLayS0a2mIDvn8RdjlU8HX","error":null,"portNumber":50198}'
,2017-07-14 11:31:45 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'i22t71dkTERLayS0a2mIDvn8RdjlU8HX', error: 'null', listeningPort: '50198''
,2017-07-14 11:31:45 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E89525DA-D2AA-454F-878F-E377A11FB974:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E89525DA-D2AA-454F-878F-E377A11FB974:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:23 [4, 9, 15, 23]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FC9BE05F-AFF6-433D-9CB7-76BD6CCEBD78
[ThaliCore] Session.startOutputStream(with:) peer:FC9BE05F-AFF6-433D-9CB7-76BD6CCEBD78
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:24 [4, 9, 15, 23, 24]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-14 11:31:45 - DEBUG testUtils: 'Got response data'
2017-07-14 11:31:45 - DEBUG testUtils: 'Got end'
ok 321 response body should match testData
ok 322 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-14 11:31:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 11:31:4,5 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkT,ype":null}})'
2017-07-14 11:31:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-14 11:31:45 - DEBUG tha,liMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:31:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-14 11:31:45 - DEBU,G, makeIntoCloseAllServer: 'closeAll called on server'
ok 323 must be stopped
[ThaliCore] BrowserManager.disconnect peer:E89525DA-D2AA-454F-878F-E377A11FB974
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningF,orConnectionsAndDisconnectClients() port:50198
[ThaliCore] VirtualSocket.closeStreams() vsID:23
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:fa,lse socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore], AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:24
[ThaliCore] VirtualSocket.closeStreams() vsID:24
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreams,H,andler disconnecting:true
[ThaliCore] VirtualSocket exited RunLoop vsID:23
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:24
[ThaliCore] Session.disconnect() peer:E89525DA-D2AA-454F-878F-E377A11FB974:0
[ThaliCore] VirtualSocket.deinit vsID:23 [4, 9, 15, 24]
,[ThaliCore] VirtualSocket.deinit vsID:24 [4, 9, 15]
[ThaliCore] Session.session(_:peer:didChange:) peer:E89525DA-D2AA-454F-878F-E377A11FB974:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "E89525DA-D2AA-454F-878F-,E377A11FB974", generation: 0)
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "E89525DA-D2AA-454F-878F-E377A11FB974", generation: 0)
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:FC9BE05F-AFF6-433D-9CB7-76BD6CCEBD78 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "D5043C6C-65B0-4F29-8A29-F635EBFE335E", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:FC9BE05F-AFF6-433D-9CB7-76BD6CCEBD78
[ThaliCore] Advert,iserRelay.deinit
[ThaliCore] Session.deinit peer:FC9BE05F-AFF6-433D-9CB7-76BD6CCEBD78
,2017-07-14 11:31:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:31:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:31:46 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:31:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 11:31:46 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 11:31:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 11:31:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 11:31:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# will fail bad PSK connection between peers
,ok 324 FIX ME, PLEASE!!!
,# teardown
,ok 325 must be stopped
,# setup
,2017-07-14 11:31:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:31:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:31:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:31:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 11:31:47 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 11:31:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 11:31:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 11:31:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We provide notification when a listener dies and we recreate it
,2017-07-14 11:31:47 - DEBUG CoordinatedClient: 'test was skipped, name: 'We provide notification when a listener dies and we recreate it''
,# teardown
,ok 326 must be stopped
,# setup
,2017-07-14 11:31:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:31:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:31:47 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:31:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 11:31:47 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-14 11:31:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-14 11:31:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-14 11:31:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated
,2017-07-14 11:31:47 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''
,# teardown
,ok 327 must be stopped
,# setup
,ok 328 ThaliMobile should be stopped
,# #startListeningForAdvertisements should fail if start not called
,ok 329 specific error should be returned
,# teardown
,2017-07-14 11:31:48 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"2DAB5366-D8ED-405B-840D-3F714804033E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 11:31:48 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 11:31:48 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"E89525DA-D2AA-454F-878F-E377A11FB974","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 11:31:48 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 330 error should be null
,ok 331 error should be null
,# setup
,ok 332 ThaliMobile should be stopped
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 333 specific error should be returned
,# teardown
,ok 334 error should be null
,ok 335 error should be null
,# setup
,ok 336 ThaliMobile should be stopped
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-14 11:31:48 - DEBUG thaliMobileNativeWrapper: 'listening 50201'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:31:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 337 error should be null
,ok 338 error should be null
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:31:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 339 error should be null
,ok 340 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 11:31:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:31:48 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 11:31:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-14 11:31:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-14 11:31:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 341 error should be null
ok 342 error should be null
,# setup
,ok 343 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-07-14 11:31:49 - DEBUG thaliMobileNativeWrapper: 'listening 50202'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:5A6924D5-0EB5-4A4F-BD0C-12440F480433
[ThaliCore] Browser.st,artListening
2017-07-14 11:31:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 344 error should be null
ok 345 error should be null
[ThaliCore] BrowserManager.startListe,ningForAdvertisements
2017-07-14 11:31:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 346 error should be null
ok 347 error should be null
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E", generation: 0)
,2017-07-14 11:31:49 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E","generation":0}]'
,2017-07-14 11:31:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E","generation":0}'
,2017-07-14 11:31:49 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 11:31:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 11:31:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:31:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:31:49 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-14 11:31:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 11:31:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:31:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-14 11:31:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 348 error should be null
,ok 349 error should be null
,# setup
,ok 350 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-14 11:31:49 - DEBUG thaliMobileNativeWrapper: 'listening 50203'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "EA62A928-D02C-4387-9827-6BEDF6BD1F7F", generation: 0)
[ThaliCore] Advertiser.startA,dvertising with peerID:EA62A928-D02C-4387-9827-6BEDF6BD1F7F
2017-07-14 11:31:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 351 error should be null
ok 352 error should, be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "EA62A928-D02C-4387-9827-6BEDF6BD1F7F", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:EA62A928-D02C-4387-9827-6BEDF6BD1F7F
20,17-07-14 11:31:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 353 error should be null
ok 354 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-14 11:31:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"adv,ertisingActive":false}'
,2017-07-14 11:31:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 11:31:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpd,ateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:31:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-14 11:31:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server',
,ok 355 error should be null
,ok 356 error should be null
,# setup
,ok 357 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-14 11:31:49 - DEBUG thaliMobileNativeWrapper: 'listening 50206'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 11:31:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingAct,ive":false}'
ok 358 error should be null
ok 359 error should be null
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 11:31:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActi,ve":false}'
,ok 360 error should be null
ok 361 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 11:31:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:31:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 11:31:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:31:50 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-14 11:31:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 362 error should be null
ok 363 error should be null
,# setup
,ok 364 ThaliMobile should be stopped
,# #start - Causing native or wifi to fail will cause a promise reject 
,2017-07-14 11:31:50 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
,ok 365 This should not cause wifi to fail
ok 366 native router should be bad
,# teardown
,ok 367 error should be null
ok 368 error should be null
,# setup
,ok 369 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-07-14 11:31:50 - DEBUG thaliMobileNativeWrapper: 'listening 50207'
ok 370 first call should succeed
ok 371 first call should succeed
ok 372 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 11:31:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:31:50 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:31:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:31:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-14 11:31:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 373 error should be null
ok 374 error should be null
,# setup
,ok 375 ThaliMobile should be stopped
,# #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)
,2017-07-14 11:31:51 - DEBUG CoordinatedClient: 'test was skipped, name: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''
,# teardown
,ok 376 error should be null
ok 377 error should be null
,# setup
,ok 378 ThaliMobile should be stopped
,# does not emit duplicate discoveryAdvertisingStateUpdate
,2017-07-14 11:31:51 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
,# teardown
,ok 379 error should be null
ok 380 error should be null
,# setup
,ok 381 ThaliMobile should be stopped
,# does not send duplicate availability changes
,2017-07-14 11:31:51 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"bd68ce26-2f62-470d-a60d-09a3e68e2c04","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 382 should be calle,d once
ok 383 should not have been called more than once
,# teardown
,2017-07-14 11:31:52 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"bd68ce26-2f62-470d-a60d-09a3e68e2c04","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 384 error should be null
ok 385 error should be null
,# setup
,ok 386 ThaliMobile should be stopped
,# can get the network status
,ok 387 network status should have certain non-empty properties
,# teardown
,ok 388 error should be null
ok 389 error should be null
,# setup
,ok 390 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (native)
,ok 391 we have not added peer to the cache yet
,2017-07-14 11:31:52 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a16f3596-88ae-4084-909f-7071fbe884b9","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 392 peer should be ,available
ok 393 cache contains native peer
2017-07-14 11:31:52 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a16f3596-88ae-4084-909f-7071fbe884b9","connectionType":"MPCF","peerAvailable":false,"generation":0,",newAddressPort":null}'
ok 394 peer should be unavailable
ok 395 peer has been removed from cache
,# teardown
,ok 396 error should be null
ok 397 error should be null
,# setup
,ok 398 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 399 we have not added peer to the cache yet
,2017-07-14 11:31:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9b77e711-1983-4714-8cb9-d10cc5bcab30","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 400 peer should be a,vailable
ok 401 cache contains wifi peer
2017-07-14 11:31:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9b77e711-1983-4714-8cb9-d10cc5bcab30","connectionType":"tcp","peerAvailable":false,"generation":0,"newA,ddressPort":null}'
ok 402 peer should be unavailable
ok 403 peer has been removed from cache
,# teardown
,ok 404 error should be null
ok 405 error should be null
,# setup
,ok 406 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-07-14 11:31:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"bef665d6-dd9e-49e3-83b0-8d31775e2e8e","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 407 first peer is a,vailable
2017-07-14 11:31:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2df1c844-be4b-4bc5-a0d8-f6d6c61cc934","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 408 second, peer is available
ok 409 first and second peers are different
,# teardown
,2017-07-14 11:31:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"bef665d6-dd9e-49e3-83b0-8d31775e2e8e","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 11:31:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"2df1c844-be4b-4bc5-a0d8-f6d6c61cc934","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 410 error should be null
,ok 411 error should be null
,# setup
,ok 412 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 413 should not be in cache at start
,2017-07-14 11:31:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a6e25a68-a636-465c-ad67-a5eb077a4d64","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 414 peer is available
,# teardown
,2017-07-14 11:31:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"a6e25a68-a636-465c-ad67-a5eb077a4d64","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 415 error should be null
ok 416 error should be null
,# setup
,ok 417 ThaliMobile should be stopped
,# native available - peer with same port and different generation is cached (BLUETOOTH)
,2017-07-14 11:31:53 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with same port and different generation is cached (BLUETOOTH)''
,# teardown
,ok 418 error should be null
ok 419 error should be null
,# setup
,ok 420 ThaliMobile should be stopped
,# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
,2017-07-14 11:31:53 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''
,# teardown
,ok 421 error should be null
,ok 422 error should be null
,# setup
,ok 423 ThaliMobile should be stopped
,# native available - peer with greater generation is cached (MPCF)
,2017-07-14 11:31:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"83e32b86-b8d7-4880-9898-a6cce267845c","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
ok 424 peer should be ,available
,2017-07-14 11:31:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"83e32b86-b8d7-4880-9898-a6cce267845c","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 425 peer should be ,available
ok 426 should store correct generation
,# teardown
,2017-07-14 11:31:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"83e32b86-b8d7-4880-9898-a6cce267845c","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 427 error should be null
ok 428 error should be null
,# setup
,ok 429 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-07-14 11:31:54 - DEBUG thaliMobileNativeWrapper: 'listening 50208'
,2017-07-14 11:31:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8828de6c-302b-4d8d-9e5f-6369cd6aa351","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
,ok 430 discovered correct peer
,ok 431 got correct generation
,2017-07-14 11:31:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8828de6c-302b-4d8d-9e5f-6369cd6aa351","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 432 discovered correct peer
,ok 433 got correct generation
,# teardown
,2017-07-14 11:31:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"8828de6c-302b-4d8d-9e5f-6369cd6aa351","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
,2017-07-14 11:31:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:31:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:31:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 434 error should be null
,ok 435 error should be null
,# setup
,ok 436 ThaliMobile should be stopped
,# native unavailable - new peer is ignored
,2017-07-14 11:31:55 - DEBUG thaliMobileNativeWrapper: 'listening 50209'
,2017-07-14 11:31:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ee1e0784-8423-4ce7-83ae-5db9b0af09aa","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 437 discovered avai,lable peer
ok 438 peer is available
,# teardown
,2017-07-14 11:31:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"ee1e0784-8423-4ce7-83ae-5db9b0af09aa","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-14 11:31:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:31:55 - INFO thaliMobile: 'Filtered out discoveryAdvert,isingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 11:31:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:31:55 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-14 11:31:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 439 error should be null
,ok 440 error should be null
,# setup
,ok 441 ThaliMobile should be stopped
,# native unavailable - cached peer is removed
,2017-07-14 11:31:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8cd3a865-97af-4c2a-af2d-0f9f0523f490","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 442 peer should be ,available
2017-07-14 11:31:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8cd3a865-97af-4c2a-af2d-0f9f0523f490","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 443 peer, should be unavailable
ok 444 should be removed from cache
,# teardown
,ok 445 error should be null
ok 446 error should be null
,# setup
,ok 447 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-07-14 11:31:55 - DEBUG thaliMobileNativeWrapper: 'listening 50210'
2017-07-14 11:31:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3043c828-2d1a-4641-8e2b-8f91d72a723e","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 448 first peer is expected to be available
2017-07-14 11:31:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"bca8d04f-f1b8-4f03-bf8f-77e59a166559","connectio,nType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 449 second peer is expected to be available
,2017-07-14 11:31:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"bca8d04f-f1b8-4f03-bf8f-77e59a166559","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 450 peer, became unavailable
ok 451 it was wifi peer
2017-07-14 11:31:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"bca8d04f-f1b8-4f03-bf8f-77e59a166559","connectionType":"tcp","peerAvailable":true,"generation":0,"ne,wAddressPort":false}'
ok 452 we found peer again
ok 453 it was wifi peer
2017-07-14 11:31:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"bca8d04f-f1b8-4f03-bf8f-77e59a166559","connectionType":"tcp",,"peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 454 peer became unavailable
ok 455 it was wifi peer
,# teardown
,2017-07-14 11:31:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"3043c828-2d1a-4641-8e2b-8f91d72a723e","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-14 11:31:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 11:31:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpd,ateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:31:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:31:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 456 error should be null
,ok 457 error should be null
,# setup
,ok 458 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
,2017-07-14 11:31:56 - DEBUG CoordinatedClient: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''
,# teardown
,ok 459 error should be null
ok 460 error should be null
,# setup
,ok 461 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
,2017-07-14 11:31:56 - DEBUG thaliMobileNativeWrapper: 'listening 50211'
,2017-07-14 11:31:56 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"35f4a977-7f62-47e1-9b18-37fdeea4e6bf","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 462 first peer is expected to be available
,2017-07-14 11:31:56 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"92dea6e4-934c-43a5-b517-8da8a442b214","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 463 second peer is expected to be available
,2017-07-14 11:31:56 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"35f4a977-7f62-47e1-9b18-37fdeea4e6bf","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 464 peer became unavailable
,2017-07-14 11:31:56 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"92dea6e4-934c-43a5-b517-8da8a442b214","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 465 peer became unavailable
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:31:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:31:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:31:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 466 error should be null
,ok 467 error should be null
,# setup
,ok 468 ThaliMobile should be stopped
,# multiconnect failure - new peer is ignored (MPCF)
,2017-07-14 11:31:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
,# teardown
,ok 469 error should be null
ok 470 error should be null
,# setup
,ok 471 ThaliMobile should be stopped
,# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
,2017-07-14 11:31:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
,# teardown
,ok 472 error should be null
ok 473 error should be null
,# setup
,ok 474 ThaliMobile should be stopped
,# newAddressPort field (TCP_NATIVE)
,2017-07-14 11:31:58 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ab29fc71-77c0-409a-991e-503b703e74db","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 475 peer discovered first time does not have new address
2017-07-14 11:31:58 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ab29fc71-77c0-409a-991e-503b703e74db","connectionType":"tcp","peerAvailable":true,"ge,neration":20,"newAddressPort":false}'
ok 476 address has not been changed
2017-07-14 11:31:58 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ab29fc71-77c0-409a-991e-503b703e74db","connectionType":"tcp","peerAvai,lable":true,"generation":20,"newAddressPort":true}'
ok 477 new port handled correctly
2017-07-14 11:31:58 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ab29fc71-77c0-409a-991e-503b703e74db","connectionType":"tc,p","peerAvailable":true,"generation":20,"newAddressPort":true}'
ok 478 new host handled correctly
2017-07-14 11:31:58 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ab29fc71-77c0-409a-991e-503b703e74db","connec,t,ionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}'
ok 479 newAddressPort is null for unavailable peers
,# teardown
,ok 480 error should be null
ok 481 error should be null
,# setup
,ok 482 ThaliMobile should be stopped
,# newAddressPort field (BLUETOOTH)
,2017-07-14 11:31:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort field (BLUETOOTH)''
,# teardown
,ok 483 error should be null
ok 484 error should be null
,# setup
,ok 485 ThaliMobile should be stopped
,# newAddressPort field (MPCF)
,ok 486 NOT IMPLEMENTED # SKIP
,# teardown
,ok 487 error should be null
ok 488 error should be null
,# setup
,ok 489 ThaliMobile should be stopped
,# newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)
,2017-07-14 11:31:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''
,# teardown
,ok 490 error should be null
ok 491 error should be null
,# setup
,ok 492 ThaliMobile should be stopped
,# #getPeerHostInfo - error when peer has not been discovered yet
,ok 493 should be equal
,# teardown
,ok 494 error should be null
ok 495 error should be null
,# setup
,ok 496 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)
,2017-07-14 11:31:59 - DEBUG CoordinatedClient: 'test was skipped, name: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''
,# teardown
,ok 497 error should be null
ok 498 error should be null
,# setup
,ok 499 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)
,2017-07-14 11:32:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 500 contains expected properties
,ok 501 the same hostAddress
,ok 502 the same portNumber
,# teardown
,2017-07-14 11:32:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 503 error should be null
,ok 504 error should be null
,# setup
,ok 505 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached wifi peer
,2017-07-14 11:32:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 506 contains expected properties
ok 507 the same hostAddress
ok 508 the same portNumber
,# teardown
,2017-07-14 11:32:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 509 error should be null
ok 510 error should be null
,# setup
,ok 511 ThaliMobile should be stopped
,# #disconnect fails on wifi peers
,2017-07-14 11:32:01 - DEBUG thaliMobileNativeWrapper: 'listening 50212'
,2017-07-14 11:32:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"04e2dca0-287e-4d91-aa22-b4acb817b097","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 512 Got specific error message
,# teardown
,2017-07-14 11:32:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"04e2dca0-287e-4d91-aa22-b4acb817b097","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:32:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:32:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:32:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:32:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:32:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 513 error should be null
,ok 514 error should be null
,# setup
,ok 515 ThaliMobile should be stopped
,# #disconnect delegates native peers to the native wrapper
,2017-07-14 11:32:01 - DEBUG thaliMobileNativeWrapper: 'listening 50213'
,2017-07-14 11:32:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c6cf0125-6994-452f-8ae5-c1a1905e6f1c","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] BrowserManager.disconnect peer:c6cf0125-6994-452f-8ae5-c1a1905e6f1c
,ok 516 native wrapper `disconnect` called once
,ok 517 native wrapper `disconnect` called with peer data
,# teardown
,2017-07-14 11:32:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c6cf0125-6994-452f-8ae5-c1a1905e6f1c","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:32:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:32:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:32:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:32:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:32:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 518 error should be null
,ok 519 error should be null
,# setup
,ok 520 ThaliMobile should be stopped
,# network changes emitted correctly
,2017-07-14 11:32:01 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes emitted correctly''
,# teardown
,ok 521 error should be null
ok 522 error should be null
,# setup
,ok 523 ThaliMobile should be stopped
,# network changes not emitted in started state
,2017-07-14 11:32:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in started state''
,# teardown
,ok 524 error should be null
,ok 525 error should be null
,# setup
,ok 526 ThaliMobile should be stopped
,# network changes not emitted in stopped state
,2017-07-14 11:32:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in stopped state''
,# teardown
,ok 527 error should be null
ok 528 error should be null
,# setup
,ok 529 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on Android
,2017-07-14 11:32:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on Android''
,# teardown
,ok 530 error should be null
ok 531 error should be null
,# setup
,ok 532 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on iOS
,2017-07-14 11:32:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on iOS''
,# teardown
,ok 533 error should be null
ok 534 error should be null
,# setup
,ok 535 ThaliMobile should be stopped
,# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
,2017-07-14 11:32:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''
,# teardown
,ok 536 error should be null
,ok 537 error should be null
,# setup
,ok 538 ThaliMobile should be stopped
,# does not fire duplicate events after peer listener recreation
,2017-07-14 11:32:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not fire duplicate events after peer listener recreation''
,# teardown
,ok 539 error should be null
ok 540 error should be null
,# setup
,ok 541 ThaliMobile should be stopped
,# #stop should change peers
,2017-07-14 11:32:03 - DEBUG thaliMobileNativeWrapper: 'listening 50214'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9524BDC5-645D-4B8E-BBD3-60F5370DBFCC
[ThaliCore] Browser.startListening
2017-07-14 11:32:03 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:32:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b60bd19e-3a7f-41c9-82b1-6f3634b544d4","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E", generation: 0)
,ok 542 Peer availabilities has one entry for our connection type
2017-07-14 11:32:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8c446560-c9a7-4389-b955-8dbeabfcfb35","connectionType":"tcp","peerAvailable":tru,e,"generation":0,"newAddressPort":false}'
,ok 543 Peer availabilities has one entry for our connection type
,2017-07-14 11:32:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"b60bd19e-3a7f-41c9-82b1-6f3634b544d4","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 11:32:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"8c446560-c9a7-4389-b955-8dbeabfcfb35","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:32:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:32:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,1,11],"networkType":"BOTH"}})'
,2017-07-14 11:32:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 11:32:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:32:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:32:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:32:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:32:03 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E","generation":0}]'
,2017-07-14 11:32:03 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E","generation":0}'
,2017-07-14 11:32:03 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,ok 544 No peers
,ok 545 No peers
,ok 546 No peers
,# teardown
,ok 547 error should be null
,ok 548 error should be null
,# setup
,ok 549 ThaliMobile should be stopped
,# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
,2017-07-14 11:32:04 - DEBUG thaliMobileNativeWrapper: 'listening 50215'
,2017-07-14 11:32:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f5d29573-e397-4d47-a80a-cd3595992bba","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 550 1
,ok 551 2
,2017-07-14 11:32:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5ee18f71-b26e-437a-9f4a-b2fc7cd0bab1","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-07-14 11:32:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"f5d29573-e397-4d47-a80a-cd3595992bba","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 11:32:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5ee18f71-b26e-437a-9f4a-b2fc7cd0bab1","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:32:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:32:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:32:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:32:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:32:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 552 error should be null
,ok 553 error should be null
,# setup
,ok 554 ThaliMobile should be stopped
,# peer should be found once after listening and discovery started
,2017-07-14 11:32:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer should be found once after listening and discovery started''
,# teardown
,ok 555 error should be null
ok 556 error should be null
,# setup
,ok 557 ThaliMobile should be stopped
,# can get data from all participants
,2017-07-14 11:32:05 - DEBUG thaliMobileNativeWrapper: 'listening 50216'
ok 558 error should be null
ok 559 error should be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "780F3D92-A26A-44CD-934D-63,6A0E30EC8B", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:780F3D92-A26A-44CD-934D-636A0E30EC8B
2017-07-14 11:32:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive,":true}'
,ok 560 error should be null
ok 561 error should be null
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:347F6BE3-9E54-4136-A461-18BE2D6B7794
[ThaliCore] Browser.startListening
2,017-07-14 11:32:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
ok 562 error should be null
ok 563 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:994F4DE1-7A0E-410E-9D9D-4D8018271D03:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "994F4DE1-7A0E-410E-9D9D-4D8018271D03", generation: 0)
2017-07-14 11:32:06 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"994F4DE1-7A0E-410E-9D9D-4D8018271D03","generation":0}]'
2017-07-14 11:32:06 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"994F4DE1-7A0E-410E-9D9D-4D8018271D03","generation":0}'
,2017-07-14 11:32:06 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"994F4DE1-7A0E-410E-9D9D-4D8018271D03","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-14 11:32:06 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"994F4DE1-7A0E-410E-9D9D-4D8018271D03","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-14 11:32:06 - DEBUG thaliMobileNativeWrapper: 'Issuing multi,Connect for 994F4DE1-7A0E-410E-9D9D-4D8018271D03 (syncValue: 0)'
2017-07-14 11:32:06 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "994F4DE1-7A0E-410E-9D9D-4D801,8271D03", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "994F4DE1-7A0E-410E-9D9D-4D8018271D03", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9,9,4F4DE1-7A0E-410E-9D9D-4D8018271D03:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:42877076-2AF7-4818-A925-8E37D50E743E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "42877076-2AF7-4818-A925-8E37D50E743E", generation: 0)
2017-07-14 11:32:06 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"42877076-2AF7-4818-A925-8E37D50E743E","generation":0}]'
,2017-07-14 11:32:06 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"42877076-2AF7-4818-A925-8E37D50E743E","generation":0}'
,2017-07-14 11:32:06 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"42877076-2AF7-4818-A925-8E37D50E743E","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-14 11:32:06 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"42877076-2AF7-4818-A925-8E37D50E743E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:994F4DE1-7A0E-410E-9D9D-4D8018271D03:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:780F3D92-A26A-44CD-934D-636A0E30EC8B:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "780F3D92-A26A-44CD-934D-636A0E30EC8B", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:994F4DE1-7A0E-410E-9D9D-4D8018271D03:0
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CF906A19-8B04-431A-ACC6-1FA163302ED2
[ThaliCore] Advertiser: session connected Peer(uuid: "780F3D92-A26A-44CD-934D-636A0E30EC8B", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:CF906A19-8B04-431A-ACC6-1FA163302ED2 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:994F4DE1-7A0E-410E-9D9D-4D8018271D03:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "994F4DE1-7A0E-410E-9D9D-4D8018271D03", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50219
,2017-07-14 11:32:09 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":null,"portNumber":50219}'
,2017-07-14 11:32:09 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 42877076-2AF7-4818-A925-8E37D50E743E (syncValue: 1)'
,2017-07-14 11:32:09 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "42877076-2AF7-4818-A925-8E37D50E743E", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "42877076-2AF7-4818-A925-,8E37D50E743E", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:42877076-2AF7-4818-A925-8E37D50E743E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:994F4DE1-7A0E-410E-9D9D-4D8018271D03:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:994F4DE1-7A0E-410E-9D9D-4D8018271D03:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:25 [4, 9, 15, 25]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 11:32:09 - DEBUG testUtils: 'Got response data'
,2017-07-14 11:32:09 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.session(_:peer:didChange:) peer:42877076-2AF7-4818-A925-8E37D50E743E:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CF906A19-8B04-431A-ACC6-1FA163302ED2
,[ThaliCore] Session.session(_:peer:didChange:) peer:CF906A19-8B04-431A-ACC6-1FA163302ED2 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CF906A19-8B04-431A-ACC6-1FA163302ED2
[ThaliCore] Session.startOutputStream(with:) peer:CF906A19-8B04-431A-ACC6-1FA163302ED2
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:26 [4, 9, 15, 25, 26]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:42877076-2AF7-4818-A925-8E37D50E743E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:42877076-2AF7-4818-A925-8E37D50E743E:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "42877076-2AF7-4818-A925-8E37D50E743E", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50224
2017-07-14 11:32:12 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":null,"portNumber":50224}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:42877076-2AF7-4818-A925-8E37D50E743E:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:42877076-2AF7-4818-A925-8E37D50E743E:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:27 [4, 9, 15, 25, 26, 27]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 11:32:12 - DEBUG testUtils: 'Got response data'
,2017-07-14 11:32:12 - DEBUG testUtils: 'Got end'
,ok 564 received all uuids
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:39B8D97C-8A45-4508-9AE2-11E8F8BE0FF7
[ThaliCore] Advertiser: session connected Peer(uuid: "780F3D92-A26A-44CD-934D-636A0E30EC8B", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:39B8D97C-8A45-4508-9AE2-11E8F8BE0FF7 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:39B8D97C-8A45-4508-9AE2-11E8F8BE0FF7
,[ThaliCore] Session.session(_:peer:didChange:) peer:39B8D97C-8A45-4508-9AE2-11E8F8BE0FF7 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:39B8D97C-8A45-4508-9AE2-11E8F8BE0FF7
[ThaliCore] Session.startOutputStream(with:) peer:39B8D97C-8A45-4508-9AE2-11E8F8BE0FF7
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,8 [4, 9, 15, 25, 26, 27, 28]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-14 11:32:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"994F4DE1-7A0E-410E-9D9D-4D8018271D03","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-14, 11:32:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"42877076-2AF7-4818-A925-8E37D50E743E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 11:32:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 11:32:17 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-14 11:32:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] Brows,erManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 11:32:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:32:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-14 11:32:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:26
[ThaliCore] VirtualSocket.closeStreams() vsID:26
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:28
[ThaliCore] VirtualSocket.closeS,treams() vsID:28
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:26
[ThaliCore] VirtualSocket.deinit vsID:26 [4, 9, 15, 25, 27, 28]
[ThaliCore] AdvertiserRelay.didCloseVi,rtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:28
[ThaliCore] VirtualSocket.deinit vsID:28 [4, 9, 15, 25, 27]
,ok 565 error should be null
,ok 566 error should be null
,# setup
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:27
[ThaliCore] VirtualSocket.closeStreams() vsID:27
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:27
[ThaliCore] VirtualSocket.deinit vsID:27 [4, 9, 15, 25]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,ok 567 ThaliMobile should be stopped
,# test for data corruption
,2017-07-14 11:32:17 - DEBUG CoordinatedClient: 'test was skipped, name: 'test for data corruption''
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:25
[ThaliCore] VirtualSocket.closeStreams() vsID:25
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:25,
[ThaliCore] VirtualSocket.deinit vsID:25 [4, 9, 15]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,# teardown
,ok 568 error should be null
ok 569 error should be null
,# setup
,# #testThaliPeerAction - test getters
,ok 570 getPeerIdentifier
ok 571 getConnectionType
ok 572 getActionType
ok 573 getActionState
ok 574 getPskIdentity
ok 575 getPskKey
,# teardown
,# setup
,# #testThaliPeerAction - start and kill
,ok 576 initial state
,ok 577 after start
2017-07-14 11:32:18 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 578 after kill
,# teardown
,# setup
,# #testThaliPeerAction - double start
,ok 579 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - start after kill
,2017-07-14 11:32:19 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 580 clean kill
ok 581 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - make sure ids are unique
,ok 582 should not be equal
,# teardown
,# setup
,# #testThaliPeerAction - check that forever agent can be destroyed
,ok 583 forever agent should have it's own destroy method
,ok 584 agent's destroy should be called
ok 585 agent's destroy should not be called again
ok 586 agent is destroyed
,# teardown
,# setup
,# Test PeerDictionary basic functionality
,ok 587 Entry counter must be 1
,ok 588 Entry exists
,ok 589 Size must be 1
,ok 590 Entry counter must be 2
,ok 591 Entry exists
,ok 592 Size must be 2
,ok 593 Entry counter must be 1
,ok 594 Entry exists
,ok 595 Size must be 3
,ok 596 Entry counter must be 2
,ok 597 Entry exists
,ok 598 Size must be 4
,ok 599 Entry 1_1 should not be found
,ok 600 Entry 1_1 does not exist
,ok 601 Size must be 3
,ok 602 Entry 1_2 should not be found
,ok 603 Entry 1_2 does not exist
,ok 604 Size must be 2
,ok 605 should be equal
,ok 606 Entry 2_1 should not be found
,ok 607 Entry 2_2 should not be found
,ok 608 Entry 2_1 does not exist
,ok 609 Entry 2_2 does not exist
,ok 610 Size must be 0
,# teardown
,# setup
,# Test PeerDictionary with multiple entries.
,ok 611 Size must be100
,ok 612 Entries between 20 and MAXSIZE + 20 should exist
,ok 613 WAITING state entry should not be removed
,# teardown
,# setup
,# RESOLVED entries are removed before WAITING state entry.
,ok 614 Entries between 6 and MAXSIZE + 4 should exist
,ok 615 Size should be MAXSIZE
ok 616 Size should be MAXSIZE+6
,# teardown
,# setup
,# WAITING entries are removed before CONTROLLED_BY_POOL state entry.
,ok 617 WAITING state entry should not be removed
,ok 618 Waiting entries between 6 and MAXSIZE + 4 should exist
,ok 619 Size should be MAXSIZE
,ok 620 entryCounter should be MAXSIZE+6
,# teardown
,# setup
,# When CONTROLLED_BY_POOL entry is removed and kill is called.
,ok 621 Kill should be called once
ok 622 Size should be MAXSIZE
,# teardown
,# setup
,# #ThaliPeerPoolDefault - single action
,ok 623 is an agent
ok 624 enqueue is fine
ok 625 Everything should be off the queue
,# teardown
,# setup
,# #ThaliPeerPoolDefault - multiple actions
,ok 626 is an agent
ok 627 first enqueue is fine
ok 628 is an agent
ok 629 second enqueue is fine
ok 630 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 631 Queue is empty
,# teardown
,# setup
,# #ThaliPeerPoolDefault - PSK Pool works
,ok 632 is an agent
ok 633 good enqueue
,ok 634 Identity should match
,2017-07-14 11:32:24 - DEBUG testUtils: 'Got response data'
,2017-07-14 11:32:24 - DEBUG testUtils: 'Got end'
,ok 635 Got expected response
,ok 636 Got psk call back
,# teardown
,2017-07-14 11:32:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #ThaliPeerPoolDefault - stop
,ok 637 is an agent
ok 638 enqueue worked
,ok 639 is an agent
,ok 640 enqueue 2 worked
,ok 641 enqueue is not available when stopped
,ok 642 start action is killed
,ok 643 killed action is still killed
,ok 644 enqueued action when stopped is killed
,ok 645 inQueue is empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that start verifies queue length
,ok 646 good start
ok 647 good enqueue
ok 648 queue is not empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - bad enqueues
,ok 649 null arg
ok 650 wrong arg type
ok 651 wrong arg type
,# teardown
,# setup
,# #ThaliPeerPoolInterface - do not allow same object type
,ok 652 good enqueue
ok 653 already enqueued
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
,ok 654 good enqueue
ok 655 2nd good enqueue
ok 656 we are in the pool
ok 657 We are out of the pool
ok 658 Action was killed
ok 659 The original kill was called too
ok 660 second item is still in queue
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
,ok 661 good enqueue
ok 662 first kill
ok 663 second NOOP kill
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that stop removes all actions
,ok 664 1st good enqueue
ok 665 2nd good enqueue
,ok 666 1st action is in the pool
ok 667 2nd action is in the pool
ok 668 1st action is out of the pool
ok 669 2st action is out of the pool
ok 670 pool is empty
,# teardown
,# setup
,# We reject unrecognized connection type
,2017-07-14 11:32:27 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 671 Got right error
,ok 672 Start should not be called
,ok 673 Kill should have been called at least once
,# teardown
,# setup
,# We reject unrecognized action type
,2017-07-14 11:32:27 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-14 11:32:27 - ERROR thaliPeerPoolOneAtATime: 'Got unsupported action type: blah'
,ok 674 Got right error
,ok 675 Start should not be called
,ok 676 Kill should have been called at least once
,# teardown
,# setup
,# One action on bluetooth
,2017-07-14 11:32:27 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 677 Got null
,2017-07-14 11:32:27 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 678 is an agent
,2017-07-14 11:32:27 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 679 Got killed at least once
,# teardown
,# setup
,# Two notification actions
,2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 680 Got Null
,ok 681 Got another null
,2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,ok 682 is an agent
,2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 683 is an agent
,2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 684 Action 1 killed at least once
,ok 685 Action 1 went first
,ok 686 Action 2 killed at least once
,# teardown
,# setup
,# replicateThroughProblems
,2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
,2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
,2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 687 should have gotten null
,2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
,2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activity time out - noActivityTimeOut'
,ok 688 Should have stopped nicely
,2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
,2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButNotAvailable'
,ok 689 Still looking for null
,2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
,2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
,2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'Replication action failed badly so we are going to retry'
,2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
,2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
,2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 690 Yup, another null
,ok 691 We cloned!
,# teardown
,# setup
,# Replication goes first
,2017-07-14 11:32:29 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 692 Null 1
,ok 693 (unnamed assert)
,2017-07-14 11:32:29 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 694 is an agent
,ok 695 Null 3
,ok 696 Replication not yet called
,ok 697 Notification 2 not yet called
,2017-07-14 11:32:29 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,2017-07-14 11:32:29 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
ok 698 is an agent
,ok 699 Notification went first
,ok 700 Notification 2 not called yet
,2017-07-14 11:32:29 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,2017-07-14 11:32:29 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-14 11:32:29 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 701 is an agent
,ok 702 Notification finished
,ok 703 Replication finished
,2017-07-14 11:32:29 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,# teardown
,# setup
,# wifi allows many parallel non-replication actions
,2017-07-14 11:32:30 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2017-07-14 11:32:30 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
ok 704 is an agent
ok 705 First does, not throw
2017-07-14 11:32:30 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
ok 706 is an agent
ok 707 Second does not throw
2017-07-14 11:32:30 - DEBUG thaliPeerPoolOneAtAT,ime: 'action returned successfully from start - Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
truetruefalsetrue
,2017-07-14 11:32:30 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
truetruetruetrue
# teardown
,# setup
,# wifi allows no more than 2 simultaneous replication actions for same peerID
,2017-07-14 11:32:30 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-14 11:32:30 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 708 is an agent
,ok 709 first ok
,2017-07-14 11:32:30 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 710 is an agent
,ok 711 second ok
,ok 712 third ok
,2017-07-14 11:32:30 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-07-14 11:32:30 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-07-14 11:32:30 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-14 11:32:30 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,# teardown
,# setup
,# Client to server request coordinated
,2017-07-14 11:32:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'Client to server request coordinated''
,# teardown
,2017-07-14 11:32:31 - INFO testThaliNotification: 'Participants:0 Peers Replied to us:0 Peers requested to:0'
,# setup
,# Test BEACONS_RETRIEVED_AND_PARSED locally
,ok 713 peerIdentifier should match
,ok 714 generation should match
,ok 715 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 716 good beacon
,ok 717 good preAmble
,ok 718 public keys match!
,ok 719 must return null after successful call
,ok 720 Once start returns the action should be in KILLED state
,# teardown
,2017-07-14 11:32:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test HTTP_BAD_RESPONSE locally
,ok 721 Response should be HTTP_BAD_RESPONSE
,ok 722 must return null after successful call
,# teardown
,2017-07-14 11:32:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test NETWORK_PROBLEM locally
,ok 723 Response should be NETWORK_PROBLEM
,ok 724 reject reason should be: Could not establish TCP connection
,# teardown
,2017-07-14 11:32:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails when getPeerHostInfo fails
,ok 725 Resolution should be BAD_PEER
,ok 726 correct error message
,# teardown
,2017-07-14 11:32:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the start two times
,ok 727 Call start once
,ok 728 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 729 must return null after successful call.
,# teardown
,2017-07-14 11:32:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill before calling the start
,ok 730 Should be Killed
,ok 731 Start after killed
,# teardown
,2017-07-14 11:32:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill immediately after the start
,ok 732 Should be KILLED
ok 733 must return null after successful kill
,# teardown
,2017-07-14 11:32:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill while waiting a response from the server
,ok 734 Should be KILLED
,ok 735 must return null after successful kill
,# teardown
,2017-07-14 11:32:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test to exceed the max content size locally
,ok 736 HTTP_BAD_RESPONSE should be response when content size is exceeded
,ok 737 must return null after successful call
,# teardown
,2017-07-14 11:32:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Close the server socket while the client is waiting a response from the server. Local test.
,2017-07-14 11:32:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 738 Should be NETWORK_PROBLEM caused closing server socket
ok 739 Should be Could not establish TCP connection
,# teardown
,# setup
,# Close the client socket while the client is waiting a response from the server. Local test.
,ok 740 Should be NETWORK_PROBLEM caused closing client socket
,ok 741 Should be Could not establish TCP connection
,# teardown
,2017-07-14 11:32:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #generatePreambleAndBeacons bad args
,ok 742 publicKeysToNotify cannot be null
ok 743 ecdh for local device cannot be null
ok 744 milliseconds cannot be less than 0
ok 745 milliseconds cannot be 0
ok 746 milliseconds cannot be greater than one_day
,# teardown
,# setup
,# #generatePreambleAndBeacons empty keys to notify
,ok 747 should be equal
,# teardown
,# setup
,# #generatePreambleAndBeacons multiple keys to notify
,ok 748 should be equal
,ok 749 should be equal
,ok 750 (unnamed assert)
,ok 751 should be equal
,# teardown
,# setup
,# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
,ok 752 should throw
,# teardown
,# setup
,# #parseBeacons invalid expiration in beaconStreamWithPreAmble
,ok 753 Preamble expiration must be a 64 bit integer
,# teardown
,# setup
,# #parseBeacons expiration out of range lower
,ok 754 Expiration out of range
,# teardown
,# setup
,# #parseBeacons expiration out of range lower
,ok 755 Expiration out of range
,# teardown
,# setup
,# #parseBeacons no beacons returns null
,ok 756 should be equal
,# teardown
,# setup
,# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
,ok 757 Malformed encrypted beacon key ID
,# teardown
,# setup
,# #parseBeacons addressBookCallback fails decrypt
,ok 758 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns no matches
,ok 759 should be equal
ok 760 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns spurious match
,ok 761 should be equal
ok 762 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns public key
,ok 763 right number of calls to address book
,ok 764 good preAmble
,ok 765 good unencryptedKeyId
,ok 766 good beacon
,# teardown
,# setup
,# validate generatePskIdentityField
,ok 767 decoded buffers match
,# teardown
,# setup
,# validate generatePskSecret
,ok 768 secrets match
,# teardown
,# setup
,# validate generatePskSecrets
,ok 769 Matching numbers
,ok 770 We have an entry!
ok 771 keys match
,ok 772 secrets match
,ok 773 We have an entry!
ok 774 keys match
,ok 775 secrets match
,ok 776 We have an entry!
,ok 777 keys match
ok 778 secrets match
,# teardown
,# setup
,# validate generateBeaconStreamAndSecrets
,ok 779 Streams have same length
,ok 780 matching size
,ok 781 keys match
,ok 782 secrets match
,# teardown
,# setup
,# Add two Peers.
,ok 783 should be equal
,ok 784 peerDictionalty contains 2 peers
,ok 785 bluetooth peer's notification has correct connection type
,ok 786 tcp peer's notification has correct connection type
,2017-07-14 11:32:51 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
2017-07-14 11:32:51 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-14 11:32:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# TCP_NATIVE peer loses DNS
,ok 787 notification peer dictionary contains exactly 1 peer
2017-07-14 11:32:52 - WARN thaliNotificationClient: 'peer is not available'
ok 788 notification peer dictionary does not contain any peers
2017-07-14 11:32:52 - DEBUG thaliPeerPoolDefault: 'Got, err   peer not available'
,# teardown
,2017-07-14 11:32:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Received beacons with no values for us
,ok 789 entry exists
,ok 790 entry is resolved
,# teardown
,2017-07-14 11:32:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Notification action killed with a superseded
,ok 791 Action should be KILLED
ok 792 Peer state should be RESOLVED
,# teardown
,2017-07-14 11:32:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally
,ok 793 hostAddress must match
,ok 794 portNumber must match
,ok 795 suggestedTCPTimeout must match
,ok 796 connectionType must match
,ok 797 peerIDs must match
,# teardown
,2017-07-14 11:32:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 798 Correct error
,# teardown
,2017-07-14 11:32:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally using ThaliPeerPoolDefault
,ok 799 hostAddress must match
,ok 800 portNumber must match
,ok 801 suggestedTCPTimeout must match
,ok 802 connectionType must match
,ok 803 peerIds must match
,# teardown
,2017-07-14 11:32:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails because of a bad hostname.
,2017-07-14 11:32:55 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 804 action should be resolved with NETWORK_PROBLEM error
,2017-07-14 11:32:55 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 805 action should be resolved with NETWORK_PROBLEM error
,2017-07-14 11:32:56 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 806 action should be resolved with NETWORK_PROBLEM error
,2017-07-14 11:32:56 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 807 action should be resolved with NETWORK_PROBLEM error
,ok 808 correct number of requests
,ok 809 correct number of failures
,ok 810 correct final peer state
,# teardown
,2017-07-14 11:32:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# hostaddress is removed when the action is running. 
,2017-07-14 11:32:59 - WARN thaliNotificationClient: 'peer is not available'
2017-07-14 11:32:59 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 811 peerDictionary should become empty
,# teardown
,2017-07-14 11:32:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notificationClient does not retry action with BAD_PEER resolution
,2017-07-14 11:32:59 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 812 failed with expected error
ok 813 peer state should be RESOLVED
,# teardown
,2017-07-14 11:32:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notification client correctly handles peer availability changes of the same peer
,2017-07-14 11:32:59 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 814 First action failed
,ok 815 second action killed
# teardown
,2017-07-14 11:33:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Client to server request locally
,ok 816 secrets are equal
ok 817 Public key matches with the server key
,ok 818 hostAddress must match
,ok 819 portNumber must match
,ok 820 suggestedTCPTimeout must match
,ok 821 connectionType must match
,# teardown
,2017-07-14 11:33:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache clean and expiration
,ok 822 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
ok 823 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
,ok 824 All entries should be expired after 1 second
,# teardown
,2017-07-14 11:33:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache getSecret and getPublic
,ok 825 All keys need to be available in the cache
,ok 826 All entries should be expired after 1 second
# teardown
,2017-07-14 11:33:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache multiple entries
,ok 827 Size of the cache should be 2
ok 828 Cache doesn't contain dictionary1
,ok 829 Size of the cache should be 1
,ok 830 Cache doesn't contain beaconStreamAndSecretDictionary2
,# teardown
,2017-07-14 11:33:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start and stop ThaliNotificationServer
,ok 831 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
,ok 832 ThaliMobile.StopAdvertisingAndListeningshould be called once
,# teardown
,2017-07-14 11:33:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty array to ThaliNotificationServer.start
,ok 833 StartUpdateAdvertisingAndListening should not be called
,ok 834 ThaliMobile.StopAdvertisingAndListening should be called once
,ok 835 no error
,ok 836 should be 204
,# teardown
,2017-07-14 11:33:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass a string to ThaliNotificationServer.start
,ok 837 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-14 11:33:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty parameter to ThaliNotificationServer.start
,ok 838 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-14 11:33:08 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2017-07-14 11:33:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:33:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:33:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:33:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:33:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:33:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-4,06D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:33:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:33:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:33:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:33:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-4,06D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:33:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:33:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:34:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:34:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-4,06D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server that is not listening yet witheatNotRunning set to true'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue and run in order'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly han,dled'
2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: ski,pped - skip'
2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiConnect properly fails on legal but non-existent peerID'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with invalid syncValue'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call disconnect with invalid peer id'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - disconnect doesn't fail on plausible but bogus peer ID'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get same port when trying to connect multiple times on iOS'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - initial peer discovery'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 1'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 2'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - check latest peer discovery'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Set up for no peer discovery test'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - no peer discovery'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits incomingConnectionState'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server connections all up'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can create servers manager'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling stop without start causes error'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can start/stop servers manager'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connection'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single local http request'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single coordinated request ios native'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple local http requests'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple coordinated request ios native'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status before starting'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - error returned with bad router'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are started when we call start'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP Servers Manager should be null when we call start on iOS'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are stopped when we call stop'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateConnection is properly hooked up'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateConnection is return error if we get called on iOS'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateListener is properly hooked up'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateListener is return error if we get called on iOS'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure we actually call kill connections properly'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from multiConnectConnection'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure bad PSK connections fail'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer changes handled from a queue'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - relaying discoveryAdvertisingStateUpdateNonTCP'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - we successfully receive and replay discoveryAdvertisingStateUpdate'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests between peers'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can still do HTTP requests between peers with coordinator'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - calls correct starts when network changes'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test to coordinate connection cut'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests after connections are cut'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - will fail bad PSK connection between peers'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We provide notification when a listener dies and we recreate it'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start - Causing native or wifi to fail will cause a promise reject '
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start should fail if called twice in a row'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not emit duplicate discoveryAdvertisingStateUpdate'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - does not send duplicate availability changes'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (native)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (wifi)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - new peer is cached'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with same port and different generation is cached (BLUETOOTH)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with greater generation is cached (MPCF)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with same or older generation is ignored (MPCF)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - new peer is ignored'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - cached peer is removed'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for wifi peers'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - new peer is ignored (MPCF)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (TCP_NATIVE)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort field (BLUETOOTH)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (MPCF)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - error when peer has not been discovered yet'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached wifi peer'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect fails on wifi peers'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect delegates native peers to the native wrapper'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes emitted correctly'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in started state'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in stopped state'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on Android'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on iOS'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not fire duplicate events after peer listener recreation'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #stop should change peers'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer should be found once after listening and discovery started'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get data from all participants'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - test for data corruption'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - test getters'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start and kill'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - double start'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start after kill'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - make sure ids are unique'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - check that forever agent can be destroyed'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary basic functionality'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary with multiple entries.'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - RESOLVED entries are removed before WAITING state entry.'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - WAITING entries are removed before CONTROLLED_BY_POOL state entry.'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - When CONTROLLED_BY_POOL entry is removed and kill is called.'
2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - single acti,on'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - multiple actions'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - PSK Pool works'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - stop'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that start verifies queue length'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - bad enqueues'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - do not allow same object type'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure we catch kill and dequeue'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that stop removes all actions'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized connection type'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized action type'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One action on bluetooth'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Two notification actions'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - replicateThroughProblems'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Replication goes first'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows many parallel non-replication actions'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows no more than 2 simultaneous replication actions for same peerID'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Client to server request coordinated'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test BEACONS_RETRIEVED_AND_PARSED locally'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test HTTP_BAD_RESPONSE locally'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test NETWORK_PROBLEM locally'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails when getPeerHostInfo fails'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the start two times'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill before calling the start'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill immediately after the start'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill while waiting a response from the server'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test to exceed the max content size locally'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the server socket while the client is waiting a response from the server. Local test.'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the client socket while the client is waiting a response from the server. Local test.'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons bad args'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons empty keys to notify'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons multiple keys to notify'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid expiration in beaconStreamWithPreAmble'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons no beacons returns null'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback fails decrypt'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns no matches'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns spurious match'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns public key'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskIdentityField'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecret'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecrets'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generateBeaconStreamAndSecrets'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Add two Peers.'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP_NATIVE peer loses DNS'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Received beacons with no values for us'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Notification action killed with a superseded'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally using ThaliPeerPoolDefault'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails because of a bad hostname.'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - hostaddress is removed when the action is running. '
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notificationClient does not retry action with BAD_PEER resolution'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notification client correctly handles peer availability changes of the same peer'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Client to server request locally'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache clean and expiration'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache getSecret and getPublic'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache multiple entries'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start and stop ThaliNotificationServer'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty array to ThaliNotificationServer.start'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass a string to ThaliNotificationServer.start'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - Pass an empty parameter to ThaliNotificationServer.start, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Application/52EEA99F-2246,-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/blue,bird/js/release/timers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1
''
,2017-07-14 11:34:08 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-07-14 11:34:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:34:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:34:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:34:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:34:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:34:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:34:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:34:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:34:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:34:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:35:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:35:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:35:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:35:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:35:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:35:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:35:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:35:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-4,06D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:35:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:35:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:35:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:35:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-4,06D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:36:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:36:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-4,06D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:36:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:36:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:36:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:36:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:36:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:36:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:36:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:36:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:36:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:36:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-4,06D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:37:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:37:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:37:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:37:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:37:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:37:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:37:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:37:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:37:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:37:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:37:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:37:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:38:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:38:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:38:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:38:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:38:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:38:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:38:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:38:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:38:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:38:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-4,06D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:38:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:38:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:39:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:39:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:39:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:39:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:39:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:39:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-4,06D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:39:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:39:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:39:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:39:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:39:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:39:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:40:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:40:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:40:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:40:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-4,06D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:40:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:40:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:40:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:40:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:40:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:40:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:40:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:40:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:41:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:41:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:41:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:41:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:41:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:41:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-4,06D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:41:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:41:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:41:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:41:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:41:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:41:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-4,06D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:42:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:42:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:42:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:42:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:42:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:42:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:42:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:42:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:42:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:42:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:42:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:42:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:43:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:43:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:43:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:43:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:43:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:43:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:43:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:43:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:43:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:43:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:43:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:43:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:44:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:44:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-4,06D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:44:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:44:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:44:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:44:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:44:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:44:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:44:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:44:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:44:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:44:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:45:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:45:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:45:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:45:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:45:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:45:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:45:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:45:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:45:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:45:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:45:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:45:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:46:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:46:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:46:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:46:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:46:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:46:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:46:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:46:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:46:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:46:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:46:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:46:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:47:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:47:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:47:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:47:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-4,06D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:47:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:47:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:47:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406,D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:47:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/52EEA99F-2246-4,06D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/52EEA99F-2246-406D-B80E-F21B69448165/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''

```
