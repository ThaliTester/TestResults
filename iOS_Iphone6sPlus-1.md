#### Test 132007755285fc7e_iOS_Iphone6sPlus-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/132007755285fc7e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/595C947D-6DE1-47FD-8253-7DC269962487/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'
,Executing commands in '/tmp/595C947D-6DE1-47FD-8253-7DC269962487/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/132007755285fc7e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/132007755285fc7e/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55597"
,(lldb)     command script import "/tmp/595C947D-6DE1-47FD-8253-7DC269962487/fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.py"
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
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-07-24 12:10:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:10:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:10:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:10:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:10:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 12:10:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:10:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DE269C40-AE42-4AF3-B5,17-DD1F1ACA9766", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:DE269C40-AE42-4AF3-B517-DD1F1ACA9766
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2FA0F1F1-EFCB-4751-A064-CD7B25048ABA
[ThaliCore] Browser,.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C41E3101-,4978-421F-AE17-AC0283FF4A64
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1704303A-7E73-46F1-8264-1FD3C6492031", generation: 0)
[ThaliCore] Advertiser.startAdvertisi,ng with peerID:1704303A-7E73-46F1-8264-1FD3C6492031
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1704303A-7E73-46F1-8264-1FD3C6492031:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1704303A-7E73-46F1-8264-1FD3C6492031", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo,rrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-07-24 12:10:07 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.60621303319931
,2017-07-24 12:10:07 - DEBUG UnitTest_app: 'My device name is: 'Apple-Iphone6sPlus-1''
,2017-07-24 12:10:07 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:1704303A-7E73-46F1-8264-1FD3C6492031:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "1704303A-7E73-46F1-8264-1FD3C6492031", generation: 0)
,2017-07-24 12:10:08 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-24 12:10:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-24 12:10:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-24 12:10:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-24 12:10:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-24 12:10:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-24 12:10:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-24 12:10:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-24 12:10:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-24 12:10:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-24 12:10:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-24 12:10:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-24 12:10:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-24 12:10:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-24 12:10:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-24 12:10:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-24 12:10:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-24 12:10:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-24 12:10:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-24 12:10:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-24 12:10:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-24 12:10:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-24 12:10:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-24 12:10:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-24 12:10:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-24 12:10:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-24 12:10:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-24 12:10:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-24 12:10:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-24 12:10:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-24 12:10:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-24 12:10:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-24 12:10:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-24 12:10:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-24 12:10:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-24 12:10:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-24 12:10:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-24 12:10:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-24 12:10:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-24 12:10:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-24 12:10:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-24 12:10:10 - DEBUG UnitTest_app: 'Unit Test app is loaded'
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-24 12:10:10 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-24 12:10:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:10:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:10:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:10:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:10:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:10:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:10:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:10:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:10:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:10:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:10:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:10:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:10:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:11:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:11:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:11:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:11:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:11:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:11:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:11:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:11:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:11:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:11:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:11:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:11:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:12:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:12:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:12:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:12:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:12:26 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-07-24 12:12:26 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-24 12:12:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 1 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll with promise
,2017-07-24 12:12:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 2 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-24 12:12:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-07-24 12:12:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-07-24 12:12:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-07-24 12:12:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-07-24 12:12:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-07-24 12:12:35 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
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
,2017-07-24 12:12:46 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-07-24 12:12:47 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-07-24 12:12:48 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
,2017-07-24 12:12:51 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-24 12:12:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:12:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:12:52 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:12:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 12:12:52 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 12:12:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 12:12:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 12:12:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-24 12:12:52 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 12:12:53 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E5A32D8A-0A2C-4E20-B4F6-10EA2143610C
[ThaliCore] Browser.startListening
2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 12:12:53 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-24 12:12:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvert,isements()
[ThaliCore] Browser.stopListening()
2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:12:53 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:12:53 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 12:12:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:12:53 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:12:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C18893B5-2C4D-41CC-95E9-10E0D7CE28EC
[ThaliCore] Browser.startListening
2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 12:12:53 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-24 12:12:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.startListeningForAdver,tisements
2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 12:12:53 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActiv,e":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:12:53 - INFO thaliMobile: 'Filtered out discoveryA,d,vertisingStateUpdate (was in stopped state).'
ok 65 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24, 12:12:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-07-24 12:12:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:12:53 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:12:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:12:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:12:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 66 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:12:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingAct,ive":false}'
2017-07-24 12:12:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:12:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:12:54 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:12:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 12:12:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:12:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:12:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:12:54 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:12:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 12:12:54 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 12:12:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 12:12:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 12:12:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6DB3B962-2F49-4318-BB21-F03E1DD0C31D", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:6DB3B962-2F49-4318-BB21-F03E1DD0C31D
,2017-07-24 12:12:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:12:55 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:12:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:6DB3B962-2F49-4318-BB21-F03E1DD0C31D
2017-07-24 12:12:55 ,- DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:12:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Can call ,s,topAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:12:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:12:55 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:12:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 12:12:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:12:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:12:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:12:55 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:12:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:12:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:12:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:12:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:12:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "376B8886-B42B-4A02-B0EF-53DA938C7C60", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:376B8886-B42B-4A02-B0EF-53DA938C7C60
,2017-07-24 12:12:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:12:55 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:12:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 70 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "376B8886-B42B-4A02-B0EF-53DA938C7C60", generation: 1)
[,ThaliCore] Advertiser.startAdvertising with peerID:376B8886-B42B-4A02-B0EF-53DA938C7C60
2017-07-24 12:12:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:12:55, ,- INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTyp,e":null}})'
2017-07-24 12:12:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:12:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:12:56 - INFO thaliMobile: 'Receive,d state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:1,2:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:376B8886-B42B-4A02-B0EF-53DA938C7C60
[ThaliCore] Advertiser.s,topAdvertising() peerID:376B8886-B42B-4A02-B0EF-53DA938C7C60
2017-07-24 12:12:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:12:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 12:12:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:12:56 - DEBUG thaliMo,bileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:12:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:12:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:12:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:12:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:12:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-07-24 12:12:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:12:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:12:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 72 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:12:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:12:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Can call stopAdverti,singAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:12:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:12:56 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:12:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 12:12:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:12:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:12:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:12:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:12:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 12:12:56 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 12:12:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 12:12:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 12:12:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E4B9B596-003C-4812-A751-BA727FF36A55", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:E4B9B596-003C-4812-A751-BA727FF36A55
,2017-07-24 12:12:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:12:58 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:12:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DCACE8A7-84C5-4E5C-AF08-A51DDE20B,BDC
[ThaliCore] Browser.startListening
2017-07-24 12:12:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 12:12:58 - INFO thaliMobile: 'Received state ({"discovery,A,ctive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:12:58 - INFO thaliMobil,e: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9AC440CA-971E-4F78-BB2F-BC94E406C8C1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9AC440CA-971E-4F78-BB2F-BC94E406C8C1", generation: 0)
ok 76 peers must be an array,
ok 77 peers must not be zero-length
ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
ok 79 peerIdentifier must be a string
ok 80 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E4B9B596-003C-4812-A751-BA727FF36A55:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E4B9B596-003C-4812-A751-BA727FF36A55", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 12:12:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 ,12:12:59 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-24 12:12:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:E4B9B596-003C-4812-A751-B,A727FF36A55
2017-07-24 12:12:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:12:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
2017-07-24 12:12:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:12:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07,-24 12:12:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:12:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:12:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:12:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:12:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:12:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6E6B3997-56C8-4EBD-8540-DB22D429A7D1", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:6E6B3997-56C8-4EBD-8540-DB22D429A7D1
2017-07-24 1,2:13:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:13:04 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:13:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 81 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:5149F07E-0275-4E9E-AF1F-3A0611BA7CBA
[Thal,i,Core] Browser.startListening
2017-07-24 12:13:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 12:13:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:13:04 - INFO thaliMobile: 'Filtere,d out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7CD4A326-EA8C-4C7A-9109-4C3844A1A542:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7CD4A326-EA8C-4C7A-9109-4C3844A1A542", generation: 0)
2017-07-24 12:13:05 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"7CD4A326-EA8C-4C7A-9109-4C3844A1A542","generation":0}'
,2017-07-24 12:13:05 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 7CD4A326-EA8C-4C7A-9109-4C3844A1A542 (syncValue: hv1DgUVZELpxjtyGVuUkIgLBwckO8eJm)'
,2017-07-24 12:13:05 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7CD4A326-EA8C-4C7A-9109-4C3844A1A542", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7CD4A326-EA8C-4C7A-9109-4C3844A1A542", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7CD4A326-EA8C-4C7A-9109-4C3844A1A542:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0B72AB8C-48DE-4B01-8934-F06A26A55C20
[ThaliCore] Advertiser: session connected Peer(uuid: "6E6B3997-56C8-4EBD-8540-DB22D429A7D1", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:0B72AB8C-48DE-4B01-8934-F06A26A55C20 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:7CD4A326-EA8C-4C7A-9109-4C3844A1A542:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6E6B3997-56C8-4EBD-8540-DB22D429A7D1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6E6B3997-56C8-4EBD-8540-DB22D429A7D1", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:75DD76C5-36DA-429E-9B49-8B4F23A6900D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "75DD76C5-36DA-429E-9B49-8B4F23A6900D", generation: 0)
2017-07-24 12:13:05 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"75DD76C5-36DA-429E-9B49-8B4F23A6900D","generation":0}'
2017-07-24 12:13:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 12:13:05 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7CD4A326-EA8C-4C7A-9109-4C3844A1A542:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:7CD4A326-EA8C-4C7A-9109-4C3844A1A542:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "7CD4A326-EA8C-4C7A-9109-4C3844A1A542", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60168
2017-07-24 12:13:07 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"hv1DgUVZELpxjtyGVuUkIgLBwckO8eJm","error":null,"portNumber":60168}'
2017-07-24 12:13:07 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'hv1DgUVZELpxjtyGVuUkIgLBwckO8eJm', error: 'null', listeningPort: '60168''
,2017-07-24 12:13:07 - INFO testThaliMobileNative: ''
ok 83 Must have listeningPort
ok 84 listeningPort must be a number
ok 85 listening port should not be 0
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0B72AB8C-48DE-4B01-8934-F06A26A55C20
,[ThaliCore] Session.session(_:peer:didChange:) peer:0B72AB8C-48DE-4B01-8934-F06A26A55C20 state: connecting -> connected
,2017-07-24 12:13:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 12:13:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:13:08 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:13:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:6E6B3997-56C8-4EBD-8540-DB22D429A7D1
,2017-07-24 12:13:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:13:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.disconnect peer:7CD4A326-EA8C-4C7A-9109-4C3844A1A542
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:60168
[ThaliCore] Session.disconnect,() peer:7CD4A326-EA8C-4C7A-9109-4C3844A1A542:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:7CD4A326-EA8C-4C7A-9109-4C3844A1A542:0
[ThaliCore] BrowserRelay.deinit
,2017-07-24 12:13:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:13:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:13:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:13:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:13:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:13:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:13:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:13:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:0B72AB8C-48DE-4B01-8934-F06A26A55C20 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "6E6B3997-56C8-4EBD-8540-DB22D429A7D1", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
,[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:0B72AB8C-48DE-4B01-8934-F06A26A55C20
[ThaliCore] AdvertiserRelay.deinit
,# setup
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "21ED5147-420B-4877-B71D-3C4D9F498B8D", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:21ED5147-420B-4877-B71D-3C4D9F498B8D
2017-07-24 12:13:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:13:09, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-24 12:13:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Thal,iCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:991B4017-09A7-43E7-8D5A-F7E501EA632D
[ThaliCore] Browser.startListening
2017-07-24 12:13:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adver,tisingActive":true}'
2017-07-24 12:13:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"rout,er":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:13:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Session.deinit peer:0B72AB8C-48DE-4B01-8934-F06A26A55C20
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:75DD76C5-36DA-429E-9B49-8B4F23A6900D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "75DD76C5-36DA-429E-9B49-8B4F23A6900D", generation: 0)
2017-07-24 12:13:09 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"75DD76C5-36DA-429E-9B49-8B4F23A6900D","generation":0}'
2017-07-24 12:13:09 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 75DD76C5-36DA-429E-9B49-8B4F23A6900D, (syncValue: BE6SvtSsTpEbozlNRJx3Re7hkcYCTvZ9)'
2017-07-24 12:13:09 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "75DD76C5-36DA-429E-9B49-8B4F23A,6900D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "75DD76C5-36DA-429E-9B49-8B4F23A6900D", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:75DD76C5-36DA-429E-9B49-8B4F23A6900D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:870B7B74-771B-4859-AAB3-509F704123AD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "870B7B74-771B-4859-AAB3-509F704123AD", generation: 0)
2017-07-24 12:13:10 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"870B7B74-771B-4859-AAB3-509F704123AD","generation":0}'
2017-07-24 12:13:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 12:13:10 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0", generation: 0)
2017-07-24 12:13:10 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0","generation":0}'
2017-07-24 12:13:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 12:13:10 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-24 12:13:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:21ED5147-420B-4877-B71D-3C4D9F498B8D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "21ED5147-420B-4877-B71D-3C4D9F498B8D", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:75DD76C5-36DA-429E-9B49-8B4F23A6900D:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "75DD76C5-36DA-429E-9B49-8B4F23A6900D", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:75DD76C5-36DA-429E-9B49-8B4F23A6900D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:75,DD76C5-36DA-429E-9B49-8B4F23A6900D:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "75DD76C5-36DA-429E-9B49-8B4F23A6900D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,5DD76C5-36DA-429E-9B49-8B4F23A6900D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "75DD76C5-36DA-429E-9B49-8B4F23A6900D", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 12:13:12 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"BE6SvtSsTpEbozlNRJx3Re7hkcYCTvZ9","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 12:13:12 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'BE6SvtSsTpEbozlNRJx3Re7hkcYCTvZ9', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-24 12:13:12 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-24 12:13:12 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 870B7B74-771B-4859-AAB3-509F704123AD (syncValue: Eq5HL6UswR7EASHCP2Nz3p1,9PiuRMbWh)'
2017-07-24 12:13:12 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "870B7B74-771B-4859-AAB3-509F704123AD", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "870B7B74-771B-4859-AAB3-509F704123AD", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:870B7B74-771B-4859-AAB3-509F7,04123AD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-24 12:13:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:75DD76C5-36DA-429E-9B49-8B4F23A6900D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:870B7B74-771B-4859-AAB3-509F704123AD:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:870B7B74-771B-4859-AAB3-509F704123AD:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:870B7B74-771B-4859-AAB3-509F704123AD:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "870B7B74-771B-4859-AAB3-509F704123AD", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60174
2017-07-24 12:13:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Eq5HL6UswR7EASHCP2Nz3p19PiuRMbWh",,"error":null,"portNumber":60174}'
2017-07-24 12:13:15 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Eq5HL6UswR7EASHCP2Nz3p19PiuRMbWh', error: 'null', listeningPort: '60174''
,Connecting to the localhost:60174
,Connected to the localhost:60174
2017-07-24 12:13:15 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
2017-07-24 12:13:15 - DEBUG testThaliMobileNative: 'Client data flushed'
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCor,e] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:870B7B74-771B-4859-AAB3-509F704123AD:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:870B7B74-771B-4859-AAB3-509F704123AD:0
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
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:735DEB32-1B38-4817-8CCF-B343AF28D0D1
[ThaliCore] Advertiser: session connected Peer(uuid: "21ED5147-420B-4877-B71D-3C4D9F498B8D", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:735DEB32-1B38-4817-8CCF-B343AF28D0D1 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:735DEB32-1B38-4817-8CCF-B343AF28D0D1
,[ThaliCore] Session.session(_:peer:didChange:) peer:735DEB32-1B38-4817-8CCF-B343AF28D0D1 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:735DEB32-1B38-4817-8CCF-B343AF28D0D1
[ThaliCore] Session.startOutputStream(with:) peer:735DEB32-1B38-4817-8CCF-B343AF28D0D1
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2, [2]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-24 12:13:24 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-07-24 12:13:24 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-24 12:13:24 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-07-24 12:13:24 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:2
[ThaliCore] VirtualSocket.closeStreams() vsID:2
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-24 12:13:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 12:13:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:13:25 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 12:13:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:21ED5147-420B-4877-B71D-3C4D9F498B8D
2017-07-2,4 12:13:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:13:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:870B7B74-771B-4859-AAB3-509F704123AD
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:60174
[ThaliCore] Session.disconnect() p,eer:870B7B74-771B-4859-AAB3-509F704123AD:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:735DEB32-1B38-4817-8CCF-B343AF28D0D1 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "21ED5147-420B-4877-B71D-3C4D9F498B8D", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:735DEB32-1B38-4817-8CCF-B343AF28D0D1
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:870B7B74-771B-4859-AAB3-509F704123AD:0
[ThaliCore] BrowserRelay.deinit
,2017-07-24 12:13:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:13:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:13:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:13:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:13:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:13:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:13:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:13:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,[ThaliCore] Session.deinit peer:735DEB32-1B38-4817-8CCF-B343AF28D0D1
,# setup
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5D5997C9-1AFA-49E8-8859-3D3CF8615E09", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:5D5997C9-1AFA-49E8-8859-3D3CF8615E09
2017-07-24 12:13:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:13:25, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-24 12:13:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 89 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Thal,iCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:27D1361A-E08C-4C40-9A05-F4BF7A98811D
[ThaliCore] Browser.startListening
2017-07-24 12:13:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adve,r,tisingActive":true}'
2017-07-24 12:13:25 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"rout,er":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:13:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:870B7B74-771B-4859-AAB3-509F704123AD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "870B7B74-771B-4859-AAB3-509F704123AD", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0", generation: 0)
2017-07-24 12:13:26 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"870B7B74-771B-4859-AAB3-509F704123AD","generation":0}'
,2017-07-24 12:13:26 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 870B7B74-771B-4859-AAB3-509F704123AD (syncValue: JQ4deZLarcqKSe4qfz4Y9DvRQirvSapj)'
,2017-07-24 12:13:26 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "870B7B74-771B-4859-AAB3-509F704123AD", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "870B7B74-771B-4859-AAB3-509F704123AD", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:870B7B74-771B-4859-AAB3-509F704123AD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-07-24 12:13:26 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0","generation":0}'
2017-07-24 12:13:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!',
,2017-07-24 12:13:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6C05AD67-A1F8-454C-9056-1AD3142D948D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6C05AD67-A1F8-454C-9056-1AD3142D948D", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5D5997C9-1AFA-49E8-8859-3D3CF8615E09:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5D5997C9-1AFA-49E8-8859-3D3CF8615E09", generation: 0)
,2017-07-24 12:13:27 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6C05AD67-A1F8-454C-9056-1AD3142D948D","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:65639090-B4AF-4DEF,-914A-52E21168A9FB:0
2017-07-24 12:13:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "65639090-B4AF-4DEF-914A-52E21168A9FB", generation: 0)
2017-07-24 12:13:27 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,2017-07-24 12:13:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:13:27 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"65639090-B4AF-4DEF-914A-52E21168A9FB","generation":0}'
2017-07-24 12:13:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 12:13:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:13:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 12:13:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:870B7B74-771B-4859-AAB3-509F704123AD:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:87,0B7B74-771B-4859-AAB3-509F704123AD:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "870B7B74-771B-4859-AAB3-509F704123AD", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,70B7B74-771B-4859-AAB3-509F704123AD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "870B7B74-771B-4859-AAB3-509F704123AD", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:870B7B74-771B-4859-AAB3-509F704123AD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:870B7B74-771B-4859-AAB3-509F704123AD:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:870B7B74-771B-4859-AAB3-509F704123AD:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:87,0B7B74-771B-4859-AAB3-509F704123AD:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "870B7B74-771B-4859-AAB3-509F704123AD", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,70B7B74-771B-4859-AAB3-509F704123AD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "870B7B74-771B-4859-AAB3-509F704123AD", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:870B7B74-771B-4859-AAB3-509F704123AD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:870B7B74-771B-4859-AAB3-509F704123AD:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:870B7B74-771B-4859-AAB3-509F704123AD:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:87,0B7B74-771B-4859-AAB3-509F704123AD:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "870B7B74-771B-4859-AAB3-509F704123AD", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,70B7B74-771B-4859-AAB3-509F704123AD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "870B7B74-771B-4859-AAB3-509F704123AD", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:870B7B74-771B-4859-AAB3-509F704123AD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:870B7B74-771B-4859-AAB3-509F704123AD:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:870B7B74-771B-4859-AAB3-509F704123AD:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "870B7B74-771B-4859-AAB3-509F704123AD", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:870B7B74-771B-4859-AAB3-509F704123AD:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:87,0B7B74-771B-4859-AAB3-509F704123AD:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "870B7B74-771B-4859-AAB3-509F704123AD", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:870B7B74,-771B-4859-AAB3-509F704123AD error: max retries exceeded
2017-07-24 12:13:37 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"JQ4deZLarcqKSe4qfz4Y9DvRQirvSapj","error":"Connection could not be established","portNumber":null}'
2017-0,7-24 12:13:37 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'JQ4deZLarcqKSe4qfz4Y9DvRQirvSapj', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-24 12:13:37 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-24 12:13:37 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0 (syncValue: WYpv54V,PrhVnw2sI5sJ29ctVVjEuiwfG)'
2017-07-24 12:13:37 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C59D3ABD-41F1,-42F9-B7F0-88F33F9AD8F0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-24 12:13:37 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
,2017-07-24 12:13:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:13:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:870B7B74-771B-4859-AAB3-509F704123AD:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C5,9D3ABD-41F1-42F9-B7F0-88F33F9AD8F0:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C5,9D3ABD-41F1-42F9-B7F0-88F33F9AD8F0:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C5,9D3ABD-41F1-42F9-B7F0-88F33F9AD8F0:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C5,9D3ABD-41F1-42F9-B7F0-88F33F9AD8F0:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:C59D3ABD,-41F1-42F9-B7F0-88F33F9AD8F0 error: max retries exceeded
2017-07-24 12:13:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"WYpv54VPrhVnw2sI5sJ29ctVVjEuiwfG","error":"Connection could not be established","portNumber":null}'
2017-0,7-24 12:13:48 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'WYpv54VPrhVnw2sI5sJ29ctVVjEuiwfG', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-24 12:13:48 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-24 12:13:48 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 6C05AD67-A1F8-454C-9056-1AD3142D948D (syncValue: 2K7fJT2,pwiBCfhWtrurw9rifAL83KuBa)'
2017-07-24 12:13:48 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6C05AD67-A1F8-454C-9056-1AD3142D948D", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6C05AD67-A1F8-454C-9056-1AD3142D948D", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6C05AD67-A1F8,-454C-9056-1AD3142D948D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-24 12:13:48 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-07-24 12:13:48 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 12:13:48 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:6C05AD67-A1F8-454C-9056-1AD3142D948D:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6C05AD67-A1F8-454C-9056-1AD3142D948D:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:6C05AD67-A1F8-454C-9056-1AD3142D948D:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "6C05AD67-A1F8-454C-9056-1AD3142D948D", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60199
2017-07-24 12:13:51 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2K7fJT2pwiBCfhWtrurw9rifAL83KuBa",,"error":null,"portNumber":60199}'
2017-07-24 12:13:51 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '2K7fJT2pwiBCfhWtrurw9rifAL83KuBa', error: 'null', listeningPort: '60199''
,Connecting to the localhost:60199
Connecting to the localhost:60199
Connecting to the localhost:60199
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:,) peer:6C05AD67-A1F8-454C-9056-1AD3142D948D:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:6C05AD67-A1F8-454C-9056-1AD3142D948D:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:6C05AD67-A1F8-454C-9056-1AD3142D948D:0
,Connected to the localhost:60199
Connected to the localhost:60199
Connected to the localhost:60199
,ok 91 correct string length
,2017-07-24 12:13:51 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 92 correct string length
,2017-07-24 12:13:51 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6C05AD67-A1F8-454C-9056-1AD3142D948D:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [2, 3]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 93 correct string length
,2017-07-24 12:13:51 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-24 12:13:51 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-24 12:13:51 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-24 12:13:51 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6C05AD67-A1F8-454C-9056-1AD3142D948D:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [2, 3, 4]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6C05AD67-A1F8-454C-9056-1AD3142D948D:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [2, 3, 4, 5]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 94 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams,() vsID:3
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,ok 95 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vs,ID:4
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:4
,[ThaliCore] VirtualSocket.deinit vsID:4 [2, 3, 5]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:5
ok 96 got the same ,data back
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:5
[ThaliCore] VirtualSocket.deinit vsID:5 [2, 3]
,# teardown
,2017-07-24 12:13:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 12:13:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:13:53 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:13:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:5D5997C9-1AFA-49E8-8859-3D3CF8615E09
,2017-07-24 12:13:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:13:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.disconnect peer:6C05AD67-A1F8-454C-9056-1AD3142D948D
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:60199
[ThaliCore] Session.disconnect,() peer:6C05AD67-A1F8-454C-9056-1AD3142D948D:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:6C05AD67-A1F8-454C-9056-1AD3142D948D:0
,2017-07-24 12:13:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:13:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:13:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:13:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:13:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:13:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:13:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:13:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FCE18425-0E52-4D6C-8613-24BC52DDA992", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:FCE18425-0E52-4D6C-8613-24BC52DDA992
,2017-07-24 12:13:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:13:54 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:13:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 97 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9AD19499-5E01-459B-843B-D0E4154BBA37
[ThaliCore] Browser.startListening
,2017-07-24 12:13:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 12:13:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-24 12:13:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6C05AD67-A1F8-454C-9056-1AD3142D948D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6C05AD67-A1F8-454C-9056-1AD3142D948D", generation: 0)
2017-07-24 12:13:54 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6C05AD67-A1F8-454C-9056-1AD3142D948D","generation":0}'
2017-07-24 12:13:54 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 6C05AD67-A1F8-454C-9056-1AD3142D948D, (syncValue: BfzcAzTrUFDGImU8C6mtOHgH1gTJ8KQB)'
2017-07-24 12:13:54 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6C05AD67-A1F8-454C-9056-1AD3142,D948D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6C05AD67-A1F8-454C-9056-1AD3142D948D", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:6C05AD67-A1F8-454C-9056-1AD3142D948D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:53598C96-6AC0-493D-B665-40226186CD36:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "53598C96-6AC0-493D-B665-40226186CD36", generation: 0)
2017-07-24 12:13:55 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"53598C96-6AC0-493D-B665-40226186CD36","generation":0}'
2017-07-24 12:13:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 12:13:55 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D00BC9A6-5676-4EAE-B32C-0930BC0FF439:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D00BC9A6-5676-4EAE-B32C-0930BC0FF439", generation: 0)
,2017-07-24 12:13:55 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D00BC9A6-5676-4EAE-B32C-0930BC0FF439","generation":0}'
,2017-07-24 12:13:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:13:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:13:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FCE18425-0E52-4D6C-8613-24BC52DDA992:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FCE18425-0E52-4D6C-8613-24BC52DDA992", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:6C05AD67-A1F8-454C-9056-1AD3142D948D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:6C,05AD67-A1F8-454C-9056-1AD3142D948D:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "6C05AD67-A1F8-454C-9056-1AD3142D948D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,C05AD67-A1F8-454C-9056-1AD3142D948D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6C05AD67-A1F8-454C-9056-1AD3142D948D", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:6C05AD67-A1F8-454C-9056-1AD3142D948D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:6C05AD67-A1F8-454C-9056-1AD3142D948D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:6C05AD67-A1F8-454C-9056-1AD3142D948D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:6C,05AD67-A1F8-454C-9056-1AD3142D948D:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "6C05AD67-A1F8-454C-9056-1AD3142D948D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,C05AD67-A1F8-454C-9056-1AD3142D948D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6C05AD67-A1F8-454C-9056-1AD3142D948D", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:6C05AD67-A1F8-454C-9056-1AD3142D948D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:6C05AD67-A1F8-454C-9056-1AD3142D948D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:6C05AD67-A1F8-454C-9056-1AD3142D948D:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "6C05AD67-A1F8-454C-9056-1AD3142D948D", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:6C05AD67-A1F8-454C-9056-1AD3142D948D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:6C,05AD67-A1F8-454C-9056-1AD3142D948D:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "6C05AD67-A1F8-454C-9056-1AD3142D948D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,C05AD67-A1F8-454C-9056-1AD3142D948D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6C05AD67-A1F8-454C-9056-1AD3142D948D", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 12:14:03 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"BfzcAzTrUFDGImU8C6mtOHgH1gTJ8KQB","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 12:14:03 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'BfzcAzTrUFDGImU8C6mtOHgH1gTJ8KQB', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-24 12:14:03 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-24 12:14:03 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 53598C96-6AC0-493D-B665-40226186CD36 (syncValue: 1ch2tEmjVDUNhlC6rqWR1F3,vo8PuUxXZ)'
2017-07-24 12:14:03 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "53598C96-6AC0-493D-B665-40226186CD36", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "53598C96-6AC0-493D-B665-40226186CD36", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:53598C96-6AC0-493D-B665-40226,186CD36:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-24 12:14:03 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:6C05AD67-A1F8-454C-9056-1AD3142D948D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:53598C96-6AC0-493D-B665-40226186CD36:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:53598C96-6AC0-493D-B665-40226186CD36:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:53598C96-6AC0-493D-B665-40226186CD36:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "53598C96-6AC0-493D-B665-40226186CD36", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60215
,2017-07-24 12:14:06 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1ch2tEmjVDUNhlC6rqWR1F3vo8PuUxXZ","error":null,"portNumber":60215}'
,2017-07-24 12:14:06 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '1ch2tEmjVDUNhlC6rqWR1F3vo8PuUxXZ', error: 'null', listeningPort: '60215''
,Connecting to the localhost:60215
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:53598C96-6AC0-493D-B665-40226186CD36:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:53598C96-6AC0-493D-B665-40226186CD36:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [2, 3, 6]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:60215
,2017-07-24 12:14:06 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-24 12:14:06 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:6
[ThaliCore] VirtualSocket.closeStreams() vsID:6
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,ok 99 got the same data back
,# teardown
,2017-07-24 12:14:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 12:14:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:14:12 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:14:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:FCE18425-0E52-4D6C-8613-24BC52DDA992
,2017-07-24 12:14:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:14:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.disconnect peer:53598C96-6AC0-493D-B665-40226186CD36
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:60215
[ThaliCore] Session.disconnect,() peer:53598C96-6AC0-493D-B665-40226186CD36:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:53598C96-6AC0-493D-B665-40226186CD36:0
,2017-07-24 12:14:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:14:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:14:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:14:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:14:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:14:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:14:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:14:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8182CC2F-9EF8-4D77-B70E-B56490A7A0EF", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:8182CC2F-9EF8-4D77-B70E-B56490A7A0EF
,2017-07-24 12:14:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:14:13 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:14:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 100 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:0F68199C-9850-4C75-B33B-6C8AD890D704
[ThaliCore] Browser.startList,ening
,2017-07-24 12:14:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 12:14:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-24 12:14:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:53598C96-6AC0-493D-B665-40226186CD36:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "53598C96-6AC0-493D-B665-40226186CD36", generation: 0)
2017-07-24 12:14:13 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"53598C96-6AC0-493D-B665-40226186CD36","generation":0}'
2017-07-24 12:14:13 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 53598C96-6AC0-493D-B665-40226186CD36, (syncValue: L4c2Xb828yzDX1s99EUKxogDdDePnUiv)'
2017-07-24 12:14:13 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "53598C96-6AC0-493D-B665-4022618,6CD36", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "53598C96-6AC0-493D-B665-40226186CD36", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:53598C96-6AC0-493D-B665-40226186CD36:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8182CC2F-9EF8-4D77-B70E-B56490A7A0EF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8182CC2F-9EF8-4D77-B70E-B56490A7A0EF", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B315A267-2416-4D99-838E-75A6F373469D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B315A267-2416-4D99-838E-75A6F373469D", generation: 0)
2017-07-24 12:14:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B315A267-2416-4D99-838E-75A6F373469D","generation":0}'
2017-07-24 12:14:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 12:14:14 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:453E9D44-4CC9-41AA-81C6-484AB3F7CC29:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "453E9D44-4CC9-41AA-81C6-484AB3F7CC29", generation: 0)
2017-07-24 12:14:15 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"453E9D44-4CC9-41AA-81C6-484AB3F7CC29","generation":0}'
2017-07-24 12:14:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 12:14:15 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-24 12:14:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:53598C96-6AC0-493D-B665-40226186CD36:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:53,598C96-6AC0-493D-B665-40226186CD36:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "53598C96-6AC0-493D-B665-40226186CD36", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,3598C96-6AC0-493D-B665-40226186CD36", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "53598C96-6AC0-493D-B665-40226186CD36", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:53598C96-6AC0-493D-B665-40226186CD36:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:53598C96-6AC0-493D-B665-40226186CD36:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:53598C96-6AC0-493D-B665-40226186CD36:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:53598C96-6AC0-493D-B665-40226186CD36:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "53598C96-6AC0-493D-B665-40226186CD36", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,3598C96-6AC0-493D-B665-40226186CD36", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "53598C96-6AC0-493D-B665-40226186CD36", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:53598C96-6AC0-493D-B665-40226186CD36:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:53598C96-6AC0-493D-B665-40226186CD36:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:53598C96-6AC0-493D-B665-40226186CD36:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "53598C96-6AC0-493D-B665-40226186CD36", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:53598C96-6AC0-493D-B665-40226186CD36:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:53,598C96-6AC0-493D-B665-40226186CD36:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "53598C96-6AC0-493D-B665-40226186CD36", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,3598C96-6AC0-493D-B665-40226186CD36", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "53598C96-6AC0-493D-B665-40226186CD36", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 12:14:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"L4c2Xb828yzDX1s99EUKxogDdDePnUiv","error":"Peer is unavailable","portNumber":null}'
2017-07-24 12:14:22 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'L4c2Xb828yzDX1s99EUKxogDdDePnUiv', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-24 12:14:22 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-24 12:14:22 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B315A267-2416-4D99-838E-75A6F373469D (syncValue: 3i3q7ilvqGq7jxQqp4vLg8K,sn4Z00tBe)'
2017-07-24 12:14:22 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B315A267-2416-4D99-838E-75A6F373469D", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B315A267-2416-4D99-838E-75A6F373469D", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B315A267-2416-4D99-838E-75A6F,373469D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-24 12:14:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:53598C96-6AC0-493D-B665-40226186CD36:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B315A267-2416-4D99-838E-75A6F373469D:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9AE183A7-A964-45CF-B0A2-3F949DC986C2
[ThaliCore] Advertiser: session connected Peer(uuid: "8182CC2F-9EF8-4D77-B70E-B56490A7A0EF", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:9AE183A7-A964-45CF-B0A2-3F949DC986C2 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B315A267-2416-4D99-838E-75A6F373469D:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B315A267-2416-4D99-838E-75A6F373469D:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "B315A267-2416-4D99-838E-75A6F373469D", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60229
2017-07-24 12:14:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3i3q7ilvqGq7jxQqp4vLg8Ksn4Z00tBe",,"error":null,"portNumber":60229}'
2017-07-24 12:14:26 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '3i3q7ilvqGq7jxQqp4vLg8Ksn4Z00tBe', error: 'null', listeningPort: '60229''
Connecting to the localhost:60229
[ThaliCore] TCPL,istener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B315A267-2416-4D99-838E-75A6F373469D:0
Connected to the localhost:60229
2017-07-24 12:14:26 - DEBUG testThaliMo,b,ileNative: 'Client sends data (65536 bytes):'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B315A267-2416-4D99-838E-75A6F373469D:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [2, 3, 6, 7]
,2017-07-24 12:14:26 - DEBUG testThaliMobileNative: 'Client data flushed'
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
ok 102 got the same data back
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStream,s() vsID:7
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:7
[ThaliCore] VirtualSocket.deinit vsID:7 [2, 3, 6]
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9AE183A7-A964-45CF-B0A2-3F949DC986C2
,[ThaliCore] Session.session(_:peer:didChange:) peer:9AE183A7-A964-45CF-B0A2-3F949DC986C2 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9AE183A7-A964-45CF-B0A2-3F949DC986C2
[ThaliCore] Session.startOutputStream(with:) peer:9AE183A7-A964-45CF-B0A2-3F949DC986C2
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8, [2, 3, 6, 8]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-24 12:14:29 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
2017-07-24 12:14:29 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
2017-07-24 12:14:29 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
2017,-07-24 12:14:29 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
2017-07-24 12:14:29 - DEBUG testThaliMobileNative: 'Server received (5475 bytes):'
2017-07-24 12:14:29 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 12:14:29 - DEBUG testThaliMobileNative: 'Server received (2048 bytes):'
,2017-07-24 12:14:29 - DEBUG testThaliMobileNative: 'Server received (5617 bytes):'
,2017-07-24 12:14:29 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-24 12:14:29 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-24 12:14:29 - DEBUG testThaliMobileNative: 'Server received (6570 bytes):'
,2017-07-24 12:14:29 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-24 12:14:29 - DEBUG testThaliMobileNative: 'Server received (2119 bytes):'
,2017-07-24 12:14:29 - DEBUG testThaliMobileNative: 'Server received (3356 bytes):'
,2017-07-24 12:14:29 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-24 12:14:29 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-24 12:14:29 - DEBUG testThaliMobileNative: 'Server received (9691 bytes):'
,2017-07-24 12:14:29 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-24 12:14:29 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-24 12:14:29 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:8
[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:8
[ThaliCore] VirtualSocket.deinit vsID:8 [2, 3, 6]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:737E56A2-2A45-4574-AF5C-F65E503621CA
[ThaliCore] Advertiser: session connected Peer(uuid: "8182CC2F-9EF8-4D77-B70E-B56490A7A0EF", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:737E56A2-2A45-4574-AF5C-F65E503621CA state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:737E56A2-2A45-4574-AF5C-F65E503621CA
,[ThaliCore] Session.session(_:peer:didChange:) peer:737E56A2-2A45-4574-AF5C-F65E503621CA state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:737E56A2-2A45-4574-AF5C-F65E503621CA
[ThaliCore] Session.startOutputStream(with:) peer:737E56A2-2A45-4574-AF5C-F65E503621CA
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [2, 3, 6, 9]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-24 12:14:36 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 12:14:36 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-24 12:14:36 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-24 12:14:36 - DEBUG testThaliMobileNative: 'Server received (3072 bytes):'
,2017-07-24 12:14:36 - DEBUG testThaliMobileNative: 'Server received (284 bytes):'
,2017-07-24 12:14:36 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-24 12:14:36 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-24 12:14:36 - DEBUG testThaliMobileNative: 'Server received (142 bytes):'
,2017-07-24 12:14:36 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-24 12:14:36 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 12:14:36 - DEBUG testThaliMobileNative: 'Server received (5546 bytes):'
,2017-07-24 12:14:36 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-24 12:14:36 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-24 12:14:36 - DEBUG testThaliMobileNative: 'Server received (1166 bytes):'
,2017-07-24 12:14:36 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-24 12:14:36 - DEBUG testThaliMobileNative: 'Server received (7594 bytes):'
,2017-07-24 12:14:36 - DEBUG testThaliMobileNative: 'Server received (10950 bytes):'
,2017-07-24 12:14:36 - DEBUG testThaliMobileNative: 'Server received (13282 bytes):'
,2017-07-24 12:14:36 - DEBUG testThaliMobileNative: 'Server received (7501 bytes):'
,2017-07-24 12:14:36 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-24 12:14:36 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-24 12:14:36 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:9
[ThaliCore] VirtualSocket.closeStreams() vsID:9
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:9
,[ThaliCore] VirtualSocket.deinit vsID:9 [2, 3, 6]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:737E56A2-2A45-4574-AF5C-F65E503621CA state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "8182CC2F-9EF8-4D77-B70E-B56490A7A0EF", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:737E56A2-2A45-4574-AF5C-F65E503621CA
,[ThaliCore] Session.session(_:peer:didChange:) peer:9AE183A7-A964-45CF-B0A2-3F949DC986C2 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "8182CC2F-9EF8-4D77-B70E-B56490A7A0EF", generation: 0)
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:737E56A2-2A45-4574-AF5C-F65E503621CA
,2017-07-24 12:14:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 12:14:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-24 12:14:37 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-24 12:14:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:8182CC2F-9EF8-4D77-B70E-B56490A7A0EF
,2017-07-24 12:14:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:14:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:B315A267-2416-4D99-838E-75A6F373469D
[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:60229
,[ThaliCore] Session.disconnect() peer:B315A267-2416-4D99-838E-75A6F373469D:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B315A267-2416-4D99-838E-75A6F373469D:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "B315A267-2416-4D99-838E-75A6F373469D", generation: 0)
,2017-07-24 12:14:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:14:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:14:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:14:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:14:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:14:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:14:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:14:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-24 12:14:37 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3i3q7ilvqGq7jxQqp4vLg8Ksn4Z00tBe","error":"Session disconnected","portNumber":null}'
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] Session.deinit peer:B315A267-2416-4D99-838E-75A6F373469D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "684CBCC0-3066-4B00-81CD-27930DF3952A", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:684CBCC0-3066-4B00-81CD-27930DF3952A
2017-07-24 1,2:14:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:14:39 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:14:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 103 Ready to advertise
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B32C077D-1F64-43B6-8E7A-1E3DE35C0CB6
[ThaliCore] Browser.startListening
2017-07,-,24 12:14:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 12:14:39 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 12:14:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 104 Ready to listen
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:62A427F4-39CB-44D6-8DAF-F8C47295B57B:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "62A427F4-39CB-44D6-8DAF-F8C47295B57B", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D63D92FE-3772-48E1-B182-B4E7084DA19C:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D63D92FE-3772-48E1-B182-B4E7084DA19C", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B315A267-2416-4D99-838E-75A6F373469D:0
[ThaliCore] BrowserManager.fo,undPeerHandler peer:Peer(uuid: "B315A267-2416-4D99-838E-75A6F373469D", generation: 0)
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:684CBCC0-3066-4B00-81CD-27930DF3952A
2017-07-24 12:14:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 12:14:40 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:14:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 105 stop ads worked
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 12:14:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:14:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 106 test stop worked
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:14:43 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 12:14:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:14:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Test updating advertising and parallel data transfer
,2017-07-24 12:14:43 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:14:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:14:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:14:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A8C8C1F6-B181-4AF6-93AB-D10549D562E5
,[ThaliCore] Browser.startListening
,ok 107 discoveryActive should be false
,ok 108 advertisingActive should be true
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "89677820-3AFE-4464-BFDC-8342518F383D", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:89677820-3AFE-4464-BFDC-8342518F383D
,ok 109 discoveryActive should be false
,ok 110 advertisingActive should be true
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,ok 111 discoveryActive should be false
,ok 112 advertisingActive should be true
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:89677820-3AFE-4464-BFDC-8342518F383D
,ok 113 discoveryActive should be false
,ok 114 advertisingActive should be true
,ok 115 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:14:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-07-24 12:14:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:14:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:14:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 116 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:14:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:14:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 117 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-24 12:14:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:14:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:14:44 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 118 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:14:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:14:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 119 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-24 12:14:44 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:14:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:14:45 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:14:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:14:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-24 12:14:45 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:14:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:14:45 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 122 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:14:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:14:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 123 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-24 12:14:45 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:14:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:14:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 124 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:14:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:14:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 125 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-24 12:14:46 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:14:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:14:46 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 126 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:14:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:14:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 127 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 128 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:5aeb229b-168b-480a-805e-2f5f8fae7092 error: startListeningNotActive
,2017-07-24 12:14:46 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"IUnC4nJdeF5p5etCzhyjltS1YfvDtpaQ","error":"startListeningForAdvertisements is not active","portNumber":null}'
ok 129 Should only get called after multiConnect retur,ned
ok 130 SyncValue matches
ok 131 Got right error
ok 132 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:14:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:14:46 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:14:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 12:14:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:14:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:14:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:14:46 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:14:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 12:14:46 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 12:14:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 12:14:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 12:14:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:30931112-7699-4939-8EC2-847BCB43A792
[ThaliCore] Browser.startListening
,2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 12:14:47 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:14:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 133 No error on starting
ok 134 Got null as expected
2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ydrUIMg8dYNk5UkzlSjByhWBeXcIXyLL","error":"Illegal peerID","portNumber",:null}'
ok 135 Should only get called after multiConnect returned
ok 136 SyncValue matches
ok 137 Got right error
ok 138 listeningPort is null
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B315A267-2416-4D99-838E-75A6F373469D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B315A267-2416-4D99-838E-75A6F373469D", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:453E9D44-4CC9-41AA-81C6-484AB3F7CC29:0
2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdent,ifier":"B315A267-2416-4D99-838E-75A6F373469D","generation":0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "453E9D44-4CC9-41AA-81C6-484AB3F7CC29", generation: 0)
2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"B315A267-2416-4D99-838E-75A6F373469D","generation":0}'
2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"453E9D44-4CC9-41AA-81C6-484AB3F7CC29","generation":0}]'
2017-07-24 12:14:47 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"453E9D44-4CC9-41AA-81C6-484AB3F7CC29","generation":0}'
,2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24, 12:14:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-07-24 12:14:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 12:14:47 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# multiConnect properly fails on legal but non-existent peerID
,2017-07-24 12:14:47 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:14:47 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 12:14:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 12:14:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
,2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D8055946-E67F-4149-B097-30F20BEE68D9
[ThaliCore] Browser.startListening
2017-07-24 12:14:48 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 12:14:48 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-24 12:14:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 139 No error on starting
ok 140 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-24 12:14:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:14:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:14:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:14:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:14:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:14:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:14:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:14:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:14:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:14:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:14:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:14:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call disconnect with invalid peer id
,ok 141 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:14:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:14:48 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:14:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 12:14:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:14:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:14:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:14:48 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:14:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 12:14:48 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 12:14:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 12:14:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 12:14:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:3d12770a-428c-4434-a04e-69c8944e8ddb
ok 142 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:14:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:14:48 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:14:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 12:14:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:14:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:14:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:14:49 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:14:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 12:14:49 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 12:14:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 12:14:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 12:14:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "782C8DC0-393C-431F-B729-125C1A096E99", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:782C8DC0-393C-431F-B729-125C1A096E99
2017-07-24 1,2:14:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:14:49 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:14:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 143 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:AFE4AF79-A6E3-437E-9F0F-E3EE269535CF
[Tha,l,iCore] Browser.startListening
2017-07-24 12:14:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 12:14:49 - INFO thaliMobile: 'Received state ({"discoveryActive":tru,e,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:14:49 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 144 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B315A267-2416-4D99-838E-75A6F373469D:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B315A267-2416-4D99-838E-75A6F373469D", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:453E9D44-4CC9-41AA-81C6-484AB3F7CC29:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "453E9D44-4CC9-41AA-81C6-484AB3F7CC29", generation: 0)
2017-07-24 12:14:49 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B315A267-2416-4D99-838E-75A6F373469D","generation":0}'
,2017-07-24 12:14:49 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B315A267-2416-4D99-838E-75A6F373469D (syncValue: Q9WwNK6zTCzZGicr2PDJwfjTitUmiPHV)'
,2017-07-24 12:14:49 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B315A267-2416-4D99-838E-75A6F373469D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B3,15A267-2416-4D99-838E-75A6F373469D", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B315A267-2416-4D99-838E-75A6F373469D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 12:14:49 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"453E9D44-4CC9-41AA-81C6-484AB3F7CC29","generation":0}'
2017-07-24 12:14:49 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 12:14:49 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B11581D3-CDC4-4C93-A560-BD4A6375972C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B11581D3-CDC4-4C93-A560-BD4A6375972C", generation: 0)
2017-07-24 12:14:50 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B11581D3-CDC4-4C93-A560-BD4A6375972C","generation":0}'
2017-07-24 12:14:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 12:14:50 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-24 12:14:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:782C8DC0-393C-431F-B729-125C1A096E99:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "782C8DC0-393C-431F-B729-125C1A096E99", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8E62C46C-7157-4AC0-8447-5248FCCDBD3C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8E62C46C-7157-4AC0-8447-5248FCCDBD3C", generation: 0)
2017-07-24 12:14:50 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8E62C46C-7157-4AC0-8447-5248FCCDBD3C","generation":0}'
2017-07-24 12:14:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 12:14:50 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-24 12:14:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 12:14:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:B315A267-2416-4D99-838E-75A6F373469D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B3,15A267-2416-4D99-838E-75A6F373469D:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "B315A267-2416-4D99-838E-75A6F373469D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,315A267-2416-4D99-838E-75A6F373469D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B315A267-2416-4D99-838E-75A6F373469D", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B315A267-2416-4D99-838E-75A6F373469D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B315A267-2416-4D99-838E-75A6F373469D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:453E9D44-4CC9-41AA-81C6-484AB3F7CC29:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "453E9D44-4CC9-41AA-81C6-484AB3F7CC29", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B315A267-2416-4D99-838E-75A6F373469D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B3,15A267-2416-4D99-838E-75A6F373469D:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "B315A267-2416-4D99-838E-75A6F373469D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,315A267-2416-4D99-838E-75A6F373469D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B315A267-2416-4D99-838E-75A6F373469D", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B315A267-2416-4D99-838E-75A6F373469D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B315A267-2416-4D99-838E-75A6F373469D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B315A267-2416-4D99-838E-75A6F373469D:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B315A267-2416-4D99-838E-75A6F373469D", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B315A267-2416-4D99-838E-75A6F373469D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B3,15A267-2416-4D99-838E-75A6F373469D:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "B315A267-2416-4D99-838E-75A6F373469D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,315A267-2416-4D99-838E-75A6F373469D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B315A267-2416-4D99-838E-75A6F373469D", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 12:14:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Q9WwNK6zTCzZGicr2PDJwfjTitUmiPHV","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 12:14:57 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Q9WwNK6zTCzZGicr2PDJwfjTitUmiPHV', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-24 12:14:57 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-24 12:14:57 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B11581D3-CDC4-4C93-A560-BD4A6375972C (syncValue: CcZkmSrYcrFZ4WfVTvNDF1J,KWE7FxHBd)'
2017-07-24 12:14:57 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B11581D3-CDC4-4C93-A560-BD4A6375972C", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B11581D3-CDC4-4C93-A560-BD4A6375972C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B11581D3-CDC4-4C93-A560-BD4A6,375972C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-24 12:14:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:B315A267-2416-4D99-838E-75A6F373469D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B11581D3-CDC4-4C93-A560-BD4A6375972C:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:453E9D44-4CC9-41AA-81C6-484AB3F7CC29:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "453E9D44-4CC9-41AA-81C6-484AB3F7CC29", generation: 0)
2017-07-24 12:14:58 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"453E9D44-4CC9-41AA-81C6-484AB3F7CC29","generation":0}'
2017-07-24 12:14:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 12:14:58 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-24 12:14:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B11581D3-CDC4-4C93-A560-BD4A6375972C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B11581D3-CDC4-4C93-A560-BD4A6375972C:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "B11581D3-CDC4-4C93-A560-BD4A6375972C", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60245
,2017-07-24 12:15:00 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"CcZkmSrYcrFZ4WfVTvNDF1JKWE7FxHBd","error":null,"portNumber":60245}'
,2017-07-24 12:15:00 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'CcZkmSrYcrFZ4WfVTvNDF1JKWE7FxHBd', error: 'null', listeningPort: '60245''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B11581D3-CDC4-4C93-A560-BD4A6375972C:0
,ok 145 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B11581D3-CDC4-4C93-A560-BD4A6375972C", generation: 0) found active relay
,2017-07-24 12:15:00 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Djc7rbrpu2SYonEQtD1IsBvPsOZTcx1v","error":null,"portNumber":60245}'
,ok 146 No error
,ok 147 Ports equal
,ok 148 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B11581D3-CDC4-4C93-A560-BD4A6375972C", generation: 0) found active relay
,2017-07-24 12:15:00 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"C8YmAM55NHaFJByIVC1LF9llGxzTva8I","error":null,"portNumber":60245}'
,ok 149 No error
,ok 150 Ports equal
,# teardown
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B11581D3-CDC4-4C93-A560-BD4A6375972C:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [2, 3, 6, 10]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:B11581D3-CDC4-4C93-A560-BD4A6375972C:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() po,rt:60245
[ThaliCore] VirtualSocket.closeStreams() vsID:10
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket exited RunLoop vsID:10
[ThaliCore] Session.disconnect() peer:B11581D3-CDC4-4C93-A560-BD4A6375972C:0
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "B11581D3-CDC4-4C93-A560-BD4A6375972C", generation: 0)
[ThaliCore] VirtualSocket.closeStreams() vsID:10
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconne,cting
[ThaliCore] VirtualSocket.deinit vsID:10 [2, 3, 6]
[ThaliCore] TCPListener.deinit
,2017-07-24 12:15:01 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"CcZkmSrYcrFZ4WfVTvNDF1JKWE7FxHBd","error":"Session disconnected","portNumber":null}'
,2017-07-24 12:15:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 12:15:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:15:02 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:15:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:782C8DC0-393C-431F-B729-125C1A096E99
2017-07-24 12:15:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"a,dvertisingActive":false}'
2017-07-24 12:15:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:B11581D3-CDC4-4C93-A560-BD4A6375972C
2017-07-24 12:15:02 - DEBUG thaliMob,ileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:15:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:15:02 - DEBUG thaliMobileNativeWrapper: 'Metho,d multiConnectResolved registered to native'
,[ThaliCore] Session.deinit peer:B11581D3-CDC4-4C93-A560-BD4A6375972C:0
[ThaliCore] BrowserRelay.deinit
,2017-07-24 12:15:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:15:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:15:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:15:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:15:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# initial peer discovery
,2017-07-24 12:15:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-07-24 12:15:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:15:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:15:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:15:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 12:15:03 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 12:15:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 12:15:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 12:15:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-07-24 12:15:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-07-24 12:15:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:15:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:15:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:15:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 12:15:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-24 12:15:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 12:15:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 12:15:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-07-24 12:15:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-07-24 12:15:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:15:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:15:03 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:15:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 12:15:03 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 12:15:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 12:15:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 12:15:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-07-24 12:15:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-07-24 12:15:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:15:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:15:04 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:15:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 12:15:04 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 12:15:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 12:15:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 12:15:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-07-24 12:15:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-07-24 12:15:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:15:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:15:04 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:15:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 12:15:04 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 12:15:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 12:15:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 12:15:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-07-24 12:15:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-07-24 12:15:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:15:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:15:04 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:15:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 12:15:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-24 12:15:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 12:15:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 12:15:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-24 12:15:05 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-24 12:15:05 - DEBUG createNativeListener: 'listening 60248'
ok 151 Should throw
,# teardown
,2017-07-24 12:15:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 12:15:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 12:15:05 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-24 12:15:05 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 12:15:05 - DEBUG createNativeListener: 'listening 60250'
,2017-07-24 12:15:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-24 12:15:05 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 152 initial connection state should be CONNECTED
,2017-07-24 12:15:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 153 final connection state should be DISCONNECTED
,# teardown
,2017-07-24 12:15:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 12:15:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 12:15:05 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-07-24 12:15:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 12:15:05 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-24 12:15:05 - DEBUG createNativeListener: 'listening 60253'
,2017-07-24 12:15:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-24 12:15:05 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 12:15:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 154 tried to connect to right port
,ok 155 failed due to refused connection
,ok 156 routerPortConnectionFailed is emitted
,# teardown
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-24 12:15:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-24 12:15:06 - DEBUG createNativeListener: 'listening 60257'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-24 12:15:06 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2017-07-24 12:15:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 157 Send/recvd #1 should be equal length
,ok 158 Send/recvd #1 should be same
ok 159 Send/recvd #2 should be equal length
ok 160 Send/recvd #2 should be same
ok 161 Should be exactly 2 client sockets
,# teardown
,2017-07-24 12:15:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 12:15:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-24 12:15:06 - DEBUG createNativeListener: 'listening 60262'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-24 12:15:06 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2017-07-24 12:15:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 162 socket shouldn't close until after stream
ok 163 incoming remains open
# teardown
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-24 12:15:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 12:15:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 12:15:06 - DEBUG createNativeListener: 'Native Server - close'
2017-07-24 12:15:06, - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-07-24 12:15:07 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-24 12:15:07 - DEBUG createNativeListener: 'listening 60266'
,2017-07-24 12:15:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-24 12:15:07 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 164 we should not have gotten an error
,2017-07-24 12:15:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-24 12:15:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-07-24 12:15:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 165 socket shouldn't close until after incoming
,ok 166 incoming is cleaned up
,# teardown
,2017-07-24 12:15:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-24 12:15:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 12:15:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 12:15:07 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-24 12:15:07 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 12:15:07 - DEBUG createNativeListener: 'listening 60270'
,2017-07-24 12:15:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-24 12:15:07 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 12:15:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-24 12:15:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-24 12:15:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-24 12:15:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 167 stream was closed
,ok 168 incoming should survive
,ok 169 mux should have no streams
,# teardown
,2017-07-24 12:15:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 12:15:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 12:15:07 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-24 12:15:07 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-24 12:15:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-24 12:15:08 - DEBUG createNativeListener: 'listening 60274'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-24 12:15:08 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 170 we should not have gotten an error
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 171 Buffers are identical
,2017-07-24 12:15:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 172 native server is nulled out
,ok 173 native server should be closed
,ok 174 incoming has been removed
,ok 175 Incoming should be done
,ok 176 The mux object should be closed
,ok 177 The mux stream should be closed
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-24 12:15:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-24 12:15:08 - DEBUG createNativeListener: 'listening 60278'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-24 12:15:08 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
,2017-07-24 12:15:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 178 native server is nulled out
,ok 179 native server should be closed
,ok 180 incoming has been removed
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-24 12:15:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-07-24 12:15:10 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 12:15:10 - DEBUG createNativeListener: 'listening 60330'
,2017-07-24 12:15:10 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-24 12:15:10 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 181 we should not have gotten an error
,2017-07-24 12:15:10 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 182 Buffers are identical
2017-07-24 12:15:10 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-07-24 12:15:10 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client co,nnection <-> Mux - 0 - close'
,2017-07-24 12:15:10 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 183 server should be fine
ok 184 server should be open
ok 185 incoming has been removed
ok 186 The mux object should be clos,ed
ok 187 The mux stream should be closed
2017-07-24 12:15:10 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-24 12:15:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 12:15:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 12:15:10 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-24 12:15:10 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 12:15:10 - DEBUG createNativeListener: 'listening 60334'
,2017-07-24 12:15:10 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-24 12:15:10 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 188 we should not have gotten an error
,2017-07-24 12:15:10 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 189 Buffers are identical
,2017-07-24 12:15:10 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
2017-07-24 12:15:10 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to ,node - 0 - 0 - closed'
2017-07-24 12:15:10 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-07-24 12:15:10 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux, - 0 - close'
ok 190 server should be fine
ok 191 server should be open
ok 192 incoming has been removed
ok 193 The mux object should be closed
ok 194 The mux stream should be closed
,# teardown
,2017-07-24 12:15:10 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-24 12:15:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 12:15:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 12:15:10 - DEBUG createNativeListener: 'Native Server - close'
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
,2017-07-24 12:15:11 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-24 12:15:11 - DEBUG createNativeListener: 'listening 60337'
ok 198 port must be in range
,# teardown
,2017-07-24 12:15:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 12:15:11 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-24 12:15:11 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-24 12:15:11 - DEBUG createNativeListener: 'listening 60338'
ok 199 second start should return same port
,# teardown
,2017-07-24 12:15:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 12:15:11 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-24 12:15:12 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 12:15:12 - DEBUG createNativeListener: 'listening 60340'
,2017-07-24 12:15:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-24 12:15:12 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 200 we should be connected
2017-07-24 12:15:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 201 now we are disconnected
,2017-07-24 12:15:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-24 12:15:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 12:15:12 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-07-24 12:15:12 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
ok 202 Passed bogus id
2017-07-24 12:15:12 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
ok 203 Passed good id but bogus port
2017-07-24 12:15:12 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
ok 204 Passed right context
ok 205 Right server
ok 206 No error should be set
ok 207 Ret,ry should be false
ok 208 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 60342
,ok 209 should be equal
# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:15:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:15:12 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:15:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 12:15:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:15:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 12:15:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:15:12 - DEBUG thaliMobileNativeWrapper: 'Method disc,overyAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:15:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:15:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:15:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:15:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:15:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:15:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7E4D774A-7882-49FA-98A2-2FB6F737A46A", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:7E4D774A-7882-49FA-98A2-2FB6F737A46A
,2017-07-24 12:15:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:15:12 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:15:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 210 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2F4A4E81-4725-4348-9DB6-439977FBC066
[ThaliCore] Browser.startListening
2017-07-24 12:15:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":true}'
,2017-07-24 12:15:12 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 12:15:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 211 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8E62C46C-7157-4AC0-8447-5248FCCDBD3C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8E62C46C-7157-4AC0-8447-5248FCCDBD3C", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:453E9D44-4CC9-41AA-81C6-484AB3F7CC29:0
2017-07-24 12:15:12 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8E62C46C-7157-4AC0-8447-5248FCCDBD,3C","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "453E9D44-4CC9-41AA-81C6-484AB3F7CC29", generation: 0)
2017-07-24 12:15:12 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 8E62C46C-7157-4AC0-8447-5248FCCDBD3C (syncValue: SzRF64KiflKxlHfLntuQDoXwKoUtz2Zg)'
,2017-07-24 12:15:12 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8E62C46C-7157-4AC0-8447-5248FCCDBD3C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8E62C46C-7157-4AC0-8447-5248FCCDBD3C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8E62C46C-7157-4AC0-8447-5248FCCDBD3C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-07-24 12:15:12 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"453E9D44-4CC9-41AA-81C6-484AB3F7CC29","generation":0}'
2017-07-24 12:15:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 12:15:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2", generation: 0)
2017-07-24 12:15:13 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2","generation":0}'
2017-07-24 12:15:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 12:15:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 12:15:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA", generation: 0)
2017-07-24 12:15:13 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA","generation":0}'
2017-07-24 12:15:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 12:15:13 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-24 12:15:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 12:15:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7E4D774A-7882-49FA-98A2-2FB6F737A46A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7E4D774A-7882-49FA-98A2-2FB6F737A46A", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:8E62C46C-7157-4AC0-8447-5248FCCDBD3C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:8E,62C46C-7157-4AC0-8447-5248FCCDBD3C:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "8E62C46C-7157-4AC0-8447-5248FCCDBD3C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,E62C46C-7157-4AC0-8447-5248FCCDBD3C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8E62C46C-7157-4AC0-8447-5248FCCDBD3C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:8E62C46C-7157-4AC0-8447-5248FCCDBD3C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:8E62C46C-7157-4AC0-8447-5248FCCDBD3C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:8E62C46C-7157-4AC0-8447-5248FCCDBD3C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "8E62C46C-7157-4AC0-8447-5248FCCDBD3C", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8E62C46C-7157-4AC0-8447-5248FCCDBD3C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8E62C46C-7157-4AC0-8447-5248FCCDBD3C", generation: 0)
2017-07-24 12:15:16 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8E62C46C-7157-4AC0-8447-5248FCCDBD3C","generation":0}'
2017-07-24 12:15:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 12:15:16 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-24 12:15:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 12:15:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:8E62C46C-7157-4AC0-8447-5248FCCDBD3C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:8E,62C46C-7157-4AC0-8447-5248FCCDBD3C:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "8E62C46C-7157-4AC0-8447-5248FCCDBD3C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,E62C46C-7157-4AC0-8447-5248FCCDBD3C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8E62C46C-7157-4AC0-8447-5248FCCDBD3C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:8E62C46C-7157-4AC0-8447-5248FCCDBD3C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:8E62C46C-7157-4AC0-8447-5248FCCDBD3C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:453E9D44-4CC9-41AA-81C6-484AB3F7CC29:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "453E9D44-4CC9-41AA-81C6-484AB3F7CC29", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:8E62C46C-7157-4AC0-8447-5248FCCDBD3C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "8E62C46C-7157-4AC0-8447-5248FCCDBD3C", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:8E62C46C-7157-4AC0-8447-5248FCCDBD3C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:8E,62C46C-7157-4AC0-8447-5248FCCDBD3C:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "8E62C46C-7157-4AC0-8447-5248FCCDBD3C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,E62C46C-7157-4AC0-8447-5248FCCDBD3C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8E62C46C-7157-4AC0-8447-5248FCCDBD3C", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 12:15:20 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"SzRF64KiflKxlHfLntuQDoXwKoUtz2Zg","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 12:15:20 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'SzRF64KiflKxlHfLntuQDoXwKoUtz2Zg', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-24 12:15:20 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-24 12:15:20 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2 (syncValue: ZQ4LFNmBmoKDPIMebfupuDv,J97Tf5AkD)'
2017-07-24 12:15:20 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9C47D77D-9ABB-4FDD-AB7A-AF5F6,222D9C2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-24 12:15:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:8E62C46C-7157-4AC0-8447-5248FCCDBD3C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1F103392-5B0F-4BC3-9847-39D5168EED90
[ThaliCore] Advertiser: session connected Peer(uuid: "7E4D774A-7882-49FA-98A2-2FB6F737A46A", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:1F103392-5B0F-4BC3-9847-39D5168EED90 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60354
2017-07-24 12:15:23 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ZQ4LFNmBmoKDPIMebfupuDvJ97Tf5AkD",,"error":null,"portNumber":60354}'
2017-07-24 12:15:23 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ZQ4LFNmBmoKDPIMebfupuDvJ97Tf5AkD', error: 'null', listeningPort: '60354''
,ok 212 should be equal
2017-07-24 12:15:23 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA (syncValue: oA4h2giHyKauFoElRiN3M4xRAA7nOfoS)'
2017-07-24 12:15:23 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConn,ected:) Peer(uuid: "0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocke,tTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1F103392-5B0F-4BC3-9847-39D5168EED90
,[ThaliCore] Session.session(_:peer:didChange:) peer:1F103392-5B0F-4BC3-9847-39D5168EED90 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60358
,2017-07-24 12:15:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"oA4h2giHyKauFoElRiN3M4xRAA7nOfoS","error":null,"portNumber":60358}'
,2017-07-24 12:15:27 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'oA4h2giHyKauFoElRiN3M4xRAA7nOfoS', error: 'null', listeningPort: '60358''
,ok 213 should be equal
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:278F4659-BFD7-4AA1-9A8F-AB7B5CBFC374
[ThaliCore] Advertiser: session connected Peer(uuid: "7E4D774A-7882-49FA-98A2-2FB6F737A46A", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:278F4659-BFD7-4AA1-9A8F-AB7B5CBFC374 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:278F4659-BFD7-4AA1-9A8F-AB7B5CBFC374
,[ThaliCore] Session.session(_:peer:didChange:) peer:278F4659-BFD7-4AA1-9A8F-AB7B5CBFC374 state: connecting -> connected
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 12:15:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:15:31 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 12:15:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:7E4D774A-7882-49FA-98A2-2FB6F737A46A
2017-07-24 12:15:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"a,dvertisingActive":false}'
,2017-07-24 12:15:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:60354
,[ThaliCore] Session.disconnect() peer:9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1F103392-5B0F-4BC3-9847-39D5168EED90 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "7E4D774A-7882-49FA-98A2-2FB6F737A46A", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:278F4659-BFD7-4AA1-9A8F-AB7B5CBFC374
,[ThaliCore] Session.deinit peer:9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:60358
,[ThaliCore] Session.disconnect() peer:0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:278F4659-BFD7-4AA1-9A8F-AB7B5CBFC374
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA:0
[ThaliCore] BrowserRelay.deinit
2017-07-24 12:15:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 12:15:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvai,labilityChanged registered to native'
2017-07-24 12:15:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:15:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered ,to native'
,2017-07-24 12:15:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 12:15:31 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 12:15:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 12:15:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-07-24 12:15:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple local http requests
,listening on 60360
,ok 214 should be equal
ok 215 should be equal
ok 216 should be equal
# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:15:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:15:32 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:15:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 12:15:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:15:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 12:15:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:15:32 - DEBUG thaliMobileNativeWrapper: 'Method disc,overyAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:15:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:15:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 12:15:32 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 12:15:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 12:15:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 12:15:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A7B6BF29-41D3-42E8-899C-68B2A3229814", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:A7B6BF29-41D3-42E8-899C-68B2A3229814
2017-07-24 12:15:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:15:33, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-24 12:15:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 217 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Tha,liCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E0BDBFF6-6503-47DF-9A21-9C8128FAC6B8
[ThaliCore] Browser.startListening
2017-07-24 12:15:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adv,e,rtisingActive":true}'
2017-07-24 12:15:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"rou,ter":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:15:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 218 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2", generation: 0)
2017-07-24 12:15:33 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2","generation":0}'
2017-07-24 12:15:33 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2, (syncValue: sdoCMfly6XowXzohC1G5rzB9AT40VED6)'
2017-07-24 12:15:33 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9C47D77D-9ABB-4FDD-AB7A-AF5F622,2D9C2", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:) peer:9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInf,o:) found peer:0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA", generation: 0)
2017-07-24 12:15:33 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailabl,e":true,"peerIdentifier":"0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA","generation":0}'
2017-07-24 12:15:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 12:15:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D9B3E1DE-3AB4-4E08-AD80-781C08B55D07:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D9B3E1DE-3AB4-4E08-AD80-781C08B55D07", generation: 0)
,2017-07-24 12:15:33 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D9B3E1DE-3AB4-4E08-AD80-781C08B55D07","generation":0}'
,2017-07-24 12:15:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:15:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:15:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:161D7F1C-A29F-4896-AC9A-D46CC97A4B88:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "161D7F1C-A29F-4896-AC9A-D46CC97A4B88", generation: 0)
,2017-07-24 12:15:33 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"161D7F1C-A29F-4896-AC9A-D46CC97A4B88","generation":0}'
,2017-07-24 12:15:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:15:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:15:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:15:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A7B6BF29-41D3-42E8-899C-68B2A3229814:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A7B6BF29-41D3-42E8-899C-68B2A3229814", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:9C,47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:9C,47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:9C,47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:9C,47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:9C47D77D,-9ABB-4FDD-AB7A-AF5F6222D9C2 error: max retries exceeded
2017-07-24 12:15:44 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"sdoCMfly6XowXzohC1G5rzB9AT40VED6","error":"Connection could not be established","portNumber":null}'
2017-0,7-24 12:15:44 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'sdoCMfly6XowXzohC1G5rzB9AT40VED6', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-24 12:15:44 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-24 12:15:44 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA (syncValue: tYMOzfS,mfJnXFXKWVOUB4KVaD2GatQHp)'
2017-07-24 12:15:44 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0DDEFBB8-1F1A,-41FA-A4D9-BE44D742FEAA:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-24 12:15:44 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-07-24 12:15:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 12:15:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9B88E045-E289-49A1-A686-335529ED42F5
[ThaliCore] Advertiser: session connected Peer(uuid: "A7B6BF29-41D3-42E8-899C-68B2A3229814", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:9B88E045-E289-49A1-A686-335529ED42F5 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9FC7397B-2F7A-4F06-A1A6-6B3CDB0C5DD2
[ThaliCore] Advertiser: session connected Peer(uuid: "A7B6BF29-41D3-42E8-899C-68B2A3229814", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:9FC7397B-2F7A-4F06-A1A6-6B3CDB0C5DD2 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9B88E045-E289-49A1-A686-335529ED42F5
,[ThaliCore] Session.session(_:peer:didChange:) peer:9B88E045-E289-49A1-A686-335529ED42F5 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9FC7397B-2F7A-4F06-A1A6-6B3CDB0C5DD2
,[ThaliCore] Session.session(_:peer:didChange:) peer:9FC7397B-2F7A-4F06-A1A6-6B3CDB0C5DD2 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:0D,DEFBB8-1F1A-41FA-A4D9-BE44D742FEAA:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:0D,DEFBB8-1F1A-41FA-A4D9-BE44D742FEAA:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 12:15:52 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"tYMOzfSmfJnXFXKWVOUB4KVaD2GatQHp","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 12:15:52 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'tYMOzfSmfJnXFXKWVOUB4KVaD2GatQHp', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-24 12:15:52 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-24 12:15:52 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D9B3E1DE-3AB4-4E08-AD80-781C08B55D07 (syncValue: yAneh44nMpVZexwt9DtRkoV,qbK7cZN01)'
2017-07-24 12:15:52 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D9B3E1DE-3AB4-4E08-AD80-781C08B55D07", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D9B3E1DE-3AB4-4E08-AD80-781C08B55D07", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D9B3E1DE-3AB4-4E08-AD80-781C0,8B55D07:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-24 12:15:52 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:D9B3E1DE-3AB4-4E08-AD80-781C08B55D07:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D9B3E1DE-3AB4-4E08-AD80-781C08B55D07:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D9B3E1DE-3AB4-4E08-AD80-781C08B55D07:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "D9B3E1DE-3AB4-4E08-AD80-781C08B55D07", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60385
2017-07-24 12:15:55 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"yAneh44nMpVZexwt9DtRkoVqbK7cZN01",,"error":null,"portNumber":60385}'
2017-07-24 12:15:55 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'yAneh44nMpVZexwt9DtRkoVqbK7cZN01', error: 'null', listeningPort: '60385''
,ok 219 should be equal
,ok 220 should be equal
,ok 221 should be equal
,2017-07-24 12:15:55 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 161D7F1C-A29F-4896-AC9A-D46CC97A4B88 (syncValue: RCAoSiUEevLZswRVxjlMTBiFWwOpV7ii)'
,2017-07-24 12:15:55 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "161D7F1C-A29F-4896-AC9A-D46CC97A4B88", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "161D7F1C-A29F-4896-AC9A-D46CC97A4B88", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:161D7F1C-A29F-4896-AC9A-D46CC97A4B88:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:161D7F1C-A29F-4896-AC9A-D46CC97A4B88:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:161D7F1C-A29F-4896-AC9A-D46CC97A4B88:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:161D7F1C-A29F-4896-AC9A-D46CC97A4B88:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "161D7F1C-A29F-4896-AC9A-D46CC97A4B88", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60391
2017-07-24 12:15:58 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"RCAoSiUEevLZswRVxjlMTBiFWwOpV7ii",,"error":null,"portNumber":60391}'
2017-07-24 12:15:58 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'RCAoSiUEevLZswRVxjlMTBiFWwOpV7ii', error: 'null', listeningPort: '60391''
,ok 222 should be equal
ok 223 should be equal
ok 224 should be equal
# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 12:15:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 ,12:15:58 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-24 12:15:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:A7B6BF29-41D3-42E8-899C-6,8B2A3229814
2017-07-24 12:15:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:15:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:D9B3E1DE-3AB4-4E08-AD80-781C08B55D07
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCo,re] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:60385
[ThaliCore] Session.disconnect() peer:D9B3E1DE-3AB4-4E08-AD80-781C08B55D07:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TC,PListener.deinit
,[ThaliCore] Session.deinit peer:D9B3E1DE-3AB4-4E08-AD80-781C08B55D07:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:161D7F1C-A29F-4896-AC9A-D46CC97A4B88
[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:60391
[ThaliCore] Session.disconnect() peer:161D7F1C-A29F-4896-AC9A-D46CC97A4B88:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[Thali,Core] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:9B88E045-E289-49A1-A686-335529ED42F5 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "A7B6BF29-41D3-42E8-899C-68B2A3229814", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:9FC7397B-2F7A-4F06-A1A6-6B3CDB0C5DD2
,[ThaliCore] Session.deinit peer:161D7F1C-A29F-4896-AC9A-D46CC97A4B88:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-24 12:15:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 12:15:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:15:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:15:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:15:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:15:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:15:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:15:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:15:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:9FC7397B-2F7A-4F06-A1A6-6B3CDB0C5DD2
[ThaliCore] AdvertiserRelay.deinit
,# #startListeningForAdvertisements should fail if start not called
,ok 225 specific error should be returned
,# teardown
,ok 226 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:15:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:15:59 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:15:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:15:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:15:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:15:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:15:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:15:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 12:15:59 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 12:15:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 12:15:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 12:15:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 227 specific error should be returned
,# teardown
,ok 228 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:00 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-24 12:16:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:16:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:16:00 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 12:16:00 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 12:16:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 12:16:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 12:16:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-24 12:16:00 - DEBUG thaliMobileNativeWrapper: 'listening 60395'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:16:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 229 no errors
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:16:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 230 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:16:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:16:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 231 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:16:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:16:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:16:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startListeningForAdvertisements many times
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'listening 60396'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:EB104AF3-2F10-439A-81E4-F5B19F4AB74D
[ThaliCore] Browser.st,artListening
2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 12:16:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:16:01 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
ok 232 no errors
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertis,i,ngActive":false}'
2017-07-24 12:16:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router,":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:16:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 233 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 12:16:01 - INFO thaliMobile: 'Received state ({"d,iscoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:16:01 - INFO ,thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisi,ngStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 234 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:16:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'listening 60397'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E23415B6-783F-4694-9FEF-A461635085B5", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:E23415B6-783F-4694-9FEF-A461635085B5
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-24 12:16:01 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 12:16:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 235 no errors
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E23415B6-783F-4694-9FEF-A461635085B5", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:E23415B6-783F-4694-9FEF-A461635085B5
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:16:01 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 12:16:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 236 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:E23415B6-783F-4694-9FEF-A461635085B5
[ThaliCore] Advertiser.stopAdvertising() peerID:E23415B6-783F-4694-9FEF-A461635085B5
2017-07-24 12:16:01 - DEBUG thaliMo,bileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stop,ListeningForAdvertisements()
2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
2017-07-24 12:16:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 237 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: ',d,iscoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:16:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-24 12:16:02 - DEBUG thaliMobileNativeWrapper: 'listening 60400'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingAct,ive":false}'
2017-07-24 12:16:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 238 no errors
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:02 - DEBUG thaliMobileNativeWrapper: 'discover,yAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 239 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:02 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 12:16:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 240 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:16:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:16:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:16:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:16:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:16:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:16:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:16:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:16:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can get the network status before starting
,ok 241 network status should have certain non-empty properties
,# teardown
,ok 242 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:03 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 12:16:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:16:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:16:03 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 12:16:03 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 12:16:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 12:16:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 12:16:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# error returned with bad router
,2017-07-24 12:16:03 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
,ok 243 specific error expected
,# teardown
,ok 244 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:03 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 12:16:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:16:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:16:03 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 12:16:03 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 12:16:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 12:16:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 12:16:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are started when we call start
,2017-07-24 12:16:03 - DEBUG thaliMobileNativeWrapper: 'listening 60401'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4B7B31AD-E8E3-431B-931F-D5FD331AC354
[ThaliCore] Browser.st,artListening
2017-07-24 12:16:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 12:16:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:16:03 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DD6CB5E1-60F0-4532-A107-1486B6FCAAAA", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,DD6CB5E1-60F0-4532-A107-1486B6FCAAAA
2017-07-24 12:16:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 12:16:03 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:16:03 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 245 all connection succeed
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:DD6CB5E1-60F0-4532-A107-1486B6FCAAAA
2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-24 12:16:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:16:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
,2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-24 12:16:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 246 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdate,NonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:04 - DEBUG thali,MobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 12:16:04 - DEBUG ,t,haliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper:, 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:16:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# TCP Servers Manager should be null when we call start on iOS
,2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'listening 60404'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:EB82F94A-EBCD-45BC-8838-EF49C40E7266
[ThaliCore] Browser.st,artListening
2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 12:16:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:16:04 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C0071D25-D4DE-49A3-AE49-7506650E2D99", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,C0071D25-D4DE-49A3-AE49-7506650E2D99
2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 12:16:04 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:16:04 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 247 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:C0071D25-D4DE-49A3-AE49-7506650E2D99
,2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 12:16:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 12:16:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24, 12:16:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 248 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {,"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:16:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are stopped when we call stop
,2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'listening 60406'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D680E727-2E0D-451C-A8E4-FA297064FBA3
[ThaliCore] Browser.st,artListening
2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 12:16:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:16:05 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "31DB27F6-9658-4DD5-ACC2-66EB0D74BA2A", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,31DB27F6-9658-4DD5-ACC2-66EB0D74BA2A
2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 12:16:05 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:16:05 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:31DB27F6-9658-4DD5-ACC2-66EB0D74BA2A
2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrap,per: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 12:16:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"lis,t,ening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:16:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24, 12:16:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 12:16:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 249 is stopped after calling stop
,ok 250 connection should fail after stopping
,# teardown
,ok 251 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:16:05 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is properly hooked up
,2017-07-24 12:16:05 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
,# teardown
,ok 252 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:05 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-24 12:16:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:16:05 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 12:16:05 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is return error if we get called on iOS
,ok 253 error description matches
,# teardown
,ok 254 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:05 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-24 12:16:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:16:05 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 12:16:05 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is properly hooked up
,2017-07-24 12:16:06 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 255 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:06 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:16:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-24 12:16:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:16:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:16:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 12:16:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:16:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:16:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:16:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is return error if we get called on iOS
,ok 256 error description matches
,# teardown
,ok 257 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:06 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 12:16:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:16:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:16:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 12:16:06 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 12:16:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 12:16:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 12:16:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure we actually call kill connections properly
,ok 258 IMPLEMENT ME!!!!!!
,# teardown
,ok 259 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:07 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-24 12:16:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:16:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:16:07 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 12:16:07 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 12:16:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 12:16:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 12:16:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-07-24 12:16:07 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 260 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:07 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:16:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:16:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:16:07 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 12:16:07 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 12:16:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 12:16:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 12:16:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-07-24 12:16:07 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 261 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:07 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:16:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:16:07 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 12:16:07 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 12:16:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 12:16:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 12:16:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-07-24 12:16:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 262 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:08 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:16:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-24 12:16:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:16:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:16:08 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 12:16:08 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 12:16:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 12:16:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 12:16:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-07-24 12:16:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 263 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 12:16:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:16:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:16:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 12:16:08 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 12:16:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 12:16:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 12:16:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 264 NOT IMPLEMENTED # SKIP
,# teardown
,ok 265 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:09 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:16:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:16:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:16:09 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 12:16:09 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 12:16:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 12:16:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 12:16:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure bad PSK connections fail
,2017-07-24 12:16:10 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 266 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 12:16:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:16:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:16:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 12:16:10 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 12:16:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 12:16:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 12:16:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peer changes handled from a queue
,2017-07-24 12:16:10 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 267 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:11 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-24 12:16:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:16:11 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 12:16:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-07-24 12:16:11 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 268 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:11 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-24 12:16:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:16:11 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 12:16:11 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-07-24 12:16:11 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 269 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:11 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 12:16:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:16:11 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 12:16:11 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'listening 60409'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E7A2E4ED-3178-446C-AEF1-5D2A3E317C75
[ThaliCore] Browser.st,artListening
2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 12:16:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:16:11 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
ok 270 discoveryActive matches
ok 271 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonT,C,P: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 12:16:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:16:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisemen,ts()
[ThaliCore] Browser.stopListening()
2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:11 - INFO thaliMobile: 'Filtered out discoveryAd,vertisingStateUpdate (was in stopped state).'
ok 272 discoveryActive matches
ok 273 advertisingActive matches
,2017-07-24 12:16:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 12:16:12 - DEBUG thaliMobileNativeWrapper: 'listening 60410'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D9CF6E37-0CA1-4064-871F-7BEC9CC79311", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:D9CF6E37-0CA1-4064-871F-7BEC9CC79311
,2017-07-24 12:16:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-24 12:16:12 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 12:16:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 274 discoveryActive matches
,ok 275 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:D9CF6E37-0CA1-4064-871F-7BEC9CC79311
,2017-07-24 12:16:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 276 discoveryActive matches
,ok 277 advertisingActive matches
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:16:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 12:16:12 - DEBUG thaliMobileNativeWrapper: 'listening 60412'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:16:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:16:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 278 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:16:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:16:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:16:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:16:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:16:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:16:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:16:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:16:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'listening 60413'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:931652E6-8207-412A-BD5D-141E5840ECC0
[ThaliCore] Browser.st,artListening
2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 12:16:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:16:13 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "713F86DE-1B8D-4A80-9357-FB7298868583", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,713F86DE-1B8D-4A80-9357-FB7298868583
2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 12:16:13 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:16:13 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D9B3E1DE-3AB4-4E08-AD80-781C08B55D07:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D9B3E1DE-3AB4-4E08-AD80-781C08B55D07", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:161D7F1C-A29F-4896-AC9A-D46CC97A4B88:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "161D7F1C-A29F-4896-AC9A-D46CC97A4B88", generation: 0)
2017-07-24 12:16:13 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"D9B3E1DE-3AB4-4E08-AD80-781C08B55D07","generation":0}]'
2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"D9B3E1DE-3AB4-4E08-AD80-781C08B55D07","generation":0}'
2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,,"peerIdentifier":"161D7F1C-A29F-4896-AC9A-D46CC97A4B88","generation":0}]'
2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"161D7F1C-A29F-4896-AC9A-D46CC97A4B88",",generation":0}'
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"D9B3E1DE-3AB4-4E08-AD80-781C08B55D07","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:16:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"D9B3E1DE-3AB4-4E08-AD80-781C08B55D07","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 279 portNumber equal null
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"161D7F1C-A29F-4896-AC9A-D46CC97A4B88","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:16:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"161D7F1C-A29F-4896-AC9A-D46CC97A4B88","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:713F86DE-1B8D-4A80-9357-FB7298868583
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 12:16:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:16:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 280 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:16:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests between peers
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'listening 60415'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BDCD7795-8CEE-4F64-A87F-D7D24E9F18D5
[ThaliCore] Browser.st,artListening
2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 12:16:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 12:16:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "77A703D4-9056-42B9-ABF4-7877E1E90C13", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:77A703D4-9056-42B9-ABF4-7877E1E90C13
2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 12:16:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-24 12:16:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D9B3E1DE-3AB4-4E08-AD80-781C08B55D07:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D9B3E1DE-3AB4-4E08-AD80-781C08B55D07", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:161D7F1C-A29F-4896-AC9A-D46CC97A4B88:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "161D7F1C-A29F-4896-AC9A-D46CC97A4B88", generation: 0)
2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'Rec,eived peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"D9B3E1DE-3AB4-4E08-AD80-781C08B55D07","generation":0}]'
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"D9B3E1DE-3AB4-4E08-AD80-781C08B55D07","generation":0}'
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"161D7F1C-A29F-4896-AC9A-D46CC97A4B88","generation":0}]'
2017-07-24 12:16:13 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"161D7F1C-A29F-4896-AC9A-D46CC97A4B88","generation":0}'
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"D9B3E1DE-3AB4-4E08-AD80-781C08B55D07","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"D9B3E1DE-3AB4-4E08-AD80-781C08B55D07","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D9B3E1DE-3AB4-4E08-AD80-781C08B55D07 (syncValue: ZDw4wCl99jperwcU4Akd0l5G784wTEXg)'
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D9B3E1DE-3AB4-4E08-AD80-781C08B55D07", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D9B3E1DE-3AB4-4E08-AD80-781C08B55D07", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D9B3E1DE-3AB4-4E08-AD80-781C08B55D07:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"161D7F1C-A29F-4896-AC9A-D46CC97A4B88","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"161D7F1C-A29F-4896-AC9A-D46CC97A4B88","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C4D10B98-F43F-4736-BE2A-F1793B701211:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C4D10B98-F43F-4736-BE2A-F1793B701211", generation: 0)
2017-07-24 12:16:14 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"C4D10B98-F43F-4736-BE2A-F1793B701211","generation":0}]'
2017-07-24 12:16:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"C4D10B98-F43F-4736-BE2A-F1793B701211","generation":0}'
,2017-07-24 12:16:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"C4D10B98-F43F-4736-BE2A-F1793B701211","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-24 12:16:14 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"C4D10B98-F43F-4736-BE2A-F1793B701211","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-24 12:16:14 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"C4D10B98-F43F-4736-BE2A-F1793B701211","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:43207632-8028-448D-889D-1C62D213765D:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "43207632-8028-448D-889D-1C62D213765D", generation: 0)
,2017-07-24 12:16:14 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"43207632-8028-448D-889D-1C62D213765D","generation":0}]'
,2017-07-24 12:16:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"43207632-8028-448D-889D-1C62D213765D","generation":0}'
,2017-07-24 12:16:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"43207632-8028-448D-889D-1C62D213765D","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:16:14 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"43207632-8028-448D-889D-1C62D213765D","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 12:16:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"43207632-8028-448D-889D-1C62D213765D","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:77A703D4-9056-42B9-ABF4-7877E1E90C13:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "77A703D4-9056-42B9-ABF4-7877E1E90C13", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:D9B3E1DE-3AB4-4E08-AD80-781C08B55D07:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D9,B3E1DE-3AB4-4E08-AD80-781C08B55D07:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "D9B3E1DE-3AB4-4E08-AD80-781C08B55D07", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,9B3E1DE-3AB4-4E08-AD80-781C08B55D07", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D9B3E1DE-3AB4-4E08-AD80-781C08B55D07", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:D9B3E1DE-3AB4-4E08-AD80-781C08B55D07:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:D9B3E1DE-3AB4-4E08-AD80-781C08B55D07:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:D9B3E1DE-3AB4-4E08-AD80-781C08B55D07:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "D9B3E1DE-3AB4-4E08-AD80-781C08B55D07", generation: 0)
[ThaliCore] Browser.browser(_:lostPeer:) lost peer,:161D7F1C-A29F-4896-AC9A-D46CC97A4B88:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "161D7F1C-A29F-4896-AC9A-D46CC97A4B88", generation: 0)
2017-07-24 12:16:16 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from n,ative layer [{"peerAvailable":false,"peerIdentifier":"D9B3E1DE-3AB4-4E08-AD80-781C08B55D07","generation":0}]'
2017-07-24 12:16:16 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"D9B,3E1DE-3AB4-4E08-AD80-781C08B55D07","generation":0}'
2017-07-24 12:16:16 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"161D7F1C-A29F-4896-AC9A-D46CC97A4B88","generatio,n,":0}]'
2017-07-24 12:16:16 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"161D7F1C-A29F-4896-AC9A-D46CC97A4B88","generation":0}'
,2017-07-24 12:16:16 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"D9B3E1DE-3AB4-4E08-AD80-781C08B55D07","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-24 12:16:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"D9B3E1DE-3AB4-4E08-AD80-781C08B55D07","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-24 12:16:16 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnav,ailable - Emitting {"peerIdentifier":"161D7F1C-A29F-4896-AC9A-D46CC97A4B88","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-24 12:16:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"161D7F1C-,A29F-4896-AC9A-D46CC97A4B88","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:D9B3E1DE-3AB4-4E08-AD80-781C08B55D07:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D9,B3E1DE-3AB4-4E08-AD80-781C08B55D07:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "D9B3E1DE-3AB4-4E08-AD80-781C08B55D07", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,9B3E1DE-3AB4-4E08-AD80-781C08B55D07", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D9B3E1DE-3AB4-4E08-AD80-781C08B55D07", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 12:16:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ZDw4wCl99jperwcU4Akd0l5G784wTEXg","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 12:16:19 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ZDw4wCl99jperwcU4Akd0l5G784wTEXg', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-24 12:16:19 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-24 12:16:19 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C4D10B98-F43F-4736-BE2A-F1793B701211 (syncValue: pUz5OmfcBtlOqSIua8GJnRv,sEg545QSV)'
2017-07-24 12:16:19 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C4D10B98-F43F-4736-BE2A-F1793B701211", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C4D10B98-F43F-4736-BE2A-F1793B701211", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C4D10B98-F43F-4736-BE2A-F1793,B701211:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:D9B3E1DE-3AB4-4E08-AD80-781C08B55D07:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:C4D10B98-F43F-4736-BE2A-F1793B701211:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C4D10B98-F43F-4736-BE2A-F1793B701211:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:C4D10B98-F43F-4736-BE2A-F1793B701211:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "C4D10B98-F43F-4736-BE2A-F1793B701211", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60423
2017-07-24 12:16:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"pUz5OmfcBtlOqSIua8GJnRvsEg545QSV",,"error":null,"portNumber":60423}'
2017-07-24 12:16:22 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'pUz5OmfcBtlOqSIua8GJnRvsEg545QSV', error: 'null', listeningPort: '60423''
,2017-07-24 12:16:22 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:C4D10B98-F43F-4736-BE2A-F1793B701211:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C4D10B98-F43F-4736-BE2A-F1793B701211:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [2, 3, 6, 11]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 12:16:23 - DEBUG testUtils: 'Got response data'
2017-07-24 12:16:23 - DEBUG testUtils: 'Got end'
ok 281 response body should match testData
ok 282 must be started
,# teardown
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:11
[ThaliCore] VirtualSocket.closeStreams() vsID:11
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] TCPListener.socketDidDisconnect(_:withErr,or:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:77A703D4-9056-42B9-ABF4-7877E1E90C13
2017-07-24 12:16:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-24 12:16:29 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:16:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-07-24 12:16:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 12:16:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 283 must be stopped
[ThaliCore] BrowserManager.stopListenin,gForAdvertisements()
2017-07-24 12:16:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate ,(was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:29 - INFO thaliM,obile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:C4D10B98-F43F-4736-BE2A-F1793B701211
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningFor,C,onnectionsAndDisconnectClients() port:60423
[ThaliCore] Session.disconnect() peer:C4D10B98-F43F-4736-BE2A-F1793B701211:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:C4D10B98-F43F-4736-BE2A-F1793B701211:0
,2017-07-24 12:16:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:16:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:16:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 12:16:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:16:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:16:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:16:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can still do HTTP requests between peers with coordinator
,2017-07-24 12:16:30 - DEBUG thaliMobileNativeWrapper: 'listening 60425'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:564F3E34-1A3E-48E6-8FCA-DFB7221CB474
[ThaliCore] Browser.st,artListening
2017-07-24 12:16:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 12:16:30 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:16:30 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F5668ED9-ED3C-4A98-9698-3926B9298543", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,F5668ED9-ED3C-4A98-9698-3926B9298543
2017-07-24 12:16:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 12:16:30 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:16:30 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C4D10B98-F43F-4736-BE2A-F1793B701211:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C4D10B98-F43F-4736-BE2A-F1793B701211", generation: 0)
2017-07-24 12:16:30 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"C4D10B98-F43F-4736-BE2A-F1793B701211","generation":0}]'
2017-07-24 12:16:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"C4D10B98-F43F-4736-BE2A-F1793B701211","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:43207632-8028-448D-889D-1C62D213765D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "43207632-8028-448D-889D-1C62D213765D", generation: 0)
2017-07-24 12:16:30 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"C4D10B98-F43F-4736-BE2A-F1793B701211","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-24 12:16:30 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"pe,erIdentifier":"C4D10B98-F43F-4736-BE2A-F1793B701211","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-24 12:16:30 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C4D10B98-F43F-4736-BE2A-F1793B701211 (syncValue: IuExv2BGLmJU1kT,bH1wdcv5IUFxEYvu1)'
2017-07-24 12:16:30 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C4D10B98-F43F-4736-BE2A-F1793B701211", generation: 0) crea,t,ing a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C4D10B98-F43F-4736-BE2A-F1793B701211", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C4D10B98-F43F-4736-BE2A-F1793B701211:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 12:16:30 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"43207632-8028-448D-889D-1C62D213765D","generation":0}]'
2017-07-24 12:16:30 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"43207632-8028-448D-889D-1C62D213765D","generation":0}'
,2017-07-24 12:16:30 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"43207632-8028-448D-889D-1C62D213765D","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-24 12:16:30 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"43207632-8028-448D-889D-1C62D213765D","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F5668ED9-ED3C-4A98-9698-3926B9298543:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F5668ED9-ED3C-4A98-9698-3926B9298543", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4BA2E6AE-E25A-4688-907A-325BF6EAD4E8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4BA2E6AE-E25A-4688-907A-325BF6EAD4E8", generation: 0)
2017-07-24 12:16:31 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"4BA2E6AE-E25A-4688-907A-325BF6EAD4E8","generation":0}]'
2017-07-24 12:16:31 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"4BA2E6AE-E25A-4688-907A-325BF6EAD4E8","generation":0}'
,2017-07-24 12:16:31 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"4BA2E6AE-E25A-4688-907A-325BF6EAD4E8","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-24 12:16:31 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4BA2E6AE-E25A-4688-907A-325BF6EAD4E8","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-24 12:16:31 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"4BA2E6AE-E25A-4688-907A-325BF6EAD4E8","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7F5CBA13-5171-4B86-A630-E05A6F334A94:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7F5CBA13-5171-4B86-A630-E05A6F334A94", generation: 0)
2017-07-24 12:16:31 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"7F5CBA13-5171-4B86-A630-E05A6F334A94","generation":0}]'
2017-07-24 12:16:31 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"7F5CBA13-5171-4B86-A630-E05A6F334A94","generation":0}'
,2017-07-24 12:16:31 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7F5CBA13-5171-4B86-A630-E05A6F334A94","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-24 12:16:31 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7F5CBA13-5171-4B86-A630-E05A6F334A94","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-24 12:16:31 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"7F5CBA13-5171-4B86-A630-E05A6F334A94","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:C4D10B98-F43F-4736-BE2A-F1793B701211:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C4,D10B98-F43F-4736-BE2A-F1793B701211:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "C4D10B98-F43F-4736-BE2A-F1793B701211", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,4D10B98-F43F-4736-BE2A-F1793B701211", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C4D10B98-F43F-4736-BE2A-F1793B701211", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:C4D10B98-F43F-4736-BE2A-F1793B701211:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:C4D10B98-F43F-4736-BE2A-F1793B701211:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:C4D10B98-F43F-4736-BE2A-F1793B701211:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C4,D10B98-F43F-4736-BE2A-F1793B701211:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "C4D10B98-F43F-4736-BE2A-F1793B701211", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,4D10B98-F43F-4736-BE2A-F1793B701211", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C4D10B98-F43F-4736-BE2A-F1793B701211", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:C4D10B98-F43F-4736-BE2A-F1793B701211:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:C4D10B98-F43F-4736-BE2A-F1793B701211:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:C4D10B98-F43F-4736-BE2A-F1793B701211:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C4,D10B98-F43F-4736-BE2A-F1793B701211:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "C4D10B98-F43F-4736-BE2A-F1793B701211", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,4D10B98-F43F-4736-BE2A-F1793B701211", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C4D10B98-F43F-4736-BE2A-F1793B701211", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:C4D10B98-F43F-4736-BE2A-F1793B701211:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:C4D10B98-F43F-4736-BE2A-F1793B701211:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:C4D10B98-F43F-4736-BE2A-F1793B701211:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C4,D10B98-F43F-4736-BE2A-F1793B701211:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "C4D10B98-F43F-4736-BE2A-F1793B701211", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:C4D10B98,-F43F-4736-BE2A-F1793B701211 error: max retries exceeded
2017-07-24 12:16:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"IuExv2BGLmJU1kTbH1wdcv5IUFxEYvu1","error":"Connection could not be established","portNumber":null}'
2017-0,7-24 12:16:41 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'IuExv2BGLmJU1kTbH1wdcv5IUFxEYvu1', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-24 12:16:41 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-24 12:16:41 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 43207632-8028-448D-889D-1C62D213765D (syncValue: VY1cUPp,C2UGy6WJBDlbYoONuZQfJx5UP)'
2017-07-24 12:16:41 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "43207632-8028-448D-889D-1C62D213765D", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "43207632-8028-448D-889D-1C62D213765D", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:43207632-8028,-448D-889D-1C62D213765D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:C4D10B98-F43F-4736-BE2A-F1793B701211:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A3D6730E-18BC-403B-BDA5-19249F3CDCE0
[ThaliCore] Advertiser: session connected Peer(uuid: "F5668ED9-ED3C-4A98-9698-3926B9298543", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:17FDC70A-55FB-4656-AE02-D3FC45735E13
[ThaliCore] Advertiser: session connected Peer(uuid: "F5668ED9-ED3C-4A98-9698-3,926B9298543", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:A3D6730E-18BC-403B-BDA5-19249F3CDCE0 state: notConnected -> connecting
[T,haliCore] Session.session(_:peer:didChange:) peer:17FDC70A-55FB-4656-AE02-D3FC45735E13 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:43207632-8028-448D-889D-1C62D213765D:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "43207632-8028-448D-889D-1C62D213765D", generation: 0)
2017-07-24 12:16:42 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"43207632-8028-448D-889D-1C62D213765D","generation":0}]'
2017-07-24 12:16:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"43207632-8028-448D-889D-1C62D213765D","generation":0}'
,2017-07-24 12:16:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"43207632-8028-448D-889D-1C62D213765D","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-24 12:16:42 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"43207632-8028-448D-889D-1C62D213765D","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:43207632-8028-448D-889D-1C62D213765D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:43,207632-8028-448D-889D-1C62D213765D:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "43207632-8028-448D-889D-1C62D213765D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,3207632-8028-448D-889D-1C62D213765D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "43207632-8028-448D-889D-1C62D213765D", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 12:16:43 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"VY1cUPpC2UGy6WJBDlbYoONuZQfJx5UP","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 12:16:43 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'VY1cUPpC2UGy6WJBDlbYoONuZQfJx5UP', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-24 12:16:43 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-24 12:16:43 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4BA2E6AE-E25A-4688-907A-325BF6EAD4E8 (syncValue: xhzfgYmUZj8A3sh5SkwVvMV,A6qVyb9oa)'
2017-07-24 12:16:43 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4BA2E6AE-E25A-4688-907A-325BF6EAD4E8", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4BA2E6AE-E25A-4688-907A-325BF6EAD4E8", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4BA2E6AE-E25A-4688-907A-325BF,6EAD4E8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:43207632-8028-448D-889D-1C62D213765D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:17FDC70A-55FB-4656-AE02-D3FC45735E13
,[ThaliCore] Session.session(_:peer:didChange:) peer:4BA2E6AE-E25A-4688-907A-325BF6EAD4E8:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A3D6730E-18BC-403B-BDA5-19249F3CDCE0
,[ThaliCore] Session.session(_:peer:didChange:) peer:A3D6730E-18BC-403B-BDA5-19249F3CDCE0 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A3D6730E-18BC-403B-BDA5-19249F3CDCE0
[ThaliCore] Session.startOutputStream(with:) peer:A3D6730E-18BC-403B-BDA5-19249F3CDCE0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [2, 3, 6, 11, 12]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:17FDC70A-55FB-4656-AE02-D3FC45735E13 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:17FDC70A-55FB-4656-AE02-D3FC45735E13
[ThaliCore] Session.startOutputStream(with:) peer:17FDC70A-55FB-4656-AE02-D3FC45735E13
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [2, 3, 6, 11, 12, 13]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:C4D10B98-F43F-4736-BE2A-F1793B701211:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "C4D10B98-F43F-4736-BE2A-F1793B701211", generation: 0)
2017-07-24 12:16:45 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"C4D10B98-F43F-4736-BE2A-F1793B701211","generation":0}]'
2017-07-24 12:16:45 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"C4D10B98-F43F-4736-BE2A-F1793B701211","generation":0}'
,2017-07-24 12:16:45 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"C4D10B98-F43F-4736-BE2A-F1793B701211","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-24 12:16:45 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"C4D10B98-F43F-4736-BE2A-F1793B701211","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4BA2E6AE-E25A-4688-907A-325BF6EAD4E8:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:4BA2E6AE-E25A-4688-907A-325BF6EAD4E8:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "4BA2E6AE-E25A-4688-907A-325BF6EAD4E8", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60440
2017-07-24 12:16:46 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"xhzfgYmUZj8A3sh5SkwVvMVA6qVyb9oa",,"error":null,"portNumber":60440}'
2017-07-24 12:16:46 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'xhzfgYmUZj8A3sh5SkwVvMVA6qVyb9oa', error: 'null', listeningPort: '60440''
,2017-07-24 12:16:46 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) pee,r:4BA2E6AE-E25A-4688-907A-325BF6EAD4E8:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4BA2E6AE-E25A-4688-907A-325BF6EAD4E8:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [2, 3, 6, 11, 12, 13, 14]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 12:16:46 - DEBUG testUtils: 'Got response data'
2017-07-24 12:16:46 - DEBUG testUtils: 'Got end'
ok 284 response body should match testData
ok 285 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:F5668ED9-ED3C-4A98-9698-3926B9298543
2017-07-24 12:16:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-24 12:16:47 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:16:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
,2017-07-24 12:16:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-24 12:16:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 286 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdate,NonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:47 - DEBUG thali,MobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.d,i,sconnect peer:4BA2E6AE-E25A-4688-907A-325BF6EAD4E8
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescript,ion=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket close,d by remote peer})
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] TCPListener.sto,pListeningForConnectionsAndDisconnectClients() port:60440
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.closeStreams() vsI,D,:14
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:12
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:13
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] VirtualSocket.closeStreams() vsID:12
[ThaliCore] VirtualSocket.closeStre,ams() vsID:13
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket exited RunLoop vsID:14
[ThaliCore] BrowserRelay.d,idSocketDisconnectHandler
[ThaliCore] Session.disconnect() peer:4BA2E6AE-E25A-4688-907A-325BF6EAD4E8:0
[ThaliCore] VirtualSocket.deinit vsID:14 [2, 3, 6, 11, 12, 13]
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.deinit peer:4BA2E6AE-E25A-4688-907A,-325BF6EAD4E8:0
[ThaliCore] BrowserRelay.deinit
2017-07-24 12:16:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:16:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:16:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:12
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.deinit vsI,D:12 [2, 3, 6, 11, 13]
[ThaliCore] VirtualSocket exited RunLoop vsID:13
[ThaliCore] VirtualSocket.deinit vsID:13 [2, 3, 6, 11]
,2017-07-24 12:16:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:16:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:16:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:16:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:16:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:A3D6730E-18BC-403B-BDA5-19249F3CDCE0 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "F5668ED9-ED3C-4A98-9698-3926B9298543", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:17FDC70A-55FB-4656-AE02-D3FC45735E13
[ThaliCore] Sessio,n.deinit peer:17FDC70A-55FB-4656-AE02-D3FC45735E13
[ThaliCore] AdvertiserRelay.deinit
,# calls correct starts when network changes
,2017-07-24 12:16:47 - DEBUG CoordinatedClient: 'test was skipped, name: 'calls correct starts when network changes''
,# teardown
,ok 287 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:48 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 12:16:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:16:48 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 12:16:48 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# test to coordinate connection cut
,# teardown
,ok 288 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:48 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 12:16:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 12:16:48 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests after connections are cut
,2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'listening 60442'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:012C3002-26D3-46F6-B870-042527C7A835
[ThaliCore] Browser.st,artListening
2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 12:16:48 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:16:48 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E2E80740-826A-40B4-B83A-A8A5E1CA7D0A", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,E2E80740-826A-40B4-B83A-A8A5E1CA7D0A
2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 12:16:48 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:16:48 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7F5CBA13-5171-4B86-A630-E05A6F334A94:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7F5CBA13-5171-4B86-A630-E05A6F334A94", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:4BA2E6AE-E25A-4688-907A-325BF6EAD4E8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4BA2E6AE-E25A-4688-907A-325BF6EAD4E8", generation: 0)
2017-07-24 12:16:49 - DEBUG thaliMobileNativeWrapper: 'Rec,eived peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"7F5CBA13-5171-4B86-A630-E05A6F334A94","generation":0}]'
2017-07-24 12:16:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"p,eerAvailable":true,"peerIdentifier":"7F5CBA13-5171-4B86-A630-E05A6F334A94","generation":0}'
,2017-07-24 12:16:49 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"4BA2E6AE-E25A-4688-907A-325BF6EAD4E8","generation":0}]'
,2017-07-24 12:16:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"4BA2E6AE-E25A-4688-907A-325BF6EAD4E8","generation":0}'
,2017-07-24 12:16:49 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7F5CBA13-5171-4B86-A630-E05A6F334A94","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:16:49 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"7F5CBA13-5171-4B86-A630-E05A6F334A94","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:16:49 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 7F5CBA13-5171-4B86-A630-E05A6F334A94 (syncValue: Trup9oYLbCXuOtoeptjOtXrda7qdG1H9)'
,2017-07-24 12:16:49 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7F5CBA13-5171-4B86-A630-E05A6F334A94", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7F5CBA13-5171-4B86-A630-E05A6F334A94", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7F5CBA13-5171-4B86-A630-E05A6F334A94:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 12:16:49 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"4BA2E6AE-E25A-4688-907A-325BF6EAD4E8","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:16:49 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"4BA2E6AE-E25A-4688-907A-325BF6EAD4E8","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4", generation: 0)
2017-07-24 12:16:49 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4","generation":0}]'
2017-07-24 12:16:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4","generation":0}'
,2017-07-24 12:16:49 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:16:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7146B875-BFA5-464A-88ED-B177AA3D7C16:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7146B875-BFA5-464A-88ED-B177AA3D7C16", generation: 0)
,2017-07-24 12:16:49 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:16:49 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"7146B875-BFA5-464A-88ED-B177AA3D7C16","generation":0}]'
,2017-07-24 12:16:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"7146B875-BFA5-464A-88ED-B177AA3D7C16","generation":0}'
,2017-07-24 12:16:49 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7146B875-BFA5-464A-88ED-B177AA3D7C16","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:16:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7146B875-BFA5-464A-88ED-B177AA3D7C16","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 12:16:49 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"7146B875-BFA5-464A-88ED-B177AA3D7C16","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E2E80740-826A-40B4-B83A-A8A5E1CA7D0A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E2E80740-826A-40B4-B83A-A8A5E1CA7D0A", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:7F5CBA13-5171-4B86-A630-E05A6F334A94:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:7F,5CBA13-5171-4B86-A630-E05A6F334A94:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "7F5CBA13-5171-4B86-A630-E05A6F334A94", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,F5CBA13-5171-4B86-A630-E05A6F334A94", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7F5CBA13-5171-4B86-A630-E05A6F334A94", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:7F5CBA13-5171-4B86-A630-E05A6F334A94:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:7F5CBA13-5171-4B86-A630-E05A6F334A94:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:7F5CBA13-5171-4B86-A630-E05A6F334A94:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:7F,5CBA13-5171-4B86-A630-E05A6F334A94:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "7F5CBA13-5171-4B86-A630-E05A6F334A94", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,F5CBA13-5171-4B86-A630-E05A6F334A94", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7F5CBA13-5171-4B86-A630-E05A6F334A94", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:7F5CBA13-5171-4B86-A630-E05A6F334A94:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:7F5CBA13-5171-4B86-A630-E05A6F334A94:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:7F5CBA13-5171-4B86-A630-E05A6F334A94:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:7F,5CBA13-5171-4B86-A630-E05A6F334A94:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "7F5CBA13-5171-4B86-A630-E05A6F334A94", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,F5CBA13-5171-4B86-A630-E05A6F334A94", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7F5CBA13-5171-4B86-A630-E05A6F334A94", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:7F5CBA13-5171-4B86-A630-E05A6F334A94:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:7F5CBA13-5171-4B86-A630-E05A6F334A94:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:4BA2E6AE-E25A-4688-907A-325BF6EAD4E8:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "4BA2E6AE-E25A-4688-907A-325BF6EAD4E8", generation: 0)
2017-07-24 12:16:58 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"4BA2E6AE-E25A-4688-907A-325BF6EAD4E8","generation":0}]'
2017-07-24 12:16:58 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"4BA2E6AE-E25A-4688-907A-325BF6EAD4E8","generation":0}'
,2017-07-24 12:16:58 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"4BA2E6AE-E25A-4688-907A-325BF6EAD4E8","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-24 12:16:58 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"4BA2E6AE-E25A-4688-907A-325BF6EAD4E8","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:7F5CBA13-5171-4B86-A630-E05A6F334A94:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:7F,5CBA13-5171-4B86-A630-E05A6F334A94:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "7F5CBA13-5171-4B86-A630-E05A6F334A94", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:7F5CBA13,-5171-4B86-A630-E05A6F334A94 error: max retries exceeded
2017-07-24 12:16:59 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Trup9oYLbCXuOtoeptjOtXrda7qdG1H9","error":"Connection could not be established","portNumber":null}'
2017-0,7-24 12:16:59 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Trup9oYLbCXuOtoeptjOtXrda7qdG1H9', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-24 12:16:59 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-24 12:16:59 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4 (syncValue: nAWCYQF,ykGn4HKwzYMqqqzqu7MlUV4TI)'
2017-07-24 12:16:59 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B9D0FED2-8EEB,-4D6E-8AC0-E651ACCCA2D4:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:7F5CBA13-5171-4B86-A630-E05A6F334A94:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60456
2017-07-24 12:17:02 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"nAWCYQFykGn4HKwzYMqqqzqu7MlUV4TI",,"error":null,"portNumber":60456}'
2017-07-24 12:17:02 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'nAWCYQFykGn4HKwzYMqqqzqu7MlUV4TI', error: 'null', listeningPort: '60456''
,2017-07-24 12:17:02 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) pee,r:B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [2, 3, 6, 11, 15]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 12:17:03 - DEBUG testUtils: 'Got response data'
2017-07-24 12:17:03 - DEBUG testUtils: 'Got end'
ok 289 response body should match testData
ok 290 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:E2E80740-826A-40B4-B83A-A8A5E1CA7D0A
2017-07-24 12:17:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-24 12:17:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:17:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
,2017-07-24 12:17:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:17:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-24 12:17:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 291 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:17:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdate,NonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:17:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:17:03 - DEBUG thali,MobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:17:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:60456
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] VirtualSocket.closeStreams() vsID:15
,[ThaliCore] VirtualSocket exited RunLoop vsID:15
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] VirtualSocket.deinit vsID:15 [2, 3, 6, 11]
[ThaliCore] Session.disconnect() peer:B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4:0
,[ThaliCore] Session.deinit peer:B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-24 12:17:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:17:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:17:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:17:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:17:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:17:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:17:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:17:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# will fail bad PSK connection between peers
,ok 292 FIX ME, PLEASE!!!
,# teardown
,ok 293 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:17:04 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 12:17:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 12:17:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We provide notification when a listener dies and we recreate it
,2017-07-24 12:17:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'We provide notification when a listener dies and we recreate it''
,# teardown
,ok 294 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:17:04 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:17:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:17:04 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 12:17:04 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated
,2017-07-24 12:17:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''
,# teardown
,ok 295 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:17:04 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:17:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:17:04 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 12:17:04 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,ok 296 ThaliMobile should be stopped
,# #startListeningForAdvertisements should fail if start not called
,ok 297 specific error should be returned
,# teardown
,2017-07-24 12:17:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"7F5CBA13-5171-4B86-A630-E05A6F334A94","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-24, 12:17:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-24 12:17:05 ,- DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"7146B875-BFA5-464A-88ED-B177AA3D7C16","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 298 error should be null
ok 299 error should be null
,# setup
,ok 300 ThaliMobile should be stopped
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 301 specific error should be returned
,# teardown
,ok 302 error should be null
ok 303 error should be null
,# setup
,ok 304 ThaliMobile should be stopped
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-24 12:17:05 - DEBUG thaliMobileNativeWrapper: 'listening 60458'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:17:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 305 error should be null
,ok 306 error should be null
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:17:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 307 error should be null
,ok 308 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:17:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:17:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:17:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:17:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:17:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 309 error should be null
,ok 310 error should be null
,# setup
,ok 311 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-07-24 12:17:06 - DEBUG thaliMobileNativeWrapper: 'listening 60459'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DEF27F41-9F51-4614-9CEF-527224C704C1
[ThaliCore] Browser.st,artListening
2017-07-24 12:17:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 312 error should be null
ok 313 error should be null
[ThaliCore] BrowserManager.startListe,ningForAdvertisements
2017-07-24 12:17:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 314 error should be null
ok 315 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:17:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 12:17:06 - INFO thaliMobile: 'Received state ({"d,iscoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-24 12:17:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 12:17:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:17:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-24 12:17:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 316 error should be null
,ok 317 error should be null
,# setup
,ok 318 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-24 12:17:06 - DEBUG thaliMobileNativeWrapper: 'listening 60460'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F9A89C22-2DC8-45BE-AA46-804A34A5D71E", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:F9A89C22-2DC8-45BE-AA46-804A34A5D71E
,2017-07-24 12:17:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 319 error should be null
,ok 320 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F9A89C22-2DC8-45BE-AA46-804A34A5D71E", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:F9A89C22-2DC8-45BE-AA46-804A34A5D71E
,2017-07-24 12:17:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 321 error should be null
ok 322 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:F9A89C22-2DC8-45BE-AA46-804A34A5D71E
[ThaliCore] Advertiser.stopAdvertising() peerID:F9A89C22-2DC8-45BE-AA46-804A34A5D71E
2017-07-24 12:17:06 - DEBUG thaliMo,bileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:17:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:17:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:17:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 12:17:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 323 error should be null
ok 324 error should be null
,# setup
,ok 325 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-24 12:17:06 - DEBUG thaliMobileNativeWrapper: 'listening 60463'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:17:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingAct,ive":false}'
ok 326 error should be null
ok 327 error should be null
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:17:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 328 error should be null
,ok 329 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:17:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:17:07 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:17:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 12:17:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 12:17:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 330 error should be null
ok 331 error should be null
,# setup
,ok 332 ThaliMobile should be stopped
,# #start - Causing native or wifi to fail will cause a promise reject 
,2017-07-24 12:17:07 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
,ok 333 This should not cause wifi to fail
ok 334 native router should be bad
,# teardown
,ok 335 error should be null
ok 336 error should be null
,# setup
,ok 337 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-07-24 12:17:07 - DEBUG thaliMobileNativeWrapper: 'listening 60464'
ok 338 first call should succeed
ok 339 first call should succeed
ok 340 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:17:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:17:08 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:17:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:17:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-24 12:17:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 341 error should be null
ok 342 error should be null
,# setup
,ok 343 ThaliMobile should be stopped
,# #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)
,2017-07-24 12:17:08 - DEBUG CoordinatedClient: 'test was skipped, name: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''
,# teardown
,ok 344 error should be null
ok 345 error should be null
,# setup
,ok 346 ThaliMobile should be stopped
,# does not emit duplicate discoveryAdvertisingStateUpdate
,2017-07-24 12:17:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
,# teardown
,ok 347 error should be null
ok 348 error should be null
,# setup
,ok 349 ThaliMobile should be stopped
,# does not send duplicate availability changes
,2017-07-24 12:17:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a7ed1fc5-a9f0-40f6-a921-c1c36bae7966","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 350 should be called once
ok 351 should not have been called more than once
,# teardown
,2017-07-24 12:17:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"a7ed1fc5-a9f0-40f6-a921-c1c36bae7966","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 352 error should be null
ok 353 error should be null
,# setup
,ok 354 ThaliMobile should be stopped
,# can get the network status
,ok 355 network status should have certain non-empty properties
,# teardown
,ok 356 error should be null
ok 357 error should be null
,# setup
,ok 358 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (native)
,ok 359 we have not added peer to the cache yet
2017-07-24 12:17:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7f9c1958-6ca0-424f-ad49-0caa51224b22","connectionType":"MPCF","peerAvailable":true,"generation":0,,"newAddressPort":false}'
,ok 360 peer should be available
ok 361 cache contains native peer
2017-07-24 12:17:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7f9c1958-6ca0-424f-ad49-0caa51224b22","connectionType":"MPCF","peerAvailable":,false,"generation":0,"newAddressPort":null}'
ok 362 peer should be unavailable
ok 363 peer has been removed from cache
,# teardown
,ok 364 error should be null
ok 365 error should be null
,# setup
,ok 366 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 367 we have not added peer to the cache yet
,2017-07-24 12:17:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"80480f44-3c0f-41f6-b1b5-c05c18dc5398","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 368 peer should be a,vailable
ok 369 cache contains wifi peer
2017-07-24 12:17:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"80480f44-3c0f-41f6-b1b5-c05c18dc5398","connectionType":"tcp","peerAvailable":false,"generation":0,"newA,ddressPort":null}'
ok 370 peer should be unavailable
ok 371 peer has been removed from cache
,# teardown
,ok 372 error should be null
,ok 373 error should be null
,# setup
,ok 374 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-07-24 12:17:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c85ed981-7906-4903-a025-95f45aa47ab1","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 375 first peer is a,vailable
2017-07-24 12:17:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9f0f1ee9-87f2-47c0-b8bb-ddc449c87ab6","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 376 second, peer is available
ok 377 first and second peers are different
,# teardown
,2017-07-24 12:17:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c85ed981-7906-4903-a025-95f45aa47ab1","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-24, 12:17:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9f0f1ee9-87f2-47c0-b8bb-ddc449c87ab6","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 378 error should be null
ok 379 error should be null
,# setup
,ok 380 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 381 should not be in cache at start
2017-07-24 12:17:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"bedb8880-6edd-4b71-9e46-3c3ab5ac57c4","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddr,essPort":false}'
,ok 382 peer is available
,# teardown
,2017-07-24 12:17:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"bedb8880-6edd-4b71-9e46-3c3ab5ac57c4","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 383 error should be null
ok 384 error should be null
,# setup
,ok 385 ThaliMobile should be stopped
,# native available - peer with same port and different generation is cached (BLUETOOTH)
,2017-07-24 12:17:10 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with same port and different generation is cached (BLUETOOTH)''
,# teardown
,ok 386 error should be null
ok 387 error should be null
,# setup
,ok 388 ThaliMobile should be stopped
,# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
,2017-07-24 12:17:11 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''
,# teardown
,ok 389 error should be null
ok 390 error should be null
,# setup
,ok 391 ThaliMobile should be stopped
,# native available - peer with greater generation is cached (MPCF)
,2017-07-24 12:17:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7343db32-7214-4e69-9fa1-d0e19fa9c4fb","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
,ok 392 peer should be available
,2017-07-24 12:17:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7343db32-7214-4e69-9fa1-d0e19fa9c4fb","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 393 peer should be available
ok 394 should store correct generation
,# teardown
,2017-07-24 12:17:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"7343db32-7214-4e69-9fa1-d0e19fa9c4fb","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 395 error should be null
ok 396 error should be null
,# setup
,ok 397 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-07-24 12:17:11 - DEBUG thaliMobileNativeWrapper: 'listening 60465'
2017-07-24 12:17:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4ec20494-27e1-48ad-96a7-899d50ea5e32","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
ok 398 discovered correct peer
ok 399 got correct generation
,2017-07-24 12:17:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4ec20494-27e1-48ad-96a7-899d50ea5e32","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 400 discovered correct peer
ok 401 got correct generation
,# teardown
,2017-07-24 12:17:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"4ec20494-27e1-48ad-96a7-899d50ea5e32","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-24 12:17:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:17:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:17:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpd,ateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:17:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 12:17:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server',
,ok 402 error should be null
ok 403 error should be null
,# setup
,ok 404 ThaliMobile should be stopped
,# native unavailable - new peer is ignored
,2017-07-24 12:17:11 - DEBUG thaliMobileNativeWrapper: 'listening 60466'
,2017-07-24 12:17:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"005f101c-825e-4f7a-b651-3699d2327066","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 405 discovered available peer
,ok 406 peer is available
,# teardown
,2017-07-24 12:17:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"005f101c-825e-4f7a-b651-3699d2327066","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:17:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:17:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:17:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:17:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:17:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 407 error should be null
,ok 408 error should be null
,# setup
,ok 409 ThaliMobile should be stopped
,# native unavailable - cached peer is removed
,2017-07-24 12:17:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"df97e1d6-f460-4fbc-a3db-5fd1c4d81c3a","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 410 peer should be ,available
2017-07-24 12:17:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"df97e1d6-f460-4fbc-a3db-5fd1c4d81c3a","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 411 peer, should be unavailable
ok 412 should be removed from cache
,# teardown
,ok 413 error should be null
ok 414 error should be null
,# setup
,ok 415 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-07-24 12:17:12 - DEBUG thaliMobileNativeWrapper: 'listening 60467'
2017-07-24 12:17:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5090067e-7d70-4168-8b93-f631d7fba262","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 416 first peer is expected to be available
2017-07-24 12:17:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"acc03b15-4276-412e-9653-9cfc8270b253","connectio,nType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 417 second peer is expected to be available
2017-07-24 12:17:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"acc03b15-4276-,412e-9653-9cfc8270b253","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 418 peer became unavailable
ok 419 it was wifi peer
2017-07-24 12:17:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handle,P,eer {"peerIdentifier":"acc03b15-4276-412e-9653-9cfc8270b253","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 420 we found peer again
ok 421 it was wifi peer
2017-07-24 12:17:12 - DEBUG thaliMobile: 'Emitting peerAv,ailabilityChanged from emitPeerUnavailable {"peerIdentifier":"acc03b15-4276-412e-9653-9cfc8270b253","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 422 peer became unavailable
ok 423 it was wifi peer
,# teardown
,2017-07-24 12:17:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5090067e-7d70-4168-8b93-f631d7fba262","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-24 12:17:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:17:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:17:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpd,ateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:17:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 12:17:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 424 error should be null
,ok 425 error should be null
,# setup
,ok 426 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
,2017-07-24 12:17:12 - DEBUG CoordinatedClient: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''
,# teardown
,ok 427 error should be null
ok 428 error should be null
,# setup
,ok 429 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
,2017-07-24 12:17:13 - DEBUG thaliMobileNativeWrapper: 'listening 60468'
,2017-07-24 12:17:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"865e0c89-51c0-48eb-ac2b-3b0d600a3ee3","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 430 first peer is expected to be available
,2017-07-24 12:17:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"cd1e4715-ccf8-4ad2-afde-036d2e76fd8e","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 431 second peer is expected to be available
,2017-07-24 12:17:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"865e0c89-51c0-48eb-ac2b-3b0d600a3ee3","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 432 peer became unavailable
,2017-07-24 12:17:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"cd1e4715-ccf8-4ad2-afde-036d2e76fd8e","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 433 peer became unavailable
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:17:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:17:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:17:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:17:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:17:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 434 error should be null
,ok 435 error should be null
,# setup
,ok 436 ThaliMobile should be stopped
,# multiconnect failure - new peer is ignored (MPCF)
,2017-07-24 12:17:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
,# teardown
,ok 437 error should be null
ok 438 error should be null
,# setup
,ok 439 ThaliMobile should be stopped
,# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
,2017-07-24 12:17:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
,# teardown
,ok 440 error should be null
ok 441 error should be null
,# setup
,ok 442 ThaliMobile should be stopped
,# newAddressPort field (TCP_NATIVE)
,2017-07-24 12:17:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"35aec3fd-cf73-4a61-95f2-9c4dda2c4f33","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 443 peer discovered ,first time does not have new address
2017-07-24 12:17:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"35aec3fd-cf73-4a61-95f2-9c4dda2c4f33","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddres,sPort":false}'
ok 444 address has not been changed
2017-07-24 12:17:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"35aec3fd-cf73-4a61-95f2-9c4dda2c4f33","connectionType":"tcp","peerAvailable":true,"generation,":20,"newAddressPort":true}'
ok 445 new port handled correctly
2017-07-24 12:17:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"35aec3fd-cf73-4a61-95f2-9c4dda2c4f33","connectionType":"tcp","peerAvailable":tru,e,,"generation":20,"newAddressPort":true}'
ok 446 new host handled correctly
2017-07-24 12:17:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"35aec3fd-cf73-4a61-95f2-9c4dda2c4f33","connectionType":"tcp","peerAva,ilable":false,"generation":20,"newAddressPort":null}'
ok 447 newAddressPort is null for unavailable peers
,# teardown
,ok 448 error should be null
ok 449 error should be null
,# setup
,ok 450 ThaliMobile should be stopped
,# newAddressPort field (BLUETOOTH)
,2017-07-24 12:17:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort field (BLUETOOTH)''
,# teardown
,ok 451 error should be null
ok 452 error should be null
,# setup
,ok 453 ThaliMobile should be stopped
,# newAddressPort field (MPCF)
,ok 454 NOT IMPLEMENTED # SKIP
,# teardown
,ok 455 error should be null
ok 456 error should be null
,# setup
,ok 457 ThaliMobile should be stopped
,# newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)
,2017-07-24 12:17:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''
,# teardown
,ok 458 error should be null
ok 459 error should be null
,# setup
,ok 460 ThaliMobile should be stopped
,# #getPeerHostInfo - error when peer has not been discovered yet
,ok 461 should be equal
,# teardown
,ok 462 error should be null
ok 463 error should be null
,# setup
,ok 464 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)
,2017-07-24 12:17:15 - DEBUG CoordinatedClient: 'test was skipped, name: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''
,# teardown
,ok 465 error should be null
ok 466 error should be null
,# setup
,ok 467 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)
,2017-07-24 12:17:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 468 contains expected properties
ok 469 the same hostAddress
ok 470 the same portNumber
,# teardown
,2017-07-24 12:17:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 471 error should be null
,ok 472 error should be null
,# setup
,ok 473 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached wifi peer
,2017-07-24 12:17:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 474 contains expected properties
,ok 475 the same hostAddress
,ok 476 the same portNumber
,# teardown
,2017-07-24 12:17:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 477 error should be null
,ok 478 error should be null
,# setup
,ok 479 ThaliMobile should be stopped
,# #disconnect fails on wifi peers
,2017-07-24 12:17:16 - DEBUG thaliMobileNativeWrapper: 'listening 60469'
,2017-07-24 12:17:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c076e993-8043-4b82-badc-7765941f546a","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 480 Got specific error message
,# teardown
,2017-07-24 12:17:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c076e993-8043-4b82-badc-7765941f546a","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:17:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:17:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:17:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:17:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:17:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 481 error should be null
,ok 482 error should be null
,# setup
,ok 483 ThaliMobile should be stopped
,# #disconnect delegates native peers to the native wrapper
,2017-07-24 12:17:16 - DEBUG thaliMobileNativeWrapper: 'listening 60470'
2017-07-24 12:17:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"545869d8-14e1-4f3b-8ab7-89130dbd2e80","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
[ThaliCore] BrowserManager.disconnect peer:545869d8-14e1-4f3b-8ab7-89130dbd2e80
,ok 484 native wrapper `disconnect` called once
ok 485 native wrapper `disconnect` called with peer data
,# teardown
,2017-07-24 12:17:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"545869d8-14e1-4f3b-8ab7-89130dbd2e80","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-24 12:17:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:17:16 - INFO thaliMobile: 'Filtered out discoveryAdvert,isingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:17:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017,-07-24 12:17:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 12:17:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 486 error should be null
ok 487 error should be null
,# setup
,ok 488 ThaliMobile should be stopped
,# network changes emitted correctly
,2017-07-24 12:17:16 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes emitted correctly''
,# teardown
,ok 489 error should be null
ok 490 error should be null
,# setup
,ok 491 ThaliMobile should be stopped
,# network changes not emitted in started state
,2017-07-24 12:17:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in started state''
,# teardown
,ok 492 error should be null
ok 493 error should be null
,# setup
,ok 494 ThaliMobile should be stopped
,# network changes not emitted in stopped state
,2017-07-24 12:17:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in stopped state''
,# teardown
,ok 495 error should be null
ok 496 error should be null
,# setup
,ok 497 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on Android
,2017-07-24 12:17:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on Android''
,# teardown
,ok 498 error should be null
ok 499 error should be null
,# setup
,ok 500 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on iOS
,2017-07-24 12:17:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on iOS''
,# teardown
,ok 501 error should be null
ok 502 error should be null
,# setup
,ok 503 ThaliMobile should be stopped
,# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
,2017-07-24 12:17:19 - DEBUG CoordinatedClient: 'test was skipped, name: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''
,# teardown
,ok 504 error should be null
ok 505 error should be null
,# setup
,ok 506 ThaliMobile should be stopped
,# does not fire duplicate events after peer listener recreation
,2017-07-24 12:17:19 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not fire duplicate events after peer listener recreation''
,# teardown
,ok 507 error should be null
ok 508 error should be null
,# setup
,ok 509 ThaliMobile should be stopped
,# #stop should change peers
,2017-07-24 12:17:19 - DEBUG thaliMobileNativeWrapper: 'listening 60471'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C133458D-0FF3-416A-B986-38E2030635E2
[ThaliCore] Browser.startListening
2017-07-24 12:17:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 12:17:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"180ceabf-7239-426b-921c-96f720b4cabb","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 510 Peer availabilities has one entry for our connection type
,2017-07-24 12:17:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"193a2655-62ff-4cca-83a9-64681c0b213b","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 511 Peer availabilities has one entry for our connection type
,2017-07-24 12:17:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"180ceabf-7239-426b-921c-96f720b4cabb","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 12:17:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"193a2655-62ff-4cca-83a9-64681c0b213b","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:17:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 12:17:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,1,11],"networkType":"BOTH"}})'
,2017-07-24 12:17:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 12:17:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:17:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:17:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 12:17:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 512 No peers
,ok 513 No peers
,ok 514 No peers
,# teardown
,ok 515 error should be null
ok 516 error should be null
,# setup
,ok 517 ThaliMobile should be stopped
,# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
,2017-07-24 12:17:20 - DEBUG thaliMobileNativeWrapper: 'listening 60472'
2017-07-24 12:17:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"88f34c8a-bc98-4cf4-93d7-41e832a13048","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 518 1
ok 519 2
2017-07-24 12:17:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"045eae03-a604-427e-81bc-7864d7bcd66a","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-07-24 12:17:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"88f34c8a-bc98-4cf4-93d7-41e832a13048","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 12:17:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"045eae03-a604-427e-81bc-7864d7bcd66a","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:17:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:17:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:17:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:17:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:17:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 520 error should be null
,ok 521 error should be null
,# setup
,ok 522 ThaliMobile should be stopped
,# peer should be found once after listening and discovery started
,2017-07-24 12:17:20 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer should be found once after listening and discovery started''
,# teardown
,ok 523 error should be null
ok 524 error should be null
,# setup
,ok 525 ThaliMobile should be stopped
,# can get data from all participants
,2017-07-24 12:17:21 - DEBUG thaliMobileNativeWrapper: 'listening 60473'
ok 526 error should be null
ok 527 error should be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4961DB67-3624-4134-A11C-6B,F58A47872B", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:4961DB67-3624-4134-A11C-6BF58A47872B
2017-07-24 12:17:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive,":true}'
ok 528 error should be null
ok 529 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:5138BB49-C82C-45D8-B3E4-2F6BA646ECA8
[ThaliCore] Browser.startListening
2017-07-24 12:17:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
ok 530 error should be null
ok 531 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7146B875-BFA5-464A-88ED-B177AA3D7C16:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7146B875-BFA5-464A-88ED-B177AA3D7C16", generation: 0)
,2017-07-24 12:17:21 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"7146B875-BFA5-464A-88ED-B177AA3D7C16","generation":0}]'
,2017-07-24 12:17:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"7146B875-BFA5-464A-88ED-B177AA3D7C16","generation":0}'
,2017-07-24 12:17:21 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7146B875-BFA5-464A-88ED-B177AA3D7C16","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:17:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7146B875-BFA5-464A-88ED-B177AA3D7C16","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 12:17:21 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 7146B875-BFA5-464A-88ED-B177AA3D7C16 (syncValue: 0)'
,2017-07-24 12:17:21 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7146B875-BFA5-464A-88ED-B177AA3D7C16", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7146B875-BFA5-464A-88ED-B177AA3D7C16", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7146B875-BFA5-464A-88ED-B177AA3D7C16:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4", generation: 0)
2017-07-24 12:17:22 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4","generation":0}]'
2017-07-24 12:17:22 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4","generation":0}'
,2017-07-24 12:17:22 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-24 12:17:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F894B066-A1FC-4515-99B1-1CE0256E1FEC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F894B066-A1FC-4515-99B1-1CE0256E1FEC", generation: 0)
2017-07-24 12:17:22 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F894B066-A1FC-4515-99B1-1CE0256E1FEC","generation":0}]'
2017-07-24 12:17:22 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"F894B066-A1FC-4515-99B1-1CE0256E1FEC","generation":0}'
,2017-07-24 12:17:22 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"F894B066-A1FC-4515-99B1-1CE0256E1FEC","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-24 12:17:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"F894B066-A1FC-4515-99B1-1CE0256E1FEC","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4961DB67-3624-4134-A11C-6BF58A47872B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4961DB67-3624-4134-A11C-6BF58A47872B", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:7146B875-BFA5-464A-88ED-B177AA3D7C16:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:71,46B875-BFA5-464A-88ED-B177AA3D7C16:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "7146B875-BFA5-464A-88ED-B177AA3D7C16", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,146B875-BFA5-464A-88ED-B177AA3D7C16", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7146B875-BFA5-464A-88ED-B177AA3D7C16", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:7146B875-BFA5-464A-88ED-B177AA3D7C16:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:7146B875-BFA5-464A-88ED-B177AA3D7C16:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:7146B875-BFA5-464A-88ED-B177AA3D7C16:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "7146B875-BFA5-464A-88ED-B177AA3D7C16", generation: 0)
2017-07-24 12:17:23 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"7146B875-BFA5-464A-88ED-B177AA3D7C16","generation":0}]'
2017-07-24 12:17:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"7146B875-BFA5-464A-88ED-B177AA3D7C16","generation":0}'
,2017-07-24 12:17:23 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"7146B875-BFA5-464A-88ED-B177AA3D7C16","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-24 12:17:23 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"7146B875-BFA5-464A-88ED-B177AA3D7C16","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:7146B875-BFA5-464A-88ED-B177AA3D7C16:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:71,46B875-BFA5-464A-88ED-B177AA3D7C16:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "7146B875-BFA5-464A-88ED-B177AA3D7C16", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,146B875-BFA5-464A-88ED-B177AA3D7C16", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7146B875-BFA5-464A-88ED-B177AA3D7C16", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 12:17:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":"Peer is unavailable","portNumber":null}'
,2017-07-24 12:17:26 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4 (syncValue: 1)'
2017-07-24 12:17:26 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4", ge,neration: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnec,ted:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7146B875-BFA5-464A-88ED-B177AA3D7C16:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7146B875-BFA5-464A-88ED-B177AA3D7C16", generation: 0)
,2017-07-24 12:17:26 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"7146B875-BFA5-464A-88ED-B177AA3D7C16","generation":0}]'
,2017-07-24 12:17:26 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"7146B875-BFA5-464A-88ED-B177AA3D7C16","generation":0}'
,2017-07-24 12:17:26 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7146B875-BFA5-464A-88ED-B177AA3D7C16","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:17:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7146B875-BFA5-464A-88ED-B177AA3D7C16","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.deinit peer:7146B875-BFA5-464A-88ED-B177AA3D7C16:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60481
2017-07-24 12:17:28 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":null,"portNumber":60481,}'
,2017-07-24 12:17:28 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for F894B066-A1FC-4515-99B1-1CE0256E1FEC (syncValue: 2)'
2017-07-24 12:17:28 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "F894B066-A1FC-4515-99B1-1CE0256E1FEC", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F894B066-A1FC-4515-99B1-1CE0256E1FEC", ge,neration: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F894B066-A1FC-4515-99B1-1CE0256E1FEC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnec,ted:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [2, 3, 6, 11, 16]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:F894B066-A1FC-4515-99B1-1CE0256E1FEC:0 state: notConnected -> connecting
,2017-07-24 12:17:30 - DEBUG testUtils: 'Got response data'
2017-07-24 12:17:30 - DEBUG testUtils: 'Got end'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:7146B875-BFA5-464A-88ED-B177AA3D7C16:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "7146B875-BFA5-464A-88ED-B177AA3D7C16", generation: 0)
2017-07-24 12:17:31 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"7146B875-BFA5-464A-88ED-B177AA3D7C16","generation":0}]'
2017-07-24 12:17:31 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"7146B875-BFA5-464A-88ED-B177AA3D7C16","generation":0}'
,2017-07-24 12:17:31 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"7146B875-BFA5-464A-88ED-B177AA3D7C16","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-24 12:17:31 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7146B875-BFA5-464A-88ED-B177AA3D7C16","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A5A79C3E-823F-4844-9BBC-C713FFDB589B
[ThaliCore] Advertiser: session connected Peer(uuid: "4961DB67-3624-4134-A11C-6BF58A47872B", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:A5A79C3E-823F-4844-9BBC-C713FFDB589B state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F894B066-A1FC-4515-99B1-1CE0256E1FEC:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:60481
[ThaliCore] VirtualSocket.closeStreams() vsID:16
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] Session.disconnect() peer:6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4:0
[ThaliCore] VirtualSocket.closeStreams() vsID:16
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] TCPListener.deinit
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4", generation: 0)
,2017-07-24 12:17:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:F894B066-A1FC-4515-99B1-1CE0256E1FEC:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "F894B066-A1FC-4515-99B1-1CE0256E1FEC", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60485
,2017-07-24 12:17:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":null,"portNumber":60485}'
,2017-07-24 12:17:32 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 7146B875-BFA5-464A-88ED-B177AA3D7C16 (syncValue: 3)'
,2017-07-24 12:17:32 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7146B875-BFA5-464A-88ED-B177AA3D7C16", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "71,46B875-BFA5-464A-88ED-B177AA3D7C16", generation: 0)
,[ThaliCore] Session.deinit peer:6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4:0
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 12:17:33 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":"Peer is unavailable","portNumber":null}'
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F894B066-A1FC-4515-99B1-1CE0256E1FEC:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F894B066-A1FC-4515-99B1-1CE0256E1FEC:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [2, 3, 6, 11, 16, 17]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 12:17:33 - DEBUG testUtils: 'Got response data'
2017-07-24 12:17:33 - DEBUG testUtils: 'Got end'
ok 532 received all uuids
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A5A79C3E-823F-4844-9BBC-C713FFDB589B
,[ThaliCore] Session.session(_:peer:didChange:) peer:A5A79C3E-823F-4844-9BBC-C713FFDB589B state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A5A79C3E-823F-4844-9BBC-C713FFDB589B
[ThaliCore] Session.startOutputStream(with:) peer:A5A79C3E-823F-4844-9BBC-C713FFDB589B
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,8 [2, 3, 6, 11, 16, 17, 18]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F513D266-4360-4A67-8F33-8053B564FDAC
[ThaliCore] Advertiser: session connected Peer(uuid: "4961DB67-3624-4134-A11C-6BF58A47872B", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:F513D266-4360-4A67-8F33-8053B564FDAC state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:F513D266-4360-4A67-8F33-8053B564FDAC state: connecting -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "4961DB67-3624-4134-A11C-6BF58A47872B", generation: 0)
[ThaliCore] Advertis,erRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:F513D266-4360-4A67-8F33-8053B564FDAC
[ThaliCore] Adver,tiserRelay.deinit
[ThaliCore] Session.deinit peer:F513D266-4360-4A67-8F33-8053B564FDAC
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F513D266-4360-4A67-8F33-8053B564FDAC
[ThaliCore] Advertiser: session connected Peer(uuid: "4961DB67-3624-4134-A11C-6BF58A47872B", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:F513D266-4360-4A67-8F33-8053B564FDAC state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F513D266-4360-4A67-8F33-8053B564FDAC
,[ThaliCore] Session.session(_:peer:didChange:) peer:F513D266-4360-4A67-8F33-8053B564FDAC state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F513D266-4360-4A67-8F33-8053B564FDAC
[ThaliCore] Session.startOutputStream(with:) peer:F513D266-4360-4A67-8F33-8053B564FDAC
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [2, 3, 6, 11, 16, 17, 18, 19]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:17
[ThaliCore] VirtualSocket.closeStreams() vsID:17
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:17
[Th,aliCore] VirtualSocket.deinit vsID:17 [2, 3, 6, 11, 16, 18, 19]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRela,y.didSocketDisconnectHandler
,2017-07-24 12:17:56 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-24, 12:17:56 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"F894B066-A1FC-4515-99B1-1CE0256E1FEC","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Advertis,erManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:4961DB67-3624-4134-A11C-6BF58A47872B
2017-07-24 12:17:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":fal,se}'
2017-07-24 12:17:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-24 12,:,17:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 12:17:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:17:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 12:17:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:18
[ThaliCore] VirtualSocket.closeStreams() vsID:18
ok 533 error should be null
ok 534 error should be null
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:19
[ThaliCore] VirtualSocket.closeStreams() vsID:19
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:18
[ThaliCore] VirtualSocket.deinit vsID:18 [2, 3, 6, 11, 16, 19]
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:19
[ThaliCore] VirtualSocket.deinit vsID:19 [2, 3, 6, 11, 16]
,# setup
,ok 535 ThaliMobile should be stopped
,# test for data corruption
,2017-07-24 12:17:56 - DEBUG CoordinatedClient: 'test was skipped, name: 'test for data corruption''
,# teardown
,ok 536 error should be null
ok 537 error should be null
,# setup
,# #testThaliPeerAction - test getters
,ok 538 getPeerIdentifier
ok 539 getConnectionType
ok 540 getActionType
ok 541 getActionState
ok 542 getPskIdentity
ok 543 getPskKey
,# teardown
,# setup
,# #testThaliPeerAction - start and kill
,ok 544 initial state
,ok 545 after start
,2017-07-24 12:17:57 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 546 after kill
,# teardown
,# setup
,# #testThaliPeerAction - double start
,ok 547 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - start after kill
,2017-07-24 12:17:58 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 548 clean kill
,ok 549 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - make sure ids are unique
,ok 550 should not be equal
,# teardown
,# setup
,# #testThaliPeerAction - check that forever agent can be destroyed
,ok 551 forever agent should have it's own destroy method
ok 552 agent's destroy should be called
ok 553 agent's destroy should not be called again
ok 554 agent is destroyed
,# teardown
,# setup
,# Test PeerDictionary basic functionality
,ok 555 Entry counter must be 1
ok 556 Entry exists
ok 557 Size must be 1
ok 558 Entry counter must be 2
ok 559 Entry exists
ok 560 Size must be 2
ok 561 Entry counter must be 1
ok 562 Entry exists
ok 563 Size must be 3
ok 564 Entry counter must be, 2
ok 565 Entry exists
ok 566 Size must be 4
ok 567 Entry 1_1 should not be found
ok 568 Entry 1_1 does not exist
ok 569 Size must be 3
ok 570 Entry 1_2 should not be found
,ok 571 Entry 1_2 does not exist
,ok 572 Size must be 2
ok 573 should be equal
,ok 574 Entry 2_1 should not be found
ok 575 Entry 2_2 should not be found
ok 576 Entry 2_1 does not exist
ok 577 Entry 2_2 does not exist
ok 578 Size must be 0
,# teardown
,# setup
,# Test PeerDictionary with multiple entries.
,ok 579 Size must be100
,ok 580 Entries between 20 and MAXSIZE + 20 should exist
,ok 581 WAITING state entry should not be removed
,# teardown
,# setup
,# RESOLVED entries are removed before WAITING state entry.
,ok 582 Entries between 6 and MAXSIZE + 4 should exist
,ok 583 Size should be MAXSIZE
ok 584 Size should be MAXSIZE+6
,# teardown
,# setup
,# WAITING entries are removed before CONTROLLED_BY_POOL state entry.
,ok 585 WAITING state entry should not be removed
,ok 586 Waiting entries between 6 and MAXSIZE + 4 should exist
,ok 587 Size should be MAXSIZE
,ok 588 entryCounter should be MAXSIZE+6
,# teardown
,# setup
,# When CONTROLLED_BY_POOL entry is removed and kill is called.
,ok 589 Kill should be called once
,ok 590 Size should be MAXSIZE
,# teardown
,# setup
,# #ThaliPeerPoolDefault - single action
,ok 591 is an agent
,ok 592 enqueue is fine
ok 593 Everything should be off the queue
,# teardown
,# setup
,# #ThaliPeerPoolDefault - multiple actions
,ok 594 is an agent
ok 595 first enqueue is fine
,ok 596 is an agent
ok 597 second enqueue is fine
ok 598 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 599 Queue is empty
,# teardown
,# setup
,# #ThaliPeerPoolDefault - PSK Pool works
,ok 600 is an agent
ok 601 good enqueue
,ok 602 Identity should match
,2017-07-24 12:18:03 - DEBUG testUtils: 'Got response data'
,2017-07-24 12:18:03 - DEBUG testUtils: 'Got end'
,ok 603 Got expected response
,ok 604 Got psk call back
,# teardown
,2017-07-24 12:18:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #ThaliPeerPoolDefault - stop
,ok 605 is an agent
,ok 606 enqueue worked
ok 607 is an agent
,ok 608 enqueue 2 worked
,ok 609 enqueue is not available when stopped
,ok 610 start action is killed
,ok 611 killed action is still killed
,ok 612 enqueued action when stopped is killed
,ok 613 inQueue is empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that start verifies queue length
,ok 614 good start
,ok 615 good enqueue
,ok 616 queue is not empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - bad enqueues
,ok 617 null arg
,ok 618 wrong arg type
ok 619 wrong arg type
,# teardown
,# setup
,# #ThaliPeerPoolInterface - do not allow same object type
,ok 620 good enqueue
,ok 621 already enqueued
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
,ok 622 good enqueue
ok 623 2nd good enqueue
ok 624 we are in the pool
ok 625 We are out of the pool
ok 626 Action was killed
ok 627 The original kill was called too
ok 628 second item is still in queue
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
,ok 629 good enqueue
ok 630 first kill
ok 631 second NOOP kill
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that stop removes all actions
,ok 632 1st good enqueue
ok 633 2nd good enqueue
,ok 634 1st action is in the pool
ok 635 2nd action is in the pool
ok 636 1st action is out of the pool
ok 637 2st action is out of the pool
ok 638 pool is empty
,# teardown
,# setup
,# We reject unrecognized connection type
,2017-07-24 12:18:05 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 639 Got right error
,ok 640 Start should not be called
,ok 641 Kill should have been called at least once
,# teardown
,# setup
,# We reject unrecognized action type
,2017-07-24 12:18:06 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-24 12:18:06 - ERROR thaliPeerPoolOneAtATime: 'Got unsupported action type: blah'
,ok 642 Got right error
,ok 643 Start should not be called
,ok 644 Kill should have been called at least once
,# teardown
,# setup
,# One action on bluetooth
,2017-07-24 12:18:06 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 645 Got null
2017-07-24 12:18:06 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier,: peerID'
ok 646 is an agent
2017-07-24 12:18:06 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 647 Got killed at least once
,# teardown
,# setup
,# Two notification actions
,2017-07-24 12:18:06 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 648 Got Null
,ok 649 Got another null
,2017-07-24 12:18:06 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,ok 650 is an agent
,2017-07-24 12:18:06 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,2017-07-24 12:18:06 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 651 is an agent
,2017-07-24 12:18:06 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 652 Action 1 killed at least once
,ok 653 Action 1 went first
,ok 654 Action 2 killed at least once
,# teardown
,# setup
,# replicateThroughProblems
,2017-07-24 12:18:07 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
,2017-07-24 12:18:07 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
,2017-07-24 12:18:07 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 655 should have gotten null
,2017-07-24 12:18:07 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
,2017-07-24 12:18:07 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activity time out - noActivityTimeOut'
,ok 656 Should have stopped nicely
,2017-07-24 12:18:07 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
,2017-07-24 12:18:07 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButNotAvailable'
,ok 657 Still looking for null
,2017-07-24 12:18:07 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
,2017-07-24 12:18:07 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
,2017-07-24 12:18:07 - DEBUG thaliPeerPoolOneAtATime: 'Replication action failed badly so we are going to retry'
,2017-07-24 12:18:07 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
,2017-07-24 12:18:07 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
,2017-07-24 12:18:07 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 658 Yup, another null
,ok 659 We cloned!
,# teardown
,# setup
,# Replication goes first
,2017-07-24 12:18:07 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 660 Null 1
ok 661 (unnamed assert)
2017-07-24 12:18:07 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBlu,etooth, Peer Identifier: notificationAction'
ok 662 is an agent
ok 663 Null 3
ok 664 Replication not yet called
ok 665 Notification 2 not yet called
2017-07-24 12:18:07 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action, ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
2017-07-24 12:18:07 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidB,luetooth, Peer Identifier: replicationAction'
ok 666 is an agent
ok 667 Notification went first
ok 668 Notification 2 not called yet
,2017-07-24 12:18:07 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
2017-07-24 12:18:07 - DEBUG thaliPeerPoo,lOneAtATime: 'Got a replication response with no error!'
2017-07-24 12:18:07 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
ok 669 is, an agent
ok 670 Notification finished
ok 671 Replication finished
2017-07-24 12:18:07 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,# teardown
,# setup
,# wifi allows many parallel non-replication actions
,2017-07-24 12:18:08 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-24 12:18:08 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
ok 672 is an agent
ok 673 First does not throw
2017-07-24 12:18:08 - DEBUG thaliPeerPoolOneAtATime: 'Action ,Started Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
ok 674 is an agent
ok 675 Second does not throw
2017-07-24 12:18:08 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 594, Action Ty,pe: foo, Connection Type: tcp, Peer Identifier: 2'
truetruefalsetrue
,2017-07-24 12:18:08 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
truetruetruetrue
# teardown
,# setup
,# wifi allows no more than 2 simultaneous replication actions for same peerID
,2017-07-24 12:18:09 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2017-07-24 12:18:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
ok 676 is an agent
ok ,677 first ok
2017-07-24 12:18:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
ok 678 is an agent
ok 679 second ok
,ok 680 third ok
,2017-07-24 12:18:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
2017-07-24 12:18:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned, successfully from start - Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
2017-07-24 12:18:09 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
2017-07-24 12:18:09 - DEBUG thaliPeerPoo,lOneAtATime: 'Got a replication response with no error!'
# teardown
,# setup
,# Client to server request coordinated
,2017-07-24 12:18:09 - DEBUG thaliMobileNativeWrapper: 'listening 60491'
ok 681 error should be null
,ok 682 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9217F548-C7E8-4106-A99F-8C3D222B81B7", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:9217F548-C7E8-4106-A99F-8C3D222B81B7
,2017-07-24 12:18:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7C91E292-3CF0-47D2-ADE9-B63906DF4EBF
[ThaliCore] Browser.startListening
,2017-07-24 12:18:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4", generation: 0)
2017-07-24 12:18:09 - INFO testThaliNotification: 'startListeningForAdvertisements'
,2017-07-24 12:18:09 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4","generation":0}]'
,2017-07-24 12:18:09 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4","generation":0}'
,2017-07-24 12:18:09 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:18:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 12:18:09 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4 (syncValue: 4)'
,2017-07-24 12:18:09 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:836E24B5-833B-49F1-B94E-975EDDFDC93D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "836E24B5-833B-49F1-B94E-975EDDFDC93D", generation: 0)
2017-07-24 12:18:11 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"836E24B5-833B-49F1-B94E-975EDDFDC93D","generation":0}]'
2017-07-24 12:18:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"836E24B5-833B-49F1-B94E-975EDDFDC93D","generation":0}'
,2017-07-24 12:18:11 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"836E24B5-833B-49F1-B94E-975EDDFDC93D","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-24 12:18:11 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"836E24B5-833B-49F1-B94E-975EDDFDC93D","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A5A79C3E-823F-4844-9BBC-C713FFDB589B
[ThaliCore] Session.startOutputStream(with:) peer:A5A79C3E-823F-4844-9BBC-C713FFDB589B
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,0 [2, 3, 6, 11, 16, 20]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=2 "No such file or directory" UserInfo={NSLocalizedDescription=No such file or directory, NSLocalizedFailureReason=Error ,in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:20
[ThaliCore] VirtualSocket.closeStreams() vsID:20
[ThaliCore] Advert,iserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:20
[ThaliCore] VirtualSocket.deinit vsID:20 [2, 3, 6, 11, 16]
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:24A433EC-908C-42BD-8EC8-ADC70B763155
[ThaliCore] Advertiser: session connected Peer(uuid: "9217F548-C7E8-4106-A99F-8C3D222B81B7", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:24A433EC-908C-42BD-8EC8-ADC70B763155 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6EE1358B-49C1-44F9-AE2B-8B17E5A90B39:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6EE1358B-49C1-44F9-AE2B-8B17E5A90B39", generation: 0)
2017-07-24 12:18:11 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"6EE1358B-49C1-44F9-AE2B-8B17E5A90B39","generation":0}]'
2017-07-24 12:18:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"6EE1358B-49C1-44F9-AE2B-8B17E5A90B39","generation":0}'
,2017-07-24 12:18:11 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"6EE1358B-49C1-44F9-AE2B-8B17E5A90B39","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-24 12:18:11 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6EE1358B-49C1-44F9-AE2B-8B17E5A90B39","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9217F548-C7E8-4106-A99F-8C3D222B81B7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9217F548-C7E8-4106-A99F-8C3D222B81B7", generation: 0)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F513D266-4360-4A67-8F33-8053B564FDAC
[ThaliCore] Session.startOutputStream(with:) peer:F513D266-4360-4A67-8F33-8053B564FDAC
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:21 [2, 3, 6, 11, 16, 21]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=2 "No such file or directory" UserInfo={NSLocalizedDescription=No such file or directory, NSLocalizedFailureReason=Error ,in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:21
[ThaliCore] VirtualSocket.closeStreams() vsID:21
[ThaliCore] Advert,iserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:21
[ThaliCore] VirtualSocket.deinit vsID:21 [2, 3, 6, 11, 16]
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4", generation: 0)
2017-07-24 12:18:11 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4","generation":0}]'
2017-07-24 12:18:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4","generation":0}'
,2017-07-24 12:18:11 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-24 12:18:11 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-24 12:18:11 - WARN thaliNotificationClient: 'peer is not available'
,[ThaliCore] Session.session(_:peer:didChange:) peer:6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:67,49A33F-EC4C-44D3-9AD7-D83F9D71FFE4:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,749A33F-EC4C-44D3-9AD7-D83F9D71FFE4", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 12:18:12 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":"Peer is unavailable","portNumber":null}'
,2017-07-24 12:18:12 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 836E24B5-833B-49F1-B94E-975EDDFDC93D (syncValue: 5)'
,2017-07-24 12:18:12 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "836E24B5-833B-49F1-B94E-975EDDFDC93D", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "836E24B5-833B-49F1-B94E-975EDDFDC93D", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:836E24B5-833B-49F1-B94E-975EDDFDC93D:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 12:18:12 - DEBUG thaliPeerPoolDefault: 'Got err   Peer is unavailable'
,[ThaliCore] Session.deinit peer:6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:836E24B5-833B-49F1-B94E-975EDDFDC93D:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:24A433EC-908C-42BD-8EC8-ADC70B763155
,[ThaliCore] Session.session(_:peer:didChange:) peer:24A433EC-908C-42BD-8EC8-ADC70B763155 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:24A433EC-908C-42BD-8EC8-ADC70B763155
[ThaliCore] Session.startOutputStream(with:) peer:24A433EC-908C-42BD-8EC8-ADC70B763155
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:22 [2, 3, 6, 11, 16, 22]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:24A433EC-908C-42BD-8EC8-ADC70B763155
[ThaliCore] Session.startOutputStream(with:) peer:24A433EC-908C-42BD-8EC8-ADC70B763155
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,3 [2, 3, 6, 11, 16, 22, 23]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:22
[ThaliCore] VirtualSocket.closeStreams() vsID:22
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandl,er disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:22
[ThaliCore] VirtualSocket.deinit vsID:22 [2, 3, 6, 11, 16, 23]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.so,cketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:23
,[ThaliCore] VirtualSocket.closeStreams() vsID:23
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F4A6FA35-7039-4607-8510-571C8926B0EE
[ThaliCore] Advertiser: session connected Peer(uuid: "9217F548-C7E8-4106-A99F-8C3D222B81B7", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:F4A6FA35-7039-4607-8510-571C8926B0EE state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:836E24B5-833B-49F1-B94E-975EDDFDC93D:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:836E24B5-833B-49F1-B94E-975EDDFDC93D:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "836E24B5-833B-49F1-B94E-975EDDFDC93D", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60501
2017-07-24 12:18:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5","error":null,"portNumber":60501,}'
,2017-07-24 12:18:15 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 6EE1358B-49C1-44F9-AE2B-8B17E5A90B39 (syncValue: 6)'
2017-07-24 12:18:15 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "6EE1358B-49C1-44F9-AE2B-8B17E5A90B39", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6EE1358B-49C1-44F9-AE2B-8B17E5A90B39", ge,neration: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6EE1358B-49C1-44F9-AE2B-8B17E5A90B39:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnec,ted:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:836E24B5-833B-49F1-B94E-975EDDFDC93D:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:836E24B5-833B-49F1-B94E-975EDDFDC93D:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:24 [2, 3, 6, 11, 16, 23, 24]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandl,er
,2017-07-24 12:18:16 - INFO testThaliNotification: 'PeerAdvertisesDataForUs:MPCF, 127.0.0.1, 127.0.0.1, 60501,836E24B5-833B-49F1-B94E-975EDDFDC93D'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:836E24B5-833B-49F1-B94E-975EDDFDC93D:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:24
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:24
[ThaliCore] VirtualSocket.deinit vsID:24 [2, 3, 6, 11, 16, 23]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:836E24B5-833B-49F1-B94E-975EDDFDC93D:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:25 [2, 3, 6, 11, 16, 23, 25]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:25
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:25
,[ThaliCore] VirtualSocket.deinit vsID:25 [2, 3, 6, 11, 16, 23]
,[ThaliCore] Session.session(_:peer:didChange:) peer:6EE1358B-49C1-44F9-AE2B-8B17E5A90B39:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F4A6FA35-7039-4607-8510-571C8926B0EE
,[ThaliCore] Session.session(_:peer:didChange:) peer:F4A6FA35-7039-4607-8510-571C8926B0EE state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A5A79C3E-823F-4844-9BBC-C713FFDB589B
[ThaliCore] Session.startOutputStream(with:) peer:A5A79C3E-823F-4844-9BBC-C713FFDB589B
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:26 [2, 3, 6, 11, 16, 23, 26]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:26
[ThaliCore] VirtualSocket.closeStreams() vsID:26
[ThaliCore] Advertiser,Relay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:26
[ThaliCore] VirtualSocket.deinit vsID:26 [2, 3, 6, 11, 16, 23]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F4A6FA35-7039-4607-8510-571C8926B0EE
[ThaliCore] Session.startOutputStream(with:) peer:F4A6FA35-7039-4607-8510-571C8926B0EE
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:27 [2, 3, 6, 11, 16, 23, 27]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F513D266-4360-4A67-8F33-8053B564FDAC
[ThaliCore] Session.startOutputStream(with:) peer:F513D266-4360-4A67-8F33-8053B564,FDAC
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:28 [2, 3, 6, 11, 16, 23, 27, 28]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() function})
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:28
,[ThaliCore] VirtualSocket.closeStreams() vsID:28
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:28
,[ThaliCore] VirtualSocket.deinit vsID:28 [2, 3, 6, 11, 16, 23, 27]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F4A6FA35-7039-4607-8510-571C8926B0EE
,[ThaliCore] Session.startOutputStream(with:) peer:F4A6FA35-7039-4607-8510-571C8926B0EE
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:29 [2, 3, 6, 11, 16, 23, 27, 29]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:27
[ThaliCore] VirtualSocket.closeStreams() vsID:27
[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:27
[ThaliCore] VirtualSocket.deinit vsID:27 [2, 3, 6, 11, 16, 23, 29]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError,:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:F513D266-4360-4A67-8F33-8053B564FDAC state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "4961DB67-3624-4134-A11C-6BF58A47872B", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:F513D266-4360-4A67-8F33-8053B564FDAC
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:29
[ThaliCore] VirtualSocket.closeStreams() vsID:29
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:29
[ThaliCore] VirtualSocket.deinit vsID:29 [2, 3, 6, 11, 16, 23]
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:F513D266-4360-4A67-8F33-8053B564FDAC
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A5A79C3E-823F-4844-9BBC-C713FFDB589B
[ThaliCore] Session.startOutputStream(with:) peer:A5A79C3E-823F-4844-9BBC-C713FFDB589B
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:30 [2, 3, 6, 11, 16, 23, 30]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:30
[ThaliCore] VirtualSocket.closeStreams() vsID:30
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:30
[ThaliCore] VirtualSocket.deinit vsID:30 [2, 3, 6, 11, 16, 23]
,[ThaliCore] Session.session(_:peer:didChange:) peer:A5A79C3E-823F-4844-9BBC-C713FFDB589B state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "4961DB67-3624-4134-A11C-6BF58A47872B", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6EE1358B-49C1-44F9-AE2B-8B17E5A90B39:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:6EE1358B-49C1-44F9-AE2B-8B17E5A90B39:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "6EE1358B-49C1-44F9-AE2B-8B17E5A90B39", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60511
2017-07-24 12:18:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6","error":null,"portNumber":60511,}'
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:6EE1358B-49C1-44F9-AE2B-8B17E5A90B39:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6EE1358B-49C1-44F9-AE2B-8B17E5A90B39:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:31 [2, 3, 6, 11, 16, 23, 31]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 12:18:19 - INFO testThaliNotification: 'PeerAdvertisesDataForUs:MPCF, 127.0.0.1, 127.0.0.1, 60511,6EE1358B-49C1-44F9-AE2B-8B17E5A90B39'
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:6EE1358B-49C1-44F9-AE2B-8B17E5A90B39:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:31
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:31
[ThaliCore] VirtualSocket.deinit vsID:31 [2, 3, 6, 11, 16, 23]
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) pee,r:6EE1358B-49C1-44F9-AE2B-8B17E5A90B39:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:32 [2, 3, 6, 11, 16, 23, 32]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:32
[ThaliCore] VirtualSocket.closeStreams() vsID:32
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:32
[Th,aliCore] VirtualSocket.deinit vsID:32 [2, 3, 6, 11, 16, 23]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.di,dSocketDisconnectHandler
,ok 683 Peer made successful https requests to all peers
,ok 684 Peer received right amount of https requests
,ok 685 HTTPS server received zero PSK Identities. Count:0
,# teardown
,2017-07-24 12:18:20 - INFO testThaliNotification: 'Participants:3 Peers Replied to us:2 Peers requested to:2'
,2017-07-24 12:18:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"836E24B5-833B-49F1-B94E-975EDDFDC93D","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-24, 12:18:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"6EE1358B-49C1-44F9-AE2B-8B17E5A90B39","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Advertis,erManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:9217F548-C7E8-4106-A99F-8C3D222B81B7
2017-07-24 12:18:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":fal,se}'
2017-07-24 12:18:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-24 12,:,18:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 12:18:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:18:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 12:18:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:18:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:18:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,# Test BEACONS_RETRIEVED_AND_PARSED locally
,ok 686 peerIdentifier should match
,ok 687 generation should match
,ok 688 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 689 good beacon
,ok 690 good preAmble
,ok 691 public keys match!
,ok 692 must return null after successful call
,ok 693 Once start returns the action should be in KILLED state
,# teardown
,2017-07-24 12:18:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test HTTP_BAD_RESPONSE locally
,ok 694 Response should be HTTP_BAD_RESPONSE
,ok 695 must return null after successful call
,# teardown
,2017-07-24 12:18:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test NETWORK_PROBLEM locally
,ok 696 Response should be NETWORK_PROBLEM
,ok 697 reject reason should be: Could not establish TCP connection
,# teardown
,2017-07-24 12:18:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails when getPeerHostInfo fails
,ok 698 Resolution should be BAD_PEER
,ok 699 correct error message
,# teardown
,2017-07-24 12:18:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the start two times
,ok 700 Call start once
,ok 701 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 702 must return null after successful call.
,# teardown
,2017-07-24 12:18:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill before calling the start
,ok 703 Should be Killed
ok 704 Start after killed
,# teardown
,2017-07-24 12:18:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill immediately after the start
,ok 705 Should be KILLED
,ok 706 must return null after successful kill
,# teardown
,2017-07-24 12:18:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill while waiting a response from the server
,ok 707 Should be KILLED
ok 708 must return null after successful kill
,# teardown
,2017-07-24 12:18:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test to exceed the max content size locally
,ok 709 HTTP_BAD_RESPONSE should be response when content size is exceeded
ok 710 must return null after successful call
,# teardown
,2017-07-24 12:18:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Close the server socket while the client is waiting a response from the server. Local test.
,2017-07-24 12:18:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 711 Should be NETWORK_PROBLEM caused closing server socket
ok 712 Should be Could not establish TCP connection
,# teardown
,# setup
,# Close the client socket while the client is waiting a response from the server. Local test.
,ok 713 Should be NETWORK_PROBLEM caused closing client socket
ok 714 Should be Could not establish TCP connection
,# teardown
,2017-07-24 12:18:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #generatePreambleAndBeacons bad args
,ok 715 publicKeysToNotify cannot be null
,ok 716 ecdh for local device cannot be null
,ok 717 milliseconds cannot be less than 0
,ok 718 milliseconds cannot be 0
,ok 719 milliseconds cannot be greater than one_day
,# teardown
,# setup
,# #generatePreambleAndBeacons empty keys to notify
,ok 720 should be equal
,# teardown
,# setup
,# #generatePreambleAndBeacons multiple keys to notify
,ok 721 should be equal
,ok 722 should be equal
,ok 723 (unnamed assert)
,ok 724 should be equal
,# teardown
,# setup
,# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
,ok 725 should throw
,# teardown
,# setup
,# #parseBeacons invalid expiration in beaconStreamWithPreAmble
,ok 726 Preamble expiration must be a 64 bit integer
,# teardown
,# setup
,# #parseBeacons expiration out of range lower
,ok 727 Expiration out of range
,# teardown
,# setup
,# #parseBeacons expiration out of range lower
,ok 728 Expiration out of range
,# teardown
,# setup
,# #parseBeacons no beacons returns null
,ok 729 should be equal
,# teardown
,# setup
,# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
,ok 730 Malformed encrypted beacon key ID
,# teardown
,# setup
,# #parseBeacons addressBookCallback fails decrypt
,ok 731 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns no matches
,ok 732 should be equal
,ok 733 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns spurious match
,ok 734 should be equal
,ok 735 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns public key
,ok 736 right number of calls to address book
,ok 737 good preAmble
ok 738 good unencryptedKeyId
,ok 739 good beacon
,# teardown
,# setup
,# validate generatePskIdentityField
,ok 740 decoded buffers match
,# teardown
,# setup
,# validate generatePskSecret
,ok 741 secrets match
,# teardown
,# setup
,# validate generatePskSecrets
,ok 742 Matching numbers
,ok 743 We have an entry!
,ok 744 keys match
,ok 745 secrets match
,ok 746 We have an entry!
,ok 747 keys match
,ok 748 secrets match
,ok 749 We have an entry!
,ok 750 keys match
ok 751 secrets match
,# teardown
,# setup
,# validate generateBeaconStreamAndSecrets
,ok 752 Streams have same length
,ok 753 matching size
,ok 754 keys match
,ok 755 secrets match
,# teardown
,# setup
,# Add two Peers.
,ok 756 should be equal
,ok 757 peerDictionalty contains 2 peers
,ok 758 bluetooth peer's notification has correct connection type
,ok 759 tcp peer's notification has correct connection type
,2017-07-24 12:18:43 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,2017-07-24 12:18:43 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-24 12:18:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# TCP_NATIVE peer loses DNS
,ok 760 notification peer dictionary contains exactly 1 peer
,2017-07-24 12:18:44 - WARN thaliNotificationClient: 'peer is not available'
,ok 761 notification peer dictionary does not contain any peers
,2017-07-24 12:18:44 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-24 12:18:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Received beacons with no values for us
,ok 762 entry exists
,ok 763 entry is resolved
,# teardown
,2017-07-24 12:18:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Notification action killed with a superseded
,ok 764 Action should be KILLED
,ok 765 Peer state should be RESOLVED
,# teardown
,2017-07-24 12:18:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally
,ok 766 hostAddress must match
,ok 767 portNumber must match
,ok 768 suggestedTCPTimeout must match
,ok 769 connectionType must match
,ok 770 peerIDs must match
,# teardown
,2017-07-24 12:18:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 771 Correct error
,# teardown
,2017-07-24 12:18:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally using ThaliPeerPoolDefault
,ok 772 hostAddress must match
,ok 773 portNumber must match
,ok 774 suggestedTCPTimeout must match
,ok 775 connectionType must match
,ok 776 peerIds must match
,# teardown
,2017-07-24 12:18:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails because of a bad hostname.
,2017-07-24 12:18:49 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 777 action should be resolved with NETWORK_PROBLEM error
,2017-07-24 12:18:49 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 778 action should be resolved with NETWORK_PROBLEM error
,2017-07-24 12:18:49 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 779 action should be resolved with NETWORK_PROBLEM error
,2017-07-24 12:18:50 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 780 action should be resolved with NETWORK_PROBLEM error
ok 781 correct number of requests
ok 782 correct number of failures
ok 783 correct final peer state
,# teardown
,2017-07-24 12:18:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# hostaddress is removed when the action is running. 
,2017-07-24 12:18:53 - WARN thaliNotificationClient: 'peer is not available'
2017-07-24 12:18:53 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 784 peerDictionary should become empty
,# teardown
,2017-07-24 12:18:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notificationClient does not retry action with BAD_PEER resolution
,2017-07-24 12:18:53 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 785 failed with expected error
ok 786 peer state should be RESOLVED
,# teardown
,2017-07-24 12:18:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notification client correctly handles peer availability changes of the same peer
,2017-07-24 12:18:54 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 787 First action failed
,ok 788 second action killed
# teardown
,2017-07-24 12:18:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Client to server request locally
,ok 789 secrets are equal
,ok 790 Public key matches with the server key
,ok 791 hostAddress must match
,ok 792 portNumber must match
,ok 793 suggestedTCPTimeout must match
,ok 794 connectionType must match
,# teardown
,2017-07-24 12:18:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache clean and expiration
,ok 795 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
,ok 796 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
,ok 797 All entries should be expired after 1 second
# teardown
,2017-07-24 12:18:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache getSecret and getPublic
,ok 798 All keys need to be available in the cache
,ok 799 All entries should be expired after 1 second
# teardown
,2017-07-24 12:18:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache multiple entries
,ok 800 Size of the cache should be 2
ok 801 Cache doesn't contain dictionary1
,ok 802 Size of the cache should be 1
ok 803 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
,2017-07-24 12:19:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start and stop ThaliNotificationServer
,ok 804 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
ok 805 ThaliMobile.StopAdvertisingAndListeningshould be called once
,# teardown
,2017-07-24 12:19:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty array to ThaliNotificationServer.start
,ok 806 StartUpdateAdvertisingAndListening should not be called
,ok 807 ThaliMobile.StopAdvertisingAndListening should be called once
,ok 808 no error
ok 809 should be 204
# teardown
,2017-07-24 12:19:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass a string to ThaliNotificationServer.start
,ok 810 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-24 12:19:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty parameter to ThaliNotificationServer.start
,ok 811 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-24 12:19:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons
,ok 812 no error
,ok 813 should be 200
,ok 814 should be equal
,ok 815 should be equal
,ok 816 (unnamed assert)
,ok 817 no error
,ok 818 should be 204
,# teardown
,2017-07-24 12:19:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons (no keys)
,ok 819 error should be null
ok 820 should be 204
# teardown
,2017-07-24 12:19:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeaconsbefore calling start
,ok 821 should be 404
# teardown
,2017-07-24 12:19:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure peerDictionaryKey is reasonable
,ok 822 equal keys
ok 823 not equal connection type
ok 824 same connection type, different buffer
,# teardown
,# setup
,# Make sure start works
,2017-07-24 12:19:06 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 825 First start and on called correctly
,# teardown
,# setup
,# Make sure stop works
,ok 826 second cleared dictionary
,2017-07-24 12:19:07 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 827 First start and on called correctly
,ok 828 First stop and removeListener called correctly
ok 829 first action kill called
ok 830 second action kill called
ok 831 first cleared dictionary
,ok 832 first cleared pool
,ok 833 second cleared dictionary
,ok 834 second cleared pool
,# teardown
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 835 Correct error
,# teardown
,# setup
,# Simple peer event
,2017-07-24 12:19:08 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 836 listener has been set
,ok 837 peer dictionary has expected number of entries
,ok 838 Dictionary and pool have same action
,ok 839 ads match
,ok 840 PouchDB matches
,ok 841 DB Names match
,ok 842 public keys match
,ok 843 peer dictionary has expected number of entries
,ok 844 Dictionary and pool have same action
,ok 845 ads match
,ok 846 PouchDB matches
,ok 847 DB Names match
,ok 848 public keys match
,2017-07-24 12:19:08 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
,ok 849 start called once
,ok 850 One entry left
,ok 851 Dictionary and pool have same action
,ok 852 Start never called
,ok 853 Kill called once
,ok 854 no entries left
,ok 855 Third action is dead
,ok 856 peer dictionary has expected number of entries
,ok 857 Dictionary and pool have same action
,ok 858 ads match
,ok 859 PouchDB matches
,ok 860 DB Names match
,ok 861 public keys match
,# teardown
,# setup
,# Coordinated pull replication from notification test
,2017-07-24 12:19:09 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-24 12:19:09 - DEBUG thaliMobileNativeWrapper: 'listening 60564'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:EDE36A20-3EDF-4903-B9FE-AAFEF64DCF7D
[ThaliCore] Browser.startListening
,2017-07-24 12:19:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "560FF751-846E-4A58-8A52-A4E2B97186CC", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:560FF751-846E-4A58-8A52-A4E2B97186CC
,2017-07-24 12:19:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "560FF751-846E-4A58-8A52-A4E2B97186CC", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7982C450-B190-41BA-9C3F-1E4EBCCE4055
[ThaliCore] Advertiser: session connected Peer(uuid: "560FF751-846E-4A58-8A52-A4E2B97186CC", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:7982C450-B190-41BA-9C3F-1E4EBCCE4055 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B358F577-9A2C-4F71-9BC2-6A69E0B99696:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B358F577-9A2C-4F71-9BC2-6A69E0B99696", generation: 0)
2017-07-24 12:19:11 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B358F577-9A2C-4F71-9BC2-6A69E0B99696","generation":0}]'
2017-07-24 12:19:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"B358F577-9A2C-4F71-9BC2-6A69E0B99696","generation":0}'
,2017-07-24 12:19:11 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B358F577-9A2C-4F71-9BC2-6A69E0B99696","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-24 12:19:11 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B358F577-9A2C-4F71-9BC2-6A69E0B99696","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-24 12:19:11 - DEBUG thaliMobileNativeWrapper: 'Issuing multi,Connect for B358F577-9A2C-4F71-9BC2-6A69E0B99696 (syncValue: 7)'
2017-07-24 12:19:11 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B358F577-9A2C-4F71,-9BC2-6A69E0B99696", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B358F577-9A2C-4F71-9BC2-6A69E0B99696", generation: 0)
[ThaliCore] Session.init(session:identifier:connected,:,notConnected:) peer:B358F577-9A2C-4F71-9BC2-6A69E0B99696:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E9586F70-5B36-4872-8956-BF5C544C75F6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E9586F70-5B36-4872-8956-BF5C544C75F6", generation: 0)
,2017-07-24 12:19:11 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"E9586F70-5B36-4872-8956-BF5C544C75F6","generation":0}]'
2017-07-24 12:19:11 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"E9586F70-5B36-4872-8956-BF5C544C75F6","generation":0}'
,2017-07-24 12:19:11 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"E9586F70-5B36-4872-8956-BF5C544C75F6","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:19:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"E9586F70-5B36-4872-8956-BF5C544C75F6","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:41CD5606-68A0-4B38-BB1E-5F21BA470708
[ThaliCore] Advertiser: session connected Peer(uuid: "560FF751-846E-4A58-8A52-A4E2B97186CC", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:41CD5606-68A0-4B38-BB1E-5F21BA470708 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:B358F577-9A2C-4F71-9BC2-6A69E0B99696:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B358F577-9A2C-4F71-9BC2-6A69E0B99696:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B358F577-9A2C-4F71-9BC2-6A69E0B99696:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "B358F577-9A2C-4F71-9BC2-6A69E0B99696", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60567
2017-07-24 12:19:14 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"7","error":null,"portNumber":60567,}'
2017-07-24 12:19:14 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E9586F70-5B36-4872-8956-BF5C544C75F6 (syncValue: 8)'
,2017-07-24 12:19:14 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E9586F70-5B36-4872-8956-BF5C544C75F6", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E9586F70-5B36-4872-8956-BF5C544C75F6", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E9586F70-5B36-4872-8956-BF5C544C75F6:0
[Thali,Core] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7982C450-B190-41BA-9C3F,-1E4EBCCE4055
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B358F577-9A2C-4F71-9BC2-6A69E0B99696:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:7982C450-B190-41BA-9C3F-1E4EBCCE4055 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B358F577-9A2C-4F71-9BC2-6A69E0B99696:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:33 [2, 3, 6, 11, 16, 23, 33]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7982C450-B190-41BA-9C3F-1E4EBCCE4055
[ThaliCore] Session.startOutputStream(with:) peer:7982C450-B190-41BA-9C3F-1E4EBCCE4055
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:34 [2, 3, 6, 11, 16, 23, 33, 34]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:33
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:33
[ThaliCore] VirtualSocket.deinit vsID:33 [2, 3, 6, 11, 16, 23, 34]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B358F577-9A2C-4F71-9BC2-6A69E0B99696:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B358F577-9A2C-4F71-9BC2-6A69E0B99696:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:35 [2, 3, 6, 11, 16, 23, 34, 35]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsH,andler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:34
[ThaliCore] VirtualSocket.closeStreams() vsID:34
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:34
[ThaliCore] VirtualSocket.deinit vsID:34 [2, 3, 6, 11, 16, 23, 35]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:,withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7982C450-B190-41BA-9C3F-1E4EBCCE4055
[ThaliCore] Session.startOutputStream(with:) peer:7982C450-B190-41BA-9C3F-1E4EBCCE4055
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:36 [2, 3, 6, 11, 16, 23, 35, 36]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:E9586F70-5B36-4872-8956-BF5C544C75F6:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:41CD5606-68A0-4B38-BB1E-5F21BA470708
,[ThaliCore] Session.session(_:peer:didChange:) peer:41CD5606-68A0-4B38-BB1E-5F21BA470708 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:41CD5606-68A0-4B38-BB1E-5F21BA470708
[ThaliCore] Session.startOutputStream(with:) peer:41CD5606-68A0-4B38-BB1E-5F21BA470708
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:37 [2, 3, 6, 11, 16, 23, 35, 36, 37]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-24 12:19:14 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B358F577-9A2C-4F71-9BC2-6A69E0B99696:0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:37
[ThaliCore] VirtualSocket.closeStreams() vsID:37
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:37
[ThaliCore] VirtualSocket.deinit vsID:37 [2, 3, 6, 11, 16, 23, 35, 36]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnec,t(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:41CD5606-68A0-4B38-BB1E-5F21BA470708
[ThaliCore] Session.startOutputStream(with:) peer:41CD5606-68A0-4B38-BB1E-5F21BA470708
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:38 [2, 3, 6, 11, 16, 23, 35, 36, 38]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B358F577-9A2C-4F71-9BC2-6A69E0B99696:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:39 [2, 3, 6, 11, 16, 23, 35, 36, 38, 39]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:41CD5606-68A0-4B38-BB1E-5F21BA470708
[ThaliCore] Session.startOutputStream(with:) peer:41CD5606-68A0-4B38-BB1E-5F21BA470708
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:40 [2, 3, 6, 11, 16, 23, 35, 36, 38, 39, 40]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7982C450-B190-41BA-9C3F-1E4EBCCE4055
[ThaliCore] Session.startOutputStream(with:) peer:7982C450-B190-41BA-9C3F-1E4EBCCE4055
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:41 [2, 3, 6, 11, 16, 23, 35, 36, 38, 39, 40, 41]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B358F577-9A2C-4F71-9BC2-6A69E0B99696:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B358F577-9A2C-4F71-9BC2-6A69E0B99696:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:42 [2, 3, 6, 11, 16, 23, 35, 36, 38, 39, 40, 41, 42]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:41CD5606-68A0-4B38-BB1E-5F21BA470708
[ThaliCore] Session.startOutputStream(with:) peer:41CD5606-68A0-4B38-BB1E-5F21BA470708
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:43 [2, 3, 6, 11, 16, 23, 35, 36, 38, 39, 40, 41, 42, 43]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B358F577-9A2C-4F71-9BC2-6A69E0B99696:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B358F577-9A2C-4F71-9BC2-6A69E0B99696:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:44 [2, 3, 6, 11, 16, 23, 35, 36, 38, 39, 40, 41, 42, 43, 44]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:41CD5606-68A0-4B38-BB1E-5F21BA470708
,[ThaliCore] Session.startOutputStream(with:) peer:41CD5606-68A0-4B38-BB1E-5F21BA470708
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:45 [2, 3, 6, 11, 16, 23, 35, 36, 38, 39, 40, 41, 42, 43, 44, 45]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7982C450-B190-41BA-9C3F-1E4EBCCE4055
[ThaliCore] Session.startOutputStream(with:) peer:7982C450-B190-41BA-9C3F-1E4EBCCE4055
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4,6 [2, 3, 6, 11, 16, 23, 35, 36, 38, 39, 40, 41, 42, 43, 44, 45, 46]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:41CD5606-68A0-4B38-BB1E-5F21BA470708
[ThaliCore] Session.startOutputStream(with:) peer:41CD5606-68A0-4B38-BB1E-5F21BA470708
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:47 [2, 3, 6, 11, 16, 23, 35, 36, 38, 39, 40, 41, 42, 43, 44, 45, 46, 47]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7982C450-B190-41BA-9C3F-1E4EBCCE4055
[ThaliCore] Session.startOutputStream(with:) peer:7982C450-B190-41BA-9C3F-1E4EBCCE4055
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4,8 [2, 3, 6, 11, 16, 23, 35, 36, 38, 39, 40, 41, 42, 43, 44, 45, 46, 47, 48]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:45
[ThaliCore] VirtualSocket.closeStreams() vsID:45
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:45
,[ThaliCore] VirtualSocket.deinit vsID:45 [2, 3, 6, 11, 16, 23, 35, 36, 38, 39, 40, 41, 42, 43, 44, 46, 47, 48]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B358F577-9A2C-4F71-9BC2-6A69E0B99696:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B358F577-9A2C-4F71-9BC2-6A69E0B99696:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:49 [2, 3, 6, 11, 16, 23, 35, 36, 38, 39, 40, 41, 42, 43, 44, 46, 47, 48, 49]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:41CD5606-68A0-4B38-BB1E-5F21BA470708
,[ThaliCore] Session.startOutputStream(with:) peer:41CD5606-68A0-4B38-BB1E-5F21BA470708
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:50 [2, 3, 6, 11, 16, 23, 35, 36, 38, 39, 40, 41, 42, 43, 44, 46, 47, 48, 49, 50]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7982C450-B190-41BA-9C3F-1E4EBCCE4055
[ThaliCore] Session.startOutputStream(with:) peer:7982C450-B190-41BA-9C3F-1E4EBCCE4055
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:51 [2, 3, 6, 11, 16, 23, 35, 36, 38, 39, 40, 41, 42, 43, 44, 46, 47, 48, 49, 50, 51]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:48
[ThaliCore] VirtualSocket.closeStreams() vsID:48
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:48
,[ThaliCore] VirtualSocket.deinit vsID:48 [2, 3, 6, 11, 16, 23, 35, 36, 38, 39, 40, 41, 42, 43, 44, 46, 47, 49, 50, 51]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-24 12:19:15 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
,[ThaliCore] VirtualSocket.closeStreams() vsID:49
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:49
[ThaliCore] VirtualSocket.deinit vsID:49 [2, 3, 6, 11, 16, 23, 35, 36, 38, 39, 40, 41, 42, 43, 44, 46, 47, 50, 51]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:50
[ThaliCore] VirtualSocket.closeStreams() vsID:50
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:50
[ThaliCore] VirtualSocket.deinit vsID:50 [2, 3, 6, 11, 16, 23, 35, 36, 38, 39, 40, 41, 42, 43, 44, 46, 47, 51]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:41CD5606-68A0-4B38-BB1E-5F21BA470708
,[ThaliCore] Session.startOutputStream(with:) peer:41CD5606-68A0-4B38-BB1E-5F21BA470708
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:52 [2, 3, 6, 11, 16, 23, 35, 36, 38, 39, 40, 41, 42, 43, 44, 46, 47, 51, 52]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7982C450-B190-41BA-9C3F-1E4EBCCE4055
[ThaliCore] Session.startOutputStream(with:) peer:7982C450-B190-41BA-9C3F-1E4EBCCE4055
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:53 [2, 3, 6, 11, 16, 23, 35, 36, 38, 39, 40, 41, 42, 43, 44, 46, 47, 51, 52, 53]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:47
[ThaliCore] VirtualSocket.closeStreams() vsID:47
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,47
[ThaliCore] VirtualSocket.deinit vsID:47 [2, 3, 6, 11, 16, 23, 35, 36, 38, 39, 40, 41, 42, 43, 44, 46, 51, 52, 53]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(,_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:41CD5606-68A0-4B38-BB1E-5F21BA470708
[ThaliCore] Session.startOutputStream(with:) peer:41CD5606-68A0-4B38-BB1E-5F21BA470708
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:54 [2, 3, 6, 11, 16, 23, 35, 36, 38, 39, 40, 41, 42, 43, 44, 46, 51, 52, 53, 54]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:52
[ThaliCore] VirtualSocket.closeStreams() vsID:52
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:52
[ThaliCore] VirtualSocket.deinit vsID:52 [2, 3, 6, 11, 16, 23, 35, 36, 38, 39, 40, 41, 42, 43, 44, 46, 51, 53, 54]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:n,il
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:53
[ThaliCore] VirtualSocket.closeStreams() vsID:53
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,53
[ThaliCore] VirtualSocket.deinit vsID:53 [2, 3, 6, 11, 16, 23, 35, 36, 38, 39, 40, 41, 42, 43, 44, 46, 51, 54]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:wi,thError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E9586F70-5B36-4872-8956-BF5C544C75F6:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:E9586F70-5B36-4872-8956-BF5C544C75F6:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "E9586F70-5B36-4872-8956-BF5C544C75F6", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60592
,2017-07-24 12:19:16 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8","error":null,"portNumber":60592}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E9586F70-5B36-4872-8956-BF5C544C75F6:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E9586F70-5B36-4872-8956-BF5C544C75F6:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:55 [2, 3, 6, 11, 16, 23, 35, 36, 38, 39, 40, 41, 42, 43, 44, 46, 51, 54, 55]
[ThaliCor,e] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:55
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:55
[ThaliCore] VirtualSocket.deinit vsID:55 [2, 3, 6, 11, 16, 23, 35, 36, 38, 39, 40, 41, 42, 43, 44, 46, 51, 54]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E9586F70-5B36-4872-8956-BF5C544C75F6:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E9586F70-5B36-4872-8956-BF5C544C75F6:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:56 [2, 3, 6, 11, 16, 23, 35, 36, 38, 39, 40, 41, 42, 43, 44, 46, 51, 54, 56]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 12:19:17 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E9586F70-5B36-4872-8956-BF5C544C75F6:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E9586F70-5B36-4872-8956-BF5C544C75F6:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:57 [2, 3, 6, 11, 16, 23, 35, 36, 38, 39, 40, 41, 42, 43, 44, 46, 51, 54, 56, 57]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:E9586F70-5B36-4872-8956-BF5C544C75F6:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E9586F70-5B36-4872-8956-BF5C544C75F6:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:58 [2, 3, 6, 11, 16, 23, 35, 36, 38, 39, 40, 41, 42, 43, 44, 46, 51, 54, 56, 57, 58]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7982C450-B190-41BA-9C3F-1E4EBCCE4055
[ThaliCore] Session.startOutputStream(with:) peer:7982C450-B190-41BA-9C3F-1E4EBCCE4055
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:59 [2, 3, 6, 11, 16, 23, 35, 36, 38, 39, 40, 41, 42, 43, 44, 46, 51, 54, 56, 57, 58, 59]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E9586F70-5B36-4872-8956-BF5C544C75F6:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E9586F70-5B36-4872-8956-BF5C544C75F6:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:60 [2, 3, 6, 11, 16, 23, 35, 36, 38, 39, 40, 41, 42, 43, 44, 46, 51, 54, 56, 57, 58, 59, 60]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E9586F70-5B36-4872-8956-BF5C544C75F6:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E9586F70-5B36-4872-8956-BF5C544C75F6:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:61 [2, 3, 6, 11, 16, 23, 35, 36, 38, 39, 40, 41, 42, 43, 44, 46, 51, 54, 56, 57, 58, 59, 60, 61]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:41CD5606-68A0-4B38-BB1E-5F21BA470708
[ThaliCore] Session.startOutputStream(with:) peer:41CD5606-68A0-4B38-BB1E-5F21BA470708
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:62 [2, 3, 6, 11, 16, 23, 35, 36, 38, 39, 40, 41, 42, 43, 44, 46, 51, 54, 56, 57, 58, 59, 60, 61, 62]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,2017-07-24 12:19:18 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-24 12:19:18 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:59
[ThaliCore] VirtualSocket.closeStreams() vsID:59
2017-07-24 12:19:18 - DEBUG thaliPeerPoolDefault: 'Got err   No activity time out'
[ThaliCore] AdvertiserRelay.didCloseVirtualSock,etStreamsHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:35
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:59
,[ThaliCore] VirtualSocket.deinit vsID:59 [2, 3, 6, 11, 16, 23, 35, 36, 38, 39, 40, 41, 42, 43, 44, 46, 51, 54, 56, 57, 58, 60, 61, 62]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
,[ThaliCore] VirtualSocket.closeStreams() vsID:39
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:42
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NS,LocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:44
[ThaliCore] VirtualSocket exited RunLoop vsID:35
,[ThaliCore] VirtualSocket.deinit vsID:35 [2, 3, 6, 11, 16, 23, 36, 38, 39, 40, 41, 42, 43, 44, 46, 51, 54, 56, 57, 58, 60, 61, 62]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:42
[ThaliCore] VirtualSocket.deinit vsID:42 [2, 3, 6,, 11, 16, 23, 36, 38, 39, 40, 41, 43, 44, 46, 51, 54, 56, 57, 58, 60, 61, 62]
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:44
[ThaliCore] VirtualSocket.deinit vsID:44 [2, 3, 6,, 11, 16, 23, 36, 38, 39, 40, 41, 43, 46, 51, 54, 56, 57, 58, 60, 61, 62]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:60
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:60
[ThaliCore] VirtualSocket.deinit vsID:60 [2, 3, 6, 11, 16, 23, 36, 38, 39, 40, 41, 43, 46, 51, 54, 56, 57, 58, 61, 62]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7982C450-B190-41BA-9C3F-1E4EBCCE4055
[ThaliCore] Session.startOutputStream(with:) peer:7982C450-B190-41BA-9C3F-1E4EBCCE4055
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:63 [2, 3, 6, 11, 16, 23, 36, 38, 39, 40, 41, 43, 46, 51, 54, 56, 57, 58, 61, 62, 63]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:62
[ThaliCore] VirtualSocket.closeStreams() vsID:62
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:62
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:62 [2, 3, 6, 11, 16, 23, 36, 38, 39, 40, 41, 43, 46, 51, 54, 56, 57, 58, 61, 63]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-24 12:19:18 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:63
[ThaliCore] VirtualSocket.closeStreams() vsID:63
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:63
[ThaliCore] VirtualSocket.deinit vsID:63 [2, 3, 6, 11, 16, 23, 36, 38, 39, 40, 41, 43, 46, 51, 54, 56, 57, 58, 61]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:n,il
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7982C450-B190-41BA-9C3F-1E4EBCCE4055
[ThaliCore] Session.startOutputStream(with:) peer:7982C450-B190-41BA-9C3F-1E4EBCCE4055
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:64 [2, 3, 6, 11, 16, 23, 36, 38, 39, 40, 41, 43, 46, 51, 54, 56, 57, 58, 61, 64]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:64
[ThaliCore] VirtualSocket.closeStreams() vsID:64
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:64
[ThaliCore] VirtualSocket.deinit vsID:64 [2, 3, 6, 11, 16, 23, 36, 38, 39, 40, 41, 43, 46, 51, 54, 56, 57, 58, 61]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:n,il
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:38
[ThaliCore] VirtualSocket.closeStreams() vsID:38
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:38
,[ThaliCore] VirtualSocket.deinit vsID:38 [2, 3, 6, 11, 16, 23, 36, 39, 40, 41, 43, 46, 51, 54, 56, 57, 58, 61]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withEr,ror:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:40
[ThaliCore] VirtualSocket.closeStreams() vsID:40
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:40
,[ThaliCore] VirtualSocket.deinit vsID:40 [2, 3, 6, 11, 16, 23, 36, 39, 41, 43, 46, 51, 54, 56, 57, 58, 61]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:43
[ThaliCore] VirtualSocket.closeStreams() vsID:43
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:43
[ThaliCore] VirtualSocket.deinit vsID:43 [2, 3, 6, 11, 16, 23, 36, 39, 41, 46, 51, 54, 56, 57, 58, 61]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:54
[ThaliCore] VirtualSocket.closeStreams() vsID:54
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:54
[ThaliCore] VirtualSocket.deinit vsID:54 [2, 3, 6, 11, 16, 23, 36, 39, 41, 46, 51, 56, 57, 58, 61]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-24 12:19:20 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-24 12:19:20 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
2017-07-24 12:19:20 - DEBUG thaliPeerPoolDefault: 'Got err   No activity time out'
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by r,emote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vs,ID:56
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPLis,tener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:57
[ThaliCore], TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDi,s,connect(_:withError:) socket removed, count:1
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:56
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket ex,ited RunLoop vsID:57
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] VirtualSocket.deinit vsID:56 [2, 3, 6, 11, 16, 23, 36, 39, 41, 46, 51, 57, 58, 61]
[T,haliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket.closeStreams() vsID:58
[ThaliCore] VirtualSocket.deinit vsID:57 [2, 3, 6, 11, 16, 23, 36, 39, 41, 46,,, 51, 58, 61]
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:58
[ThaliCore] VirtualSocket.closeStream,s() vsID:61
[ThaliCore] VirtualSocket.deinit vsID:58 [2, 3, 6, 11, 16, 23, 36, 39, 41, 46, 51, 61]
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:61
,[ThaliCore] VirtualSocket.deinit vsID:61 [2, 3, 6, 11, 16, 23, 36, 39, 41, 46, 51]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:36
[ThaliCore] VirtualSocket.closeStreams() vsID:36
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:36
[ThaliCore] VirtualSocket.deinit vsID:36 [2, 3, 6, 11, 16, 23, 39, 41, 46, 51]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:41
[ThaliCore] VirtualSocket.closeStreams() vsID:41
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:41
[ThaliCore] VirtualSocket.deinit vsID:41 [2, 3, 6, 11, 16, 23, 39, 46, 51]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisco,nnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:46
[ThaliCore] VirtualSocket.closeStreams() vsID:46
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:46
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.deinit vsID:46 [2, 3, 6, 11, 16, 23, 39, 51]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:51
[ThaliCore] VirtualSocket.closeStreams() vsID:51
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:51
[ThaliCore] VirtualSocket.deinit vsID:51 [2, 3, 6, 11, 16, 23, 39]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-24 12:22:10 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2017-07-24 12:22:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:22:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:22:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:22:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:22:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:22:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:22:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:22:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:22:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:22:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-4,5F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:22:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:22:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:23:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:23:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:23:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:23:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:23:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:23:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-4,5F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:23:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:23:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-4,5F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:23:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:23:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:23:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:23:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:24:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:24:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:24:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:24:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:24:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:24:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-4,5F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:24:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:24:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:24:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:24:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:24:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:24:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:25:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:25:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:25:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:25:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:25:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:25:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:25:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:25:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:25:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:25:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-4,5F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:25:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:25:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:26:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:26:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:26:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:26:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:26:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:26:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:26:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:26:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:26:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:26:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:26:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:26:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:27:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:27:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:27:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:27:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:27:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:27:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:27:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:27:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:27:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:27:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:27:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:27:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:28:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:28:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-4,5F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:28:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:28:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:28:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:28:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:28:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:28:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:28:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:28:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:28:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:28:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:29:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:29:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server that is not listening yet witheatNotRunning set to true'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue and run in order'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiConnect properly fails on legal but non-existent peerID'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with invalid syncValue'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call disconnect with invalid peer id'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - disconnect doesn't fail on plausible but bogus peer ID'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Get same port when trying to connect multiple times on iOS'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - initial peer discovery'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 1'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 2'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - check latest peer discovery'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Set up for no peer discovery test'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - no peer discovery'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits incomingConnectionState'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server connections all up'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can create servers manager'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling stop without start causes error'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can start/stop servers manager'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connection'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single local http request'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single coordinated request ios native'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple local http requests'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple coordinated request ios native'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status before starting'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - error returned with bad router'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are started when we call start'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP Servers Manager should be null when we call start on iOS'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are stopped when we call stop'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateConnection is properly hooked up'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateConnection is return error if we get called on iOS'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateListener is properly hooked up'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateListener is return error if we get called on iOS'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure we actually call kill connections properly'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from multiConnectConnection'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure bad PSK connections fail'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer changes handled from a queue'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - relaying discoveryAdvertisingStateUpdateNonTCP'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - we successfully receive and replay discoveryAdvertisingStateUpdate'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests between peers'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can still do HTTP requests between peers with coordinator'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - calls correct starts when network changes'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test to coordinate connection cut'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests after connections are cut'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - will fail bad PSK connection between peers'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We provide notification when a listener dies and we recreate it'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start - Causing native or wifi to fail will cause a promise reject '
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start should fail if called twice in a row'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not emit duplicate discoveryAdvertisingStateUpdate'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - does not send duplicate availability changes'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (native)'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (wifi)'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - new peer is cached'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with same port and different generation is cached (BLUETOOTH)'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with greater generation is cached (MPCF)'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with same or older generation is ignored (MPCF)'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - new peer is ignored'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - cached peer is removed'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for wifi peers'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - new peer is ignored (MPCF)'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (TCP_NATIVE)'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort field (BLUETOOTH)'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (MPCF)'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - error when peer has not been discovered yet'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached wifi peer'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect fails on wifi peers'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect delegates native peers to the native wrapper'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes emitted correctly'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in started state'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in stopped state'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on Android'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on iOS'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not fire duplicate events after peer listener recreation'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #stop should change peers'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer should be found once after listening and discovery started'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get data from all participants'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - test for data corruption'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - test getters'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start and kill'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - double start'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start after kill'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - make sure ids are unique'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - check that forever agent can be destroyed'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary basic functionality'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary with multiple entries.'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - RESOLVED entries are removed before WAITING state entry.'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - WAITING entries are removed before CONTROLLED_BY_POOL state entry.'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - When CONTROLLED_BY_POOL entry is removed and kill is called.'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - single action'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - multiple actions'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - PSK Pool works'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - stop'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that start verifies queue length'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - bad enqueues'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - do not allow same object type'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure we catch kill and dequeue'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that stop removes all actions'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized connection type'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized action type'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One action on bluetooth'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Two notification actions'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - replicateThroughProblems'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Replication goes first'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows many parallel non-replication actions'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows no more than 2 simultaneous replication actions for same peerID'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Client to server request coordinated'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test BEACONS_RETRIEVED_AND_PARSED locally'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test HTTP_BAD_RESPONSE locally'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test NETWORK_PROBLEM locally'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails when getPeerHostInfo fails'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the start two times'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill before calling the start'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill immediately after the start'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill while waiting a response from the server'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test to exceed the max content size locally'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the server socket while the client is waiting a response from the server. Local test.'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the client socket while the client is waiting a response from the server. Local test.'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons bad args'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons empty keys to notify'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons multiple keys to notify'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid expiration in beaconStreamWithPreAmble'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons no beacons returns null'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback fails decrypt'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns no matches'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns spurious match'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns public key'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskIdentityField'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecret'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecrets'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generateBeaconStreamAndSecrets'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Add two Peers.'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP_NATIVE peer loses DNS'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Received beacons with no values for us'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Notification action killed with a superseded'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally using ThaliPeerPoolDefault'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails because of a bad hostname.'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - hostaddress is removed when the action is running. '
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notificationClient does not retry action with BAD_PEER resolution'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notification client correctly handles peer availability changes of the same peer'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Client to server request locally'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache clean and expiration'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache getSecret and getPublic'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache multiple entries'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start and stop ThaliNotificationServer'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty array to ThaliNotificationServer.start'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass a string to ThaliNotificationServer.start'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty parameter to ThaliNotificationServer.start'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons (no keys)'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeaconsbefore calling start'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure peerDictionaryKey is reasonable'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure start works'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure stop works'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Simple peer event'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - Coordinated pull replication from notification test, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3,-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/bluebird/,js/release/timers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1
''
2017-07-24 12:29:09 ,- ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-07-24 12:29:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:29:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,not ok 862 failed with TimeoutError
  ---
    operator: fail
  ...
,# teardown
,2017-07-24 12:29:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:29:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:29:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:29:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:29:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:29:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:29:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:29:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:30:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:30:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:30:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:30:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:30:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:30:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:30:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:30:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-4,5F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:30:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:30:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:30:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:30:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-4,5F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:31:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:31:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:31:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:31:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:31:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:31:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:31:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:31:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:31:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:31:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:31:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:31:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:32:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:32:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:32:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F,3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:32:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/EA1B8CF2-CB93-45F3-9E7A-7E73F4329066/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''

```
