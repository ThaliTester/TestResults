#### Test 145917619d0aee2c_iOS_Iphone6sPlus-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/145917619d0aee2c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/8694A99F-C555-4AFE-B59F-6625779D0E59/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'
,Executing commands in '/tmp/8694A99F-C555-4AFE-B59F-6625779D0E59/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/145917619d0aee2c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/145917619d0aee2c/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50576"
,(lldb)     command script import "/tmp/8694A99F-C555-4AFE-B59F-6625779D0E59/fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.py"
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
,JXcore Cordova bridge is ready
,JXcore engine is started
,2017-10-11 11:44:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-11 11:44:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-11 11:44:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-11 11:44:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-10-11 11:44:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-11 11:44:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-11 11:44:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A3B3119C-4099-44FA-84,25-432BDC69F352", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:A3B3119C-4099-44FA-8425-432BDC69F352
,Optional(true)
Optional(false)
AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3F2A9FF2-5A41-48D7-A887-,87BFDF45C9FB
[ThaliCore] Browser.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:fo,undPeer:lostPeer:) peer:DACF82E3-08C9-4640-B34D-79B1A41A828C
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B0D1EE55-74B5-49F1-BA77-257D850E0788", generation: 0)
[Tha,liCore] Advertiser.startAdvertising with peerID:B0D1EE55-74B5-49F1-BA77-257D850E0788
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B0D1EE55-74B5-49F1-BA77-257D850E0788:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B0D1EE55-74B5-49F1-BA77-257D850E0788", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo,rrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-10-11 11:44:53 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
,Number of ignored tests:  0
Total duration:  1.480082035064697
,2017-10-11 11:44:53 - DEBUG UnitTest_app: 'My device name is: 'Apple-Iphone6sPlus-1''
,2017-10-11 11:44:53 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B0D1EE55-74B5-49F1-BA77-257D850E0788:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B0D1EE55-74B5-49F1-BA77-257D850E0788", generation: 0)
,2017-10-11 11:44:55 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-10-11 11:44:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-10-11 11:44:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-10-11 11:44:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-10-11 11:44:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-10-11 11:44:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-10-11 11:44:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-10-11 11:44:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-10-11 11:44:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-10-11 11:44:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-10-11 11:44:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-10-11 11:44:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-10-11 11:44:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-10-11 11:44:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-10-11 11:44:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-10-11 11:44:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-10-11 11:44:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-10-11 11:44:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-10-11 11:44:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-10-11 11:44:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-10-11 11:44:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-10-11 11:44:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-10-11 11:44:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-10-11 11:44:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-10-11 11:44:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-10-11 11:44:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-10-11 11:44:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-10-11 11:44:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-10-11 11:44:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-10-11 11:44:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-10-11 11:44:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-10-11 11:44:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-10-11 11:44:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-10-11 11:44:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-10-11 11:44:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-10-11 11:44:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-10-11 11:44:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-10-11 11:44:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-10-11 11:44:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-10-11 11:44:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-10-11 11:44:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-10-11 11:44:57 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-10-11 11:44:57 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-10-11 11:44:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:44:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:44:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:45:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:45:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:45:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:45:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:45:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:45:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:45:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:45:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:45:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:45:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:45:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:45:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:46:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:46:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:46:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:46:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:46:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:46:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:46:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:46:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:46:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:46:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:46:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:46:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:47:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:47:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:47:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:47:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:47:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:47:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:47:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:47:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:47:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:47:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:47:52 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-10-11 11:47:52 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-10-11 11:47:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 1 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll with promise
,2017-10-11 11:47:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-10-11 11:48:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-10-11 11:48:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-10-11 11:48:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-10-11 11:48:06 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-10-11 11:48:07 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-10-11 11:48:07 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
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
ok 33 second
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
,2017-10-11 11:48:22 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-10-11 11:48:23 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-10-11 11:48:27 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
,ok 59 throws if usn has invalid identifier format
,ok 60 throws if usn has invalid generation
,ok 61 correctly stringifies peer
,# teardown
,# setup
,# onPeerLost calls jxcore
,2017-10-11 11:48:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-10-11 11:48:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-11 11:48:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-11 11:48:41 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-11 11:48:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-10-11 11:48:41 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-10-11 11:48:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-10-11 11:48:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-10-11 11:48:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-10-11 11:48:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-10-11 11:48:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-11 11:48:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-11 11:48:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-11 11:48:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-10-11 11:48:42 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-10-11 11:48:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-10-11 11:48:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-10-11 11:48:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3AE85C1C-9499-49A0-804E-F2F916D01091
[ThaliCore] Browser.startListening
,2017-10-11 11:48:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-10-11 11:48:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-11 11:48:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-10-11 11:48:42 - DEBUG thaliMobileNativeWrapper: 'disco,veryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-11 11:48:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without e,r,ror
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-11 11:48:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-11 11:48:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-11 11:48:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-10-11 11:48:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-11 11:48:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-11 11:48:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-11 11:48:42 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-11 11:48:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-10-11 11:48:42 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-10-11 11:48:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-10-11 11:48:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-10-11 11:48:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7F01A5FE-6B70-47D4-BA70-5F72BD95EB36
[ThaliCore] Browser.startListening
2017-10-11 11:48:43 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-10-11 11:48:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-11 11:48:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Can call startLis,teningForAdvertisements without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-10-11 11:48:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-10-1,1, 11:48:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,",networkType":null}})'
2017-10-11 11:48:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-10-11 11:48:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-11, 11:48:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-11 11:48:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-10-11 11:48:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-11 11:48:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-11 11:48:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-11 11:48:44 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-11 11:48:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-10-11 11:48:44 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-10-11 11:48:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-10-11 11:48:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-10-11 11:48:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-11 11:48:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-11 11:48:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 66 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-11 11:48:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisin,gActive":false}'
2017-10-11 11:48:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-11 11:48:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-11 11:48:48 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-11 11:48:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-10-11 11:48:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-11 11:48:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-11 11:48:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-11 11:48:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-11 11:48:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-10-11 11:48:48 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-10-11 11:48:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-10-11 11:48:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-10-11 11:48:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2BC108C0-3CC5-4C15-992A-53741516498F", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:2BC108C0-3CC5-4C15-992A-53741516498F
,2017-10-11 11:48:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-10-11 11:48:49 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-10-11 11:48:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 68 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:2BC108C0-3CC5-4C15-992A-53741516498F
,2017-10-11 11:48:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-11 11:48:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 69 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-11 11:48:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-11 11:48:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-11 11:48:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-11 11:48:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-11 11:48:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-11 11:48:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-11 11:48:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-11 11:48:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-11 11:48:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-11 11:48:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-11 11:48:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-11 11:48:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2536E842-1BC4-4391-A6D4-B3AB3E10CACC", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:2536E842-1BC4-4391-A6D4-B3AB3E10CACC
,2017-10-11 11:48:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-11 11:48:50 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-11 11:48:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 70 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2536E842-1BC4-4391-A6D4-B3AB3E10CACC", generation: 1)
[,ThaliCore] Advertiser.startAdvertising with peerID:2536E842-1BC4-4391-A6D4-B3AB3E10CACC
2017-10-11 11:48:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-11 11:48:50, ,- INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTyp,e":null}})'
2017-10-11 11:48:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-11 11:48:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-11 11:48:52 - INFO thaliMobile: 'Receive,d state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-11 11:4,8:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:2536E842-1BC4-4391-A6D4-B3AB3E10CACC
[ThaliCore] Advertiser.s,topAdvertising() peerID:2536E842-1BC4-4391-A6D4-B3AB3E10CACC
,2017-10-11 11:48:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-11 11:48:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-10-11 11:48:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-11 11:48:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-11 11:48:52 ,- DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-11 11:48:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-11 11:48:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-11 11:48:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-11 11:48:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-11 11:48:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-11 11:49:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-11 11:49:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 72 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-11 11:49:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive",:false}'
2017-10-11 11:49:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-11 11:49:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-11 11:49:05 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-11 11:49:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-10-11 11:49:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-11 11:49:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-11 11:49:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-11 11:49:05 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-11 11:49:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-10-11 11:49:05 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-10-11 11:49:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-10-11 11:49:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-10-11 11:49:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "75F23093-476E-4543-93E5-6091E21DEA89", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:75F23093-476E-4543-93E5-6091E21DEA89
2017-10-11 11:49:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-10-11 11:49:06 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-10-11 11:49:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdv,ertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:EA287F40-5949-4C01-B1D8-403A9A0D193B
[ThaliCore] Browser.startListening
2017-10-11 11:49:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryA,ctive":true,"advertisingActive":true}'
2017-10-11 11:49:06 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","sta,r,tArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-11 11:49:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DA861A75-8005-4738-B121-D6D2FA3CB68E:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DA861A75-8005-4738-B121-D6D2FA3CB68E", generation: 0)
,ok 76 peers must be an array
,ok 77 peers must not be zero-length
,ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
,ok 79 peerIdentifier must be a string
,ok 80 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:75F23093-476E-4543-93E5-6091E21DEA89:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "75F23093-476E-4543-93E5-6091E21DEA89", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:939B08FA-41FE-498B-B51E-E9333112CF98:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "939B08FA-41FE-498B-B51E-E9333112CF98", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-10-11 11:49:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-11 ,11:49:08 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-10-11 11:49:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:75F23093-476E-4543-93E5-6,091E21DEA89
2017-10-11 11:49:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-11 11:49:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
2017-10-11 11:49:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-11 11:49:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10,-11 11:49:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-11 11:49:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-11 11:49:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-11 11:49:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-11 11:49:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-11 11:49:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8
2017-10-11 1,1:49:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-11 11:49:28 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-11 11:49:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 81 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:04B709C6-6D9C-4B90-BFB4-9A384D6EE6AB
[Thal,i,Core] Browser.startListening
2017-10-11 11:49:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-10-11 11:49:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-11 11:49:28 - INFO thaliMobile: 'Filtere,d out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B684C49D-590F-4A16-9CBA-CC5ED8CDA416:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B684C49D-590F-4A16-9CBA-CC5ED8CDA416", generation: 0)
,2017-10-11 11:49:28 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B684C49D-590F-4A16-9CBA-CC5ED8CDA416","generation":0}'
,2017-10-11 11:49:28 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B684C49D-590F-4A16-9CBA-CC5ED8CDA416 (syncValue: n4FbHN3HKiEOq0JKqOo5skMFq9maLoxh)'
,2017-10-11 11:49:28 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B684C49D-590F-4A16-9CBA-CC5ED8CDA416", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B684C49D-590F-4A16-9CBA-CC5ED8CDA416", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B684C49D-590F-4A16-9CBA-CC5ED8CDA416:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D02F1F86-EBDA-4870-9326-FAE8B7DE5FCA
[ThaliCore] Advertiser: session connected Peer(uuid: "C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:D02F1F86-EBDA-4870-9326-FAE8B7DE5FCA state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:B684C49D-590F-4A16-9CBA-CC5ED8CDA416:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B12CCD5C-504E-4635-8DB3-BE9514508331:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B12CCD5C-504E-4635-8DB3-BE9514508331", generation: 0)
2017-10-11 11:49:31 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B12CCD5C-504E-4635-8DB3-BE9514508331","generation":0}'
2017-10-11 11:49:31 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-11 11:49:31 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B684C49D-590F-4A16-9CBA-CC5ED8CDA416:0
[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D02F1F86-EBDA-4870-9326-FAE8B7DE5FCA
,[ThaliCore] Session.session(_:peer:didChange:) peer:B684C49D-590F-4A16-9CBA-CC5ED8CDA416:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "B684C49D-590F-4A16-9CBA-CC5ED8CDA416", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] Session.session(_:peer:didChange:) peer:D02F1F86-EBDA-4870-9326-FAE8B7DE5FCA state: connecting -> connected
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52076
2017,-10-11 11:49:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"n4FbHN3HKiEOq0JKqOo5skMFq9maLoxh","error":null,"portNumber":52076}'
2017-10-11 11:49:31 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'n4FbH,N3HKiEOq0JKqOo5skMFq9maLoxh', error: 'null', listeningPort: '52076''
,2017-10-11 11:49:31 - INFO testThaliMobileNative: ''
ok 83 Must have listeningPort
ok 84 listeningPort must be a number
ok 85 listening port should not be 0
,# teardown
,2017-10-11 11:49:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-10-11 11:49:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-11 11:49:35 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-11 11:49:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8
,2017-10-11 11:49:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-11 11:49:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.disconnect peer:B684C49D-590F-4A16-9CBA-CC5ED8CDA416
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:52076
[ThaliCore] Session.disconnect,() peer:B684C49D-590F-4A16-9CBA-CC5ED8CDA416:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:B684C49D-590F-4A16-9CBA-CC5ED8CDA416:0
[ThaliCore] BrowserRelay.deinit
,2017-10-11 11:49:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-11 11:49:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-11 11:49:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-11 11:49:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-11 11:49:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-11 11:49:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-11 11:49:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-11 11:49:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:D02F1F86-EBDA-4870-9326-FAE8B7DE5FCA state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:D02F1F86-EBDA-4870-9326-FAE8B7DE5FCA
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] Session.deinit peer:D02F1F86-EBDA-4870-9326-FAE8B7DE5FCA
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "693ACD69-7D6C-45C9-A0EE-2855E12F155B", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:693ACD69-7D6C-45C9-A0EE-2855E12F155B
,2017-10-11 11:49:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-11 11:49:42 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-11 11:49:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E7FD0F07-6302-4489-A30F-9733F134,5F7A
[ThaliCore] Browser.startListening
2017-10-11 11:49:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-10-11 11:49:42 - INFO thaliMobile: 'Received state ({"discover,y,Active":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-11 11:49:42 - INFO thaliMobi,le: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B684C49D-590F-4A16-9CBA-CC5ED8CDA416:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B684C49D-590F-4A16-9CBA-CC5ED8CDA416", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B12CCD5C-504E-4635-8DB3-BE9514508331:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B12CCD5C-504E-4635-8DB3-BE9514508331", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9F70A025-7FB6-44F8-842A-A7168F9BD13B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9F70A025-7FB6-44F8-842A-A7168F9BD13B", generation: 0)
,2017-10-11 11:49:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B684C49D-590F-4A16-9CBA-CC5ED8CDA416","generation":0}'
,2017-10-11 11:49:42 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B684C49D-590F-4A16-9CBA-CC5ED8CDA416 (syncValue: jRwD5caawBAayu6NWCLpwvhBmfxc5Fze)'
,2017-10-11 11:49:42 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B684C49D-590F-4A16-9CBA-CC5ED8CDA416", generation: 0) creating a new relay
[Tha,liCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B684C49D-590F-4A16-9CBA-CC5ED8CDA416", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B684C49D-590F-4A16-9CBA-CC5ED8CDA416:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,2017-10-11 11:49:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B12CCD5C-504E-4635-8DB3-BE9514508331","generation":0}'
2017-10-11 11:49:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-11 11:49:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-11 11:49:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9F70A025-7FB6-44F8-842A-A7168F9BD13B","generation":0}'
,2017-10-11 11:49:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-11 11:49:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-11 11:49:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BF4CF963-A10F-4CDD-9A86-7AE2A53CC641:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BF4CF963-A10F-4CDD-9A86-7AE2A53CC641", generation: 0)
,2017-10-11 11:49:43 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BF4CF963-A10F-4CDD-9A86-7AE2A53CC641","generation":0}'
,2017-10-11 11:49:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-11 11:49:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-11 11:49:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-11 11:49:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:693ACD69-7D6C-45C9-A0EE-2855E12F155B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "693ACD69-7D6C-45C9-A0EE-2855E12F155B", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B684C49D-590F-4A16-9CBA-CC5ED8CDA416:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B6,84C49D-590F-4A16-9CBA-CC5ED8CDA416:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "B684C49D-590F-4A16-9CBA-CC5ED8CDA416", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,684C49D-590F-4A16-9CBA-CC5ED8CDA416", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B684C49D-590F-4A16-9CBA-CC5ED8CDA416", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B684C49D-590F-4A16-9CBA-CC5ED8CDA416:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B684C49D-590F-4A16-9CBA-CC5ED8CDA416:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B684C49D-590F-4A16-9CBA-CC5ED8CDA416:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B6,84C49D-590F-4A16-9CBA-CC5ED8CDA416:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "B684C49D-590F-4A16-9CBA-CC5ED8CDA416", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,684C49D-590F-4A16-9CBA-CC5ED8CDA416", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B684C49D-590F-4A16-9CBA-CC5ED8CDA416", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B684C49D-590F-4A16-9CBA-CC5ED8CDA416:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B684C49D-590F-4A16-9CBA-CC5ED8CDA416:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B684C49D-590F-4A16-9CBA-CC5ED8CDA416:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B6,84C49D-590F-4A16-9CBA-CC5ED8CDA416:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "B684C49D-590F-4A16-9CBA-CC5ED8CDA416", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,684C49D-590F-4A16-9CBA-CC5ED8CDA416", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B684C49D-590F-4A16-9CBA-CC5ED8CDA416", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B684C49D-590F-4A16-9CBA-CC5ED8CDA416:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B684C49D-590F-4A16-9CBA-CC5ED8CDA416:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B684C49D-590F-4A16-9CBA-CC5ED8CDA416:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B6,84C49D-590F-4A16-9CBA-CC5ED8CDA416:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "B684C49D-590F-4A16-9CBA-CC5ED8CDA416", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:B684C49D,-590F-4A16-9CBA-CC5ED8CDA416 error: max retries exceeded
2017-10-11 11:49:53 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"jRwD5caawBAayu6NWCLpwvhBmfxc5Fze","error":"Connection could not be established","portNumber":null}'
2017-1,0-11 11:49:53 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'jRwD5caawBAayu6NWCLpwvhBmfxc5Fze', error: 'Connection could not be established', listeningPort: '%s''
,2017-10-11 11:49:53 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-10-11 11:49:53 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B12CCD5C-504E-4635-8DB3-BE9514508331 (syncValue: mwRnO1K,y08r1IsdWyydZlUlOB1Cjtd8J)'
2017-10-11 11:49:53 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B12CCD5C-504E-4635-8DB3-BE9514508331", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B12CCD5C-504E-4635-8DB3-BE9514508331", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B12CCD5C-504E,-4635-8DB3-BE9514508331:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-10-11 11:49:53 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-10-11 11:49:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-11 11:49:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:B684C49D-590F-4A16-9CBA-CC5ED8CDA416:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B12CCD5C-504E-4635-8DB3-BE9514508331:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B12CCD5C-504E-4635-8DB3-BE9514508331", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:42E2D5F6-4D5F-4F48-90AF-B83527681F42
[ThaliCore] Advertiser: session connected Peer(uuid: "693ACD69-7D6C-45C9-A0EE-2855E12F155B", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:42E2D5F6-4D5F-4F48-90AF-B83527681F42 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:B12CCD5C-504E-4635-8DB3-BE9514508331:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B1,2CCD5C-504E-4635-8DB3-BE9514508331:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "B12CCD5C-504E-4635-8DB3-BE9514508331", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,12CCD5C-504E-4635-8DB3-BE9514508331", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B12CCD5C-504E-4635-8DB3-BE9514508331", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-10-11 11:49:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"mwRnO1Ky08r1IsdWyydZlUlOB1Cjtd8J","error":"Peer is unavailable",,"portNumber":null}'
2017-10-11 11:49:56 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'mwRnO1Ky08r1IsdWyydZlUlOB1Cjtd8J', error: 'Peer is unavailable', listeningPort: '%s''
,2017-10-11 11:49:56 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-10-11 11:49:56 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9F70A025-7FB6-44F8-842A-A7168F9BD13B (syncValue: 1Rt2VjoFK5qEinc4xIEwvsOPnN2IddNd)'
2017-10-11 11:49:56 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9F70A025-7FB6-44F8-842A-A7168F9BD13B", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9F70A025-7FB6-44F8-842A-A7168F9BD13B", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9F70A025-7FB6-44F8-842A-A7168,F9BD13B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-10-11 11:49:56 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-11 ,11:49:56 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:B12CCD5C-504E-4635-8DB3-BE9514508331:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:9F70A025-7FB6-44F8-842A-A7168F9BD13B:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:42E2D5F6-4D5F-4F48-90AF-B83527681F42
,[ThaliCore] Session.session(_:peer:didChange:) peer:42E2D5F6-4D5F-4F48-90AF-B83527681F42 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:42E2D5F6-4D5F-4F48-90AF-B83527681F42
[ThaliCore] Session.startOutputStream(with:) peer:42E2D5F6-4D5F-4F48-90AF-B83527681F42
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1, [1]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:1
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 20 vsID:1
,2017-10-11 11:49:58 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-10-11 11:49:58 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
2017-10-11 11:49:58 - DEBUG testThaliMobileNative: 'Server sends data bac,k to client (20 bytes):'
2017-10-11 11:49:58 - DEBUG testThaliMobileNative: 'Server data flushed'
[ThaliCore] VirtualSocket.writeDataToOutputStream len:20 count:1 vsID:1
[ThaliCore] VirtualSocket.writePendingData() to write:20 written:20 count:0 vsID:1,
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:1
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 0 vsID:1
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:1
[ThaliCore] VirtualSocket.closeStreams() vsID:1
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler d,isconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:1
[ThaliCore] VirtualSocket.deinit vsID:1 []
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9F70A025-7FB6-44F8-842A-A7168F9BD13B:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:9F70A025-7FB6-44F8-842A-A7168F9BD13B:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "9F70A025-7FB6-44F8-842A-A7168F9BD13B", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52084
2017-10-11 11:49:59 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1Rt2VjoFK5qEinc4xIEwvsOPnN2IddNd",,"error":null,"portNumber":52084}'
2017-10-11 11:49:59 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '1Rt2VjoFK5qEinc4xIEwvsOPnN2IddNd', error: 'null', listeningPort: '52084''
,Connecting to the localhost:52084
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9F70A025-7FB6-44F8-842A-A7168F9BD13B:0
Connected to the localh,ost:52084
2017-10-11 11:49:59 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
2017-10-11 11:49:59 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9F70A025-7FB6-44F8-842A-A7168F9BD13B:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [2]
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:2
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:20 count:1 vsID:2
,[ThaliCore] VirtualSocket.writePendingData() to write:20 written:20 count:0 vsID:2
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:2
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 20 vsID:2
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:2
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:2
[ThaliCore] VirtualSocket.deinit vsID:2 []
ok 88 got the same data back
,# teardown
,2017-10-11 11:49:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-10-11 11:49:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-11 11:49:59 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-10-11 11:49:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:693ACD69-7D6C-45C9-A0EE-2855E12F155B
2017-10-11 11:49:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"a,dvertisingActive":false}'
,2017-10-11 11:49:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:9F70A025-7FB6-44F8-842A-A7168F9BD13B
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:52084
[ThaliCore] Session.disconnect() peer:9F70A025-7FB6-44F8-842A-A7168F9BD13B:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:9F70A025-7FB6-44F8-842A-A7168F9BD13B:0
[ThaliCore] BrowserRelay.deinit
,2017-10-11 11:49:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-11 11:49:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-11 11:49:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-11 11:49:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-10-11 11:49:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-11 11:49:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-11 11:49:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-11 11:49:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:42E2D5F6-4D5F-4F48-90AF-B83527681F42 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "693ACD69-7D6C-45C9-A0EE-2855E12F155B", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:42E2D5F6-4D5F-4F48-90AF-B83527681F42
,[ThaliCore] AdvertiserRelay.deinit
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CA4F3AF0-C6E6-4A7D-ABF3-25A3D4AC92FA", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:CA4F3AF0-C6E6-4A7D-ABF3-25A3D4AC92FA
2017-10-11 11:50:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-11 11:50:00, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-10-11 11:50:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 89 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Thal,iCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:AD3E6ED2-0B78-4737-B11D-2B6AC00B67F1
[ThaliCore] Browser.startListening
2017-10-11 11:50:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adve,r,tisingActive":true}'
2017-10-11 11:50:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"rout,er":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-11 11:50:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Session.deinit peer:42E2D5F6-4D5F-4F48-90AF-B83527681F42
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9F70A025-7FB6-44F8-842A-A7168F9BD13B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9F70A025-7FB6-44F8-842A-A7168F9BD13B", generation: 0)
2017-10-11 11:50:00 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9F70A025-7FB6-44F8-842A-A7168F9BD13B","generation":0}'
2017-10-11 11:50:00 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9F70A025-7FB6-44F8-842A-A7168F9BD13B, (syncValue: 4d8fDhyYJRYq7956hgKxibw8RmKCv4pe)'
2017-10-11 11:50:00 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9F70A025-7FB6-44F8-842A-A7168F9,BD13B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9F70A025-7FB6-44F8-842A-A7168F9BD13B", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:9F70A025-7FB6-44F8-842A-A7168F9BD13B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CF3EAD01-0759-464B-B522-6E5D1376B433:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CF3EAD01-0759-464B-B522-6E5D1376B433", generation: 0)
2017-10-11 11:50:01 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CF3EAD01-0759-464B-B522-6E5D1376B433","generation":0}'
2017-10-11 11:50:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-11 11:50:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B8643CF2-FE60-44D6-A9DE-05A1F25612CE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B8643CF2-FE60-44D6-A9DE-05A1F25612CE", generation: 0)
2017-10-11 11:50:01 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B8643CF2-FE60-44D6-A9DE-05A1F25612CE","generation":0}'
2017-10-11 11:50:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-11 11:50:01 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-10-11 11:50:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CA4F3AF0-C6E6-4A7D-ABF3-25A3D4AC92FA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CA4F3AF0-C6E6-4A7D-ABF3-25A3D4AC92FA", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:9F70A025-7FB6-44F8-842A-A7168F9BD13B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:9F,70A025-7FB6-44F8-842A-A7168F9BD13B:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "9F70A025-7FB6-44F8-842A-A7168F9BD13B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,F70A025-7FB6-44F8-842A-A7168F9BD13B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9F70A025-7FB6-44F8-842A-A7168F9BD13B", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:9F70A025-7FB6-44F8-842A-A7168F9BD13B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:9F70A025-7FB6-44F8-842A-A7168F9BD13B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:9F70A025-7FB6-44F8-842A-A7168F9BD13B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:9F,70A025-7FB6-44F8-842A-A7168F9BD13B:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "9F70A025-7FB6-44F8-842A-A7168F9BD13B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,F70A025-7FB6-44F8-842A-A7168F9BD13B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9F70A025-7FB6-44F8-842A-A7168F9BD13B", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:9F70A025-7FB6-44F8-842A-A7168F9BD13B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:9F70A025-7FB6-44F8-842A-A7168F9BD13B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:9F70A025-7FB6-44F8-842A-A7168F9BD13B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:9F,70A025-7FB6-44F8-842A-A7168F9BD13B:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "9F70A025-7FB6-44F8-842A-A7168F9BD13B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,F70A025-7FB6-44F8-842A-A7168F9BD13B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9F70A025-7FB6-44F8-842A-A7168F9BD13B", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:9F70A025-7FB6-44F8-842A-A7168F9BD13B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:9F70A025-7FB6-44F8-842A-A7168F9BD13B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:9F70A025-7FB6-44F8-842A-A7168F9BD13B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:9F,70A025-7FB6-44F8-842A-A7168F9BD13B:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "9F70A025-7FB6-44F8-842A-A7168F9BD13B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:9F70A025,-7FB6-44F8-842A-A7168F9BD13B error: max retries exceeded
2017-10-11 11:50:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4d8fDhyYJRYq7956hgKxibw8RmKCv4pe","error":"Connection could not be established","portNumber":null}'
2017-1,0-11 11:50:11 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '4d8fDhyYJRYq7956hgKxibw8RmKCv4pe', error: 'Connection could not be established', listeningPort: '%s''
,2017-10-11 11:50:11 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-10-11 11:50:11 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CF3EAD01-0759-464B-B522-6E5D1376B433 (syncValue: 4cx2jIA,GxQPWe0TkK0dDUd8vtdr5OLER)'
2017-10-11 11:50:11 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CF3EAD01-0759-464B-B522-6E5D1376B433", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CF3EAD01-0759-464B-B522-6E5D1376B433", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CF3EAD01-0759,-464B-B522-6E5D1376B433:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-10-11 11:50:11 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-10-11 11:50:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:9F70A025-7FB6-44F8-842A-A7168F9BD13B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:CF3EAD01-0759-464B-B522-6E5D1376B433:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CF3EAD01-0759-464B-B522-6E5D1376B433:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:CF3EAD01-0759-464B-B522-6E5D1376B433:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "CF3EAD01-0759-464B-B522-6E5D1376B433", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52100
,2017-10-11 11:50:14 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4cx2jIAGxQPWe0TkK0dDUd8vtdr5OLER","error":null,"portNumber":52100}'
,2017-10-11 11:50:14 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '4cx2jIAGxQPWe0TkK0dDUd8vtdr5OLER', error: 'null', listeningPort: '52100''
,Connecting to the localhost:52100
,Connecting to the localhost:52100
Connecting to the localhost:52100
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:CF3EAD01-0759-464B-B522-6E5D,1376B433:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:CF3EAD01-0759-464B-B522-6E5D1376B433:0
[ThaliCore] TCPListener.socket(_:didAcceptNewS,ocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:CF3EAD01-0759-464B-B522-6E5D1376B433:0
,Connected to the localhost:52100
,Connected to the localhost:52100
,Connected to the localhost:52100
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CF3EAD01-0759-464B-B522-6E5D1376B433:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [3]
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:3
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CF3EAD01-0759-464B-B522-6E5D1376B433:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [3, 4]
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CF3EAD01-0759-464B-B522-6E5D1376B433:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [3, 4, 5]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:4
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:5
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 91 correct string length
,2017-10-11 11:50:14 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:16384 count:1 vsID:3
,[ThaliCore] VirtualSocket.writePendingData() to write:16384 written:16384 count:0 vsID:3
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:3
,ok 92 correct string length
,2017-10-11 11:50:14 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
[ThaliCore] VirtualSocket.writeDataToOutputStream len:16384 count:1 vsID:4
,[ThaliCore] VirtualSocket.writePendingData() to write:16384 written:16384 count:0 vsID:4
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:4
,ok 93 correct string length
,2017-10-11 11:50:14 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:16384 count:1 vsID:5
,[ThaliCore] VirtualSocket.writePendingData() to write:16384 written:16384 count:0 vsID:5
,2017-10-11 11:50:14 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-10-11 11:50:14 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-10-11 11:50:14 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:5
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:3
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 3569 vsID:3
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:3
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2474 vsID:3
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:3
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1054 vsID:3
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:3
,[ThaliCore] VirtualSocket exited RunLoop vsID:3
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:3 [4, 5]
,ok 94 got the same data back
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:4
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:4
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:4
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:4
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:4
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:4
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:4
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:4
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:4
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:4
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:4
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:4
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:4
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:4
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1054 vsID:4
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,ok 95 got the same data back
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:5
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:5
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:5
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:5
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:5
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:5
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:5
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:5
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:5
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:5
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:5
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:5
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:5
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:5
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1054 vsID:5
,ok 96 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:5
[ThaliCore] Browser,Relay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:5
[ThaliCore] VirtualSocket.deinit vsID:5 [4]
,# teardown
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:9F70A025-7FB6-44F8-842A-A7168F9BD13B:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "9F70A025-7FB6-44F8-842A-A7168F9BD13B", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:310847F9-0DDB-407E-BB04-355C1C3E5A99
[ThaliCore] Advertiser: session connected Peer(uuid: "CA4F3AF0-C6E6-4A7D-ABF3-25A3D4AC92FA", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:310847F9-0DDB-407E-BB04-355C1C3E5A99 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D9BAB450-56B2-4619-8D12-1D81A214243C
[ThaliCore] Advertiser: session connected Peer(uuid: "CA4F3AF0-C6E6-4A7D-ABF3-25A3D4AC92FA", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:D9BAB450-56B2-4619-8D12-1D81A214243C state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:310847F9-0DDB-407E-BB04-355C1C3E5A99
,[ThaliCore] Session.session(_:peer:didChange:) peer:310847F9-0DDB-407E-BB04-355C1C3E5A99 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:310847F9-0DDB-407E-BB04-355C1C3E5A99
[ThaliCore] Session.startOutputStream(with:) peer:310847F9-0DDB-407E-BB04-355C1C3E5A99
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6, [4, 6]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:6
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D9BAB450-56B2-4619-8D12-1D81A214243C
,[ThaliCore] Session.session(_:peer:didChange:) peer:D9BAB450-56B2-4619-8D12-1D81A214243C state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:310847F9-0DDB-407E-BB04-355C1C3E5A99
[ThaliCore] Session.startOutputStream(with:) peer:310847F9-0DDB-407E-BB04-355C1C3E5A99
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [4, 6, 7]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:310847F9-0DDB-407E-BB04-355C1C3E5A99
[ThaliCore] Session.startOutputStream(with:) peer:310847F9-0DDB-407E-BB04-355C1C3E5A99
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [4, 6, 7, 8]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:7
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:8
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D9BAB450-56B2-4619-8D12-1D81A214243C
[ThaliCore] Session.startOutputStream(with:) peer:D9BAB450-56B2-4619-8D12-1D81A214243C
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [4, 6, 7, 8, 9]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D9BAB450-56B2-4619-8D12-1D81A214243C
[ThaliCore] Session.startOutputStream(with:) peer:D9BAB450-56B2-4619-8D12-1D81A214243C
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,0 [4, 6, 7, 8, 9, 10]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D9BAB450-56B2-4619-8D12-1D81A214243C
[ThaliCore] Session.startOutputStream(with:) peer:D9BAB450-56B2-4619-8D12-1D81A214243C
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [4, 6, 7, 8, 9, 10, 11]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:9
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:10
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:11
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:9
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:9
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:9
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:9
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:9
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:9
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:9
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:9
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:9
2017-10-11 11:50:23 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:9
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:9
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:9
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:9
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:9
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1054 vsID:9
,2017-10-11 11:50:23 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-10-11 11:50:23 - DEBUG testThaliMobileNative: 'Server received (10950 bytes):'
,2017-10-11 11:50:23 - DEBUG testThaliMobileNative: 'Server received (3244 bytes):'
,2017-10-11 11:50:23 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-10-11 11:50:23 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-10-11 11:50:23 - DEBUG testThaliMobileNative: 'Server data flushed',
[ThaliCore] VirtualSocket.writeDataToOutputStream len:16384 count:1 vsID:9
[ThaliCore] VirtualSocket.writePendingData() to write:16384 written:16384 count:0 vsID:9
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:9
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:10
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:10
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:10
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:10
,2017-10-11 11:50:23 - DEBUG testThaliMobileNative: 'Server received (4096 bytes):'
,2017-10-11 11:50:23 - DEBUG testThaliMobileNative: 'Server received (12288 bytes):'
,2017-10-11 11:50:23 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-10-11 11:50:23 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-10-11 11:50:23 - DEBUG testThaliMobileNative: 'Server data flushed',
[ThaliCore] VirtualSocket.writeDataToOutputStream len:16384 count:1 vsID:10
[ThaliCore] VirtualSocket.writePendingData() to write:16384 written:16384 count:0 vsID:10
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:10
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 3285 vsID:11
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:11
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 0 vsID:9
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:9
[ThaliCore] VirtualSocket.closeStreams() vsID:9
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:9
,[ThaliCore] VirtualSocket.deinit vsID:9 [4, 6, 7, 8, 10, 11]
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 0 vsID:10
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:10
[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:10
[ThaliCore] VirtualSocket.deinit vsID:10 [4, 6, 7, 8, 11]
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1054 vsID:11
,2017-10-11 11:50:23 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-10-11 11:50:23 - DEBUG testThaliMobileNative: 'Server received (7665 bytes):'
,2017-10-11 11:50:23 - DEBUG testThaliMobileNative: 'Server received (5434 bytes):'
,2017-10-11 11:50:23 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-10-11 11:50:23 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
[ThaliCore] VirtualSocket.writeDataToOutputStream len:16384 count:1 vsID:,11
[ThaliCore] VirtualSocket.writePendingData() to write:16384 written:16384 count:0 vsID:11
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:11
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 0 vsID:11
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:11
[ThaliCore] VirtualSocket.closeStreams() vsID:11
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,2017-10-11 11:50:23 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket exited RunLoop vsID:11
,[ThaliCore] VirtualSocket.deinit vsID:11 [4, 6, 7, 8]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:6
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:6
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:6
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:6
2017-10-11 11:50:23 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:6
,2017-10-11 11:50:23 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:6
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:6
,2017-10-11 11:50:23 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:6
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:6
2017-10-11 11:50:23 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:6
,2017-10-11 11:50:23 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:6
,2017-10-11 11:50:23 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:6
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:6
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:6
,2017-10-11 11:50:23 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1054 vsID:6
,2017-10-11 11:50:23 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-10-11 11:50:23 - DEBUG testThaliMobileNative: 'Server received (2149 bytes):'
,2017-10-11 11:50:23 - DEBUG testThaliMobileNative: 'Server received all data: jOEYm5QDpJQFGOUw1dRWEqtcqn9FipSOlNcz81SYSG56wCgTgBHzmaLUmYajTEkoduM0csLHSiKxtcImUzKUzPDPnkCIpM1HM54wGwmLDjcKanA4ldS7OodwZ8Uh72ogELT2lbD86L5PSzn2AZ3JAimzikseZs1EMkLy2n2iO8CdwuBjS1strblisrafkoHGUQj0wlL4Qvj1Am16n6z1imHjPccwfdB7iGz4YlecHGjsk0WqNfNvspGGnxV9FzPXa9XxmeTg4Et2k4JPykKZ2oWj9WbCRMopVBLbC1G8OXYfKuUZpVPs2Uv2MaQ01AEA0Y9vIRdxCmQXuZ1mrm2vdoE7bZWN64jBL7JNAUJfyB3F3tbiHIZKAyZtZjfL9lOkZ88pMfkLFUtxu0CJzH4UlWHo3MzRiNwsv1d1KDLnb79qI7Oajf,IRdDdgbX7PqspjueNgSDqFC3I3s4ydRy5eFLVVpJMC0jF1fy32JSFqFnCYv41xRnnTlrP8f3dHlbFdyiXEHtmE6AXRa5Zs9m37JnWGNCj8EcFoJkV5KxVcEzdUmr0DSl8YscWcIuUjSfaHMOnW7knZRuHUgfmxD9gP4vDkMkHbKp3T8EAzpnrrKdW35TrtgrXKFadC8XMSYVLKRfUTbrYUbXlkoUxXMgui3rRF7oSL9MrYMj3O56ItQw3NXPN8qV,xuTDGRsvqVdePHEHyPzX6X7uDqAwGVvClhPeIVKQOD6RDtnbFuTKp1MmBQ9QEfLce3oF1klymkYvDORilbgBb6379qiTw0KBNvn4sqy1s51MY5pVf4pGpvvgkM6PUWnHfBAnKqKNPh9Qap3ZnKDwaFPoSxdg6621LCFUPFuFAoPRSeuP5j6Fpg8MzRRpe7GBE1ojPaETAFb26C7g6peHe4E1CtInoC3A1EoaGI0FHo3fOi4jXYmZDBCUcOgWlwlb,gIniP21udMAuE2wjZjn2ykqBW4C0Hi9XeuM2MtXG7fpfPrLrHBYeNdpYyVUA99TkvMVvEEWRUfaG3wNp9TCqYn35JGgCkUZDVLuSruEX6Zg0lhHoEOZwIouOrOYNXLegya5QSvGVtDczf7BJqalQSaelRMhuZDjSBBb7VWuEPG6uEVAS2Y6OKNOIWQ9nqW3p32N4X7uAMORWLpV4YhKZJSN18atPOM05jzaIo3Za83OLfPzX9yvyCnhI5Qe6VMwL,48uLF3km32krMF8ltGK6ltlrD4wShM21pnhDiEygJrI4Tij6if3xfgpYCgdaddKWmYz8dzJaphcaseK7bqkvTor6JwBNgtRnpltnfoNVsKp7b6CSuiMvoMyGG3E773g9ytVdfUkkrRCBndXVqEZLFB6jhbEtEAJ4P2KYiwLV755Z8JeOd7VQSyN1kIvhEvdmmKU1KrxT1zKXPNEJcONIP4052omQ6oN9lZt6lF1iG3KO2zqTnIdD8Z0wVrliDkKs,lUOnUmd1mlZSqcY0tzgDZ9PdSy1tf5iOawmQkSnvJq4S6Ua18k9zN8R6X0NiwAzIbhGvFDN6Tgo8uFnQJUdMlE83ZKvYWIlZmDPfO2jXOq1YqyGpBZQ3rafIXdDO68e98xZ53xXARs3zc51qOe0FmjZBGtDsOItG8HkmRFYB0slAZVbLTR69FAponNrBFpbvsBZ3Eybzz5qRGQly5SxEFL9jTlWSlMYLvFBzaidA1o2w5V2e3RHTfjDzOI5zuk7f,ueOSxsPamn8oUsOGHaqmxM5aoRv2YwLO6WbyRCJ0RyhjlARhbJi2OGFrxnYWTsEsDsep5XGKTRImddIxPO1UYWJxnmtCPmnEptIvNjU8zi0scvdfREhRjB95ij3ZnA3SScRzYUsbO6NkF1wSRg4HDwDtr5LPFlqEXHBHim7d93j7zDdnlcbMJcXwZq896xXNrD3NgHSv8RWmxycvda9GOkCYZITldG5BPe63xGtKizCQrFwc9Zy7SF496pd6K6eO,SA7Ep9zvOCZmRq2IRfisW2oiohIfevGtNgriZsl2F9k3cRs0tKScAv4ZUZEZGVBug0Hxqq75oDmFp5sbN20SDl7dHp83eTmwmWAzqi0KM1vAq8Cv37xhouMvam9vHeDMMW3K771g1SVMyDYQOTUxNaQXnaOHTr1aDMAx8Ndn3hhj1DijEuxLzJD7g000t3JLfhJ6x9L2jbAALN1fKUMHKsnTCicGWZTzmXitQJ95erNGdwLFz5KigtBKFb6b4B7M,wXjKUO6yerGlANuGUBVNFkerMNymOeWK4dDKw0vwQSLARIdE4AbmyR47J0SYqwLk7oGHK770kIKqqZkN8leYyWPc0lS8kwvbL9tlsDYCNxq9MFNwYD5nIkmTj5xyOoaHYu5G63p6qxnB4XwdHy3Veq4fCChwxUpCGPb3FoKYsXARq57xyxpigbZNWZInxAEiuhALxiQb3mwDSfdmWUaimbYsybGljLYefcMQTbCZ2W2kfosEImAcFMcWKEG3Rtkn,PLtcHy5520cAfqJ80wl4ZtM39W4KIYNcbsp3D8XmPRNB4a7L0GuqQ6jeL8NOCieP1cInTkz5yQqiIUdHZsZMlaneM3D8ITR1IwXPs0vBCxXSiLLZ69Vi1nf7HCRqepK5nFs1JEKG0kBy0njWAhB25fQQNQIZZaq7K78rtr2FYXGw0BbQEvMlwiH0Fhzp7HYF6MFWkfdoOnUh93h7aUcS53MrBZXHAVMOASMcUyW6VrzCYzsCtovGGGhWPwU2JSiO,SAwGPxgga5jmAXHfCKTQGxMvPyc541rz6gpApAcNFFgyi5LPzHmpX7ZCdvTHGt3lD8wjkXQlkhy1jdQb3NEGoy3EtUIrJDzu1swS7QsfcgtxDsCJ4Jqb52Pz2uQzyevHqAlzsvWNZeA4MOMZISp2Gft0V0U0FH3pLLPh8Zd3jA2C4kVWMVYL4iZKGrnx4GNtVk9koxN2tLRZCcICcGrUbnQhDlxpldYRNKqTyP55MoFS4miyLWRu1c7iaUxl84TZ,B1tlOQlXjU4ZT4VxiGvQrw6IJmWAPY7GALbkqtaoliGBynwxBh7foTEu0VhCfaaSeo0CpvoFLSsgQbB8h1M80IKyvygOXTaszKn4TwSwgzIt4SF3Jyu6c3MNMdGiMNhVJapQVK7hO3Bdbs1mGmRxXieDHOk26khS3wfJ7Sl4NHSjHoXMqASdfLSfaK72hEtodWHqfmqRsaZaHbmnDQ7MJGokRtkISIzTBCWnb4RepqTkYRBtPWQkO5xBNQgZ3VN0,vIzQtdVXpZuK07DJ7tB6WW9yjmXluckHnnIgXdiwQfoHKODBtvAbvRZBY9hspshtmpuBzgI2LcOm40SJEhVLYgJ90zryKXB6ZOQikisFbMDhc8rPSsvYzF6jjE3nEXQgaOskUNiuHyZRVq4EfWSZZZA1Que1Fiy0Pc81mErEd6YG4Sjb9gEpz2Qq0eulqr7J2aXPY3xVk4rYKfu4RvNCAyklYBukbiUW03dZpG1wU2rKltV71LP1xI3jzhp8M11C,JSetLfWb4X2WIrdD4TNyjDvYnU0gtc6wCiQb770Vuq6cVivhP0ArlAoVJfhGkfUMCmF8ChkuL3PNLQwED9ZMHt9QYmxVl52Y4TspNoBhQkD0Uzbv9RRE4YFCZEmY6W5RRlFrrutRnTW6NXmHEeNy1nSa5OHLhJunqF6DXWXaoNvjSj9murSYWnG97pIZPXgNYamPYX9b4JlIzwYgmqTnKhzM9SwKYktYNdWlOtW3PyjXP1zg5bON7G1fL2qeFXol,KIdFVJdSmEMJ3cCEMnpN86aw3GW05tkEVwAVb51f10P2AdCdTsKXzmFf0nc5Gykd3Y7tn3dI381aW47ppteaugJsCdR38Q50Pw5QLFSEHamyfeNNCsHSyto41XKVCZbh6uekJCQ4ZeRuFDULqhkNxFNbgmn4w1W9d8zXiKs6LFJyGibsbKKAhAIKQyVohh5VrDMawOajH24jgbCHc229gk1TooxLMGM3MtdqQrtchkkRvbQpv2dL2sj9FgpksJSl,M4YKtysPw3naAgAYv3tCWe24soiB13FVxDSPPozqWmIj1XHJFEXeoawDPaqzvJMFmzElefCf6c3rASQKacIKZUOGGHJKF4tbeuykOs5aBWRDSrDCgoxCDMNY3gmXOr6AD7obF4NMF08DsGbL5pd1dDoDrMuSpHasgOv2lfUoWKGGMR78hkKyIF6pBYIvzURS4KXEeLk8XSiZtQi0fZvfpLbqE6UKibEDgHgNBgp03mTZtQObSNmSFT5a3GOcg0no,BfNcltHLWr6Zfx48pj24oV75QZ73Sn18IfJdobyOudSVBPjaIIRSMZiCM9h5xKYL0Y6L6tsMJ7OG8EdPh3tjq9ng2j1tpKsR1uySRYDs0yMSHvlun42sicsZU1evpIrH1XpdqHKzAD0aTdZfT4IsrrrxDf5481o9MEJzvlvmVaYc133toOD48Sx94oWZwOKYZNypUH0NTJ1DvUOKm03bThCy7HOcjTqxABEBAJRcRg17flYvXcnez3WO9wiwxjDz,TlC6IQMYltuaombVPmj6wHYCWwbtgbDntm9vy2Ng0iA3KgeZTH4NVqnRuMo8oHQ1ZHDXLUP77OkFLULHjHbQamnM1W5IB76Ztd1Il7XdJ34BJHeXY9rjhWOgVWGroOSbrm4Q3bCtRrpqWwJpyQz9AxO5jr5ILLc6lnb5OV3mp7ei00bUVAbC5pTAj9tcTw4RlQCVPFZPYbPh6827DCRbOFmZX1sPGU4aIkhaoiFtHxqeM7lteiQVHwenGKhBbcwJ,k9YmYvKypamUC5uUCQJBePaZWTKFqGsqVhc8TU2YMLqSydMkQjm5zUQC3pZNfiKbzJaaameQOg3ZCFiQXkL5fXXa0NVjf2hp5LSkD1WWo5lGEvYsONq8SEqRYHZPPvugjuUMJyqnUXrFXquNjoP4GbDL4h7B26Gvw9BayhuHPpeVpuIujJihaGPFcPbobToT6ZUDrT1yCZ4dNoThobdc9kodGWaS7NFNyqDNIuBW8h65ZnW2phbkfJ4KChdZKCeN,H8OfSBwyCvpj9JLxUSXQYUQM3ojbIkYbeaLlMtBWoVpJ9eMR4dlquRcEk5aiKtAWf9VTZDDi7ktAy3ZGEfYrV41EBDNAxFHZJ5cjQ93lv0TBFQgvS2VH4dG4CECMqwK0W9aAXsRhwEMymaUcFt59hr7MvC0uF7INZJqk3hto3bis6swjnQaebvKRb3uXPwMsbd7IIoCvRpm83qLJ0XkCaAwhx9NaNB0gK9osKeQoHFGlqK2q2qZxSCmbYH8FggxZ,Di6EHdzFK6DHFCuUXj4VDXpKpRlH8F0kd8VLMsTSlcCSjjWJLrgK6caR6RvcOqnuJU800NWjwA7QuAmztnznRE33lfzfA27S7nYxEUvtnzCuKRV0ZPQwTTbaRzTlct5BFGu2BwDuOURASRlCJpdHse2T6O0YUpUSbCko3aBJKD0oqaXkOCoW4rqzEoyWXY1oZwJydLUzACCaa3ldevnBkrxhf1admrz6AIBLv3HC88h6aUmprcPsQC1CaQjb3aYp,lOcvu3xwsEndWIlF0EcgN2wKAeCTLJQawkKCFokrAyz1hSAiIe4pabr0qi22bJ9THRoCcR1iqERz0AOHfDim5qc07B4CLvJtzAiigzxBHhRCP3tdEOuiPZt5xv1hseyHaPZ9AKpkAJunpbCtKmJiTlkAlcz4yQXUSUzCGEQU2bbfIJDHpb57J5T10Ll5ujppfQlrNRbL7PjSzXiwqvxFuPmLmC737jhapTL8YDLLDdAxOAOZclLk7QjFC2scoEAZ,I49pkg5VyT8rCZ2vGlKWlwHTnrFJwbHXKofHciVYCJZEX8B268ldVX3IiBBOPRq7YrSAi22g6ahybzqDOlq0TpiM1Q0ubbfwbHPVViHFxdW1xBapcJwohuNIQjycEZzqCyUuVZgJutQ3q6bbZk0k1iIwvfH1toL0q0lfMvjS1nUYuNdMS5sfJx6nBjyWkN9y7C3OGAMIn0UQ0encBuelw4KZLvvPfpA2XBBdDH96KGNfrbNhiSMyz8Gkt80dGMGs,1KIjETRB6iOzNcxW9neS9hK0d3x78esjszP3biuqIe657sUHLWT3WcyfxBA006gp2GQ4GibBXpwifBgQ9BtM5QSWhjum7zodUAm7SZuZknoDMk04CoHBWyl1kRgDg2WZb2YUB5Ij004WRGrPva8XC1z6PS1nbWiTZnGiyRRfVNDpxf4cr9vLnFThGMLycuUoc3cI5WKabr2LNQIu4IKFvvyQNNUSpxlINB40n2LM5xCiVVkF67FXDWRVozQOjN8z,Ya57Kv8Yrfn9quFVmQRs61YDzjWf2fGylHhoAf9tRaUBCs0qo0wUAL7AHajt2dH0ghnHTzg5ipzO847SnmK0Iu0T6sqYyVSiYBnffzYkC51oKXdSc0UK5h2bF3ClQ0xyry8tHl4DW7gugTXpFE6zLucBPdyy6TvsnXFbgY2BEIEu9dF1Xb2WPaf7lktbrHBzrbiWiHn7bChdUxjBB5trwHwEKYBxPlNoWysLT5ZeSUHWiG94xPbKDVt5N44CxEYZ,jtQQqML6iZ4nNuaSLs6ZNXbdJq6njCSWZGACzkdYqL6s09yHx58dyoNa89KJGBoSP9HDqGhegdlgSezU6UHj9avKLyUDOJVNC6Wzuap6yekTVJ6YCgv6RGUvDtQSyQDFylrQLn0PiW6E1XZMGPFzh1DBPomsOENmPh7zYS06lXLNdberGjWJsLalgMa230X7BlzuQeWzsUZwNt4eFzZaTs72Re7hjldHTqyxIjzNi974VO7n66hQIL9hNF7W5eD2,sOKS2EDhD9vM3SsqcCCb0KsYHbo6IBYN0maSxDqpaKG0aIoO34qTPZwdDEtEwc1PsIAYqb6YYUArHBpdNKLqd4ocBsVLjGZH8Aw5WsQTvUUfBJYc2266mzcLZnlIJzqyR7fKJS6pYXmP27ZxLG2BbswR1kd7YB5cKW67HD5a1OjtJBb58zqx8um803fVlFXj994aSPjW9K1PaNNZA96Xce7riIZVa4FTTgWnB4GIWBcvNoT4i9ZIXN4BTb3uXH7R,ggSWx6i1VMGKh26r7w0iKlYUYJOPAdV6amEMTVbokX4pxyJrWyfftx1H6Dk9TJqzALp3Atgd9axNpqyJOxXqXwfmn6v3FpAhWZJypCJE0WoVWYrLZKmSowuzxa0o0VZw2ImZBRio6ofn53ngewjYUzDOWYiV1AiHg91oP2fqe37VDhq8MvD6MkxeMVn6QG6TdgEMAF6rv6k47FwoAMhtFZcckeMwhvbKAD4QbuMLiE9Z5xviAVS3nG6xtxexKaPq,EOI9MseFPeXHa6vfMZuYg7cFDld8xQnoUZYPUZjfWjz7GOhqw25kscdWwPXp2KU30l0cs5cEr5wNt91H5U0E9LIQi9iHvnlGpYbo3atcxkIQrX7XzBOnZZAcd6li9Pok5PzE6C0CxwxgZsBmThEb0RzIVkEGyqexdCCmuTzAbKHaaRf0e2NC5xycEXD2MBQIvJHqzqDVHzWgbqGODf32oOiX6ggHxN7hToZ4o7leQMIk6PkHlG9xMCIkuri6R7Dd,J2XD6oBKuXbwpOwsb4JzUZaWNFJbFUWiBKnFlKDUnTUDiMzQQhXIzt0Bwem2u43Wn1WIgCSg0olQ7oaCUW3KVTGwuImQHZSmAqVCm3U6YK5wzwZEaisuiZpGIgkUYUdTWcW7QmAijV02zS6S8GxNyWglMyH3p7TJTl3L1GZINYnS1va7hBsF8PaYRaZZp98H8RYySZLcYZvao9VZk7iZdgZiVhjcOok1DtC8RlhG2V6X229AjfkSaIuLBjZ9NfT8,1Og5H1LyJ0NyOPizQSF21O2sr0WZXfAX91vnNCtasotmYvH57vrb3S9PhmRtqjmreMdweW6XmzTEXpJPUIHg7TE8SmdpMt7qEZbwZhZbM8k3tplLPJIIchLuQCrNa4tLCz1biFsAxFrT0KS4ZYwNSoYCXRghREPcpNBhgWZJ4zLSzp5fXmfsvkfkaPgpsYB2tnkoCtRMB60mCOCJWxOwFWI3OHY5ApV4uf0p6PIy4Pp8kHkcY5xvuH6neIZqEAHX,47k2fzJaR4FOHPX4G0mmXin1oYpQkPeFXm8PQp9vr2HisrMM77Uv1DI7rX3uKCLs0ZtPLaiRgxw5NssotyWIF2uArJCVPyxSRSQgr9P1l4QFG6pr00ZPTZwckFeqhaGlCIuO4UPmKWcyK8GGAaMhTiHaAfuv5lByQaLVdkSNMKRVPLMwUGYc57aE5mSMh0QVqnApG2nStNEwJAdjBICwqMmsAqm4h3h3Rqr019B6wfv38jrf9eGa3QfHpwBK5qL4,zPHiBFEIzxf6Nyea7aQgaIudVB06HMe6Mfo4AFnsG33d30y506vsVoC89aPJbMxk9F1NOOmvrLnmg7M02xdpeSnbPdvLwrUS2Hal9s2Lk1bxxH8Fj5FTeyCAqo9gnH7FwRFHVTywtFrOLlHdHcEE8uMVQVuCMu9FYUsILaZRYBMTjJWSde6iFEaBDm0VlZTCBg7BVZOPf9uCowXqxjx6hH9pTHSUrJC6H3a1i2eNm1otU9PWltVs3RrTmRsjWkAk,ANKUSc0jHJl81XjgkbkeNQS9hEIHSixCMEv6iNZQX2ZXnISNwoyFPVpLknUnnQH4xGpH1KUMeUiEy7pCYiIpTVxrrM8J7G8VGyftQlaJNBNUDxnMqWSf0fOS1TaWctzWPF7nkBduQFQQxOhyLJ8Ihbh10g9KxDWr4pLXm2Nd2UR6yTZuBgIuZOuxLtsdR4jaDkB49zxJXOAAiH2JTBi2MV0Z760WXKRhZnOaxspTDfANuNVWNYpmftTTYyoS6fO4,dDSt3HsJpqMm9saDEIZQnmXKphExQ1MEr3b0Mcvf8cLh7d862WLpGEnQwIOqoUAyKMI3uLMzo220MVHRMrdGptQ17NuHVO0A6C0MkUsfkoJskJRk7Hl2tT2FdXXe8o2R4TNrcvBkltB53yS9Lw9L9CyV7lo7PYdo1qKdkuAKqkQDswWntjyanrpI4j7dqYvb9YYMjuB4InNwYapDgCRpYwH4zv7bnLC12mrEg3y6FdRwmc65xRESPpipliHBU46M,boRgD55dzMFqZ70YuA7GzRdvwVz5SIOUmlj2VCaUpWD73MkeskZcjdlxCkMM03SuNCU1uSXodVDZy3Ldj3NCDhfka7SKEiK3UFPMa0Y6TOEinQt2laNJ1sesCPMZDslThL8dv6VcwtrcwuXV44L8s923SniJAPlkcSHkCXV1FaZi5n4lRHisv75xNrwoUAad5MwT9HSQGu6qaAdpkNOWaNDaih47p6FMnxJQ8XHfwdGYBZshYNLti7Mw44zK3u98,BIGX1NWuxUd3y48Po0I1TEogANYQGH7UJ6sjtW2KFo3KaDOqV0FeneKxPQ2OMoDwyGOFWAXhyZQNL5Juu9EDjntjSUDZE46Wod8zmsq5bPU9OwHRsHH3IxIYOEE4lSLnRNaQhBesigHl0TIF88Zo4qDw6NZMV0FNv6CKZgdWb3zyymHYZVdJBYPJkvp6ffP9HneNlOgSlVe9ZGcOTAkfAVY3423qjB8gYtN904oycRK5j64muvRjsgNBVFzYcJli,xFikbfaLbU35wXf0f0NXRIUhS9DYlHUTD44vX75880qarmP0FEJDgZZan0560BkWf2vsHgq3ddqlKoaf27lHK5itNAxGcdG2ELNsvJuLbGrXCUewPpP0BokuCwpP6ISE39sgJbonBpmp24hAFnKphj7XBIyR1h8yZIJ1IaJ8EeQEThv27DkK6hBRpRQXIPnIgPQelfW3AO729JLGGOxKu1mK5uUgfPNdGg6A0yUjGReKOEgP5AdPI8oCmuBmhzih,gBCgaQpNaa3couvnfVBgL3bNsJth2dDmsbvix1b2TtZaMD38CUciJmnXU3BLEaTR0rx8PEwElOYw1NFrre7WUNQ5qgoWndZqmZWNghW4oyuTySE94c0P5G1Mxxp6ru5g5MCtrBXQQUaa5J9TLItZPPBebRnTXaFtI30Q0HwM8ycns1vvXQ6GBHYkj303BUOl3LCUuaOutLnq8aujBNmf0LvuelQA2A2QPtYdIALVkn25bmmsj2aw8mBedQlCcRUD,zevpbHKsC9YVbm56c7Zi64cJtSRlrnBNapW6l3mXNeBt3tgD49JwAAaKGfYlIIfKUDrqDfL8AyHlK9wNIk9sceEZPvCzO9TfYoxmgyT9E9uFsyzNFy8qwM3lHD2aM4SJzmSV2N4O7DJHflzBNlX1x3FQu8xF7Wn6OtW7Wm1e41xUhmK41y7yZDJ2B7q1XdSxw2AMHX59WggWQrFEuqweDWk0udEULMZh06Lb6VG2f6eFgztqCSWHf8eFRy5HXgkH,JvXdoS8IP1yqDUpSat8aSbWytQiyL160HW4ZS6J2aooFKTbXfB0Kwat1DTrcUP8Le6uNYX1FMOi4cXbzulMDgcNGQfE9joZkAS9cemumM35KmexFRKZjGCK6GJAE5hUeInrPdwJChQPShD2En99h0066mWSKHpS3o8baBXYTSsdNUNGhmYSpSsVSXhhMDF0GPLLldpXwi7cJqdIN1chMHuSANOJ19rY0NQDurMHXGYNlLl2HN8H9yAi8J28XYGIM,mEFJEN7h06e0quA6HLe5epfjAU2uLH9VdKCd3n5zwPMbtmkGJfHBoIQzzd7Nlsz0hCe6VdlKuVafCSYmKuja5bDiiy6iPfgheYgpxXHjLXLqUcJliTa0Y9z7ZYVYDD0aiEUL1wF3Q8oXrgirTwOhnq9yjtGRnVIR4vObfxLbWGVzb70LpryLcnzQrZHo3G3FJHWQlZlbZYjnHAoDp9ZS8XqKVm8tlZKL1epchbtT3X9UvWpUkPe0AMYUFnuWYLLB,rInsKxaeiKCV4iUKeAWe889Rm6tXnqp9qrHv6cfBivXa6ontgMtGIjCgMJx0evsdQuZNwj3D7LGCzonNewP37JApJYmiskTp5my8LXOHZexGpamrwJvGLY1Zm5JT82jwjSRwxdmJkJwqQkBGIMzpP53t4qUDwNw86GUzzfKQtutmWOHxboYKkJRwUkqUNYFsgxl1SVKRWeUltlTAK33WYOMNPQ3d322HquSwysiijDZM5mLmo4DBZgDhD8FvrYT2,xOfP6xy16KjEFiR933LHp9QNZOuKq4kdP5p8zfQdx3nuY4NeRe2mqh2pynVqDaVWbUXPYYfMDwR0FIYJYQpgGynEMnaNIoE7xua8Ux8SxXkQhhyH3NrNugm40GeQeyxKO0lPyKCsVjmoQWHadmS3uDntFhukXmyUVqAHGL3S3AvpAOsHnFrkcWYKBuZRAPeflSUuxCGLgetOrO8gdXmXVTvRAoPQ0VSQ5iaHln9esEfLqPHSOPgepndVGygtjpsc,I50zdUFVTigTKgKwvrGC4USfIlOyrpfg8tQZDk4SRdWFwp6NmsZNO8HlkKtZAOuiSLjLU7srHZHFVR6lAG87DMo5yc2ky47GkLAEyHbhkIosx9puxCCSEZGXCeBMRQYLcu7o4BpoMnz64s9z9bFXQOHbTT2axFi5qPAqhHzrxWd9MKr91S24m6yulWHYzLnHYq9HOHzME9X91CofS5R0ESZSorpFSR7kTbkxdI1o8AW8i6f4ztkNzvDzCAA01BKu,Aw9SLlfmoMAJdeDtVFokECkVR6YTPJSR9NddjbaWN3iHE9FRqckEhc475QBzqDF2DOxZqXOnHOLZinkoCdIpWEyj719jE6fI5zWetjvh3GwMxNfyQi147pzbpukl6RCCawcRaAkKLose2XsyiEEqklRmowV84J5buU29Jluq38fqK0ShMgexuOXvztqiN8ZjWJj3JYv3cWZUsSKn0wgNBfrMHIl2JJp8pVe4M1Cg8INP738oywNtwBtXfXlopOzO,ElzQKoGrjRtDmVh2K3GtduxzPyAZMudXBMV2zcgJWdxuxP9crZXGr6SLCWFegRAPUG0BqTnIdi7QYo3jwrLbQ2fK2I6qohtAMiygjjRKzJqpR2AxAKUfZxQzjDQut9YibLJECMHbIUDdbbzurzP2ZyhKR8H7TqwOFyZ728bKDNaTzOiv3TejEWej04YA4DZmI41oX83LndBxf7z22QVtgeOx4Xd0nDKjlBLf96X15QdKtcFVJD7wRft3ztDvDi0W,1tKyoMDTaVDPLKJAXnFhMM7VePOebpbSF7WTfV9S33uxoagCo6T7sqB75x34ieg7rX1GAGz2uJcm2mLeR5rLqWbySqTkc7qMCjF7GDNHq2Fkr2wnllnnqq6pMzVvL5BHhs8Bk282LO6rWHYYqdB1GF6g1k79P9NlR8T7T22y7lfEwZnGirKtqxFQdmcsYiLZCoOIKjtVeByWFEdXaS55LJQKcXIviH9RV8oSm2ccJhUV47mevkcQCOanDH5UmycP,NDbgxpKlksq59mF2fBZFNLUSrkhmWbT1bM4Wx5DV2rhhhtr8A5TXQ0gXRDlnrWKwDHNmUSUMB0IY0C2hsMt9l7j2OHILTq4y6QqJ0Z5qoVVwf9LrdeaXEaAhYylOPBIta0dSzu8tULafhZ5UlT49cnkBFVqe36kAmPNdO5pN9bU31FfIZaSN8NQlb8A4isAdGoicCoLCi6eRh94Bix6O9b5NIo1L3Tdr3ApIYa5TpEtWc75EDHFbaOVAKTEXYg8a,8pfG3Fn6xbVChOxKkI4eHLq9llueoYJPIiGIwsWJRptTTLpSjXxl7ZORyUvp2InOwOkoL8VpDyPv2lqCPAIZIxUbHYYLD9q7ZIljWxSbw2poHkwobUReNubFnmxRIBv9Jbp87uWnTr2MUg2fPkWeGDooboqlRCnBokbriktF13k3OXZ2gb4xXHnWFifGliRHNLTonkZv1xNvrS4eLFXBZiIz73raLeOjnlWjJDni1ZI1dMWkPxSWuBNgs9dZQI3Z,EFc9eIUL9wZsiUHNiTyfPkI4sfbmHPDChKyUWoBzCFGX1awzmQEbHc2XeGm6s8L0kaLFWcVtQMjgpqDtbUInm6PApejwNZG6lSbXoaQkaUfcWaIPr21YUf3lZ5Z4EXsoAY4I0YyvoCvQ7JmXH78CXEXT1qTR60lPbWtM297AaJY2vdSI9XM7FtBYU5CnBR85x2ePOC2aNVjjwPbSrlcvXDxOuILcELnrwd2377x8CN7Y0HgWZ7cPRDRIlrIpVeWB,gvHAUY56tiD6V8Y5BmvpYqXbfyKUzSwpCEhZnj2lYiW8ZC0PiSqzzeFmBasrg3oDM7DykgASYe4jX5tyK2o8QJDA3CuJ9OblBDCITsQKtGubKUplfOYN5Ocy5Sz5RSa9T5SPYssSvbjQjVeWnRhsoBOPMsIym6LIowkmAuuZpUd01e9mqnhnQcbOwDG3oPrXzxQafiOwlIOiizlP9QBS0uoPPektKg2w3KSQ85CDgvTRIjtCtIkTGlFRGoRNHCCx,71ltO1ytPx37nVi3aEYE42yOpBCs0ySMkTax6Hg3Rleull3Mhag3mdTyAxmGGvIZUdJsLYAeNHSMI31WDfTqX4hYijqXTVEgL4t9Rbj5HUDxGFq1XlxtoFSd2vB9BEIDMjaxLudNxNnnc9SrZqQgAjBRhv1lzO2BiWcXb4cIcYQTAltL48bICk0ggot9ddKCAkPYK3Qxnbt9nfBbQEYgf1Wb5ych6acZNSpSKm5ooodI7Yhx3QHKl8IlaS40xfjq,LjOzgNMoeKoS6T6GYI8xwHxrMwAMsmPSHvBZlJjAlaTRGR4k0yNK0PNWg6MP2hxvpJvArmMFiHh8uAMi4L3PnBXVcnPigNc2fkYQwFMUaxlQ25EtPRVHOyMyGQ9EWF1CuSQITthhjvlEH8bOcamqo6ETSvjJsVBl7L2WTiwNrUdnTmVHjKletPsugw9FbhVl0aX8KBC30cYa9wpl1azs8lkhXbKcDLwGbG2tLmRSwy1Lc0Z5wv9M6NKc4sFC3REp,wsDLeUa5j1bCO2Q4LBzhSR5GpNz3nAAjZ7obaNYlVSDWLkw6VtN3y3UEhlgqLyELYIabdNku9n9bb2BOErkDCqFIXYwd2kv7HTJWqgAjrmkFyKMQ91X3TZWfINN2hpJbiwlAoNnEJ6frvxyeZBCIimYA1oMBEpu5sq62VRwTDTeTvTcFh3nj3eZnkEvKaOkykgbI2sQrQGofIbZVJhWXaiqz4LWdDiTQPdrzuBKceMBFFgTbVvychFaJFuRWMfId,aNIBmNfiZXMDT6ZgYYcT0cehbyTrNFRwEeT0XL3zfbKomOzLHRa5Ef7VUEJrPsvHmT4qtf2D7L8erIN4fYnaL5jVbOkSYb0e8gLifF5y9L0kzxhUF6Udp6IARZ0iipuX8OWs1Wl8r8IKaKK2nOPRH88tCEiCAiMVN7D902Mfdlzoi0uj2N5usYySjAAMnEyqxyxhfLjsBWp96MgInyDGXX4w2nTE5KU1dkDjdHSNChra9baU03WWSfMN6rDDlajt,JZy0Ypd2UPZv7UC89q6mBdokkNshqHehixOzemz7mc4JlQ0BpOtP59gIUWKZ1uyXXpfVzpUsQfKlm3JCDObWXv1l2O8wGIBjGWHAruVd71fhWvLdvaNyi9JA3lU3ev5tlpCTAwuW3Wzxq3wfisDoOhnL8RyjTamD5qVSWrpRKK3y5rBER7eyjB1LjG2FWHGBBKS4rub6W7Lgj7iaeHrMpqPI8XgyUj40TWza9gq6cDJBN52wOnlKVhgqOxn8fcrk,ZaIHZi7p3kDUDZRamcNHOW8n1uvkkAucyaXJYKGBpYP3PUevBxIlp9P9Cr4GjTj5S0HaasWYI5XFOXOcqrZ9wsupqbBpTkZIdee6VjOkmDABO35v3oDerhh590pcWWmomazakAJKUYjxqPoHTsip4kjoBiHNcHwP7KbwfnfUlgW5JzERp4WtbOgj2I0Ygv4SatFGBNn2Wp4A8kHLehzllOCCkr7uRm86O6ZZHyC67TcRUkBoWNF51BOEy0lNBDhN,CcGwf5zpk2kVQGBRkHozU4cTJPkNRG37f97NlixBeqnPdkqj0HXOaQ0GG28sQ77IEIm5ucQVkyITYec9qRbs3sMFsqGJfT5LrNwKRFcN9XALyDAfartePNtoVNSRxyU0sFvUpUG2ooriKj6M12HMh0lFwcGdmUJGvMMxNBAKky3gRF3ZytTNuR1rjvotBg8DXgPqtyN4Kb3kzhfx9CIlzQ99TuLTmiOhvMZ1YmFc9YuV8TIpNI3RUscUdSsdIYZR,pSwVMPjbLDJ69c54FNOomNMP2iTJYEFhTkrib0cVFwrI5E4wfuhw7H4ordCL5GxGmb7ChAtwFLj2fzDugUn5TEBpd6vC5c7pvh5vrtbshkndJ2T967nJoTUlbW9emosRRTDxbBdro33rO7gin5qSOHVGeV0MGMpaUc2dw9MlhHoDRmCETgqnskuWw4k2kpqzTtN09e7UGFJpTULarGVdEbTYjwWJVzJbaeqxwhp8g5R5xqFZSKPywqsuV6ktWjLB,79MzpbZF29PLCNsXaoAVsmbfDECvNFQhVJ0est47GKFdfEjqgaMvjBgsOkLrceNh0OcZjGBfqbi5FTC6oqg8MumockLpQu5e9GiweuFoRoHhhy55Z4ScVNAATjtg14Xa8AYXd0pCyspNQ4io9fstdC70Q7dxu4ONFe6Rwb4EfaaMBVrgkuzSPUmsbM6PFcLLozVnmN2nNeOshvM3jtUuNJFelwdDN0KuF9NEG7bGszPg1lbXLbLmdkceHQibmx79,q6viL3PDrJ2bHuh9cIo4F9H0B2mA6VHqMdpdeG617hp5PGUNuiA5y5qGKjxyrX6LTIWRncNeTBLm9AjkmNRceSDevsCWLc8acQydKqwpBl9M8hnDKWZMKAZedQbk7U7n5BTuBNGJjgN9hYAMk7whlTuXBRlXoOcymr39N6dDIG7f26gNcMpEG6kMS7mj9aCARsusxKfQsf8Odqg5rkvFdjHwLc30Aa2qqEvdQr4JL4A1WHvZudEwipILGGJEn8EU,twFqdzUwSaQFSeeVJy7HoM3sm08f4zC0x0WZ9CTnd48h3IMfrIO9SVLR0ejKE1jykz37C9orrkUysrCuhK5Uq3C096Zd4QJTr5fm1hF8SAsXaAOvf3uokPKwC8yYS6aIbBh5bgZ0VZJCO7eAkGiNrP8HbTZS77uSSIPe0wEUsfjKQwwwLfiGoiU2kuiTHnKrW75rpkUa1LAIOuumXJ46lc1Vm4uJyo5NTDcu1Z65sHNOyLAWgt9yIxqvAxU6zPye,J0UhpluvoDMMsLzmRXxypU4k5L3kX1JE0WGlk9dZe5DS0PKT5xoYr4sUu1FgEyBqa1vKqzNH9HuFAt'
2017-10-11 11:50:23 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-10-11 11:50:23 - DEBUG testThaliMobileNative: 'Server data flushed',
[ThaliCore] VirtualSocket.writeDataToOutputStream len:16384 count:1 vsID:6
[ThaliCore] VirtualSocket.writePendingData() to write:16384 written:16384 count:0 vsID:6
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:6
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 0 vsID:6
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:6
[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:8
,2017-10-11 11:50:23 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:8
,2017-10-11 11:50:23 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:8
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:8
,2017-10-11 11:50:23 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 3285 vsID:7
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 3285 vsID:8
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 3285 vsID:7
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:8
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:7
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:8
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:7
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:8
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:7
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:8
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:7
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:8
,2017-10-11 11:50:23 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:7
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:8
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1054 vsID:8
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:7
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1054 vsID:7
2017-10-11 11:50:23 - DEBUG testThaliMobileNative: 'Server received (5475 bytes):'
,2017-10-11 11:50:23 - DEBUG testThaliMobileNative: 'Server received (6529 bytes):'
,2017-10-11 11:50:23 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-10-11 11:50:24 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-10-11 11:50:24 - DEBUG testThaliMobileNative: 'Server data flushed',
2017-10-11 11:50:24 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
2017-10-11 11:50:24 - DEBUG testThaliMobileNative: 'Server received all data: 4yZpqgpXZOHSKp0mbg658tWlqEpCXWwx1P9UXpjmVfDiAzzr7jiolREXuFvbQkx11maZ5HugOhSMU1g9znFqTCn73cPU,2kf8JfdWn4MFfcvDw1g61oqmiWz0wpaF43S8aNK6Z9f43hxIWsPoTJtu731SbcHcv0j2jFMqtH0XA1VWkvGBVAJdKrNY7vDMhW4NZpPXP8a1no6edOeFxlui9drunCBcz5KQKG9aYCOaxPnpoZRAzYvT9ynJIuQ0w5ueyA7LH4fd5XIB8e00WgleWGxnEze2MqtRFT7WiD4X22BBRUlpyj0PKlac9FyHZGEqoSv7gY3BUmcLavqPdJLFVl8b5NLx,cRYAbaEtnSikZ8KOSzUJzQ9WAWvG8I68jTo8y9Vy90tEihJ8VxXVNfych5eziz6YfRCkbuovikwx7gDzbdPSyQlXIufJvslNnJ0Xpiwr0leQC4S3NdrINv0CAlhOplLv7gV8dIfFWhUihHeOpYfqgVaM37xPhMwSur6Z77AIiGD0Py9Ndva1yc3qcpVhYJkzQlfXEnmVXJ7O4RSnv8uYRwn073nUhus7YaewNvUcDnn4E9cCDrnCtFeyk1Yt[Tha,liCore] VirtualSocket.writeDataToOutputStream len:16384 count:1 vsID:8
[ThaliCore] VirtualSocket.writePendingData() to write:16384 written:16384 count:0 vsID:8
cNaKLTriAnnI6WqV6R1oEfHS1zYPzjPqkTCTdXJba11JRnnEqmIfyDTcYkCNcTiC6QKvv05y1ZQZfvkM4czVcbXKMeK7HQ,1xLva5liVp58zhMSQM9Hffl4bj8jX3sW7uZfBUO5wcpxgLTnCdnRqS99LulDyrFInidSKLpfLkZMImXZB2CanyHXCkPRPEEmkwU6vhpZOSyxjbnqs9UbVwVVAPYY8wlzIRZBsIqSMT1wZAss4nxrm2EzwwyxiOwZ9KDVGefLRS8Jyzx6WQL8SvWXX6sMonFPliOm6tE15vV62sVn1QbFjIhCcdakskVvhLpzSboODfpOha0fCB7GUWYZo25lu1r0,IA1Kr2B81YYqQP8LEGMwsTuEa3S4b8BtNMC3sZOqI3VNPLTuivU0qQ77w4VYyDb2HMJDEhiPFe2ujPv0Vo96ezOdMPYc189ed4PJryvDlXYumSc90NSmTVywJf5k4hw5LE7SeeorxWY9snT0eMvpscstwKMjumbUcbtlY799nc8kmBIEzDrB1WUBJpE2LP415jYNHf7yP0zqsXNSe2wBH6yjW0mci3oIsVTp4k2h6tJw71cDNXEgfEGbkyYG4LBn,i72EW1ZNRZ6IYkX9z3JpQswVH8aRDyUTELe1oqBbEzed2rN0TuXrMmUXjF83mDDDBsEjrKNn0rHE8zw0PPXBOr4xmZZPecEQamrbcJE5xJS7RBiAdaHqwanWQDU3AkDCAqgbRuqsKJS8ghyArUFjqR2LHk4oUJGkfiS9gpLNVyLxeLqTMrX5LAmjSB2G0OdBzbpa1tFH5Bj3x8tSbXf1YwwK5QRSuWgIgGBUIPtp45wLzP62tsKorN1BlZhmhZPk,bgTvrYQRZPd79RsYHNYhXkvZcjqTZ6Isc8rr7y25idzBw6UXxKvSZd32OxsIjy3B3NSJqA7ME8mtonPwe5QKMBJSIhUBJfhX4D5b5iE62N1IdWjIxqULUKfwxppEvKil536SdugBIlokNTNUhe8qvl9BSfX3S7yV5MywQwBptDMTl9vhocLivjLcjFRfS6CAepiVP63H3jNtMlIiL8kIVVkHVjxXKvViyNlB42UKfCS9KayHTIkk6VEEabMKmiBv,uHbftwxqj3YJjh6PsO0ENAqkmZjTjR7cHUlk2vCR5RvewDPZwwCT1yNtrX8tUT38rGBLSIokCjkdnKMYZ6yLJiR9RhogC2eSWl4wW2Px0uivfbp74x5Tuj7H1ucKYQtTk0Yu85fj7ROvJr7UKNEHcjnkDgWGKaC7kJrHd3y7zf5Vk4ZaL4KINLC3bwcQhklKn030d0ONddbzLEpTzGSRvgW8lnAeFfR7Kq0c1S08b1n1AOpdI1I60dYqipiomK7t,RCo18JAl3hOS82dKCrzItQglJk9vTiC7Jdxdjyyi6S1A2GdAPotWXqYK56vQqx2Aog8zt9rk4MuMsvtb8dSUKsyDaCGpxGc3G7Wmhn8UTJiIVb2wiJg4AqKZR6TyxKRxFHEMBvRPmDT6KH4qGkiScofQpRgM7Q8xzrRH9CdWBamInsUAJ44wQzYdl0mrIMZuonyxuDIvRaa8WouECHdedSDHHeLkW5d10BEuZVucTghyitOuCZy2qx23YaoVeYqK,6UuJy3kFjI6SLw0swRya21Ie8YwBYOrGDlvPA8gMz2xWfiwWIrsKvARIycEFmPS8PBGV0LgWSs40rBSSkvs47KoFLilL3dv2LGgSBcwBReFNG0qFnSZu9fbwea2o9OWYzM2jhoZDfHJ0dg2Hi7S1IUw93SJqPpywbQh9ZJsxOMaXRgudDWOQ4ekrzPY1Y9lXIbmv95Fm65mLtvwvMwmSc2b60EDAFLId1wgf6I8QQuIRp7jTE0FdcTGnlYEIPg5l,qy1JaKLujhqhiob341PIjXOTtGazHlSBU7YFnTRCgGu9J9xNncNEYG0mnRjx9JvhDHikaNTpR7ZMpbZeymrAnPMzaMpdy5UZmK38gWynEruLQbNAqDXwAbaJRbzLPeTUUaEn4xfoBRvaI48Cme17o6gbZgB1JDX6QOnX82ngvUhPn8foLYP5HYusW3sdqm17EdTkdgaNoJsVFGh6HS5PGOd6Zcq7ePH6tEYPpu6hDUDPucpxNoupDyw40WTNF2n4,bFNjUZK60Y0kl6BDvF4A0DBlNM3t2mPycezogG4zOtVTL7g5RWzK3fFNH3x6kyq2YfrKJu7coT2ERdFcUJtysWbMI6hvITFmO8DV1bkiyDhBE8eO5WE00cMjWrBLiFEizp7CR7NAh0SJKEWSLXk7Dg78ZukWZJ5hGr90MqBoRRZdHtuOr3YO2iQJyvKUzcLGNpTX1kzOSY6vjTHK4fmJWKe4Inx5yi8JNdkaZZ8ZtC5cLES0TzJs4vifzQL4pGgo,xs9vm3srKzPiigzrH6UiDNWtF5sUvyWjZ5Pp3i1BuIdJACvCufcDJNzdDRaMcNQXglyLnRrd9IGyqapgkBOxjbFEhD8FbWKhqNj8sYP8RbRJoeoLXEQDvD2AjVZD6C2MVO7EavnKGA2C2BwdIr7GnQODCmqoYmbBOHMNcTxpxJM545N8Qstgu7OZ10LZKPG6dQQzRrIXMDj64PwMnwx29qa40xm4ofnAUPmyMMetsRLiiZp47pmPM0W7pFpZEpAw,IqZSjhhi3zTEzZuDADFYIvP9Es7nqN1UUP4sUw3SKltm9PpI7z2uAyM8u80HS2SyY1UclrHhFufrtOxjxuu1m1LqDqB4ZT7TbTzsE8T8joEw2I41J5NFGYMmaNmkplwcaYLUTqVXhV1XIYCN58tLv2MoUK9zmZ66kxH9GQHuNLrhIzd8hWeMoISndCNE7e04Izq9iU2XQjA77F6V3xoCynS5DtAQkEx3j2PhU6jRvRSz0odCEKTuPCLVyq2ZggVc,1LzwiLQKoE8OzMSOTyHB2Sanx0Jgn0ubX48j4ggATZLCFyAkiHHyyUEgpcDuijf7D4qMGRDx0A5otliacrRvFY0KUh4tqNmGdDimcL2eFXg2P3GuluExPu83rseLJwWsFqDToMb7KjLXPKaERh5RSkTBEGgdQvjGGz60gVpJqyvIS1rMJAHoWJSU52pRDy0gLxRpsDdNrf2LZVRTqBiHkBu20e6v22henb3m0H1XpxaxjjfyWkxXQ6uDk0TCOZ8b,LjNpKRDerfQteqIdywbJqWBd0UDy4o1x6aEcyUDQ4SpPUQ5wI5JFYqzo8XMLqRwsuPtlxDKuabHhGFQzDhLBOOaZWFMaXDrm7otW7X5jV2XlYmGzwWb0cJ92Gykg3Uauwh5wVndPzj8uAkEjoJEEHOfVYJmYl8u3MxbxnYpRDrKebT1iDkBgJewt8unvmqP2vEzsGcLrAw1y1eBHcfoMfAfO5HCCtccpYaAYIUapPEtZJ1tOKDfhVdPcH2R59BTB,BARqgVqsJidPdrOlpSsr6e4U1Lr1FLoHa28UGdf91gOCWTCmxmnM9ynywMbEPimuKthgCV4D7FVdu7FqdtgGZVb9rZtgmGquRxpbuVcRnY0he24arnjX9CLMm1L6C8O5FcxDaHlg0HkgWVKJDbNkAIV4UX156a1Y9iEjnIDwTnCsGPkSOdvEvGEzd1FZz0WghD4t4DFyJEaxcf21Og0ezb9dS7AYYrUUdUPbqgWAhq27ZSS5wYyug6zvIdCoPazz,DoWdJSVPU330zJN4GLETLxC006kQUfsetCBmgQeNTEIR7ubLT9YxJJm5N5k07OyFg0sfMSTHgfuPYlN7fO83f3NPsEQpkBUtzF1YJbvQAuW2YjHOVwxSVvL0SM6rv6thY9hpgdeWNdnbO1pTqWrKMtMvlP9MVPso9RtU13tUJsoYO0zGkDfbBajTN8SQ31L46AeVhDbf8eppkx3c8kwBAKTQEvE89oSAG8g91ajqvi6r6NT39m6p4Extjj1[Thal,iCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:8
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'
2017-10-11 11:50:24 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):',
2017-10-11 11:50:24 - DEBUG testThaliMobileNative: 'Server data flushed'
[ThaliCore] VirtualSocket.writeDataToOutputStream len:16384 count:1 vsID:7
[ThaliCore] VirtualSocket.writePendingData() to write:16384 written:16384 count:0 vsID:7
[ThaliCore] Vir,tualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:7
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 0 vsID:8
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:8
[ThaliCore] VirtualSocket.closeStreams() vsID:8
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler d,isconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:8
[ThaliCore] VirtualSocket.deinit vsID:8 [4, 6, 7]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 0 vsID:7
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:7
[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:7
[ThaliCore] VirtualSocket.deinit vsID:7 [4, 6]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-10-11 11:51:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-10-11 11:51:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
2017-10-11 11:51:14 - INFO, CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-10-11 11:51:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server ,that is not listening yet witheatNotRunning set to true'
2017-10-11 11:51:14 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
,2017-10-11 11:51:14 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-10-11 11:51:14 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReache,d handler on multiple db changes that are in the checkpoints plugin delay interval'
2017-10-11 11:51:14 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints ,plugin delay interval'
2017-10-11 11:51:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-10-11 11:51:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
2017-10-11 11:51:14 - INFO C,oordinatedClient: '***TEST_LOGGER result: passed - enqueue and run in order'
2017-10-11 11:51:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
2017-10-11 11:51:14 - INFO CoordinatedClient: '***TEST_LOGGER res,u,lt: passed - mix enqueue and enqueueAtTop'
2017-10-11 11:51:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
2017-10-11 11:51:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are a,lways executed asynchronously'
2017-10-11 11:51:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
2017-10-11 11:51:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
2017-10-,11 11:51:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
2017-10-11 11:51:14 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
2017-10-11 11:51:14 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another ,skip'
2017-10-11 11:51:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
2017-10-11 11:51:14 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
2017-10-11 11:51:14 - INFO CoordinatedC,l,ient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
2017-10-11 11:51:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
2017-10-11 11:51:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed ,- test sinon sansbox restore after test end'
2017-10-11 11:51:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
2017-10-11 11:51:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifie,s USN'
2017-10-11 11:51:15 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
2017-10-11 11:51:15 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
2017-10-11 11:51:15 - INFO Coo,rdinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
2017-10-11 11:51:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
2017-10-11 11:5,1,:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-10-11 11:51:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-10-11 11:51:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-10-11 11:51:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-10-11 11:51:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-10-11 11:51:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-10-11 11:51:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-10-11 11:51:15 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - Can shift data via parallel connections, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEE,E81BF9/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/t,imers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1
''
,2017-10-11 11:51:15 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,[ThaliCore] Session.session(_:peer:didChange:) peer:310847F9-0DDB-407E-BB04-355C1C3E5A99 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "CA4F3AF0-C6E6-4A7D-ABF3-25A3D4AC92FA", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:D9BAB450-56B2-4619-8D12-1D81A214243C
,[ThaliCore] Session.session(_:peer:didChange:) peer:D9BAB450-56B2-4619-8D12-1D81A214243C state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "CA4F3AF0-C6E6-4A7D-ABF3-25A3D4AC92FA", generation: 0)
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:D9BAB450-56B2-4619-8D12-1D81A214243C
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:CF3EAD01-0759-464B-B522-6E5D1376B433:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "CF3EAD01-0759-464B-B522-6E5D1376B433", generation: 0)
[ThaliCore] BrowserRelay.closeRelay() state:connec,ted
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:52100
[ThaliCore] Session.disconnect() peer:CF3EAD01-0759-464B-B522-6E5D1376B433:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[,ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:CF3EAD01-0759-464B-B522-6E5D1376B433:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "CF3EAD01-0759-464B-B522-6E5D1376B433", generation: 0) relay removed
,2017-10-11 11:52:47 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2017-10-11 11:52:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:52:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:52:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:52:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4,B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:53:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:53:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:53:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:53:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:53:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:53:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:53:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:53:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B8643CF2-FE60-44D6-A9DE-05A1F25612CE:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B8643CF2-FE60-44D6-A9DE-05A1F25612CE", generation: 0)
,2017-10-11 11:53:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:53:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:53:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:53:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:54:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:54:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:54:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:54:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:54:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:54:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:54:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:54:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:54:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:54:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:54:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:54:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:55:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:55:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:55:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:55:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:55:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:55:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:55:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:55:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:55:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:55:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:55:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:55:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:56:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:56:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:56:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:56:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:56:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:56:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:56:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:56:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:56:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:56:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:56:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:56:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:57:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:57:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:57:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:57:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:57:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:57:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:57:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:57:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:57:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:57:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:57:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:57:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:58:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:58:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:58:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:58:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:58:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:58:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:58:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:58:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:58:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:58:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:58:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:58:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:59:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:59:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:59:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:59:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:59:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:59:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:59:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:59:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:59:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:59:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:59:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:59:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:00:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:00:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:00:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:00:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:00:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:00:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:00:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:00:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:00:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:00:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:00:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:00:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:01:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:01:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:01:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:01:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:01:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:01:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:01:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:01:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:01:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:01:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:01:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:01:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:02:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:02:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:02:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:02:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:02:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:02:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:02:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:02:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:02:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:02:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:02:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:02:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:03:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:03:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:03:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:03:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:03:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:03:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:03:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:03:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:03:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:03:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4,B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:04:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:04:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:04:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:04:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:04:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:04:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:04:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:04:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:04:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:04:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:04:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:04:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:05:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:05:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:05:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:05:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:05:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:05:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:05:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:05:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:05:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:05:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:05:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:05:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:06:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:06:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:06:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:06:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:06:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:06:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:06:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:06:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:06:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:06:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:06:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:06:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:07:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:07:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:07:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8,F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:07:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/A6BBB601-7E1D-4B8F-B871-5ABDEEE81BF9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''

```
