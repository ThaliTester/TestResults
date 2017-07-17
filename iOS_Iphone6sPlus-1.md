#### Test 1271987109197780_iOS_Iphone6sPlus-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/1271987109197780/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/22BD589D-5C30-4ACD-8AE5-80894340C490/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'
,Executing commands in '/tmp/22BD589D-5C30-4ACD-8AE5-80894340C490/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/1271987109197780/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/1271987109197780/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63207"
,(lldb)     command script import "/tmp/22BD589D-5C30-4ACD-8AE5-80894340C490/fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.py"
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
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-07-17 11:35:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:35:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:35:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:35:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:35:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:35:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:35:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "13D80448-026D-4282-B5,8C-6C7EBC9C0EFC", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:13D80448-026D-4282-B58C-6C7EBC9C0EFC
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:099B9B87-EF05-4063-95DB-BC752033D49B
[ThaliCore] Browser,.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4C4A6CB0-,C05E-4593-8CAC-4A1581A05A03
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6527B74E-3BCD-4E53-AFF6-76755FE82D57", generation: 0)
[ThaliCore] Advertiser.startAdvertisi,ng with peerID:6527B74E-3BCD-4E53-AFF6-76755FE82D57
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6527B74E-3BCD-4E53-AFF6-76755FE82D57:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6527B74E-3BCD-4E53-AFF6-76755FE82D57", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo,rrect finished
AppContextTests finished
All tests finished
All tests finished
2017-07-17 11:35:37 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of fail,ed tests:  0
Number of ignored tests:  0
Total duration:  1.512712061405182
2017-07-17 11:35:37 - DEBUG UnitTest_app: 'My device name is: 'Apple-Iphone6sPlus-1''
2017-07-17 11:35:37 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:6527B74E-3BCD-4E53-AFF6-76755FE82D57:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "6527B74E-3BCD-4E53-AFF6-76755FE82D57", generation: 0)
,2017-07-17 11:35:39 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-17 11:35:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-17 11:35:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-17 11:35:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-17 11:35:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-17 11:35:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-17 11:35:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-17 11:35:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-17 11:35:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-17 11:35:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-17 11:35:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-17 11:35:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-17 11:35:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-17 11:35:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-17 11:35:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-17 11:35:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-17 11:35:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-17 11:35:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-17 11:35:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-17 11:35:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-17 11:35:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-17 11:35:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-17 11:35:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-17 11:35:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-17 11:35:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-17 11:35:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-17 11:35:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-17 11:35:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-17 11:35:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-17 11:35:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-17 11:35:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-17 11:35:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-17 11:35:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-17 11:35:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-17 11:35:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-17 11:35:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-17 11:35:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-17 11:35:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-17 11:35:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-17 11:35:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-17 11:35:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-17 11:35:41 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-17 11:35:41 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-17 11:35:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:35:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:35:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:35:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:35:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:35:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:35:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:36:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:36:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:36:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:36:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:36:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:36:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:36:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:36:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:36:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:36:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:36:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:36:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:37:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:37:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:37:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:37:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:37:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:37:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:37:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:37:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:37:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:37:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:37:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:37:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:38:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:38:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:38:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:38:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:38:26 - DEBUG CoordinatedClient: 'reconnected to the test server'
2017-07-17 11:38:26 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-17 11:38:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 1 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll with promise
,2017-07-17 11:38:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-17 11:38:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-07-17 11:38:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-07-17 11:38:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-07-17 11:38:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-07-17 11:38:33 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-07-17 11:38:33 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
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
,2017-07-17 11:38:50 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-07-17 11:38:51 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-07-17 11:38:52 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
,2017-07-17 11:38:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-17 11:39:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:39:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:39:00 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:39:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-17 11:39:00 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-17 11:39:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-17 11:39:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-17 11:39:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-17 11:39:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:39:01 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-17 11:39:01 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1A6C899F-FE11-41AF-AA97-89CA094D327F
[ThaliCore] Browser.startListening
2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-17 11:39:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-17 11:39:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvert,isements()
[ThaliCore] Browser.stopListening()
2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:39:01 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:39:01 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdver,tisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:39:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:39:01 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-17 11:39:01 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:EC663501-D590-4C7C-9A4D-58FAFE4211C5
[ThaliCore] Browser.startListening
,2017-07-17 11:39:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-17 11:39:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:39:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 66 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-17 11:39:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"di,scoveryActive":true,"advertisingActive":false}'
2017-07-17 11:39:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":",B,OTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:39:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call startListeningForAdvertisements twice without e,rror
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-17 11:39:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17, 11:39:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 68 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-17 11:39:02 - DEBUG thal,iMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:39:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-17 11:39:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:39:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:39:02 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:39:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:39:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:39:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:39:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:39:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-17 11:39:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:39:02 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 70 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-17 11:39:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingAct,ive":false}'
2017-07-17 11:39:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 71 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-17 11:39:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:39:03 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 72 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-17 11:39:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdver,tisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:39:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-17 11:39:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:39:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:39:03 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:39:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-17 11:39:03 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-17 11:39:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-17 11:39:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-17 11:39:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1C4285D6-7BBB-4DEA-B836-187838F720FC", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:1C4285D6-7BBB-4DEA-B836-187838F720FC
,2017-07-17 11:39:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-17 11:39:03 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:39:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:1C4285D6-7BBB-4DEA-B836-187838F720FC
2017-07-17 11:39:03 ,- DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:39:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 75 Can call stopAdvertisingAndListening without error
# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-17 11:39:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:39:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 76 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-17 11:39:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:39:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 77 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-17 11:39:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:39:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:39:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:39:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:39:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:39:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:39:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:39:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "09CE715A-4B24-45FF-AEAD-03751D721D23", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:09CE715A-4B24-45FF-AEAD-03751D721D23
,2017-07-17 11:39:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-17 11:39:07 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:39:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 78 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "09CE715A-4B24-45FF-AEAD-03751D721D23", generation: 1)
[,ThaliCore] Advertiser.startAdvertising with peerID:09CE715A-4B24-45FF-AEAD-03751D721D23
2017-07-17 11:39:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-17 11:39:07, ,- INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:39:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 79 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-17 11:39:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-17 11:39:07 - INFO thaliMobile: 'Receive,d state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:3,9:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 80 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertisin,g() peerID:09CE715A-4B24-45FF-AEAD-03751D721D23
[ThaliCore] Advertiser.stopAdvertising() peerID:09CE715A-4B24-45FF-AEAD-03751D721D23
,2017-07-17 11:39:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:39:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 81 Should be able to call stopAdvertisingAndListening in teardown
2017-07-17 11:39:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:39:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAd,vertisingStateUpdateNonTCP registered to native'
2017-07-17 11:39:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:39:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:39:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:39:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:39:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:39:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-17 11:39:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:39:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 82 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-17 11:39:08 - DEBUG th,aliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:39:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 83 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-17 11:39:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:39:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 84 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-17 11:39:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:39:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 85 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-17 11:39:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:39:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:39:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:39:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:39:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:39:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:39:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:39:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "71CDA35F-9267-45B6-A828-FDA702B4717C", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:71CDA35F-9267-45B6-A828-FDA702B4717C
,2017-07-17 11:39:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-17 11:39:08 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:39:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:53C526DE-272B-479F-8B91-44D3B2171,72E
[ThaliCore] Browser.startListening
2017-07-17 11:39:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-17 11:39:08 - INFO thaliMobile: 'Received state ({"discovery,A,ctive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:39:08 - INFO thaliMobil,e: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:072F8955-002F-4FB8-B690-7FD6A3751092:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "072F8955-002F-4FB8-B690-7FD6A3751092", generation: 0)
ok 88 peers must be an array,
ok 89 peers must not be zero-length
,ok 90 peer must have only peerIdentifier, peerAvailable and generation properties
,ok 91 peerIdentifier must be a string
,ok 92 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:71CDA35F-9267-45B6-A828-FDA702B4717C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "71CDA35F-9267-45B6-A828-FDA702B4717C", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-17 11:39:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-17 ,11:39:10 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-17 11:39:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 93 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:71CDA35F-9267-45B6-A828-FDA702B4717C
,2017-07-17 11:39:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:39:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 94 Should be able to call stopAdvertisingAndListening in teardown
2017-07-17 11:39:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:39:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:39:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:39:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:39:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:39:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:39:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:39:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6D26B543-6D86-4464-9151-F821BBB0AE6A", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:6D26B543-6D86-4464-9151-F821BBB0AE6A
2017-07-17 1,1:39:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-17 11:39:21 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:39:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 95 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:0A4575A2-3A49-41BB-BD72-8B94BB6A9FC9
[Thal,i,Core] Browser.startListening
2017-07-17 11:39:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-17 11:39:21 - INFO thaliMobile: 'Received state ({"discoveryActive":true,,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:39:21 - INFO thaliMobile: 'Filtere,d out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 96 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:613A62B9-F503-4283-BB13-6AFB671D570F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "613A62B9-F503-4283-BB13-6AFB671D570F", generation: 0)
2017-07-17 11:39:22 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"613A62B9-F503-4283-BB13-6AFB671D570F","generation":0}'
2017-07-17 11:39:22 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 613A62B9-F503-4283-BB13-6AFB671D570F, (syncValue: 7tMbVKa1wot7UV9g4TPvON3LIstWOVHM)'
2017-07-17 11:39:22 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "613A62B9-F503-4283-BB13-6AFB671,D570F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "613A62B9-F503-4283-BB13-6AFB671D570F", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:613A62B9-F503-4283-BB13-6AFB671D570F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3D697D64-8E3B-41E6-AC54-F02BB2C336FA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3D697D64-8E3B-41E6-AC54-F02BB2C336FA", generation: 0)
2017-07-17 11:39:22 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3D697D64-8E3B-41E6-AC54-F02BB2C336FA","generation":0}'
2017-07-17 11:39:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-17 11:39:22 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:613A62B9-F503-4283-BB13-6AFB671D570F:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6D26B543-6D86-4464-9151-F821BBB0AE6A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6D26B543-6D86-4464-9151-F821BBB0AE6A", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:613A62B9-F503-4283-BB13-6AFB671D570F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:613A62B9-F503-4283-BB13-6AFB671D570F:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "613A62B9-F503-4283-BB13-6AFB671D570F", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:51857
2017-07-17 11:39:25 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"7tMbVKa1wot7UV9g4TPvON3LIstWOVHM","error":null,"portNumber":51857}'
2017-07-17 11:39:25 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '7tMbVKa1wot7UV9g4TPvON3LIstWOVHM', error: 'null', listeningPort: '51857''
,2017-07-17 11:39:25 - INFO testThaliMobileNative: ''
ok 97 Must have listeningPort
ok 98 listeningPort must be a number
ok 99 listening port should not be 0
,# teardown
,2017-07-17 11:39:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-17 11:39:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-17 11:39:25 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:39:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 100 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:6D26B543-6D86-4464-9151-F821BBB0AE6A
2017-07-17 11:39:25 - DEBUG thaliMobileNativeWr,apper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:39:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 101 Should be able to call stopAdvertisi,ngAndListening in teardown
[ThaliCore] BrowserManager.disconnect peer:613A62B9-F503-4283-BB13-6AFB671D570F
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:51857
[Thali,Core] Session.disconnect() peer:613A62B9-F503-4283-BB13-6AFB671D570F:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:613A62B9-F503-4283-BB13-6AFB671D570F:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-17 11:39:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:39:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:39:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:39:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:39:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:39:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:39:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:39:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "EB99FC28-FDE5-47DF-88AC-5B18CA1373EE", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:EB99FC28-FDE5-47DF-88AC-5B18CA1373EE
2017-07-17 11:39:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-17 11:39:27, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-17 11:39:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 102 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Tha,liCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:12625EC5-6A4D-4CF0-9EAB-D40EAED969C2
[ThaliCore] Browser.startListening
2017-07-17 11:39:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adv,e,rtisingActive":true}'
2017-07-17 11:39:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"rou,ter":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:39:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 103 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:613A62B9-F503-4283-BB13-6AFB671D570F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "613A62B9-F503-4283-BB13-6AFB671D570F", generation: 0)
2017-07-17 11:39:27 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"613A62B9-F503-4283-BB13-6AFB671D570F","generation":0}'
2017-07-17 11:39:27 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 613A62B9-F503-4283-BB13-6AFB671D570F, (syncValue: 0GhylQFn481EQWckJOHQw8jknMl7HN7H)'
2017-07-17 11:39:27 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "613A62B9-F503-4283-BB13-6AFB671,D570F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "613A62B9-F503-4283-BB13-6AFB671D570F", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:) peer:613A62B9-F503-4283-BB13-6AFB671D570F:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3D697D64-8E3B-41E6-AC54-F02BB2C336FA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3D697D64-8E3B-41E6-AC54-F02BB2C336FA,", generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-17 11:39:27 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailabl,e":true,"peerIdentifier":"3D697D64-8E3B-41E6-AC54-F02BB2C336FA","generation":0}'
2017-07-17 11:39:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-17 11:39:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:09DC3B5D-BE85-4C89-8D0B-68348FA2CA72:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "09DC3B5D-BE85-4C89-8D0B-68348FA2CA72", generation: 0)
2017-07-17 11:39:28 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"09DC3B5D-BE85-4C89-8D0B-68348FA2CA72","generation":0}'
2017-07-17 11:39:28 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-17 11:39:28 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-17 11:39:28 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EB99FC28-FDE5-47DF-88AC-5B18CA1373EE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EB99FC28-FDE5-47DF-88AC-5B18CA1373EE", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:613A62B9-F503-4283-BB13-6AFB671D570F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:613A62B9-F503-4283-BB13-6AFB671D570F:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "613A62B9-F503-4283-BB13-6AFB671D570F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,13A62B9-F503-4283-BB13-6AFB671D570F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "613A62B9-F503-4283-BB13-6AFB671D570F", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:613A62B9-F503-4283-BB13-6AFB671D570F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9D7996ED-C4B3-4E8B-A736-13A79E300A64
[ThaliCore] Advertiser: session connected Peer(uuid: "EB99FC28-FDE5-47DF-88AC-5B18CA1373EE", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] Session.session(_:peer:didChange:) peer:9D7996ED-C4B3-4E8B-A736-13A79E300A64 state: notConnected -> connecting
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Session.deinit peer:613A62B9-F503-4283-BB13-6AFB671D570F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E8D0C536-7136-43E6-A780-C955908E4A7D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E8D0C536-7136-43E6-A780-C955908E4A7D", generation: 0)
2017-07-17 11:39:29 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E8D0C536-7136-43E6-A780-C955908E4A7D","generation":0}'
2017-07-17 11:39:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-17 11:39:29 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-17 11:39:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-17 11:39:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:613A62B9-F503-4283-BB13-6AFB671D570F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:61,3A62B9-F503-4283-BB13-6AFB671D570F:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "613A62B9-F503-4283-BB13-6AFB671D570F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,13A62B9-F503-4283-BB13-6AFB671D570F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "613A62B9-F503-4283-BB13-6AFB671D570F", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:613A62B9-F503-4283-BB13-6AFB671D570F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:613A62B9-F503-4283-BB13-6AFB671D570F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:613A62B9-F503-4283-BB13-6AFB671D570F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:61,3A62B9-F503-4283-BB13-6AFB671D570F:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "613A62B9-F503-4283-BB13-6AFB671D570F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,13A62B9-F503-4283-BB13-6AFB671D570F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "613A62B9-F503-4283-BB13-6AFB671D570F", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:613A62B9-F503-4283-BB13-6AFB671D570F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:613A62B9-F503-4283-BB13-6AFB671D570F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:3D697D64-8E3B-41E6-AC54-F02BB2C336FA:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "3D697D64-8E3B-41E6-AC54-F02BB2C336FA", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9D7996ED-C4B3-4E8B-A736-13A79E300A64
,[ThaliCore] Session.session(_:peer:didChange:) peer:9D7996ED-C4B3-4E8B-A736-13A79E300A64 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9D7996ED-C4B3-4E8B-A736-13A79E300A64
[ThaliCore] Session.startOutputStream(with:) peer:9D7996ED-C4B3-4E8B-A736-13A79E300A64
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-17 11:39:31 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-17 11:39:31 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-17 11:39:31 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-07-17 11:39:31 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:1
[ThaliCore] VirtualSocket.closeStreams() vsID:1
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:613A62B9-F503-4283-BB13-6AFB671D570F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:61,3A62B9-F503-4283-BB13-6AFB671D570F:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "613A62B9-F503-4283-BB13-6AFB671D570F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:613A62B9,-F503-4283-BB13-6AFB671D570F error: max retries exceeded
2017-07-17 11:39:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0GhylQFn481EQWckJOHQw8jknMl7HN7H","error":"Connection could not be established","portNumber":null}'
2017-0,7-17 11:39:31 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '0GhylQFn481EQWckJOHQw8jknMl7HN7H', error: 'Connection could not be established', listeningPort: '%s''
2017-07-17 11:39:31 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"613A62B9-F503-4283-BB13-6AFB671D570F","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-17 11:39:31 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-17 11:39:31 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"613A62B9-F503-4283-BB13-6AFB671D570F","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-17 11:39:31 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-17 11:39:31 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5175208D-F083-4D40-B64F-794FF141DDD1
[ThaliCore] Advertiser: session connected Peer(uuid: "EB99FC28-FDE5-47DF-88AC-5B18CA1373EE", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:5175208D-F083-4D40-B64F-794FF141DDD1 state: notConnected -> connecting
2017-07-17 11:39:31 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 09DC3B5D-BE85-4C89-8D0B-68348FA2CA72 (syncValue: WLI6QLq891HtYkM5Se0SIKkFZYOFCCCE)'
2017-07-17 11:39:31 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:compl,etion:) Peer(uuid: "09DC3B5D-BE85-4C89-8D0B-68348FA2CA72", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "09DC3B5D-BE85-4C89-8D0B-68348FA2CA72", generation: 0)
[ThaliCore] Sess,ion.init(session:identifier:connected:notConnected:) peer:09DC3B5D-BE85-4C89-8D0B-68348FA2CA72:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-0,7-17 11:39:31 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-17 11:39:31 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:613A62B9-F503-4283-BB13-6AFB671D570F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:09DC3B5D-BE85-4C89-8D0B-68348FA2CA72:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5175208D-F083-4D40-B64F-794FF141DDD1
,[ThaliCore] Session.session(_:peer:didChange:) peer:5175208D-F083-4D40-B64F-794FF141DDD1 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5175208D-F083-4D40-B64F-794FF141DDD1
[ThaliCore] Session.startOutputStream(with:) peer:5175208D-F083-4D40-B64F-794FF141DDD1
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2, [1, 2]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-17 11:39:34 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-07-17 11:39:34 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
2017-07-17 11:39:34 - DEBUG testThaliMobileNative: 'Server sends data bac,k to client (20 bytes):'
2017-07-17 11:39:34 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:2
[ThaliCore] VirtualSocket.closeStreams() vsID:2
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:with,Error:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:09DC3B5D-BE85-4C89-8D0B-68348FA2CA72:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:09DC3B5D-BE85-4C89-8D0B-68348FA2CA72:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "09DC3B5D-BE85-4C89-8D0B-68348FA2CA72", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:51868
2017-07-17 11:39:35 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"WLI6QLq891HtYkM5Se0SIKkFZYOFCCCE",,"error":null,"portNumber":51868}'
2017-07-17 11:39:35 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'WLI6QLq891HtYkM5Se0SIKkFZYOFCCCE', error: 'null', listeningPort: '51868''
,Connecting to the localhost:51868
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:09DC3B5D-BE85-4C89-8D0B-68348FA2CA72:0
Connected to the localh,ost:51868
2017-07-17 11:39:35 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
2017-07-17 11:39:35 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:09DC3B5D-BE85-4C89-8D0B-68348FA2CA72:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [1, 2, 3]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 104 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
# teardown
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:3
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:3
,[ThaliCore] VirtualSocket.deinit vsID:3 [1, 2]
,2017-07-17 11:39:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-17 11:39:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-17 11:39:35 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:39:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 105 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:EB99FC28-FDE5-47DF-88AC-5B18CA1373EE
2017-07-17 11:39:35 - DEBUG thaliMobileNativeWr,apper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:39:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 106 Should be able to call stopAdvertisi,ngAndListening in teardown
[ThaliCore] BrowserManager.disconnect peer:09DC3B5D-BE85-4C89-8D0B-68348FA2CA72
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:51868
[Thali,Core] Session.disconnect() peer:09DC3B5D-BE85-4C89-8D0B-68348FA2CA72:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5175208D-F083-4D40-B64F-794FF141DDD1 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "EB99FC28-FDE5-47DF-88AC-5B18CA1373EE", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
,[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:5175208D-F083-4D40-B64F-794FF141DDD1
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:09DC3B5D-BE85-4C89-8D0B-68348FA2CA72:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-17 11:39:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:39:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:39:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:39:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:39:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:39:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:39:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:39:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:9D7996ED-C4B3-4E8B-A736-13A79E300A64 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "EB99FC28-FDE5-47DF-88AC-5B18CA1373EE", generation: 0)
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4B7E8D7E-A7F8-444B-9652-0AE90AED8376", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:4B7E8D7E-A7F8-444B-9652-0AE90AED8376
,2017-07-17 11:39:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-17 11:39:35 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-17 11:39:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 107 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:0DADBCFB-6B0A-4018-943C-1F6F4172E508
,[ThaliCore] Browser.startListening
,2017-07-17 11:39:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-17 11:39:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-17 11:39:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 108 Can call startListeningForAdvertisements without error
,[ThaliCore] Session.deinit peer:5175208D-F083-4D40-B64F-794FF141DDD1
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E8D0C536-7136-43E6-A780-C955908E4A7D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E8D0C536-7136-43E6-A780-C955908E4A7D", generation: 0)
2017-07-17 11:39:36 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E8D0C536-7136-43E6-A780-C955908E4A7D","generation":0}'
2017-07-17 11:39:36 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for E8D0C536-7136-43E6-A780-C955908E4A7D, (syncValue: iohypdlK6QI2rTEz2ni4CL7x1SiGTXHZ)'
2017-07-17 11:39:36 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E8D0C536-7136-43E6-A780-C955908,E4A7D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E8D0C536-7136-43E6-A780-C955908E4A7D", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:E8D0C536-7136-43E6-A780-C955908E4A7D:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:09DC3B5D-BE85-4C89-8D0B-68348FA2CA72:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "09DC3B5D-BE85-4C89-8D0B-68348FA2CA72",, generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-17 11:39:36 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable,":true,"peerIdentifier":"09DC3B5D-BE85-4C89-8D0B-68348FA2CA72","generation":0}'
2017-07-17 11:39:36 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-17 11:39:36 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E0CF7079-E931-4613-8F13-41A68FDA7BF3", generation: 0)
2017-07-17 11:39:37 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E0CF7079-E931-4613-8F13-41A68FDA7BF3","generation":0}'
2017-07-17 11:39:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-17 11:39:37 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-17 11:39:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:E8D0C536-7136-43E6-A780-C955908E4A7D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:E8,D0C536-7136-43E6-A780-C955908E4A7D:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "E8D0C536-7136-43E6-A780-C955908E4A7D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,8D0C536-7136-43E6-A780-C955908E4A7D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E8D0C536-7136-43E6-A780-C955908E4A7D", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:E8D0C536-7136-43E6-A780-C955908E4A7D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:E8D0C536-7136-43E6-A780-C955908E4A7D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:09DC3B5D-BE85-4C89-8D0B-68348FA2CA72:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "09DC3B5D-BE85-4C89-8D0B-68348FA2CA72", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:523A7280-3273-4765-AF24-D29D03483576:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "523A7280-3273-4765-AF24-D29D03483576", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4B7E8D7E-A7F8-444B-9652-0AE90AED8376:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4B7E8D7E-A7F8-444B-9652-0AE90AED8376", generation: 0)
2017-07-17 11:39:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"523A7280-3273-4765-AF24-D29D03483576","generation":0}'
,2017-07-17 11:39:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-17 11:39:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-17 11:39:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:E8D0C536-7136-43E6-A780-C955908E4A7D:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:E8D0C536-7136-43E6-A780-C955908E4A7D:0
,[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "E8D0C536-7136-43E6-A780-C955908E4A7D", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E8D0C536-7136-43E6-A780-C955908E4A7D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E8,D0C536-7136-43E6-A780-C955908E4A7D", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E8D0C536-7136-43E6-A780-C955908E4A7D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:E8D0C536-7136-43E6-A780-C955908E4A7D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:E8D0C536-7136-43E6-A780-C955908E4A7D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:E8,D0C536-7136-43E6-A780-C955908E4A7D:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "E8D0C536-7136-43E6-A780-C955908E4A7D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,8D0C536-7136-43E6-A780-C955908E4A7D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E8D0C536-7136-43E6-A780-C955908E4A7D", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:E8D0C536-7136-43E6-A780-C955908E4A7D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:E8D0C536-7136-43E6-A780-C955908E4A7D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:E8D0C536-7136-43E6-A780-C955908E4A7D:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "E8D0C536-7136-43E6-A780-C955908E4A7D", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:E8D0C536-7136-43E6-A780-C955908E4A7D:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "E8D0C536-7136-43E6-A780-C955908E4A7D", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:E8D0C536-7136-43E6-A780-C955908E4A7D error: max retries exceeded
2017-07-17 11:39:40 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"iohypdlK6QI2rTEz2,ni4CL7x1SiGTXHZ","error":"Connection could not be established","portNumber":null}'
2017-07-17 11:39:40 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'iohypdlK6QI2rTEz2ni4CL7x1SiGTXHZ', error: 'Connection could not be establishe,d', listeningPort: '%s''
2017-07-17 11:39:40 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"E8D0C536-7136-43E6-A780-C955908E4A7D","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-17 ,1,1:39:40 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-17 11:39:40 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"E8D0C536-,7136-43E6-A780-C955908E4A7D","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-17 11:39:40 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-17 11:39:40 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-17 11:39:40 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for E0CF7079-E931-4613-8F13-41A68FDA7BF3 (syncValue: gFEj5UA,WL1FNJFdXGsKqlTE5jmDuqG2i)'
2017-07-17 11:39:40 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E0CF7079-E931-4613-8F13-41A68FDA7BF3", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E0CF7079-E931-4613-8F13-41A68FDA7BF3", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E0CF7079-E931,-4613-8F13-41A68FDA7BF3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-17 11:39:40 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-17 11:39:40 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6FE84F03-A547-4FBC-ABF4-B6EE9FBB59CE
[ThaliCore] Advertiser: session connected Peer(uuid: "4B7E8D7E-A7F8-444B-9652-0AE90AED8376", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:6FE84F03-A547-4FBC-ABF4-B6EE9FBB59CE state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6FE84F03-A547-4FBC-ABF4-B6EE9FBB59CE
,[ThaliCore] Session.session(_:peer:didChange:) peer:6FE84F03-A547-4FBC-ABF4-B6EE9FBB59CE state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "E0CF7079-E931-4613-8F13-41A68FDA7BF3", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:51888
2017-07-17 11:39:44 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"gFEj5UAWL1FNJFdXGsKqlTE5jmDuqG2i",,"error":null,"portNumber":51888}'
2017-07-17 11:39:44 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'gFEj5UAWL1FNJFdXGsKqlTE5jmDuqG2i', error: 'null', listeningPort: '51888''
[ThaliCore] Session.session(_:didReceive:withName:f,romPeer:) peer:6FE84F03-A547-4FBC-ABF4-B6EE9FBB59CE
[ThaliCore] Session.startOutputStream(with:) peer:6FE84F03-A547-4FBC-ABF4-B6EE9FBB59CE
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [1, 2, 4]
[ThaliCore] TCPClient.connectToLocalho,s,t(onPort:)
Connecting to the localhost:51888
Connecting to the localhost:51888
Connecting to the localhost:51888
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutput,Stream(with:) peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0,
,Connected to the localhost:51888
Connected to the localhost:51888
Connected to the localhost:51888
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6FE84F03-A547-4FBC-ABF4-B6EE9FBB59CE
[ThaliCore] Session.startOutputStream(with:) peer:6FE84F03-A547-4FBC-ABF4-B6EE9FBB59CE
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [1, 2, 4, 5]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6FE84F03-A547-4FBC-ABF4-B6EE9FBB59CE
[ThaliCore] Session.startOutputStream(with:) peer:6FE84F03-A547-4FBC-ABF4-B6EE9FBB59CE
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [1, 2, 4, 5, 6]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [1, 2, 4, 5, 6, 7]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [1, 2, 4, 5, 6, 7, 8]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [1, 2, 4, 5, 6, 7, 8, 9]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 109 correct string length
,2017-07-17 11:39:44 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 110 correct string length
,2017-07-17 11:39:44 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 111 correct string length
,2017-07-17 11:39:44 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-17 11:39:44 - DEBUG testThaliMobileNative: 'Client data flushed'
2017-07-17 11:39:44 - DEBUG testThaliMobileNative: 'Client data flushed'
2017-07-17 11:39:44 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-17 11:39:44 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-17 11:39:44 - DEBUG testThaliMobileNative: 'Server received (8760 bytes):'
,2017-07-17 11:39:44 - DEBUG testThaliMobileNative: 'Server received (3244 bytes):'
2017-07-17 11:39:44 - DEBUG testThaliMobileNative: 'Server received all data: xE26XGAOgbHvrU2sHrf1CqVaFtod1LLeB3Og3rKyIeTKaIkrapqEAufj5BSMprGpPQlfStDyubdT87bpWVWF5ejVWzV9dW,WDRFMLytKjSudj34B58lmwzPqYE4PayWTjMLYbjLxhU4uLDd2xSN4l06UDoTjS1Z20ZrNOTW7TRbIPqI52uo3HxxbIwlTJ5VLdQklihn0Qn2JvXq9w8cYif60jydRRMf52xgwmlp9v2tQdwSZlQhevLh5xfffHAiR4vvmY1AKcaC2ZNajpoA5xzTDLTLeDUzHly1AuIBFrw5dHtF8GQFEv9b0qQbVwNzQIlZ4IFOEOcLoKI5yv32i1xrLes4EtNS,G4CpJWLzhekn0zRMqN7OCO7rfgiFN9iqs25fJ4kbQhkThLJSYtoFb8h7vSbcVWeJWRKuKg5xqXHT0yAM3VJI3EVlu1szeN4QbnAd6YXatoX1l6ZyLT4K92mBOA3Bc8jWFWbp9bYMc2y8LyUb4VT9xtk9qVACsRRrtwee2JSfWdONaO8yEZxZQgnB8lTqhMDEs742Is1ez1WkTcDBws7aMioVJaZ8pM4X5jez1te61pJRELFkrLm8YxWjMPhrfuDs3bYmSGMksVFqW3xbefyTZw0CCvzLwykQRa7ReJyjfK4gbOdzERpIAOXZrmGI9mGGRbJWcpjFIYcHLHyAnaLHoeVVhgiIVMSrjZX5yk8Pk3T5j0YVvw4m2Yuaq194mMkdXAh1e5mAVgfjh7EbvRLYhGtep9SDViEVDtxLbELrOup8nAL7XJaZB2L2zER38fJYSOLiBYQXbHJwTVkaHxB1kFu56e3AM5s3NCyY5PnjgnKQNIFmI13lU6sppSWI7sND,FGNFVsciYqj7hhUyYczRCPjL84d7CbM3ZWap6VfL892OY6O0oMwMbKfU9YtTcO9qIRcGegWWAx1vtxAwQlHAaTZ1wg3Zgm3pMxjEhXLP53wpqlRGPVXehQY5xEnIDN9g2pKe7VfUL3SaHjr5fDHsxNV3O4zunRh2NOcjfhCZ8EUzTA83g2rQixTVpeKxJfCAjY02y7eDIq3s2LR0aqu2DEYvLZSNWxTESVJnVBK1az98R2f4UAu3amJ1G2MfoPWi,7esCsei2tXRa8UtcM0KYEWxlGft9PdUmeShqg2EqO8kqjaoobtP6S58FJxYniXCpsKcUFvBputGSsZSpWzCaHnSVtZDZOLzavQniEZ44l66q49zCOOMhOWunxc3EJ9EztSJMXBwYZdaycs8RI6MtLQaZNO8HAHEnEF1bARgMxYKSwkGE01N10oUYhI2F1xvaWXScvvS2n15W71nvEakF9nqDzL30VndEoNdZH8TlWCckQEdYWil2a4PkPQ3f7Jb0,pNZgRxlG161rGQRXmdC8gHSz4TWR3tXMcZ7mCip8f91pcnPxSoW1RDxxwPaJ6UKhZtd2lOPzFnJp6OiWwKRbCvBXk8yw0y8aj4MhyuINpD4HtYbypItYWjQ5Vomw9ARTYus62EL7YIvLIUFjqfJe9UoJLTVW0fl4fSwUfDrymllFbuP3FozeuRW1FWbjfK1FlOIxeo508tasgDlhAcpLVX9di6eCLdMkXUWR92C9CS6Nc7R3rcT6Nxhel8dyZ8Jl,GMmnOwkB9m7bebWqGvTbsqpwKMa1XCQIxyHNSlcG7K6XdSN7ruRSFkhn9td0LmUjsn4rOIAjMYLMO8bZ6BnTudHQFm5dDhRmJZ7Slsj8nbsEFhAHVTE0Q81S71B86ME8lXXcox40hjOGZETEnYAg6QVj9AR411Sx8n2pFwOwDUVa205l0wjeNcPAX5x6QkgOWrn1nJmUk9UvnHoYa5ScfcCyRK2oXttnXyGzdELELTzBmiigNr7YIhyZoWSI3Xj,3,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,5,iNCAqFRQNgdxFX3hBtuqdjKAm7AzXKlo4iZfrelH7EkqCP6GnF6ErZvYMM9ZiVNV9dpWnyucAfGE8RLmAKWPtNuiCaCoSzWR3NveKeQumju2IzfXDYVhnIy54lSiFbvTf2DAZgjH9VHcZkfYpBzD1BywxXRsjcQexeeXYRSGxn5Yq7XYTx9hMdQsslYVBJ1QGz4X5gzbRKtvAmqXmjDzf78NEFh8YeQyCIEG8y8lLPNtDi9VSJD8XVTtlVC7duUV,qpCnFJYNEESnJORM5DiwBviIC3CvQ8BN9HJt9G6fkwftykwgItfMMttMCaHJym9BPE6fmKqDozILH51IQ6fgXDRW0vhzgPcbvHooYfmBeuwxjW0H05GS3q3Ek6Zuq0LXgZW4NZOlqtdk9oa6QLeIHhyPa8rxFVrMv7AOqq0ppipc6Qr4f21XzZHcMBNGP44QV7rAYl7GlkZ5rHwT5BCMwQkmpVczjIyvC197SJ0K2b4Cld1mifaFuiWWBxdThe7H,STukwfIYreHfPeja0UWXsf8lauwBztb7TtXhGRbxfcOhDMAGY0gWvloHDvZGkvOImYzJ4NPntszzRiSL8sMhWMDTyFSE3TneLTp0X34KvoV5l0ol9tUX90qpb5cm9uxtfEouXf9WGDYrqm8KCpHWBSbgOBnPpsffve8vEUAQbiAZwYPEBITIreKlSokl0jlxGxoXIBCpjPgND5NVgAgmmdOKzhgVRDVG4onwv0kZtIu0XYOYLCEGcxOOfQxYdkMQ,FUGKSuiRDJfn7udMuv9bUPJQTDeXrcSXSuulWzl8MsQSFVAwj26L6FTzxW5iK9Fh9BNH19jEswGd62KddCpAHRqSTs5X3VUuKc3hPYryvhiCr1K7R4k9jLu0rfmpfnSLQkqVcdOSIcKOoKAKyjkUQUDxkIiq52x4693F95hsCioV8on6bnYesSqmUePFuCLseIMIdNMkizaGtUCmrEwqA72qebiqXduwgIOOTAoDkFwsL9eL5AyyKi1RulNxW41,u,aJUokfT9iIZd1gqapuXV2sXsXYkqfjIkUPPq87lGsc51tkZlBn6zRdpQUXK69clT2OlIU5DMpIZtOGWivPxj766U1tbhk8T4SDDMaXOpciIaMBuxebDT6S8r0Z9em5RSdOz5XQ0A3IF6XayV6maDJAhFTpbB2i3eGvk2c0ItXg76bUJ1rzUBHxy9XKztSKDHGBMWSYroZ1XMk5dZFMTy3u1HRYlmD918FKi3J2a0Op4KYhtElV8uY0u0vAd71tkd,xEqUc1RsB6qs3brmsGYiBMJa9XabECcyQa9rzfRC5ZzcFw19HWFDuhsR3GjyZYxm5LVVZ2ZksEhqjzzaqXx6kHhkc0PvlS2r142La0PLbQTuJfxUVoCtGObHKqzOAWDF8piX6ZPfEgrH71xcG0J61qT9U1kK3TLN77w60lT9Mvxy8Brjs0HTdkTsy1Z9lvnS9agQ5PD4dKJdstbG9P77ZE7keKAVPvMhPV9SMeZ2N1cvAKUeAJdOR8MtC42GaIXi,TReW8dM8zrdIAZdRHnEA1e2JfpZ0LjgUL3ZIHmITQPWQitUUo9lCqNb9L9x3G5Ii89NN0RrNgm728K0BbvUcY1ekHdCqi7IvEy6yjAtVI0PPQX6y2NbwJmvNiNWfMKSFoiY7BXXs5AIBE52MCyZXKhiJaqv6pQuQEDVJN8I0BIcEqKMgMxewGtftNnW6NDmmLk8xrk1NyxtKf7of0eB8EwUsVjeWnAszFu0o2W4vGblAwR1DcYOXXRtxVIGbqyji,NKnTCJesK47v5AqUzWgCzIP0H6WSgmK3VivEthtISCTxhPoZLMoCvCeq6fk1AvQB9gJuwXLyN9gGAq3CT2xZdraHEWNTrPNAeC0aYSFHrIjDwc83CifGB3VGFRP30VAbM60nC0sKOfeCWxtIAhxZ3FYhBxAdOTrZAgUAiJjv2byKOMmx3tKB8rFU776JGs2jQjonGkGobj0ZEmZ5kVsWkW86iyLad4Fqq5pR2l45CjuPxMbR6pEmcwId9IVvyMl,J,B9D5nlqB9bapkq40zOcx5MUzOlfuVAq1c8UUGkRCUN4XCTeD2RpSsnf5Yu7gfvcgqq7nr6aCLf0Akh2BqZMFvHK2rpSGZV4F9Rcs8e0HARfHIU84KBaMlksswgcS3pDUY0LCJgljp6IeARpPU56L9R5Bjf7dlw27REFeWuEgfdGOPBq66QLN1eeKeg6GGkT127tMxG9bv9gQeP1vRadJxbzlIXRKmBjtWMxGB9dU5IBhUFEwiamVPe1eD12cWTgN,t9vusk7y6W8OcwACDuQLbP0rcxSWx1ZiMhoVtPTxqZyTIDejjZDWKqXgr0kCwva0LET2EayaHqSUFFvAxGCMzvX7t5Via6MBrtBaSgbJVizzIMEvew2izhQVxfYx9fecm9Zp7VaVqfj0JCLkI23ch6iCCesF7DFX69fLtwQsVSQdhzjCyq5AL5Rnqpuy3OZEFmknOtlJNSOMrkygYpEfeIjlQU1wVYAQhnDL7EQFKbMKFVaAUfgosPs2rshfZTwZ,YajZ0Zal3JJBs9xCvnIhimeQuZ30UNTVhQhZuF3Tbr7LXuwG3t7ETWWrhCte4rYPdV7Xdr1u9yWazFgLTq68qzLjAHVDuSB14rHwxly2ugBmApDfNOkF2lxqcdiehjOQ8HBOhqZqPb9j2lYsbDcUKxh0pLBqryvitgA4cPYZGzL7yYNC6m67vmHDvPTksm6wFGu5fUgieZuTCaFKiKdW02tQZAAdXwMkxUuIDcwJS4ewHiXKDoU3mIVgK3LRN3sQ,aBOeLySMNgYkRbQqI1YYq6YNfwsH2rl1YxiZE0Le6q6ccRBijTsAF2CG46tFx9g4QMfoyD0nO6m7LLt80PK5kmMjhtmlxboAQVQiRdEHgnaW7NElKvWhtUdTHOqZ6y8dCIed31rksiwow3rhI0phPTQQReYGjAzdFoo6CyvIUcn4itoWfzCmBkZzp5nZPsYaDrEUkXRt0UGrINCF96WEgF3y5OSaAw1EcyZTDLccPGQIAIQtEnnOrDLhCfDlEbn,x,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,c,aqf3jkDfmiSK54t0uHm0B0g0uSWFBH1gulyG79gZg6goL3fettlWM8BgWk3AgByBdHt909XTcGkkWSXx0ICUjBabfiEmMZgnOm1sjE4ebbj9xZSR655fBhStRwh2ioAzijTReK5US3vGPi71tjltADA5IyDVE6P3D2nBdJSyuqHfEg071yEwgzHTaO1hDr1p4enY9JJLwJzATsernyvak4IJ80DOAm15m8A9WNIvfoaCiKZfVWxNZAvaKEquqs6z,Yc2GhwKVWFpWKjJSXwtfy0C5LzYSDYXBIXQs4pgDUZxGjTTlQDrOLE5RNhsYBNH3IgNAwtR3f0YMH18eXaiXwpHcxPd1ZTho6g8M1Iyssvw1MW9VywJUzfyEwSphEX3XF1XMr73X6cQlxghxdqjSZVpiLhOrEtItNgzab54aAY1YK2soW0PN0tSq88ObexhJ9nJXhYP0eJ7P3ZukHL3OiKHVANjK8blJjHeeaYarMr4ki5jaVT6sF59nzz9LUaTF,K11CGDVrRxoOYxdlbzXT3h6z50qwSDvyG8SOdi1TZEO2G7rY24lbAZlFC9s2g02G9MSJf8VCeY7MSWMEZjHQqiuIuYgOewULJZNS9ZGvvc3oUQ9wENenx0KNsO2lsY3RSPpHPxPjTRIWqwFOPjCWDPKXkeC6DI1OOoixlhLxs0Oly1mPPYhFjtNKRol8EuYlCulq9OhhYTXlV7OLP1OP0RRQkYNbrcGVdPyjRYByadQN5X0r5YKa3xlFeeEch16d,I3uTH0PcKGjWsDt82UxSvfg31SpRggXo2uAQC8ILYPaSKhusiPiP7Pp0lntEPDsZp6VRTU1kuTwg8ufFn9FNzJQxZGcIhmRy3kSOCmytns33Kz2JKsbAZYEsEdyH6t2iQ8M2pMiTCIT3wlzhBuNo5s9OuBv2cii9dOSuK80VhEXfxj0A8KcegzuPo7upViLpu1xzWIdR1vbklARUec1A7TposbkdBjbP6CFCtzUWDC37mXTHK5L0isjOToLtL9c,Q,l7ol03qWrIJhWG8gdgkgZfQUnWM3MmaaL9WDYaZu1pdpdjN865itBp1m0h1hcGPo8MM65RUhmNwlnKxO7azTcBrSyBDH8iqYo5UtT5k7mKr7KgxdTA5yJ34avwXLs1zbdbW8HCXd2C8RZRzvJsQuRo7nuLtxeSiINykVlcUjeTnvHc7payhwntRXzlJ169WRaj8RaxVhWCakJbjpOrZiFigAjxKLv9BPwuBjobaDGQUaOV9o15edRVqlQg9q3HNC,7aNlt97vLUOXmHnlajHSIZwsYc1f5DGeD0cc5cEVnVnylIhNNSokRqlAYjdPk6R5JnFcQ2nEvFxHX93aERR9TXdmmnLl2Cb1OWlZzSkMeIQnK2t8sIBaYY6shsXOnRzyrXkS3wa052Z8JxPAK6SMnLI7kSEDkoOxmzjxwt3kQMYlCL83tOZZtp86kB12k3MRYlhEnZUMuKyncsvsQdUMH3VKHmoPXWt8EnUiqdHPQ6wbsdPATew9EsqiB4H48llF,Hfwoi10ut4IA40e2UQwRvOKFdrs8UCuNv0B9Syx3ntZEEMFSErDuwRBR1SawrSnYB13AAlCd7zYsKKpWF4JnJOMBGbxR3yVZUJp2vfl6eAzccO6wjpfRQPT6JlWLJYhxKjpyny6R1r8E057WdbcTZBLweMIHnljoo8Ifz8boAx7P1GgsHTh9q5dRKFE13nLS9EInro0P3ExL3iOcHpYAfjjSDbGVUbs32vNomUwbFHl2rvXjjrbazqtKc0eRsijI,9VIHbm8mMyfAohNTgDqotBasRREn8uyBijew8t3g8yuEWfUhw77CSmCCleVPVyBOnvxRs7hdNW3iJhu1nLPvltSq5mlgzYouupnge8ydQfhr1jpvBph8G1LEW2b7UKKsV6QqJeffOkdVg8kHhS6RNsnZ8RY0eOI9jBatlfQ8Xb1IrRnmFrpZJ1j4M2qDqhbDSG2gCFVLhosPGPfbzUEairJcUEoWPdAXz8XlagGZoZk0JegkblBCH7nfHBTO58E,2,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,s,AqOvl9oJWcBJSaVv9IspysQhGqbMvs40vhwXUJxeZeS3X9cyDuS3KDEvaSD3FM0pDa9rued9hkM5Ncs9Dyphur50OPnm9j4i4M9egy9BBQgdSsjq3UPmLpnOzMwohHp8WJVYE1usi7tG0buvsg6iPgz27ituhoxljxar'
2017-07-17 11:39:44 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-17 11:39:44 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-17 11:39:44 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
2017-07-17 11:39:44 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
2017-07-17 11:39:44 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-17 11:39:44 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-17 11:39:44 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
2017-07-17 11:39:44 - DEBUG testThaliMobileNative: 'Server received (3244 bytes):'
2017-07-17 11:39:44 - DEBUG testThaliMobileNative: 'Server received all data: XbcDRqFwlR,cQVGcGvBSp08IDVQwKDiv0gUXEbhE2feop6WstHxd4KLcZKQKa7isa64WKa7iJbVo7sxLgsHqJOReqX8wWDgCAmw70N6eWUGOsLq98PDyQ8IvSSiOHSbtgmRNGHY0Q7CQktn2inYSWIiQYAkmuyQh3wvJ1e0oCRSZqRoVo4E39YA0OBfQ7TKY6BJX1Ul3AbXcSp2ZM4Du8M3ffyW3N9dc21zqI6eM7b03hiu5wsQEtGWlDiNZCmNZYoNUM6KsxVOfbiIb7AryyT3gcOVun0Qbvsrx5Ek57ECaqnYAwIFVRILG9RF7OXQtSP4BHwYEAhODHSR6NMWZqYdjFEtDRV4fvgY2cB8wPQ55yuHL7UheyWapsJYZbEwnnnWpPhfniTzrPqgmbjngAK1pRlZCzk0vQkx54sXO41elRDMWQXY2I3rOk7eXEcFb0ru2EDytBquML0OZuw52B5KqEL4D3QNUhiVRmcZQps0GvCenxd7kRFy4mjzcg9ejhMPZy0xTqA0,aSDzHW7f1R8bNs4dvufmD0rYDKRSBTLBM8b2peA7EfxuCdC2LEUc61WirMx80TQRcYhPgsSSesst8ozYhTFariAffHVH1EFYpbozideHPAmWNgu1UMpLVmWYUoIqrL38gGTlRpWKe0kSlUtoMRRB4LAb0HXQrhhr5881zT47j629Zc1YOyro8WJ1BxWpJWNs7xxZohLEcX46dItgRbJsuGLLmVL0RZI3uNXk17GqP1MdqeBWSOpUmxIeZA0Ma9cx,kh5Fw9dsP1yF6jYKZzzXOM72e0q6XKMOsgfU4ouFEhpR1J6l9zTSUHo5WnIXMDCoAXkwTa47aKzv71uFR8jfquEVj2Dd7tedu08641vFUVNaC4BXWiWiBURhK1rUOz0ZQPy7HIbOTGgNNwigeCXJ9FRWMM5oU1qHJjAKxDbBDMuo3bS3xsPYcujWmZKQt199WZit7vcxjw4sVYWTs6SoyQPH6LVYNktCjO53PYKM3cyMArwvvTB2NrlQI26r3COK,SDk4P5fIVah15Vg6H7rD3fUpe3hqChd1fDLRb0Xd1H5dkpPrsg16WazfcyCFTdbGoPhIlf7BE4jhApscXGaV44IH6teuEnnJlsrTsSG9RftFx3fdJP7BwMdVNhSVx4wGs7cwraefD2Vc5oHGnhBz5mZv9mbPZecmfoni31iVmzJ2m3813UOiFdIbd86olyZGsFCZQVQ1t4Ti7J9FwwYwKSLy8bCzepM6LlzsXWARz5lI8LmADCApDC9QyTivTRmD,LjlUUF4x8OCVkXPb4A6zj7OKMvZqYhBaA1xjPQhynfzbBefEeSl1IlnJLANFgGNdIwcapJMUSTExhSlLyLa35uSuvYilE2m5isQjcZ5OxDk4Vpzuw6CngOrsGkYH4ZZFG2yV3b0Z8plcL3UIFFXQcL8KFa2gG4Dai8flc2AkTuNDj0E707x7RmYvttLLG2ishPpKFQ5GtR8IVO7N45xgIbVhgF10jTgheLTozX3ZJGqMsOBeT4Sd9reGCYd9qNvd,QBCT4FLASh3YOiUI8UZmZ71mbCNPnxBzHAck1T2bqyh2Y2jQYAzaRgO7axW9ILnOn1mchrkI8JBDtoq5fraUr5PtO55FtToED4YU6ylmzMuZ2W5EUTW8PdrTYHLkExmDCLzjesZilza1J5Fma7ihCu7Fd0uVJwc5kzJ94BS0yM60jvwGOzKWZBgpZPkWjigM989KUS1N02akIOoH5yoF7p8sywcS8Q1qCYvtlCAdrvX93unGIXEYXBrGNtieZJH,U,lT5zwCZjPneHO7Fg0bRWFFXHg2sXejod9kwNK6bdUn1sEeTX2jUWwhdQrKwL2U1s8fdoceI5FK2VSLu74WL2m0Y4zBnnNLp6IWBdN2wVjgPbvuzR008WXs2NTfIMkgOPSI0XAxrBWaLADCYv35ngxsxK6ZCDFTloGoTjUADwR1gyQBNmQ96a6Mcr4fcidLQqszKf3M4BDkUtyKQcm4THHb0DPNapIjRuCSZu3J5XbKIEmKdRtJlcrZYXFhbI5K6b,ip1H3JjwgZ753FRAPONb27sXN45QYo1qzXivl6my3Qn6WEcQ22pgDM3KxKY7rfLX5r2FTkMnSc8fRxerVtB9F7YL1yRwciiRr1d3jannIQclCcoR7HbFTFNXIvqY2qQRHM3m2cJ853r2a6fZldwYsBOwptF873KaVR1ZhO3DGuRL8G97N5N5RNei2K1EqGSxKFpaVRJNhghdMl8TcORzxPOtkbVuSGryUbktCAsvqqAStgKJ8LZ14bvDyblEbzH8,qgpbpwxyykexRjKI5vVjfEEHfa0OfoIDd8pNNyiaSYfr1qrjUwWKvjKkPOrh4VfHLOLQkq9rp1IDH9dLHXr8A1wTTeeq70an1tCX1HPEI38kbKrMk9q1ioxyDqzMBUFtctri30AVzjsFQNXqkZeKoCrLiu6IW111kejQfxqofoOXR850FhpOW30ZV52bWN1i0mJrBv6nUkB0zZNML1e1AmaeHKElsSPmDk0UmvkN7E76a13v6qw0a2APB7uzBrEd,cJPTs9cZIcGhKhlx0rHbfnMtjN2QnUzwBuCyp9vR71K7YCk5jPrztM4T0xiK2XM4Q34tt6GikXauOkqMNkqFy2S5rxe9K0LiOQirJOX3WRv0El6JuaogS8lqhvHBOn9rVQv7WqOTguD3ZIGIgA5hC6hERkoqd61AhJpYpl2ogIbZkRTrkNi9BLqv8VNUCycNnOHJAANf9vccwCLUhzjcmGqXbBgpffige23YpSSt1NOiTPx9rgnYjw5WX4HhHst,S,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,T,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,C,Fg8Bz6XnMc6O4Wu1SfPNWFGm3OG4GZ9W1TSYvB9Dx93BGzQa3FJZg93oetNB8XQwkHyU1xvVUmdLU8J1Tda0s3DSVqxwNzpqqZv3kyRlMWvjvlTmzSuJYPvqCkCnWvbCebkHS7JHWSkNu534CGtOlt7ygEJJP4n09A5DnaCCoNjVubHX1zTbsoTbZFpbcUUMR9IsLfeImLoy3S7Q5Rxr1pAStiHyxmEgqLMMKkmd21XyM2sy3LtfWDubyXcLkC7H,rLLfLHNgAA2iKc8GQbxi2JRoTShfxxSwK44vEGi57Gz1l6vsb1GFIWihpPTLWHduS7AvIZ33dnqxA5pcjJDuqS9OqbMwipme2IkM4BAho7uV4ZWfpjnvHb9geSBUa1CRdQjQPguD1bZYKwqfv2ucSCYnirOY04vdNkR29WgWcnc7ooGrUKnvS3TC1XH60J3JkgT0KEkqgG8vOwl3E8wpLDIEzQ4fc6t5KlQiCeC3jJME87nbKSaEutcBHGKxOSN7,BvI4EoyPBCoBiV8lMueKQQMDs3SyBZRvzNzJYNonxCNhpJ7KJbPl8Tdo56M2StDdZfsgimUC41tHxRmXt28M33jc8e2FAcNmUk464jg0RyXYt5UYNyQaNFbPZqbhQH0xs5MpM7bbbxu3uBGRVbFXX86JSszOK2RP9GCjaBKdcfaaEJu8L1l42QuIWFFIayu9MxODBLEcmvTqYUqdrnH9iQCXHTztyOm9x4TQrFN3rFO3O53iY3GFi3Su6OfgPtFI,W9fa5E3zmMtj64K1ZA9RfqMS5dO1LvM2vXLgnBiQ1QB2m3ZD4IF7k3UGHBIdlWqPJa2GOpx3OhBobY7n4xsFNMdsWT89e3Vjn3Gcs3Fyh80faOTg1Ypx3P9mchW3tGvtLW9GVVYwc8JiDb35r0VKiKY7n3GhcV23DN2crqQiW3EwEqFEv0snHml9RS9HhcveEiGXG6hVveOg14UMbO2oufK8QwMcsBi25nAae6opcJWRYMGBsZcn1znS8qtRBYv,W,Pdqe6UvYsi6lBJ4p1YS58iBSGU0QcqKPdBLinVCAghVWK3yBXzNx6QHypg8d2d4UrAy2tz94xiJr0qNdEVS6crH8nemqtXfOBooN8Ad2rJU1hzanv5QcUng2qFDQpX1U8rEoc7TnkIda1CyztxuToayV3Iz6eJBfYQOmHINrZJJkl5S1T2M60rfDncAqBAXebw4BWQTdbYM6EMYURzrFoP9G51h1D4YnqRtpiTGkRaY09Km5yrTwTxvWKiAgQ7iz,teYLOgCCfB2wAwpg6B2MgsJ4Uq1XSrExRZmXDqFBLxS7Sh8Ts78uKlZuk3g9gyBY7xR0D715p0oo9HVVzOzvPqu2CYeMzboTFEY70leN0fHgKzsZNJlSu940pBB6Afb1tavazsjShl4LOMT4NvxEROb96qhN5llPuRbS1LmgTrAj9rLp26vW0p7CiX7NRIrO08lCpDPosmTluHRtFaIGdS35BcyYKWt6Ikm4sOc7Y2xHpq9HcvthG7JLZAHAKo0E,uWzSf3FQ477CWVmTZjE88JN3regdPwUyrVVrjXFOvx60IC7rnPVYfqXNzoNkPXsKrB4vEyvHiasCHuI56MT5J9BUbYmxkWMYsPpuI0kyxwKsO0zSBsI662MZOYNnRGvd7VYExmDlKlbGwcUz4LxMv62dvFzbhKmQ9dzC5GKOqQ1reA9edJ0wB8Ahw2nHMMaT6WVdsySwbenjVXRRL4xuC4ZcfE1HrFSqJeTgGAcTTOEtbLkM93GJS2TbynrMKfWH,oRaDl9eSx0AXsWp56peWN7af5P975qu1WyoTdW4b4SUTWLNmVLAfhzWytIo1CVjwVJeMZUSGR2lmwztAK1t3RKXGk9EH7pmoQ1JuJJdHfLip1HUtUmy85VCUThA05OhAFfBNmc4dNCJUIikhFZc8dys7evMG8b0SS0QfHtxe2cu8nnqhDQzfYQ4gk6SIAOE6K7z2C3szrrWOhH4ajkxcshmJWYygvoiSWxOg56doUcXd04hY9kDXTgzjRRuZyTW,X,amwAzs9yW5yRmPN0jhkxQhrULHP5OLp02ytEZeYCtUpFQ03mILG3FQeDNCmO8knFXXc4mYo9iKKHwYRCgGWOwKKaF6vvC7EVaU4YAfG315K7WmKSp6rocMGeLKpvS5V61fia3vY8AlS7mY6L1Z6CpVjFYUNjpjeGH4zEagOFaXmkzxqON2sworOB7OUjN6V8w4DSIZebx1nU3qyc7g5x0vn0OIsWzI7csiDolt06NWcbVYv6ZuWN3KV2I1vgoUgz,ipVM8GOU5S4Mbj4soTIGCNWLXQ2HIdvyDa1InbkOMYbZKVlJnDaXaq7uzyTSN9491QRPdGicVFJRAWZCtWm9tYKSLfXHqdwHLwuY7AXSuElZpW3C0L7D8wemDk3347FIQcXUXXJzyDhquGFK0wY0uBG8fNvh9KZMeMZu2HH577HK3gYzkhTSL7PuA0zX9RYdX1fuEE9k7U8uc8KxDYL2khlgeTRCm99fhTq6YEZt9ofefFKyKBx4Xn3IoVmU58xn,E2ToED3yTFbdeXAidmuNcpgo6hObaU1n5m3bscuDthjrfURE6fiPsl4pu6oQW0JT4FVbRQ9YyLTwSowTpXuNlB668G0dRt6Z43JrxGILg8D4rYNbolbaGHbj1U1E6Zji7rF8oNlDNxg4IBehGBueq1KI9EhIl3XtGNGqWdNppE7d5XXUcOVtXB8aWGRWbupjZmGGjMaNUygrnYLa0pRg9IfnRTksDBGjnrlgBDzicJawaQ3PeQ3ZjqwU1gHPB8sU,qidH0Ch7v52iMUYLK3YBOshFAYZGAeCuiKDGLW5uQXveR0IrIICq21nLOBwM2kPnkAGq2tlpv3lz65p8yCF6hi8Ur63O7YcUkzkvVmUCeAuX5OpYOsMxmCkxer7vIpoTmIPmU5B8GFudA6uwTyy1O3zSynKGqL2w985xIIvUk8pW2gSi2vIHxDF1F1dzAKBXeJZYieaNzbqt9Vk8mZZDIXPhewwzulDuv5qSn9CaJXW2F5ziY3WZBxfnV7m5fn7,k,5K6PxYioxHFOyjLoOn3GMopX1mNUbuMmWoHJYrH9HGWCLClkvtVPKzkrJVveJocyliprCCNc6Pud0nkluXA71cpCVbyKEKTXfT9AK9AoSbCs5T54K3Mza3ZijNfTMjMesGj6Yz5uDa1CAZozmGRIll0gxLHjMzk9fIGI4H8OhfFIBm5V6vWiBWY186jKWf8wArIMN63TWNOXej9ulTP7vxVciMgI5ihpmJhobmktizrmAbAhLGEiHsr5qyxHpZjk,wN9xc0ftEwQnkW18vqjZvje8SkXm5k2vIwCY5v7Qv7sG0MEVBMjxdrOcjxiN4iFEQrpUuNG1Pj4cP6ETwWvFWwLBAOQQlrk6tM2hHNa8h4GefveOzJ3f5IsSk08g5b6k4d0IQD6yf1GGcZMX8pIO1M1oo3ZI1AWwEJDZmYUBAzYGmr5jVDQxGRceiYhuNHM68u1DThxGCqkHjzh0XbSSD2Hp346LImfarAixBHro245yHpSdPmaHhsa4xwNYsQim,67u2jIdnVpskHZL2L3YKKOkVOguyR9v82B4cWxoJYggR1ICnE8loe4fjbV1aIXQeTK1OZKkmv7nkZYFICXfCtlFjA7JCW9owxjA1BWZHJFMQ0gXcdHrTDCC0L5NzPQWHIgFCGbKsjdaw8j8taMSlYCjA7BaJUYJxaCMUXokqHqZgSiPCvqyCnvIRCAiup1GX32EPgiTudJAyNdot22hMrPBnWpNPMzEiyX6Udqu1DjYsdNG1F31ltwhygibpn12U,qXFPjOW76TY77oNe7mW3YaohG4gm9AOVvc35IEuTXFVDUGfu9LWA06frsPi03iGw2F8FVFJYPpKFsaRhXt03x0EMZRI0KX2Jqh8SCBTPEqOM6CWOom3eZCPH6qnwm3WeKohG95EnB1kl1dOhsCho26A6Zw5XoODGviUfMPrjWg2z7wU1dVMEixIFvbqgURZiPWxMtUwsldBkSF68eb5CP7oxM4BkMNYTMv0B9pFZbnpo4MhIRxoesRJlEY3RFGW,Z,Nu2FRSy70vwek3CE82yqw3UvHY7XR4JtDdZUtqiVhlcAlcLbIMPBcFHNmD3PkYWP1XIySIxMjcfRuT8groiWlgwekummnq505dDb9STLAM9wAimsSfjr8Mt8pvbT4lJpMX66JYWY0i1TjxrcInseGnHRlqsfSsNkGsV8FMm2h9wwF9bcuRRh4X1Tt4ErRhKS8sQPWJBRV0gwBoetmnXgxQriIyti3JWoecbYV6jeCkc6x2bX4bGLHywhQEXjAGsX,VSl0J5yv8dUhEROFdIhRxxrt7GVJuXQ53SwRoaxGagvyQ5GvBE5bJZkHPxNiLASViko2QDYi67HVa9BcUhvKJlr0RsunYKE16RZwosg0ja2kwGadCBilNquKoXHfOO0ASmV4OzyAxPKgDyVjPL01WWXj56rjbVgPYQOXydJzWPThTFu0opW2pj7K57A1fsfElRzLGXSHORByTWRqdMlYbXbOAeXzofNoNw5YgPvdTJWWghzJekzVwwi8hbnmA9EH,PPfwqtjPfEvR2trDX3hfrhyEjHe7chFcoyOxbrQU4NZeUlmHJPh9f5OaH0HVsPsP10zmDhtN6yeCna26VV7Cvng9Gwi73crKnbzKxnxX71STPLQq8Hs3bAADJe47Nz0yEUrJIWRVAsQddctjJ27FDxcmNqx7hkH2s6pj3pWVsuF3kbLs7Oz7uYwEb8ygGrOLwcDMCo2isXd66MrH6KavIcdZWrGqAzxbPMnbDK2hJ0LnMguyyY1RTbTzSRbmGTS9,Vd9IZOuCkBn5jzNsnvaTikLeCyDe2NjLET6JK6l6z0mRu1z3EgOh9uPWFVr8HS0LlPAsXDqWmld4iI5jBAVLr3E3l8n034x0ZMZXWf3uRGPv8p6QmOVeFvYr5IieJwjWTENkKOfO56HIqnS3FREd0qsCvEOSobLgGULvDejJb8SyTBqrVvYrFlRHUuA33WLdWNHERLd4itAttXPq3kJHFIrNIGFMVnpNYNTZ7cnxKNxEWFaE9MrXO1H9Y0pWr0J,P,f31Ci7ilJqzJsyMmJUchUCPURYh6XnGoHG88YfEqq7Sflyqh5uiBcEYjD78kF4cHrtRw0t8jcy8yvEFxuwzWVKUJ952lc6ZHFChXHe8vMsaycQszQ0ZaRykEuSpBgpXPXP25tpcfXH9d1YIQwLa0PkVUtbprFWi06UZyaAfFDMF3gxmPgaj9mb44cmCSJOJmABMr6EJiLQV0uHFBMVNtFKMmopB76tpGxuZZW2a935VfVkwiTxD7KQ3V5JvCUbrn,hRQy7yMQi39SGVDuS68LV0a6vzMpa4wSXpJChBhzamBUbCbx7tvcywU5UfX6RO3I1yOoLALP0pwdJhkAxIIGL6YgqHLeijCdw0Hgb96x9AtLxuhxXXdr53jUcPDNE52zUfxMDEGVtbNDRMqkduu989HkrD4YIhT075ODZrSZj8rlzMRAgoUMhu4fz6liWnLI2VPrwczsFonm8DS61nwVPqsHkQ776Pxc5UIHPBUgXtjUbDOe4DIAnf8m3oZBfdhm,YlY3lIBaX0CUpwedNvUOpe8akYenjG81UvNq7h70bD88Nhm82kd2tNTkVj9zd67RTpupzdUFV6PuSqeofSnEsOOyNljJMpOCXZqGqOzJ0W23J6t8tpgpLEC9as1QTX7SEguM2GSqZLolirX2KWZSiPPNn6YhghmrkhuVetHXzfaQu2cSlOEkcnKLqO3yn9nIQyUqDQYLVzoY68WzPATxJSO0uQxGE4SvCyZon8BCHzNu0IuS2NxM9qRJYJOK6ONF,666NZg4pRnKrNVxnmgnxefEsf6i35dZDqIBDEjOZt0b9dCuiIeyPtZJKWHqIkF9tCSsTCJXit3kg3PaQQOIyPhnqdWxnPbQCHqfhzc9wHHeAYOicOSSGsotfrtgNiYydKqJi874IB1yEIq4G2aOse0g3aXa4PhnGdgEYceRg1yXIrQa84RjyGnrqPBENorraMrhdT3oVGlHGPa3bC9GtQ6XnCIqQtSkipggV23jMn64ObjLofWHmnPnU7y6GjKG,n,6qkXDB6xrfjTdogxBgFBZSrQYLgPAidb2BCUmrr52Gvj0zECxpAIpq5s4hGC3ltSD40KiFdbt8wpkDrUSERJeshPShPoCUzv4tev3Ovfi2Bo8qRphdZ1COZ6w9YlZC2gryRQbMsrBQkaQCtdu0NxJR72Gs6bH1bCpVAGtGeq01N5mESlCMOuck5i20ImQeNITrTmW8EznzZeQNKtXQc9xf1MybEcWLGx3cty077YSnjZlwmJaEYngJrHKhBKV2ed,FlHoGB3Ro9qXrHrdfWAsog7ediFw7OU3COEO1wYdfATaJfiNf4ta7g7OHWnq8mjVThSvknPZSStrwAPSCHVCMTjXy1YSTTZc0UXVbuqP2PuB8y22dlk4QfUxZQgJKbdRdckOBgTSzWsc3fTmuyXUmkN0AtDVyVmJFssrcQ6WhoGuXz4T0SH694gJLFmHdEKSy0Wgysz6IsFmq1D7DGi22x9OUxS32wANvwo9dg54OB1tHxBRgQ5CtowzdYTUfUVF,rNltDIz5Y3rzIqHQojJFQq7NDPQ3BPGcSsBOcG6rl8fEqFgiqWO6nQWtwLRMwGlw9fzR7eycZLQ18MA6ttiVLwyDgJBqRvGAYY0A2DtU5vhrmeoozrkt6NkiuyEIzgNJ35ErXJRc1vXEt3IX88bJFyE8aCblhDDk4a3kqPt25gYeNWzCI1WrBXVIfYJbT5fH1mYwlcRqlqb1qRX1d25VeZ1IMWw2CHIxqwgQR8NfBBcUkCAVsrra7hgOlBuWhlnZ,KM15jmUKMygdXXmgKIC28WeoCsk9NSjRC5re8fxVkCI6ue3HW8zgGcnDSWWCa7Vyp3sHy2pKCeAWeLL6eYukoEJ6RLpWrdiZtUPm1QavTlbrwCzK5x9bdF8RwxFuqwZUE1ftvkykh7qiiJWpcTM5jkrijWSnI3XylFWL9kTLS3hEu1hULZPpGuZx71B2czR0TRG45V4DzEWR560T7gxNtjq7hmaqsU7epaeT8gqbsNSpMMLZjcunnkZjD1pMCFH,8,y0YKjNFzbDY2ct28cHoADTGS9m2zo3j2jFww56BbOqnsXnxv8qSsYUrK15Kd8tT66na0SAKz6HN5LvIFwAXpbTOSnPN7bGQ0ddEPPa8hd9xNr2uY9L2tYcZc50ozsbLNpkvlqS69j75TpStZoa65HF2TODQQZI7ro1kixTviEgw3U2W2oGUJOupQrY09992c0q5mgX1agK4hGxqhFj0Dhhcr2tkdaoHHqK27fmnSXNmwO2hgC37Sb4wtEHh9VF0P,11N4xS471Pi95P90is1BOWLjDjdCZwxG4Kzux6oygPtYUdGwsYXBW6z6ZUdCtqaB6WQGtfFOGKJzUkJugqCB4SVlMdPmfuSVAytR7Q6Saj2GWxhvbq4IrxFkJdhQ0PuefXnCaqk5iFJXYzb75PZgKgRpCGSSYOnf8heDiVDY2ldYHo4pQrD3wHq9Jnyl0mNEXh9EK5USHUQ1dE3fXwrb82Tgj3gnDFDGoCe6jK1I23CUtcSjZJAcfrej5LHUumPI,sbzsOJrZizFkSjAS9zo9yPHiHheTHt5FIb8HViKJvQk5aoMylcDbTsHgMoHoGv1lbx9DY9dRb7OyqdCmViEZ9Fj3Ah5JCEMKxAxurBCyxR3hZp0Qgpq5U3jgWOxEFehdcRW1PXRWrzMZAQ6qhpYlu2eMS1BHQmBhKlMOvfsWS5nrk9Nbq9IEFZ2LzHFgjNxQ3iVjX6zusWKwvgnq3Uc6rhp9P6OnpyZpdQWnWTOoVGMjL42Fi25ybB9YPOR3Xxe7,yiNYqq0pZxzc1pNYwV68tq77AA6TzS5KtCIH6Xvnk0d0XbPkUaOwXDDbdERIJ3uCmHTLXYAx8VGNcw3sHtLSJ04PnCgW9NBquxfvNaxlHXCHczYrC3ZOapWRNGwHXxAkIlZKb4QWNdRMJ6HBUesUa4Bpnezr75Si2bfSORJHT4L6xlIQ0KS3ulap8yEH6opXegnzdaC9BHX1lzJwbN0JcvBzwFTcrzwBJPEpNCI1KiN1wmy1BPIoOsaapcR0wxP,I,d2HYjsKFwP0mqF5Mjbtu4yGi6wEUJ9DrT2ImODsgQcrMsFs6BiST7WZXPOn8PpQkFLaNog5vQXyrLkg28b9D0WhhFEclCCGRIk4zglCR5EUWIL4m0oeTUYpkGq5U2je0aLBg9IdORLGryt0fettAqvuXjTLPWkBEgf0euEyOyyWq5WdkMyJzTitdJzdoXUvFeriAfzt5j3Cs7i2Kjb4vKBcrtPGipunpfRb6JyzwevjZDIheUz3dKZW3CgSpKbRL,6hwgRjlvGGQrhUZAbx39pvoSjs368oiA2t1AdNHJ6cpGopa3PKogpE62fBlivpU0RiGajCWa6VTGEjFKlXzbrgeJgC0AE60UFNC9F0XzkV1sTDbKQB8gq6XuXflBcGAygVeTX7MXNf0mxkRkypPokdB6RG5sFKDMiUV3Vw4sHZ65XhwpIKcOecT683UlvJPO1YXXINbAxH00i7qNyuP9U5su9XwzPxtz71H8hqSRFt4nq7nLRLZ2uJ0G3zF5QByP,yJ5N4Jb36eBAg23yDuqoC0f9wfWKbtZiEHu9MReYQwdmrvxnQMLUTsOdZfwpa2rPjin1w9rS3BMNEPVb1C0cMLjP0oOR5znK39tpgl3E4S1O02tsyG442aCdO0iPv3RlB0cGpwgC5sAam3VN3ODxq7ykENS1yOUfKIfuNHhPL1xOBSwPjs1j27YTkrGeAD4959gEJxN2P7JxiClYyGzeDJ8cizDdMptLxc4ACsD6UspVod8Q8meDKYg4fBOJVNUD,fArxDgwmLz9So1bLVj9347yUTGBKSTfj8KMhdjovaxu8q61gW7WWOphqLktMesM47wS3zLImts1U25zKRcnybyIwdgqqnvgu7OSAhcfZ8zzg4LuqMaadhGjWRh58d8tFDQS8RbZDNEBn969wrdAXm5RCCrf6A3UaFM0lF7AFhjOpd8Iay80kD84voBe6Uw1cssQnXoMShx7haavsWwI8CpaDaA8hqmrxXe4hzQ9iuxP4JWgJAnPGHOvHmeGleCR,1,CQnm0xjFUPQnIY6aI2VQMw97bgMDJK3cewRjE4zunVoJpYDSJD3Sk9qJP5h3RLHn3A2rOLsxVa3Fy5UWqSnNfYWd37ttSSljbTtE4Wel0RBWDgaCbMbkESyBZsTnf2XELYv1Uh5L1QVJqy1IsCffZNX8AyF8F2SgN9j7gljKMRWzdHyzD4OjOBo3nj8zQmJ7OOShXoF9esZR8dIXkmrXZGc50xFhPE01mdXzvMUt7Z2fxJXmJY3oMtIC'
2017-07-17 11:39:44 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-17 11:39:44 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-17 11:39:44 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
2017-07-17 11:39:44 - DEBUG testThaliMobileNative: 'Server received (9855 bytes):'
,2017-07-17 11:39:44 - DEBUG testThaliMobileNative: 'Server received (2149 bytes):'
2017-07-17 11:39:44 - DEBUG testThaliMobileNative: 'Server received all data: H841BCWBy56JH76EcaFbB9AOTc1eTgMHT0n05is5BlP5EwehUYhhPyqCsR27prYc8ZkkGaJZAngFz6MHMIEY61Tp2B51kL,diGOOSMQBafAGCQP6XyaCDkVgxHlBJCcSnQPOiNa7VLqFmwy7gYcXRyBhr6MNMpUI6UWdtEK1mRsTgUFYw6i9yPLmgvz99XKUU4X5Lnyy6QvBks0zKCGKICg6UmPwivQLUUaLK17VeuYJXOCYMvT8E3lwzfMMY02QyI8I35cgA3V8GvGxOkuoqcfCwFtUB1PBAnX9rnh41PPpdZIkf7PxfbRLZhpIreJPIobrgivP5FqVd3EJK4IsZFzOyPF8YNE,uC6dyJyVXgTkVRVhbtzY4C0oAQXcGT9QpLmixABl9r4OzdXUEejuezOFt0nNuuuyc16tHr8vMvbzGYWFVKAjn8YSFYdcatwiG73YWImeUc9FT3Fxmxe7JMc6nHyA7QgoG4b3ByrofSLCQxmjlZxRzp2gUyBxCNYxkOeWrdZRGv65PJ3sqDdYnFyhbsurLiDRSMnb4fmrorWTCdRKqtwMNf8wrHHs83DFiKJQugILoG6hyrMVT7YSjuH2MwCHUz9m,FDz79477lgq0ZN3FLcvtwanieqFwhjI76BUJ26fNPGC6cHOIxsUYZNX2a5Pa6mrehgE19JoYKkNeomUQlYupotBykO6VKmx5yqtI8NBKicnl4rooYd74jry8ASwgqnIlfRdJK60tKfpJn82eqDn7tf7aeg1u9S8H0bhKxxBxtz7MZR9MyTGcSCrjv2hbN98o9caBxD5XlJRDVeFrCd4ri0cy1xMQzGZJ3q5CB3D5mJgRahzonuxHdPjsbDeeqWU,T,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,e,tbqxGlFowAJMJCbtKpxUVYHGzya8rUsm5oSmGou0zMtIpg3xX9scN3zcHt2jsG4TgnDdPmlnavcVyZeq1v9W3qrzfCBmQ6cKLr5B5Rtkqm1qhbRNNxuXcrLCe014WfBa9BIWNwsSRi0HRGKNBVir8zvIMXFTwKI6JTaiIuOwEdiImZ6wx2TlY4fXYP56FxYyN9eXZ5wIZ3RKoqWxE2B3jbGpGEZD8TumxDjmzeDyMDqoQFViDTI83RTlK8Z0CPLT,HKSoKJesffO8R94ZRBxb6QoibDwi3rb3wueCJ08ZUsJEU1xJF5ZVw11khPPm3j8LACvAfxs3VuxWo1r37hLLRWTkScDFLMoGVFuiPuzlXLw7qBJsmt79ZfEUMvBqQOqx9lKRUbEYhqMfHhSwPECJd8gVfHo0qiyApvztmZr0E4d1Xn53FYdEmjFqvxMyM62NdRKI1PWJBcIadMoAyhcnHab0ff0nuXe6MvPFEUQaYG64mcxnTkLfBlGsY09ebQ31,dPqPzGJa7ZV7JOAL08CwVULkLmQmmhUGmamSYIpuZ0M7tZDHKW8TQ4Cdeaa09Z6An5QtjZrgO7vpAF9JkMgPCzLz4BwgqgUuSsLFWru28B3MTMe35jEN3Vp6hcwiWke1zfjGIaVPSFEZbUBCBXjGrayR5MWgUDr9VOaYxnhXolpg3p4LZ6ENq4mzFNSsilqqqarPzzNvIvvXTnKglCqFs7hPwCrcq8XxccaN69WrZfnrqLanh6a6DTqzKV2BSTx5,Nn2xCrC2xUIcs00qoNgyywFx9hoguLCWJ80GpUH2YdSyLBPyjIWFhIHBQYc7MscCiFqvmMtIQkBi4Y1mlsGdQRjpa2LkNq1GymMzpSuLkPcwn6YTmpLYEbpG2MgX1hfCZnDr72iMWJTrT27nJ1b4KJBzq1Dvodba6bI9fwVF1abyndrPRX15n5yPIfal0Ny1ItRQ1EEt450HENSxIbDi308MvT3L4ImFmz5BMhKkbbffMY7mJwYrBx9KAPPbi8A,k,gr3cW2WAPiYwynmIAPnlKdN2Zbezbge2zHwDw24qjsGzMuhPXWthhOltW60mNy192mOCLAUFC1ngh2HUsxYEvdCb8Dv9x4kdsxnyZ5FPpf3adqlExvAq68zLVY3jex6cV8k0QTA0f8MwG5J0DaSlis0vUrN8hQ4L9tHporRPdMcyKkkVKEct9zc2Qrs21VL3nDq4FTwIAy8LjG9yeZHa8jAUNujt64tincYDV5nCss8nlQ0Ot2UlRdWe1sp3jw6z,yXalRddC8nXK0JkpvczFbrNxTEEF64tvGLMgvODDylA1BRTtpZujTWChvnvvBoRNtXu88euolV5oTY6hU7uyVQmtD7mqCPwvZzWnCQ7jyC7uEhbBp5yyPlruer2f8KniTS0xEEYKCFodJgIkAGzGgSUhv5VzbjPiiybKs60Xq0fKb2Zc3LvLrBb4gXWkfyYm062H3NFM7tETGsaGPA8MPCbpKOjERqF7uoVHMBwPL9vEaWTcDvCvoNYNY864veHk,K9oAaFgvJIkpM5Jiu9HgZtSIfJCKekDjs3fQPIIFz9w4IgGcpJdRZplSWarzPQwPpXh9AXDO0dReaZpNxsTv7ZwsoOjc2GTlhaY39Svkoho4n3ppAgsx1xSLhLd18aW1PFem2F7Y4zecZAJI1F8w33qsKqZCsLU7qe75l2LC90wE6EYwLaRaAzW1LGcpyj2yiZ5o698uc2lGsPi2EYkFCk9yDVPggBKNu66aY6tbOjzUV0T7GVUgNx1tCkrRWNTW,JiziqM8KqKuFuPtQB8Eq9P7iuEr4GckwDdeU8kW3SPUvlPQpHqdGpwvS5IwftMVDbQQ1fAq4VcEQE7WeSwkMsF9SzeBJp3T5vUlTP9lbkGY2RFHmxtBtLz7f980GhjxMDJBeLBWM4bF2RzoJWRFXsS4C1n5q6UlnpwEfSRXjv1oP9PtdPlyjg2NLGVU5Wp03Ur3KnS7nXwGm70enErGoKIve8FRmZjncqnAxsv9XHtkb3MNAID5KfFWa8FISV3a,C,A4UJqVjHTTAniABQ5jpeu6sMgQX4M36V5r66kN38gpwRp8igwZmoWoyivCdFXQMTQO2rbJaXyopuYxhu1Uy7yKGdslCHpjDbfanG8nZ0bRjD2vymdYGfpMmgPXDeAZ8RppfyDw5K1OdIukIGg14ABBYzP9kTMhuiuNzqg26vuPkZYUJnHgHk1aUQAK5sPq7u7SHx6gkZPHwiVNpQ4pxnaYBjJoKSrQ9GXhOvBwcwxdWr6Tm2xZQkwWm9wNf1WBrmnnmjts17sT1PfT0hvvJLliMAUJLupz1hWFwKINBZQ1OreO4yCGlAtcodO0wGn794lrYT8kghCRYe75gebEROvSwMzzBTEJhw5nnXIkxhiTZoXBaygeU2sw708ZqeBRiVLemMKnsWiSQWEpNfqdUuomkjQlArfz6PkkvO678mv4DMMGbhTwD1TIRmpRNx4Ci6z58AQnHTUdCC6vh3N6rEpp4VGOl1MISTdI8IF7MTnxznkK0IuJalUgdYNGUrkV33,jMl5oth1Hr9p5feZ1zenRJtimDFN0nwViQ7ytPhbGLG8Bt28PM8UnzqVfzWdsQugy52094svqsOx1lLPVMPh45HMXpcc3GNm4ZyHGqQH5kNyTV2B6mfiydZMHdxHTT0e6XIBHVujRd4Wc931hxtkZu5MG8cPk9M0OVhgiPpIpQfggXc8xVo57nPOtiI1jPc78zNaKBV3VF6YmNmBW7mrKNccYXPGzDWoSMsGVytgJ4mUdAUVYtKdVs1iCfXZwwaG,lwdJRKkkFvpyq0qwjiYShZ9RtwNflIxRHqBtdk0jvzLxWzuPODKpU7cy2ppfaVYdCTQakbQoI6ChLhVC8f6IRN7ibtadNE4A1iE6hR2xgeFhW5ZXlZDyfzwupxsdhBm1W0Izs1eCecYtyAmynpqOEmEl69axwcvlSHbuFeKuzqyhGptCJQixnHZ3DPbi2130UbilVjsfLdWbD3TC8YKIs3IputN6NRt5ENX3DiErSk5ZeUENTiS79d8h2KbKVsS,D,2c8SLCKBNLndxJRo4iFIS4KaB9Y0mnESpiKwjQbX1Q8PNJQQ7NlX4aTFlDM53oKHGRKuXbF8KrvXG5WNs9r3QcCUx2NCdKrzCa4ZDhIQDhE5ZWQVvqqF8QqwLrxtKgC78hYDohgNQ6B447vHVUiFjNRgT9Yo2Q6DFOMGADHvDI92pygabOv9XY9Ar2MQ9Js579WA1EkSLJdT4aEqQXOCIoo7d7vHQbbzrAHlKTUCBfwJdalXDo6ri2zsO2lnMxmL,yDoAmaJ5MhynL17t4uYLou4vuARI5U8ZpqoyehihPc3jYEW1g798huUfSIM8z7HFw4hPnvXPpLQZCknxL1sLs3ZznmkokOs9lbFsl66jgw2cGH9eK6YK2yAwgcEz6ab8A8qmpAhzEI9enhzGhV89yEShzshdH1GEkhWUyyux4JixMgWekRBBKzOARsVYvhlZd3JUQir8DjqBXtcn66yOiSDhOyzPuJumQ7KpB3HcHuYqX5j5Cv88QARViUd0JI0z,Qw58dh5UNdezbnOtmYeRMrmQtRP9sICxpMPaWcUp9nMEl3KOjSHkfFyx0iqiRQjNAhcQqCPVO7JXLrOk9rijydnPHPhdAo5E6Qzbg6hibxW5h7Sup0uOQmqnZSzfFEWOTvo5OBjeF8DfREk4yMuyNhTu2F7jg8LBWymjQpAWzag0NjSfTDTr5x5sGsC7yR8WddgCr4YMQvZSWkzmZyCmVWQxKOAygoXeNw2hPNzASKH2JDF5Olj7FHnPenfsRzIa,8oi0lof4av7V3kK7gmArUePagrKnHwuRD5e2R0NMMnLkmhz9vq3peD450hHhFSUAQCWqBOXQlwJ3GeM7lI87nKqS03dzqgMZ9At3mHqdCBMNn6WMgmfzX8rVvWtj77MMO0rjo9SKWsiakhqnb1w60zXsj11FNQypACtui098BYXj4OVwmZxfVDtRKHmUksoKwYE8BkJdj5XB1yEXhCutnMDcGnZLm2AGTFAzFsIiiGo0anQj6eWzT5RhTh6CzHo,A,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,F,G4zJuf4zj3RcXexatNGT6FQER4bJHRPx09gqzBnAYkJqmuVoyaQxPFEA7hOCbEauVitGWAyuIQVURTGWbbJhSBs0HJoqKf5xuc7QATUyo41INWUYio8I5ynvEoIZPzSMPIF4IeoQ464zYoeo49B0xPADu5azfbpJ0txpCPFLTJBEZhdzysJ4heYuQQg4bpHmGLLdSbJ8jNMshDhddf8tr4iFrk3NxSbFQZJ8hweGjl9eNZweh5qBnU7oICuRFlF7,Opf7pclLrSHatra9bVFomVV4jTs7xUbIjMhvM76x7YEgWnlIKU4xQlJiYf3VPzljRi5jy7OWXH6zeglFT7mZ2eic0MkyfWXWivi2ANavPcSnHgnkm6GCLfjQ2SnZuvgLjhCEVvuOUfqHv7igj0BmEm3k3PYREFcTPFPR2yzylaJvQraCivmg2LwiRsHoKmes8fCL8GRH0jN8tPa8Dolqs8yvs2hglm8DnNFj0OcmXyDyqR90kKDEsGyMOdsAJlGt,w37mM5vTAQU6Zw2NPBHpAuejlj6tqsoKthrWq7r1YTOoJjj78kqB5NIGu1mfO79pw0Q5mctzFtTyD0DRnZsXi69J2Pi8KilmnQaVZRfqK9MfcjYDD7AuOTKnwZpTtyGfgF3mIqGxqPd2ObvXxilNxMHBSNGT30DiTFiTVri1hXpDiaUDb5PgkCCshqreIJSE7fA5k6oV3KffBCD0DyowQSXG1brB0JpommCt6gwk0FC0U2YDMmMUTxuP9c1nl9tu,JzqIOtC2kXOHQZ7lxdGGRFsPc8EcLgOP6LmZ3YGJGtVqx1gPMmbzbsZC9e8ydW88ulyWaOmF72Ta1V1pBih57QUxxfraSODChLE0gGBwEnsL4yknKRzltoK4arXnBUxZW9gXLmro5dyRBP7TxJCUeXRD7cztRqfXnSrzPDds23IaNUjPRtzFQy39NkuKBoLVIbxWnBGNgXl5JU7cNpSPrlMpPW9NRUtggP5rj1ZaVM4DkcXcWag4rlQwGr5Hc8d,5,iEGmt1cpCOJrQ6h0XDkqvvWerO9hJ474gkdhJRA6JLaTuBO1QeE6LdWIQbU6JKZZNysgMuv1sYh4M1bMW57zLyx66wa0wc2qTsM0XY5CM6pPisJGhhqITJhrmlktR7D4Tv3d1JUUmra4vGyzPU1JShgjaFchhsYOBwCDCo0t3IsdF47iEQkeH3ucIfKzE5Ur0HYIbR8YhoRGc55OiNA0d83gR5gkL6THKmQChns1plLThc6Ef3wJOwbIMrHZNyh1,NNrLIozzJU9FpUksYocDrrfRnBq2awBBnUtQboyEN87oFjYJSyyQdhtzFZ2BMvZlPQktYgOhfLI1zqeoa3kyytkQSGiFET3uwfsyt7ICkm2o6YMfH1sJowuPGk8aTuvgraFtViW3i0aVAhbgojL1h4l58CDAdeOQzJWWb7wXCjf7MKmlJIT6qpL0rkhO9TZs95UmOPoRi1XXtJ6OPAnZVdFpfJvDhPmXgoa6dGnKYnd7W5mcOsoJoBDxrn9NSHda,r6HVKxg0288hXigxq6hYOYPuZsqho9d3NIefl7fl4rqkWcQgHSxjUakqUSTPaKnVljX0kh6IVwVnDEqcaEhPRWI7cYHpIPOZRJFxcmfKR3bselH9JAKQLZoY0Gpn8nmSqoERO4ZWRCDjcNXwrE2vodCULm30XecW0gM8POQgNXihT1QG11rGKDOC1SThkhOtlXJvFqaONGpmq5z8J2J5hJ3Xn6aNjh8Dx7GAfpT2BQHd2ujZ58ZsoNocDJw0xbuW,teC5meJJOlik4cOeRvZ05p9SMAPG5Td08AxhBTApKuBMSb4u3xDFx2MfcZuPj7bUftDGAJBlXgxiNfIzlBgKsVmJnUwEhwLsynj6BUG2YghbJlEP3BKlMIkTRHdznWGjHh0IfhWHFivssDdO4yDgo56LW7J3zJXBIralmHGtJg4e04Gh29lUutZK6uqog3hi29z6WIbFxUD4xtqVHalgv3hailwJBEnxjUJFQD9oT9PnvRL8uT2sR4PkZ0BxlV5,8,tNyEfzukXIAD005RhUvLZlnSxmRG3ylFcbql4j00F9wbiz5lkcQvBipbIcUvrXdrSa2xsBcOZCcG4Pj9P45lWIgUxs2nBQJoK4za3lpGYqRZNgtWQ5QdpKX9PcmSr8AwIsCbsAv4e4vWJF5808dDkX0GjS1CamQ0WXhnDGW5mgfFOnH46smvMjUE35skmaLzqHsPEOxY2hdQLOVLSQdJ8Koes2DeLmna6aa1xlUZlBytq8YICKKwP26TtffF2nLr,1ws3B8JOquLdKUTVHMd7aGj06os2fQAAlHMThPvi8L3cRaoRrZ1YJk6YQAmuIzkfOiCc3JjKGqG7AT8x4JColwVGY0VH5RSfPjJv4hM4u7mHSkqNxLwNgSewogthe1LVlnSv3hIUqWANhhGox1jMcmX4pAXqMwWKJLqURtP5CwWgWAXah80nggNAwENBmSOcM5BLHHROjitrvWQRv3lmMLSCAFnuQoW2Sgw41popTf9ZRIanjQNmrGQxD2MLqvK1,RLfrWk7RXSDm6MeBOfGeW6GP2uhiUUCtY8wlT0NU98bGY9Zn7DWrqXMZ52zoRCsmLI7HYOCgXY9CUUnmyNhL9o2ZqGGFarHmfVoUb9tDD1A3ijVGBEbXEacw4PVOBSntaDEJpGMUXp6Qs777h71eSVYVQNdJHWPKO8wifI1Q44JyAlUCIojkukC7MwuAPiEPsDjiIMCUTSTXtDHO1zPNKQmaz2VnhUUwQhoInsuNIFi6IH4ebjZuaQj4KnpEkDAz,aTCUnoEGVq1ehfkLW2L202ITq5dZkEz3Xcmvc499SmasChpnYPVEpRMqdZp1luxzAOT9F7mzo2Nj3A25ftUsOzeqMISXybTIw0Lxt6S3Em8K8AHKLlrwHi6q52HF9QO18AShvA92riSiPa4g6hqeXPwmXFKaTYuTYq12sT2A6ezDoisak14L5KYSMoywtzrstEFI2o9mMQJBnzg8mQOHSxeUU28OiBE4HcMzorJjhroSV1qpsXgHI2GyHR5Ee6Y,1,fVjFfXxngWeiGOFfaBVpurtP2656QATb2LNQurHKkYZiXYi1masvyRiRgLZBXOBy9H5IRtrGHcjdF9KFLKmmyNI80ApeETYyeV7eO6DrapqdVNxmt60G1Yni7eOOGJF2gR7CCZza0LXkhIhAOKT6FBCzyVNkK2fdt75qwo9xpnjsgLHZPs8KOvl8ZKPuX1oc3KjddXBzJbcWIsAuyDMAxYrIILoYUMwXFtwMZem3kxvl22HVsVTV3VlE9wD8cUko,6u0dBvam0iznEsGCzZjIQdPLGtSd5sMiv9JBJycEkB07HvgEXKWiCYurrNmuvvcFNsRPAPj8fajyOIcJBwqNmbmrPFCQTs2lRdVULvKH9VNGKNFllCputDD5N37Cloo3A2lSjHg7q04rkmCxepjnqeLWqDmS8Ou49xbjXv3d2hNVCt659dsC2uyJnyQOcUIaNSKp81U653DJwKm1BY5zOj6AKWZ09jxwqUplp4EVWdMeo4gt3pCC7XYt9IIJe6p1,ai8gzqE6XwoUCsNgHwPHlNUzHMwQwwUP6cmIUdsX8p1z5O6aC7m7vlie5Sq2ZRbsifuMiAfKw8JYRwmRv2wpa1NzLD0r0WA0w98Hy4oEjOVo7o8mSq4Npi1OozVChrYscojZShNFoJguHcJBH7r1EUaNeeJKCe2KqgmhY7IXbXzLX0UGyJHcSzo8p3JOlKuTZSFqNlFDvlCi743zzLeSV0bAqOd3GBmmN4trb4ToJkag2TjuLeSESwLTZY711HoP,dlZIgvAPkkfalNXY4L4cH2Cbm4NFRtUAOQoLtXd8j7JbyFqEFNv2wN74xTb5PbTHQBuS03ElS9IJrlkN7Bp8c9VbrFmJvIOW1iyuLWtKjplfeOIOF2uFUfmMnocDNU7py8RqeGlZTgReLuUmduAx8Kw5aPkeV5TLXkpnAIHaqVKM7hybWEFF8ARlb8EjGad8ugVIXv0y7dL1gORzso58BzPQIEf85apTGETzBmEhYmogsVghuR2xn0Skps4mdbG,q,d873tdkc4kojtqpDDfJucciUPSP4SuXz50lQFuipsEfK9EhXiRYPICdlw8OxQw7WyV3GUGn2aSnU5jLrDLHg9znEX2dC22NabB49vX8eQZcgtm8d5Pc0vCAi7QgWr3QD6Y0RQ8F3Sy1ITtOPR3J0J902L29BZuLgYoYlTON2o9FPbvIJeez8hwvrQhkgViuoEkt2SkUqr5p1wSe661gMjtN4popiijYIzFTfLQ8PB3HIrmcd8i0IDC5eBTKE3bAk,4tOZme63hA6xq85ixphjMcguBVVfoP3lF2Y0qDpqx6tT6pPOGhQ1uQ4BARyMMlRc67qJ49SypatPgB5LeupTW9k9Bk9VZRvSZXCmnH8FqxaxjhqOGQKLorggSseNYqzZKxbArxNNebu4bDQIvf9GEPPWrTCXB7L7cEqHLLYIpfEZbHulxeVFLFpedCFmM6L3PXF57o0C2F6eo37yNC94pgOFB5RbrTluQYIULaB8gPI0xxSJC2GK4v1U0PoqP3Oa,3chKAUZD1pwLHsksblHX0002kZoeTd2TsEBNXas4infTxqledgAS3i1YCAyZhXC2XAHKBZlpjbSqRNbLv31EfHQCaITsKNioJYfCIkiqn7vQF8k83kX2ftunnNb9tctF2NwQ9k85BZBKj5ocbGiAwsztDzBUVi58yrtmf8VuWr3RqWpHKMhqEeG5jLZEWnBVytJHieyBCuJwV6niIYmFVe5ihDN4PBbB8jHNcMq10rVZ7SBg33CaGl6HsbzCZgKD,xRDJ8xe8AYbcIkyaZZdRfZ6FY7gRYX8XeEvr1BRADDPL80KmZJcg8kpeD3FBdp0DZ2HXUOqXTg1YhpFhfpTePsIkyDum1cThJdeDB6Phutwx2xPI6Ucvbs94fyWGhWLJdyBPTUVuSZ9qha2Q87MGFDZZdlc5FmZloa2xPlxVCFodqL9iIFkdweBgaJuS56S5ZubyFFeY2P2U2iv04r1u3IVtzr6Wfbi7Ml2EDHtWrE2Ne5dsM0oO8qaNTTtdp6x,z,DE9zy7Y7rRmSJ40X2sSYLybVO84a1HpfiD3FN7et8r83QFfHG6Ms8PWilTGcVh1PFN9ef3iOjBKuX2GXYdagLXBonx3gUbEn9adm6lRfuW2ElfJl6hYU5xJESCi3p0ul1PGuaGUT1VlurydCeMYhkPbHyrrjZgxoWNilzq4C2Zcj7dEpsRk2f4SMVhA3VzqqLBnwU5SLiB8O1tAZsF9gBFOpeMDN8pviD2Q9vByZzOImOUAyE57grabE67ILcAhd,jpjLODKudLbVjF2oIu3z0rZ2jOEsKpMCSmGkHH9ywgkhVBPhcEE2QZ3Fq6PySMHsn6dJC2YuvctWYcmt5MdAeqZMTLVeTvt8E5Vdqadq9dy943N91v834x7KiZAnWVmHum1ESrXf1wcoMuvq7mdTRteHsBeBywwaLEy2RuJg44YPNSQrreNc468lUC6lkumZUPbKuKPL982I7Sqb4PKNSAaT4bBWN6jfB50SR9uFyUBzFn5CyHRsv0sHhf1GjqYQ,kaWL1bMN2Nix9jR0o9WGvHqdpDpXtHKgxfoDvvWnap4KL7l5XDrrhWbMKvkm0C8ohwYCFeErTsdlEZA3urByNJeP8fT3ZTv2Rl86Bb2eeFaUkaHWEfupR0MbEwQ2zaEdHvejaqFsbuXpXCDiZZPPRwH3wvEGqhK5IT2380u05l4oXgaBBtBnT4x28wn2uEGsQJTxsXZGNyAOD1KnHEwuDyP63KC6QRFaChGjjKue2w6eww6uDVJSGUx7pQIxEGSy,bG43qkeQ6aD027XMG9mTMLUVLbY0rACzwpynxsBIGU2zA6m14krc39zP78yT4tcoQFDTiyuWxdcdjhbJDtQnmKDZ4u73Lmy7A4mWBoM2myHYPcO4NYn5Lv72t8qwj9IozgTH1GJN5sSi3qKW0cP4pDle1U4FnyLfGEbXUofKeIarlpNgu3lYlrNUz4oH9jcy59zavVO2IG2FbGOrE2o4KbVc2SRsjEc60TAxVslmYLPkbiuFPN2gKEyhZYcw9ot,D,jAoIbj5frqFgEOm27MUQtPQv2eWDsiprzW5N8B8BWPCm998L370LpYVutdawuyZ3r2eodXgOUXEazMknaybeex2eQ0q6sriDWwkX9eqzsat1J9ov6URGFKkiFWCeOWGiDeefkb8bkB23Q6hSDnwLJcn27U9NJkgOi9fqq4dJGb0038gI05K4lypa93ofrZJkUT0schtcbYYkwPKsCUBkA2U6PlnxPyB8zP0u4kwqqRROyKpFx6K1d9BeMDRJm5Ll,l0xSFOPBMgjsNNtYwZK2QihZ7vKzeBinH4g8U9NlfM3kJVxkiDRCWulbifW7lNnWNycQZj3MyXjzH3tyDUd2g1PAOsUx56Y2EfNPdJwrCVYnhuteS3lU0LeiTd8HrJrkXkXj4kMxsTfzoVmDLqt6TzdlFMRcTs8aG934HPDuzPJGQmhCxVam148Okf7925EXzDSGMcmOPimz07C2YL2eStKj18WNtgK2inXHxnPTWeseKYlmTg30qy7Y0trZdWHS,oJoR0I0UR3cOosDwbMVwOJJsAdoeu8Ge7KzIqJBNOef48Ar44QpcjcaEuU9t80BUDyYou4JFx9AI7lYRCidbIczkAvogKsNZS5wyeYdAf88Uj7WDBFTw9Im5E3woCuE7FuwIBbHFTArMfEmJHAH6ccaHBWuCTlP2yUbnzifgrsDSl58re6nuBKPFyAQeJz4to2aZi6Pxy2D79iXHtN36TIZQit9x03kNr2h3Vtoo0Xp017KP3KK8DLJV479acXef,16nFIKqvlKYcyG28XkrqCl3LLRJZSqHXia6c5dFM9ZOmMziJWDdzm4yDmDwRYrJKZGyZoqe1oG2SgrRYbPMmYTsOY9sgdQBhiBrm7SoOXbGaMRMl6WSoqpOOsAgJEkEju9L06N9pil85DgbDOfzWvvNLUst7MKWBbC81LRssS4ssJiIrnO7eJsiVhqPJoju9wX2LoFoox7vI31ImTvqz0Hc4PopNfDkM0KA2Ltooc12zMpceLI0w6Hm48YurrqC,d,bwFrbL1JZg1jAdEJHm5Bvl6fNb0VEP2Z7Yx0S2LB1cmqdqqZkdGkmbG06K2HFKTedGGB2FCJoFFPftmW5qoeQ7PcMZoCUn5WKdQLTyE3Iz4Pjom4BV7AvUfG7fvVDmLR8x6YH8PCHvOcTtj5I5BaaTrL1erXPV9KNJp'
2017-07-17 11:39:44 - DEBUG testThaliMobileNative: 'Server sends data back to client (1638,4 bytes):'
2017-07-17 11:39:44 - DEBUG testThaliMobileNative: 'Server data flushed'
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:4
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:5
[ThaliCore] VirtualSoc,ket.closeStreams() vsID:4
[ThaliCore] VirtualSocket.closeStreams() vsID:5
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:4
[ThaliCore] VirtualSocket.deinit vsID:4 [1, 2,, 5, 6, 7, 8, 9]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnectin,g:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:5
[ThaliCore] VirtualSocket.deinit vsID:5 [1, 2, 6, 7, 8, 9]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,ok 112 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pe,er})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] VirtualSocket exited RunLoop vsID:7
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:7 [1, 2, 6, 8, 9]
,ok 113 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pe,er})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStream,s() vsID:8
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:8
[ThaliCore] VirtualSocket.deinit vsID:8 [1, 2, 6, 9]
,ok 114 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pe,er})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStream,s() vsID:9
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:9
[ThaliCore] VirtualSocket.deinit vsID:9 [1, 2, 6]
,# teardown
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:6
[ThaliCore] VirtualSocket.closeStreams() vsID:6
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:with,Error:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-17 11:39:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-17 11:39:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-17 11:39:45 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:39:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 115 Should be able to call stopListeni,ngForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:4B7E8D7E-A7F8-444B-9652-0AE90AED8376
2017-07-17 11:39:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"a,dvertisingActive":false}'
2017-07-17 11:39:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 116 Should be able to call stopAdvertisingAndListening in teardown
[ThaliCore] BrowserManager.disconnect peer:E0C,F7079-E931-4613-8F13-41A68FDA7BF3
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:51888
[ThaliCore] Session.disconnect() peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0
[T,haliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:6FE84F03-A547-4FBC-ABF4-B6EE9FBB59CE state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "4B7E8D7E-A7F8-444B-9652-0AE90AED8376", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:6FE84F03-A547-4FBC-ABF4-B6EE9FBB59CE
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] Session.deinit peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-17 11:39:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:39:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:39:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:39:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:39:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:39:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:39:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:39:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data securely
,[ThaliCore] Session.deinit peer:6FE84F03-A547-4FBC-ABF4-B6EE9FBB59CE
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "58491740-8F67-4D72-A396-FDAC62354394", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:58491740-8F67-4D72-A396-FDAC62354394
,2017-07-17 11:39:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-17 11:39:45 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-17 11:39:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 117 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:61D3DCD6-0405-4EDE-B701-B6A0D2E19893
[ThaliCore] Browser.startList,ening
,2017-07-17 11:39:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-17 11:39:45 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-17 11:39:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 118 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:523A7280-3273-4765-AF24-D29D03483576:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "523A7280-3273-4765-AF24-D29D03483576", generation: 0)
2017-07-17 11:39:46 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"523A7280-3273-4765-AF24-D29D03483576","generation":0}'
2017-07-17 11:39:46 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 523A7280-3273-4765-AF24-D29D03483576, (syncValue: cWDxZCdSKHZHqX8eDNh4EOgPzsVdnxfe)'
2017-07-17 11:39:46 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "523A7280-3273-4765-AF24-D29D034,83576", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "523A7280-3273-4765-AF24-D29D03483576", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:523A7280-3273-4765-AF24-D29D03483576:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E0CF7079-E931-4613-8F13-41A68FDA7BF3",, generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-17 11:39:46 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable,":true,"peerIdentifier":"E0CF7079-E931-4613-8F13-41A68FDA7BF3","generation":0}'
2017-07-17 11:39:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-17 11:39:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:523A7280-3273-4765-AF24-D29D03483576:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:52,3A7280-3273-4765-AF24-D29D03483576:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "523A7280-3273-4765-AF24-D29D03483576", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,23A7280-3273-4765-AF24-D29D03483576", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "523A7280-3273-4765-AF24-D29D03483576", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:523A7280-3273-4765-AF24-D29D03483576:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:523A7280-3273-4765-AF24-D29D03483576:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "E0CF7079-E931-4613-8F13-41A68FDA7BF3", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09", generation: 0)
2017-07-17 11:39:47 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAv,ailable":true,"peerIdentifier":"EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09","generation":0}'
2017-07-17 11:39:47 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-17 11:39:47 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:15599E72-C57A-4218-B314-C9C3FB7E4346:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "15599E72-C57A-4218-B314-C9C3FB7E4346", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:58491740-8F67-4D72-A396-FDAC62354394:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "58491740-8F67-4D72-A396-FDAC62354394", generation: 0)
2017-07-17 11:39:47 - DEBUG thaliMobileNativeTestUtils: 'W,e got a peer {"peerAvailable":true,"peerIdentifier":"15599E72-C57A-4218-B314-C9C3FB7E4346","generation":0}'
,2017-07-17 11:39:47 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-17 11:39:47 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-17 11:39:47 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:523A7280-3273-4765-AF24-D29D03483576:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:52,3A7280-3273-4765-AF24-D29D03483576:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "523A7280-3273-4765-AF24-D29D03483576", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,23A7280-3273-4765-AF24-D29D03483576", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "523A7280-3273-4765-AF24-D29D03483576", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:523A7280-3273-4765-AF24-D29D03483576:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:523A7280-3273-4765-AF24-D29D03483576:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:523A7280-3273-4765-AF24-D29D03483576:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:52,3A7280-3273-4765-AF24-D29D03483576:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "523A7280-3273-4765-AF24-D29D03483576", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,23A7280-3273-4765-AF24-D29D03483576", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "523A7280-3273-4765-AF24-D29D03483576", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:523A7280-3273-4765-AF24-D29D03483576:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:523A7280-3273-4765-AF24-D29D03483576:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:523A7280-3273-4765-AF24-D29D03483576:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:52,3A7280-3273-4765-AF24-D29D03483576:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "523A7280-3273-4765-AF24-D29D03483576", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:523A7280,-3273-4765-AF24-D29D03483576 error: max retries exceeded
2017-07-17 11:39:50 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"cWDxZCdSKHZHqX8eDNh4EOgPzsVdnxfe","error":"Connection could not be established","portNumber":null}'
2017-0,7-17 11:39:50 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'cWDxZCdSKHZHqX8eDNh4EOgPzsVdnxfe', error: 'Connection could not be established', listeningPort: '%s''
2017-07-17 11:39:50 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"523A7280-3273-4765-AF24-D29D03483576","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-17 11:39:50 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-17 11:39:50 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"523A7280-3273-4765-AF24-D29D03483576","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-17 11:39:50 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-17 11:39:50 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-17 11:39:50 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09 (syncValue: h8pMH3W,vmZITRKtqLmj6ZqglPAshesbX)'
2017-07-17 11:39:50 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:EC3577AD-9A13,-49A1-BBEA-3F4ED19C9C09:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-17 11:39:50 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-07-17 11:39:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:523A7280-3273-4765-AF24-D29D03483576:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:613BA8C1-C1B8-46B6-BDAB-373632FE1402
[ThaliCore] Advertiser: session connected Peer(uuid: "58491740-8F67-4D72-A396-FDAC62354394", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:613BA8C1-C1B8-46B6-BDAB-373632FE1402 state: notConnected -> connecting
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3C438B2A-C00A-4678-9E5E-055F2C6D4DEB
[ThaliCore] Advertiser: session connected Peer(uuid: "58491740-8F67-4D72-A396-FDAC62354394", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:3C438B2A-C00A-4678-9E5E-055F2C6D4DEB state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:523A7280-3273-4765-AF24-D29D03483576:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "523A7280-3273-4765-AF24-D29D03483576", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3C438B2A-C00A-4678-9E5E-055F2C6D4DEB
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3C438B2A-C00A-4678-9E5E-055F2C6D4DEB state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:51911
,2017-07-17 11:39:53 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"h8pMH3WvmZITRKtqLmj6ZqglPAshesbX","error":null,"portNumber":51911}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:613BA8C1-C1B8-46B6-BDAB-373632FE1402
,2017-07-17 11:39:53 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'h8pMH3WvmZITRKtqLmj6ZqglPAshesbX', error: 'null', listeningPort: '51911''
,Connecting to the localhost:51911
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:613BA8C1-C1B8-46B6-BDAB-373632FE1402 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3C438B2A-C00A-4678-9E5E-055F2C6D4DEB
[ThaliCore] Session.startOutputStream(with:) peer:3C438B2A-C00A-4678-9E5E-055F2C6D4DEB
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [1, 2, 6, 10]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [1, 2, 6, 10, 11]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:613BA8C1-C1B8-46B6-BDAB-373632FE1402
[ThaliCore] Session.startOutputStream(with:) peer:613BA8C1-C1B8-46B6-BDAB-373632FE1402
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [1, 2, 6, 10, 11, 12]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,Server received psk id: psk-id
,Connected to the localhost:51911
,2017-07-17 11:39:54 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-17 11:39:54 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-17 11:39:54 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-17 11:39:54 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-17 11:39:54 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-17 11:39:54 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-17 11:39:54 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:12
[ThaliCore] VirtualSocket.closeS,treams() vsID:12
,[ThaliCore] VirtualSocket exited RunLoop vsID:12
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:12 [1, 2, 6, 10, 11]
,2017-07-17 11:39:54 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:11
[ThaliCore] VirtualSocket.closeStreams() vsID:11
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:11
,[ThaliCore] VirtualSocket.deinit vsID:11 [1, 2, 6, 10]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-17 11:39:54 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-17 11:39:54 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-17 11:39:54 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-17 11:39:54 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,ok 119 got the same data back
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:10
[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:10
[ThaliCore] VirtualSocket.deinit vsID:10 [1, 2, 6]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) clie,nt disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,# teardown
,2017-07-17 11:39:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-17 11:39:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-17 11:39:54 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,[ThaliCore] Session.session(_:peer:didChange:) peer:3C438B2A-C00A-4678-9E5E-055F2C6D4DEB state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "58491740-8F67-4D72-A396-FDAC62354394", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:3C438B2A-C00A-4678-9E5E-055F2C6D4DEB
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:613BA8C1-C1B8-46B6-BDAB-373632FE1402 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "58491740-8F67-4D72-A396-FDAC62354394", generation: 0)
,2017-07-17 11:39:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:58491740-8F67-4D72-A396-FDAC62354394
,2017-07-17 11:39:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:39:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09
[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:51911
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09:0 state: connected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09", generation: 0)
,2017-07-17 11:39:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:39:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:39:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.deinit peer:3C438B2A-C00A-4678-9E5E-055F2C6D4DEB
,2017-07-17 11:39:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:39:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:39:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:39:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:39:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,2017-07-17 11:39:54 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"h8pMH3WvmZITRKtqLmj6ZqglPAshesbX","error":"Session disconnected","portNumber":null}'
,2017-07-17 11:39:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-17 11:39:54 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-17 11:39:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-17 11:39:54 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# setup
,[ThaliCore] Session.deinit peer:EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09:0
[ThaliCore] BrowserRelay.deinit
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8763C22E-349D-4875-B6BD-8F71D8CD3697", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:8763C22E-349D-4875-B6BD-8F71D8CD3697
,2017-07-17 11:39:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-17 11:39:54 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:39:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 122 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForA,dvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:97049D03-FF8B-4917-87CA-E5C43D1A8355
[ThaliCore] Browser.startListening
,2017-07-17 11:39:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-17 11:39:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:39:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 123 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09", generation: 0)
2017-07-17 11:39:55 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09","generation":0}'
2017-07-17 11:39:55 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09, (syncValue: Q7CC7I1BbCEtXdE9lYU0sZ4N57QpRDhi)'
2017-07-17 11:39:55 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "EC3577AD-9A13-49A1-BBEA-3F4ED19,C9C09", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:15599E72-C57A-4218-B314-C9C3FB7E4346:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "15599E72-C57A-4218-B314-C9C3FB7E4346",, generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-17 11:39:56 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable,":true,"peerIdentifier":"15599E72-C57A-4218-B314-C9C3FB7E4346","generation":0}'
2017-07-17 11:39:56 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-17 11:39:56 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:15599E72-C57A-4218-B314-C9C3FB7E4346:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "15599E72-C57A-4218-B314-C9C3FB7E4346", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8763C22E-349D-4875-B6BD-8F71D8CD3697:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8763C22E-349D-4875-B6BD-8F71D8CD3697", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:09BB567D-7B1E-4093-B10E-64E73CF5C4BE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "09BB567D-7B1E-4093-B10E-64E73CF5C4BE", generation: 0)
2017-07-17 11:39:56 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"09BB567D-7B1E-4093-B10E-64E73CF5C4BE","generation":0}'
2017-07-17 11:39:56 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-17 11:39:56 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5FA8589D-0E52-4FB5-86A3-8C265869ADC1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5FA8589D-0E52-4FB5-86A3-8C265869ADC1", g,eneration: 0)
2017-07-17 11:39:56 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5FA8589D-0E52-4FB5-86A3-8C265869ADC1","generation":0}'
2017-07-17 11:39:56 - DEBUG thaliMobileNativeTestUtils: 'Already running ,t,est!'
2017-07-17 11:39:56 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-17 11:39:56 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:EC,3577AD-9A13-49A1-BBEA-3F4ED19C9C09:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,C3577AD-9A13-49A1-BBEA-3F4ED19C9C09", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:EC,3577AD-9A13-49A1-BBEA-3F4ED19C9C09:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,C3577AD-9A13-49A1-BBEA-3F4ED19C9C09", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:EC,3577AD-9A13-49A1-BBEA-3F4ED19C9C09:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,C3577AD-9A13-49A1-BBEA-3F4ED19C9C09", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:EC,3577AD-9A13-49A1-BBEA-3F4ED19C9C09:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:EC3577AD,-9A13-49A1-BBEA-3F4ED19C9C09 error: max retries exceeded
2017-07-17 11:40:00 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Q7CC7I1BbCEtXdE9lYU0sZ4N57QpRDhi","error":"Connection could not be established","portNumber":null}'
2017-0,7-17 11:40:00 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Q7CC7I1BbCEtXdE9lYU0sZ4N57QpRDhi', error: 'Connection could not be established', listeningPort: '%s''
2017-07-17 11:40:00 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-17 11:40:00 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-17 11:40:00 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-17 11:40:00 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-17 11:40:00 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-17 11:40:00 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 09BB567D-7B1E-4093-B10E-64E73CF5C4BE (syncValue: JjlxziErhDqWWXXe9tGh0q7PcKkylahP)'
2017-07-17 11:40:00 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "09BB567D-7B1E-4093-B10E-64E73CF5C4BE", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "09BB567D-7B1E-4093-B10E-64E73CF5C4BE", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:09BB567D-7B1E,-4093-B10E-64E73CF5C4BE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-17 11:40:00 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-07-17 11:40:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8BABBB55-79ED-47D1-8E13-FC6391DA4CFC
[ThaliCore] Advertiser: session connected Peer(uuid: "8763C22E-349D-4875-B6BD-8F71D8CD3697", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:8BABBB55-79ED-47D1-8E13-FC6391DA4CFC state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:09BB567D-7B1E-4093-B10E-64E73CF5C4BE:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CAC20A51-C0E4-43E0-9E0C-6E8B9B3113FF
[ThaliCore] Advertiser: session connected Peer(uuid: "8763C22E-349D-4875-B6BD-8F71D8CD3697", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:CAC20A51-C0E4-43E0-9E0C-6E8B9B3113FF state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:09BB567D-7B1E-4093-B10E-64E73CF5C4BE:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:09BB567D-7B1E-4093-B10E-64E73CF5C4BE:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "09BB567D-7B1E-4093-B10E-64E73CF5C4BE", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:51932
2017-07-17 11:40:03 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"JjlxziErhDqWWXXe9tGh0q7PcKkylahP",,"error":null,"portNumber":51932}'
,2017-07-17 11:40:03 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'JjlxziErhDqWWXXe9tGh0q7PcKkylahP', error: 'null', listeningPort: '51932''
,Connecting to the localhost:51932
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:09BB567D-7B1E-4093-B10E-64E73CF5C4BE:0
,Connected to the localhost:51932
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:09BB567D-7B1E-4093-B10E-64E73CF5C4BE:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [1, 2, 6, 13]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8BABBB55-79ED-47D1-8E13-FC6391DA4CFC
,2017-07-17 11:40:03 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-17 11:40:03 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:peer:didChange:) peer:8BABBB55-79ED-47D1-8E13-FC6391DA4CFC state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8BABBB55-79ED-47D1-8E13-FC6391DA4CFC
[ThaliCore] Session.startOutputStream(with:) peer:8BABBB55-79ED-47D1-8E13-FC6391DA4CFC
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [1, 2, 6, 13, 14]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09", generation: 0)
,2017-07-17 11:40:03 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-17 11:40:03 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-17 11:40:03 - DEBUG testThaliMobileNative: 'Server received (3072 bytes):'
,2017-07-17 11:40:03 - DEBUG testThaliMobileNative: 'Server received (4096 bytes):'
,2017-07-17 11:40:03 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-17 11:40:03 - DEBUG testThaliMobileNative: 'Server received (2048 bytes):'
,2017-07-17 11:40:03 - DEBUG testThaliMobileNative: 'Server received (2829 bytes):'
,2017-07-17 11:40:03 - DEBUG testThaliMobileNative: 'Server received (7736 bytes):'
,2017-07-17 11:40:03 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-17 11:40:03 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-17 11:40:03 - DEBUG testThaliMobileNative: 'Server received (3356 bytes):'
,2017-07-17 11:40:03 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-17 11:40:03 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-17 11:40:03 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-17 11:40:03 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-17 11:40:03 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-17 11:40:03 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-17 11:40:03 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:13
,[ThaliCore] VirtualSocket exited RunLoop vsID:13
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:13 [1, 2, 6, 14]
,2017-07-17 11:40:03 - DEBUG testThaliMobileNative: 'Server received (20641 bytes):'
,2017-07-17 11:40:03 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-17 11:40:03 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-17 11:40:03 - DEBUG testThaliMobileNative: 'Server data flushed'
ok 124 got the same data back
# teardown
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:14
[ThaliCore] VirtualSocket.closeStreams() vsID:14
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:14
[ThaliCore] VirtualSocket.deinit vsID:14 [1, 2, 6]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CAC20A51-C0E4-43E0-9E0C-6E8B9B3113FF
,[ThaliCore] Session.session(_:peer:didChange:) peer:CAC20A51-C0E4-43E0-9E0C-6E8B9B3113FF state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CAC20A51-C0E4-43E0-9E0C-6E8B9B3113FF
[ThaliCore] Session.startOutputStream(with:) peer:CAC20A51-C0E4-43E0-9E0C-6E8B9B3113FF
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,5 [1, 2, 6, 15]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-17 11:40:05 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
2017-07-17 11:40:05 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
2017-07-17 11:40:05 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-17 11:40:05 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-17 11:40:05 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-17 11:40:05 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-17 11:40:05 - DEBUG testThaliMobileNative: 'Server received (3214 bytes):'
,2017-07-17 11:40:05 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-17 11:40:06 - DEBUG testThaliMobileNative: 'Server received (3356 bytes):'
,2017-07-17 11:40:06 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-17 11:40:06 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-17 11:40:06 - DEBUG testThaliMobileNative: 'Server received (5475 bytes):'
,2017-07-17 11:40:06 - DEBUG testThaliMobileNative: 'Server received (22528 bytes):'
,2017-07-17 11:40:06 - DEBUG testThaliMobileNative: 'Server received (2493 bytes):'
,2017-07-17 11:40:06 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-17 11:40:06 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-17 11:40:06 - DEBUG testThaliMobileNative: 'Server data flushed',
,2017-07-17 11:40:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-17 11:40:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socke,tDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-17 11:40:06 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-17 11:40:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 125 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:8763C22E-349D-4875-B6BD-8F71D8CD3697
2017-07-17 11:40:06 - DEBUG thaliMobileNativeWr,apper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:40:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:15
[ThaliCore] VirtualSocket.closeStreams() vsID:15
ok 126 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:09BB567D-7B1E-4093-B10E-64E73CF5C4BE
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:51932
[ThaliCore] Session.disconnect() p,eer:09BB567D-7B1E-4093-B10E-64E73CF5C4BE:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:15
,[ThaliCore] VirtualSocket.deinit vsID:15 [1, 2, 6]
,[ThaliCore] Session.session(_:peer:didChange:) peer:8BABBB55-79ED-47D1-8E13-FC6391DA4CFC state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "8763C22E-349D-4875-B6BD-8F71D8CD3697", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:CAC20A51-C0E4-43E0-9E0C-6E8B9B3113FF
,[ThaliCore] Session.deinit peer:09BB567D-7B1E-4093-B10E-64E73CF5C4BE:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-17 11:40:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:40:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:40:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-17 11:40:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,[ThaliCore] Session.deinit peer:CAC20A51-C0E4-43E0-9E0C-6E8B9B3113FF
[ThaliCore] AdvertiserRelay.deinit
,2017-07-17 11:40:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2D8C6C0F-A26C-43F5-B82B-A160D7AA36DC", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:2D8C6C0F-A26C-43F5-B82B-A160D7AA36DC
2017-07-17 1,1:40:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-17 11:40:09 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:40:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 127 Ready to advertise
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:EA152D53-D868-4A2C-8DCB-867C9FCA3408
[ThaliCore] Browser.startListening
2017-07,-,17 11:40:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-17 11:40:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not ma,tch with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:40:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate ,(was in stopped state).'
ok 128 Ready to listen
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D0E56831-394E-47D9-BA4F-82F9ECB0DA87:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D0E56831-394E-47D9-BA4F-82F9ECB0DA87", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:C22ED207-1690-4275-814E-7C3ED1327DC2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C22ED207-1690-4275-814E-7C3ED1327DC2", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:,) found peer:5FA8589D-0E52-4FB5-86A3-8C265869ADC1:0
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:2D8C6C0F-A26C-43F5-B82B-A160D7AA36DC
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5FA8589,D-0E52-4FB5-86A3-8C265869ADC1", generation: 0)
2017-07-17 11:40:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-17 11:40:10 - INFO thaliMobile: 'Received state ({"di,scoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-17 11:40:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 129 stop ads worked
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-17 11:40:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:40:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 130 test stop worked
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-17 11:40:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:40:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 131 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-17 11:40:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:40:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 132 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-17 11:40:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:40:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:40:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-17 11:40:13 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-17 11:40:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-17 11:40:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-17 11:40:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Test updating advertising and parallel data transfer
,2017-07-17 11:40:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:40:14 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 133 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:40:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 134 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:40:14 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-17 11:40:14 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B62A2F7A-8E90-4B77-AA81-1AE2D8507400
[ThaliCore] Browser.startListening
ok 135 discoveryActive should be false
ok 136 advertisingA,ctive should be true
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "07F7C7C3-79CA-4128-B74C-5DF7C5177434", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:07F7C7C3-79CA-4128-B74C-5DF7,C5177434
ok 137 discoveryActive should be false
ok 138 advertisingActive should be true
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
ok 139 discoveryActive should be false
ok 140 advertisingActive sh,ould be true
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:07F7C7C3-79CA-4128-B74C-5DF7C5177434
ok 141 discoveryActive should be false
ok 142 advertisingActive should be true
ok 143 Can call startListe,ningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,ok 144 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,ok 145 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:14 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-07-17 11:40:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-17 11:40:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:40:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 146 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-17 11:40:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-17 11:40:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 147 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-17 11:40:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-17 11:40:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:40:16 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 148 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-17 11:40:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:40:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 149 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-17 11:40:16 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-17 11:40:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:40:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 150 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-17 11:40:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:40:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 151 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-17 11:40:17 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-17 11:40:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:40:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 152 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-17 11:40:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:40:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 153 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-17 11:40:17 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-17 11:40:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:40:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 154 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-17 11:40:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:40:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 155 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-17 11:40:17 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-17 11:40:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:40:17 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 156 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-17 11:40:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:40:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 157 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 158 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:3643ed28-c3b4-41d4-a300-3e1034801598 error: startListeningNotActive
2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved:, {"syncValue":"j67TfN0ezhnqMUDL4opfDRtBM6wIixls","error":"startListeningForAdvertisements is not active","portNumber":null}'
ok 159 Should only get called after multiConnect returned
ok 160 SyncValue matches
ok 161 Got right error
ok 162 listeningPort ,is null
2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3643ed28-c3b4-41d4-a300-3e1034801598","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-17 11:40:18 - DEBUG t,haliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3643ed28-c3b4-41d4-a300-3,e,1034801598","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:40:18 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 163 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:40:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 164 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:40:18 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-17 11:40:18 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:849A6C2C-8346-47AB-BCF9-D63F734A7E26
[ThaliCore] Browser.startListening
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-17 11:40:18 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:40:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 165 No error on starting
ok 166 Got null as expected
2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"RMrfnLnGpiRmmjGBAjz0k06ij3Qtx7jA","error":"Illegal peerID","portNumber",:null}'
ok 167 Should only get called after multiConnect returned
ok 168 SyncValue matches
ok 169 Got right error
ok 170 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17, 11:40:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 171 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-17 11:40:18 - DEBUG tha,liMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:40:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 172 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# multiConnect properly fails on legal but non-existent peerID
,2017-07-17 11:40:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:40:18 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 173 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:40:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 174 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-17 11:40:18 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:525BFC54-AC79-42CE-BD63-0159F9DD30CB
[ThaliCore] Browser.startListening
2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-17 11:40:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:40:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 175 No error on star,ting
ok 176 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17, 11:40:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 177 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-17 11:40:19 - DEBUG tha,liMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:40:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 178 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call disconnect with invalid peer id
,ok 179 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:40:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 180 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:40:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 181 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:21f5fbcb-d257-433f-987f-965362ed38c4
ok 182 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:40:19 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 183 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:40:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 184 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:40:19 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:20 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3C2C6DFD-3481-46B7-BF2E-3B8B8326D366", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:3C2C6DFD-3481-46B7-BF2E-3B8B8326D366
2017-07-17 11:40:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-17 11:40:20, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-17 11:40:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 185 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Tha,liCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C09065A6-0F62-42D6-9222-BDBE3A9BDF26
[ThaliCore] Browser.startListening
2017-07-17 11:40:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adv,ertisingActive":true}'
2017-07-17 11:40:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"ro,uter":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:40:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 186 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5FA8589D-0E52-4FB5-86A3-8C265869ADC1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5FA8589D-0E52-4FB5-86A3-8C265869ADC1", generation: 0)
,2017-07-17 11:40:20 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5FA8589D-0E52-4FB5-86A3-8C265869ADC1","generation":0}'
,2017-07-17 11:40:20 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5FA8589D-0E52-4FB5-86A3-8C265869ADC1 (syncValue: Xihp3j3ZC8Dzv2D4QjMClxJfQt1YlOHa)'
,2017-07-17 11:40:20 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5FA8589D-0E52-4FB5-86A3-8C265869ADC1", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5FA8589D-0E52-4FB5-86A3-8C265869ADC1", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5FA8589D-0E52-4FB5-86A3-8C265869ADC1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:5FA8589D-0E52-4FB5-86A3-8C265869ADC1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5F,A8589D-0E52-4FB5-86A3-8C265869ADC1:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "5FA8589D-0E52-4FB5-86A3-8C265869ADC1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,FA8589D-0E52-4FB5-86A3-8C265869ADC1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5FA8589D-0E52-4FB5-86A3-8C265869ADC1", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5FA8589D-0E52-4FB5-86A3-8C265869ADC1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5FA8589D-0E52-4FB5-86A3-8C265869ADC1:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3227DF1D-62DA-41B7-BCBA-445AE86618B2", generation: 0)
,2017-07-17 11:40:21 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3227DF1D-62DA-41B7-BCBA-445AE86618B2","generation":0}'
,2017-07-17 11:40:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-17 11:40:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6396697D-E678-496B-A513-1569FA649E5E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6396697D-E678-496B-A513-1569FA649E5E", generation: 0)
,2017-07-17 11:40:21 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6396697D-E678-496B-A513-1569FA649E5E","generation":0}'
,2017-07-17 11:40:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-17 11:40:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-17 11:40:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:02E46E65-5DF2-473F-A3F7-4C3E32C1CD9C
[ThaliCore] Advertiser: session connected Peer(uuid: "3C2C6DFD-3481-46B7-BF2E-3B8B8326D366", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:02E46E65-5DF2-473F-A3F7-4C3E32C1CD9C state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3C2C6DFD-3481-46B7-BF2E-3B8B8326D366:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3C2C6DFD-3481-46B7-BF2E-3B8B8326D366", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:5FA8589D-0E52-4FB5-86A3-8C265869ADC1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5F,A8589D-0E52-4FB5-86A3-8C265869ADC1:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "5FA8589D-0E52-4FB5-86A3-8C265869ADC1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,FA8589D-0E52-4FB5-86A3-8C265869ADC1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5FA8589D-0E52-4FB5-86A3-8C265869ADC1", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5FA8589D-0E52-4FB5-86A3-8C265869ADC1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5FA8589D-0E52-4FB5-86A3-8C265869ADC1:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5FA8589D-0E52-4FB5-86A3-8C265869ADC1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5F,A8589D-0E52-4FB5-86A3-8C265869ADC1:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "5FA8589D-0E52-4FB5-86A3-8C265869ADC1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,FA8589D-0E52-4FB5-86A3-8C265869ADC1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5FA8589D-0E52-4FB5-86A3-8C265869ADC1", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5FA8589D-0E52-4FB5-86A3-8C265869ADC1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5FA8589D-0E52-4FB5-86A3-8C265869ADC1:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:02E46E65-5DF2-473F-A3F7-4C3E32C1CD9C
,[ThaliCore] Session.session(_:peer:didChange:) peer:02E46E65-5DF2-473F-A3F7-4C3E32C1CD9C state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:02E46E65-5DF2-473F-A3F7-4C3E32C1CD9C
[ThaliCore] Session.startOutputStream(with:) peer:02E46E65-5DF2-473F-A3F7-4C3E32C1CD9C
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [1, 2, 6, 16]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:5FA8589D-0E52-4FB5-86A3-8C265869ADC1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5F,A8589D-0E52-4FB5-86A3-8C265869ADC1:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "5FA8589D-0E52-4FB5-86A3-8C265869ADC1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:5FA8589D,-0E52-4FB5-86A3-8C265869ADC1 error: max retries exceeded
2017-07-17 11:40:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Xihp3j3ZC8Dzv2D4QjMClxJfQt1YlOHa","error":"Connection could not be established","portNumber":null}'
2017-0,7-17 11:40:24 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Xihp3j3ZC8Dzv2D4QjMClxJfQt1YlOHa', error: 'Connection could not be established', listeningPort: '%s''
2017-07-17 11:40:24 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"5FA8589D-0E52-4FB5-86A3-8C265869ADC1","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-17 11:40:24 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-17 11:40:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"5FA8589D-0E52-4FB5-86A3-8C265869ADC1","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-17 11:40:24 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-17 11:40:24 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-17 11:40:24 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3227DF1D-62DA-41B7-BCBA-445AE86618B2 (syncValue: j2aM6gL,LvY4bXmEUO7g7WUqNnZadSwkC)'
2017-07-17 11:40:24 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3227DF1D-62DA-41B7-BCBA-445AE86618B2", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3227DF1D-62DA-41B7-BCBA-445AE86618B2", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3227DF1D-62DA,-41B7-BCBA-445AE86618B2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-17 11:40:24 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-07-17 11:40:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:5FA8589D-0E52-4FB5-86A3-8C265869ADC1:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "3227DF1D-62DA-41B7-BCBA-445AE86618B2", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:51951
2017-07-17 11:40:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"j2aM6gLLvY4bXmEUO7g7WUqNnZadSwkC",,"error":null,"portNumber":51951}'
2017-07-17 11:40:27 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'j2aM6gLLvY4bXmEUO7g7WUqNnZadSwkC', error: 'null', listeningPort: '51951''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2:0
ok 187 Got null as expected
[ThaliCore] BrowserManager.co,nnectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3227DF1D-62DA-41B7-BCBA-445AE86618B2", generation: 0) found active relay
2017-07-17 11:40:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Al38wcPiO1QZTkuTpvnNtPEwtvBhgJP,E","error":null,"portNumber":51951}'
ok 188 No error
ok 189 Ports equal
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [1, 2, 6, 16, 17]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 190 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3227DF1D-62DA-41B7-BCBA-445AE86618B2", generation: 0) found active relay
,2017-07-17 11:40:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"CB8NmpsoUy7Oiw4BG9KPbRYuGx1IHeVH","error":null,"portNumber":51951}'
,ok 191 No error
,ok 192 Ports equal
,# teardown
,2017-07-17 11:40:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-17 11:40:29 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:40:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 193 Should be able to call stopListeni,ngForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:3C2C6DFD-3481-46B7-BF2E-3B8B8326D366
2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateN,o,nTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:40:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 194 Should be able to call stopAdvertisingAndListening in teardown
[ThaliCore] T,CPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketD,idDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:16
[ThaliCore] VirtualSocket.closeStreams() vsID,:16
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:16
[ThaliCore] VirtualSocket.deinit vsID:16 [1, 2, 6, 17]
[ThaliCore] BrowserManager.disconnect peer:3227DF1D-62DA-41,B,7-BCBA-445AE86618B2
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:51951
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] VirtualSocket.closeStreams() vsID:17
,[ThaliCore] VirtualSocket exited RunLoop vsID:17
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] VirtualSocket.deinit vsID:17 [1, 2, 6]
,[ThaliCore] Session.disconnect() peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "3227DF1D-62DA-41B7-BCBA-445AE86618B2", generation: 0)
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:02E46E65-5DF2-473F-A3F7-4C3E32C1CD9C state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "3C2C6DFD-3481-46B7-BF2E-3B8B8326D366", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:02E46E65-5DF2-473F-A3F7-4C3E32C1CD9C
[ThaliCore] Advert,iserRelay.deinit
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"j2aM6gLLvY4bXmEUO7g7WUqNnZadSwkC","error":"Session disconnected","portNumber":null}'
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3227DF1D-62DA-41B7-BCBA-445AE86618B2","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3227DF1D-62DA-41B7-BCBA-445AE86618B2","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# setup
,[ThaliCore] Session.deinit peer:02E46E65-5DF2-473F-A3F7-4C3E32C1CD9C
[ThaliCore] Session.deinit peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2:0
[ThaliCore] BrowserRelay.deinit
,# initial peer discovery
,2017-07-17 11:40:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-17 11:40:29 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-07-17 11:40:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-07-17 11:40:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:40:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:40:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-07-17 11:40:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-07-17 11:40:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:40:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:40:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-07-17 11:40:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:40:31 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-17 11:40:31 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-07-17 11:40:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-07-17 11:40:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-17 11:40:32 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-17 11:40:32 - DEBUG createNativeListener: 'listening 51954'
ok 195 Should throw
,# teardown
,2017-07-17 11:40:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-17 11:40:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-17 11:40:32 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-17 11:40:32 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-17 11:40:32 - DEBUG createNativeListener: 'listening 51956'
,2017-07-17 11:40:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-17 11:40:32 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 196 initial connection state should be CONNECTED
,2017-07-17 11:40:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 197 final connection state should be DISCONNECTED
,# teardown
,2017-07-17 11:40:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-17 11:40:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-17 11:40:32 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-07-17 11:40:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:40:32 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-17 11:40:32 - DEBUG createNativeListener: 'listening 51959'
,2017-07-17 11:40:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-17 11:40:32 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-17 11:40:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-17 11:40:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 198 tried to connect to right port
,ok 199 failed due to refused connection
,ok 200 routerPortConnectionFailed is emitted
,# teardown
,2017-07-17 11:40:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-17 11:40:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-17 11:40:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-17 11:40:33 - DEBUG createNativeListener: 'Native Server - close'
2017-07-17 11:40:33 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <,-> Mux - 0 - close'
,2017-07-17 11:40:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-07-17 11:40:33 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-17 11:40:33 - DEBUG createNativeListener: 'listening 51963'
,2017-07-17 11:40:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-17 11:40:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-17 11:40:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-17 11:40:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 201 Send/recvd #1 should be equal length
,ok 202 Send/recvd #1 should be same
,ok 203 Send/recvd #2 should be equal length
,ok 204 Send/recvd #2 should be same
,ok 205 Should be exactly 2 client sockets
,# teardown
,2017-07-17 11:40:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-17 11:40:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-17 11:40:33 - DEBUG createNativeListener: 'Native Server - close'
2017-07-17 11:40:33, - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-17 11:40:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
2017-07-17 11:40:33 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close',
2017-07-17 11:40:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
2017-07-17 11:40:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
2017-07-17 11:40:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection, to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'listening 51968'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 206 socket shouldn't close until after stream
,ok 207 incoming remains open
,# teardown
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-17 11:40:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:40:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'listening 51972'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 208 we should not have gotten an error
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 209 socket shouldn't close until after incoming
,ok 210 incoming is cleaned up
,# teardown
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-17 11:40:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:40:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'listening 51976'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-17 11:40:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2017-07-17 11:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-07-17 11:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 211 stream was closed
ok 212 incoming should survive
ok 213 mux should have no streams
,# teardown
,2017-07-17 11:40:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-17 11:40:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-17 11:40:34 - DEBUG createNativeListener: 'Native Server - close'
2017-07-17 11:40:34, - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'listening 51980'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-17 11:40:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 214 we should not have gotten an error
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 215 Buffers are identical
,2017-07-17 11:40:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'Native Server - close'
2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 216 native server is nulled out
,ok 217 native server should be closed
,ok 218 incoming has been removed
,ok 219 Incoming should be done
,ok 220 The mux object should be closed
,ok 221 The mux stream should be closed
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-17 11:40:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-17 11:40:35 - DEBUG createNativeListener: 'listening 51984'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-17 11:40:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-07-17 11:40:35 - DEBUG createNativeListener: 'incom,ing - incoming Android TCP/IP client connection <-> Mux - 1'
2017-07-17 11:40:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
2017-07-17 11:40:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
,2017-07-17 11:40:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 222 native server is nulled out
,ok 223 native server should be closed
,ok 224 incoming has been removed
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-17 11:40:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-17 11:40:36 - DEBUG createNativeListener: 'listening 52036'
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-17 11:40:36 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 225 we should not have gotten an error
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 226 Buffers are identical
2017-07-17 11:40:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-07-17 11:40:36 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client co,nnection <-> Mux - 0 - close'
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 227 server should be fine
ok 228 server should be open
ok 229 incoming has been removed
ok 230 The mux object should be clos,ed
ok 231 The mux stream should be closed
2017-07-17 11:40:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-17 11:40:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-17 11:40:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-17 11:40:36 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'listening 52040'
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-17 11:40:36 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 232 we should not have gotten an error
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 233 Buffers are identical
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
2017-07-17 11:40:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to ,node - 0 - 0 - closed'
2017-07-17 11:40:36 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-07-17 11:40:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux, - 0 - close'
ok 234 server should be fine
ok 235 server should be open
ok 236 incoming has been removed
ok 237 The mux object should be closed
ok 238 The mux stream should be closed
,# teardown
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-17 11:40:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:40:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# can create servers manager
,ok 239 serversManager must not be null
ok 240 serversManager must be an object
,# teardown
,# setup
,# calling stop without start causes error
,ok 241 We need to call start first
,# teardown
,# setup
,# can start/stop servers manager
,2017-07-17 11:40:37 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-17 11:40:37 - DEBUG createNativeListener: 'listening 52043'
ok 242 port must be in range
,# teardown
,2017-07-17 11:40:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-17 11:40:37 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-17 11:40:37 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-17 11:40:37 - DEBUG createNativeListener: 'listening 52044'
ok 243 second start should return same port
,# teardown
,2017-07-17 11:40:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-17 11:40:37 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-17 11:40:37 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-17 11:40:37 - DEBUG createNativeListener: 'listening 52046'
,2017-07-17 11:40:37 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-17 11:40:37 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 244 we should be connected
2017-07-17 11:40:37 - DEB,UG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 245 now we are disconnected
,2017-07-17 11:40:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-17 11:40:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-17 11:40:37 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-07-17 11:40:38 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
ok 246 Passed bogus id
2017-07-17 11:40:38 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port, 901'
ok 247 Passed good id but bogus port
2017-07-17 11:40:38 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
ok 248 Passed right context
,ok 249 Right server
ok 250 No error should be set
ok 251 Retry should be false
ok 252 We called close server
,# teardown
,# setup
,2017-07-17 11:40:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:40:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:40:38 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-17 11:40:38 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-17 11:40:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-17 11:40:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-17 11:40:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Single local http request
,listening on 52048
,ok 253 should be equal
# teardown
,2017-07-17 11:40:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,2017-07-17 11:40:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:40:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:40:38 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-17 11:40:38 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-17 11:40:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-17 11:40:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-17 11:40:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "138D52C4-835A-43F4-9A26-BD832DE1F30C", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:138D52C4-835A-43F4-9A26-BD832DE1F30C
,2017-07-17 11:40:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-17 11:40:38 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:40:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 254 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:539EB86C-8D4D-4722-BD49-12F54DB,0DA3E
[ThaliCore] Browser.startListening
2017-07-17 11:40:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-17 11:40:38 - INFO thaliMobile: 'Received state ({"discover,yActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:40:38 - INFO thaliMob,ile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 255 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3227DF1D-62DA-41B7-BCBA-445AE86618B2", generation: 0)
,2017-07-17 11:40:38 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3227DF1D-62DA-41B7-BCBA-445AE86618B2","generation":0}'
2017-07-17 11:40:38 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3227DF1D-62DA-41B7-BCBA-445AE86618B2 (syncValue: 7MHeLjLwkz3xXTvOJHnGUwzPFUDzuVot)'
,2017-07-17 11:40:38 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3227DF1D-62DA-41B7-BCBA-445AE86618B2", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "32,27DF1D-62DA-41B7-BCBA-445AE86618B2", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A01F0780-5874-4132-B66C-844CF07ED48B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 0)
2017-07-17 11:40:39 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","generation":0}'
2017-07-17 11:40:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-17 11:40:39 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
[ThaliCore] Session.session(_:peer:didChange:) peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.dein,it
[ThaliCore] Session.disconnect() peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "3227DF1D-62DA-41B7-BCBA-445AE86618B2", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:sy,n,cValue:retryCount:completion:) Peer(uuid: "3227DF1D-62DA-41B7-BCBA-445AE86618B2", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3227DF1D-62DA-41B7-BCBA-445AE86618B2", generatio,n: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5", generation: 0)
2017-07-17 11:40:40 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5","generation":0}'
2017-07-17 11:40:40 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-17 11:40:40 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-17 11:40:40 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "138D52C4-835A-43F4-9A26-BD832DE1F30C", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:32,27DF1D-62DA-41B7-BCBA-445AE86618B2:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "3227DF1D-62DA-41B7-BCBA-445AE86618B2", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,227DF1D-62DA-41B7-BCBA-445AE86618B2", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3227DF1D-62DA-41B7-BCBA-445AE86618B2", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:32,27DF1D-62DA-41B7-BCBA-445AE86618B2:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "3227DF1D-62DA-41B7-BCBA-445AE86618B2", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,227DF1D-62DA-41B7-BCBA-445AE86618B2", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3227DF1D-62DA-41B7-BCBA-445AE86618B2", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:32,27DF1D-62DA-41B7-BCBA-445AE86618B2:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "3227DF1D-62DA-41B7-BCBA-445AE86618B2", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:3227DF1D,-62DA-41B7-BCBA-445AE86618B2 error: max retries exceeded
2017-07-17 11:40:43 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"7MHeLjLwkz3xXTvOJHnGUwzPFUDzuVot","error":"Connection could not be established","portNumber":null}'
2017-0,7-17 11:40:43 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '7MHeLjLwkz3xXTvOJHnGUwzPFUDzuVot', error: 'Connection could not be established', listeningPort: '%s''
2017-07-17 11:40:43 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"3227DF1D-62DA-41B7-BCBA-445AE86618B2","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-17 11:40:43 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-17 11:40:43 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3227DF1D-62DA-41B7-BCBA-445AE86618B2","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-17 11:40:43 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-17 11:40:43 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-17 11:40:43 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for A01F0780-5874-4132-B66C-844CF07ED48B (syncValue: Z5XaUGAvrCQ1JLmVkiz5ZFYtcv7lJXXB)'
,2017-07-17 11:40:43 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A01F0780-5874-4132-B66C-844CF07ED48B:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-17 11:40:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-17 11:40:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:A01F0780-5874-4132-B66C-844CF07ED48B:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A01F0780-5874-4132-B66C-844CF07ED48B:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:A01F0780-5874-4132-B66C-844CF07ED48B:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52062
2017-07-17 11:40:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Z5XaUGAvrCQ1JLmVkiz5ZFYtcv7lJXXB",,"error":null,"portNumber":52062}'
2017-07-17 11:40:45 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Z5XaUGAvrCQ1JLmVkiz5ZFYtcv7lJXXB', error: 'null', listeningPort: '52062''
,ok 256 should be equal
2017-07-17 11:40:45 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5 (syncValue: kuuhrtixwT5jcKiiXqNVOJusIOvucULA)'
2017-07-17 11:40:45 - DEBUG thaliMobileNativeTestUtils: 'Got 'mul,tiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConn,ected:) Peer(uuid: "CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocke,tTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-17 11:40:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FDA92EF8-70AE-4D80-AB07-C80D2F8FD317
[ThaliCore] Advertiser: session connected Peer(uuid: "138D52C4-835A-43F4-9A26-BD832DE1F30C", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:FDA92EF8-70AE-4D80-AB07-C80D2F8FD317 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1D80F1B1-0202-45D3-A18B-E0E00346B988
[ThaliCore] Advertiser: session connected Peer(uuid: "138D52C4-835A-43F4-9A26-BD832DE1F30C", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:1D80F1B1-0202-45D3-A18B-E0E00346B988 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52067
2017-07-17 11:40:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"kuuhrtixwT5jcKiiXqNVOJusIOvucULA",,"error":null,"portNumber":52067}'
2017-07-17 11:40:48 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'kuuhrtixwT5jcKiiXqNVOJusIOvucULA', error: 'null', listeningPort: '52067''
,ok 257 should be equal
,# teardown
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "3227DF1D-62DA-41B7-BCBA-445AE86618B2", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FDA92EF8-70AE-4D80-AB07-C80D2F8FD317
,[ThaliCore] Session.session(_:peer:didChange:) peer:FDA92EF8-70AE-4D80-AB07-C80D2F8FD317 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1D80F1B1-0202-45D3-A18B-E0E00346B988
,[ThaliCore] Session.session(_:peer:didChange:) peer:1D80F1B1-0202-45D3-A18B-E0E00346B988 state: connecting -> connected
,[ThaliCore] BrowserManager.disconnect peer:A01F0780-5874-4132-B66C-844CF07ED48B
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:52062
[ThaliCore] Session.disconnect() peer:A01F0780-5874-4132-B66C-844CF07ED48B:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:A01F0780-5874-4132-B66C-844CF07ED48B:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:52067
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5", generation: 0)
,2017-07-17 11:40:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:40:50 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"kuuhrtixwT5jcKiiXqNVOJusIOvucULA","error":"Session disconnected","portNumber":null}'
,2017-07-17 11:40:50 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-17 11:40:50 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-17 11:40:50 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-17 11:40:50 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# setup
,[ThaliCore] Session.deinit peer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1D80F1B1-0202-45D3-A18B-E0E00346B988 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "138D52C4-835A-43F4-9A26-BD832DE1F30C", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:1D80F1B1-0202-45D3-A18B-E0E00346B988
[ThaliCore] Advert,iserRelay.deinit
[ThaliCore] Session.session(_:peer:didChange:) peer:FDA92EF8-70AE-4D80-AB07-C80D2F8FD317 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "138D52C4-835A-43F4-9A26-BD832DE1F30C", generation: 0)
,2017-07-17 11:40:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:40:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:40:51 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-17 11:40:51 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-17 11:40:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-17 11:40:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-17 11:40:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Multiple local http requests
,[ThaliCore] Session.deinit peer:1D80F1B1-0202-45D3-A18B-E0E00346B988
,listening on 52069
,ok 258 should be equal
,ok 259 should be equal
,ok 260 should be equal
,# teardown
,2017-07-17 11:40:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,2017-07-17 11:40:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:40:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:40:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "138D52C4-835A-43F4-9A26-BD832DE1F30C", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:138D52C4-835A-43F4-9A26-BD832DE1F30C
,2017-07-17 11:40:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-17 11:40:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-17 11:40:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 261 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-17 11:40:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-17 11:40:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-17 11:40:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 262 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "138D52C4-835A-43F4-9A26-BD832DE1F30C", generation: 1)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A01F0780-5874-4132-B66C-844CF07ED48B:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 1)
2017-07-17 11:40:53 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","generation":1}'
2017-07-17 11:40:53 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for A01F0780-5874-4132-B66C-844CF07ED48B, (syncValue: kxsa9ZSD3OWguAJIPSdhen7WjR1NaipF)'
2017-07-17 11:40:53 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A01F0780-5874-4132-B66C-844CF07,ED48B", generation: 1) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 1)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:) peer:A01F0780-5874-4132-B66C-844CF07ED48B:1
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5,", generation: 1)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-17 11:40:53 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailabl,e":true,"peerIdentifier":"CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5","generation":1}'
2017-07-17 11:40:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-17 11:40:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:A01F0780-5874-4132-B66C-844CF07ED48B:1 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A01F0780-5874-4132-B66C-844CF07ED48B:1
,[ThaliCore] Session.session(_:peer:didChange:) peer:A01F0780-5874-4132-B66C-844CF07ED48B:1 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 1)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52076
2017-07-17 11:40:55 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"kxsa9ZSD3OWguAJIPSdhen7WjR1NaipF",,"error":null,"portNumber":52076}'
2017-07-17 11:40:55 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'kxsa9ZSD3OWguAJIPSdhen7WjR1NaipF', error: 'null', listeningPort: '52076''
,ok 263 should be equal
,ok 264 should be equal
,ok 265 should be equal
,2017-07-17 11:40:55 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5 (syncValue: un2RQ85kYj1zm0XkiDDEun7j88P7HypL)'
,2017-07-17 11:40:55 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5", generation: 1) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5", generation: 1)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5:1
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1D80F1B1-0202-45D3-A18B-E0E00346B988
[ThaliCore] Advertiser: session connected Peer(uuid: "138D52C4-835A-43F4-9A26-BD832DE1F30C", generation: 1)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:1D80F1B1-0202-45D3-A18B-E0E00346B988 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FDA92EF8-70AE-4D80-AB07-C80D2F8FD317
[ThaliCore] Advertiser: session connected Peer(uuid: "138D52C4-835A-43F4-9A26-BD832DE1F30C", generation: 1)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:FDA92EF8-70AE-4D80-AB07-C80D2F8FD317 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5:1 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5:1
,[ThaliCore] Session.session(_:peer:didChange:) peer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5:1 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5", generation: 1)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52082
2017-07-17 11:40:58 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"un2RQ85kYj1zm0XkiDDEun7j88P7HypL",,"error":null,"portNumber":52082}'
2017-07-17 11:40:58 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'un2RQ85kYj1zm0XkiDDEun7j88P7HypL', error: 'null', listeningPort: '52082''
,ok 266 should be equal
ok 267 should be equal
ok 268 should be equal
# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1D80F1B1-0202-45D3-A18B-E0E00346B988
[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FDA92EF8-70AE-4D80-AB07-C80D2F8FD317
,[ThaliCore] Session.session(_:peer:didChange:) peer:1D80F1B1-0202-45D3-A18B-E0E00346B988 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:FDA92EF8-70AE-4D80-AB07-C80D2F8FD317 state: connecting -> connected
,[ThaliCore] BrowserManager.disconnect peer:A01F0780-5874-4132-B66C-844CF07ED48B
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:52076
[ThaliCore] Session.disconnect() peer:A01F0780-5874-4132-B66C-844CF07ED48B:1
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5:1 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() po,rt:52082
[ThaliCore] Session.disconnect() peer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5:1
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5", generation: 1)
[ThaliCore] TCPListener.socketDidDisc,onnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:A01F0780-5874-4132-B66C-844CF07ED48B:1
[ThaliCore] BrowserRelay.deinit
[ThaliCore] BrowserManager.disconnect peer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5
2017-07-17 11:40:59 - DEBUG makeIntoCloseAllServer: 'closeAll called o,n server'
2017-07-17 11:40:59 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"un2RQ85kYj1zm0XkiDDEun7j88P7HypL","error":"Session disconnected","portNumber":null}'
2017-07-17 11:40:59 - DEBUG thaliMobileNativeWrapper: 'Received peer, availability changed event with {"peerIdentifier":"CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-17 11:40:59 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due, to not being in started state'
2017-07-17 11:40:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-,0,7-17 11:40:59 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# setup
[ThaliCore] Session.session(_:peer:didChange:) peer:1D80F1B1-0202-45D3-A18B-E0E00346B988 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "138D52C4-835A-43F4-9A26-BD832DE1F30C", generation: 1)
[ThaliCore] ,AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:FDA92EF8-70AE-4D80-AB07-C80D2F8FD317
,[ThaliCore] Session.deinit peer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5:1
[ThaliCore] BrowserRelay.deinit
[ThaliCore] Session.deinit peer:FDA92EF8-70AE-4D80-AB07-C80D2F8FD317
[ThaliCore] AdvertiserRelay.deinit
,# #startListeningForAdvertisements should fail if start not called
,ok 269 specific error should be returned
,# teardown
,ok 270 must be stopped
,2017-07-17 11:41:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:41:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:41:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-17 11:41:00 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-17 11:41:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-17 11:41:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-17 11:41:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 271 specific error should be returned
,# teardown
,ok 272 must be stopped
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:41:01 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-17 11:41:01 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'listening 52086'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-17 11:41:01 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-17 11:41:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 273 no errors
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-17 11:41:01 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-17 11:41:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 274 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:138D52C4-835A-43F4-9A26-BD832DE1F30C
,[ThaliCore] Advertiser.stopAdvertising() peerID:138D52C4-835A-43F4-9A26-BD832DE1F30C
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:41:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:41:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-17 11:41:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 275 must be stopped
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startListeningForAdvertisements many times
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'listening 52087'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2EE3F1E9-E17D-4E7E-8B45-8FFF339A43BF
,[ThaliCore] Browser.startListening
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-17 11:41:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-17 11:41:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 276 no errors
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-17 11:41:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-17 11:41:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 277 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-17 11:41:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-17 11:41:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:41:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-17 11:41:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 278 must be stopped
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'listening 52088'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CA8B3E6E-32B9-428E-A6AE-D4EB513748F6", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:CA8B3E6E-32B9-428E-A6AE-D4EB513748F6
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-17 11:41:02 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-17 11:41:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 279 no errors
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CA8B3E6E-32B9-428E-A6AE-D4EB513748F6", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:CA8B3E6E-32B9-428E-A6AE-D4EB513748F6
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-17 11:41:02 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-17 11:41:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 280 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:CA8B3E6E-32B9-428E-A6AE-D4EB513748F6
[ThaliCore] Advertiser.stopAdvertising() peerID:CA8B3E6E-32B9-428E-A6AE-D4EB513748F6
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:41:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:41:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-17 11:41:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 281 must be stopped
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: ',Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'listening 52091'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingAct,ive":false}'
2017-07-17 11:41:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 282 no errors
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'discover,yAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:41:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 283 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:41:02 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-17 11:41:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-17 11:41:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 284 must be stopped
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:41:02 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can get the network status before starting
,ok 285 network status should have certain non-empty properties
,# teardown
,ok 286 must be stopped
,2017-07-17 11:41:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:41:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:41:03 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-17 11:41:03 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-17 11:41:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-17 11:41:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-17 11:41:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# error returned with bad router
,2017-07-17 11:41:03 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
ok 287 specific error expected
,# teardown
,ok 288 must be stopped
,2017-07-17 11:41:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:41:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:41:03 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-17 11:41:03 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-17 11:41:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-17 11:41:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-17 11:41:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are started when we call start
,2017-07-17 11:41:03 - DEBUG thaliMobileNativeWrapper: 'listening 52092'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:452E22B7-99FD-495E-91C9-F2B8676D901A
[ThaliCore] Browser.st,artListening
2017-07-17 11:41:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-17 11:41:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:41:03 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B6BB5671-8859-49E0-833E-F0B2041C6F31", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,B6BB5671-8859-49E0-833E-F0B2041C6F31
2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-17 11:41:04 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:41:04 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 289 all connection succeed
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:B6BB5671-8859-49E0-833E-F0B2041C6F31
2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-17 11:41:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:41:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:41:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-17 11:41:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 290 must be stopped
2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:41:04 - DEBUG thaliMobil,eNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# TCP Servers Manager should be null when we call start on iOS
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'listening 52095'
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6B13C8D5-D637-4619-BFB2-B092780A17D3
,[ThaliCore] Browser.startListening
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-17 11:41:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-17 11:41:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "93938A04-82DB-44ED-9506-B457568C3DF5", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:93938A04-82DB-44ED-9506-B457568C3DF5
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-17 11:41:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-17 11:41:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 291 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:93938A04-82DB-44ED-9506-B457568C3DF5
2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-17 11:41:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:41:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:41:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,stopped state).'
2017-07-17 11:41:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 292 must be stopped
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are stopped when we call stop
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'listening 52097'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:21E1193B-F7E6-4519-BCDC-7E9D9D608078
,[ThaliCore] Browser.startListening
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-17 11:41:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-17 11:41:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "74186036-F210-4555-8234-63206DFBF724", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:74186036-F210-4555-8234-63206DFBF724
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5", generation: 0)
2017-07-17 11:41:04 - INFO th,aliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}}),'
2017-07-17 11:41:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:74186036-F210-4555-8234-63206DFBF724
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-17 11:41:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:41:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"ad,vertisingActive":false}'
2017-07-17 11:41:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-17 11:41:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 293 is stopped after calling stop
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5","generation":0}]'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5","generation":0}'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,ok 294 connection should fail after stopping
,# teardown
,ok 295 must be stopped
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:05 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is properly hooked up
,2017-07-17 11:41:05 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
,# teardown
,ok 296 must be stopped
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:05 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is return error if we get called on iOS
,ok 297 error description matches
,# teardown
,ok 298 must be stopped
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-17 11:41:05 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is properly hooked up
,2017-07-17 11:41:05 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 299 must be stopped
,2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:41:06 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-17 11:41:06 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is return error if we get called on iOS
,ok 300 error description matches
,# teardown
,ok 301 must be stopped
,2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:41:06 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-17 11:41:06 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure we actually call kill connections properly
,ok 302 IMPLEMENT ME!!!!!!
,# teardown
,ok 303 must be stopped
,2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:41:06 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-17 11:41:06 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-07-17 11:41:06 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 304 must be stopped
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:41:07 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-17 11:41:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-07-17 11:41:07 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 305 must be stopped
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:41:07 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-17 11:41:07 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-07-17 11:41:07 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 306 must be stopped
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-17 11:41:07 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-07-17 11:41:07 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 307 must be stopped
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 308 NOT IMPLEMENTED # SKIP
,# teardown
,ok 309 must be stopped
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure bad PSK connections fail
,2017-07-17 11:41:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 310 must be stopped
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peer changes handled from a queue
,2017-07-17 11:41:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 311 must be stopped
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-07-17 11:41:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 312 must be stopped
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-17 11:41:09 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-07-17 11:41:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 313 must be stopped
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:41:09 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-17 11:41:09 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'listening 52100'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D3CADFE3-DEC0-47D2-AD44-912C34B36427
,[ThaliCore] Browser.startListening
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-17 11:41:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-17 11:41:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 314 discoveryActive matches
,ok 315 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-17 11:41:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-17 11:41:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:41:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 316 discoveryActive matches
,ok 317 advertisingActive matches
,2017-07-17 11:41:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'listening 52101'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "04350879-3BA0-4D16-93D5-A6731FAD4BE1", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:04350879-3BA0-4D16-93D5-A6731FAD4BE1
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-17 11:41:09 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-17 11:41:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 318 discoveryActive matches
,ok 319 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:04350879-3BA0-4D16-93D5-A6731FAD4BE1
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:41:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 320 discoveryActive matches
,ok 321 advertisingActive matches
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:41:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-17 11:41:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'listening 52103'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:41:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:41:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-17 11:41:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 322 must be stopped
,2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS
,2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'listening 52104'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:059B9078-02D1-4B2E-A83B-5BC4834F2D81
,[ThaliCore] Browser.startListening
,2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-17 11:41:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-17 11:41:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "143BC745-1F91-4BA2-A049-76A23351B43F", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:143BC745-1F91-4BA2-A049-76A23351B43F
2017-07-17 1,1:41:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-17 11:41:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-17 11:41:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A01F0780-5874-4132-B66C-844CF07ED48B:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5", generation: 1)
,2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5","generation":0}]'
2017-07-17 11:41:10 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5","generation":0}'
,2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","generation":0}]'
2017-07-17 11:41:10 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","generation":0}'
2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native, layer [{"peerAvailable":true,"peerIdentifier":"CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5","generation":1}]'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A01F0780-5874-4132-B66C-844CF07ED48B:1
2017-07-17 11:41:10 - DEBUG thaliMobileN,ativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5","generation":1}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B",, generation: 1)
,2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-17 11:41:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 323 portNumber equal null
,2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-17 11:41:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5","peerAvailable":true,"generation":1,"portNumber":null}'
,2017-07-17 11:41:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5","connectionType":"MPCF","peerAvailable":true,"generation":1,"newAddressPort":false}'
,# teardown
,2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","generation":1}]'
,2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","generation":1}'
,2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","peerAvailable":true,"generation":1,"portNumber":null}'
,2017-07-17 11:41:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","connectionType":"MPCF","peerAvailable":true,"generation":1,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C1119AE2-6CED-48C1-9D20-CA6950622AA0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C1119AE2-6CED-48C1-9D20-CA6950622AA0", generation: 0)
2017-07-17 11:41:11 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"C1119AE2-6CED-48C1-9D20-CA6950622AA0","generation":0}]'
2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"C1119AE2-6CED-48C1-9D20-CA6950622AA0","generation":0}'
,2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"C1119AE2-6CED-48C1-9D20-CA6950622AA0","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-17 11:41:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"C1119AE2-6CED-48C1-9D20-CA6950622AA0","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:143BC745-1F91-4BA2-A049-76A23351B43F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "143BC745-1F91-4BA2-A049-76A23351B43F", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6B833D50-0F9F-437B-A9E0-D2582037231A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6B833D50-0F9F-437B-A9E0-D2582037231A", generation: 0)
2017-07-17 11:41:11 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"6B833D50-0F9F-437B-A9E0-D2582037231A","generation":0}]'
2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"6B833D50-0F9F-437B-A9E0-D2582037231A","generation":0}'
,2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"6B833D50-0F9F-437B-A9E0-D2582037231A","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-17 11:41:11 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6B833D50-0F9F-437B-A9E0-D2582037231A","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:143BC745-1F91-4BA2-A049-76A23351B43F
2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-17 11:41:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-17 11:41:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:41:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-17 11:41:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 324 must be stopped
,2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests between peers
,2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'listening 52106'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FF7B58EF-2C14-4BDD-8729-7E0F9727B5BA
[ThaliCore] Browser.startListening
,2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-17 11:41:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-17 11:41:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "46D0B3B1-9593-4088-AF16-D54D985A55CD", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:46D0B3B1-9593-4088-AF16-D54D985A55CD
,2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-17 11:41:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:41:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A01F0780-5874-4132-B66C-844CF07ED48B:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A01F0780-5874-4132-B66C-844CF07ED48B:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 1)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:,) found peer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5:1
2017-07-17 11:41:12 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","generation",:0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5", generation: 1)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C1119AE2-6CED-48C1-9D20-CA6950622AA0:0
2017-07-17 11:41:12 -, [ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C1119AE2-6CED-48C1-9D20-CA6950622AA0", generation: 0)
DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"A01F0780-5874-4132-B,66C-844CF07ED48B","generation":0}'
,2017-07-17 11:41:12 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","generation":1}]'
2017-07-17 11:41:12 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","generation":1}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6B833D50-0F9F-437B-A9E0-D2582037231A:0
2017-07-17 11:41:12 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdent,ifier":"CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5","generation":0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6B833D50-0F9F-437B-A9E0-D2582037231A", generation: 0)
2017-07-17 11:41:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5","generation":0}'
,2017-07-17 11:41:12 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5","generation":1}]'
,2017-07-17 11:41:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5","generation":1}'
,2017-07-17 11:41:12 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"C1119AE2-6CED-48C1-9D20-CA6950622AA0","generation":0}]'
2017-07-17 11:41:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"C1119AE2-6CED-48C1-9D20-CA6950622AA0","generation":0}'
,2017-07-17 11:41:12 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"6B833D50-0F9F-437B-A9E0-D2582037231A","generation":0}]'
,2017-07-17 11:41:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"6B833D50-0F9F-437B-A9E0-D2582037231A","generation":0}'
,2017-07-17 11:41:12 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-17 11:41:12 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-17 11:41:12 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for A01F0780-5874-4132-B66C-844CF07ED48B (syncValue: AmyfBEVIz1jg94exauU5Z6LE1Wv8dHzP)'
,2017-07-17 11:41:12 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 1) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 1)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A01F0780-5874-4132-B66C-844CF07ED48B:1
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-07-17 11:41:12 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","peerAvailable":true,"generation":1,"portNumber":null}'
,2017-07-17 11:41:12 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","peerAvailable":true,"generation":1,"portNumber":null}'
,2017-07-17 11:41:12 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-17 11:41:12 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-17 11:41:12 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5","peerAvailable":true,"generation":1,"portNumber":null}'
,2017-07-17 11:41:12 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5","peerAvailable":true,"generation":1,"portNumber":null}'
,2017-07-17 11:41:12 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"C1119AE2-6CED-48C1-9D20-CA6950622AA0","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-17 11:41:12 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"C1119AE2-6CED-48C1-9D20-CA6950622AA0","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-17 11:41:12 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"6B,833D50-0F9F-437B-A9E0-D2582037231A","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-17 11:41:12 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"6B833D50-0F9F-437B-A9E0-D2582037231A","peerAvailable":true,"generation":0,,"portNumber":null}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:C1119AE2-6CED-48C1-9D20-CA6950622AA0:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "C1119AE2-6CED-48C1-9D20-CA6950622AA0", generation: 0)
2017-07-17 11:41:13 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"C1119AE2-6CED-48C1-9D20-CA6950622AA0","generation":0}]'
2017-07-17 11:41:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"C1119AE2-6CED-48C1-9D20-CA6950622AA0","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9424ABB4-619A-4022-A320-5F9F8BA181B7:0
[ThaliCore] BrowserManager.foundPeerHandle,r peer:Peer(uuid: "9424ABB4-619A-4022-A320-5F9F8BA181B7", generation: 0)
2017-07-17 11:41:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"C1119AE2-6CED-48C1-9D20-CA6950622AA0","peerAvailable":false,"generation":n,u,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DDA978C1-76A0-4186-8090-EFD75BD499F8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DDA978C1-76A0-4186-8090-EFD75BD499F8", generation: 0)
ll,"portNumber":null}'
2017-,07-17 11:41:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"C1119AE2-6CED-48C1-9D20-CA6950622AA0","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-17 11:41:13 - DE,BUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"9424ABB4-619A-4022-A320-5F9F8BA181B7","generation":0}]'
2017-07-17 11:41:13 - DEBUG thaliMobileNativeWrapper: 'Received peer a,vailability changed event with {"peerAvailable":true,"peerIdentifier":"9424ABB4-619A-4022-A320-5F9F8BA181B7","generation":0}'
2017-07-17 11:41:13 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable,",[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:46D0B3B1-9593-4088-AF16-D54D985A55CD:0
:true,"peerIdentifier":"DDA978C1-76A0-4186-8090-EFD75BD499F8","generation":0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "46D,0B3B1-9593-4088-AF16-D54D985A55CD", generation: 0)
2017-07-17 11:41:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"DDA978C1-76A0-4186-8090-EFD75BD499F8","generation":0}'
,2017-07-17 11:41:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"9424ABB4-619A-4022-A320-5F9F8BA181B7","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-17 11:41:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9424ABB4-619A-4022-A320-5F9F8BA181B7","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-17 11:41:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"9424ABB4-619A-4022-A320-5F9F8BA181B7","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-17 11:41:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"DDA978C1-76A0-4186-8090-EFD75BD499F8","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-17 11:41:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"DDA978C1-76A0-4186-8090-EFD75BD499F8","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-17 11:41:13 - ,DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"DDA978C1-76A0-4186-8090-EFD75BD499F8","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:A01F0780-5874-4132-B66C-844CF07ED48B:1 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A0,1F0780-5874-4132-B66C-844CF07ED48B:1
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 1)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,01F0780-5874-4132-B66C-844CF07ED48B", generation: 1) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 1)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:A01F0780-5874-4132-B66C-844CF07ED48B:1
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:A01F0780-5874-4132-B66C-844CF07ED48B:1
[ThaliCore] BrowserRelay.deinit
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C1119AE2-6CED-48C1-9D20-CA6950622AA0:0
[ThaliCore] BrowserManager.foundPeerHand,ler peer:Peer(uuid: "C1119AE2-6CED-48C1-9D20-CA6950622AA0", generation: 0)
2017-07-17 11:41:14 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"C1119AE2-6CED-48C1-9D20-CA6,950622AA0","generation":0}]'
2017-07-17 11:41:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"C1119AE2-6CED-48C1-9D20-CA6950622AA0","generation":0}'
,2017-07-17 11:41:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"C1119AE2-6CED-48C1-9D20-CA6950622AA0","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-17 11:41:14 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"C1119AE2-6CED-48C1-9D20-CA6950622AA0","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-17 11:41:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"C1119AE2-6CED-48C1-9D20-CA6950622AA0","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:C1119AE2-6CED-48C1-9D20-CA6950622AA0:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "C1119AE2-6CED-48C1-9D20-CA6950622AA0", generation: 0)
2017-07-17 11:41:15 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"C1119AE2-6CED-48C1-9D20-CA6950622AA0","generation":0}]'
2017-07-17 11:41:15 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"C1119AE2-6CED-48C1-9D20-CA6950622AA0","generation":0}'
,2017-07-17 11:41:15 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"C1119AE2-6CED-48C1-9D20-CA6950622AA0","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-17 11:41:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"C1119AE2-6CED-48C1-9D20-CA6950622AA0","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:A01F0780-5874-4132-B66C-844CF07ED48B:1 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A0,1F0780-5874-4132-B66C-844CF07ED48B:1
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 1)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,01F0780-5874-4132-B66C-844CF07ED48B", generation: 1) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 1)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:A01F0780-5874-4132-B66C-844CF07ED48B:1
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:A01F0780-5874-4132-B66C-844CF07ED48B:1
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:A01F0780-5874-4132-B66C-844CF07ED48B:1 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A01F0780-5874-4132-B66C-844CF07ED48B:1
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 1)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,01F0780-5874-4132-B66C-844CF07ED48B", generation: 1) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 1)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:A01F0780-5874-4132-B66C-844CF07ED48B:1
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:A01F0780-5874-4132-B66C-844CF07ED48B:1
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:A01F0780-5874-4132-B66C-844CF07ED48B:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 0)
[ThaliCore] Browser.browser(_:lostPeer:) lost peer,:A01F0780-5874-4132-B66C-844CF07ED48B:1
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 1)
2017-07-17 11:41:16 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from n,ative layer [{"peerAvailable":false,"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","generation":1}]'
2017-07-17 11:41:16 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"A01,F0780-5874-4132-B66C-844CF07ED48B","generation":1}'
,2017-07-17 11:41:16 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-17 11:41:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:A01F0780-5874-4132-B66C-844CF07ED48B:1 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 1)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:A01F0780-5874-4132-B66C-844CF07ED48B error: max retries exceeded
2017-07-17 11:41:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"AmyfBEVIz1jg94exa,uU5Z6LE1Wv8dHzP","error":"Connection could not be established","portNumber":null}'
2017-07-17 11:41:17 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'AmyfBEVIz1jg94exauU5Z6LE1Wv8dHzP', error: 'Connection could not be establishe,d', listeningPort: '%s''
2017-07-17 11:41:17 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-17 ,1,1:41:17 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-17 11:41:17 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-17 11:41:17 - DEBUG thali,MobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A01F0780-5874-4132-B66C-844CF07ED48B","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-17 11:41:17 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peer,Identifier":"A01F0780-5874-4132-B66C-844CF07ED48B","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] BrowserManager.disconnect peer:A01F0780-5874-4132-B66C-844CF07ED48B
2017-07-17 11:41:17 - ERROR thaliMobileNativeTestUtils: 'Fatal co,nnect error: 'Connection could not be established''
2017-07-17 11:41:17 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5 (syncValue: PAU1FQDd23GM3pGlTlHSwNF3Pl3XTVvR)'
2017-07-17 11:41:17 - DEBUG thaliMo,b,ileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5", generation: 1) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:se,ssionConnected:sessionNotConnected:) Peer(uuid: "CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5", generation: 1)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5:1
[ThaliCore] BrowserRelay.init(session:,generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:6B833D50-0F9F-437B-A9E0-D2582037231A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "6B833D50-0F9F-437B-A9E0-D2582037231A", generation: 0)
2017-07-17 11:41:17 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"6B833D50-0F9F-437B-A9E0-D2582037231A","generation":0}]'
,2017-07-17 11:41:17 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"6B833D50-0F9F-437B-A9E0-D2582037231A","generation":0}'
,2017-07-17 11:41:17 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"6B833D50-0F9F-437B-A9E0-D2582037231A","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-17 11:41:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6B833D50-0F9F-437B-A9E0-D2582037231A","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5:1 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:CF,1FC3C9-6D72-4F5D-9EF5-721EF8C363B5:1
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5", generation: 1)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,F1FC3C9-6D72-4F5D-9EF5-721EF8C363B5", generation: 1) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5", generation: 1)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5:1
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5:1
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5", generation: 0)
[ThaliCore] Browser.browser(_:lostPeer:) lost peer,:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5:1
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5", generation: 1)
2017-07-17 11:41:18 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from n,ative layer [{"peerAvailable":false,"peerIdentifier":"CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5","generation":1}]'
2017-07-17 11:41:18 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"CF1,FC3C9-6D72-4F5D-9EF5-721EF8C363B5","generation":1}'
,2017-07-17 11:41:18 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-17 11:41:18 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5:1 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5", generation: 1)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5", generation: 1) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CF,1FC3C9-6D72-4F5D-9EF5-721EF8C363B5", generation: 1)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-17 11:41:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"PAU1FQDd23GM3pGlTlHSwNF3Pl3XTVvR","error":"Peer is unavailable",,"portNumber":null}'
2017-07-17 11:41:19 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'PAU1FQDd23GM3pGlTlHSwNF3Pl3XTVvR', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-17 11:41:19 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-17 11:41:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed ,event with {"peerIdentifier":"CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-17 11:41:19 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-17 11:41:19 - DEBUG thali,MobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-17 11:41:19 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peer,Identifier":"CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] BrowserManager.disconnect peer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5
2017-07-17 11:41:19 - ERROR thaliMobileNativeTestUtils: 'Fatal co,nnect error: 'Peer is unavailable''
2017-07-17 11:41:19 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9424ABB4-619A-4022-A320-5F9F8BA181B7 (syncValue: ndzOe6byjOx6gHyhRHJvnQETWkJGyRYB)'
2017-07-17 11:41:19 - DEBUG thaliMobileNativeTestUt,i,ls: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9424ABB4-619A-4022-A320-5F9F8BA181B7", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:s,essionNotConnected:) Peer(uuid: "9424ABB4-619A-4022-A320-5F9F8BA181B7", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9424ABB4-619A-4022-A320-5F9F8BA181B7:0
[ThaliCore] BrowserRelay.init(session:generation:creat,eVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:9424ABB4-619A-4022-A320-5F9F8BA181B7:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9424ABB4-619A-4022-A320-5F9F8BA181B7:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:9424ABB4-619A-4022-A320-5F9F8BA181B7:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "9424ABB4-619A-4022-A320-5F9F8BA181B7", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52123
2017-07-17 11:41:23 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ndzOe6byjOx6gHyhRHJvnQETWkJGyRYB",,"error":null,"portNumber":52123}'
2017-07-17 11:41:23 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ndzOe6byjOx6gHyhRHJvnQETWkJGyRYB', error: 'null', listeningPort: '52123''
,2017-07-17 11:41:23 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9424ABB4-619A-4022-A320-5F9F8BA181B7:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9424ABB4-619A-4022-A320-5F9F8BA181B7:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:18 [1, 2, 6, 18]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-17 11:41:23 - DEBUG testUtils: 'Got response data'
2017-07-17 11:41:23 - DEBUG testUtils: 'Got end'
ok 325 response body should match testData
ok 326 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:46D0B3B1-9593-4088-AF16-D54D985A55CD
2017-07-17 11:41:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-17 11:41:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:41:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-07-17 11:41:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:41:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-17 11:41:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 327 must be stopped
[ThaliCore] BrowserManager.disconnect p,eer:9424ABB4-619A-4022-A320-5F9F8BA181B7
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:52123
[ThaliCore] VirtualSocket.closeStreams() vsID:18
[ThaliCore] TCPListener,.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.,didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket exited RunLoop vsID:18
[ThaliCore] Session.disconnect() peer:9424ABB4-619A-4022-A320-5F9F8BA181B7:0
[ThaliCore] Virtu,a,lSocket.closeStreams() vsID:18
[ThaliCore] Session.deinit peer:9424ABB4-619A-4022-A320-5F9F8BA181B7:0
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:18 [1, 2, 6]
[ThaliCore] TCPListener.deinit
[ThaliCore] BrowserRelay.deinit
,2017-07-17 11:41:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:41:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:41:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can still do HTTP requests between peers with coordinator
,2017-07-17 11:41:24 - DEBUG thaliMobileNativeWrapper: 'listening 52125'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:CE42B30F-CC2B-4155-B099-9AE7DC113566
[ThaliCore] Browser.st,artListening
2017-07-17 11:41:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-17 11:41:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:41:24 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "304D8B74-5781-4F43-ACB7-9345FE1C4478", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,304D8B74-5781-4F43-ACB7-9345FE1C4478
2017-07-17 11:41:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-17 11:41:24 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:41:24 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DDA978C1-76A0-4186-8090-EFD75BD499F8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DDA978C1-76A0-4186-8090-EFD75BD499F8", generation: 0)
2017-07-17 11:41:25 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"DDA978C1-76A0-4186-8090-EFD75BD499F8","generation":0}]'
2017-07-17 11:41:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"DDA978C1-76A0-4186-8090-EFD75BD499F8","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9424ABB4-619A-4022-A320-5F9F8BA181B7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9424ABB4-619A-4022-A320-5F9F8BA181B7", generation: 0)
2017-07-17 11:41:25 - DEBUG t,haliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"DDA978C1-76A0-4186-8090-EFD75BD499F8","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-17 11:41:25 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"pe,erIdentifier":"DDA978C1-76A0-4186-8090-EFD75BD499F8","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-17 11:41:25 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for DDA978C1-76A0-4186-8090-EFD75BD499F8 (syncValue: W7wxklvBR5iXEvT,havIWJQH7BCHDmuLj)'
,2017-07-17 11:41:25 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "DDA978C1-76A0-4186-8090-EFD75BD499F8", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DDA978C1-76A0-4186-8090-EFD75BD499F8", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DDA978C1-76A0-4186-8090-EFD75BD499F8:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-17 11:41:25 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"9424ABB4-619A-4022-A320-5F9F8BA181B7","generation":0}]'
,2017-07-17 11:41:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"9424ABB4-619A-4022-A320-5F9F8BA181B7","generation":0}'
,2017-07-17 11:41:25 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"9424ABB4-619A-4022-A320-5F9F8BA181B7","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-17 11:41:25 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"9424ABB4-619A-4022-A320-5F9F8BA181B7","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:9424ABB4-619A-4022-A320-5F9F8BA181B7:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "9424ABB4-619A-4022-A320-5F9F8BA181B7", generation: 0)
2017-07-17 11:41:26 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"9424ABB4-619A-4022-A320-5F9F8BA181B7","generation":0}]'
2017-07-17 11:41:26 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"9424ABB4-619A-4022-A320-5F9F8BA181B7","generation":0}'
,2017-07-17 11:41:26 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"9424ABB4-619A-4022-A320-5F9F8BA181B7","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-17 11:41:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9424ABB4-619A-4022-A320-5F9F8BA181B7","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:DDA978C1-76A0-4186-8090-EFD75BD499F8:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:DD,A978C1-76A0-4186-8090-EFD75BD499F8:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "DDA978C1-76A0-4186-8090-EFD75BD499F8", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,DA978C1-76A0-4186-8090-EFD75BD499F8", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DDA978C1-76A0-4186-8090-EFD75BD499F8", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:DDA978C1-76A0-4186-8090-EFD75BD499F8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:DDA978C1-76A0-4186-8090-EFD75BD499F8:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F3572614-3152-45C7-97AC-98014F29C3FB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F3572614-3152-45C7-97AC-98014F29C3FB", generation: 0)
2017-07-17 11:41:26 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F3572614-3152-45C7-97AC-98014F29C3FB","generation":0}]'
2017-07-17 11:41:26 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"F3572614-3152-45C7-97AC-98014F29C3FB","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:304D8B74-5781-4F43-ACB7-9345FE1C4478:0
[ThaliCore] BrowserMana,ger.foundPeerHandler peer:Peer(uuid: "304D8B74-5781-4F43-ACB7-9345FE1C4478", generation: 0)
2017-07-17 11:41:26 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"F3572614-3152-45C7-97AC-98014F29C3FB","peerAvai,l,able":true,"generation":0,"portNumber":null}'
2017-07-17 11:41:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"F3572614-3152-45C7-97AC-98014F29C3FB","connectionType":"MPCF","peerAvailable":true,"generation":0,",newAddressPort":false}'
2017-07-17 11:41:26 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"F3572614-3152-45C7-97AC-98014F29C3FB","peerAvailable":true,"generation":0,"portNumber":null}'
[ThaliCore] Browser.browser(_:foundPeer:withDi,scoveryInfo:) found peer:58223822-23C2-4AFC-A05A-9BEDE692E47A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "58223822-23C2-4AFC-A05A-9BEDE692E47A", generation: 0)
2017-07-17 11:41:26 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailab,ilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"58223822-23C2-4AFC-A05A-9BEDE692E47A","generation":0}]'
2017-07-17 11:41:26 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":tr,u,e,"peerIdentifier":"58223822-23C2-4AFC-A05A-9BEDE692E47A","generation":0}'
,2017-07-17 11:41:26 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"58223822-23C2-4AFC-A05A-9BEDE692E47A","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-17 11:41:26 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"58223822-23C2-4AFC-A05A-9BEDE692E47A","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-17 11:41:26 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"58223822-23C2-4AFC-A05A-9BEDE692E47A","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:DDA978C1-76A0-4186-8090-EFD75BD499F8:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:DD,A978C1-76A0-4186-8090-EFD75BD499F8:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "DDA978C1-76A0-4186-8090-EFD75BD499F8", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,DA978C1-76A0-4186-8090-EFD75BD499F8", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DDA978C1-76A0-4186-8090-EFD75BD499F8", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:DDA978C1-76A0-4186-8090-EFD75BD499F8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:DDA978C1-76A0-4186-8090-EFD75BD499F8:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:DDA978C1-76A0-4186-8090-EFD75BD499F8:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "DDA978C1-76A0-4186-8090-EFD75BD499F8", generation: 0)
,2017-07-17 11:41:28 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"DDA978C1-76A0-4186-8090-EFD75BD499F8","generation":0}]'
,2017-07-17 11:41:28 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"DDA978C1-76A0-4186-8090-EFD75BD499F8","generation":0}'
,2017-07-17 11:41:28 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"DDA978C1-76A0-4186-8090-EFD75BD499F8","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-17 11:41:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"DDA978C1-76A0-4186-8090-EFD75BD499F8","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:DDA978C1-76A0-4186-8090-EFD75BD499F8:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "DDA978C1-76A0-4186-8090-EFD75BD499F8", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "DDA978C1-76A0-4186-8090-EFD75BD499F8", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DD,A978C1-76A0-4186-8090-EFD75BD499F8", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-17 11:41:28 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"W7wxklvBR5iXEvThavIWJQH7BCHDmuLj","error":"Peer is unavailable",,"portNumber":null}'
2017-07-17 11:41:28 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'W7wxklvBR5iXEvThavIWJQH7BCHDmuLj', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-17 11:41:28 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"DDA978C1-76A0-4186-8090-EFD75BD499F8","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-17 11:41:28 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed ,event with {"peerIdentifier":"DDA978C1-76A0-4186-8090-EFD75BD499F8","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-17 11:41:28 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"DDA978C1-76A0-4186-8090-EFD75BD499F8","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-17 11:41:28 - DEBUG thali,MobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"DDA978C1-76A0-4186-8090-EFD75BD499F8","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-17 11:41:28 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peer,Identifier":"DDA978C1-76A0-4186-8090-EFD75BD499F8","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] BrowserManager.disconnect peer:DDA978C1-76A0-4186-8090-EFD75BD499F8
2017-07-17 11:41:28 - ERROR thaliMobileNativeTestUtils: 'Fatal co,nnect error: 'Peer is unavailable''
2017-07-17 11:41:28 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F3572614-3152-45C7-97AC-98014F29C3FB (syncValue: CUOyny4dfvTMo7TjiFaqpGgnA5E8uNf5)'
2017-07-17 11:41:28 - DEBUG thaliMobileNativeTestUt,i,ls: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F3572614-3152-45C7-97AC-98014F29C3FB", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F3572614-3152-45C7-97AC-98014F29C3FB", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F3572614-3152-45C7-97AC-98014F29C3FB:0
[ThaliCore] BrowserRelay.init(session:generation:creat,eVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:F3572614-3152-45C7-97AC-98014F29C3FB:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:027C6EEA-7FF8-4C41-8901-71E7E29D5622
[ThaliCore] Advertiser: session connected Peer(uuid: "304D8B74-5781-4F43-ACB7-9345FE1C4478", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:027C6EEA-7FF8-4C41-8901-71E7E29D5622 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:EE485A3A-73F5-4E3B-8875-AACA32AE9DAA
[ThaliCore] Advertiser: session connected Peer(uuid: "304D8B74-5781-4F43-ACB7-9345FE1C4478", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:EE485A3A-73F5-4E3B-8875-AACA32AE9DAA state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F3572614-3152-45C7-97AC-98014F29C3FB:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:F3572614-3152-45C7-97AC-98014F29C3FB:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "F3572614-3152-45C7-97AC-98014F29C3FB", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52139
2017-07-17 11:41:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"CUOyny4dfvTMo7TjiFaqpGgnA5E8uNf5",,"error":null,"portNumber":52139}'
2017-07-17 11:41:31 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'CUOyny4dfvTMo7TjiFaqpGgnA5E8uNf5', error: 'null', listeningPort: '52139''
2017-07-17 11:41:31 - WARN thaliMobileNativeTestUti,ls: 'Retry count for getSamePeerWithRetry is 1'
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F3572614-3152-45C7-97AC-98014F29C3FB:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F3572614-3152-45C7-97AC-98014F29C3FB:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [1, 2, 6, 19]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-17 11:41:31 - DEBUG testUtils: 'Got response data'
,2017-07-17 11:41:31 - DEBUG testUtils: 'Got end'
,ok 328 response body should match testData
,ok 329 must be started
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:027C6EEA-7FF8-4C41-8901-71E7E29D5622
,[ThaliCore] Session.session(_:peer:didChange:) peer:027C6EEA-7FF8-4C41-8901-71E7E29D5622 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:027C6EEA-7FF8-4C41-8901-71E7E29D5622
[ThaliCore] Session.startOutputStream(with:) peer:027C6EEA-7FF8-4C41-8901-71E7E29D5622
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [1, 2, 6, 19, 20]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-17 11:41:33 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:EE485A3A-73F5-4E3B-8875-AACA32AE9DAA
,[ThaliCore] Session.session(_:peer:didChange:) peer:EE485A3A-73F5-4E3B-8875-AACA32AE9DAA state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:EE485A3A-73F5-4E3B-8875-AACA32AE9DAA
[ThaliCore] Session.startOutputStream(with:) peer:EE485A3A-73F5-4E3B-8875-AACA32AE9DAA
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,1 [1, 2, 6, 19, 20, 21]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-17 11:41:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:41:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:41:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:41:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:41:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:41:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:41:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:41:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:42:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:42:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:42:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:42:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:42:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:42:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
2017-07-17 11:42:31 - INFO, CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server ,that is not listening yet witheatNotRunning set to true'
2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOG,GER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoi,n,ts plugin delay interval'
2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-07-17 11:42:31 - INFO Coordin,atedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue, and run in order'
2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
2017-07-17 11:,42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
2017-07-17 11:42:31 - INF,O, CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER resu,lt: passed - another'
2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
2017-07-17 11:42:31 - INFO CoordinatedClient: '***T,EST_LOGGER result: passed - test sinon sansbox spy'
2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox ,stub override'
2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
2017-07-17 ,1,1:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiConnect properly fails on legal but non-existent peerID'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with invalid syncValue'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call disconnect with invalid peer id'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - disconnect doesn't fail on plausible but bogus peer ID'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Get same port when trying to connect multiple times on iOS'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - initial peer discovery'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 1'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 2'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - check latest peer discovery'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Set up for no peer discovery test'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - no peer discovery'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits incomingConnectionState'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server connections all up'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can create servers manager'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling stop without start causes error'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can start/stop servers manager'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connection'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single local http request'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single coordinated request ios native'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple local http requests'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple coordinated request ios native'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status before starting'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - error returned with bad router'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are started when we call start'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP Servers Manager should be null when we call start on iOS'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are stopped when we call stop'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateConnection is properly hooked up'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateConnection is return error if we get called on iOS'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateListener is properly hooked up'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateListener is return error if we get called on iOS'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure we actually call kill connections properly'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from multiConnectConnection'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure bad PSK connections fail'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer changes handled from a queue'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - relaying discoveryAdvertisingStateUpdateNonTCP'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - we successfully receive and replay discoveryAdvertisingStateUpdate'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests between peers'
,2017-07-17 11:42:31 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - can still do HTTP requests between peers with coordinator, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Application/7A4809CC-2E8,E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/blu,ebird/js/release/timers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1
''
,2017-07-17 11:42:31 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-07-17 11:42:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:42:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:42:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:42:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:42:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:42:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:43:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:43:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:43:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:43:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:43:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:43:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:43:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:43:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:43:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:43:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:44:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:44:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:44:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:44:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:44:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:44:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:44:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:44:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:44:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:44:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:44:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:44:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:45:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:45:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-4,46F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:45:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:45:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:45:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:45:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:45:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:45:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:45:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:45:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:45:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:45:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:46:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:46:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:46:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:46:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:46:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:46:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:46:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:46:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:46:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:46:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:46:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:46:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:47:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:47:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:47:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:47:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-4,46F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:47:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:47:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-4,46F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:47:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:47:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-4,46F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:47:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:47:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:47:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:47:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:48:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:48:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:48:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:48:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:48:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:48:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:48:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:48:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:48:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:48:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:48:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:48:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:49:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:49:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:49:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:49:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:49:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:49:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:49:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:49:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:49:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:49:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:49:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:49:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:50:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:50:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:50:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:50:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-4,46F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:50:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:50:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:50:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:50:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:50:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:50:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:50:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:50:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:51:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:51:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:51:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:51:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-4,46F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:51:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:51:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:51:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:51:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:51:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:51:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:51:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:51:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:52:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:52:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:52:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:52:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:52:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:52:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:52:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:52:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:52:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:52:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:52:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:52:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:53:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:53:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:53:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:53:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:53:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:53:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:53:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:53:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-4,46F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:53:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:53:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:53:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:53:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:54:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:54:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:54:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:54:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:54:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:54:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:54:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:54:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:54:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:54:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:54:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:54:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:55:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:55:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:55:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:55:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:55:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:55:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:55:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:55:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:55:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:55:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:55:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:55:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:56:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:56:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:56:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:56:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:56:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:56:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:56:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:56:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:56:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:56:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:56:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:56:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:57:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:57:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:57:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:57:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:57:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:57:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:57:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:57:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:57:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446,F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:57:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/7A4809CC-2E8E-446F-A834-454B6481AE0E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''

```
