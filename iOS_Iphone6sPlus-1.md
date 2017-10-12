#### Test 1459176191a53731_iOS_Iphone6sPlus-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/1459176191a53731/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/EA0BC7EB-24BC-4F0B-ABFF-8C75E32F567E/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'
,Executing commands in '/tmp/EA0BC7EB-24BC-4F0B-ABFF-8C75E32F567E/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/1459176191a53731/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/1459176191a53731/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52438"
,(lldb)     command script import "/tmp/EA0BC7EB-24BC-4F0B-ABFF-8C75E32F567E/fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.py"
,(lldb)     command script add -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready
,JXcore engine is started
,2017-10-12 14:05:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:05:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:05:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:05:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:05:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:05:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:05:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserMa,nager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "AEA45CDC-38CB-49D1-8331-5D5126979D37", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:AEA45CDC-38CB-49D1-8331-5D5126979D37
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:68FC03F1-CE51-4594-A8DC-58D1443FF217
[ThaliCore] Browser.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:12E99940-,67D6-4D14-8E7C-9AD8CE1D572F
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "199CBDE2-06DE-4EFC-AD17-244883B3D2FB", generation: 0)
[ThaliCore] Advertiser.startAdvertisi,ng with peerID:199CBDE2-06DE-4EFC-AD17-244883B3D2FB
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:199CBDE2-06DE-4EFC-AD17-244883B3D2FB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "199CBDE2-06DE-4EFC-AD17-244883B3D2FB", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCorrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-10-12 14:05:42 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.307536065578461
,2017-10-12 14:05:42 - DEBUG UnitTest_app: 'My device name is: 'Apple-Iphone6sPlus-1''
2017-10-12 14:05:42 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:199CBDE2-06DE-4EFC-AD17-244883B3D2FB:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "199CBDE2-06DE-4EFC-AD17-244883B3D2FB", generation: 0)
,2017-10-12 14:05:43 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-10-12 14:05:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-10-12 14:05:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-10-12 14:05:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-10-12 14:05:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-10-12 14:05:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-10-12 14:05:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-10-12 14:05:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-10-12 14:05:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-10-12 14:05:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-10-12 14:05:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-10-12 14:05:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-10-12 14:05:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-10-12 14:05:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-10-12 14:05:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-10-12 14:05:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-10-12 14:05:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-10-12 14:05:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-10-12 14:05:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-10-12 14:05:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-10-12 14:05:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-10-12 14:05:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-10-12 14:05:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-10-12 14:05:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-10-12 14:05:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-10-12 14:05:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-10-12 14:05:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-10-12 14:05:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-10-12 14:05:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-10-12 14:05:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-10-12 14:05:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-10-12 14:05:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-10-12 14:05:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-10-12 14:05:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-10-12 14:05:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-10-12 14:05:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-10-12 14:05:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-10-12 14:05:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-10-12 14:05:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-10-12 14:05:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-10-12 14:05:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-10-12 14:05:45 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-10-12 14:05:45 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-10-12 14:05:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:05:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:05:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:05:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:05:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:06:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:06:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:06:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:06:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:06:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:06:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:06:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:06:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:06:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:06:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:06:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:06:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:07:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:07:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:07:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:07:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:07:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:07:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:07:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:07:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:07:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:07:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:07:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:07:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:08:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:08:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:08:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:08:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:08:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:08:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:08:34 - DEBUG CoordinatedClient: 'reconnected to the test server'
2017-10-12 14:08:34 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-10-12 14:08:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 1 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll with promise
,2017-10-12 14:08:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-10-12 14:08:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-10-12 14:08:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-10-12 14:08:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-10-12 14:08:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-10-12 14:08:42 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-10-12 14:08:43 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
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
,2017-10-12 14:08:53 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-10-12 14:08:54 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-10-12 14:08:54 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
,2017-10-12 14:08:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-10-12 14:08:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:08:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:08:58 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:08:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-10-12 14:08:58 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-10-12 14:08:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-10-12 14:08:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-10-12 14:08:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-10-12 14:08:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-10-12 14:08:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:08:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:08:59 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:08:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-10-12 14:08:59 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-10-12 14:08:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-10-12 14:08:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-10-12 14:08:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:85B238A7-1398-45F3-B385-744E2D9C1962
[ThaliCore] Browser.startListening
,2017-10-12 14:08:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-10-12 14:08:59 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:08:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-10-12 14:08:59 - DEBUG thaliMobileNativeWrapper: 'disco,veryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:08:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without e,r,ror
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:08:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:08:59 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:08:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-10-12 14:08:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:08:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:08:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:08:59 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:08:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-10-12 14:08:59 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-10-12 14:08:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-10-12 14:08:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-10-12 14:08:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:827AF444-9B55-460E-B74E-FDBEC802C9C7
[ThaliCore] Browser.startListening
2017-10-12 14:09:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":false}'
2017-10-12 14:09:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments",:{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:09:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserMa,nager.startListeningForAdvertisements
2017-10-12 14:09:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-10-12 14:09:01 - INFO thaliMobile: 'Received state ({"discoveryA,c,tive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:09:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-10-12 14:09:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12, 14:09:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:09:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-10-12 14:09:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:09:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:09:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:09:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:09:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-10-12 14:09:02 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-10-12 14:09:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-10-12 14:09:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:09:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:09:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:09:02 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:09:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdver,tisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:09:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:09:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:09:03 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:09:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-10-12 14:09:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:09:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:09:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:09:03 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:09:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-10-12 14:09:03 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-10-12 14:09:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-10-12 14:09:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-10-12 14:09:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DEBE040F-D198-4B56-9F6B-8A8D28D3EF9F", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:DEBE040F-D198-4B56-9F6B-8A8D28D3EF9F
,2017-10-12 14:09:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-10-12 14:09:07 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-10-12 14:09:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 68 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:DEBE040F-D198-4B56-9F6B-8A8D28D3EF9F
,2017-10-12 14:09:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:09:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 69 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:09:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:09:08 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:09:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-10-12 14:09:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:09:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:09:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:09:08 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:09:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-10-12 14:09:08 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-10-12 14:09:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-10-12 14:09:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:09:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7937C6B7-22F9-4F20-B1E4-CF99DC572C65", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:7937C6B7-22F9-4F20-B1E4-CF99DC572C65
,2017-10-12 14:09:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 14:09:09 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:09:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 70 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7937C6B7-22F9-4F20-B1E4-CF99DC572C65", generation: 1)
[,ThaliCore] Advertiser.startAdvertising with peerID:7937C6B7-22F9-4F20-B1E4-CF99DC572C65
2017-10-12 14:09:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 14:09:09, ,- INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:09:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:09:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 14:09:09 - INFO thaliMobile: 'Receive,d state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:0,9:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:7937C6B7-22F9-4F20-B1E4-CF99DC572C65
[ThaliCore] Advertiser.s,topAdvertising() peerID:7937C6B7-22F9-4F20-B1E4-CF99DC572C65
2017-10-12 14:09:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:09:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:09:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:09:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:09:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:09:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:09:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:09:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:09:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:09:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:09:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:09:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 72 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:09:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive",:false}'
2017-10-12 14:09:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:09:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:09:10 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:09:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-10-12 14:09:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:09:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:09:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:09:10 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:09:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-10-12 14:09:10 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-10-12 14:09:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-10-12 14:09:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-10-12 14:09:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8A4FF9A1-67A7-4775-8320-CFA8061C113C", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:8A4FF9A1-67A7-4775-8320-CFA8061C113C
2017-10-12 14:09:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-10-12 14:09:11 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-10-12 14:09:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdv,ertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1AD2147D-F37C-4842-8494-FAE6FBADE4C0
[ThaliCore] Browser.startListening
2017-10-12 14:09:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryA,ctive":true,"advertisingActive":true}'
2017-10-12 14:09:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","sta,r,tArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:09:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3806CC5D-8F7F-45C0-B357-1E5F3C9E873D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3806CC5D-8F7F-45C0-B357-1E5F3C9E873D", generation: 0)
ok 76 peers must be an array
ok 77 peers must not be zero-length
ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
ok 79 peerIdentifier must be a string
ok 80 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7CE7BB6E-C82C-4C8F-B9DB-C90F6B8C394F:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7CE7BB6E-C82C-4C8F-B9DB-C90F6B8C394F", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8A4FF9A1-67A7-4775-8320-CFA8061C113C:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8A4FF9A1-67A7-4775-8320-CFA8061C113C", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-10-12 14:09:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 ,14:09:13 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-10-12 14:09:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:8A4FF9A1-67A7-4775-8320-C,FA8061C113C
2017-10-12 14:09:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:09:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
2017-10-12 14:09:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:09:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:09:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:09:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:09:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:09:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:09:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:09:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1E35A50E-3E8B-4739-963D-88DB705300A6", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:1E35A50E-3E8B-4739-963D-88DB705300A6
2017-10-12 1,4:09:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 14:09:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:09:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 81 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:44955EBC-6F63-44A4-8959-38ED685B534C
[Thal,i,Core] Browser.startListening
2017-10-12 14:09:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-10-12 14:09:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:09:23 - INFO thaliMobile: 'Filtere,d out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:70A7F325-6D8D-4559-BC64-A9F5A71AB0FA
,[ThaliCore] Advertiser: session connected Peer(uuid: "1E35A50E-3E8B-4739-963D-88DB705300A6", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] Session.session(_:peer:didChange:) peer:70A7F325-6D8D-4559-BC64-A9F5A71AB0FA state: notConnected -> connecting
,[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1E35A50E-3E8B-4739-963D-88DB705300A6:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1E35A50E-3E8B-4739-963D-88DB705300A6", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:AF5469F9-24AD-4DE5-8938-C5288B08F245:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "AF5469F9-24AD-4DE5-8938-C5288B08F245", generation: 0)
,2017-10-12 14:09:24 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"AF5469F9-24AD-4DE5-8938-C5288B08F245","generation":0}'
,2017-10-12 14:09:24 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for AF5469F9-24AD-4DE5-8938-C5288B08F245 (syncValue: NClCdTLi75mz1vZKSxiGC4psZ7yl3nI0)'
,2017-10-12 14:09:24 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "AF5469F9-24AD-4DE5-8938-C5288B08F245", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "AF,5469F9-24AD-4DE5-8938-C5288B08F245", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:AF5469F9-24AD-4DE5-8938-C5288B08F245:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:AF5469F9-24AD-4DE5-8938-C5288B08F245:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7A795224-AA94-44DF-BB33-0C1B76A830D2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7A795224-AA94-44DF-BB33-0C1B76A830D2", generation: 0)
2017-10-12 14:09:25 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"7A795224-AA94-44DF-BB33-0C1B76A830D2","generation":0}'
2017-10-12 14:09:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:09:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:69CE5C4D-7A96-40EA-B08E-72F219D6EECD
[ThaliCore] Advertiser: session connected Peer(uuid: "1E35A50E-3E8B-4739-963D-88DB705300A6", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:69CE5C4D-7A96-40EA-B08E-72F219D6EECD state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:70A7F325-6D8D-4559-BC64-A9F5A71AB0FA
,[ThaliCore] Session.session(_:peer:didChange:) peer:70A7F325-6D8D-4559-BC64-A9F5A71AB0FA state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:AF5469F9-24AD-4DE5-8938-C5288B08F245:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:AF5469F9-24AD-4DE5-8938-C5288B08F245:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "AF5469F9-24AD-4DE5-8938-C5288B08F245", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52551
,2017-10-12 14:09:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"NClCdTLi75mz1vZKSxiGC4psZ7yl3nI0","error":null,"portNumber":52551}'
,2017-10-12 14:09:27 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'NClCdTLi75mz1vZKSxiGC4psZ7yl3nI0', error: 'null', listeningPort: '52551''
,2017-10-12 14:09:27 - INFO testThaliMobileNative: ''
,ok 83 Must have listeningPort
,ok 84 listeningPort must be a number
,ok 85 listening port should not be 0
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:69CE5C4D-7A96-40EA-B08E-72F219D6EECD
,[ThaliCore] Session.session(_:peer:didChange:) peer:69CE5C4D-7A96-40EA-B08E-72F219D6EECD state: connecting -> connected
,2017-10-12 14:09:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-10-12 14:09:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 14:09:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:09:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:1E35A50E-3E8B-4739-963D-88DB705300A6
,2017-10-12 14:09:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:09:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:AF5469F9-24AD-4DE5-8938-C5288B08F245
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:52551
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:AF5469F9-24AD-4DE5-8938-C5288B08F245:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:AF5469F9-24AD-4DE5-8938-C5288B08F245:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "AF5469F9-24AD-4DE5-8938-C5288B08F245", generation: 0)
,2017-10-12 14:09:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:09:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:09:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:09:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:09:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:09:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:09:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:09:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-10-12 14:09:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"NClCdTLi75mz1vZKSxiGC4psZ7yl3nI0","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:AF5469F9-24AD-4DE5-8938-C5288B08F245:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:69CE5C4D-7A96-40EA-B08E-72F219D6EECD state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "1E35A50E-3E8B-4739-963D-88DB705300A6", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:69CE5C4D-7A96-40EA-B08E-72F219D6EECD
[ThaliCore] Advert,iserRelay.deinit
[ThaliCore] Session.session(_:peer:didChange:) peer:70A7F325-6D8D-4559-BC64-A9F5A71AB0FA state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "1E35A50E-3E8B-4739-963D-88DB705300A6", generation: 0)
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "27902114-8768-484E-9050-1BAE80B6CED9", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:27902114-8768-484E-9050-1BAE80B6CED9
2017-10-12 1,4:09:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 14:09:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:09:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F64D23A4-BF51-4897-BCF6-DAEC3A2B3C1F
[Thal,i,Core] Browser.startListening
,2017-10-12 14:09:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-10-12 14:09:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-10-12 14:09:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Session.deinit peer:69CE5C4D-7A96-40EA-B08E-72F219D6EECD
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:AF5469F9-24AD-4DE5-8938-C5288B08F245:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "AF5469F9-24AD-4DE5-8938-C5288B08F245", generation: 0)
2017-10-12 14:09:33 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"AF5469F9-24AD-4DE5-8938-C5288B08F245","generation":0}'
2017-10-12 14:09:33 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for AF5469F9-24AD-4DE5-8938-C5288B08F245, (syncValue: PcM4ZTB1RZWGkbxFPYZP8ZbPFMvPByFQ)'
2017-10-12 14:09:33 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "AF5469F9-24AD-4DE5-8938-C5288B0,8F245", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "AF5469F9-24AD-4DE5-8938-C5288B08F245", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:) peer:AF5469F9-24AD-4DE5-8938-C5288B08F245:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7A795224-AA94-44DF-BB33-0C1B76A830D2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7A795224-AA94-44DF-BB33-0C1B76A830D2,", generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-10-12 14:09:33 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailabl,e":true,"peerIdentifier":"7A795224-AA94-44DF-BB33-0C1B76A830D2","generation":0}'
2017-10-12 14:09:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 14:09:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:780BD97C-6130-4480-B34B-311832BCA220:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "780BD97C-6130-4480-B34B-311832BCA220", generation: 0)
,2017-10-12 14:09:34 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"780BD97C-6130-4480-B34B-311832BCA220","generation":0}'
,2017-10-12 14:09:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:09:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:09:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4", generation: 0)
,2017-10-12 14:09:34 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4","generation":0}'
,2017-10-12 14:09:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:09:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:09:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:09:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:27902114-8768-484E-9050-1BAE80B6CED9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "27902114-8768-484E-9050-1BAE80B6CED9", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:AF5469F9-24AD-4DE5-8938-C5288B08F245:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:AF,5469F9-24AD-4DE5-8938-C5288B08F245:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "AF5469F9-24AD-4DE5-8938-C5288B08F245", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,F5469F9-24AD-4DE5-8938-C5288B08F245", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "AF5469F9-24AD-4DE5-8938-C5288B08F245", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:AF5469F9-24AD-4DE5-8938-C5288B08F245:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:AF5469F9-24AD-4DE5-8938-C5288B08F245:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:7A795224-AA94-44DF-BB33-0C1B76A830D2:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "7A795224-AA94-44DF-BB33-0C1B76A830D2", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:AF5469F9-24AD-4DE5-8938-C5288B08F245:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:AF,5469F9-24AD-4DE5-8938-C5288B08F245:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "AF5469F9-24AD-4DE5-8938-C5288B08F245", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,F5469F9-24AD-4DE5-8938-C5288B08F245", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "AF5469F9-24AD-4DE5-8938-C5288B08F245", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:AF5469F9-24AD-4DE5-8938-C5288B08F245:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:AF5469F9-24AD-4DE5-8938-C5288B08F245:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:AF5469F9-24AD-4DE5-8938-C5288B08F245:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:AF,5469F9-24AD-4DE5-8938-C5288B08F245:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "AF5469F9-24AD-4DE5-8938-C5288B08F245", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,F5469F9-24AD-4DE5-8938-C5288B08F245", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "AF5469F9-24AD-4DE5-8938-C5288B08F245", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:AF5469F9-24AD-4DE5-8938-C5288B08F245:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:AF5469F9-24AD-4DE5-8938-C5288B08F245:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:AF5469F9-24AD-4DE5-8938-C5288B08F245:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:AF,5469F9-24AD-4DE5-8938-C5288B08F245:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "AF5469F9-24AD-4DE5-8938-C5288B08F245", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:AF5469F9,-24AD-4DE5-8938-C5288B08F245 error: max retries exceeded
2017-10-12 14:09:44 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"PcM4ZTB1RZWGkbxFPYZP8ZbPFMvPByFQ","error":"Connection could not be established","portNumber":null}'
2017-1,0-12 14:09:44 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'PcM4ZTB1RZWGkbxFPYZP8ZbPFMvPByFQ', error: 'Connection could not be established', listeningPort: '%s''
,2017-10-12 14:09:44 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-10-12 14:09:44 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 780BD97C-6130-4480-B34B-311832BCA220 (syncValue: jTLBv84,JTesZ6NWUmMWCwJgr2z5GZcdH)'
2017-10-12 14:09:44 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "780BD97C-6130-4480-B34B-311832BCA220", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "780BD97C-6130-4480-B34B-311832BCA220", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:780BD97C-6130,-4480-B34B-311832BCA220:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-10-12 14:09:44 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-10-12 14:09:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:AF5469F9-24AD-4DE5-8938-C5288B08F245:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:780BD97C-6130-4480-B34B-311832BCA220:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:780BD97C-6130-4480-B34B-311832BCA220:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:780BD97C-6130-4480-B34B-311832BCA220:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "780BD97C-6130-4480-B34B-311832BCA220", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52558
,2017-10-12 14:09:47 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"jTLBv84JTesZ6NWUmMWCwJgr2z5GZcdH","error":null,"portNumber":52558}'
,2017-10-12 14:09:47 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'jTLBv84JTesZ6NWUmMWCwJgr2z5GZcdH', error: 'null', listeningPort: '52558''
,Connecting to the localhost:52558
,Connected to the localhost:52558
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:780BD97C-6130-4480-B34B-311832BCA220:0
2017-10-12 14:09:47 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-10-12 14:09:47 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:780BD97C-6130-4480-B34B-311832BCA220:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:1
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:20 count:1 vsID:1
,[ThaliCore] VirtualSocket.writePendingData() to write:20 written:20 count:0 vsID:1
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:1
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 20 vsID:1
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:1
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:1
,ok 88 got the same data back
,[ThaliCore] VirtualSocket.deinit vsID:1 []
,# teardown
,2017-10-12 14:09:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-10-12 14:09:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-10-12 14:09:48 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-10-12 14:09:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:27902114-8768-,484E-9050-1BAE80B6CED9
,2017-10-12 14:09:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:09:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:780BD97C-6130-4480-B34B-311832BCA220
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:52558
[ThaliCore] Session.disconnect() peer:780BD97C-6130-4480-B34B-311832BCA220:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:780BD97C-6130-4480-B34B-311832BCA220:0
[ThaliCore] BrowserRelay.deinit
,2017-10-12 14:09:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:09:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:09:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:09:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-10-12 14:09:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:09:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:09:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:09:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BBF9DB54-27C0-4C93-909E-CE62E7FD08F3", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:BBF9DB54-27C0-4C93-909E-CE62E7FD08F3
2017-10-12 14:09:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 14:09:49, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-10-12 14:09:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 89 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Thal,iCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1D82DA74-FEB4-4D98-B04D-C50C0C3F30C0
[ThaliCore] Browser.startListening
2017-10-12 14:09:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adve,r,tisingActive":true}'
2017-10-12 14:09:49 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"rout,er":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:09:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:780BD97C-6130-4480-B34B-311832BCA220:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "780BD97C-6130-4480-B34B-311832BCA220", generation: 0)
2017-10-12 14:09:49 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"780BD97C-6130-4480-B34B-311832BCA220","generation":0}'
2017-10-12 14:09:49 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 780BD97C-6130-4480-B34B-311832BCA220, (syncValue: fujl69ImY733fxljnGySZ89ngOrYQ83Z)'
2017-10-12 14:09:49 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "780BD97C-6130-4480-B34B-311832B,CA220", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "780BD97C-6130-4480-B34B-311832BCA220", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:780BD97C-6130-4480-B34B-311832BCA220:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4",, generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-10-12 14:09:49 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable,":true,"peerIdentifier":"926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4","generation":0}'
2017-10-12 14:09:49 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 14:09:49 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5425ADD4-4917-4D69-B6C4-BE1BB3866CFD", generation: 0)
2017-10-12 14:09:49 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5425ADD4-4917-4D69-B6C4-BE1BB3866CFD","generation":0}'
,2017-10-12 14:09:49 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:09:49 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:09:49 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BBF9DB54-27C0-4C93-909E-CE62E7FD08F3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BBF9DB54-27C0-4C93-909E-CE62E7FD08F3", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4D5CF258-9502-47E8-8BC3-9388881E8557:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4D5CF258-9502-47E8-8BC3-9388881E8557", generation: 0)
2017-10-12 14:09:50 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4D5CF258-9502-47E8-8BC3-9388881E8557","generation":0}'
2017-10-12 14:09:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 14:09:50 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-10-12 14:09:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 14:09:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:780BD97C-6130-4480-B34B-311832BCA220:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:78,0BD97C-6130-4480-B34B-311832BCA220:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "780BD97C-6130-4480-B34B-311832BCA220", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,80BD97C-6130-4480-B34B-311832BCA220", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "780BD97C-6130-4480-B34B-311832BCA220", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:780BD97C-6130-4480-B34B-311832BCA220:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:780BD97C-6130-4480-B34B-311832BCA220:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "926E3705-DB20-4BDE-A6DB-E3E0E96DA5C4", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:780BD97C-6130-4480-B34B-311832BCA220:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:78,0BD97C-6130-4480-B34B-311832BCA220:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "780BD97C-6130-4480-B34B-311832BCA220", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,80BD97C-6130-4480-B34B-311832BCA220", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "780BD97C-6130-4480-B34B-311832BCA220", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:780BD97C-6130-4480-B34B-311832BCA220:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:780BD97C-6130-4480-B34B-311832BCA220:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3B9D1D7C-E050-448B-830C-5BD3BC2EA2DF
[ThaliCore] Advertiser: session connected Peer(uuid: "BBF9DB54-27C0-4C93-909E-CE62E7FD08F3", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:3B9D1D7C-E050-448B-830C-5BD3BC2EA2DF state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:780BD97C-6130-4480-B34B-311832BCA220:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:78,0BD97C-6130-4480-B34B-311832BCA220:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "780BD97C-6130-4480-B34B-311832BCA220", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,80BD97C-6130-4480-B34B-311832BCA220", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "780BD97C-6130-4480-B34B-311832BCA220", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:780BD97C-6130-4480-B34B-311832BCA220:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:780BD97C-6130-4480-B34B-311832BCA220:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3B9D1D7C-E050-448B-830C-5BD3BC2EA2DF
,[ThaliCore] Session.session(_:peer:didChange:) peer:3B9D1D7C-E050-448B-830C-5BD3BC2EA2DF state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3B9D1D7C-E050-448B-830C-5BD3BC2EA2DF
[ThaliCore] Session.startOutputStream(with:) peer:3B9D1D7C-E050-448B-830C-5BD3BC2EA2DF
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2, [2]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3B9D1D7C-E050-448B-830C-5BD3BC2EA2DF
[ThaliCore] Session.startOutputStream(with:) peer:3B9D1D7C-E050-448B-830C-5BD3BC2E,A2DF
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [2, 3]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3B9D1D7C-E050-448B-830C-5BD3BC2EA2DF
[ThaliCore] Session.startOutputStream(with:) peer:3B9D1D7C-E050-448B-830C-5BD3BC2EA2DF
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4, [2, 3, 4]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:2
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:3
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:4
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:2
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:2
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:2
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:2
,2017-10-12 14:09:59 - DEBUG testThaliMobileNative: 'Server received (4096 bytes):'
,2017-10-12 14:09:59 - DEBUG testThaliMobileNative: 'Server received (12288 bytes):'
2017-10-12 14:09:59 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-10-12 14:09:59 - DEBUG testThaliMobileNative: 'Server sends data back to client (163,84 bytes):'
2017-10-12 14:09:59 - DEBUG testThaliMobileNative: 'Server data flushed'
[ThaliCore] VirtualSocket.writeDataToOutputStream len:16384 count:1 vsID:2
[ThaliCore] VirtualSocket.writePendingData() to write:16384 written:16384 count:0 vsID:2
[Th,aliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:2
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:3
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:3
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:3
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1947 vsID:3
,2017-10-12 14:09:59 - DEBUG testThaliMobileNative: 'Server received (8192 bytes):'
,2017-10-12 14:09:59 - DEBUG testThaliMobileNative: 'Server received (6043 bytes):'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:3
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1054 vsID:3
,2017-10-12 14:09:59 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:4
,2017-10-12 14:09:59 - DEBUG testThaliMobileNative: 'Server received (1054 bytes):'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:4
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:4
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:4
,2017-10-12 14:09:59 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-10-12 14:09:59 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-10-12 14:09:59 - DEBUG testThaliMobileNative: 'Server data flushed',
[ThaliCore] VirtualSocket.writeDataToOutputStream len:16384 count:1 vsID:3
[ThaliCore] VirtualSocket.writePendingData() to write:16384 written:16384 count:0 vsID:3
2017-10-12 14:09:59 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
2017,-10-12 14:09:59 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-10-12 14:09:59 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-10-12 14:09:59 - DEBUG testThaliMobileNative: 'Server data flushed'
[Th,aliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:3
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 0 vsID:2
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:2
[ThaliCore] VirtualSocket.closeStreams(,) vsID:2
[ThaliCore] VirtualSocket.writeDataToOutputStream len:16384 count:1 vsID:4
[ThaliCore] VirtualSocket.writePendingData() to write:16384 written:16384 count:0 vsID:4
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:fa,lse
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:4
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 0 vsID:3
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:3
[ThaliCore] VirtualSocket.closeStreams() vsID:3
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 0 vsID:4
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:4
[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:4
,[ThaliCore] VirtualSocket.deinit vsID:4 [2, 3]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:780BD97C-6130-4480-B34B-311832BCA220:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:78,0BD97C-6130-4480-B34B-311832BCA220:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "780BD97C-6130-4480-B34B-311832BCA220", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:780BD97C,-6130-4480-B34B-311832BCA220 error: max retries exceeded
2017-10-12 14:10:00 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"fujl69ImY733fxljnGySZ89ngOrYQ83Z","error":"Connection could not be established","portNumber":null}'
2017-1,0-12 14:10:00 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'fujl69ImY733fxljnGySZ89ngOrYQ83Z', error: 'Connection could not be established', listeningPort: '%s''
,2017-10-12 14:10:00 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-10-12 14:10:00 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5425ADD4-4917-4D69-B6C4-BE1BB3866CFD (syncValue: GxUNGKm,EmiPIysbncAIYEhwEhQJaRb7d)'
2017-10-12 14:10:00 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5425ADD4-4917-4D69-B6C4-BE1BB3866CFD", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5425ADD4-4917-4D69-B6C4-BE1BB3866CFD", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5425ADD4-4917,-4D69-B6C4-BE1BB3866CFD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-10-12 14:10:00 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-10-12 14:10:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:780BD97C-6130-4480-B34B-311832BCA220:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "5425ADD4-4917-4D69-B6C4-BE1BB3866CFD", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52577
,2017-10-12 14:10:03 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"GxUNGKmEmiPIysbncAIYEhwEhQJaRb7d","error":null,"portNumber":52577}'
2017-10-12 14:10:03 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'GxUNGKmEmiPIysbncAIYEhwEhQJaRb7d', error: 'null', listeningPort: '52577''
,Connecting to the localhost:52577
Connecting to the localhost:52577
,Connecting to the localhost:52577
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[Th,aliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCo,re] Session.startOutputStream(with:) peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0
,Connected to the localhost:52577
Connected to the localhost:52577
,Connected to the localhost:52577
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [2, 3, 5]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:5
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [2, 3, 5, 6]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [2, 3, 5, 6, 7]
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:6
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:7
,ok 91 correct string length
,2017-10-12 14:10:03 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:16384 count:1 vsID:6
,[ThaliCore] VirtualSocket.writePendingData() to write:16384 written:16384 count:0 vsID:6
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:6
,ok 92 correct string length
,2017-10-12 14:10:03 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:16384 count:1 vsID:5
,[ThaliCore] VirtualSocket.writePendingData() to write:16384 written:16384 count:0 vsID:5
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:5
,ok 93 correct string length
,2017-10-12 14:10:03 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:16384 count:1 vsID:7
,[ThaliCore] VirtualSocket.writePendingData() to write:16384 written:16384 count:0 vsID:7
,2017-10-12 14:10:03 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-10-12 14:10:03 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:7
,2017-10-12 14:10:03 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:6
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:6
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:6
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:6
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:6
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:6
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:6
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:6
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:6
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:6
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:6
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:6
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:6
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1054 vsID:6
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:6
,[ThaliCore] VirtualSocket.deinit vsID:6 [2, 3, 5, 7]
,ok 94 got the same data back
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:5
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:5
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:5
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:5
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:5
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
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:5
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:5
[ThaliCore] VirtualSocket.deinit vsID:5 [2, 3, 7]
,ok 95 got the same data back
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:7
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:7
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:7
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:7
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:7
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:7
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:7
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:7
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:7
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:7
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:7
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:7
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:7
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:7
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1054 vsID:7
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:7
[ThaliCore] Browser,Relay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:7
[ThaliCore] VirtualSocket.deinit vsID:7 [2, 3]
ok 96 got the same data back
,# teardown
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:780BD97C-6130-4480-B34B-311832BCA220:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "780BD97C-6130-4480-B34B-311832BCA220", generation: 0)
,2017-10-12 14:10:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-10-12 14:10:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 14:10:09 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
[ThaliCore] VirtualSocket exited RunLoop vsID:2
[ThaliCore] VirtualSocket.deinit vsID:2 [3]
2017-10-12 14:10:09 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:BBF9DB54-27C0-4C93-909E-CE62E7FD08F3
,2017-10-12 14:10:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:10:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:52577
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "5425ADD4-4917-4D69-B6C4-BE1BB3866CFD", generation: 0)
,2017-10-12 14:10:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:10:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:10:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:10:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:10:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:10:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:10:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:10:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-10-12 14:10:09 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"GxUNGKmEmiPIysbncAIYEhwEhQJaRb7d","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:3B9D1D7C-E050-448B-830C-5BD3BC2EA2DF state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "BBF9DB54-27C0-4C93-909E-CE62E7FD08F3", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:3B9D1D7C-E050-448B-830C-5BD3BC2EA2DF
,[ThaliCore] Session.deinit peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:3B9D1D7C-E050-448B-830C-5BD3BC2EA2DF
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE
,2017-10-12 14:10:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-10-12 14:10:09 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-10-12 14:10:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 97 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B26A740F-A322-41AA-AC9A-48619D26B2DE
,[ThaliCore] Browser.startListening
,2017-10-12 14:10:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-10-12 14:10:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-10-12 14:10:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5425ADD4-4917-4D69-B6C4-BE1BB3866CFD", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4D5CF258-9502-47E8-8BC3-9388881E8557:0
2017-10-12 14:10:10 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5425ADD4-4917-4D69-B6C4-BE1BB3866C,FD","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4D5CF258-9502-47E8-8BC3-9388881E8557", generation: 0)
2017-10-12 14:10:10 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5425ADD4-4917-4D69-B6C4-BE1BB3866CFD (syncValue: rVIUQu8AB8tMFQD0uVpvdBzn5G7Hnqt1)'
,2017-10-12 14:10:10 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5425ADD4-4917-4D69-B6C4-BE1BB3866CFD", generation: 0) creating a new relay
[Tha,liCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5425ADD4-4917-4D69-B6C4-BE1BB3866CFD", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,2017-10-12 14:10:10 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4D5CF258-9502-47E8-8BC3-9388881E8557","generation":0}'
,2017-10-12 14:10:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:10:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:67A7E480-106F-41FD-ADAD-2706A37CB77E:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "67A7E480-106F-41FD-ADAD-2706A37CB77E", generation: 0)
,2017-10-12 14:10:10 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"67A7E480-106F-41FD-ADAD-2706A37CB77E","generation":0}'
,2017-10-12 14:10:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:10:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:10:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3", generation: 0)
,2017-10-12 14:10:10 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3","generation":0}'
,2017-10-12 14:10:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:10:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:10:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:10:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:54,25ADD4-4917-4D69-B6C4-BE1BB3866CFD:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "5425ADD4-4917-4D69-B6C4-BE1BB3866CFD", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,425ADD4-4917-4D69-B6C4-BE1BB3866CFD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5425ADD4-4917-4D69-B6C4-BE1BB3866CFD", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:4D5CF258-9502-47E8-8BC3-9388881E8557:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "4D5CF258-9502-47E8-8BC3-9388881E8557", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:54,25ADD4-4917-4D69-B6C4-BE1BB3866CFD:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "5425ADD4-4917-4D69-B6C4-BE1BB3866CFD", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,425ADD4-4917-4D69-B6C4-BE1BB3866CFD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5425ADD4-4917-4D69-B6C4-BE1BB3866CFD", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:54,25ADD4-4917-4D69-B6C4-BE1BB3866CFD:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "5425ADD4-4917-4D69-B6C4-BE1BB3866CFD", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,425ADD4-4917-4D69-B6C4-BE1BB3866CFD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5425ADD4-4917-4D69-B6C4-BE1BB3866CFD", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:54,25ADD4-4917-4D69-B6C4-BE1BB3866CFD:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "5425ADD4-4917-4D69-B6C4-BE1BB3866CFD", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:5425ADD4,-4917-4D69-B6C4-BE1BB3866CFD error: max retries exceeded
2017-10-12 14:10:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"rVIUQu8AB8tMFQD0uVpvdBzn5G7Hnqt1","error":"Connection could not be established","portNumber":null}'
2017-1,0-12 14:10:21 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'rVIUQu8AB8tMFQD0uVpvdBzn5G7Hnqt1', error: 'Connection could not be established', listeningPort: '%s''
,2017-10-12 14:10:21 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-10-12 14:10:21 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 67A7E480-106F-41FD-ADAD-2706A37CB77E (syncValue: eNMlTZc,lpPW1dQEEsVk6N8VICfkrAdFH)'
2017-10-12 14:10:21 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "67A7E480-106F-41FD-ADAD-2706A37CB77E", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "67A7E480-106F-41FD-ADAD-2706A37CB77E", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:67A7E480-106F,-41FD-ADAD-2706A37CB77E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-10-12 14:10:21 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-10-12 14:10:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:67A7E480-106F-41FD-ADAD-2706A37CB77E:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D956AAC9-65A0-4008-8432-20DB2403AA45
[ThaliCore] Advertiser: session connected Peer(uuid: "0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:D956AAC9-65A0-4008-8432-20DB2403AA45 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:67A7E480-106F-41FD-ADAD-2706A37CB77E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:67A7E480-106F-41FD-ADAD-2706A37CB77E:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "67A7E480-106F-41FD-ADAD-2706A37CB77E", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52596
2017-10-12 14:10:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"eNMlTZclpPW1dQEEsVk6N8VICfkrAdFH",,"error":null,"portNumber":52596}'
2017-10-12 14:10:24 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'eNMlTZclpPW1dQEEsVk6N8VICfkrAdFH', error: 'null', listeningPort: '52596''
,Connecting to the localhost:52596
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:67A7E480-106F-41FD-ADAD-2706A37CB77E:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:67A7E480-106F-41FD-ADAD-2706A37CB77E:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [3, 8]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:8
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:116 count:1 vsID:8
,[ThaliCore] VirtualSocket.writePendingData() to write:116 written:116 count:0 vsID:8
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:8
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 75 vsID:8
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:177 count:1 vsID:8
[ThaliCore] VirtualSocket.writePendingData() to write:177 written:177 count:0 vsID:8
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:8
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 266 vsID:8
,Connected to the localhost:52596
2017-10-12 14:10:24 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
2017-10-12 14:10:24 - DEBUG testThaliMobileNative: 'Client data flushed'
[ThaliCore] VirtualSocket.writeDataToOutputStream len:69 count:1, vsID:8
[ThaliCore] VirtualSocket.writePendingData() to write:69 written:69 count:0 vsID:8
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:8
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 69 vsID:8
,ok 99 got the same data back
# teardown
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:8
,[ThaliCore] VirtualSocket.deinit vsID:8 [3]
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:5425ADD4-4917-4D69-B6C4-BE1BB3866CFD:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "5425ADD4-4917-4D69-B6C4-BE1BB3866CFD", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D956AAC9-65A0-4008-8432-20DB2403AA45
,[ThaliCore] Session.session(_:peer:didChange:) peer:D956AAC9-65A0-4008-8432-20DB2403AA45 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D956AAC9-65A0-4008-8432-20DB2403AA45
[ThaliCore] Session.startOutputStream(with:) peer:D956AAC9-65A0-4008-8432-20DB2403AA45
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [3, 9]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 116 vsID:9
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:9
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:75 count:1 vsID:9
[ThaliCore] VirtualSocket.writePendingData() to write:75 written:75 count:0 vsID:9
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:9
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 177 vsID:9
,Server received psk id: psk-id
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:266 count:1 vsID:9
[ThaliCore] VirtualSocket.writePendingData() to write:266 written:266 count:0 vsID:9
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:9
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 69 vsID:9
,2017-10-12 14:10:27 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-10-12 14:10:27 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-10-12 14:10:27 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:69 count:1 vsID:9
[ThaliCore] VirtualSocket.writePendingData() to write:69 written:69 count:0 vsID:9
2017-10-12 14:10:27 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-10-12 14:10:27 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:53 count:1 vsID:9
[ThaliCore] VirtualSocket.writePendingData() to write:53 written:53 count:0 vsID:9
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:9
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:9
[ThaliCore] Virtu,alSocket.closeStreams() vsID:9
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:9
[ThaliCore] VirtualSocket.deinit vsID:9 [3]
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2566884B-FC74-48AA-8975-4EAD52289E05
[ThaliCore] Advertiser: session connected Peer(uuid: "0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:2566884B-FC74-48AA-8975-4EAD52289E05 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2566884B-FC74-48AA-8975-4EAD52289E05
,[ThaliCore] Session.session(_:peer:didChange:) peer:2566884B-FC74-48AA-8975-4EAD52289E05 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2566884B-FC74-48AA-8975-4EAD52289E05
[ThaliCore] Session.startOutputStream(with:) peer:2566884B-FC74-48AA-8975-4EAD52289E05
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [3, 10]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:10
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 116 vsID:10
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:75 count:1 vsID:10
,[ThaliCore] VirtualSocket.writePendingData() to write:75 written:75 count:0 vsID:10
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:10
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 177 vsID:10
,Server received psk id: psk-id
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:266 count:1 vsID:10
[ThaliCore] VirtualSocket.writePendingData() to write:266 written:266 count:0 vsID:10
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:10
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 69 vsID:10
,2017-10-12 14:10:32 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-10-12 14:10:32 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-10-12 14:10:32 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:69 count:1 vsID:10
[ThaliCore] VirtualSocket.writePendingData() to write:69 written:69 count:0 vsID:10
2017-10-12 14:10:32 - DEBUG testThaliMobileNative: 'Server data flushed'
[ThaliCore] VirtualSock,et.writeDataToOutputStream len:53 count:1 vsID:10
[ThaliCore] VirtualSocket.writePendingData() to write:53 written:53 count:0 vsID:10
2017-10-12 14:10:32 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:10
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:10
[ThaliCore] Virt,ualSocket.closeStreams() vsID:10
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:10
,[ThaliCore] VirtualSocket.deinit vsID:10 [3]
,2017-10-12 14:10:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-10-12 14:10:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 14:10:33 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:10:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE
,2017-10-12 14:10:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:10:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:67A7E480-106F-41FD-ADAD-2706A37CB77E
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:52596
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:67A7E480-106F-41FD-ADAD-2706A37CB77E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:67A7E480-106F-41FD-ADAD-2706A37CB77E:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "67A7E480-106F-41FD-ADAD-2706A37CB77E", generation: 0)
,2017-10-12 14:10:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:10:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:10:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:10:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:10:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:10:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:10:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:10:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-10-12 14:10:33 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"eNMlTZclpPW1dQEEsVk6N8VICfkrAdFH","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:2566884B-FC74-48AA-8975-4EAD52289E05 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:2566884B-FC74-48AA-8975-4EAD52289E05
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:D956AAC9-65A0-4008-8432-20DB2403AA45 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "0E8D1D4C-9C9E-44E1-8D15-EBE70814FCCE", generation: 0)
,[ThaliCore] Session.deinit peer:67A7E480-106F-41FD-ADAD-2706A37CB77E:0
[ThaliCore] BrowserRelay.deinit
,# Can shift large amounts of data
,[ThaliCore] Session.deinit peer:2566884B-FC74-48AA-8975-4EAD52289E05
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "95033898-78DB-4672-A53C-705177BC68F9", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:95033898-78DB-4672-A53C-705177BC68F9
,2017-10-12 14:10:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 14:10:33 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:10:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 100 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:AE75EEA6-D468-4610-9059-86061F105BF2
[ThaliCore] Browser.startListening
,2017-10-12 14:10:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-10-12 14:10:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:10:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:67A7E480-106F-41FD-ADAD-2706A37CB77E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "67A7E480-106F-41FD-ADAD-2706A37CB77E", generation: 0)
2017-10-12 14:10:34 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"67A7E480-106F-41FD-ADAD-2706A37CB77E","generation":0}'
2017-10-12 14:10:34 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 67A7E480-106F-41FD-ADAD-2706A37CB77E, (syncValue: y9vFOJ65aCP4HMUHBr4JArglcaFJnRsW)'
2017-10-12 14:10:34 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "67A7E480-106F-41FD-ADAD-2706A37,CB77E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "67A7E480-106F-41FD-ADAD-2706A37CB77E", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:67A7E480-106F-41FD-ADAD-2706A37CB77E:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3",, generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-10-12 14:10:34 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable,":true,"peerIdentifier":"DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3","generation":0}'
2017-10-12 14:10:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 14:10:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:95033898-78DB-4672-A53C-705177BC68F9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "95033898-78DB-4672-A53C-705177BC68F9", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3F732965-3C77-46D7-A946-F17E3B7CC083:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3F732965-3C77-46D7-A946-F17E3B7CC083", generation: 0)
,2017-10-12 14:10:35 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3F732965-3C77-46D7-A946-F17E3B7CC083","generation":0}'
,2017-10-12 14:10:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:10:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:10:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:AA3E3CD0-8C9D-4EBC-A3DA-4B1C4CC03CCC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "AA3E3CD0-8C9D-4EBC-A3DA-4B1C4CC03CCC", generation: 0)
2017-10-12 14:10:35 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"AA3E3CD0-8C9D-4EBC-A3DA-4B1C4CC03CCC","generation":0}'
2017-10-12 14:10:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 14:10:35 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-10-12 14:10:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 14:10:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:67A7E480-106F-41FD-ADAD-2706A37CB77E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:67,A7E480-106F-41FD-ADAD-2706A37CB77E:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "67A7E480-106F-41FD-ADAD-2706A37CB77E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,7A7E480-106F-41FD-ADAD-2706A37CB77E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "67A7E480-106F-41FD-ADAD-2706A37CB77E", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:67A7E480-106F-41FD-ADAD-2706A37CB77E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:67A7E480-106F-41FD-ADAD-2706A37CB77E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:67A7E480-106F-41FD-ADAD-2706A37CB77E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:67,A7E480-106F-41FD-ADAD-2706A37CB77E:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "67A7E480-106F-41FD-ADAD-2706A37CB77E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,7A7E480-106F-41FD-ADAD-2706A37CB77E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "67A7E480-106F-41FD-ADAD-2706A37CB77E", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:67A7E480-106F-41FD-ADAD-2706A37CB77E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:67A7E480-106F-41FD-ADAD-2706A37CB77E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:67A7E480-106F-41FD-ADAD-2706A37CB77E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:67,A7E480-106F-41FD-ADAD-2706A37CB77E:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "67A7E480-106F-41FD-ADAD-2706A37CB77E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,7A7E480-106F-41FD-ADAD-2706A37CB77E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "67A7E480-106F-41FD-ADAD-2706A37CB77E", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:67A7E480-106F-41FD-ADAD-2706A37CB77E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:67A7E480-106F-41FD-ADAD-2706A37CB77E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:67A7E480-106F-41FD-ADAD-2706A37CB77E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:67,A7E480-106F-41FD-ADAD-2706A37CB77E:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "67A7E480-106F-41FD-ADAD-2706A37CB77E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:67A7E480,-106F-41FD-ADAD-2706A37CB77E error: max retries exceeded
2017-10-12 14:10:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"y9vFOJ65aCP4HMUHBr4JArglcaFJnRsW","error":"Connection could not be established","portNumber":null}'
2017-1,0-12 14:10:45 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'y9vFOJ65aCP4HMUHBr4JArglcaFJnRsW', error: 'Connection could not be established', listeningPort: '%s''
,2017-10-12 14:10:45 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-10-12 14:10:45 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3 (syncValue: 46BFjmz,cbNuqPVf44bRJMB98KEEjXX6V)'
2017-10-12 14:10:45 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DDC5D80E-EA98,-4BE1-BC6C-FFDB05E03CD3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-10-12 14:10:45 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-10-12 14:10:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 14:10:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:67A7E480-106F-41FD-ADAD-2706A37CB77E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:03CB93C5-E494-4904-B899-97A742B84DC9
[ThaliCore] Advertiser: session connected Peer(uuid: "95033898-78DB-4672-A53C-705177BC68F9", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:03CB93C5-E494-4904-B899-97A742B84DC9 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:DD,C5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,DC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:03CB93C5-E494-4904-B899-97A742B84DC9
,[ThaliCore] Session.session(_:peer:didChange:) peer:03CB93C5-E494-4904-B899-97A742B84DC9 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:03CB93C5-E494-4904-B899-97A742B84DC9
[ThaliCore] Session.startOutputStream(with:) peer:03CB93C5-E494-4904-B899-97A742B84DC9
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [3, 11]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:11
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
2017-10-12 14:10:48 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
[ThaliCore] VirtualSocket.re,adDataFromInputStream() read: 1095 vsID:11
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
,2017-10-12 14:10:48 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
,2017-10-12 14:10:48 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:11
,2017-10-12 14:10:48 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
,2017-10-12 14:10:48 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:11
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
,2017-10-12 14:10:48 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:11
,2017-10-12 14:10:48 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
2017-10-12 14:10:48 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
,2017-10-12 14:10:48 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
,2017-10-12 14:10:48 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:11
,2017-10-12 14:10:48 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
,2017-10-12 14:10:48 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
,2017-10-12 14:10:48 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
2017-10-12 14:10:48 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:11
,2017-10-12 14:10:48 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
,2017-10-12 14:10:48 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
2017-10-12 14:10:48 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
,2017-10-12 14:10:48 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
,2017-10-12 14:10:48 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
2017-10-12 14:10:48 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
,2017-10-12 14:10:48 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
,2017-10-12 14:10:48 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
2017-10-12 14:10:48 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
,2017-10-12 14:10:48 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:11
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
,2017-10-12 14:10:48 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-10-12 14:10:48 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
,2017-10-12 14:10:48 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:11
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 931 vsID:11
,2017-10-12 14:10:48 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-10-12 14:10:48 - DEBUG testThaliMobileNative: 'Server received (931 bytes):'
2017-10-12 14:10:48 - DEBUG testThaliMobileNative: 'Server received all data: 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,r,OE1UES1tpxnGs4wDcECg6sTGqhPGcJM5NjScKgu3wty6Bo90bxd3hMazx3PoAIZCqAcM4BKsOykAIy7jOAHpxAlhjdDhhMEtDHlr2P2aA9La65smsJ7hgVHewbLik99I0rX0L3mpwuDSTzsrQJf4eyZg8PjM4vvL47FSO82POz0rb9povv0kLnYPawlWuGVAh9xfqLxQdrB6dSEAflImIIrzBe8chFpgXVigXRh6gvxtFhr0wnvGsrc1i4bP04A1,Ttkxtojrp6jiRCnWBod89m4zt1T1gDNtIyNHFNyva5raZKjHG7HetuDzni5EQHJHsJU3IO2au9p1qMkbdTN7movNBSZiTTcq0o0hOQgH3EmcTEC0RxpWd7YGuqScY8S175GeiKAHZkTcE9RzOxgsJCDK9GnksT2lXJJ8YBazenYpzRVqzokH5WS2zojRAZhSFFj9xFZGIkUazdOYA6aEtmo9nLkiS1mAuUOfDdgTdHfMdZtLx9pf8VcZxhB7PzMf,KP0IWFz0NS58T1b5VA4rG1wZAaJ5wSVtNt2L46qQ1ahCbCvHUvkVox5IB5mGRjqJWX9x6rcYPoekTWIolfR73sUeSewYg1LbY7cLaUThOqfCy0TvgQSR9w4nl8bL8Irml4W5gU2RhSMgKrXXtbLA8fR2PwSKHCqOQVqQo7WuwxJ6nL24nQrPzfA1Zj4dbApfygsrj1iIh2LzaDi37qxHu2ePWGZo9EqGijkSiEanYad9pvUvJSu7m93ixcQwz9IX,Wlbfx5viY7n6CBopi8FhU8FViT6NQNdUM48MygrBaIIvbW29C45pgia9iv4AoEyovFJJBwBWYfIjrnQHp1U3Rr9V8PU6xGdm44QMVwDMO77P9LSaJGYinOcY6CMghisurW3s96ozIrsIeMT9WySwx5w7gZ9wBtieKUFmr76ah4paVyUBefPbmg8QrN2M9arjaQJflCurlv1SRWuX2uVJamsNWJlE8dOPG2QMvYzpBth5lwayOyeTUrtD4LankS5,D,gCxeswF393QuJVuP9BHEL4bjAc1dNd5jGcClDDRVriTTp9RBxagEBXdUbMYjDqgrOpN8xoXcguiyFFGOibxL43mulA9cOCxfkKT0gMxcvTyerHKHBY4SWyFmKwfkUQvG2FZc2hkHqUamuGB1KnsVr7j8DxmSN39q21a4kwibpCOs7eDOqnfxYiQj1AUDd5OJa8mJUDIuWA1aoRFNnUv7Mz2gb4jkTjfbEgxgkJrEf2QFWQ2nZyeyovtulXrTRiJD,0l051OIIK7SoCp9nuEfSwe9JnzMVLlXO16pGpLdgHXegzhWPKbfl82j4pRtvhUdsoEQ1Wyr5mJBZjZ2RUXiuLytW7GsN5Ogs192mjgqSb4ywGVD81DUMJ05CWrwvPSPYc4xgC1VvWUr4fgGB2f7BR9gzxzunwLUStuk2FmgeLw1l8MoJh057fEh1Cyn13C2c1AwqYMq0zdr75SnIeoOIcBViAkN6zn7uSexZvJAmE8IzZVcfg5zQza6HZ2qFiCbR,PwWdqVEOxM0uqNdtXRm04tXJ0I49faddC6ysUC7kw4fDsn7RV1K0iNl0eMuog3vSX5uQJgbspyJ3RcWnTPfAeYrUhaWrv4maOlk6CEeNXyI6izqjv1jrUfYPCLbAjwBLdJSr8PLmuLGz8WsGQUStEjiWSfWfAfDZut5WsZqwQDpTVnYgrLhuSxy8P44RxyGSSU5OWmwIAOXOU7KST85W8iJURHMqP4RO9PrMBdqZJjBdnPcntr5S7M7UnM1ibIaV,FFThXoWic0qKN2RgnZ7eNvudxOFAH6Xmt9clZaOUhg4dn1iBoAVb24u2ZVCKl7J8Q91fMUdmBs612B4T63uGIpvA8GnB1rEZSTaHtcW6KAWnyrMaiD9U8xNfXu7nUhalofh0tnWzedxfJbBxAj2rDXNhVo1BeLEw51wQUxs7RxurNCUM2WgWplT7Ds1m9U5UXueGQ58R1xQ9ThK64SS7kEtUcLyWnDrhju2IJDmUhNbNYIqIPdr9Bjnlg5zHSPY,o,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,N,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,9,I2DnK7QpccHKd6GxLMkXqUUZxd5ZdIRrEulIuSyF6nw42JRiO6N7vi8jmDCIV0TDGp1sNdcUktSzhud0IdRPQLzNm6XD0Pv9oadZavM8nP6kWLiqRlhFYDYPbWa5Wn8sZs5Mg8jSos8UmC6nFK5Pp5IuobQ20wkuLnvNN9UN68oAkicpaNW1WZCCkFVKlSnj05luX93JEp6CWpJEfQyTINLouFQ3SjcZCna8dOldZQQTQA2RWcxa4PKeVOD243Ub,3lk3CCJiIQFqs34nA79phpM2h5cdRxHB5J0Visv1GUsUJ8KWuYvlZmAc5Gx6XOGAppocAakYjNC8ZK6YgilIWZBRyfwPUPmk1EGIKlOZxz6bOVRM2HXcWi53P1qGJ1o5gyrE1RwY4WvQmwJHvFoF5lSJNUGbgLjMfXn9o6LG3wZ6KAY9EFMGcP1LmBNBN0tFLsKg1HO0gQwabWN1UWDVd0UwIUrMDKvhDBXVhBvDtau5ar6y7K5ModYHCfyRMTvt,08yIt2lZXZnIZuYDS2HbEoMsYDHSCkUN7dAFB49pTf2HM0eEjOgilKufN0AXnw0bmABJSCvIfVMNVAIhDuBvwzz8yFCcrpew6e73eRuCZvaFtFyJNaUJNpT2wwtWaPwWIWAP91vht2gnavRAholkGkVmqiyzMRhUTqQRWbzrlAvzRI7WMwcAkSWEAmDhW7nNfzgJAHGSgym7YtgUIoVLqmiv2T7b3AdIn8Ymjs7tPrVhgyi1YKOzNbeAMz0QVTme,fGgXP8fzYpsuFWOjbqqVeO5RXiTp0N9neMDz620is8Nuzn732cq47kTbNRErfSuN0209XE2WPONMasjC1VG6HKJiciTVeRxEodITSYPwEgrlDzU6zAafhHtGTUk4HKwsCFercX6ZacFTIKmE4yF9egQsjY8r4UVLKAAbijrOIwueO5xdXiakcqIgclnAcW2hqKGycAxQ5i4xXOBI0xgQLnyMZvkp6rt96g1WLN2w85ENqS5dCiy2DqbE7ApCXHs,4,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,T,DeIUy2FjDMCiOwbI5JEMk64pnB2dotZDgyUs46kQmh06MFa1RE2myHNwlXHNLrc3CmXI1lwr1NDo0bBpxpx9UvUlqyYMdjS3sNkWKQl9CcQMHiHr2AZ5Z8lO5Z1ae3jGCXK5tihxPj0J9hjfD9vF8VKVsyuPHoxpgY5r6D2T7POIMEE7Qv3iR0NQG63E9eKBuw2kR21lJ5Fy69Ai9MXbhwrEA36EHdCRjrlcraadhDmdHODAKFOz6J1Qz2Ga2zOr,Dxq0Yyg7nlreitSsITM2RVvdGBEkMFS3r4yI1shOesv0lbBgayt4QwEcgPISipfrtJAeihcQSTZqN74lh0PQx5Nv2OF4VaIgAWGvm1a7LDgaQztbkss1vc5pAAYqeRa8EIbAVC45mPGa0iEQy9xbHVfrRrG6hZQuWyfHziaOWHwFjXfBCZr3XRTp2N8n2NvyUuEtzHqbqyXOWsCH0xHvwJ1qOmHmRTmRr6gESu0tiLNreMe3URc5sJVFBInw7lJc,9npsjmFOYefAyMtwSYulzSnRRDU3Y4kBtDsA0PtJQd3fjB9dkjpB99GYneZW1LazRyuleLaFfu7BGlCsVZG2CEThExwnPl6ZoiN6T5P8g9JnqKncT05d47WiHBeaQUuzoagO342gbc8JLAbh0oUTsRn1IypmvSO8UrvIIZ0cJWY1lMJzKFt4IWEfKN4XX10gLnBX5xD7HHPtitAO8ZtjftwILRZQbDL5VYkKxg05cFQ4bMxMag4WIHzHyCagIRrr,6TrJU7szKJ9fYwfXMJsN1pd19J5flC6rnBK47OkK5WveJs7HdxoAsMh6XG4YP6mhyR5qX6xbA1Wn4lKCvK6aS6K7puyLrGIaZT7Sy3DdVPOJAJ5f82zYEoMddjWj4t4jj7wJCUZTvOUiGvzH6ZUwESIZ8LCh1MJgV2156j3MhmLDrReTKH4aELhkJQXYo9xp5AgO3GeHVknRNDIdbSO8LXtKvtLsbpwWaWTNP1NkadnZAR719nV8B2yG0FDHEDL,y,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,C,QTaxqNtKpoMPDF6nzl5s2rPJMVpP2PHLwPfiwltBo54gcl3u6HnHtBLAWgTVm2n2k18XUjfZ6LSNPzi6gpgIJhJxV6Ec1pwOcLzmHK0U9qFLZRdTLIMHbULYEXBHVhfiM6XAST4WHOnhfsO4fsjMgIEvTzQSfAlIDA3HVkPnp8128R5eCt7cA4gBU4BpS4SGn6HMnidVrzs1IodlkoyS5WzJJkWF4rvBkXxg9lR6qaILaegZ5Q4Ym85gQV8NUaB7,UJBSn4gjIqYxVdzfKSPz7l6Pkz4FsQcw988ZDxcXZVyTZHdBSo7PWEO06oDZNRwhsXPgv1sUEJMsaK25WUq0GM3BrNy4LF2LGexpixTSsVI5wcoVrWWAu6DylwoCo8ULc6d86beT2XxIBbyUeb84U9wx0UbUk2vlXbkw5JNFXPsH6sr4C3Nb7APDlbGgkqB75LiR3WLsnJ7M6xaAFGEZ9XVTmiuOxsEf39SJFIRfszxFpIi4q99ymPsB3DTYiILS,UqUGR6vovadFmsMBXMMqKKKraSHlq5TmsXFOtVN0g0KGNNzuG8KsgqOvq5Gs0cwsIAnYy2aYEmKwYc7tlNBMm3vyq8FTPchUcZoc7P7NjaPAjNGkQaO0DSpPfLY9YRs5YWYaPciTPywZd3HKM45eNmqlIj73YhTMjucdlwTH5eB3g0Gnazyx55N3CGRbilxxxQOifrkcekpSWT7Y6zKbV6roEHpL4czsH57qPjurIaRnmHHqIW3P3Fk9bIqwfzoa,cpN0XyGYGf200wDWRrWrEP1uNIc2s7Jc7M8UpwAZSPtRi5r4nBM5Y6dpRQ8n23i82kcqcFOPdqGnbvLWtb0Ve2w2V3AVt0f97Va3rQ5PFe6tbiijGrBHEvbdF3jYF1fl1EKTqe0ba7PeYuRpJ0EbwEwe2f2MMl7Btq4JdeqYHQcKEWIrZnP8Sh4ChuZec1TCjDtjuidWE6l0B0og55APMz4P5WilKBQNYqiYGM6UMz9XcTmipcVbddzcLOJcNXT,G,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'
2017-10-12 14:10:48 - DEBUG testThaliMobileNative: 'Server sends data back to clie,nt (65536 bytes):'
2017-10-12 14:10:48 - DEBUG testThaliMobileNative: 'Server data flushed'
[ThaliCore] VirtualSocket.writeDataToOutputStream len:65536 count:1 vsID:11
[ThaliCore] VirtualSocket.writePendingData() to write:65536 written:65536 count:0 vsI,D:11
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:11
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 0 vsID:11
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:11
[ThaliCore] VirtualSocket.closeStreams() vsID:11
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:11
,[ThaliCore] VirtualSocket.deinit vsID:11 [3]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:DD,C5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,DC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:DD,C5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,DC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:DD,C5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:DDC5D80E,-EA98-4BE1-BC6C-FFDB05E03CD3 error: max retries exceeded
2017-10-12 14:10:55 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"46BFjmzcbNuqPVf44bRJMB98KEEjXX6V","error":"Connection could not be established","portNumber":null}'
2017-1,0-12 14:10:55 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '46BFjmzcbNuqPVf44bRJMB98KEEjXX6V', error: 'Connection could not be established', listeningPort: '%s''
,2017-10-12 14:10:55 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-10-12 14:10:55 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3F732965-3C77-46D7-A946-F17E3B7CC083 (syncValue: shqPLGK,8qJCokP17QqEmaHf43vsSfrsy)'
2017-10-12 14:10:55 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3F732965-3C77-46D7-A946-F17E3B7CC083", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3F732965-3C77-46D7-A946-F17E3B7CC083", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3F732965-3C77,-46D7-A946-F17E3B7CC083:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-10-12 14:10:55 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-10-12 14:10:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 14:10:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:DDC5D80E-EA98-4BE1-BC6C-FFDB05E03CD3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:3F732965-3C77-46D7-A946-F17E3B7CC083:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:67A7E480-106F-41FD-ADAD-2706A37CB77E:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "67A7E480-106F-41FD-ADAD-2706A37CB77E", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1668740B-0A4B-4BA8-BEC2-08E068BAA78A
[ThaliCore] Advertiser: session connected Peer(uuid: "95033898-78DB-4672-A53C-705177BC68F9", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:1668740B-0A4B-4BA8-BEC2-08E068BAA78A state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3F732965-3C77-46D7-A946-F17E3B7CC083:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3F732965-3C77-46D7-A946-F17E3B7CC083:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "3F732965-3C77-46D7-A946-F17E3B7CC083", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52623
2017-10-12 14:10:58 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"shqPLGK8qJCokP17QqEmaHf43vsSfrsy",,"error":null,"portNumber":52623}'
2017-10-12 14:10:58 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'shqPLGK8qJCokP17QqEmaHf43vsSfrsy', error: 'null', listeningPort: '52623''
,Connecting to the localhost:52623
Connected to the localhost:52623
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3F732965-3C77-46D7-A946-F17E3B7CC083:0
2017-10-12 14:10:58 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-10-12 14:10:58 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3F732965-3C77-46D7-A946-F17E3B7CC083:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [3, 12]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:12
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:32664 count:1 vsID:12
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:32872 count:1 vsID:12
,[ThaliCore] VirtualSocket.writePendingData() to write:32664 written:32664 count:1 vsID:12
,[ThaliCore] VirtualSocket.writePendingData() to write:32872 written:32872 count:0 vsID:12
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:12
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:12
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:12
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:12
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:12
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:12
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:12
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:12
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:12
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:12
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:12
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:12
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:12
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:12
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:12
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:12
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:12
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:12
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:12
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:12
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:12
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:12
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:12
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:12
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:12
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:12
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:12
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:12
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:12
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:12
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:12
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:12
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:12
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:12
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 3285 vsID:12
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:12
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:12
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:12
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:12
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:12
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:12
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 931 vsID:12
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:12
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,ok 102 got the same data back
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1668740B-0A4B-4BA8-BEC2-08E068BAA78A
,[ThaliCore] Session.session(_:peer:didChange:) peer:1668740B-0A4B-4BA8-BEC2-08E068BAA78A state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1668740B-0A4B-4BA8-BEC2-08E068BAA78A
[ThaliCore] Session.startOutputStream(with:) peer:1668740B-0A4B-4BA8-BEC2-08E068BAA78A
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [3, 12, 13]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:13
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:13
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1379 vsID:13
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:13
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:13
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:13
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1379 vsID:13
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:13
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:13
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 284 vsID:13
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:13
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:13
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:13
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:13
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:13
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 284 vsID:13
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:13
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:13
2017-10-12 14:10:59 - DEBUG testThaliMobileNative: 'Server received (4096 bytes):'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:13
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:13
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:13
2017-10-12 14:10:59 - DEBUG testThaliMobileNative: 'Server received (1379 bytes):'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:13
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:13
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:13
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:13
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:13
2017-10-12 14:10:59 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:13
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:13
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:13
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:13
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:13
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:13
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:13
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:13
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:13
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:13
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2026 vsID:13
,2017-10-12 14:10:59 - DEBUG testThaliMobileNative: 'Server received (26280 bytes):'
,2017-10-12 14:10:59 - DEBUG testThaliMobileNative: 'Server received (32686 bytes):'
,2017-10-12 14:10:59 - DEBUG testThaliMobileNative: 'Server received all data: Hx1UvwNswcbzEFp9u31Ap78lrA7u9poMudurRoNyUuSFm38rKk4I9Bn1dxzpzAa6QSKXkaVnR1hA7cwgcY9TCGVKGcq7oopPeqOCkhYjw61tRL5xIJVxXaFqmO6ql52pqguJv3zj0cxRo2iCPtsw84tg44ssjEd5cE31xfH0GRCgwAqUvl0ojEoh1FZ27ZVJcHEKBNrckCjIWJssJoi6GpFT4S09XDUKnyriI9YbtotQZw88iutx4YpmJHoifLDeGOG4f18LmS1uvJgatLFbh5nT3sHkinJv5eel1rVqsFDKiDHQcrmsEvKrMe21fwKEiRG3kTAMGiJvsAaeKg8jCvfSWTj2K71hdJrVoFVWFJBpoJxV7vXMQQeSpAIhOIPduvhoIDIJZymTX1l8JRFLcfJxvPCElfjmXN5dHFwYX7DNRjF0pw,mGbVPs0FOeXmOFzXXXvr3LDjH4iHadJ1Hb9VJr6874O8S4O0W5tmKCCz4KAnPHFPgBgbay0P3HQ3U8kVZ10NUntiaPFx4tMDjtLKg86rijXyzkDqcR7wA762fMepIjoJlklytnUGu2wuz6IJsPR5TdAe0OH3vROqIaxDa6PJwe9ossy0rGFbu3hjIAkzkyOROzQ7alFfMnALznlWErsdBXm80osnZfNSn0gDWJOgSl3qsbHQcnPk6dYfJ2pWaNYH,0TvnQDQyowtBQaHQhjXXlLzwUlqY3GLwcyzE2c1MFAlWovNhAr3GnuReorVgDPES3IAk6OX37GD0AAGyR7S2FAk8rb9mfIMTZEmnDNzhe3aHqAG63Ke77a7yEUgbOjz3tJqql6AY2mhYPOwby3VIvljVyVAjCl0tQtfw0LVAncR62YC5DwRMRd9ybN7aB3Zjsj6vQsUVa1Ln0Vi1H4Fjt0MSYyuwSLeIx5tj0i7PxJqZTZk6wkoOlY5iomIxSVlv,pvIV7hUefwbCiieypQIFE8wjXK9aMgTHijsLdwoPfZb7VFEUgDM7pulQQ2kSfNS3dtWIkIbxGeGqJVhCskc0yWyKkv0KitIiCwFIF4UpmAqbxwCOjP0uZhfwinlvURxwtGFY0URCHoMAx7bunqdUtRzBorzDvuWLl4SwPGZxD4d1fF9inJydho0lX3dmxphhaTd8ciuhnZBNJqeZYwT4GKy2NWrPLR0rXWwLl0PKFD7Fay7XXyR3iO0b7GwzjyIW,EEXaA8bmdB16GiOv72EJW7Y3EYjYnrBCskscwCev1NbBXAI44zIaOwhjsxIbLiuehty0ZjdTZtfZTD5ZS0A8kadQE7oYyXNJNDjYB4X5gQjDkD1YkMsiFb2OfpRJqSAR51hRtzeBbxZVM5V7gqsjMkKpanMDcCsD1c3YW0d1wORynkIOKOKeBMNM5A8VcF4XKAqeGVcvxOVupRxFypZnZQ7j7RsT44lWB9qo490oj6e6WIQwBJ5sZYCSaDWRoHgF,mBw4nJ71DslpSeYvR6FWcNcTlz1PPboNlh5Sa4czuyyYobT5HCoHjrgIn3uLhc1wfYQAzgMsMJFyiRhuQgyt4EEaZJpGAP9Y6T4nBpD0ld2PWmZZHnpEnfAWecBoM3hTl21zskXPdCeXywQXllKMP70lEer9bzrPtRM7HxC1YVCTNpu9t76Zan2TtU12OMEiqzPLK7ImC9XlawBtFtLObYZ5DGAD3l3IC3X2lJl264tWl71hHwmnJ3xSFwMk16uy,nRGZvnJZvaZSH9wuY53OSAzHUPDTA8dpwRr1DER3MdoMglagBINmpKhtBuvWUinf6tgiTozDkIBHafcOYJSIMjvANHQrMdI5H992F17Gi5JoOoT9mdlgU1kdvQEimYeINkPcEo2KKCINYkOrz1YHdLe0LYOH3EpyapM1Ex0LUYi3THYwUIuMRfZkyMex1E3GJyammP1H5LgQ0HXKp7r2AXmRKNfB8DuEHILvyiEUUx7oTrkuE5dryHnlKLVFwkr0,pFwwSmTzreeZBGIncpShhJJSxFCtdLN7JL6vB1o1LMcWEz6mJr22FHh9fL5kg7ono2aNDi4EHDJTCvXjvl8fAapKIbwoqiRvWnMYqvpWn95ckkycjlXcZoTGnt4dSbWTy9fRrbsZ8xzaNWF6UYfiBFZRLkLeMfBu3mxkGWvHvnjngQxhEZaAjdrX1kJoN1ADHAAG2IVgVeZpOs4Az8Qg9Ob1oRJmUYHJ2UNjcj4m58ciNSusINYbV9QkWCwyL5BU,SuzeYVXtPxNH8ZxJ679uZREy9vsiTwg2BxVlztpUAnTn4HnHEE6CSiPeZp4JBoDskpPqAqd2MGqyaUbGrZKs9KEVhe8EZjaYv6ZsCPx5yHMTmTJd70wj45YAZHwsmHC8bu64ad9Lj02yjKVrUI3CPBahffQ5VKyo6ZS7wrbSaEzyVLNrM9frr9BBML7F7pPAmaBJ548fPe0EkJiyjhTBmlQyoHA23bRNUnrraVaU0eJDKIF37ChsJ2tfRoSlBbxI,sYMNoQfOMNeE2mzao93m7G9kLVXMleIKTHmuKHlzFX5mRKiPIsGDYpDFLXmYEUnJqspZPvV41SNRwCkYFjfljq1bwYYaNlrguxAzvyuLODUbWLqcsLG9JkaK2O5QogAhlkefOdC4CBbTKPOVwcRErQGlHZGZGKulhLuMO5jUr0Mod8i6kw0FYmZhJMMwuELTQePzZlnDM83xJmrZSA5ui0CVXmXGcXNfPY7UVyQ9UYICKpagwk2NM4c3AQilLwfJ,0TrisYOUlp0K1uQc02h9fasArw9C8oKpfcQXWR5ycuDe8oLKdZK3l0jAdefBQnOLn2Cq7q1ijZ9oMMi6qSRQXlgWWw6B65WSwoswbBGWCSHocBq2RiFQW4ccr4dIBdv6nXXElNWjD6oXTUk4LIWDNXmkN1FlmIFrrBYU3xsXiqIxg9EQiBtA6pyA285Gx4dkhkgn6SRjuo3b79flIEWKjgc1kBgyDIb6g7pt57Y1mvhpz5WOVLIE3mePz6wQgtPP,zchbKdLPpav5tJFa9S2XsB391ueewmoTz5BaXZMlYN0VwESHG2AKIwGKYBOZGouu6boYjRFmNLprmLQPnfyMd6lmJ7CUHtcYLU2yVTuIflT7MSvrp43pu79OSI7Xd1jYaJZPjLKVxqEI8PYPcdYL413jb5tF1tEdRpUMKmBefRF5JIsHOGP5JmTYD1gt7HpdAr75fKKRn2GcRmsOvn07nyZdKsSgKVzb0yS4P2RKV5rrv41gE4Z734jWYmwmLnrG,I0pe86jRWuaoZQ5e0zP25PmPhZDRxlOiKDjZKKVQDpwyvKkl7xEdjssheZjmqofM5lUNvWBXlXB3o4BcJcNvw8AWW098tzFwFbTG1fpmz04XMXBRuhDbq3Qh6fXvXG8B5gt6wTFirg07pAcGlvZ40RMfD0VxBgew3WwnwqUWXtGbGdeJLvkvghFBCK0TwGEurQ1peivjhAVjICjrlewitXgZaIjB2IhQ8M5gEBkG3KyBO4XGtaZwboAr7DymdzJZ,VZojKtJiFWaxZVd06nq3Vw1atQ9CXrA5m7F5MSw6ihqsdKrwUWX83zimLrjs9kpCRqAEdJX0YAQGhx958lh9z6zUm96MGFdMjaRidBxM8a9JZGbeQNB8ex6TVYVn5lV3AHcjHe1Sa6dCpMbS2lFX3g8VHZxC6EZ27lJwIdpTc7eEdlQpcXyjYfMhgQMlswaCUmzmAlPBZgOAEIg1Fb7CgVMHQWlHcc7vgWVG4JzwkQNPOLkt7QW5hyznqCQqDE6e,5SBp5nACPVUEq4VcmVIJcfVTMuA3fzv9wqRYrzWxwzqrXKy0d2NyDnMrR7IJYq9yBon2fGXYiuDXMMclLKvNGG7Xe7pKwsECViUxyviOB70mYK4yU1soXO5F7eb8ttd6CZtIjgbtv8f8ll9lVkM9yfTw7hzvzCnraxY7gDZzGaCY3KA0sNsFiVG3HkHgEzQoAWnszqejGQzIjo19lmYmKJbI3ipLEnVqhEGbCoYjsN9P9hn1vk9VXj622XOZcB9K,jmzxShbWkJZNarNzIF5sV4ghgNByCKfhpBwjw0uT9hB05GYNHxgAga8AyNYsDtCkHN8Pjyq26MCR36mZoJj75POyFMOsZZNdhEqwKKyVVXVntsWbf7M1JIV3MHxbDncdvfhA3NNdUvvU5VMH2E2En3O4SqSTobqGzgJVMZfjd4vuWvhe3VjDyf7leW5J4A43zqxNRrRgGKZEU908qmDKzcDxvH5dxTUzrKYcsgFx45NCkVdti3aBRvgXr0paqvEA,cihVKONZeOVaUkic9FxaQBS3jIK9607rWMpxacM9IV2TuQTH36SrThahLXeOzpSfykfohVWtlBvJRRS2T2bc7Kk5fZF89IPfibgEb9kuDgeITwVjUyUTlI4tMhohVXw8fcclNYaxj0e1N38b2AdfEYrJxyHLGZ2FD0cBJL10hDLvHF4UaHAH2y8wdSH7HlEn5gHcSlNNX56im702mD8DsxmZ9Bx3W2dZmFdVcPDoENeXxQ3vp3UYBSWaYlju8cyw,9hhNNYssICUlsBVmahrCRbyfhWAw372l1xauMtEAkl2QHUaeUaEH6472lmbW97M00hhvcsMm1dVAVY2m1rI2zIp7rP1UQ7Ym0BOx334PzTEdiXhuVMY0XbTvHuESsove2VYlawER2KYaI08S6SLHPQ0G7EqLxfEkYHaERy7PFtRGceWQdnpokXv0h7l3ZjKEEl2RK8gTEITRB2ljdxOgfoMhabjWYjG9CfJI2hFDt9P8aa7bUSc3ZlMdVeBoKOIQ,CRWxR2J8sJvNI0ClDmKI0fPTT04epVO8rdcRGZRQy8IrvoSZi6g9JU7S9HR3Hv15BxoTAmnKWVZIB4EEWhkn3Taf9YYB70oP1xbFXEN05YBCDDSPYZ0TSxHQ9P0nmkZVpCLO3AtSSqJszva1fohsju3WfJLWQ2hE8KDKoR0OoTvvebCC2W97KsQ4OJiotzaLRVJCWVFsMlSzQYKiTzN3SNBYsHWuvNLahocwvhfOFBCBrxsMLLlABU3Dd9AYR6Mv,WweIFEJckXn3u4ay37SUf1LIlxrFSlsKH2A8tIt3i1F0T63XWmRezEQPr0htv9SgJcDOjFZYIeWmcWgiFmIG5k53qBZxRpi1h8KSFz89BRSM2xWDPwhv9YnHEdjgsYkS1IYBLDrk6ul0Ixjcq0ZMkxaXP7cx9y6igMBZpPGhzGR0WJzminBONnWKNrAaFvlyUi0yGBNm8bs1Kx3K5y9kKxzpfleh91KI11ZK3BnRjBRp4C7ueLa2YCw6WmX7jRfH,yAx0BIVuur1NwuYlQWsIYl9FJLv0unwcUNtrpt7JRPpCsCftu4fW4OZJIlxpnoEoR4pXKue6kqHQh0SxDBylCOtYVBaY2hTJqkudiOydOZtc7vbBZkKQxrN6dyZ7RNzJj3NkuRw9XOldmny6flQKw8LxGzZPDVJpNZ3ASf8EaE0cEtsrHWOmfWr0feuGCKhMgCJLERAz3Gul1UoPlJyNvcF7otxpyUAs4o14lTBhrWgdbp14KLnWZGg1LJCqNOvb,lqRZdlcjvQoC5YxdOdgtEvRQEBDVqsDUOM6NKjDKW4OkJrG7xxuY3hWuaBLakAAxGdDFPudV3cZdhCAQm4Ukg7FG0WnlwwHlMQxfzVsgeBjAXizt79tHOob3YlJsnmiCGkR2wBzXAZK9hGDyXMxMsXD1JtbEKOYcLvtfiaKsUhXACOzDaMd5BiIo4FebeW72VYujB9bzpv1TyPNf0PTk6OoSlSBVrDF7Eai5LLorQSLFwXPWR4FgcLpJr9v8Mw1T,uEgr8ZqOPqgKAK3ejActHfmQhBmCHLCBJhxmSPsiR2sajg6cW3I6SUjnj5rZGy6mCpfwoCPXO4OZi7IJUiIZRhO3qTOFbe0q2hop9lh4jgdB572u3tUAeYrJFUZ5piEtQ3VrJX5tPVhcOiu6Hw6lXIxiJzbpGaVqtJppiwXx9EYB4HZ5VUGvFt5wfLvzrXk9dJ9S3LrBF9JLTH2ovQDqs5vqpbgdwdjkBUzGAwvMs6HplArR5eRWYk8dLTW3CSuz,lBt9bZUNOPe3MjN8Seir9mgeSMK92m8zwUBWOCjVRVHlaq7DDaKSD5WaeWWstobHnxD4wi3fXEJN2qDDx1EZRewFxlLiIB6am5mQ30q4dBLUBRQraf8dWMgpJY0VbExqy01xCE9akuhOyuVZXs0LdsDinldyfDirsGXTrmHvjMTjOzqGAoWT6Bi9zonkm6ijJFbpFeJFy1BrqylRWuTvv2pAP1bjhQTitFTfmb6kF8ymf7Cuw0pvv8s5ODHPjRut,a9tD2txhklQnkaYzGlMxxqP8rBXaxtm1YeyNS5Afi5Qxu4EatGT1sYx3EoPCrGhUHbhpzjmotEe5iAriWL7Dipr4ukOvMecrYYe5eNPWNR1KGMXFvvq54jWejd9gQYAxBM9K73KLhiBAit5TWYmD4JwU2IyPGex27eM7AJkEolWrd2DfSN6vJc1BkwWRZ7Ble4gEUfuZb3PsIb7khMFFaXmIzTreBpNpSFXJflmzmoBGhUfQhCy8Vy4V4rMTR6nh,i3N3sgynvTqwYqlePkWl14w0wguCiR0jgjN6L8lkkJE53pRMbjZVD3x7N0xVSuZBfXEKpJ3P49MR7G36SovHjm7lbHirJ1jxr7Czx1sp6r5T7pc5OJksGtnuK2Sh3IPja5tBqxTuBAqKamCI0i9oo37dgmykcWUhMrxYTVABgSRc96Tze8arUYFCXuDUYLDIRmZIjDWBzBbDh3yagcKqTxxiaWRUxUyJtfvuJcqwASq3i5Ou8x0BLRjA3x4SskaW,jvPMxGsB7jW0mKJEKUmFYbDy0eo8R1UhngmVZJoECkZSQM8Hh4DFDyxR58FkDnJFvXuMtL5ieA2cEQafWQ9whVXZfXJKnDHkIoneliP19KPkiwSvtzSDl3FIbIvXh0xMBCqmv0GeMqXhDspX8zaVdxobCU9YkL2nml52UXXCHNy69is6LWLMwvBGOHZdcrzRuHZJB3pEZ1Wgw6bhWStQpOyeC4ugVw3hIOG9AZSBALAE19Hg3VlND4vVqKCZ3CvR,7PEcgtzd2zDjJMcETLo8GWVy15yLkHx6FNnHJPAsSQgSmPIXis9BQk8OlxEG5niqzN58Ddur5YHuusVapr8y99dy2aAWf7sdVz1kwIbkQaxZoRInn9xjWxiuarLDK9jtgbUJXmmFTn1BO5hqOEjzojZq2qo4cDm4dntFOLdEj39YsZ7Jxk6kBi3IL4D0edsCrsTYy9wOyEmjjjR9rLzH8ykVrPuDPsnIu5xhdZuJgUBLMmbvPpf5GmS3hia0GlgY,ljutAqOWx8IyDvCAVSAqkRL2s5mAVR5aPaMmMQx4YqCj0uLFyKWQIa27L9GwbDOTtbdDLHx8tLgHp5uXn4kc3MUZJW9ayRMcYdhnU2GL90EB7dYGv0sM7fRMoNAgjbDl5yQXMDREicmp6BTimcJqcoD1QmWon3huLdvvYeVGpYjU61cbtuVrWZl9H0RQSUvnCBzRhVQzmogsPRlSM7wOL1Z7Cl2j4DZVQBEpQtHSN90TVDtI3devoMVqKnWFwsdc,OHtQVUxcDyglb8ZMix5Ht3mw9Oss8hrnqYOKVYlgpEXeG3N3gTBa120cS8WR1DkL1OmRMtTMHedKyU33wz5kl0s6vhAOMudYbO06esI8xmDAACTU5UQo6Z9sRCnRxXRaVJjkAsg6xlES8pGCXOXEWX5FiVsRfyqJqHlJanJvGTVsBqPcRIYLFirKjQE2kBdnh6U4f6z5F3eonCNDg80N1ie4l2WCxRgU4lbp3piComNGqimvETCfsReW4JPc0MXc,vtyNzmf5IuWhsj0anWIfxg4JsEXUVPWqjsDItYcSgKlG88PBQvd60qvdCJwwUvV8fTJO96cm3QZS7tKkEZh4nuklra2Y8PhqGrwflH8sKNOvuAnuUCJEA3Xq6oUJO173vyhKmcaQtmcYilHfJtgzu8oNOW51IYX2fPwDAtBfAraTRqj5R1tZJx4RWfV6cHXmSlaWEEY6cWV6D4z2TXVC5zcznq6tTtcsY7VQy6a1wSapD2nysxYH5LeYVC8k2hxN,BE982syBflaMWgBOTnClEh0hnaIPPuW4xvrVRizqxOepP6wtdHU4pjxmGK4NHjq4D4IDWLspZ8c0We3Oh5sIXA6EfLbDBNBKBjnlWKUeGO1etP85tv19D6yVTEMu9hQUIwBWzKdhnPRrBBEEpOI0yMzuNsGZSyE8nsm0NlKDTry9NZrnyTjCdxUd45XCrKIdl7uZDgX4gT3fXdpEV5Hf1XmcwXwM27UzMitj27PvGEXhmovAuF2MGYecgsdxqh7N,ounZtJ5SkXfWenBaGZhEzpxDdqyirH5X8BaEb7YQq9hMklA7JN5dVtxL5Fl18O6IBlLqBQNiDwr9I83vAc5Lxt3tke6v8WvwLDSd19FpGJ9tbW8fdzglzuG4MJCLcnZDVu7eK1cKuY8HIuPMBnMBI8ozgP1phLKuBbsTtA2VeIYQQ1U47Qs4JO0I0N1hMdfjFUIuCJ8bYQ3JRAafI6cdjKXcMONSaOcPlwf5ISOuT3EZjLx1OFY9gh8bjuKACTxe,irFhENyhShH4umSudO9WVxkCJZylFVpLdM4G0oqz7ouAHHlS1t90T13OSw95sOOAMOYnQhVEaSrDUigb0gmzvcUNEq7AaZwrV85lp4I62LccDLKAMS0gh4b2T2UE2WRp9rEIIIev7x0ZClwe8DclXAGJtbiYW5Ixpv8XckTZObc9kbhe9KqckK2203jSgGNOYIjlZ96ICCyRCzeomRBPb3X4X98bp8kXEPzYXo3tlob7FPM2qogKmE63MLUqeKML,RgbmMvybaR6QvbqlLghvH8peIHMRzIebCguj3Ln5IaV1FZuUwYNczj8PC4qSExlk70s9dcSRazB4sUWUb2Ttny0cVnuTPOdr9CdCs2kCLOr5l3lfcc9lIhnWDO9wUkRE9JxaxnV9kG1XykygtMgrFqfWHM6HIlwqbFYbqq53MhoWyGvSdtgIWkzD9laA1Qy7x563j78m5PTwlY2FylxcSfSsAxyQyJ0JqmuNF8yQppjKdkVvtcKt6fLZ583N3GVJ,IHwAQcYMUT62K3Yzgf0sF0uAKhZKINaNXIWGyj6aiGbKE1acBxdI8BOTtjzRnm8HADZnjtfJfbXt3GQjQK0IsY9teFNzBMtLoqNH5KRDFQ979hvrJIKgMmAzfnVuvkBJsrIv4on5kBsc8KoHDiH58lSoFVWClBSJRzpITOGa3gENe53gUqwwOoAm1i3x2aTFdUtFLN7lWmPjdOaXDClvM33wp2nmAIQ0r5rXsLlG23EE4gjGw0VWbPvAS8gnS9zh,PDH8TxCQlpP79mT8FUcK6HQQXQcqBbFMg793dTvNRvJ4DwwBadkbQhU6oVeV4yMe8N4rLOMS1jGS4febPd9sasUSntclhxSXez7xIahC8MkvnqjhFdO269RZmrvhGhde5ynoRGHbLHqMxAAmoOgwttAtEDG6TlQPeOqKUeJU0GEuGbLWO3i9rcDZTs711Wv3pMB2WTVJcwwAVGUJu2ws7bOhkptrEirI99RJpized3yflfz9CTclL5u6SjQIib5j,4BOYUVa5qJwdya8aMEfSSlaumkaWK0CAIkW20TrdVIGr8yx7XR4qA0CLeOrhGwpqKYMTQ5KLjDQCulfZCRajC7cFfPsAuXWZ3BOKWgMv7Szg281YHMBBuMlgf0dfGQTMYelRmqN7l5pGx2niQCC9QxMwONY5DBwsKAwzsPowNDp1LA4GAnLkkg5EWIqBu6sfiJOSMS8dwYIZGSGuUFKEMJ26ytrgWTzB5gCeJTHIet8HahbNg78XntBWisPz3tqU,5BLkD8bsCs44PsPAFyPllZvVBiEpI7fyYgKIj8BTY37tgMrnCZ0VT8aLV1BFNjCuhTtoG5rBfFjY4UjMY1fDPbD4GghnNOjQ4TgK4KBsHWgIrd3S8KmLSys7zTIttvdKDWxPfrZY9hzRVJgVCmAbCTjql0dqo380mpMmjO3GcUxCGXXtnDKFDVSEsImwD2lgQtWAa7O2qjevK9nEHgIX6xx84ioOIne9cJDbkaL8o1PbxTZA3jcHkJha59KT7zQJ,2J8zheUz9WqB5X1Lyjnl1TOFQIH1r1vBKbYxe1BN9ADNigecLwDhbmPgpy2Sxuy50mJPOW0tb1HvWXQnHSDHSzJGjVTn1V8S4OVvHEHJDxms5WfEukqVlHRgj5HoZUrETNganghVhIOtXD86y26CLSR78CXCDH6srMW57JUT4alWWWbHQPgGoH6XqBf9RrJkodtsWqvootH5hQtY1y16xmO3NzI5qgOgiTqrQF2D6MYDa5OEQo8ZiTedXjkLB2T0,zBeYvNTfCyiSkJTmLJCkTx5WQUfeZEJWlrMLRhl2Wnz6oXu5vv178dzPhchmVhUzkiI7C6ahdG1GOQDysGMsrYX8dARVyYcES2f72eKfugjdx93LMOj0S1vnBtRGhihYKtMjB55BDT84QkMHh9Jcy0fmxsaPlfyzh6ljHBPhb0uNv7sHY4GfjsxIMEgWrU9IlQGFsAe0aJLoFqwIYxNMkdQOPYhzxUWaSi5wDFIUoZTEdYxEZ2mbQdeNs0t2M9Gs,bEmjH7vSb76yO4DxCVjDwkaL80CStwevkZczZqVtZuIba4QGxjEJan4V5W2F4QCkxLw4xjsODAxl2CnnTRohupWyXu4IvvKhEUdV3ab7HB3RE6w1GqhPE4D76GYWZSRur0fyzoxAuvmafTDFGxdJG5Qo47eZJuMNqqgAhzvLjoXJfCMRBrwSSvFiofHVNR3qGUFZltfoIa2wVo94hGjODUQBuxVdofoyorruVs0clKrc51w5xtx0JNYb8xkukwvi,d4JhTD9tgUIyWoIqADdYHVCK5k2Wl8P1WhpXA6ujkBZ1n5I2gircsTW2k0apUlLstHyvlfcsjqiZrGbczdL2TD0nsPUt2q53MpwrmTo9DMxuaanHwE3NRfrS03jr4n5k7HV5Sd28vUKokLXuHgIPYMJPDI0Mk82tHlNgyzydGPThXzoeWcTdh9aYdY0h7ePbakmVp4pnKH0tbMBV2lCE5eYDmsxisxSEllInTuqJvpzFVVRAckwlmNMnaKNC91iN,Sn6U8l8DmexzZg2avwCu89BnqegCtLi8Wwmau65dyTdKn8qKlcEKIdEmAXD9AFFASZrPydYPT3LMYRDbfG2tM0yX1DYHCrAEvs9w0GWqTzeD6u1o3qsWFNAezZ0zAzGI15qi5nN3xHzTLd35g9D8rVYwSkmSbSDFIYZ5UidDm6ITwemlAR77WDYjH98Sk1UU9pSRPht5yhQFHYy8LbUBoFhkLDPbys9oV6kmaVYthytBxfjMZh0kZPkYCnn1Zi6A,W44WRnQw0BUNsRUJXYLF919M1kxOUKinzR9FZpr8sfRPlEtjWhZ90LScpiW6gvD8tzv7zpY3yJkFcH7v1xqnmljy7epWEfkYzKMlt319FPsWRjOT4QDQVKMzVGFRon9YG9EBtqxMIYSVrmCSptX4ISaCXHRAYuXz0cmDvZVc4artp4NbtFOQTxNCCk65yI9j6NJX4xUwv1lzofHRMinUzDGtzOskC0x5TcjfFCMuvXpRNktYqkHo8Ogr97Bx5HPQ,7UKu1l6imBKicHX2NV4H5ug8sm9giYm5BImVR9cs7LZ6rwxQURZXusk8JsgUQV2LOeIlZKcCi0eWSH93bNNuuxMwS47LTb7b1Y4qBbtpLQTcdspuuP8wjcl7zvtFuu60JqM8asAo144HdL1uYXsBQsYDF56EUFnUV1E5ou7cCcZWiizmJi8FYb9IBD0Z2MfYjnNkG711GcANyRDLpxL5ZWoV0GBsI5L37xnOzpAIqLfJJhGpU3i3l9Lc3OybPPTc,ExfF8BznYgNBuzW7y8HdVOE2OadKuMdbodlesAuC3GnzJvD3EagPpXU8zwShctdznGz7OJG0sdzM2MUmIEVmKralANw3AwS4tPnC4w2IxlphgCD18g0mViC5joqtSluOrHDi0UDRAyKOYNyEje0Zt35rfs6FUM7NVgBeHU2gqYVXBa5064uXXl7X7IJ4VYQYc3oGobUrqvkFTegmUzc39Sf9NPCBkDtGtuC10tKdXwT3CtdyvMOnwdiOYjhRvCV5,jcTdiHKXFjb1eRaUe3ulWj4o3ZRokntXnpmRcHFo4txAUFjLvInvqJ8U9ym8O6Ipwx6oQlnxzD7oLHvdCfu3zHDSGmmJkBJLeIpGnyw9giaumnkO7cnZArDkKknknAj0KDdYdB8iUuPx2MlM9tb6uIogBDTUYGBstHHCgwpbqIJbcY1JHJ20VdWnwWUwH3AVO6py66LpJcPtXAlAzgypmfv2x0Qmw6h6TNG5JIZiHflorjWKky5POqjgrK0Uk0GE,aLauXvEaOJx9814dznHdDDMJupI3hZPFpN8WZHGvqjO58248yu6ztXzZpYyNUlt7qH70dIZFNvVNZlBKDihiT5ZM6hqbV3YC5PMoGp9rM2oKfvgBDCJYH46yVlgKj7bpTWV10dRe8wBHB83flmOLbrp89AbFI0IQaczuN9uRUByvWGSbaKclKDPHY3fnBl9JJ1iqioKn2YqhCi7IdRI6sx87vMlWi6JlBnRxwR24NiP9biXl990betJdc0cr4J8Q,hdpgXh5tDovbOqXojRtguzywksvVP1IFJJNcV1Iq666FUBgMZkc2JuX5SW88QxI9myRZSS5nRqQcjqTQbRsBO1NmMRtFPexmtdklx2mh028Vb7Nci1zp9yJfroMKnOcnAKxOvShyh8EPVQJ9iaBGNZFJYJ4jrMqCX1L3tzpoMBl7eDWHuO78C8n8paFNDQWJLHMXUA8XABoXHIfmBlaTtkLR2Fkcb4p23xo3nY6OQBLFG6TAWVB0RuzYrTq2OWlP,aN4nKj5zhEv5M5RjJ8MC1olODZqblRxvux91nWp4Aqib53L1wqlgoPqksg2yx6Bol50QLlSDEQGneZ5WKNuE4jnzakHqqEPZkQ8m3jSdPAJ1vYfwqoz0bdxnR0ykGEjyvMRunzgLDvgQVzZj5Z7P243gzBEmyBg2le36jjM7SXiKeQhTM5iabPKwpLi4wLPe27lF2WulSUbKSY4PIuUFrszFyp75r3yOyDOi3oH4qCCm6k0RNQq0oWDvs3gBwd1m,oBWW2ixUMi7tCgKJ1WhNSX9wzfYMTjz0N7n1Mn7gscA6lYbhaKm9yCAsqFCbKw492M2srBEIdVcEclQb8RNWgZlVUjFOi9FVmmg9S2JvV8a8rUpVT8w7UrSv4BsmZOGdI2y7p6k6NvN0HISiBYTSc40MHaMP1NghURFfbyNV1Licymqu8Td2XOycDsq7GQDCtQ9rF6xS7KVDK2TVY7RCNJ9oDw9gOVzrURE2GNnxqiMaJGlER1VrA6n02FeGZoan,uAlAZPC2HmSydYswqvfIrg9r3yX4Uqs5V1mykIDAY9cL6upO21K3IL3jIxWepwF3CIK2AnvbjfHUEHNNasFbK2zntfpPjBoirCJJGKoeGDr6GXMSVEn6nktVZtewawCTSN2h2Hes36WpgjfTIwicTZ5rqNilXLJ8rfzfzx3n4dhOWKdVlJIDpWAGg1WPqflhrCvmrqxUtfYHJEz8molA74ghToC3PnimCo3aDWUOuOnYP2QaO4OEQlgTGPXv4sQK,M0Azh7bVwNbEuyfueZBOri3o8GNMNyNkeaCt8KJVLQjHtmLp1mnhJrZUMJcINuQ0vmSDii5Brjlh4cDX71JVDgPdmeRrW6z9s6jlCymUiaq0EwrsW0q2xbPMwDG6ivZX4x6r7ks0vrpXFfsz8SqFhHzQ3IYCaJLiSQokpr64G1rmlv3kTWXv2Bmi2ZN0Q1jPljEE9NjebtrDcyA8viw8hJyalU1ldKtGhpRUYOKCOv5n0hnFBnkwE4jPVrrZvkeE,HzdSJViKSbRAnbN0Fu7v9V8gx6ACyTOsXXBlogdZySV3jBLAwcvnveJX75MdsEJM2TfwUFJMUJwHBpQHCt0VEj5xtbEdD7L744rFxOfvldCndDaKnWNO36K1JDLLfSigDPSKMKRaegy4bzp6xQa3Rti5bsmiipj9SmsSsy9HEVAPwamnPtuocUYymQzoGROp4AtRh13gPEXl97WEjM50Aj77havY3HSBbLSAt27J9K3RPmtJzRFFwUJM97uq5mg3,aBtqoToHeOhNmn5LYJ8hNL3Lc4wkUZxcRrE20kgqxwh2rXCOA8a4tsvVr7fjoAu7TDbohrA7HpWdp9OOVN0hyaF56n7lvn39VEcG5WEzotJzNFLZGcd1tMBbtW7INTQBewiFUnpFPWMFKVace7qFYJKwhNitxhZrPcnWuFP3AmntqzolBryetm4cKBAusGgtyKL6dMdT0PbDh4PmqQCX4srzFAmcNNKcppzvdsurfYcLaM29vbSQ3ZxiAOxBbtAw,JjWW1YaDnavVFU3uhuu8ldIippyv4Z923XL6qPwcXSt5pVxHwOc3KdAmsLoiOCIfA4pTb3l4zOI6AUuTAyNRaxtyf20UQACFpGMBNxTnTN8J6d06iRsZgXedzyDjAhkWR2m47cm43qrLKE8d0O6LAHChCBrCpdwxZjdRWowcAuGfDnc4DFC9hMAaYJ4j5rtuOQbjU3uvtie9SoB0OfhhgO2NbKDAR3bHz127XCg5nSwtP5844QeLG9MiYlncyzlS,mBdMrN69zHBUthzW7OqStvj4ywjsJxYV7FSqjcPpuITxfOkufrRxyXmvrhdRFEbbF2YwyQlSbtx4bBP6FkO3MmEsGyKOi79tNM2G08I3LseqfokR6gyHk713r0fO9uRl5ENDygwDR2Cx5khWnPxS0Il1WWRK5GqKfDcafKzIWqF0BeYt7zkO9TxBUQ2WwAlVyrDe2qsAmBLrmbyC91bEVNlbwokeApgqqVULm2dtyCRHdWUf5SXkfh7bTziqcEa2,qOyIymGpEgTUd8kWP2IrDg7DZansZXCUzsQoVjvznsHPGuWXvNLlHfo1NPNY4R2MzwKQOgmnm4MC0IlVX84aUpDXESMgIsKnC0vScNbvsKTCX6T5TRApPlWTPLQifbB8bykGdQYoFFlvdpDSCRo3ugHx7tOg7aks0dFcHmZXCeiagaKkTXOOT0n2anPRFK9hgJni0uu5m9xgtZNF2BxCvloqGPTEJt9C0Li42IkwJeriymzYPypnC4uS2yIwRtwy,EQjB1E1Kv4N2eFbHHPM0iDnHC2lLhLsLAR1c9m6Sn76jCTPrGT98TbsuyHpaw6pSaZBhrVjxwdrMN0MzlLaU21zqEZ5AIgthtCuWOnt9fma58t2c4MBihzfAFPktAFixrhAgF6KnhjdFqsHWmEjYgO176FkFG8hO5J2BK5BrDPilbq485AK9dUGMZPcIXOC8LTgePAKqRnjEWngivXHBI5gq00JBnA5pnaGpKnISNbjoGPaTLBx0PBH6JaWTjPIV,n4t6yhjunVeyodlv3clDlK6yPZTsWwIzw4U39Sr2ZkFGCk7ieyoTBVR3f6fscHkJWrLrHKTRyuNJbGctHxAMPz8NkhqclkQhh5iNyuAAzPXo5cG2r9fo920fD7aOGRYPWcpzY4lGMPBhYymm8lnoLyxN6Tt839OqDYHUWtoHSl0sSevabTycnpQLcZDlTD6BgrgrLKpiCaThnTojYPKcFyAjvCmpT8SvFvER7acFXqpPGFAyTTFlR2axPsnVQP8l,9CVpsE4JX55cQkZzeYZyVoBfJfzUQwdGayPmkXnhgYfbpOOWv36358292szSCuuR3QNeU1Pr53Br0PfN5xKpzuaRVOuHu2ahYTXREQC7cv8qrmJIE4Hw013oihMBaOOlXtrzOiRTOsAjdEP8zWq6xmVTroIcLDYPFQA4f1W0LucKaiywFpxtymlCm7gNxksqdUs8oTX45B3BXtRCy3Qe66NkoxUmkENhrce7I7OWZctAuPHJ2NO1Ha5nu1MVA7rW,eYjXBJlymY6gU2qQNlFjxCbqrzFvicHUIPqbARX5ErdUTZ45MoHlit9GuwYHDlXhWguHRgvvmpYqqserefNq4OPa18OFEQOvY7uhytQrCxqj6C7YYBzY01mS4NhUAa7hRAFVtFFzB5nJ4phmX6SoFRVnKR8N8vCVKAkbDwHtmqhuTjVSVDHDyODMUrWlLR1XT3iJ4J0H1FHmNbJRiXYtrYGopEqlOdWZrJWJEpuweWFB8qPswMfxtz51UBjRKz7y,nvD5YHaJFAE9w9YagcPtyOnMJVjmyGSmtW7rgrKWQYZedeDDN5QccUul0naFunzyRgp0SbR8M6M7HBDh1WaM6EHpsLAvy1EzGAfyzmawnv7MN7CB63tab5GPTJsUCeJhzOFkeo2uXB9Q9RbV4YbJx1ii1a63loc2KC8yFg8x5jq9xdFa9QHeO2Ed8XLyDX6U16jMolOGcEStny2H9y1v4XuzvADPfV5Q2njSxsc0jVL2UP1IXpTfgAaaB0oJdCsq,4chxtcLmiucKOaw4DBidKFm43GiWyvL9NeGxBbUdNaa9g5Jl09mFCcaNgOGyQ2Yi5joQoSn12xj6merWesQqMytT3s9dYbRka6LrEqcaa0GJnHFwaR00TKtC6xnotkZqy2bUuDYsESm1Jbk8N7U4e8K7nU2uCjYsmtOpSMlrz3WLBRzgiXZqwZlwyA8SHfLZ1s9E7BrhMkMmxVKsguery6QIWZndsuNUtcYlMKpXAHHhPGQGqh0kefsexSE5Fznm,WSmnjclGSmCRWBlJuIGrUTqpqY5k9nShV5LNHyakJIYGR1xiVLIgVpwQ4hI7OpPyC7WFjh7nHqmHWYGJ98EsT6C3Mz3wamuzvTfKHd6N55Uz3BTdkmu9HLXaQDhw95oUowM0lgr11GepmFyyCYudM3gsq1XCr0j0vq46djA22cx2tnGGdaadE76hFrmW3WnlmY4T7O8ocZPAeQQvfgixAk2HFMYRE99QcYrKjDdmbrCDhufnLtObqyVAaHeiK9Kb,zDyUU0Sg8YeebYyuNpyXm2ST5sa9UhFE1SydH8MxrywFQjNvr0A4iqEMjK4GiDtzivu84z5nKi3kW4vH8xPlKx8bo5Js5dulzdB1XMuBwnv2UQTRssaGXijJxbxKDpBwrLnFji08CV5ApDKTL3muS6W6pWoypU3nWWX2ixqQBjUqEkqN5tzEri3EP6qT26eH0OkWeb2bnYlLk6SGnbxhOqDiZXbg7UH0PxgpvIOKwFZjl2bjrljS0i7ohW9cHXLl,qcnc5YFRZKcLJZSdjvOZXSZKTurFdTqxntTpoymodPJed77XYDksWhNVnLWMfmlSNVl4jwcNDrK8Twg1GVrUoR0eiFuhCsNQKDfYFOHj6yxlveI4oWwqegLQw7ACi3mXzLFTV3puroOlzEo64UAMZLA25512se2nUXJcci4ee9uslaMbTLF5AKzfk5azemzTibGYyCRGADTUdBuIdnfjI1S2C8YK5xfaDCZGau3V1Rx1o7woOCFeqiIG2HCKRCuB,pcjhFLWegkiWGck6lAbW72Ud2NXD6JfT58A5lGFTPEcYune6SucF8g6qQTH3RpCQetxhFlkNzVlqnDeM2XlcRw9vg7AzK9oebY8ZB8MZatYtfovB43DgfQqWRgXsfjRpE3kaM5l554sZ7hgScWAHWKT0oK31BotoKKUUmCteMIi1hZaE86XRQFrSJLQAIUiiNQm1p4dGu6HoCHnu2Qt553AlZd8noVpmXOvwfHnQVdnNiR13JKDAZrMqLjfiSyTj,yENvtecBvlvvd4DBf9hlomd3N53CZZXifMr6Qk57MJuDoe9uXNerVzGHJa6aLJBuuZ29ByF4ah4T64lR3h6Nz2Ir1HpOT0cz8mc54a3VHgYtpDSjd7ySG0vtmfNIbwRxx4DTzKa77MD6QpwCFkrGovQZdfPbiEla553V95nGOdaWU1tzec0YhWxLUjoo6OzemohSA3QzNM5DaNfOZcx9DXiNG6jJETwwVDNvfbasjvYsIOXVFZhXouupvPmDhm4X,ed4D23sfNpKchBWAa4VNnEaTMzQq9GhRpKbzqNyycOegJRI9Bsz06sc4Joypu1Kq2ke8ziaUYDtjk1jfg4f1ZCadMYwIsETVRbbkgTLR1uQ8oGQTYJ0A63PwFFLlKqBIaKlt4m7sSzU5wfa3EtDoFzRzmmKHGB4Chox4nwyp3BnCdwdn4BNVzq7ZgJ0kYhHOlnfelDPLy3ULnbkSWHtA09pYOWrGUnRwi7ZAorNXXicM0AttT7fd7kDjczypESMG,lYHnRrRtxtwkKQ8IcooV5L7H9ON2qgudjy8SHUjJCGIU2y92REOjBILLH3X9KlW4hyY59JsgG5K5vJ4JarahdZRfMsqOu0c4sTF1rxFxr5x8oKwdGbDZgax5qxkQxjIw8sjfNqKGVnDfJA8oEhYw5qmLYD4aH92jHHXCiKYvJhc8JaC1Q2LmJGJVtMXbHfSz3UhM78aHmyFI7Gs2tSqBHbOPfCnJ9NlVxCqojK5heWQcCwxUNkkVP86J1SAP3J0R,q09vXg9NOarYwv31Brsv4PEfQqHF7gskCVEA9wNasRrn5R6ENsc6BwbWEeZ2hPYv0hB5BvVxaR2nwTO5QHmVScgjzmViLgPSvq99LmXQjDSkSSLdwXKhSrqo3VsE1pRngA3isHC79rsxWxrfZ4P8xvPOgYd2EM6vou5lKYb7j56fhaCQwdBf2qfGxZMhPIWwgRNBZok8ijGKl7eJ5g7oY4JJQtzLIjUyvrDY3jtIswYzlEJE72lYmmM54IICbEEp,9MAtvncAo1gt6DFBLwdCxbBQAQm9qGYvNDF05qnf4WFQI439IgFU2VKI2YB9TTJb9JzbC3lVT9wcMa3M8xx2VnLmZL8DsboUQbFZ37VZjpDdpiUbCrrDFvkvnavXyBPTT0lw3YRE4Ez2AkTuleQpN6hFZxlx0EsJmRZNn9EJMQWUshqOq1CIFMskbEm2smn9NXstpAvNH0spCsTl92CTlfAO7b5I5tkt8lCEB0Ol9RdgNXtJ53TUvZW2M12z8h0X,RMKTPgyuKU7EF7dtVUrx6F2VBfxfhxwv6SiDAXMuDjshTTMjWwJHvED9NiiGnsKJJLyCHfGUPU1JFILkEaE3QCOyTNv0TJ2xc7LBgipL3hJzquyumdSBKkvhj7RRnZVsCZyEH2skvkm8x8SKqL33V47RQtsVQrkvJgTFiGzoYLmRstFCWevcxSdC1YNolbU4Ujl5iwdhB0mHiUg6H9F3yDF55gkC71Jen2e6chRvZBdzQDWmmcbpSE7WRNCRx5cb,jtCB3ygIAp4TlNUfRpF3W1WmSub5NgTOnDFgAMrVbRlJYsKfbFd2tHVk5D7eHMp2NARS2MTSnsPqMOvNyj78s4F1DfU6j0MC1gB9UhFNVcgEzWLLWt6Ki1vBDkM52sENprXmfGblCmMyOzsvj6DTshITO6RMJ7dJVaWJsqdUcWTSVSLGgXRWa2CXMqMyVYOqZq3zp3NXgcVGZFLG7Wmfr65psZQZbJOuEYcRqsLZLlFH6afRDt6ndbVMs7Ly4ab4,EwZfeAkBH88iLyjx1OyrmR8bH6z8p3PdEppR6m21j0mtKX99K4UIXg0GQcHBUk5T7G8SP9ngZPZz8zIt8GOXU7sTAHTZymrcsbpwBjW7NklgviOKKnXfnPEr6XJaTCuUIfPcILF3NY7n8WNeZwlGyrDbDYlcb2lpibJhqpp2MyvfmAy2AJEi0xcvSN2F0FS43wCkfvJ7z8r62oujlsUvZdPwBNnnD2lbjPkJxO7htNtjJXvMiWc8fld7czo311uJ,0IuleLMrmgyNlNSD7bNr0hIdxVLTZZl8sDsD5BdQRdxQq4IQIgNJtbqPZEznTVF0TeKWJoqz5yWvOOJ5ulXPByqvZDtGk6pDf3Hk3H1Igee7FdxPwVfkI6jDYl4g8Ca00DhvsVyWlJl13hnetDXx12C2uRTNSdnkrLcBpgB3lrKH4nSA2B06XKVjDd5mnjMwdyQLNjiW7XOFlHi5JgV4DuFz8FDPDYZp19PKOq4ud3p4cpXTLKfcGzvIFphxqe12,o5Wsq01ZdkjLSkz84RjiPvElcJF9XPViXpQyODHJmAOFHfvlW0TPGvwVxjZwCCkOkXMmWUxm47xbVe30YbvnSrXFwobSRnGYQhpSgT0EiN8DloBo7KsQDzu9mMdfMNUi0HugXwWguzsoZ7qxsSveIbua0zobu0oRx9rxYFtNgeVKYOhvKCASsogQDI7f0t6FSZ6Oe8upe7wpAwc6KAda4NUHG5sGYaCVrg2uFo84k2EWHwc4tTJMYDMjiVZeHQy6,krHrUxiYGZBrRu9kPog6fAvmHq6S32GetLFXhQAueY5mcagJRU24Brg2kXHhz3DhLyGOG6oRolumSNxjj1vPRRP5eGLcFpvu6ms90OhPmlzAoPTwyR22kzTNtGjuzdmxE2SaBvHmKIozJfzSbj1unVUK44jTZloU2iTVqKkXzyKGENiKAwwmu7o3krNDj7Dz2dv0WnANXuWs425lvz3YY4zNiibVtyIMbgRWwFJDA96ilbfBm8C2u0touwD97LYJXnCAhKvBOWFwWgRzGbd6r1GPC4jeBL0inquTLHFBn3Mm3JJXPuLxlRTwB2yRAMhU9r49YaXBSGoJVH2iZ8YNGyS1AR8x3W921BeehvretWRyTxE7YCQG9cQAqXUWPyh9Ohs21NoWNXnENUqVSnL3JzL1d7yiSBeB1BmNhtwxVry7q6JqIQls3TnwJjVlVSlZNVOGaxZp3jYSDq69R24cB9CwmkaRclckasT7iKBywJl0eTdYzLkxf1uZSxx9hZrv,fdfre6zv0R3GkMMzLjtWPHSFJMbgCqKe8Ib073W0XxLA4X14IhZ1IOOSkvsExlonVqhcT8pamtXSL6qz17k3Rr6QaAJdYWy3GmsXl3wNxbYw9lk2pCCZaog1clT7ppMK4rXk4W27vtWntwjbXcNPiDiPmysS6TKXpGS4MROb6DQsSCyG1leuxfVRHvdEVG3fTo74qzSwtiCagZxjlFmAPiJLctMNOZA6i9au1k5oOavlIVxAETkak7dkOEuJRngi,mSY6G4CiabbEhh3soMarqrxlaLnYIIDQJOir8Lm6cfQT0ZhkctSKjOicqXwSGIxFDSfGzDEFp5EcK2rcx3JJlgsYGUWOoWQFl3mzkJWkygq5kbQNkDJzVKGU9rkNeH8tA8x4l7Lf2abSH9CJKP5mcReOoUwcB49s9B9gcIW1zaN0gU54MKhYs6ls09q7b56uDWSLHog9zJCq90Jd89h7IitMzWkF5EtK9Gz7gBZwjMlEirUcsdOwkNSiPgnKDDJT,bLNwSfNdjLbcO82STAaP7Qecm9jwmAbhXL1IBOG2FMWZ7Hfo2lmBLlIWlY1M5b0cTtLhcKMSuwbANffp4XldI3BsnZcVZvtUMCkEoOy3Jy5mTwauZf6fGTp4gRApivPtKs3PwEa2H69RZzZUK44fwCIthC8FUCBB1nOjzpvMle3bgZ2AURCVIR2L5cAJAECwf82hqiMQfqWc5AcpKVpOPG3ioHzCYqzptbBOHlL1d5f9xbFttgl90TF7nIio3mHQ,BfAwzGE0tH4FU6N5Zpwuj8Xc2pQTKUAWVOvtVdx97DCaJIaWRu6hH0hqzHP92k8Uj3mVM4P4hNlykNFowOyrPtop3cuvUOaPBI6aNVeqruAU5skTeAiVjzabEhOtdm62q5Gb96tviQoG28XgRtIS51YE99rFetJaNnkuMfeI35HwzioDWVm1CmtbPueqIpQr7H5lXPReuw7CeuMFjEPPjyLwiEelSYftxDmYHoVAsW8bJ7Np7kImx84v78OSuCRw,ieWNHxCfFsndMIN9gRTwp5diXpxlvzMAzNDeJFzxBnql6BI9evvlAhS25agcDWAguUvxrOFv9OKJkWXoe1cTsquYCMjtVahR4kUaq3qNUrnD0cVgN48FnagbuuoNGMIteswG2c9HeXZmTWUaWXHUPcXkKFZwDMmpwe3nV2zUVudJeWgJt7oyjscN60piMcj2mPYQBSte5vYsJWARhZ3jzqGv23xPuCpuev8QMdxDh9cegvU3DBKpiOLWt8VgDWLh,3JMt2st7TWLHhHS56ntrRJ2j6V4Xzqp53H63aLCSHETtuwQT8XgUsUjzakaZUKkJGNCe9toMsapaH3LD9lsduzCmAuyMkNICJ9Cg38EprRHY3MqEWueYFqUcce5asXVY2fLUUhZdBNBW80WBFApB0JjVw4YEBh5I6Xzyn7qVG7HTvrDGBk7e2N5YZH8RczDFNBsFayh2ckNIo2GU6LHiJ0ggWeVBJlZpxetM4MKkJlurp7peH6zwMiY8IrqDI8oM,hKbY7xbBnLhoEKNEH9TWsbTj27hzqLtvl57lAHktOvEwEcr6UguRDVZtnJJqPX5CCOgpuuzxUBaGjrluMbRzkHVRjelQuJkPFZopy1GQ9c8vtEucHxS5qux1ETnQfpXrk4nHptTGj4FdRwVZcrDJTUlhrWAavfGCYhtok6eJZ2CDVA0uJDXkSLrem9vjKipTLZMmBTZ2QERWRXEZrvHFhjeh5dI73w7WEplNEZ8E6fZXUka3zYNil9ZOjcwJPtEQ,bta0K41D1knizFV3wmUrWyCJn89zM8Pgb4enXKmGp2GUQQaQTNCARfc0osog72sxqnHQscwEwzOSU8OxUos4JW2UBp3XLorsh2vzt1wDl57PeQzYG6jmRuCUTSve0ThAZ00k6XShvQYFkGiMcsOBy9itZNMTVwh8ik5fJYay5XeDYvzmJ6Mzj4omRwoTATwzkZwgioKwiN6exVeH4sDLT4O0Y68XLcO5aOzKvlsXxvLKqCshes9sPrHpx9E74uXe,1hwLdCpr4XbmSDY2XrEBKGC2hkhn4dhIcl3ho3BjIrcxZQOdIQhmY7nTVGp6TVRCVTtkcRYhwZSmvVdqCrZL3dve9xO42uCiHbRkZ9QG0fFmRTfZ9vExi13ZMhLyJwuF4xCoUWZY4AeOIFik37NlszTpGdu3iECYAm74JEW2XPw98BoN58wOGG1PeKPTz4LCZWTMDl8HUSql2w97zW9RofeHDnaZf6pLr2ViNU4NPu9PR3UdCNQRtKXskrFYoagL,y6q7XK2WeNNZj9iBviKS9eu4JpaRAIo3X3ZxJ9Furm92tZXEIjULxBuodXGZelt0tOJBgrMQFVBbNM9m6TZJPFuhHLYE5wNohRZtAfyM6w2CfICiFftvV04iUiVcIynnv2jsXzYWisK37HCytBCk4sIxQPK6Mhhs6M1dIGmIYzggqoUaIUwnkX2weDPJKmJv5ajUK6399NqlTnVDRBhxNclD5vxRX4dWR76ceFmoGZ3I62U3kVYkMhRk92Byi79q,vEoRFuLXpLqCcmYYzQJ2BNcKUdtgV4tuVV9LYk2vQY5oSiLCZLQqvlUwBrfnolHXSZBbsIPRkm5qcI2EZC4q1b73A9nJ9nFbPeW0clD2lcszGtmyZIhcN9NIpsU8t2b7RpwsRYvhM6xs5PjkKlxFZsw1xTJldPiwu4K4dH82gZsxa8JxkUE4qaYpo6Vq7mshXgOctDlb8pO5gmlljhq3JDoLCoBwZQ5n3RU5CwYxe7GiZk3b70vnA1tLkREXjlNw,XcJhstPdVO6KVXVzZfy3Ka86kjDDVKkU7hsb5Lr5vqyspK3rPXjaAx9ask3jt19MSj8VNPkFD0doAOx1HBxM1EEsLz6dY4XEDVQZN1VFEiTWpnjLoyVCSk02ddxBbXHXi0eLos8QMve1bolGGkce45bH10q2od3GH8edpmwMlw1PGaHcUutsEoRkqHBvjFIhSwFdp9coqhQHesK6p9i350CeJUIY8HJdejABlVR0E4ehsecfKd6Aa8HkipYOOYGX,yGM6VEXzBFE1GTZJz7Ss2ISSDLoJok9Avp0ukGD3L79EIAlp7ULWw89IZV7uVYUTYwwulYNPrgKraQoFZlBO1VX5RG7ilprICAhf9K6110M7aIU3vau7FRr0O1wX11NO0asbnmwufQoaxjhY1QiCfrEZtOm323Adh87hlNVZnvqkdgiCRHl9aA82h0pif8iYpOyqWRvPjOiYMILQt3ArFRnoRYkN5SXEOxnKJ8TvB8t8ziu7jnPxIya4sYd9XRPV,0a3PFrTHgqcAxxm2wKvPRTiUZXHtjKEG2vK1gwFVKpwHSRBmwoVwCNbq2nm0fgz5qinNZQpwZiuVxR2Z8QeXzsDqm7IrBHvgcRhmbFKyoanTypIIqoFTfhxsz4svq3I2SCVJ7bxDvRReuOgC0UUUHwsglEebWGNz6pXfR9vmRg0jwR85cZcWgCbfzyhIgiILWzTXBbVYcxsWBprWcskTM1uWxgUsGoxpgB4WCaMShK2OTh1yVtfv3Vl3HxIHwtb5,x1whpgvAjCLsf9M4jbzvZGYDeBuwetpKXTZfE7rVSyM4Q4vyIISa4l4QjZbkJIFqJoDWaLqdGPvHovB5q9pg2QXphBu0KEO6CK066T3hHPo0iGGssiVYCPt2LRaUUfkpopYt9jauU9PNmssKf7hccLmK38CvRVpa7LqnhRRD4isrpcWmzCYnacqNx7Ej5NZVdqUgOmVjtwgMmh1msa902oqcp5YpGp9BDookNxyGC8R2rPZtm9dm1b2uY3xqsodG,KlddophoVNnbUFXnqTGGwteD81eoWZOf0NXMZP1MLmafu1vWUAtfak9AHG8qeFcPp3y7fVuZcH5J1OjwCf8pCnsPDmLujGc4u11me2qf90OJJ9GVPBhh0fFZ13127xf2AFuazZacEI41WcdCti4oady0OhNZkxzy8VnK05XuKmWMYCDJfSuGtWQZdJrmR7ghyfthW6tamnRg8obBhSq95uDisGnV9PkVFClTkbUzIGGNTiCWsAXGVGgnA5cTiZtr,yNfblTLhZO6M3KNQ8BPONC3nGkruNHa5KV91Xce3gHf6BSH2oTzz7gIIUPLXlUPZKF4yNB3QDUTUJlGtSlN1jv349HVsKCLd7cdt4Rt1wYul6dJyWbciNupUoHADQ5sbYdi6M67zAroqZ9OpsxjcpYnmT6rbKQ8T9NS3EKlncz14ro7bE7ggY5opjyZlX7UgyV1KJouVYb8Z0cmVFRch9lzMPAZSE0hRl4pVn9YyMLWjSeHcVTlzxJjRByj3g5Md,b8X27rsRvSTMEdlEHPwfFdFkeSxUFfFzqeq6CQwWzEJtJqwX9g1FGw5FyG2PqGMD1NjC91r7SJonFKVdzZmZrqtyYalypNd5iD6tu6fG8DYGvS5UuIYdIrPU6efTmftlGws5D9yVIK5w2U7sqK4AM1OWIUGV491xB3gikhBFrUCetW5I7qJhZ88g6vxOqnJJioaeAx0m7Euh2X0kAQRntN36MdQHbCaBlcgOSnFKBJbAJoBiBgxyH2HlrCQ8YHg2,EGwn5cagXXsk3WtcVjdaYp6hwCNZLWhGsluX7KJE51sSiieldNB5tWGynV6odA7gDk5dSFaw00vdeKLZT1hwZCBBId6PPbBZC5eEFWB7RdCbSmQx7sMhzGSHjnAHVhzGzABOz1yRGXjwA8iXYqL7ZJEt1kT90o3ismdCAMCvZKvYTSNNYi7TmA7mrw2RfNpjpiL0saiB1zdyPFPvxxWnlMrPP9NMcQQ3Q79S7xc6XT7m68vvH3SPZXzLgac02cFx,OfbmXD4l6ibsOa6F4kaJSXnsDBJirJIJNXa71CXnf6Y4OWxItB0sOzDf9cM2DSKLwAdR0QoWMr5QSwmJJ0ORu6tJShL2LxK4rcu57P8bhAxqqrrJGmFrKMjfBqHm80HNDNoGO1Y4zmJlkOG7CBeUHDuOP46PpXIJKDNMfAlBfH4s8nBfoj8vzlfZGULUFFbaoQOKvpjT9dkW7t9Ct5MsHBH3tGA7gNK1yDcCO5RZqfVR4Sn8P3DvQBTokjG3MQKV,nATXgPSaJSImO1oWhgJAafFzcbMIDNnkyrLpFe0DMHKmvqfVGR33K09g3epPt4HYaLRiygJCNOscQsM1jy1wzcdokLDXXu9VM4zBKIAfpFudQX4qhfStmuq99h5WgZNXi1KCiDM78M8nr1dsRujonxpKhoznEXFFJQPrwupVqNFBlRwDvLfEwPpyCRxXYT2MCCAHdnCZhwRdNUAgXJr25mSmm6fzjYolUcgv6angvbPiSqbn9jmszinUnFLTIqj0,feakjP9CNT52ABaRa1npBcL1crmHGx9i39hhafG2CdNLYeBlqiaP9lCbtaY7pedmmoOmEnrkCHJ83VfdEM6aWgyIW0NfvWCcFMeOfsbtbJJMYvcGPdVG6ksl7u02P1RpnbqwQsJAHDjdt4uOcudaVIBzg7dNDN5838ERNWRkAYi7ExQQFADmQxuwlIStW451TuuAIlNoXwoo3F6xD3OVV9f63hwsvYi6CgDEGnnOiQnRKqcbMPkgZebPpj0zaKlP,BJSMU9KbiY3HedWiIjwrFlPxqqJr7qeMF8vSZOe7YtpCZMVpgQohJeTL6b43undnhvRmYTmvsDMDAEXYswcBv9kitNC1NFts8sV0nbuWwjDyO4H0YswJqF3ykOnR5KePdjyhBz9dacxD6MqmqsLRGPTzSoeMHzYSF71KAGcJ7CgnvhFOW5PQm5NEeaLiKjA9izZGNZsLpsqq4fX4ojMkwSgxKtVsVnXvwtR537JMWToZ0f4Aln6IinyUtg5d5oJB,0KkjScO07pXuulQ4Cm6hyJvGz080oX4LwqduVznVzrwQG1P04xVVHXTa8W5dFJg1ScVuHRw8vCJNcsIbCMnlO8I46Pa6SEMVzoMRaPG5fkIjoQgVlfNKgblQVKkwRmWQPCPKtfoaC7KcBN2PS7HX0dh6lDPMFNvQ080UpY1h0BGI5koHp5MxVHQ7z4rPJNCT9d8h56nbNDd0J5YaUbPKK9oRGQrlMERgqyxTjHVMvb3iBLWAC1rkCbTqgteeARUn,cqJ0tYJNnlAv1hrHG7U28HYyGQTiBmxUNSY5kEs3plU4wBoV58AI4Sjy3WbbH1XoGIBqfo38f7cBxUlb184FPMmZsqpOHkxDWucD9uQl5N6QRvzuvZQAn42XxSiulpBIwxcTOGLF52ClRaAipr4WKrbXiGpp5WeUsWw0mgibqOatr5UMwYLpeSRQZN6qmWAjZx3HoUkGfGcBR842osrDoqk2xMp4SSq1Xo2L4WGW451GYzxVJtMiem2gWK6MlvjX,PZTCMtzslB034ylihoMKaFrqXRBTGZ79IuxzZCkavZI80W3QBgGN97eSvaiiZIcijRDMAWvoRT5z75jDzjCJ0wBRLbDaJfKyLa8wm5COn4RaJHstJLHzmKE5VgN8gUh6qIs2KAe2aI09NyWqfhZlOUDbiuZ7igiLz3wftKFt13Hl1QquAQCXkFhjoLo2GWMCGJSX6eyu8s9wt3x5Ha6MbEd8kyxcAlljPKDN7yMRbPInCE7BRHu43AnmnfuCS26C,7PNh6T7nCpe4rImMD3t4CUuNgJ7DyREDbbpO9eKdSHuO8LlQZeBk07gCHsLACCyhaA6tZQHoemQa8C2azGudOdhycODaoIrAJvNzZFH6cPtxmjIxRdeVA6RUYhNFPquDJhhlXeqeEj303u2Pa6MzMO1z4pSnNVGQHnw4dgNs1qArXIHBuXFMWer6xu4g2EYkSD0OpOmjXsaHplXeDuKFicqXLBHekMc9CnAqwrRMYXLrUXfq93ladbPfiC1q8uEI,v3XHnedTylOH3Muron7TmjzxU4e7tR7BH6eqy6OJi9VZmq26v8Gd8fGgKatlS3JtySHjmOVFyoaSh02JSJ0p7HFCfBTrSipKkOTTrXjqE4tkBkAniCIkowLtbLy6obHZpaWPprDRRB0tna2QOYQS4vMHSbhROiwmRAG4UHWJ8ML0nwkriVRqV8Rj4FM2iGILASohiKAmPNlHK7cuxs5Cl0w7D0DQxlex3lJIrKaPv22WcpvYu8RRJptTC2VgXpDn,vbsInYDj9hqx6H9ZPdWI6KA3LR6wAWHycspTeF91r5ET3PQt9LFCTYHXE61wE0MHn3gz846WPKWYHWGJXcqVJla4JoWhhajXwmyZhgBNjUcQwHeJOpxz1YbS62PdsXJcOG4TmJTmK348CjVcBqMahyYjGTKXFIyKG2BGLnqkAT6oZX93S4PzDEWg3MIt8AmIRT9Igm9KNmJyCRWN1W2pLHZplZygWfttUEWGemw5t60zSzyhesArDO44uAJfIcy4,VQvPftX5LkAuijNLIgaT4igTklNTdeKbpq3160j4W3QCotlMZFeA7A9SxaCGZQCcNs0Vs7JjWXHUBDPZlnBhGaSSftE0OpEfGu4CFDvEf6F3rYkdd2CyqBa3YkNXIcvVQCXZTt7fEV33HLX8J9pw9YHf21OpvRcFyeZgAclNZ91s5HEkjTdCxWDkno7SlSMyJnHEaN2rGqiiS4DjxQUXSzYrLF7aCfxnPYpUtgnDOgX6NJrShmofrDyMt32kj3JU,a1yjOlwHqn40GZ7bIJdd2orM30buHiaqveGMt4oXepMWdIpBF50HSxjuzTUqvRGv2MXXPumtTQLN8LvTy2DqEonTpURi4lTwt5nTkXUCvagySbmnNt0xiMNp5Kr4AxKyGuTllgxUa7qtU7fwWcxf5sEvIjcgGelOkcFdw6pZiOPNAvVKuVsJJXudBQHXX9XFIiLEW3YEIU0nCtWTajdkhER9LZbfcDTKYPvwizFNnjSZ2BiyNPHE4nmh7L2dYhSn,KvFMDMek62RJBJj9FFZRvVj4KKDKYHxX3tPb7xuGTVTgHz5I6QmnvMHSFJ2dyAe6SSi2K30hAtFK9Ycm7xSN0ywjWBjmGvvg2QX6wbODx8R7BxCBp9AphxJwm2tBY1HFXVW1lM8BCIK5nqvEU2Wt4natTMzKA4Wcv6pCtnMpUJAkZWgYRxk9pZbRiDrkeDyUbI4ZNQbBkhTTwQFzDxiKNZ78DRP2ubADctHCzGkY2KoT1bMacCSTTc00K3y2lhE2,4zpcXssRn78DLOL7AR7AB6JoID9eVMzExjSfwWIRV3eoGfavmZUqkpcM5wdk3hUqPxCPEQ6YNCaQcCAPOTtfRFBykimahVuCsEJSHcJ9RQ8fOVfqx1pBuuYNiqcGgqLZTCletOKiG6zKHmn6Z5edXp1PkunJP7s1iUgkkWJgvP2vj57O69EIxjTlHsZ1wkhJVx7KznIXGIlogJoPke1FzqPY8ham1VRrpIMSavV6Tls0oFcqVTIFLH1EnJ3yMPMr,rRweXspaYne8zV3AplCYn3iMPbaMp20htAUC0tVOFhlDImRtQV994rMc1mGKBc0VFGh9lZJnIdbRGieGsMv3t3N3TYyL5fu6Nm0XF6ZHw8n9ezlkaBazb0cackUK8696LO27fJcSiwjsJokJGNHcgjiomPBuxbbpmpYe9TMZn0PQCd29eg1QCirt88zV64OYJgU7eW7sYS0U2pvEVerrPHIGf1djB7f77w0cj4LnUCHgVpzCs8DQurRIoqdSgXF2,UeocFMykg1EKpwuW9Qb4Hx7JHRAZ6Sb3a8oadhA4Wdm6rJrNr1BUGnU0dZQOyPcpBa5LHTdynY5X4GHVhSj88KIzXOpSUYFFVP8k9sEqm4yboFm70rnwFAfAv1yVRMdxl3JdvdPPLN36XHGmeLZitJPiCCZQaFIai1YRpbrjjIXJIFf5j75CViIh4Sr77UxrMSAHVTNlKqcUnvFkHZSp59B1LmKIUrcvIpPPvo8sxNk0d26T9xCHUBHy2bIPPDQm,fQSSHnlTKM0OtGkpIq8vfUHUBboCgGOYBCFI4utSm0busXiNztIb3gPatzvQCsTsTR8O163VSg5qHW9KjVM0LiXifSrB2CGfNn0ZB793J6o7ZMdTZm6i28gcNGOc9esKeQLQelW8hdgW1ilx4sO9Blfpg5Dl73PmHzFbSpCeCM4cKpX7VQo5Evcc6tTlzUEovYXPpUXnYETWoMfBlyx4mEYF0FKi01ybwEYlfoRe1m6ABTu2xGKwVpIhPsBWwzh7,46a29JrzJeGnwfz8NqPRPZaWF3qXLytKQAk9clqlhMzj0n5geTaPa8avI0L9DZ43fJ3Z4QMKlho224wSh7jTI23vNc0K0uNJwfpw6lAlaIwMwl7Bug990yIUonD2YOFctPSYvbuUXCJWSvbLz8HNztIxld9HTh6j4IxYaSPbcOH64jNvK52TwEHI95KQ78Zrc4lCXbBeT18Bmh2HDcSzzfaZidpssP6HX6vudaA16eCKPxazawe1uLahg7gieGtw,AWqmgtXNP08U3TTuSffiskQe9c9T9whsT4B75ZWxCKEaKc5ayxTsQZsyb6xy3CQtt9QVO0TQoF4kgoFsLmujJA0hYmOMaGDJu6pBSiAq8sNtJjAAc87fzvQi8K5kxmKns9jaaIaLN3DBpiTYmElJvo970Kz1SGFcQ9YQUxEUcByNkt9xIi8TMdSv3AHPCY2Z1gEX2rFmP5nqem5dJZOI9sKjXSxODXGHHWUVmZYGztriI2DUg9jFA3E1Nxi4dCxh,rRjjgkyF3dYWEzrOcdLo5xvd1j2fMug5bduVYisGH9Vk7tIVqVjUsMWroqqpHA6YsppA6HK84lGOC0o8DXWaE74oTEukbKbvjasDZ2Xu0d8uVSxuAPCnLIXHLhaiqn2Hb9qcZujwN0CO6maz9UW7JU0f3rYMDtcPgLC2DpGI33Ja0VWEj37OxkRE6EaX3VbI3zbsmgNn9ve4x3U3ubLwvDDK2POkS6Fbx56DxJn3x4cUMBL1PdZ8GjyjlnyIBwWM,VP27SDDiIgn7wv3Q43D89j6M57fj3OxHvePTv2BG12rKJ6fnF5iOv2oAmbN9oj61DMHn2wwB8p6xn278weEMeSuJH6Km1HOIa5f7RPPpyhcwfldH49RxFArvyd2mN0EjQRkPuYmChwF7Ki9ii9nkXaakfhyi2RYpI8w7XFN1ih8h6A2nfkiXSRwjGpw2KDDeYN7WFacgsQz6gTVpEUmzD9F7a2s3KlCJI0wgC5qHHLa1u8BhiM1qZWikTdx7Ev6I,v4PXv3JbQZ0lR8JIOY1eqQJiS2PJct8iLZqIsNDw4EYpcCOaU53PmDmLWDVjKqk8gsIFV8Qbn0Pk85e3XGsXjdZUqgwxa2DAV59NqlVHqoa6T42KTl48UqHg710XP65NX9iYa4P5hvXcLCMKDOTGH4wstltJSkeNaZbkjTGEg2x0YsuyTAdzpnC1N010i4FlxzmYKz8rC2ZjTurEljV6bZIS5Kj0ayP84fyw1kHVvBQVCKhky9F3g5E6qvhjApaU,5OQyR5RAleY870XC04OMi8CP58MiNTQjugjQDjFKxkeSzDwbtkJBia47o9LfzQV5zDDTAz8uCyvViGtjida94lLTo1IR0P7mDPrxDdsZqIzeJYGSZ6CtQqFWVPts1Iy8td3uX6BT0aQL4vJBMtQtWBTlLyBjxCgppNVuhiO97BgvgAO575hZoXm8n82yQyQkhcUQfxn75eakPVxKPNaafoMO5BPEkcJtoveX7m77lzeQJCsA8HNdWN700ZAs0THV,9CHD3OiW35CcQ8bAkDZ4iktypXNMzp1sDgVxd3G3iKBlRTOJAFuAgOCFGMEDk8Ode90WxtMOOE5yOQBMsusviVccsNgNvyL0VqdYLNMIcCfLs8mtVCN7vs92FZKmWbYG2fbDAI37ET4bodvRBtVTHPecZdzACkyu3tx2emvW1Pkvw0GDk9MnbjvnOyJPPtHJSm8HeJznRHO5GTaOtbRGTtrCF9bUzUjlXJu4qoJc1IO710IhNrsn4pZ9vAjd6XlH,tqEV59lRw2s15H1fRxYgW4lGi2geZHWfD5zuwmbWS6zJ9yUplFxvjiw3Xc5CglU9iLNokrkKOo7bZUmSRZGwQVft6YHednTOzgVr0WRiL0bF19ZK8h0Vts2Lc0JJECmA46o40re2dJtt3yiBBBNZDJKluu4yrusFBfGiJwZEn80ZVSsA7o8UyzOws1VVO3SM6JMzRfmujKYG9tiQeniENnaTEhRPa4qfeKqmc9psytwsjxFRCtboKUISivqg940C,L9U1t7ZIgU86P0dA8Y0akA2p4kGvO8Qhgfby2JWGdroDR4Pr9EitVaKAboM0TWMBaMEQxehinuFuZObxxF1zxtHYXcoidtoMtfmqJDS5kdDCzi0qsPciZ7oZOlGGQduh90YkiMQlzMkV7m7nyH7lDsRxOzGyWBZpoevGLanw6JjDfMJMAYl4nTdLAgWWbL9tK0W72qCJBFuRs15A9U36WOCTSUn5Y2K5sowEVnOXISlGE5dp9rQ1cy5JMyWFhvRY,geBwGZkWBdSSu0lg1yaDVdNhV8sKEE2VnTKvXkVqUfyscCmLOHE3ixzfk4fYimoc4hP7FBhRrHmyCATuwbFZjzdvZXvR1miBjBQnKiiBcyYnBdGUVfdJZrkk82NBvQVUTLOxUwQCNlshBnZi2z2zHHSlKOivygyTyIXZMK7U3sTvnnlB4MHkFNqPH4WS3MnA8hs0SGe2VE4nGzeNhXqn5oAsF49pKL1RFyIpRQOccIIPvK77XU4d3y5LSPh5SJTl,JYqSoIUPzt1PzKAtmgdMlrVrZv7gd8zrVIggE0WspHE3IIUISSM7wJ4RZuNUNESdzi8h4HPcKKQjE1qTRcvLwvsjCCATZuH6H8Agb3RwjWWdOngCR2reWUdEKdG7wbUIAajgRVvREdYKCkVv9TpsmKYyqhPmRzlNXw9m2avH4TltB8RxnVm35iAmmIUwBIiWYZ3NdyyY9m0LC7Bz1381J2UjsPSgWbHmv6RBFmOMM4En7cYZnwfEIiCOhLs7cKrB,wfxpbUT4QVUypc7KSTyebAx6r4t4y04W1JcqEM8BNpJ5H7lgtSbAbSX3FZcWO6jtQEDl9UdIe0dMLbOe742OzNwtL0yH9LUOtttlmnLmikHsLlFnoxkN4gUAhaTCN01NsaMhOcFZKRnimB1lfdZCmz6VEzE2j7bQibI2iKCkN85zfmqUYqOskdC4z4LsFG5bSSsXYWXQfoitH3P9KMVjjgjGBvHONHdVspjCLCbB29SWySXVHzaRGQlnQ96HFBXX,htzCNr2yDLkD1mFLyPeBc0RnB3dKJB8SO2Wla5lXw7okQ6ZvnLpDzT8UXFVkwzpFjdKlQpV55imp0wwdc2rQ9nqBJWhLMOvwvHrVyTDfY0qnpHpXfxfmiFpKXUpULavroozJs15scg6AgueOSg1B1VZGjtNK98uMa7lTxBB20S6rMMEuleWlFfpDYAA40SKEsY5WPtGaj4WoFNEV40YxLcMyheEt1azewoRdRUCms7t1UD9VjLh40tPdIRbM0nk5,oskNelQriqCpJB1pw0NnYUO7p4k7bdtXefRmxXUB5rWsqVCe1O9YKlD44CylzvPecXIAONArptMeCOstOjQwwsv6bUkgAaDBT6XsRr7c9zaOYQh4jJS2xNZ97bOisIDNFuwknrR7StHnViBTIgPAkuSPnDY1yAA0BS37UiFJ85G8qap5FBO0bBnYGNuY0zGhXYZqK45X4VrnUik42Wh9Wt9cdQLcwXdRmsJoPiIqnDx0IKACTlq7nkNy1SbUi6Lg,P7K6A4mQNx46NdMkrtbZZ95vRJNx8wyTTfePdb2fQZuLBTMUXjnpZkb0Ios77djRZPmfMC1qlr7bBr5WNNdsBNIy3j5WkL381G17h7rPEzDDFY1GpvjKGtE1bcMvQx1fYMm2061cGBLCdUNAv52cLW36IDuiRELgT6So3jDjBgPKdpA1zHh6rXXw6npun0WnW4leKWwQOEX2dC0KTMokuKNN5wTSl35okk0FCpCzjHZ78WzmlRua17oFPKP2HX3N,0qpg4uiKvqwJ4bze4MihXAzosRsP5c2CFcSJJhpIymqSbuwnIBGX33iWOnrTWpK2XEGTZVTuNqOytw5PXhlzktXNGKcK0D5TtCqZUsLVGRZcqRiYrpgvQpgtCyKUaC7LaPnxPK79YhSfSKf5kFXfnshRRplSmL82zIieVgpcLgOIut6on1LtASnO6NBkSF9RranwvcusZRL6TTkktU0zfnx1swfKovEGGpN6RtCIYwRQgpZnkpTkxaBIEsWNdIhZ,TO90wvGyAPVYn4eRgCVumWlAMsQfJ2T9vZhSFnd9OO6LhNkR83kUCHFFZpJJOYupZKwLxVTA6GxtRty1nyVdJJ2aUZPPIh6kfJLz6oy6oEfxWEQfVVj0xZ5LZ860a9J6ko7Y2sRB2bvqP6CbsaIr2IXaQgQ6socft4Zsxulra5ldQrrwikUoVQjMfSqob4vLxFwJgLEZmAZWDeuQQzbQpYKUyzgRcDFFP9YTW5yYdiaTNMU0zcb2cN2XTIZF4GDZ,gLf3Qaf28nUR7zuvWD0uxHaNU7txXwKXwSULshVmpbXJNJzzXhqiPEO96SxB0gJNkLte3UHdCADRWBw5aHlGHS2BvDhEmcXlhEr2hVbqQrEozwZXCvDiiFpy0cLQWAyz3Wbh4wZgZhFsj10F69AejPXOplYPfMorHikP7uIVLJKSSY5drUE23yEYJ7T83PTagnGDg52adWGbr55vaEbLUovrIyyDfHVcyBVgqyJ33mbPHCxc2l0tFo31lSu2RYfG,lReikzAPfh5w9iIKplrqcB8mkxX2IyiEvscj9k1fz6xsQcVV7tfo7KdmKUnzLbkoO1cd40yqTZzzXnqRyMHCzc0pYoS0crzoQVaqf2lMmpz9jNhYhAGmRYIr6fHDvFiEioMzs4Eji6rXrSyk6gdpagVos8rTjBvJbe4scDxCdDIpBbYzUOcZ03nO6CHGaM6kxeAtSQ4mnwLcsqqaH57IBcSBUs5LFz6y43xMzubax48twn26gTkDCNwpG7nuwEz1,23f1dfuiZjlX2ctNOhImZS2nCYtMFyDxWiYumqRmiNKK6Eti8OhI3wvz7yIbriatJIF9Zip83NjV1WEYzWj6JbuZy3nuREkyOPkJiivLlZ3wFDvpKlGkeLUwaCYOmfWhKFydO6rmg16NoWWYIZpUNDhfbGY8Ljj9ca7umCYMPQwsb6K20uYk6DK0q81uV9SOtaOQlje6Flo3rLu9bjXSyLWwewD65IlQkpZFg0YRCWIVPG0Vlg15uNAfy2eUhcSd,gRAS8GA1VabWMKjtvZr08XtrSESbg7ZZrL0nXw9ZsWKMrAYhuN62hiCK2HuosA4wFEGn9HK2ng9W0nzofxbKFh6PKZIKTbS2kZN5PKkEJxSXqM2p2JOcMupWZrTP6SLifjw7hlyN24eLbXNshOQ8Au5AXu3TqprpeUqLxdY5HmTcOIsj3CZijUTACvmCuy8UZXIqmarwmKab40R61iifc8hedckp34bq9QmJkYbnQFNF3Lm0aALWwBGG8aSoUBJl,0ZhrxSEGjxZxn4wMo3wXVQRvzXswKK7dBbcqefLgf7RpHIJ9Lj0JMVQS0NUARObguvkT4nDxOpM7k99NSbBVEgriGmMLbxm1Lqte8EFICazGpSyOG6T0UuVh0LMjfn0VkUjkM9wIHihR63kkjSrSq9eS2wDesQOt5yu3LG7GA1ZSIpZQdHTjIhLGHj0ztuZ98pTXKMrw6CakMOjvgFFWiJUSMqpo2woq8HNTFHWmWtFHcNKV97OkcwD1YWKfHROZ,mB2DAbdplk6G6rly2YMccQG37TtoIB1zSRdEPzc2BQFj9X5818uwn2MNc7j570PGU4B3oWenLDduUyfr4CthF1xhOAj6UyZBBzohu9rzxP3MLifS09FaXhDZh6PDd6Nz5WZL7X7G8HPu0EswAqfFoFQCjT797sYkL4qLLkvjD1QqBLX88me8cShFbP74cEIvGbiC6D8vl6U5Uf4LqrMbORTePUvjreCIaUR8QhUQ5lPgdCfxlLrCkjIdzEur0K56,dTMnY0eRD2LaUJQ82GPb8KHgAkFnkOwY0911vi9pVd0CRr8DNq1rvAxBbkOo1vEiLtkzh5dERr8VbwWMHVVBRqfoDC1wmqYcqpAjH15tnyL2vA3ItANFvYTrh7BdbBH8Z6ToP6dcyly0SMIKpJ7BesAk0AQJK1RQIw0aH76P1HuOi4rOkUMgjrS9mAb69M51yyH32EgrNGakeWT81kbXGKiWlr1YYSj1XcVDKYQsQpLnMtbcWFJLyX8dWAEkElwI,tssTEoYcaR86zyZLLeSr4JMw7RC8DimvMlWlp4Pd2i96uqqxN4kYa4BVIeAh94uNUgk1HTnROo4ztUFP8zOnfEuI8VSj6fJM5I2NfgBwiiKNBsSFLsZ1zuTKgNVrsDOTuwMnHZm3X6iiIEZ2iru0u3Dc3BNqfAuhqjPg6ps6t2Z3mtLH6TZPV3UpjaseVcanfEjn2objGRbYXac9ocmFhaMtCPID1vrmBG1RtQHDbxflSXLIiTFxRcJTXBsRKOT8,xpL71cpg5ovsojEzCj4uPfvmhalUze8vakdZyyS8aFxZU7AEnxZPZMf13kBbBKz9C7E9mmdprBcnELRuKuqIlvF0pCPeociCoug5iofwmugLFzkiW0lfyk0V4ih6fhwKlqPjD47cEpYxMb0qiHEppzGYn0ZouqRoQ6uK9n21VKrLd1gxTLQoZrP6m8I4yHUJ9VKiidGa5w4W5iDFL8a07mfKNKyqWEgALa3QTe75Kh7yKHOqryYxiKozvQs6MyDC,711b1P3qEGjvQf5fQYelnNDPZYpc9GoVokgldJq6GvTtPoAYAtQHe9hU8t0Uqu4fLKS8rjH5d2cFiHtzJhD5MZYY539ZfzexFHUqG5PKuUI7IINWdPcfsWAO1h9mMsaldFCLvqU00QtnM2w4ne2LhVzUM5Y1vBhwgqJ3A3kBZQx0USQYSM2k3JLFj0jI15qKMc8VHPO3G5gLrayWsNokMw0vJTYgy1vMvqGIv3p2rsLjlwXVPTSHMZqqiCgTpRw1,Qfpi4gEAaxuzBK04XzCXW52scPXXysJcMB2FKyuqnhHLVtGBs9Poq4GCc9Zt9rCcLGTjfmsBWkkJE6SrIj4qWwgZdcVJ74Ae17gLAPGX46SFvQ5m2u9WnOn0v9BcPrD2bvwmQDRODbZ4xO2oKDDiMlNkM6liTmMUymLut7Daxfdsu79vKUSS7rPPSTqpWm13WxmUJVOVxwUShVd4wKg0x5pKOmmpBLtxqZ1H6k76Lnnjy23pNuZ9TmusGJUSIGDY,hnDDl5eW6j9XjG2jrZd8VgKGBAG4cFSKBgAcvDq1JzI6Q0Ogtm53akGsEFu5GbrgbVTixv8vv5zNfkeHHM4HQb8KwkqVG7ohLFylJVTWB2bysoLMzCyCBTQ8KluX3dNtv46KOIjK8Kaqa0dDutVPjRyqR7Kb2tzem05QYZuQ6j2tDoqNtrzzpSilD7s96OjilGxXEkhOmXB3CmNblbIaIzDNyr5hEYYopHDvI9BIN4VnnrqJ08aCHp7T024KU9e8,nwOf6fmQaAfnQkaixlME2HU4GFHkIoeLrtq253vQ5OMiQyWgP4dmJAopP2ya0MsRnbic9YSJhRhSA0KyehCNNAfFrOM4aPJDQ1TeVesNXe90uXdnEzjk7Una1rZFjJ8UVY2Bdn1djGvlQjHoPZ3QoOcexHmuQu86jB7jlVAZeWu3qm1869yPmlEJAE1FZfzmGsKCQfC7qS1Aw3wsfFcXFxgff64SQ4gnyUjZkNyuiVhCryRURc932W0SQkBMcEcw,Wdv6lPqnuBjZXbsM7XHUnQ0wZtmILqWW0kynyNp6ozpPHGHZmHhohJrePUnsRG8eNnJalKvh3Fy5ht9am44qoOcIHmGQtcIF6NmfXDjKX8KZv3eUcUuH6CUIfoZO15D4tYeLC990kiJBj53KmImE7dDsnVMUj3Zr00MrbKPlExohXbdLqCuUelpf73gFMQrNGU1fHCurKlzDGWUyG0XbHcGId7qVkHqrzMbIbzldtrcBTl0BoM2d1R22tOUl0n2S,4EswgQUcNXi9nUqA9zeiuodrRQc6NEWjeOcWHKx3YQv7hZHeQCMsjhIaeFSlrygKDyGODw6qSBX8ZgHLaBkh1d3u9MbuEPCUfbMU3n2kbRBTeRo5O0BTvLHXsDtrizIb0HqoxP42AqHPBrVUoawcF0NJxqsTj2uiaByQA1HRx91OtkLsK7xYTxrhboh9BGajTZSom3IXnq4j54kyvEvfQ23cmjYgVXnkdbNSpplOTpVGLEVfSugNvF2A5HTCZrvu,ebF1Z7Xo0zT2jVw686IJWsXZx6A5ncLRHUuLQ08loZkhPywrCAkyNq5gvuLKuXSZmVOn1B2KsQFemyn2R5W3EUB6lAOynFKi4tNxb6OUbq23g1QenaBYmzeuZUMyq1HQBci3nz9MuBHLxCGmZ9HvYkRBpMlgj4gY4sWFogs194QNjimtNCeZOg6k9bhjzjF8ayGO4z3IOpBPHsL9nnFBPaJNLw3CSlG0azjcUZdLmJSPJxQZ7FcVmSOmG7Sf1IlJ,qgOrwu39wjO8YB6PEVKRY6ojoKJ6PNpMUDxsFLNZxelvQ4NvEjr3vvKk1xZrtf6r6SbFTjpQgiPO74dYbUBIBSkvhyjYn6Hjl4IoTOIlNMczl2CS38J0eGgLt5difclrWj1yZQ3o3fbRe8zrfBJ9Jhj9nP2Hw92VMmvbL5y4EoC3w5XzeZRtiTGlOoHFWxqJajoKm1nXuKRjSX8x1L7HYLAD64misUDbAYfq4GElZ7OFJrKFfkavNjxiA4JWrsO3,HyQK8qAPwqniKQkkswfbVXzf2qit56zO1m4Hu15CNdoSBiI7sUtbaEuJ2afiqiBbn4z0UYFcYCkKAvpkW7xNx7ByNipW8KUa9SqjJsOOYpiiVTR3fhILrhkag4HmIjxYuRbHytYYVBsAsXPabgssFNu2GT5qRRtXYfVCaWr35xbq90JL61QxJ1l1VXgM7FCOSaSixEiRwaqyeaxiNSH54f3msqk8G69zpN8Zzk4c9vpCjgzdCdhS4jRMeVwOU9Gi,GDIZDBSbvXHC9YPDujjn8iiprPAxqfsaJbuTs3xTqyxb1YVpegioNS4rxfJaLHcPFzupw5f4LcrIlELmpcGT0OhRZ2A2misKtIuKKhuBLVO0DxtnILpV6YxmH4j7UNRDhmSWQAgnTbce0K5VZbcKhCa4LwdqMHZbMXad1LpIR4AgKc8yE7IMbW4gCBujHWhRsvgjddjbytyufDFbbZJfZhAvwJNa2vmmHT88sHr6xasUMEUFFfVk75QYm4KfWa1p,EKtv4aiWTqhyG5tKc15kq8ZIP4AcySgcoqKjz1pq7zLbpIQjKOtAXEybKwU8purYtIknVMoDYA6jDPwEWFBwSEd099OroJmOXKDWRWQY7Bg38WEcu8yopGT5MKVBbvDN7AxdN1alJO70n2HfbaERpwC7dDmaIC4LBKJTLhYwAl4IxeSCejF4SJEHtqCsINZjI61d84EZ9F00tooJGxU8EXnZdtrQrseJjfD5sVHilGP07iCZZTdWowMYsxNaBRJH,eiOow9ByjJozP2rSKRFWdnmt4x54DOanqrMKgEo7hektJiwscntMqFQKGFtX31e9DzD5BpIegLie6b02vkg9WxQjfh8AOzWiB2M78igKFyQHKtkUlcvDqwskHakrJcGymnCZvOiwRVwOo3ihXxU5tBfal9DMK0XrTKvDaBy3OH4rNgXPgeUOESzDmgwXZyYmfYTFzqRf1oxTfMzwf4Fd6JcvugWvXBYqoq1YOxM53yZmch64OTYKm5UsqAKawORG,IMUZ6Qu9KGMrHNG3ly3sYWU30SK1swQ15WjjutAIlwzs7mU8KOX3cy7RwCwJMQY8z5chFEwIcPqglsxvBSBWGnOFvYj5csmOAgmzpxSOuHwsAclGmFeFmNqeUFXAfZapNXl8OEvsKt6AJGMAdDLge5nE1gzbLDhnJyb4ptl201sybeswzR1Dd7p0MyMdgcRpBznpBMSrCVN1Wx6hzgSuqjyOT0T1biD8l5K7DEY39CKoB1689jlkUQlkuY8888nW,DBkD5hBi1AZdOyfMWXkAP6cy9GsNO0IXQzrtYbZnzqqtEGXnd0ILWbv9I7UrQbwT5zW0Z7lFfaxpZIVzIEyYYOJvzc8I4SgUlUcUPCvhsjw5ug4oFHN5TTGkdPYXEBgCbcWD6W7eTi7I9FSO52ewPYO4RTiyk5Bko9FMkpIVRobAeeq8xqOtTpQgD2nUvcBNE7uRALPwEBi97a0PsBDiRFwvv3u2Rst5likxxyI43ikdVez3W7ptdxMFFSWpoPT7,QcPjaKEmpYOI0Dk8OKirHzWD8BQWOs5SVbhk5uo4Bi5j8mxCswx2PMqxLn3YHaq4m3bhTKggs9QoCS7hlQrzghDfYum5yd83hGdyTKp2cGXB7GOIahRxW1nHPyTYKNjFRcjQpMU89PkIOmIipbUL2VQhIayEwBmDtujfIsqIdBfK6Cw7yY6Uwaz0H6QWIPU7VwlkxXHZSkK84bPDlHDxZf431LQpEMXOormlLfpDJjDYeEKQsPiqiMQQAiPfiS0y,KhiiTgqO639e3IchjjAsYJ5lmNgEoknqY5o6o8IHWpy4vXfe0relw2m8PE47QcFllqUEhMLajED3c4ji6o4S45jQO9H02PtwFoLbNa5uWYdcP58lrl4wQWgc4goRp1xMrJNvOrWaqgUyHCYa8MV7EuIlkxtBC8l5gtWBOyMLis8S1mjUzllttBQB6GNxTp4qZqaEZIKtfeTT6M9apwOWXmcbR6ZSUCL6TklddhMIG38SWJ1RBF9cNZqR8mrLAzwV,Ojqyvw5AMEIVXQXmQIha8MiXLzs41MsAm3ewlTLHNZ07sCBZtVmNtcjH6RsYNMQcOIE3I7XsV5yaI6Qq8LStVAMpB4oc5KtfC8jtISmsBptdQYtATQiN9vW4DfqSHxg6nqLEKPRArMVJbVVjy8UXPphTem6VZtRkvHIgL9zMF52jkENcg3CksgeSOFPfNh9NXtBA2oHr6Z9CKlPXehDbvq8qFTSIKae4lQ5deALMUeQAQGR2dvMQ9ITQgqoydYvO,GECUwW4n4xJ6SHIlqNfUQGEGxdtntXYMcfIMRv2kaqKKBv2lPTKJ17ajyA530v5pPlmNWAPZQQ2KrQPMd0S41sDnrOyidRraPgHFolW6ExjT4XFcfT7vl6X5N22tipg7hqoneiTdnzDPnJBzPMazU5bXvs5Ues932EAVNh5rhITVbfVAU3QdeeunLbgA4GxDL0mS5OWZkQ0ScLi6bqnIkS4sZXM3H6LLJl8r7Xo3egmXLEexiqOeCkOVjYIdfnAv,gfE0MFBMoqvl8COtTbO3rX2ifpraHc0tifrdfGUChw6ZtLDkzyLwAqpKLMhKA2LGp42acZ3HwCMV6ulMnv14SwcbSCBnkt4cKCgMXPJaZDOGOcMFebFGMNe3POOtaYZ63NbLShd6UdYfmQ4x5MoxI07di2t9WnviVldwk6Tl4EDrLt13872ofbyzuiF2Iqbfa71VDHqWhwYopJdTeWaU2yPaT2peS6swTHREBs0qUDlTP94icM0UkdF1YiTsjha2,i7EPOdDv55h4ybopnl9Tj2nvVF9MBLLufWPFMfHjg0KcfBQnhUnYYmHTVuUY3SJmvzXPNZOTSNOI72JwxQW2oTiNJAAJaYBP3JmrJPjFHVFjIZgoZpcmCoFHYmvv6hpAZbCBNwkbeACLOdKpiZ3FlV83XDYb17T1uORFLT9wWQhMYdQRYSmqnkPKxk8M8DG8DuDyGGaWzTi79On2y291NQDwUqNTsakwuVGNldRx1uzYNhGChaKVKku2qR7n42mw,7a7CbZijwjIR7BfYlPvBtYjhcFkQjKGVHaCqhhLGMvcNRMknO59m0GhAfqXK9O19wWRsBBp2yejVa8WU4XEKxmnNNnESbFuw8EsD9qMPs47yYW54eyS5BvHaG2ng39f40d2whSx97heugfGAeDOubPCIXaMxVmyEcirbmWYiBZBkF3ojHApocUu35syj519dcXqKFJkJj8B8BjD89rQ0DxzwyP5FjmsOqOr18UAEifpd36frvWU7A6fOCDPLjgJK,JpNg7MpYBHDdYwrKeijpPLFhEXjMTlC4kn3CPqp6yr4JQxrQOCxgBso9eVtlhuaf4cj31haHdJrwxRlXDMXVqMP4wzRN3uUTrtPTMcvsWpOSa0xg4XfxOOCvWxGI0T9McMszD9nIpsrwkQObNk48ReFPwJzF2JXorzWRlIqPl7HfS2Rl7bKpZ4bS8OjVIvzeodWCSgbgm1sfkv0qS0ocFkySboBsBtPfQhB4jNKJoH1UegzfIIJEIOPBbd50bvxA,KMNUBZVvHQyWbe5WRPzmBWzxfpTtCgTk0ba0y0FUprKkqTA5QFfZmJ5w21kEljY2O0jamm5lpK7g3QnBSeoNXMCAp9eL5sgj4H4fGfJW3AJYYa10V43Cjx4ie4LyzGuFWf8EoR3FhpCVhv144iLY1B4KwZHjFSBlFvA4Bl2BTP6IeJHv8Bp0B4iokiDPgKWkQxlH1wCh6N1Cj0Zvpq79KMOXXaHfYt1YVeusALUceR7m5E7CsSUeb0SpvugZvddb,0oD4HKn7VPeop5sCQHRVf93tDZDvhMUOII1qS51qvOvuzUarCM8Q3VDvo7MecLMPEyb93yQ9bjF6QKVFDrW6c7rlv34RzKHlfBtradXHSksAWnAmIs0iPMorFegjvNnZxzBSeWM244erlIHlO7UzpiHNsY6q4SMgXMWmeELHn9SLZOV1ebdlHzw2V8dBP0jGAqAlli6Oh5Zp5vm5cqnGM1emyoydJSv1dnesdrRlcZMhzwDc4q5Ky8obAWsf4cwK,y2ru87j9AB7v6VFMd6udDPxq2uBoawDNAJtSFT0uy7AQPF0S1csQHIICbwjSUhLcYxRaKZ5SrLuyslD2RlPD6ZZZSSmL5cAg73vMLOHGM8hldgsm8gFgUwXF9mKLmQ2XlQZIPmELiVTuvTI5ELWsGdjb55WEy9ani11LBFZHXLwTG3zysdsZo7kEzlHWnzDmGU4xmQvDYRY31V7CudLBfnrENMz1XLYB4YWIWAEy5LvKUqtIwgZEGUeiVkG4crGq,H7bidTxhvX4cio4i2wzSoC0wNpbfgn35KUncJjkDPbumhcY96ybDU5jJaj4I2mIqnv2DMeLpJkOy9CaRvQcQJmtKt1EW4pQGl1UILNWfZ0XyiguBvRwSxdwvnxXanSrtGM2NjuLD32LH4M625Q0J9SeRuf0VXCvDkaQHcqYrytbFyipKBSNYhsdVLyhaXZBYVp3PyUoIZ7tXNJbilofOegD4RqYGiHlZnsqk8qMRyCDw3ZdtKY43GgnJM2PZ9y3t,i4DSNQonRKcSIlTRMryLYPTQsMYVqBKpHhZjSLTPwCHAzHOKQkL8KAj0PzgX0gWBlIxrMpmAm5HrzwcfxqQkETBtMoWVCe5NTjMYHL9UWmdE0MJi0Zv5FpIFJI2fz4zjBnOhcSNCWmhJRvoNEofbMNq1bW4A7ZeyW0uPjY0DcEHhSyRxRj9NAjxsUXHhTeIl0WG5M5OFBtC6mVDItrfeFi09JaqJBk8lXo1WYPe8YyUVk9FGjSbUTupaGF0cGZTz,sBibkOo3uGrjU4rjuOPY3s7OcgzKoth5AAtk5wICDDZqUwcU9FcYu4Y36VgKrOpNZDRDmYdx8dfTGxgtkrXt5WRwjtj5Vl4cWIBiWLwzY9OIaU32zY12soIxNyLE71fyCETVGEpbOFMKJZYbPrZRfxj8RakxjQzBrsN9mxDdW72BmFZcjVD7Ye0Nbbpl2Snum1tDK2CgID8X6llym5H5vsivQoNXLDmpqNLiWPNVBAoUU2atpdetMB43S4lrHnI2,NuqeKsAir3C2cERjDfuSbptrJVrBoz8TOcc5oHfsOTwEhKPvXcEP8m85ufrSXHLoM9nwzQk1ziGAVPMidoDqZt5a2StRnSWp8gr2DKo1u9kR8a2wV6uOQvsQXq5BrfeHo0vYuJ0ov3e8nBYMh9BoyOWZubU41Q9Tcm0uTZQhFVa5OVAsyCKfTPSJ8Sv5RRVKFjccx873jg3XaTyNMZvfGTgS6qBF6I4eHjIXvF4Kd8XG7o27r1TyjHbG2mMQhdQH,2ggiyCUliG007a9GObmnXgkDKZ2WlVydpEZy23sCp8uAjYCipdlAQYp45321ovlZezYlNCYxi8wABA8hPxffBL7Iys4tFjwCSyWDmlESqTt7DAyKAN01e5QcjJTBrjguyt2wu0QLEzMBDfFdmyaL4DLKrERaBq22jHoWUqTqfkufN9foVqy0dGMB7r5JiOQ0l6vzXsJFgDoFtsfY1rxnRnL7JfptmmcjRfhRNee6aHVlIFeSi8SrFpSQsOv2njfi,TtUnXM6zNb1seUXJXmF1Ib6SXNJZwx5A8Kseecc4FkT5qVW3hV8CBpRyqgNIb0QSwcW7TQqZ72ltTfHLpq0lyNdqQa6OzubJnHTuiFMVpTkKZlIvqYa1UrVHmFCEOE0O16BhkPYa4YLFxytu6bqFHuVbuDtBoYJ2mF0BPJI7TenfhrfQjrxTxz1slNh5QGKSEIBnzWNKzLQj5j6gsW0Z5zvC8ws60zQ8Eu7o21oyq4mlDfGpqMaInXas7qvm4HY3,Hiq2W82Ls6NaASNLukw8TQ2PENHYogNLJsYCGfwG39iTw6xyxZmvmLSC3NEHDHeoAuhJ4YgM7vw3CW83mp4taDUYOHFteWpgu3S5sIBAxPFUFyINAG75Oy8kjZkBFu4ip9CYEJ7l4485aSloWqBGoGhhSAAmqiyQyXfa46hsEl095oz0MFYuKASY56PkBnTm726YREXk8Wf3cQ8BQhkqw9Qa7bLIYuk2VdNxChQ5v1T7Ro0FxOVouIZugLYawJZI,tfatGOmTRG6AkiaPnhuvask5C1EYFck9ZzgcQhpoevtp3YNfE4Pe6aHqKPpvVsmCREze8RUFpAwT4bcSNyIWxIXNiFWMGy0WSCvsjEhRmeTLATKrf0qbf3QMfk12aTmVlqPJ8qjWmoLBZt7Wyonvw7OQ7Ejce057X2oCSEYlRLmWUADl6LG3aUQBWVdR3fOBdZpoun4t9AAzGTEEZixt8tTS9SdvDV8xUvvjGzVnvOQokYkbSjDtF7WCojAI5JhG,ldSHsJhwMgYoAX9p4KjiXy91UoI1SNcmx7C6HUDrD4t5hmgPvtmSEdixvN083RlGXgf4Xfp7YcZfFAB7gug5zwtQJFwdLhMAboe5Yeoz860v41D7tEOJirtl6pDQKqAFqW9TJD8fgE2AvpZqDlvNXFA4kdamI9cYB0IoWgNGU2s1Z98I5ot8XRSMxEkZAD6klDX2AvUZ6hPQNvIvowJA2cdpaOKyPJJnFakYReoUjTXIVMHwRzKvQvDBVBCTEkEL,DyCd0GA8FVTUnqIlmgmTfiFC6P5msUlnSWpDz3Q1QkR8unAbAblv1wVB1PkrM6vFsL4cHAXf5acBGYrPDmj1s6sEk1reknp0tZHNLtaqM1eh7q5NAqgEESMKByesQg2QSPZhxaA5A4v7ODBz7XS8OqHVZ7XhYjwnlQBKc4wBM26IRoXJco67CL41uhhTnr9cCPY0wKqbnAxRNexhdxCHrkOrQEUXLWOBmxkkAmsB54qizoAG4oPZ6TH8kl65RWzG,gi5NhMKefHv0ahXYgPzDFCtp7cNbJJFjJUvALMvwp2jdeVNaGUiKijxNvqyIE2msOt1XkJpJeySkrJQMoiR2JU2WIlg0jb8gf6LnWxYkKd7jqjSOZejdxOp94l8Jx6LrZ5jatXtFWDmJyTzQeJuTwNzs0H9v1w2OllCaf1IToMYoWiPR49NQhC3YGHIiUWGSWBvnmJFWbmBVtn6xThZNiKYc6rucJIPbq5CSiiCHiJUxhAJ5egGNXCV9kHaAstRa,7QwxZkH0sNnMzEPOLJYhUTJwowPuyxfkbalgLMhZe9GUmAfVdWci90GYvYhIhmRlbL4C6vy35SMKquwGlTHCDuqkReLgwt7xizpBiuqqRPaFUISEfKdaAdUf7l36XTyE5mgCg4WzPTeeVrW7kPFJWmLJKrXNBELCgja5HJgLvCWF2JTMBTV9jRF3Wg6MvycKduDL8zSMf2Loj8L0sB8OoEaF00a46cViJFt3adZfsTPFolfzvw0uoGbVOV6OHE10,ByreniqB2oxiFcdaSjTJvg2KvwLeBR37sM3gHHyY0LW1QolZD4LVvcflQZzKF7w1h2T76pfdtq8IdK6XmTVnu7fYmvcqJAuh1Mg1HTaXS87oCQWOGCBAYq9wx5crHd8wS1VOfTypyWxgy9sYOR1O5boPzhBD7S7TypbX7NdzR3rnr34kChgx627GgYxhsi58WZFYeS7JJIxpp0JNwlX2bS1lYySVOu814PQ3tBcG0SJwZkz4VEP8UbinyiHKbTw1,wNbomR775vWPm3ljHAP91yhbel5lKxOW5uyOzYqhXVhuL5HrizhQDy3fFxwX71QcpseugvdfVrRQJCuMLvBbH2KnWIT0BMtnEcnrYmlurFz5R8xyNHr7yVyVzaGZXeaGhy5tWa6EnQZUwvOyRShC6TJ78A0VWSJHG5waN5l8TJMS2hUCOjFPlqiuz5WERlHU12nAF0w5gdECcbC8FZo6gpG3k6ARwzFmeyRJcdtttoXsJ0JLoJ3wNIU6cwcbMtbP,9iVJtKduWXbJQw66sdTaR7TrNnBhaFN9vwo8AnPgdLifoIvUO5oEPjYle92USGXDSP1H1JRmEBvVNfMx2X9NvmN7PjK8I7Nq8RDv905eVRpp0klTUzdLzhv8qnnayQeTF2rMYhkg8pIgOF2YCe6uPN2YKiXAkTLmwaiwDW12dXm1bln2xzq5WfenWyG0zV0EOoPjk9EPHXPFFzpCwhbvh38wADhe2LOmlz6TCAQjSJLmgWM9DIPB97IpmXUnY1wo,c63rul4SFuTjpmOz04ptkNnV9NqeChL7HIOMXkBM9MO2c8PRWbvj89rLWCzZY8crc9gRik7cJm5WNRlP1DmZ0Ot2iPLwdLcc6UU3coxWBoGtHgHwzo2ub3JMFkNsRqaOOtOLDqX3uqGKBWVNFhMaqQEEox9OyKACcPbya7fgRh2Tlmlz9Cpb4uCH4G2JV879QFohGqdoF7vPUcSh2wKrCSUZFynbesRyu2nN69qqN8L2yx840uFXGxGP05DoPWe6,XBP5wMCNU4jqSGrv59FqvD4mvRtO2qSynl83Pk47GetndYz3GW7nDqqFcge2w3BV4NTijIA7eYi1SKSIXuJkdQBNBWqZHGbQide3vfntje4UVgmT31ppDcZqaZVtyqAuGn2MzPv6S2KUCYrxWFem0scTlpBPtX8m7MQh0ZfizaN3bdTCxfehWLflAsX3FfhHJmju97Y8U1s3ThodrTUH0APxujlCTsVIGfBAZSKs92qKePifrLMnPf8A5kCuFS5H,w8LGw9PLqq5SFhzYbxZd60Vq7OMzqFJ5tLHI34lLFEk4vAX4xEvDD2mXrCJXCHwujwwgIirlQ7cGnUbUAMadJNQ91fofHsdX4uv0F5R3rdz7teT0Z3v37f4RAqKyMV9WuiPWuJR3qXlI1015wx0wu3lApfLtyaNoWGOmlLEzd00LPM7547sPVkkVSWIQMfWXY8hUSe5QvhMgI9QKiucpgLTe2kzST9yH3Oi0pJwWFyeE0aOU9uKYlkKfA3a1dasr,ObNnXiU9seqPKZ25MsM46ybKgrQFEN4SAsj3socqjchQn2KkyGvMIBscQnopJurEgRKhWz0EcMhHMy5AcZ1miAlQHmSprlrslQREwDiTCKd2jdPIxQ4CzgQL74WiW2KmHTjbpV2o5mdQIbvZeGk7woh1YNq3XPcsRc8reIsOCR729IyBpEaiiLOPVMZqGXEXSy5S2jTc49B2lSap8VUx2TNm4Qj147QAEL6dobDyqbGMsAznWEmkcLx3NQe5rKzx,DutQxVt32805og3VWpxBtfefSpyXsawvalJTjariJCo8Fc9Hg8yWlNrSwornngzLvqQ0QZ9QifkvuUjA0w2yQHNPiX5Gt8BWSOuufj8mlX2YFazGyw6zWsU93V3WWa7OjFyW7JN3B44XOd0SCAeii4z1TC9GwcDI2sElp3pbFLYamGZWf5vZQc8y25LdDx6b0lPefmglyHNw3sf3jQe8Z6aZd5zy83JME5IrC0ENmrdseqhNOasbRLrmWlB9vT9g,AkTi00rxS4wPx83E8locjpZ4MffwSotyrqQ9XiEL5lDwrM3PgT5VBwcl4KRtZRj37m7haOFQgZTkURAkqXrgdP7jaGpSwMaDZ4Q8pJkFqvQ0548w7f2wgtPh5OXwKOdAnKu9zyVBaCL9ylTOFaF4U8y1OuybFe9uSfwIHvLHHnysNAsePe8Tvf3ta25t4H61RgpgXPGNIdcgmibB4lPuNOxHaqKIvVnVkxmnciGBH3A7PcKZR1wrEbLnwHB1AkWv,a4gXUe6QcnVlbRI0l918aY6AgDJs8tkvJOjTbIfm4L3FJWwRVZmUNH9WcscCxnf0b1YYXwtQk6Tu64TJXikzgxIYEjiQzxVM9UlqEubzVQ8akYhgTWwYeqLTCZOm7mK20w1MonSrZNh1e5EwzzR69d9CBDvjx54Kwpebz120YJUDA3Z3YPmKq5kKP2pCu8Bp6GttsvbsY06HAEieBT1Q0WHKJQRTdEstmX6DYk8lOepRM6MLCnszDKd8J7PKPt82,c5mzE7d9OTOH899ETYwtYCMYEMJHUqToDPQTLAAzTby4miyWLaDuTM1YLIVIRddXwcKGQrL7mocqYgtxulqld9qqyjbttx4NYgfPPJttC7JTojAE3tGNxItbgXaq02tAgmxZra2G9r1WQmgnQVqemRRg1rqrzn3TM7rHnwKiRGGhNkilLq53pI04zXppG8tYNlfYGOIMTD30VSjIQMe4ZgLAUzF0wmfP0RWbsv0z3fLRvrmCRJaVkGP1oUvAphZt,ktRPZp7AFM8bHaNgwS3oIugHhlBa6OJwhz0J1O6ACj3h3WSrDF4mZjgR4nRTHenZ6TFFjBo6AWUzp8oaG2cw85T0jQLSN3mwVz8mRsNur61lwLT2q3M36ng7qICDmfGPtz7azdDYRrFqxto81JNhaqYbXUObVXoloVWYe5lBoTtk3BfFDXLx4jTI8ZLPEpnqYBZMGqYzMPJTec5r6CoKoi4iT0FFlTyXuWDbXPeWLXI451YvI2lxcW3qWWR9vbNT,W4nCrok293u5xjanMhwGHPqNOfI7cFeqSKVY1zyYiyD8gG8lT7sbBbKAMoyI0d2Vz5s85PvJ6Ij4p2FLpxdqx0GFyJOyFdyRMfZZfeekeqzdMkrP6t8wjfIXBMYARE09BP5Mq3dizWgZdpjpLQpeiDfxjLdQoiS9BH5zhW2PssJ5KM42Aa4uNzjiiWHvjaYBr5igxnQE7aICKY4ox1wK52hqWseMApNCAYlenucD7ZMoeyiEksFAIm15hzAXlZ6B,SKVK1t2Odms4IxFxTkI1ojSgEvUBi1Aqr9Sj9fFnkKNhZGnVCUPu3sJ4MTFi2Dl5HEY3MNlNeZ3dymAdcitb9waZmSSr5VJchLpTZ9Rmc5o7nwRHfpB9hAfCcw1VzM4GtjmN0qU8tnCdK3gSuu1drj5SNQpWY69Md1EE5cxt6bAPF8v6bwgHFkZhCb8UccX45AdMlduwvxYPahWAIEux1LNwzu6GCzshXB0xc06YdCq1X3w9TJss0nkFr7QgwGlf,1hm62Zqx8pOCaJNPvDdrZjkiTNBpW8GLBP1sRvBBaBvjwFNeAeqvSpcsImDqHMen3Ve5Cm29emndTlgqAfvNtRsOEilLjJmolumIu4c6SxmQT8IyGbExDXseFN6TW8qTM8FA4kPc4SLE0Btky2L1xSPS2CI2XeIzglQLuF161boSRNc2THIengzrO6qE8FskY8XCtcxtfOyGbyO3M9m7xXnTVPe2SwN8UNxBKE9EAAFtDrZN6WMaXQVFC1OQHEJG,cFCCAt6KVJFMJRCLu5qjjk5WbZjFBFvSIkTFnRArmQXTg29et88S0vFGFIwkV5Pr6OUCkYW9tW2XXtEewW3tdVQvMqNdLDkJ6pcaLADDow5pvHuxbY35Nugesd0nAqdj46Uutop46qIaWV3l5kLWhsHnDq5xV6Qc29ZBpy0LwhwfElnxIdgRHVbDqCiiIjW7nI6fQniVwwVwC1kSYhs8zlfhtk5rVoeXL3gjuRX7J8JDybkHtsNkeKDvfYH3HnGQ,RuhY9HXPJRgh8GmEfy1n4mPZpRU85NWK7gvIuNna1j7OTOSVW84UKBHWC1jEaFTD8tfY8NuMhye9Ot3b8RCb2bYIkTjt2JxFjmMls4DCkstopDin6xWQaams7m8r8L3Xh7UYOkYJZXOyiqhPI5BFS63t9YYnDYfMb0Yt9z5S6zcOaLEiWIJAuESY9VPGhYVYrwY7bkLV6gWB7HTFHeoj40BdQM4EyZYHlX2CEDmCjQ53xXV4kJL7bBqLLWKXaGCa,TjZlkLIrhg0iBgLfklYytMtcdE1x1cqnTByX950u9BamkBji75FTV1BuLAut4DLlFc4W8WqG4k0Oqmr08Wi5UH34l3pWPDf8i6imhg1BJcp5ygzdoUMuhxjJUSuLVckzDtV0h7ZttvtOGXfpCzCDoYso4Ex4Ag2edYq4x4vg6aM5tYFSU7G7ViX8r3uTp5TGkMO9fhPLjxRMDiLjUZggSe7lZYTmpKXk2HZaK8PvPvgaDugZx4UNsXntzHwIWRHy,AdA9uV24MR0B0YfQeyUYKpljqKVRxMd9Tu0jPQ7rAexe2XcrzoLTj3dRo6ss8jZAmrEMtMsyS1ClZQ3PBtAZDZul5b4r7b2QeYyFCoBJHIwairon3XFxfcg13xvdYcB9EeTMukvqHwO3Qz5lYUsqzojMUCaI62i8Y5cqUkYXKssU276m99R2SI7zCs1ofhAcP4usA9Y7fqkBJI7wVlsZVCmBCRwRAwtkucJ6elUvISuvoO5Ydua7HvNqYMyWkGrY,Zn9DMRnP6Xu9J6891rbfIwsNjYo0VvUGUpVUS8UQTsdx5ALwiMDiggWuItHMRRodqnljqX4UxuFAfZOuptJlqCQYdU3PIHSK6yjXOBcjPWYnoxobliJUAZQzsNHbDftbKrpOK994mlUazCNS0OEDZMwCdT0ZpW4K52H7FVJ6Dc6oNy1yzkhvcBQntfDAZEVr3MPUHmAesVvzwt2xrBOgXA2GLyKodq8HnvRAtjM0R4mmct52DF6MnoczsWT1N0zK,f0JJSfywqppEYWJ4zNksZ1lK8AJuIvmDGJwFnMx3maqILhs8bT4ABAJ2UaRokacyeSl3A8BxcGCzC66GwzTNqaFh82ZJXGaPr6icO2Mzu5nBZXVn444HV6ZFMAkolAqv5MSWgVMOCQ2poDrFb1FAiHWKNkSaWbNCsRVX8kr7mo6QyNBEYyfuFBK95YC3BZo2ZbCibIgISAVqD7DRsHlFTpqedYtsbQ7W5h04ZEGu1RzLzOSgEtdSs1cdYC81aFJA,rcqO19CJoVvGAmwqXd2a5l2FKZsIA2BqUfPqyCRm07iytxg4Vh4HavTRlOuuRaeImHkyDZ9CN62L4LPmtI3i3hFdlETGpp2qfjk7v494CnowDvJqSvsbC6zRNCQoFQLdoLSkhZeS55CLqOe1TEAI8jxQAY073BVD9VkHCtHoRhj2J8uBtynzvAQQXeQg1bStfLISo2O1Nyo1Y9TpWlKOw4PdJwduZNpAZ5vjYPVJE8TfyGEZ7ylDp7aTEf06mPLJ,bSZjuE3MAmYeNFioOJcOCZNSqzpgc5LQ9XDX1fnxGxKiNSGukgap7Vb60Uz2VyrcqjT2spGTVgej9Yh3RBGT0IodCIffJjWN5y9678hRg1FieWavVDAwXpmVi9TfxKDmvBUqPKwkWEJVLXyVX35VwWAyPP4RTJlsxJY56OTQd9pStuqmcPCWdhLxZUlGm0rj0ug7uHuDcvYGpihrPV5PT0EuBfskIreUCRV8N1YGW0LHQtEHShV8qfVMPDRFXjn7,ypebbihfAzRSuotydJdMs7qXcpHjxNCYjmez8IwrDn6gbR8M6XWLUqJKxjdh2DhSEkvAqj2paNqV5lAukMhsTVz4ZVyApi2SDy66IdIgEeo09CEbSy3s9I5swH5xOeVOMJLSntmrRff6Sqys1vmwKgdINiyOc3yAOrQDmCJ34zIAFpagFYyaV2wWyIWjxwKHNXFZnq6mXVhsWuDHw2MPTMMANKtmU2MCVykIhD0RoVUB4VNh3s3Qvkn6FnFhIKoz,bsagZvizd1ui6FOmOFUBiiPg8UQO1yJV2cinXpAmFV8xnF51j92ZilP39vri5aGZpb10Q8c6QRlvVVBNdFml9NvohHOOqpap4Az777DJWLRPS5aNnc4RCNBkfR8f1Rox1UsIIa4kazSuYATOp9qrcLc2JKDoMzXBX5LUEO4fZWsuztvJSXyajx8W0SkwyuWkgl3MMacB1kMJHTU0LB20qqD6BkHC1VNnEMdnh3daknaX4nKpEkx1t8FOpb2Ak2gx,XCwO0zvT0RSbEW4vHas97Q2pb3N5gukzqOsPAuvmNXk7sOctGvpFHpqyU0QFfWeVxmo1rUYe267zAKP8PqBuQm9YGS6PvgALrvnhicZwrfij3k0mTYgDWavMEx4yO6waBEDyLwrLoG3BRvmAgGFGhMje4ZoAUPjgudwkxBMJoKolLg63a7UBaDFCnTLEW9vz5zTvRarnggeyk3j9m8JpYvIAUbHjIpIVMGkm0fjXdsE4X9jkWBwI2xfDMUg348hp,Q8Q1Mxr4l9i9Xr0sT8HMElYLyJYTdcZzop26WGntrzhno1AShyl7JnCwdiCDcE2VtwO29Sb0uTc6pECmuXLUsMQcHu0ZIugl7qz4tdnG2ck4c0PIOc0Ihl169fnnulvDP8F47fmOByzVs4cIQfYhYdzShQoDEmyXHYhXityDT9kLXQc7ij2QfSg9Qxs0ncrAXYZbdwY8rekHkLySef5kgjak89jduVMvSrfgo1oTjmHMf6yVrbTYpbVET1n2cA41,89tc188GhG7RPpU01xupUkAcaXpOiswaLPnGd5vWBHMfrgbkO3cJh2imbRdo7T6GYmM4wfHJ6ld4tU2Dbz4sTJw2sAkiCNHqKOhLOGpVd7ovdnhmIQjfagz6kx3tsm1uKnZF4lqF00Ltp8J5564vNAVjDTxECjqjFZGlbmKJeSOiOo6VAYzZlvWS1tL6bHVRXWvmdaavFRA1GkKC1KpTufsKzm2wVMSSJKZTGWPNyECREh5oRvH5M1OWkt9M1zrt,gDhMNZOTAVbcrCcDxl9yf7nVqU6dQ8Wa3uZftZyZrZdzQdj5uxbczA1NlbEEH2lBmvJQeroFpQAUwPdXjBMrhCeQSN3WXbpvwmUD39g59A5TFBu1KGohlqKpzs1ioopntI1VKDXT5vjLqGABtyrW9h586LRjpwMJJYtZ4NjNAhFOLgTlA0AfhnsMwAA3Y13hqNANWO6FPg68bT914Qqi9WEcVm4yLoOjLQaPIWXxEKo4OF99kiUGFfWFHSvmP504,8MJSXjmi3Y3u2hVc4YNtX8uHccBEDc8PKCRGqPWWthjGoMsrA1giXvf4HpxulYsPbpGNImnm5JhESsX5yVlWhQAKcBG5lIy4O7J1keyGVvMdYXL8ku7a31DvX5L5n80qY9PHclYPdO2zTGRiv1KqInflH925mcfGIHSI32L7jFhb5eAdtGdnOCDAhV9XgbuQwGB1qkQu56iLeNH7fLyT1lVihS9h54DelbLlnsgZEPjtXnhMocUfidcKul3AynLG,VqrjNw3He9xYaoYryd8Z6AJe9bSRzZ2yKL89oCvbwKFSDwbO1MSCKXc1rniVPyPGQQgpN3xYr5gZ35eJ2cX7YMcjONTRUNcGXrVcYP0LCoZOV0hkavr8AmhcqU6qAYonUUEAr8ZaFK7AZGBR0OFjsUDdXiPAfc8JUEIdGbjVAeA2fIVeVdRntVNJrLdtqpFArqKd8zNXEtmTxeQmfyqBufmE5F8yefXWajTm8m1OAN09FlZUgIw9mET6JrLyys4J,w0Yrh9itD9cC4YIq6MbFzKDyky65Y7yWHX8YflA524sAODdI2vUuTGZJwmC22NpEddnjyrXAWeeM9F4WgIxSPfN58a8fHV0fpycbP3N2eq20uBJkkKXqm6DDJicCy8XeeC3rnOGb0fJBJrCN5OOC2ROxSq3tQ4CYwVYWZTdqlZBdq4pSUNtJ1VTSYwuwgsGTQ9KNETnRkKtQrAkWeCoDdDrqlQvjTGq0yETUkoRVP3JbJP9M7VIGu4MLtjnAGCiR,DduyE8z9uIYq3vCC844OwVV9CkDRTfgyO7UhTD3T7FIkynhsOzjd69lsef8ne5RVvn2FTdosoF1Kkk5nHMtiG2cxKy3lv4TNjEuFJOsKRnDrpp0gXR6onwWiPebsC1jYgpYIXgckLyeIxYchoVS3NYi60yy12ZHAvpfg359TcKCJSPlqC4aQpY4DmDdOxl9g362cpD7i06EwG4HAnRucXtnBFiEXOtMzhJtbnY7ifRcRRMj8N9L127q7YBYE6E4o,hcktYablTzv2GyDeMC7as1CWai6raE0d7ySpfBCbS9Kv6hRIBYU17TBJEYAJq9QetIv4QUWH0YKotNLvdgMXFYajm7Z71HU06s1omwfs7LnUURNjgB2Wi2fEhMvun7PJp5I9wm977864LXpHhWyMYBe4uPwr1BvYSVbHo2CednH3j0pJrirMs65VTR8VURddj8fduJUzejEVOSjIf0ccbkkql244KmA9gmxCfj6bYLtnDiCfBsIp4Gg6tlIk1S8h,GQJXGiRRdt7tD3YaxCq8L4l0wYZq9RUR0gLecVX5hwIfySGr56SQlkxa4LJVWDgj5N9CsXWGUoObO8G07iyaYkSmojFXGgaToDfXFo7DUVR8dhyfsWMRjt1TyII0FeNkTVqnc4RppKSwmi33AxNO0SPLAlj9Xm66Q0Jfw0PrGjDqdbLaeT68L0WD1enaJ3lx6o9esedRGVWkgNPXQvPHfVryYF8W5az0x5xPf2vz5ulDEjKe5a6OL9OGTvAVBlLT,kgemDCT83jZqI9tndwPl99vtA2bmNJoiISCK3mG55K4hmw3ReLBE9BoSgvzV8lqHwo3gJbYYvmDg1enSHI2vMzugPV5AuWEbdWjdbN3xAsITFluhEV1qrxm2YsvwETIEscyeMqAfikrvF9HceZVwjRASYPJE9VyKpA1dvwAgM8WTg4zuaLcF5LwAEcYRGxpKdB0upmryOmHzoKcPYFMXVHp2opK8vkdCCqT2PgmwmNfo8XWzlkvEF5xqlPq0vXpB,feb6JsWUXJQaaheCtMNDWt02Nsrin46axO3XXhEd9djRgYEQSKRQL1Qlzyl35IRd6AJ9zqofoxJ72S6YirVdzUb0ERLRrcjjNwbBAiV5p9O64Tb3achlcdRGVwIhmucE21DVTlvYa6YISrKmuc67MkjbGKAeLcpJFIcU5KPNpW1ks55GfZbDaUJWmrMIlcilGXtKvD7zqOld6regcBY7vDmx66cH3v50PPa8zra3R7ARHlunuv2bjQfLwwuwRvnA,DjBv1nWnJfdSR3JHviQAWTq5timoseZ49mrnjGcXFMEKeeEbP4ytYXEmaBE7qgTxVv59EIq5Y8emnovJEjW0Yl5IzxzLITuhsfj9R8N88BIozb1t4ZpkOhT9cscwTNGsswjnp8cHGFleNnqEeGUXNwbrYDlCy856GnzxTONFERXNbe2geZ404WwWFqLTmsM6mCcViNgcwa7C4E1g65ufx2ml4SxOupnF7nHnRccG6WeUdYCIhUZkriKlr2UVh97w,qottDdpHXFvp8AelFcz38D8J5axKAwerpSCMpry4WsxewcERhhIQIUUHszyfck6eY9WihaduxkOXiP1y24IsUNmQVxc9MaKGj5JGttfkDgXvA3G5aeiZzWzlKNFWnAnAKBoeScbpCZPWURYfaW2WwHNfMVtHKpTtIWpH2QTTQbEJWVPRdwyKyf0VlIkrMbldtf0XqGLxFNBU9lp0fiK145P2ydt56Z27cKVMJ9U8Y1eHJXE8ZflPKhdWtXUOdb58,oK29ownj7btcdM0yWOrsjP131bXggd2jSpCXfANQ3ffnkwRDhJP1O1h9mXkBioj5mfo5xF7QRg75ubQLRcTMz7RCgJXNRYAsPH5gK5FlpAz4VmPBYHD6boSExi92juh3sUb3PwqWMjvqmPBAvYZ8dIuH6uQWjCM7ROSAiSX0T8EaoKb260mysKWhla4ayN7cciGIHdZ9TLu40GkqJouc4IfUbhP2060ZsrTe8XhCWNCVa7FrzroVexhMDFjR7gBf,wQOIFYuPBe5CEFEYTFuoFeEzTCP31sM3LsshdzlKKxaJNbYs1eBX6nszANO8ugJz9ub4PC82AVjj7yetJyIQ2I69kQBLbjBO4mxjKPSXcRU3eRlTYxTIWgfxMSJxniDtgYf9Zwrn4lCWHTnfMkkDZCrHogO3rbA9HugTrBM7qu5gD8mU1Co8jGfWDwrXiaoFfRDfQKaIjJpXY7id26Ttuhp6iqPRFFGWDVl3QyWGRHVlGVRz949pv9RoNgqGztl0,fBlsN6ziVgEGIU3VzcSkWpPBaeqpoSnA96z1fpizQfOntkqHJU2uq2uzabKGHhzPrtB3jTXSYoKeEiv8xEyICsyv15wwMEnkGZnz0t24DoaKWgFZf3OXkJMzlIwYMsV0kUpWSJCOklP7wM1n5FAQn2FpLSUTEueNAxNdXx89rRR83lGJLT73zZDEvlaq1DTj5zPXy1LRrOlIKLQdV0uaq53STYOFGpSWA7nD5a0MVQjQO5E05Wt68etVRgrpBUoM,vlHbNOZFvdiYhXo6Ohk8Baqg0ucj611GROfa0pUIaUXmaFORnFwJNjWShJ0PAgg5nzvEYJL7npEksd2XSBvhtl9tYEfac6G1At30mu57xVquvUhEfkHLVB3WGBksuOi9hhOGlskCmBZ6xKu1Mqk4FJaymw527lbwpNKkUghIq8yNlBfagGcvxCPWvtHericyru6Trjy4FWpAftRlk0KS8NlqsUxmpLFDW1kmydIHIo4sRo4QxxBojyGX92ANncKI,JqIX3YjsxxE8cFGCMdF0pGsD5NOYo0Xde7SGWwtNGp8CSs5Rii8r8qon9E53UlSNAhmv3jTQywphy3yB1jrzjkqCHB22zA0UkJjWt7Q3kOLKdt7FbUkdKDyVCRCLAuOob8FN1CArAQCBr0h7i7YK6LVelMo37zQ6LKYLKlDH6l6bUcC6deoBGy0QZxEkvCaklwmFTZX0JOWt5UlqOe3UX7UcUgyh1uJOdrriwD4DIfVAEbjbMHDxf6jA2Z5xi0em,RNnCVTqjDrc3wl00okdhaNond39MmgUcjbs4UmOiEKN5dsSamltCV6jWBMhgoBh6LbVElNCjm5ConKua4yFxrTQPKiOJccEV43A9DgjSBbX3joPOCq2zW8XSeRS2wE4S8LF32ygQ8POnSIy9y47prRqynuYdJgw6MK3BreIeR94BghBhDuL3qNmuTepOg2iEbABFyJTqDjbUlw2ixodZdeCdpzJ97yTS2zKhEz7D5lPOXNyygm9Vxt50mfJ0V95O,xTbROglLLo74lCUpFJckIK3k5lULOmDe6wYX9KUPdPKC2Qlwtzo7jYblkqpJzZRcW1y8poFmBXCQCyHkcZcGhDtO4FSZdyOPie0Iw7eKvINHFF1QQ82uyJRlgf0cGOmF3G0LZO4rUYcBkk2eu6pzRpiQzqaKidIs4fMersoaOSDp2xwWay3aSIx7B7xpaYeACxVYuxJHzdlIgcCOt8fzfGGMEiMmiebI8cd2OSlYh3CijDbjZXeRYBf5d7puPNqQ,pPrxpimnz3HeogtyILXflsKhuUXKR0g3b4BTEi1hJpi6JZpl9WJYdkFjdPsZ2bhMjb8C2iyH04xaL64pW49BF5aAKoqQcgNrWvb3bJp8UQd1DTEAqcYvbGZe9GGblSGyvtGOp8zZzpGlCciyxipF5Vw06E38IGl1bCn0OB3bhHobknSfdWJ6RQI7KVOcNLyO40QclqZtU94wvr6ZL5sZLB8eYYBjcIB5Odbi4NVre4SL73LNX9Q20kjl7JDhELvJ,7JYiyXL4VUcTLtjcgstJqLqSxEZICj1XfLGZJnpWyua6A9zanC5qsrM5PFNM8gVI5Ek4ZgaZAWbP9fughAkZB20K8KCO4xvRkyRxFwfoFKNdtOfxE2CW4IbFIfWLcWJCN85xR5Sekh0ANjlmqoAyuoVdmg7ZlYXI2iIFGbxDHqrfq7lcP2ZAhS7AaeygAm9XUMN6BJblW1ZWkfg3DOWErOclZEEvEdlZxFcRQh2jwIu3Z6nDOVy3FchhgE2P2GH9,RnfgNj7433l9SxoZOOoZ9fmf92CwyE9FOqQEEWqeMogNRsxMEQ6vsdHt05U5ZxTiIkHyLH7ciXxJ4GuZOnra6gqL8kJjIPXbEkrhmHR99zLoAT7jJvVbAPavyFhSs2XVVhQbpfXlYVbWDR0t5t8Zu7WFqKpbITWwzqvlPqGbI6tp9uCdbj2qMpIpHkuYg6URPeGJ2CIs0fNwKZX6LnPWqwMOkcENR4zwAoLIBEk6woHBaDLrK3Sn15ocpQiKNqdK,9fuzn5IVgoS66BMJDCK0SynjDx6NZQx3uzm5iVGLBLoGjf14omoBd184JzznUytkCz23xVkNIQlt1fBpWGeLjq0p7Vm2StMm0VQ9383mudXgHdHuN9ZIz4DtQmtuqD8DkRahEu159WRyW7ATBqhsDBnwcyeX2BcK6kSA0gVYp2RGCA7mhdIOS5aLZFFOgHcSVARfur57Vm30vvVeBA0swwPNp28zsjyr9YakUPUHSbMWsZHq4bu4MjkxUFAQHKyD,UQcoF24tTn32IPkUn3gdTfex1nfW6D8AGk9P81WwsMGRbER9gr1HHeGGcwEsaBjMqlHR1tVDh365iNLmDodszYmG4KUeR0i5mcaVzbom8PMohGtlzdHz0rhuchFit7EJ5xGeFGGhvRCsEHVbFnlLlEbzhW9H4XhFfSd2htRkcU5d3RzStwX4dXLxdAf6XISUFDBOdnpGvysuNK7JuOXbnypIXVrN9zeAw89HbslD3WkJVJqGCGRykZqaF1Ot32my,nTihOPnagqVagMQMdHckNOQKVOISYnshqOM91HVhNIep6OzWQorS9rwrNIG9PoSqW481IgkaMzNczboeiOVS5l1H8JtNxRKyUuoCRngmIhU2WstDphnnj9T13pmrpDkJ4BjgRk4CO9LePFuXaLWpKSWv4VBMqgDqheQwNwmyR6408PL4AG5GtA83bMF0sbCLkE69DrcnRGT1CiRadeKKSpDb2afqtywjDivC4sRItSAJsOQtm6q0q6ROHWl2TVqr,ZjijvNAy4fv9NyNSYdUiNgg3cHglwSh85YiZDV6RPiknogyiEB1ewPIei2cvmY1M2EuQ8LxFlTUDKNOdqEgcIGFE1aQW2RFy1fAufhmUn03vWpQmH2vA1NPa2XxhvWEZwMUV4fWBWMqLh07Tf7ZdiCFbzzWrzleZJpRwsCFAoRsSOwCnM0Ir32i3gUHN2TLa8rvh8bKDpgEVF0uD5Os1SjW6B5qNNnUyJ55CUwFerq1mhYV97xeKIjwTY7pMSlZJ,N7PrgGFxa8s7zjlYPhcsyrHkdzWPESy9ATIEXXDabQeIF9wECMTu0X5moF8MJ0PJ6hwP8bt2ZiUsBnV0jpQUfVYei9BCu2zCa2qLQKSKXSkrwC5SVZxPUK7IzdSOVIP7k6Zb0LhrOC1UPABNFq7uS0AmcNAAvERiznLRvMP0Go8iiDpNJ6IKKKN5QjRoLJBH9eutYNQUBvJdFH26DYTpzv5gXEi08zX1b2reAEt7VoSPm1oDv7mKIrAyjgkMsyNN,mkd2gHctrkcVOAbq7ZjrMyHhNfr94LYTaMpG0syafpeFH1jitjr4Pia8Px4MYxsz3cYA6SICMprBR0C8gAvQWG7v39cupQaxwPe51hAxm7frcBOR5PbnTp1LlnoLawNDm09lIekq4mWdXjyaW18Hjudb9j2uiHqSd90JmNehnTj2LzQCoRafESIQrCrkci25zfY2sObAswiCqzT8BpToroYAZ3Pe0ZFN5dsg4XjRkPgi2dHmKly5o1IA3Y1deuNX,xp8lNTZZklUa471WCvkPvMJPrU9qE4FOKT8cdl9SFDNwjqfaQcBcgjy6rh4rvPl1zrPVGxGvMueI3XT4BJ2c1RHIE09l7P0rTIDZ5QPAlnQDLFlA5q2x6AjOnNb4sx04aq47aMIGebmdNbCV0wJO6WGpYPy3NmyNd9eni6njJqXB04xx3bhW4fDYUUfnO7EvF54u2zatufMoBEdoGIfvOfZQul7NOoeCnZ2uVIWFR1CuS956XvH1Zk1vaALXVEmH,YsCWAvADTFt6ojKUkwdE7XzmQB6hCKWaY7DRpJT42IonnaOdp7ohRf1JlH1b2rmxfBN3m41mAJkxO1goXb9fTbI26O06Livd01Rdnya9RWrUMsd4T4NrIkaegIFJbw0RTT2XrwznKzJma0wKCUNowneWoacABNJjYewQVzmBKODhYOLuOnVZex11jg1ASQG3cSytPekDYS8g9jsJyGc9JonIeLRQxKc0TqoLrcPlDapK709652FTn3gSWH8rX8eI,2OLbzMLvIiTtn6aXZ3mM212rCPdijoZhyQlPUX9wZLEFoDtPw330mr3sIEbuvzsoIO9VdcGsQVoJzbBgMVcnYU394Sr3DmJdS8DBQQ13OEjjZi61v8J0m6NyVvGgYkR6h90VAQK6ZFy1BwoL3nMCmra43oAsEFiagNmFd0KPkO9b32MWSpCrTcysFHyO2nmuAjzpCL2Gg1qG1Q6nueef3CFcL2rZzHuxbIv7k7SNQ0bdbhvCTlfXMDeW5NlMkNwP,TyBhahvNcoQVfpxvlfK1Ocy9I7BOc2sw6PRac2C94bhqpuSjMrbnAunXbjpYWApUmVduNiCgbisAEGiImua5erkzgmeNPepV1W3iSdRfKVASVv1uxWkoBd9xsz7xcBxWd8psjK8onemWtwUsKXW1XQwQMzBAM6M1vvzymNWLqU320z592fO63wkvnBtG83kXVAeQnrYLEKyujHSHbIjykZl9lDQWHImXfQOVb39h4ZUvtGwNIkmpOL3XaSbV1iR5,X0cHzdYmpMeSP6IjMDsEH8iXTyOTiHVgWlVzyauyRsPhjPO385eeYkeCuEgJsUl4pXdJseCU98JKOfwDqkhCIiPBFmr4rGs2AlnUR6hCwiueliVBAR0Yn7nqXKwFrvfQaFFyriRvfqwRLORcl6VlhzpLGrqb4AtqgFZqrU3age3aaUFnmvWL5PNR4FkcAUKKDyYyuuFa2BYf9TgjJ0vIRgJEVH9L5fnPKkyYB1WSabhqXH9e2FzL3ATOFD7a1So6,MmcAgXuwXVBNmrNr8mpuHQ0V15lX6NDu2gqSufQnNy4AJv09aK4WtYthk7BQThb3N4swiItT4oyBlp4hlqLlrJxZVNixO5Nh5SL4FKC55iJ4ra2IxmZRXFMth2Yl5fTVhH7cKSyB4v0q8oUHRymxfHCNoDpApU141R38WLFR1qtQagfqzvdeiuDTkxTwY7gEE53seW6mWQSzun7hKHxaEBOtfQFG4FlsOs0Jom7yIGq5GuJ0ODzDS2gpi611pSnQ,Y2NJqhyqlQ4Ckpd9PasoPAHxyJMLaL6gjxCoi7cLD0065QrMY62O0HTxJ3C9bXo0Nq9DViettQOw1oNrThAV3ekQwAbVKjiFREROb6VSezcvFSWjT0eLxFKj1GbImSR6J2Ocj1Db8ir2zeLaVWgggWkIxHXkovN6JK72C6Yqskb7SHMcUpJ0cup2zHUj3kSQLF7b3fucbLjcOixhqwjlIWSiFeMJYbrLO6A8OyiXKmfOQHGAve6Km3x6cPqJucIU,y0VUBzPs4ZVRyqJC9rXq5f8LbGWsuyL24zOWuC75CHpbFLHWPBwlmuftwDPHMViTOsLNlYfkvklTNszuaEuFNKpNYyuZnE1EezBawIMpJmPzvJqyutPbv913VtxbKj99nUZcMjf7WHftFnXjyHC4eLebc5XprJ77EpoJ9x2W3zPYlWaizZVR5NxsFTJqTGU414yoKiezYqXppnoQcLsr1Q5640hegJ0Y6NOP41cfNuKvleAMyRSfddZSRgy5qrwT,iWhGv4mhRH8KZM6bd3G1xPHka9DmHrBZK4hkmxqY8voCLj0A3ZP21iEHXGhFfFIrdr83UKmhVeyK8lG6tla2RUPDSv8BSWY3iL18XqHrfkkTbLPpyDvI7wIEGGlEqZ02uIzCPHZMX9yKtUIWKL3MAgpn7FCogj63fhURGtz3iIeIKhIlI36VqwJ8fJWUvhu1AbOIr3Bp456J1iBfhhdpDuL4Qx34xFa9QDvzwuXted8rFeUx96H48w1SE3TAwOeu,0GDWpS5vnn9finVmaVVwdevOVEqiwwpmW9JcO9yxRRFtWdgumZDr8Ui7NEw09ID1bBiSKE80gHORNDrp2hh2Sdno8k9H8NC3ONtzN2U2ZbDllabndmh2OzhqRdhfk2jBlDtAvVIHSx27FexcNRRTRfuWbqatupQ5NuTfsQQRgZs7oe4Y9re0yYcrZFXw6W3TJGXpHxLB34tlTKfPsTzkTcA4k3J4z9AMFkUeIGnXLj7AY0umydeTg1aUReNaN4Mq,L7P1PqjFuxgHa0X051dL5RxJs4r3p1EI8NmoodUSTSephXWRix1IDK9yq3SdjIMpx36EV8VaFiYnZwm9rkw9wXb3tITfPWOmZYR6P4YqkUfsKCpNRKoqdkayomG4KZgeWqb0eno1QvVjOt73IEImEZ1KEYN7nBtKzVuzgfbNmLrpENxamDWJSrsik4ggFr6VOtdrzg9UO5YrA2d2CsV545F6I9RsXNCezCZDhjLF6UbJzfaBZiSVYEV3v1qBvSNR,gFfB8bJeAJMuPMZxkkxxrnBGoulliFN7q9vqQDDLb19TOoItUXIUCx55oE4zoY08Cy6CrQm8S8siFo5WJ5YgxXu4hNBcVeEpqXd5QXd08y9L7tN6uBBJ1sahUxuTX3WOedRBilv6ZBR83arkXrv2B3kXv7bhYbwgkBzDQQXoSJ5qZOTIiT68GlgYbBzdNfadO259iNvhHPXvqHwQa02Uq80k5mLcNN2NYsnKqatAPL6YHe7WZR7ctsgf73TrZVlJ,ARrN8sDmEDBPriBRdcl1eOyyjiJmmk93OxCqgMVDRP4XBCy1qJBp2pB4LGTUE1nIkystbX5CrpjcQR8I0J7TWZQBQBPQy2XfIEd38ZaETqBCL5tkvCnyK6dl69lZE9NNOpoHZhJYn5tx9ygD45Twl2WkRCLpaHGqITp3Uko4FfgjMVxovkfxpZeuYob3U10BDWe7YBgQgccMeiKALTps4S3aoWErDFFKiJXxz0gSKbX1To8a3rsrryAVZFVj3glO,lRomlXFAeHMaRUaay65WQ17Az94ttODyyepFN1Y9qyQtgXYp7bRSTYaDKsAifDLDNX2FYSrvqe8BfqahrrA7TjZl9gImEd0oarzMGRvrTwxnL3GI9GMRC3SBzk9WR6IgQ0NGlzPz55DBVkz2oogm43W7XCOsCiCdwqFbhhJLnXUi7dpaMPVyhC32kd4HZxZRbbumxvtD8Uc6WqxCdAeQjsGWYO0SoVOQYjbqt93NMJN2Utkk6ZS14YPFeRjoeqEn,3l5GAqUqSkA44Ps9D5X5yEFJMg36toIPmhgEHFBTAwVALmXNXgcUQPRF0Tm3681mznH1InIDnngIrx8oGgWVuC46bL97IYkTpZzsXDf3OsijpWyhDpM7Rv3c3NS2owxThjjoXOPkAqPC6M9a37BWSNpsdcIf2uSMDWQIFkYYTNQyjh2pp618ZKXTr83E9Io1DPr4yb1IIrQvNAthCUChD409OGO1ktfgHJyW2IF6u0QLSeImUQ5SABJQhQVSS1xR,68VlX2hNCgUQtYe9e73HukMxe3NrsfVH89Mc6U5UNRo69XexpYOxVFbj6UoCCgbyT7vBDDneNjTUmlejF7V2kaBywmyu3J8KIzrsCiWVIMncUuHUzzPQ0tkQrI0Ybr0NNszHBr3K2m1mQowoOR6nd1ZK7U6F9swPjSLw6qI39LtKCcMyCsx4pWcAOZfSzUeEwiFHUf3xAnSb9vQODFHYj8uydWfc2wJb6apn1JQup1b0pWA6rJNTJM024mRQ5Mfz,PIMtWs6CPPTgosnbCgUXnEFxtAwDw26UAdnVECfIFOYdqfZzOJRrqdoIeBWb1uW4QyqC7K4gp7mCeZq0wR13Fhn9WraMcA1OJFTIfkf0A6HSbMo5Z1PD7xM2lwVibZxShV3rIXX60vwAtbybtqBEz0H5aS9X4zwiqOBMb2phpZPtwozuHu091YjYzGJnixBvweGCRN2iFB2GuQD5xQ7VOab8Y7yRJ019rR7AYWWjQoqsYiFKoToA1AkqNUtPBoaN,Xl7wlOSYs6VvPZrweJBc8y9O1TOC6kSoG4ZP49k6gqWZomkf1hBYBGKPX5VX4dL4BvD1RJucXk20p6wW3f3XyTNBRS7GG8uuP8oUBroUbwqZI72WEbkQc3xgSdzvhgrZsbXKOhip3jErMf0nnshGC1goNXVIxluAHLxPUgp3PC9ouBwWqFQ6FFEa7WpN4WSRt8wwjTuZJ3ioAk5h14ApOIpiYt5WRXxMnuvi1Za9nZmUi8btsxhOiskfphPmJWMu,MFZZowfm9QyCyfzKKeNqBp5JW7lZMUohMN40eA6zRetpHtWGDh5nOme5JwE4PYDjj19ckaHezZUkTWdOGsK4MBLoMAeHHvZpgLcZXMCqbFphTGzSgLxvUpsrcitEKzLewfQErQxI3IEees4CVTMkesQ68CytMYV4BBiD9nCK77CsujpUIBFJ4j4K9yQdS6mNrxQsg5yAYvdJ3OGBw0xKveev73Gem1HScDaiNClidKnJsuvxLL9U1er2UQfh74e5,9FXVdX1UgcmVguau8xoxEHCTJgXKHEZb1E4EcsqMqBKPnfUfPdTIYTYZYYa8YIVutkXZq9HFstkqHAStJYzngnwXFuR0e44qNLH3JVddNZZDy2hm8vVhzyPVDcd2z0YD2Y17aaUxHbVd9XxYLRkMQYWkuznaOhum59vf8h14N0RCpjioHc7zCvN9ei4b4AzFDHGEFGQcJY4G5UsN48SuSMqCJBDYg9Z8cGlymQhADqaNgBevVQwopz1D4EtGI2YZ,etMdWNyJYf4ZdEm2JUzknRXJoiEqnCGwERPQGCLK7mUCFPJziY0EvTvZZqpQojVbyE0lCAQlz6kllG'
2017-10-12 14:10:59 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
[ThaliCore] VirtualSocket.writeDataToOutputStream len:65536 count:1 vsID:,13
[ThaliCore] VirtualSocket.writePendingData() to write:65536 written:65536 count:0 vsID:13
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:13
2017-10-12 14:10:59 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 0 vsID:13
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:13
,[ThaliCore] VirtualSocket.closeStreams() vsID:13
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:13
[ThaliCore] VirtualSocket.deinit vsID:13 [3, 12]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-10-12 14:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-10-12 14:10:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-10-12 14:10:59 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-10-12 14:10:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:95033898-78DB-4672-A53C-705177BC68F9
,2017-10-12 14:10:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:10:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,[ThaliCore] BrowserManager.disconnect peer:3F732965-3C77-46D7-A946-F17E3B7CC083
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:52623
[ThaliCore] Session.disconnect() p,eer:3F732965-3C77-46D7-A946-F17E3B7CC083:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1668740B-0A4B-4BA8-BEC2-08E068BAA78A state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "95033898-78DB-4672-A53C-705177BC68F9", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:1668740B-0A4B-4BA8-BEC2-08E068BAA78A
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:3F732965-3C77-46D7-A946-F17E3B7CC083:0
,2017-10-12 14:10:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:10:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:10:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:03CB93C5-E494-4904-B899-97A742B84DC9 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "95033898-78DB-4672-A53C-705177BC68F9", generation: 0)
,2017-10-12 14:10:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-10-12 14:10:59 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-10-12 14:10:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-10-12 14:10:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-10-12 14:10:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:1668740B-0A4B-4BA8-BEC2-08E068BAA78A
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BD5ABC2C-C6EE-49CA-8523-9FB7F5CD0609", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:BD5ABC2C-C6EE-49CA-8523-9FB7F5CD0609
2017-10-12 1,4:11:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 14:11:01 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:11:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 103 Ready to advertise
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:77588513-A6B6-4057-8A45-02EA52DA6681
[ThaliCore] Browser.startListening
2017-10,-,12 14:11:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-10-12 14:11:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not ma,tch with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:11:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate ,(was in stopped state).'
ok 104 Ready to listen
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4B3D5F4B-8FCB-4D9A-B208-1C8BB00DA397:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4B3D5F4B-8FCB-4D9A-B208-1C8BB00DA397", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:248F322F-C94D-4AF2-82E0-F19CBC6314FE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "248F322F-C94D-4AF2-82E0-F19CBC6314FE", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:AA3E3CD0-8C9D-4EBC-A3DA-4B1C4CC03CCC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "AA3E3CD0-8C9D-4EBC-A3DA-4B1C4CC03CCC", generation: 0)
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCor,e] Advertiser.stopAdvertising() peerID:BD5ABC2C-C6EE-49CA-8523-9FB7F5CD0609
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3F732965-3C77-46D7-A946-F17E3B7CC083:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3F73296,5-3C77-46D7-A946-F17E3B7CC083", generation: 0)
2017-10-12 14:11:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-10-12 14:11:03 - INFO thaliMobile: 'Received state ({"di,scoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-10-12 14:11:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 105 stop ads worked
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-10-12 14:11:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:11:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 106 test stop worked
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:11:06 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-10-12 14:11:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:11:06 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-10-12 14:11:06 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Test updating advertising and parallel data transfer
,2017-10-12 14:11:06 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:11:06 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-10-12 14:11:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:11:06 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-10-12 14:11:06 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:908B4B88-43C8-40CA-B120-4E8CF7E2F120
[ThaliCore] Browser.startListening
,ok 107 discoveryActive should be false
ok 108 advertisingActive should be true
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "07142183-355E-46BE-A073-580CEE7DD390", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:07142183-355E-46BE-A073-580CEE7DD390
ok 109 discoveryActive should be false
ok 110 advertisingActive should be true
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
ok 111 d,iscoveryActive should be false
ok 112 advertisingActive should be true
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:07142183-355E-46BE-A073-580CEE7DD390
ok 113 discoveryActive should be false
ok 114 a,dvertisingActive should be true
ok 115 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:11:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-10-12 14:11:06 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:11:06 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 116 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:11:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:11:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 117 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-10-12 14:11:07 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:11:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:11:07 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 118 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:11:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:11:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 119 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-10-12 14:11:07 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:11:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:11:07 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:11:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:11:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-10-12 14:11:07 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:11:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:11:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 122 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:11:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:11:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 123 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-10-12 14:11:08 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:11:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:11:08 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 124 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:11:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:11:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 125 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-10-12 14:11:08 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:11:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:11:08 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 126 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:11:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:11:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 127 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 128 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:ac3b3a56-044f-434e-8f08-739808b961e9 error: startListeningNotActive
2017-10-12 14:11:09 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"WAAtV6bdaRPgZi,Wgkyzxe3ptpAyupIbu","error":"startListeningForAdvertisements is not active","portNumber":null}'
ok 129 Should only get called after multiConnect returned
ok 130 SyncValue matches
ok 131 Got right error
ok 132 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:11:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:11:09 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:11:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-10-12 14:11:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:11:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:11:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:11:09 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:11:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-10-12 14:11:09 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-10-12 14:11:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-10-12 14:11:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:11:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:99B0FDA6-1CE0-4E41-AE59-F2BBCDC343F2
[ThaliCore] Browser.startListening
,2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-10-12 14:11:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:11:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 133 No error on starting
ok 134 Got null as expected
2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"H7wraZTgnjl9MFEoGe2HrJeHP1i4UX8U","error":"Illegal peerID","portNumber",:null}'
ok 135 Should only get called after multiConnect returned
ok 136 SyncValue matches
ok 137 Got right error
ok 138 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12, 14:11:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-10-12 14:11:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:11:10 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-10-12 14:11:10 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# multiConnect properly fails on legal but non-existent peerID
,2017-10-12 14:11:10 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:11:10 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-10-12 14:11:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:11:10 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-10-12 14:11:10 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-10-12 14:11:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:965FCDC4-ECD0-405E-9B1C-A2101FF53561
[ThaliCore] Browser.startListening
2017-10-12 14:11:11 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-10-12 14:11:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:11:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 139 No error on star,ting
ok 140 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-10-12 14:11:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12, 14:11:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:11:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-10-12 14:11:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-10-12 14:11:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to n,ative'
2017-10-12 14:11:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:11:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:11:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:11:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:11:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:11:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:11:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call disconnect with invalid peer id
,ok 141 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:11:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:11:11 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:11:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-10-12 14:11:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:11:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:11:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:11:11 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:11:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:11:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:11:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:11:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:11:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:5513ae3f-2d76-4211-bcc3-00fa320b3439
ok 142 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:11:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:11:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:11:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:11:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:11:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:11:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:11:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:11:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:11:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:11:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:11:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:11:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6FC9BA8A-8B4B-4A24-A049-1C26C7D4A471", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:6FC9BA8A-8B4B-4A24-A049-1C26C7D4A471
2017-10-12 14:11:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 14:11:12 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:11:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 143 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9D95AC40-480D-470C-AFB8-670885D43507
[Tha,l,iCore] Browser.startListening
2017-10-12 14:11:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-10-12 14:11:12 - INFO thaliMobile: 'Received state ({"discoveryActive":tru,e,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:11:12 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 144 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:AA3E3CD0-8C9D-4EBC-A3DA-4B1C4CC03CCC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "AA3E3CD0-8C9D-4EBC-A3DA-4B1C4CC03CCC", generation: 0)
,2017-10-12 14:11:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"AA3E3CD0-8C9D-4EBC-A3DA-4B1C4CC03CCC","generation":0}'
,2017-10-12 14:11:13 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for AA3E3CD0-8C9D-4EBC-A3DA-4B1C4CC03CCC (syncValue: lUFhxLY5QIVooV592742A5H3tRas0LE8)'
,2017-10-12 14:11:13 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "AA3E3CD0-8C9D-4EBC-A3DA-4B1C4CC03CCC", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "AA3E3CD0-8C9D-4EBC-A3DA-4B1C4CC03CCC", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:AA3E3CD0-8C9D-4EBC-A3DA-4B1C4CC03CCC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B3666918-5171-4C9E-8643-662288950CC7:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B3666918-5171-4C9E-8643-662288950CC7", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7563EA47-7507-4979-92D8-1508550C9D7E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7563EA47-7507-4979-92D8-1508550C9D7E", generation: 0)
,2017-10-12 14:11:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B3666918-5171-4C9E-8643-662288950CC7","generation":0}'
,2017-10-12 14:11:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:11:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:11:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"7563EA47-7507-4979-92D8-1508550C9D7E","generation":0}'
,2017-10-12 14:11:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:11:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:11:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6FC9BA8A-8B4B-4A24-A049-1C26C7D4A471:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6FC9BA8A-8B4B-4A24-A049-1C26C7D4A471", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:AA3E3CD0-8C9D-4EBC-A3DA-4B1C4CC03CCC:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "AA3E3CD0-8C9D-4EBC-A3DA-4B1C4CC03CCC", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:AA3E3CD0-8C9D-4EBC-A3DA-4B1C4CC03CCC:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:AA,3E3CD0-8C9D-4EBC-A3DA-4B1C4CC03CCC:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "AA3E3CD0-8C9D-4EBC-A3DA-4B1C4CC03CCC", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,A3E3CD0-8C9D-4EBC-A3DA-4B1C4CC03CCC", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "AA3E3CD0-8C9D-4EBC-A3DA-4B1C4CC03CCC", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-10-12 14:11:16 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"lUFhxLY5QIVooV592742A5H3tRas0LE8","error":"Peer is unavailable",,"portNumber":null}'
2017-10-12 14:11:16 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'lUFhxLY5QIVooV592742A5H3tRas0LE8', error: 'Peer is unavailable', listeningPort: '%s''
,2017-10-12 14:11:16 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-10-12 14:11:16 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B3666918-5171-4C9E-8643-662288950CC7 (syncValue: BcUvxucIiyRbQpllHT5Ri0B,ZXqdShJr1)'
2017-10-12 14:11:16 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B3666918-5171-4C9E-8643-662288950CC7", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B3666918-5171-4C9E-8643-662288950CC7", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B3666918-5171-4C9E-8643-66228,8950CC7:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-10-12 14:11:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:AA3E3CD0-8C9D-4EBC-A3DA-4B1C4CC03CCC:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B3666918-5171-4C9E-8643-662288950CC7:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B3666918-5171-4C9E-8643-662288950CC7:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B3666918-5171-4C9E-8643-662288950CC7:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "B3666918-5171-4C9E-8643-662288950CC7", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52634
2017-10-12 14:11:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"BcUvxucIiyRbQpllHT5Ri0BZXqdShJr1",,"error":null,"portNumber":52634}'
2017-10-12 14:11:19 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'BcUvxucIiyRbQpllHT5Ri0BZXqdShJr1', error: 'null', listeningPort: '52634''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B3666918-5171-4C9E-8643-662288950CC7:0
ok 145 Got null as expected
[ThaliCore] BrowserManager.co,nnectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B3666918-5171-4C9E-8643-662288950CC7", generation: 0) found active relay
2017-10-12 14:11:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"qOnagPfC8DBn287ndJ8D4bMbTVmeq88,T","error":null,"portNumber":52634}'
ok 146 No error
ok 147 Ports equal
ok 148 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B3666918-5171-4C9E-8643-662288950CC7", generation: 0) found active relay
2017-10-12 14:11:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"rP,ty4P5ISfYaoorceCJFBWsVqdYwRkfJ","error":null,"portNumber":52634}'
ok 149 No error
ok 150 Ports equal
# teardown
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B3666918-5171-4C9E-8643-662288950CC7:0
[ThaliCore] VirtualSocket.init(inp,utStream:outputStream:) vsID:14 [3, 12, 14]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:14
,2017-10-12 14:11:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-10-12 14:11:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 14:11:26 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:11:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:6FC9BA8A-8B4B-4A24-A049-1C26C7D4A471
2017-10-12 14:11:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14,:,11:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:B3666918-5171-4C9E-8643-662288950CC7
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:52634
[ThaliCore] VirtualSocket.closeStr,eams() vsID:14
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket remo,ved, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] Session.disconnect() peer:B3666918-5171-4C9E-8643-662288950CC7:0
[ThaliCore] VirtualSocket.clo,seStreams() vsID:14
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.deinit peer:B3666918-5171-4C9E-8643-662288950CC7:0
2017-10-12 14:11:26 - DEBUG thaliMobileNativeWrap,per: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:11:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:11:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
[ThaliCore] VirtualSocket exited RunLoop vsID:14
,[ThaliCore] VirtualSocket.deinit vsID:14 [3, 12]
,[ThaliCore] BrowserRelay.deinit
,2017-10-12 14:11:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:11:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:11:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:11:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:11:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# initial peer discovery
,2017-10-12 14:11:27 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-10-12 14:11:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:11:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:11:28 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:11:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-10-12 14:11:28 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-10-12 14:11:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-10-12 14:11:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-10-12 14:11:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-10-12 14:11:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-10-12 14:11:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:11:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:11:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:11:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-10-12 14:11:28 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-10-12 14:11:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-10-12 14:11:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-10-12 14:11:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-10-12 14:11:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-10-12 14:11:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:11:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:11:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:11:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-10-12 14:11:29 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-10-12 14:11:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-10-12 14:11:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-10-12 14:11:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-10-12 14:11:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-10-12 14:11:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:11:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:11:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:11:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-10-12 14:11:29 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-10-12 14:11:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-10-12 14:11:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-10-12 14:11:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-10-12 14:11:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-10-12 14:11:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:11:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:11:29 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:11:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-10-12 14:11:29 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-10-12 14:11:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-10-12 14:11:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-10-12 14:11:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-10-12 14:11:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-10-12 14:11:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:11:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:11:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:11:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-10-12 14:11:30 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-10-12 14:11:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-10-12 14:11:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-10-12 14:11:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-10-12 14:11:30 - DEBUG createNativeListener: 'Creating Native Server'
2017-10-12 14:11:30 - DEBUG createNativeListener: 'listening 52637'
ok 151 Should throw
,# teardown
,2017-10-12 14:11:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-10-12 14:11:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-10-12 14:11:30 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-10-12 14:11:30 - DEBUG createNativeListener: 'Creating Native Server'
,2017-10-12 14:11:30 - DEBUG createNativeListener: 'listening 52639'
,2017-10-12 14:11:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-10-12 14:11:30 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 152 initial connection state should be CONNECTED
,2017-10-12 14:11:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 153 final connection state should be DISCONNECTED
,# teardown
,2017-10-12 14:11:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-10-12 14:11:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-10-12 14:11:31 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-10-12 14:11:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-10-12 14:11:31 - DEBUG createNativeListener: 'Creating Native Server'
2017-10-12 14:11:31 - DEBUG createNativeListener: 'listening 52642'
,2017-10-12 14:11:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-10-12 14:11:31 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-10-12 14:11:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-10-12 14:11:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 154 tried to connect to right port
,ok 155 failed due to refused connection
,ok 156 routerPortConnectionFailed is emitted
,# teardown
,2017-10-12 14:11:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-10-12 14:11:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-10-12 14:11:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-10-12 14:11:31 - DEBUG createNativeListener: 'Native Server - close'
2017-10-12 14:11:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-10-12 14:11:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-10-12 14:11:31 - DEBUG createNativeListener: 'Creating Native Server'
,2017-10-12 14:11:31 - DEBUG createNativeListener: 'listening 52646'
,2017-10-12 14:11:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-10-12 14:11:31 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-10-12 14:11:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-10-12 14:11:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 157 Send/recvd #1 should be equal length
,ok 158 Send/recvd #1 should be same
,ok 159 Send/recvd #2 should be equal length
,ok 160 Send/recvd #2 should be same
,ok 161 Should be exactly 2 client sockets
,# teardown
,2017-10-12 14:11:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-10-12 14:11:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-10-12 14:11:31 - DEBUG createNativeListener: 'Native Server - close'
2017-10-12 14:11:31, - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-10-12 14:11:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
2017-10-12 14:11:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-10-12 14:11:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,2017-10-12 14:11:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-10-12 14:11:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-10-12 14:11:32 - DEBUG createNativeListener: 'Creating Native Server'
,2017-10-12 14:11:32 - DEBUG createNativeListener: 'listening 52651'
,2017-10-12 14:11:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-10-12 14:11:32 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-10-12 14:11:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-10-12 14:11:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2017-10-12 14:11:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 162 socket shouldn't close until after stream
ok 163 incoming remains open
# teardown
,2017-10-12 14:11:32 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-10-12 14:11:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-10-12 14:11:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-10-12 14:11:32 - DEBUG createNativeListener: 'Native Server - close'
2017-10-12 14:11:32, - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-10-12 14:11:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-10-12 14:11:32 - DEBUG createNativeListener: 'Creating Native Server'
2017-10-12 14:11:32 - DEBUG createNativeListener: 'listening 52655'
,2017-10-12 14:11:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-10-12 14:11:32 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 164 we should not have gotten an error
,2017-10-12 14:11:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-10-12 14:11:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-10-12 14:11:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 165 socket shouldn't close until after incoming
ok 166 incoming is cleaned up
# teardown
,2017-10-12 14:11:32 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-10-12 14:11:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-10-12 14:11:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-10-12 14:11:32 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-10-12 14:11:32 - DEBUG createNativeListener: 'Creating Native Server'
,2017-10-12 14:11:32 - DEBUG createNativeListener: 'listening 52659'
,2017-10-12 14:11:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-10-12 14:11:32 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-10-12 14:11:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-10-12 14:11:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2017-10-12 14:11:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-10-12 14:11:32 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 167 stream was closed
,ok 168 incoming should survive
,ok 169 mux should have no streams
,# teardown
,2017-10-12 14:11:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-10-12 14:11:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-10-12 14:11:33 - DEBUG createNativeListener: 'Native Server - close'
2017-10-12 14:11:33 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'Creating Native Server'
2017-10-12 14:11:33 - DEBUG createNativeListener: 'listening 52663'
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-10-12 14:11:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 170 we should not have gotten an error
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 171 Buffers are identical
2017-10-12 14:11:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-10-12 14:11:33 - DEBUG createNativeListener: 'Native Server - close'
2017-10-12 14:11:33 - DEBUG createNativeListener: 'stream - mux stream, <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-10-12 14:11:33 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 172 native server is nulled out
ok 173 native server should be cl,osed
ok 174 incoming has been removed
ok 175 Incoming should be done
ok 176 The mux object should be closed
ok 177 The mux stream should be closed
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
2017-10-12 14:11:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-10-12 14:11:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'Creating Native Server'
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'listening 52667'
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
,2017-10-12 14:11:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
,2017-10-12 14:11:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'Native Server - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 178 native server is nulled out
ok 179 native server should be closed
ok 180 incoming has been removed
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-10-12 14:11:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-10-12 14:11:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-10-12 14:11:36 - DEBUG createNativeListener: 'Creating Native Server'
2017-10-12 14:11:36 - DEBUG createNativeListener: 'listening 52719'
,2017-10-12 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-10-12 14:11:36 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 181 we should not have gotten an error
,2017-10-12 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 182 Buffers are identical
2017-10-12 14:11:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-10-12 14:11:36 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client co,nnection <-> Mux - 0 - close'
,2017-10-12 14:11:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 183 server should be fine
ok 184 server should be open
ok 185 incoming has been removed
ok 186 The mux object should be clos,ed
ok 187 The mux stream should be closed
2017-10-12 14:11:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-10-12 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-10-12 14:11:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-10-12 14:11:37 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-10-12 14:11:39 - DEBUG createNativeListener: 'Creating Native Server'
,2017-10-12 14:11:39 - DEBUG createNativeListener: 'listening 52723'
,2017-10-12 14:11:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-10-12 14:11:39 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 188 we should not have gotten an error
,2017-10-12 14:11:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 189 Buffers are identical
,2017-10-12 14:11:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
2017-10-12 14:11:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to ,node - 0 - 0 - closed'
2017-10-12 14:11:39 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-10-12 14:11:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux, - 0 - close'
ok 190 server should be fine
ok 191 server should be open
ok 192 incoming has been removed
ok 193 The mux object should be closed
ok 194 The mux stream should be closed
,# teardown
,2017-10-12 14:11:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-10-12 14:11:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-10-12 14:11:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-10-12 14:11:39 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# can create servers manager
,ok 195 serversManager must not be null
,ok 196 serversManager must be an object
,# teardown
,# setup
,# calling stop without start causes error
,ok 197 We need to call start first
,# teardown
,# setup
,# can start/stop servers manager
,2017-10-12 14:11:40 - DEBUG createNativeListener: 'Creating Native Server'
2017-10-12 14:11:40 - DEBUG createNativeListener: 'listening 52726'
,ok 198 port must be in range
,# teardown
,2017-10-12 14:11:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-10-12 14:11:40 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-10-12 14:11:40 - DEBUG createNativeListener: 'Creating Native Server'
,2017-10-12 14:11:40 - DEBUG createNativeListener: 'listening 52727'
ok 199 second start should return same port
,# teardown
,2017-10-12 14:11:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-10-12 14:11:40 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-10-12 14:11:40 - DEBUG createNativeListener: 'Creating Native Server'
,2017-10-12 14:11:40 - DEBUG createNativeListener: 'listening 52729'
,2017-10-12 14:11:40 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-10-12 14:11:40 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 200 we should be connected
2017-10-12 14:11:40 - DEB,UG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 201 now we are disconnected
,2017-10-12 14:11:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-10-12 14:11:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-10-12 14:11:40 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-10-12 14:11:41 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
ok 202 Passed bogus id
2017-10-12 14:11:41 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
ok 203 Passed good id but bogus port
2017-10-12 14:11:41 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
ok 204 Passed right context
ok 205 Right server
ok 206 No error should be set
ok 207 Ret,ry should be false
ok 208 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 52731
,ok 209 should be equal
# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:11:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:11:41 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:11:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-10-12 14:11:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:11:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-10-12 14:11:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:11:41 - DEBUG thaliMobileNativeWrapper: 'Method disc,overyAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:11:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:11:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:11:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:11:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:11:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:11:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3014F9AF-1D13-40A2-81E5-517A999AD0EE", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:3014F9AF-1D13-40A2-81E5-517A999AD0EE
,2017-10-12 14:11:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 14:11:41 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:11:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 210 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:32744408-508E-49AB-B150-13D7858,EDCA4
[ThaliCore] Browser.startListening
2017-10-12 14:11:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-10-12 14:11:41 - INFO thaliMobile: 'Received state ({"discove,r,yActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:11:41 - INFO thaliMob,ile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 211 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7563EA47-7507-4979-92D8-1508550C9D7E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7563EA47-7507-4979-92D8-1508550C9D7E", generation: 0)
,2017-10-12 14:11:41 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"7563EA47-7507-4979-92D8-1508550C9D7E","generation":0}'
,2017-10-12 14:11:41 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 7563EA47-7507-4979-92D8-1508550C9D7E (syncValue: MoIWnhIMV4ihWq1oTCNjxjg93kx4lI2E)'
,2017-10-12 14:11:41 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7563EA47-7507-4979-92D8-1508550C9D7E", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7563EA47-7507-4979-92D8-1508550C9D7E", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7563EA47-7507-4979-92D8-1508550C9D7E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3014F9AF-1D13-40A2-81E5-517A999AD0EE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3014F9AF-1D13-40A2-81E5-517A999AD0EE", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DFD51C65-E602-49DB-BA9A-26A7B16A95DB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DFD51C65-E602-49DB-BA9A-26A7B16A95DB", generation: 0)
2017-10-12 14:11:43 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"DFD51C65-E602-49DB-BA9A-26A7B16A95DB","generation":0}'
2017-10-12 14:11:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 14:11:43 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:766863A9-E14B-4B2C-AC66-EEF3271F0561:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "766863A9-E14B-4B2C-AC66-EEF3271F0561", generation: 0)
2017-10-12 14:11:43 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"766863A9-E14B-4B2C-AC66-EEF3271F0561","generation":0}'
2017-10-12 14:11:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 14:11:43 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-10-12 14:11:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:7563EA47-7507-4979-92D8-1508550C9D7E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:7563EA47-7507-4979-92D8-1508550C9D7E:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "7563EA47-7507-4979-92D8-1508550C9D7E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,563EA47-7507-4979-92D8-1508550C9D7E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7563EA47-7507-4979-92D8-1508550C9D7E", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:7563EA47-7507-4979-92D8-1508550C9D7E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:7563EA47-7507-4979-92D8-1508550C9D7E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4DA2D295-F6F0-4264-8E65-79653B414127
[ThaliCore] Advertiser: session connected Peer(uuid: "3014F9AF-1D13-40A2-81E5-517A999AD0EE", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:4DA2D295-F6F0-4264-8E65-79653B414127 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:7563EA47-7507-4979-92D8-1508550C9D7E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:75,63EA47-7507-4979-92D8-1508550C9D7E:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "7563EA47-7507-4979-92D8-1508550C9D7E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,563EA47-7507-4979-92D8-1508550C9D7E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7563EA47-7507-4979-92D8-1508550C9D7E", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:7563EA47-7507-4979-92D8-1508550C9D7E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:7563EA47-7507-4979-92D8-1508550C9D7E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4DA2D295-F6F0-4264-8E65-79653B414127
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:7563EA47-7507-4979-92D8-1508550C9D7E:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "7563EA47-7507-4979-92D8-1508550C9D7E", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:64CB4EB8-66D5-4A95-B512-55DFC2DF3FF5
[ThaliCore] Session.session(_:peer:didChange:) peer:64CB4EB8-66D5-4A95-B512-55DFC2DF3FF5 state: notConnected -> connecting
[ThaliCore] Advertiser: session connected Peer(uuid: "3014F9AF-1D13-40A2-81E5-517A999AD0EE", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:4DA2D295-F6F0-4264-8E65-79653B414127 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:7563EA47-7507-4979-92D8-1508550C9D7E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:75,63EA47-7507-4979-92D8-1508550C9D7E:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "7563EA47-7507-4979-92D8-1508550C9D7E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,563EA47-7507-4979-92D8-1508550C9D7E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7563EA47-7507-4979-92D8-1508550C9D7E", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-10-12 14:11:49 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"MoIWnhIMV4ihWq1oTCNjxjg93kx4lI2E","error":"Peer is unavailable",,"portNumber":null}'
2017-10-12 14:11:49 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'MoIWnhIMV4ihWq1oTCNjxjg93kx4lI2E', error: 'Peer is unavailable', listeningPort: '%s''
,2017-10-12 14:11:49 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-10-12 14:11:49 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for DFD51C65-E602-49DB-BA9A-26A7B16A95DB (syncValue: NSIONwQZseRqdKvWpxrxZAP,vyzpZhnzf)'
2017-10-12 14:11:49 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "DFD51C65-E602-49DB-BA9A-26A7B16A95DB", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DFD51C65-E602-49DB-BA9A-26A7B16A95DB", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DFD51C65-E602-49DB-BA9A-26A7B,16A95DB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-10-12 14:11:49 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:7563EA47-7507-4979-92D8-1508550C9D7E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:DFD51C65-E602-49DB-BA9A-26A7B16A95DB:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:64CB4EB8-66D5-4A95-B512-55DFC2DF3FF5
,[ThaliCore] Session.session(_:peer:didChange:) peer:64CB4EB8-66D5-4A95-B512-55DFC2DF3FF5 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:DFD51C65-E602-49DB-BA9A-26A7B16A95DB:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:DFD51C65-E602-49DB-BA9A-26A7B16A95DB:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "DFD51C65-E602-49DB-BA9A-26A7B16A95DB", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52743
2017-10-12 14:11:52 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"NSIONwQZseRqdKvWpxrxZAPvyzpZhnzf",,"error":null,"portNumber":52743}'
2017-10-12 14:11:52 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'NSIONwQZseRqdKvWpxrxZAPvyzpZhnzf', error: 'null', listeningPort: '52743''
,ok 212 should be equal
2017-10-12 14:11:52 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 766863A9-E14B-4B2C-AC66-EEF3271F0561 (syncValue: vfk063MBDlqQUlkDF28yQBvdDXLpgHUw)'
2017-10-12 14:11:52 - DEBUG thaliMobileNativeTestUtils: 'Got 'mul,tiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "766863A9-E14B-4B2C-AC66-EEF3271F0561", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConn,ected:) Peer(uuid: "766863A9-E14B-4B2C-AC66-EEF3271F0561", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:766863A9-E14B-4B2C-AC66-EEF3271F0561:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocke,tTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:766863A9-E14B-4B2C-AC66-EEF3271F0561:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B3666918-5171-4C9E-8643-662288950CC7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B3666918-5171-4C9E-8643-662288950CC7", generation: 0)
2017-10-12 14:11:55 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B3666918-5171-4C9E-8643-662288950CC7","generation":0}'
2017-10-12 14:11:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 14:11:55 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:766863A9-E14B-4B2C-AC66-EEF3271F0561:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:766863A9-E14B-4B2C-AC66-EEF3271F0561:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "766863A9-E14B-4B2C-AC66-EEF3271F0561", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52747
2017-10-12 14:11:55 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"vfk063MBDlqQUlkDF28yQBvdDXLpgHUw",,"error":null,"portNumber":52747}'
2017-10-12 14:11:55 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'vfk063MBDlqQUlkDF28yQBvdDXLpgHUw', error: 'null', listeningPort: '52747''
,ok 213 should be equal
# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-10-12 14:11:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-10-12 14:11:55 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-10-12 14:11:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:3014F9AF-1D13-40A2-81E5-517A999AD0EE
,2017-10-12 14:11:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:11:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:DFD51C65-E602-49DB-BA9A-26A7B16A95DB
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:52743
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:DFD51C65-E602-49DB-BA9A-26A7B16A95DB:0
[ThaliCore] Session.session(_:peer:didChange:) peer:DFD51C65-E602-49DB-BA9A-26A7B16A95DB:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "DFD51C65-E602-49DB-BA9A-26A7B16A95DB", generation: 0)
,[ThaliCore] BrowserManager.disconnect peer:766863A9-E14B-4B2C-AC66-EEF3271F0561
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:52747
[ThaliCore] Session.disconnect() peer:766863A9-E14B-4B2C-AC66-EEF3271F0561:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:766863A9-E14B-4B2C-AC66-EEF3271F0561:0
[ThaliCore] BrowserRelay.deinit
,2017-10-12 14:11:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-10-12 14:11:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:11:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:11:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:11:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:11:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:11:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:11:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-10-12 14:11:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
2017-10-12 14:11:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"NSIONwQZseRqdKvWpxrxZAPvyzpZhnzf","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:DFD51C65-E602-49DB-BA9A-26A7B16A95DB:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:4DA2D295-F6F0-4264-8E65-79653B414127 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "3014F9AF-1D13-40A2-81E5-517A999AD0EE", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
,[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
,[ThaliCore] Session.disconnect() peer:64CB4EB8-66D5-4A95-B512-55DFC2DF3FF5
,[ThaliCore] Session.deinit peer:64CB4EB8-66D5-4A95-B512-55DFC2DF3FF5
[ThaliCore] AdvertiserRelay.deinit
,# Multiple local http requests
,listening on 52749
,ok 214 should be equal
,ok 215 should be equal
,ok 216 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:11:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:11:57 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:11:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-10-12 14:11:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:11:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-10-12 14:11:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:11:57 - DEBUG thaliMobileNativeWrapper: 'Method disc,overyAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:11:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:11:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-10-12 14:11:57 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-10-12 14:11:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-10-12 14:11:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-10-12 14:11:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2A40386E-2B01-46CD-87DA-781E0DD5ECDD", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:2A40386E-2B01-46CD-87DA-781E0DD5ECDD
2017-10-12 1,4:11:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 14:11:57 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:11:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 217 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:0AB1B968-D064-4A59-B55A-ED2E3F467D33
[Tha,liCore] Browser.startListening
2017-10-12 14:11:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-10-12 14:11:57 - INFO thaliMobile: 'Received state ({"discoveryActive":tr,ue,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:11:57 - INFO thaliMobile: 'Filte,red out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 218 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B3666918-5171-4C9E-8643-662288950CC7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B3666918-5171-4C9E-8643-662288950CC7", generation: 0)
2017-10-12 14:11:58 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B3666918-5171-4C9E-8643-662288950CC7","generation":0}'
2017-10-12 14:11:58 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B3666918-5171-4C9E-8643-662288950CC7, (syncValue: 9rwN01FTwHn38gZzbih6RTRs40MH6Xax)'
2017-10-12 14:11:58 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B3666918-5171-4C9E-8643-6622889,50CC7", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B3666918-5171-4C9E-8643-662288950CC7", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:) peer:B3666918-5171-4C9E-8643-662288950CC7:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:766863A9-E14B-4B2C-AC66-EEF3271F0561:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "766863A9-E14B-4B2C-AC66-EEF3271F0561,", generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-10-12 14:11:58 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailabl,e":true,"peerIdentifier":"766863A9-E14B-4B2C-AC66-EEF3271F0561","generation":0}'
2017-10-12 14:11:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 14:11:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DFD51C65-E602-49DB-BA9A-26A7B16A95DB:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DFD51C65-E602-49DB-BA9A-26A7B16A95DB", generation: 0)
2017-10-12 14:11:58 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"DFD51C65-E602-49DB-BA9A-26A7B16A95DB","generation":0}'
,2017-10-12 14:11:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 14:11:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:11:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:DFD51C65-E602-49DB-BA9A-26A7B16A95DB:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "DFD51C65-E602-49DB-BA9A-26A7B16A95DB", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:F53D4835-021E-4B75-99AB-2901B2A6C2E5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F53D4835-021E-4B75-99AB-2901B2A6C2E5", generation: 0)
2017-10-12 14:11:59 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAv,ailable":true,"peerIdentifier":"F53D4835-021E-4B75-99AB-2901B2A6C2E5","generation":0}'
2017-10-12 14:11:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 14:11:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-1,0-12 14:11:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:899195D7-975F-4830-8A7A-ABF48513F94C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "899195D7-975F-4830-8A7A-ABF48513F94C", generation: 0)
2017-10-12 14:11:59 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"899195D7-975F-4830-8A7A-ABF48513F94C","generation":0}'
2017-10-12 14:11:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 14:11:59 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-10-12 14:11:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 14:11:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:2A40386E-2B01-46CD-87DA-781E0DD5ECDD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2A40386E-2B01-46CD-87DA-781E0DD5ECDD", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B3666918-5171-4C9E-8643-662288950CC7:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B3,666918-5171-4C9E-8643-662288950CC7:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "B3666918-5171-4C9E-8643-662288950CC7", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,3666918-5171-4C9E-8643-662288950CC7", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B3666918-5171-4C9E-8643-662288950CC7", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B3666918-5171-4C9E-8643-662288950CC7:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B3666918-5171-4C9E-8643-662288950CC7:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B3666918-5171-4C9E-8643-662288950CC7:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B3,666918-5171-4C9E-8643-662288950CC7:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "B3666918-5171-4C9E-8643-662288950CC7", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,3666918-5171-4C9E-8643-662288950CC7", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B3666918-5171-4C9E-8643-662288950CC7", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B3666918-5171-4C9E-8643-662288950CC7:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B3666918-5171-4C9E-8643-662288950CC7:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B3666918-5171-4C9E-8643-662288950CC7:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B3666918-5171-4C9E-8643-662288950CC7", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B3666918-5171-4C9E-8643-662288950CC7:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B3,666918-5171-4C9E-8643-662288950CC7:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "B3666918-5171-4C9E-8643-662288950CC7", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,3666918-5171-4C9E-8643-662288950CC7", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B3666918-5171-4C9E-8643-662288950CC7", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-10-12 14:12:06 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9rwN01FTwHn38gZzbih6RTRs40MH6Xax","error":"Peer is unavailable",,"portNumber":null}'
2017-10-12 14:12:06 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '9rwN01FTwHn38gZzbih6RTRs40MH6Xax', error: 'Peer is unavailable', listeningPort: '%s''
,2017-10-12 14:12:06 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-10-12 14:12:06 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 766863A9-E14B-4B2C-AC66-EEF3271F0561 (syncValue: s1DedOhTuxKM1UTrXypuedJ,i9Dxj36nx)'
2017-10-12 14:12:06 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "766863A9-E14B-4B2C-AC66-EEF3271F0561", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "766863A9-E14B-4B2C-AC66-EEF3271F0561", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:766863A9-E14B-4B2C-AC66-EEF32,71F0561:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-10-12 14:12:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-12 ,1,4:12:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:B3666918-5171-4C9E-8643-662288950CC7:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B772FC20-08B9-4154-9EA0-BECA2A84867F
[ThaliCore] Advertiser: session connected Peer(uuid: "2A40386E-2B01-46CD-87DA-781E0DD5ECDD", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:B772FC20-08B9-4154-9EA0-BECA2A84867F state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:766863A9-E14B-4B2C-AC66-EEF3271F0561:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:76,6863A9-E14B-4B2C-AC66-EEF3271F0561:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "766863A9-E14B-4B2C-AC66-EEF3271F0561", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,66863A9-E14B-4B2C-AC66-EEF3271F0561", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "766863A9-E14B-4B2C-AC66-EEF3271F0561", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:766863A9-E14B-4B2C-AC66-EEF3271F0561:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:766863A9-E14B-4B2C-AC66-EEF3271F0561:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:22114238-337B-4DEA-B3CE-8BD17D02606B
[ThaliCore] Advertiser: session connected Peer(uuid: "2A40386E-2B01-46CD-87DA-781E0DD5ECDD", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:22114238-337B-4DEA-B3CE-8BD17D02606B state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B772FC20-08B9-4154-9EA0-BECA2A84867F
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:766863A9-E14B-4B2C-AC66-EEF3271F0561:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "766863A9-E14B-4B2C-AC66-EEF3271F0561", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:766863A9-E14B-4B2C-AC66-EEF3271F0561:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "766863A9-E14B-4B2C-AC66-EEF3271F0561", generation: 0)
,2017-10-12 14:12:10 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"766863A9-E14B-4B2C-AC66-EEF3271F0561","generation":0}'
,2017-10-12 14:12:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:12:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-12 14:12:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:B772FC20-08B9-4154-9EA0-BECA2A84867F state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:766863A9-E14B-4B2C-AC66-EEF3271F0561:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:76,6863A9-E14B-4B2C-AC66-EEF3271F0561:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "766863A9-E14B-4B2C-AC66-EEF3271F0561", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,66863A9-E14B-4B2C-AC66-EEF3271F0561", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "766863A9-E14B-4B2C-AC66-EEF3271F0561", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:766863A9-E14B-4B2C-AC66-EEF3271F0561:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:766863A9-E14B-4B2C-AC66-EEF3271F0561:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:22114238-337B-4DEA-B3CE-8BD17D02606B
,[ThaliCore] Session.session(_:peer:didChange:) peer:22114238-337B-4DEA-B3CE-8BD17D02606B state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:766863A9-E14B-4B2C-AC66-EEF3271F0561:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:76,6863A9-E14B-4B2C-AC66-EEF3271F0561:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "766863A9-E14B-4B2C-AC66-EEF3271F0561", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,66863A9-E14B-4B2C-AC66-EEF3271F0561", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "766863A9-E14B-4B2C-AC66-EEF3271F0561", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:766863A9-E14B-4B2C-AC66-EEF3271F0561:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:766863A9-E14B-4B2C-AC66-EEF3271F0561:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:766863A9-E14B-4B2C-AC66-EEF3271F0561:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:76,6863A9-E14B-4B2C-AC66-EEF3271F0561:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "766863A9-E14B-4B2C-AC66-EEF3271F0561", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:766863A9,-E14B-4B2C-AC66-EEF3271F0561 error: max retries exceeded
2017-10-12 14:12:16 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"s1DedOhTuxKM1UTrXypuedJi9Dxj36nx","error":"Connection could not be established","portNumber":null}'
2017-1,0-12 14:12:16 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 's1DedOhTuxKM1UTrXypuedJi9Dxj36nx', error: 'Connection could not be established', listeningPort: '%s''
,2017-10-12 14:12:16 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-10-12 14:12:16 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F53D4835-021E-4B75-99AB-2901B2A6C2E5 (syncValue: SSPWs1d,0BAJ7dvWYGuT2Zulyd9AwN8KF)'
2017-10-12 14:12:16 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F53D4835-021E-4B75-99AB-2901B2A6C2E5", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F53D4835-021E-4B75-99AB-2901B2A6C2E5", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F53D4835-021E,-4B75-99AB-2901B2A6C2E5:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-10-12 14:12:16 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-10-12 14:12:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:766863A9-E14B-4B2C-AC66-EEF3271F0561:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:F53D4835-021E-4B75-99AB-2901B2A6C2E5:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F53D4835-021E-4B75-99AB-2901B2A6C2E5:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:F53D4835-021E-4B75-99AB-2901B2A6C2E5:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "F53D4835-021E-4B75-99AB-2901B2A6C2E5", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52771
,2017-10-12 14:12:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"SSPWs1d0BAJ7dvWYGuT2Zulyd9AwN8KF","error":null,"portNumber":52771}'
,2017-10-12 14:12:19 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'SSPWs1d0BAJ7dvWYGuT2Zulyd9AwN8KF', error: 'null', listeningPort: '52771''
,ok 219 should be equal
,ok 220 should be equal
ok 221 should be equal
,2017-10-12 14:12:19 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 899195D7-975F-4830-8A7A-ABF48513F94C (syncValue: p2fBHGZrLKjLhtxzKkUvUbE17KnmoZkM)'
,2017-10-12 14:12:19 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "899195D7-975F-4830-8A7A-ABF48513F94C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "89,9195D7-975F-4830-8A7A-ABF48513F94C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:899195D7-975F-4830-8A7A-ABF48513F94C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-10-12 14:12:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:766863A9-E14B-4B2C-AC66-EEF3271F0561:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "766863A9-E14B-4B2C-AC66-EEF3271F0561", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:899195D7-975F-4830-8A7A-ABF48513F94C:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:899195D7-975F-4830-8A7A-ABF48513F94C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:899195D7-975F-4830-8A7A-ABF48513F94C:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "899195D7-975F-4830-8A7A-ABF48513F94C", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52777
2017-10-12 14:12:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"p2fBHGZrLKjLhtxzKkUvUbE17KnmoZkM",,"error":null,"portNumber":52777}'
2017-10-12 14:12:22 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'p2fBHGZrLKjLhtxzKkUvUbE17KnmoZkM', error: 'null', listeningPort: '52777''
,ok 222 should be equal
ok 223 should be equal
ok 224 should be equal
# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-10-12 14:12:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-12 ,14:12:22 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-10-12 14:12:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:2A40386E-2B01-46CD-87DA-7,81E0DD5ECDD
2017-10-12 14:12:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:F53D4835-021E-4B75-99AB-2901B2A6C2E5
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCo,re] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:52771
[ThaliCore] Session.disconnect() peer:F53D4835-021E-4B75-99AB-2901B2A6C2E5:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B772FC20-08B9-4154-9EA0-BECA2A84867F state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "2A40386E-2B01-46CD-87DA-781E0DD5ECDD", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:22114238-337B-4DEA-B3CE-8BD17D02606B
,[ThaliCore] Session.deinit peer:F53D4835-021E-4B75-99AB-2901B2A6C2E5:0
[ThaliCore] BrowserRelay.deinit
[ThaliCore] BrowserManager.disconnect peer:899195D7-975F-4830-8A7A-ABF48513F94C
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCP,Listener.stopListeningForConnectionsAndDisconnectClients() port:52777
[ThaliCore] Session.disconnect() peer:899195D7-975F-4830-8A7A-ABF48513F94C:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListen,er.deinit
,[ThaliCore] Session.deinit peer:22114238-337B-4DEA-B3CE-8BD17D02606B
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:899195D7-975F-4830-8A7A-ABF48513F94C:0
,[ThaliCore] BrowserRelay.deinit
,2017-10-12 14:12:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-10-12 14:12:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:12:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:12:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:12:22 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:12:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:12:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:12:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startListeningForAdvertisements should fail if start not called
,ok 225 specific error should be returned
,# teardown
,ok 226 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:12:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:23 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:12:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-10-12 14:12:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:12:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:12:23 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-10-12 14:12:23 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-10-12 14:12:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-10-12 14:12:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-10-12 14:12:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 227 specific error should be returned
,# teardown
,ok 228 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:12:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:23 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:12:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-10-12 14:12:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:12:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:12:23 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-10-12 14:12:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-10-12 14:12:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-10-12 14:12:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-10-12 14:12:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopListeningForAdvertisements many times
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'listening 52781'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 229 no errors
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 230 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 231 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:12:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startListeningForAdvertisements many times
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'listening 52782'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:00273704-39BB-4202-B8EE-E44C613EDB1A
[ThaliCore] Browser.startListening
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-10-12 14:12:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-10-12 14:12:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 232 no errors
,[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-10-12 14:12:24 - INFO thaliMobile: 'Received, state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-10-12 14:12:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 233 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-10-12 14:12:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-10-12 14:12:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 234 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:12:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:12:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'listening 52783'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7A4A0766-8038-45ED-9972-36C04A183B61", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:7A4A0766-8038-45ED-9972-36C04A183B61
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-10-12 14:12:25 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-10-12 14:12:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 235 no errors
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7A4A0766-8038-45ED-9972-36C04A183B61", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:7A4A0766-8038-45ED-9972-36C04A183B61
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-10-12 14:12:25 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-10-12 14:12:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 236 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:7A4A0766-8038-45ED-9972-36C04A183B61
,[ThaliCore] Advertiser.stopAdvertising() peerID:7A4A0766-8038-45ED-9972-36C04A183B61
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 237 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:12:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopAdvertisingAndListening many times
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'listening 52786'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingAct,ive":false}'
2017-10-12 14:12:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 238 no errors
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'discover,yAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 239 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:25 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-10-12 14:12:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 240 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonT,CP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:12:25 - DEBUG thaliMobi,leNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:12:25 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-10-12 14:12:25 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:12:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can get the network status before starting
,ok 241 network status should have certain non-empty properties
,# teardown
,ok 242 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:26 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-10-12 14:12:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:12:26 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-10-12 14:12:26 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# error returned with bad router
,2017-10-12 14:12:26 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
,ok 243 specific error expected
,# teardown
,ok 244 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:26 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:12:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are started when we call start
,2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'listening 52787'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C5963328-E90E-4974-A72B-90E344029611
,[ThaliCore] Browser.startListening
,2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-10-12 14:12:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-10-12 14:12:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5E16293B-6A7F-4B7E-9583-9134A48938BE", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:5E16293B-6A7F-4B7E-9583-9134A48938BE
,2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-10-12 14:12:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:12:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 245 all connection succeed
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:5E16293B-6A7F-4B7E-9583-9134A48938BE
,2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-10-12 14:12:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-10-12 14:12:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12, 14:12:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-10-12 14:12:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 246 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:26 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:12:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:12:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# TCP Servers Manager should be null when we call start on iOS
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'listening 52790'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B8DC6E78-1780-4EFC-BEF3-B69892688419
[ThaliCore] Browser.st,artListening
2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-10-12 14:12:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:12:27 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CA2888F4-6D79-479A-9F9F-B13F19586D3A", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,CA2888F4-6D79-479A-9F9F-B13F19586D3A
2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-10-12 14:12:27 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:12:27 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 247 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F53D4835-021E-4B75-99AB-2901B2A6C2E5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F53D4835-021E-4B75-99AB-2901B2A6C2E5", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:899195D7-975F-4830-8A7A-ABF48513F94C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "899195D7-975F-4830-8A7A-ABF48513F94C", generation: 0)
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F53D4835-021E-4B75-99AB-2901B2A6C2E5","generation":0}]'
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"F53D4835-021E-4B75-99AB-2901B2A6C2E5","generation":0}'
2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'Rece,ived peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"899195D7-975F-4830-8A7A-ABF48513F94C","generation":0}]'
2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"pe,erAvailable":true,"peerIdentifier":"899195D7-975F-4830-8A7A-ABF48513F94C","generation":0}'
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"F53D4835-021E-4B75-99AB-2901B2A6C2E5","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-10-12 14:12:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"F53D4835-021E-4B75-99AB-2901B2A6C2E5","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"899195D7-975F-4830-8A7A-ABF48513F94C","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-10-12 14:12:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"899195D7-975F-4830-8A7A-ABF48513F94C","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:CA2888F4-6D79-479A-9F9F-B13F19586D3A
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-10-12 14:12:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-10-12 14:12:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 248 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:12:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are stopped when we call stop
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'listening 52792'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:392191B8-5ECC-42C4-AA8F-105FF3E38F0D
[ThaliCore] Browser.st,artListening
2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-10-12 14:12:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-10-12 14:12:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "436ED50C-8FD,8-4BC3-BFCA-EA9BB30E7B43", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:436ED50C-8FD8-4BC3-BFCA-EA9BB30E7B43
2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adve,rtisingActive":true}'
2017-10-12 14:12:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"ro,u,ter":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:12:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising(), peerID:436ED50C-8FD8-4BC3-BFCA-EA9BB30E7B43
2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-10-12 14:12:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-10-12 14:12:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-10-12 14:12:27 - DEBUG thaliMobileNativeW,rapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-10-12 14:12:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 249 is stopped after calling stop
,ok 250 connection should fail after stopping
,# teardown
,ok 251 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:12:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:12:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is properly hooked up
,2017-10-12 14:12:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
,# teardown
,ok 252 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:12:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:28 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:12:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-10-12 14:12:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:12:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:12:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-10-12 14:12:28 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-10-12 14:12:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-10-12 14:12:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-10-12 14:12:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is return error if we get called on iOS
,ok 253 error description matches
,# teardown
,ok 254 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:12:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:28 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:12:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-10-12 14:12:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:12:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:12:28 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-10-12 14:12:29 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-10-12 14:12:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-10-12 14:12:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-10-12 14:12:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is properly hooked up
,2017-10-12 14:12:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 255 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:12:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:29 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:12:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-10-12 14:12:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:12:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:12:29 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-10-12 14:12:29 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-10-12 14:12:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-10-12 14:12:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-10-12 14:12:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is return error if we get called on iOS
,ok 256 error description matches
,# teardown
,ok 257 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:12:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:30 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:12:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-10-12 14:12:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:12:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:12:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-10-12 14:12:30 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-10-12 14:12:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-10-12 14:12:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-10-12 14:12:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure we actually call kill connections properly
,ok 258 IMPLEMENT ME!!!!!!
,# teardown
,ok 259 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:12:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:30 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:12:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-10-12 14:12:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:12:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:12:30 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-10-12 14:12:30 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-10-12 14:12:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-10-12 14:12:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-10-12 14:12:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-10-12 14:12:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 260 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:31 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-10-12 14:12:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:12:31 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-10-12 14:12:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-10-12 14:12:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 261 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:31 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:12:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-10-12 14:12:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 262 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:31 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:12:31 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-10-12 14:12:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-10-12 14:12:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 263 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:31 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:12:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:12:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 264 NOT IMPLEMENTED # SKIP
,# teardown
,ok 265 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:32 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:12:32 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-10-12 14:12:32 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure bad PSK connections fail
,2017-10-12 14:12:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 266 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:32 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-10-12 14:12:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:12:32 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-10-12 14:12:32 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peer changes handled from a queue
,2017-10-12 14:12:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 267 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:32 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-10-12 14:12:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:12:32 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-10-12 14:12:32 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-10-12 14:12:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-10-12 14:12:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 268 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:33 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-10-12 14:12:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:12:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-10-12 14:12:33 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 269 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:33 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:12:33 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-10-12 14:12:33 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'listening 52795'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4DC6E0A6-6306-4373-BB42-81CAC834D558
[ThaliCore] Browser.st,artListening
2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-10-12 14:12:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:12:33 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
ok 270 discoveryActive matches
ok 271 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonT,C,P: {"discoveryActive":true,"advertisingActive":false}'
2017-10-12 14:12:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkT,ype":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:12:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisemen,ts()
[ThaliCore] Browser.stopListening()
2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:33 - INFO thaliMobile: 'Filtered out discoveryAd,vertisingStateUpdate (was in stopped state).'
ok 272 discoveryActive matches
ok 273 advertisingActive matches
2017-10-12 14:12:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'listening 52796'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6D00CA81-D6DA-4825-9876-ED698EBA583C", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:6D00CA81-D6DA-4825-9876-ED698EBA583C
2017-10-12 1,4:12:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-10-12 14:12:33 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-10-12 14:12:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 274 discoveryActive matches
,ok 275 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:6D00CA81-D6DA-4825-9876-ED698EBA583C
2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateN,onTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 276 discoveryActive matches
,ok 277 advertisingActive matches
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14,:12:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-10-12 14:12:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-10-12 14:12:33 - DEBUG thaliMobileNativeWrapper: 'listening 52798'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:12:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:12:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-10-12 14:12:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 278 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:12:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdate,NonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:12:34 - DEBUG thali,MobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:34 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:12:34 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:12:34 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:12:34 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:12:34 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:12:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:12:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS
,2017-10-12 14:12:34 - DEBUG thaliMobileNativeWrapper: 'listening 52799'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A738BB45-2969-4FAA-ABC7-F8F5962D20FB
[ThaliCore] Browser.st,artListening
2017-10-12 14:12:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-10-12 14:12:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:12:34 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "59B3AA1A-9B47-4CE6-8EC7-1A9CAA535F0D", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,59B3AA1A-9B47-4CE6-8EC7-1A9CAA535F0D
2017-10-12 14:12:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-10-12 14:12:34 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:12:34 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:899195D7-975F-4830-8A7A-ABF48513F94C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "899195D7-975F-4830-8A7A-ABF48513F94C", generation: 0)
2017-10-12 14:12:35 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"899195D7-975F-4830-8A7A-ABF48513F94C","generation":0}]'
,2017-10-12 14:12:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"899195D7-975F-4830-8A7A-ABF48513F94C","generation":0}'
,2017-10-12 14:12:35 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"899195D7-975F-4830-8A7A-ABF48513F94C","peerAvailable":true,"generation":0,"portNumber":null}'
,ok 279 portNumber equal null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:59B3AA1A-9B47-4CE6-8EC7-1A9CAA535F0D
,2017-10-12 14:12:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-10-12 14:12:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-10-12 14:12:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-10-12 14:12:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-12 14:12:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 280 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:12:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:12:35 - DEBUG thaliMobi,leNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:12:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:12:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:12:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:12:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-10-12 14:12:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:12:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:12:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:12:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests between peers
,2017-10-12 14:12:36 - DEBUG thaliMobileNativeWrapper: 'listening 52801'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3EC027BB-FE08-4A57-AA94-BE6D3AB678D0
[ThaliCore] Browser.st,artListening
,2017-10-12 14:12:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-10-12 14:12:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-10-12 14:12:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "ABD6CB4A-6271-425B-A46F-AF3661BD6BDF", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:ABD6CB4A-6271-425B-A46F-AF3661BD6BDF
2017-10-12 1,4:12:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-10-12 14:12:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-10-12 14:12:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:76CF7764-5163-4F9C-84F2-74BED114CDC9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "76CF7764-5163-4F9C-84F2-74BED114CDC9", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:899195D7-975F-4830-8A7A-ABF48513F94C:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "899195D7-975F-4830-8A7A-ABF48513F94C", generation: 0)
,2017-10-12 14:12:37 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651","generation":0}]'
,2017-10-12 14:12:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651","generation":0}'
,2017-10-12 14:12:37 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"76CF7764-5163-4F9C-84F2-74BED114CDC9","generation":0}]'
,2017-10-12 14:12:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"76CF7764-5163-4F9C-84F2-74BED114CDC9","generation":0}'
,2017-10-12 14:12:37 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"899195D7-975F-4830-8A7A-ABF48513F94C","generation":0}]'
,2017-10-12 14:12:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"899195D7-975F-4830-8A7A-ABF48513F94C","generation":0}'
,2017-10-12 14:12:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-10-12 14:12:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-10-12 14:12:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-10-12 14:12:37 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651 (syncValue: iHEkKvGTbb67iPDZjK7aiQUiuNgZ86Cl)'
,2017-10-12 14:12:37 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-10-12 14:12:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"76CF7764-5163-4F9C-84F2-74BED114CDC9","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-10-12 14:12:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"76CF7764-5163-4F9C-84F2-74BED114CDC9","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-10-12 14:12:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"76CF7764-5163-4F9C-84F2-74BED114CDC9","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-10-12 14:12:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"899195D7-975F-4830-8A7A-ABF48513F94C","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-10-12 14:12:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"899195D7-975F-4830-8A7A-ABF48513F94C","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:76CF7764-5163-4F9C-84F2-74BED114CDC9:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "76CF7764-5163-4F9C-84F2-74BED114CDC9", generation: 0)
2017-10-12 14:12:38 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"76CF7764-5163-4F9C-84F2-74BED114CDC9","generation":0}]'
2017-10-12 14:12:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"76CF7764-5163-4F9C-84F2-74BED114CDC9","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F773DE60-18A4-400C-8204-9798A9B73E46:0
[ThaliCore] BrowserManager.foundPeerHandle,r peer:Peer(uuid: "F773DE60-18A4-400C-8204-9798A9B73E46", generation: 0)
2017-10-12 14:12:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"76CF7764-5163-4F9C-84F2-74BED114CDC9","peerAvailable":false,"generation":n,u,ll,"portNumber":null}'
2017-10-12 14:12:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"76CF7764-5163-4F9C-84F2-74BED114CDC9","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":nul,l}'
2017-10-12 14:12:38 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F773DE60-18A4-400C-8204-9798A9B73E46","generation":0}]'
2017-10-12 14:12:38 - DEBUG thaliMobileNa,tiveWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"F773DE60-18A4-400C-8204-9798A9B73E46","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:81780A6B-66B6-4FF1-8B15-F2911,B9E5A76:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "81780A6B-66B6-4FF1-8B15-F2911B9E5A76", generation: 0)
2017-10-12 14:12:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"F773DE60-18A4,-,400C-8204-9798A9B73E46","peerAvailable":true,"generation":0,"portNumber":null}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ABD6CB4A-6271-425B-A46F-AF3661BD6BDF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ABD,6CB4A-6271-425B-A46F-AF3661BD6BDF", generation: 0)
2017-10-12 14:12:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"F773DE60-18A4-400C-8204-9798A9B73E46","connectionType":"MPCF","peerAvailable":true,"generation,":0,"newAddressPort":false}'
,2017-10-12 14:12:38 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"F773DE60-18A4-400C-8204-9798A9B73E46","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-10-12 14:12:38 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"81780A6B-66B6-4FF1-8B15-F2911B9E5A76","generation":0}]'
,2017-10-12 14:12:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"81780A6B-66B6-4FF1-8B15-F2911B9E5A76","generation":0}'
,2017-10-12 14:12:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"81780A6B-66B6-4FF1-8B15-F2911B9E5A76","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-10-12 14:12:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"81780A6B-66B6-4FF1-8B15-F2911B9E5A76","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-10-12 14:12:38 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"81780A6B-66B6-4FF1-8B15-F2911B9E5A76","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:76CF7764-5163-4F9C-84F2-74BED114CDC9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "76CF7764-5163-4F9C-84F2-74BED114CDC9", generation: 0)
2017-10-12 14:12:38 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"76CF7764-5163-4F9C-84F2-74BED114CDC9","generation":0}]'
2017-10-12 14:12:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"76CF7764-5163-4F9C-84F2-74BED114CDC9","generation":0}'
,2017-10-12 14:12:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"76CF7764-5163-4F9C-84F2-74BED114CDC9","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-10-12 14:12:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"76CF7764-5163-4F9C-84F2-74BED114CDC9","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-10-12 14:12:38 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"76CF7764-5163-4F9C-84F2-74BED114CDC9","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:76CF7764-5163-4F9C-84F2-74BED114CDC9:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "76CF7764-5163-4F9C-84F2-74BED114CDC9", generation: 0)
2017-10-12 14:12:39 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"76CF7764-5163-4F9C-84F2-74BED114CDC9","generation":0}]'
2017-10-12 14:12:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"76CF7764-5163-4F9C-84F2-74BED114CDC9","generation":0}'
,2017-10-12 14:12:39 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"76CF7764-5163-4F9C-84F2-74BED114CDC9","peerAvailable":false,"generation":null,"portNumber":null}'
2017-10-12 14:12:39 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"76CF7764-5163-4F9C-84F2-74BED114CDC9","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,A8ACC72-CBD4-4A4C-ACF7-A8702F78F651", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5A,8ACC72-CBD4-4A4C-ACF7-A8702F78F651:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,A8ACC72-CBD4-4A4C-ACF7-A8702F78F651", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:899195D7-975F-4830-8A7A-ABF48513F94C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "899195D7-975F-4830-8A7A-ABF48513F94C", generation: 0)
2017-10-12 14:12:42 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"899195D7-975F-4830-8A7A-ABF48513F94C","generation":0}]'
2017-10-12 14:12:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"899195D7-975F-4830-8A7A-ABF48513F94C","generation":0}'
,2017-10-12 14:12:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"899195D7-975F-4830-8A7A-ABF48513F94C","peerAvailable":false,"generation":null,"portNumber":null}'
2017-10-12 14:12:42 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"899195D7-975F-4830-8A7A-ABF48513F94C","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651", generation: 0)
2017-10-12 14:12:43 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651","generation":0}]'
2017-10-12 14:12:43 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651","generation":0}'
,2017-10-12 14:12:43 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651","peerAvailable":false,"generation":null,"portNumber":null}'
2017-10-12 14:12:43 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5A,8ACC72-CBD4-4A4C-ACF7-A8702F78F651:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:5A8ACC72,-CBD4-4A4C-ACF7-A8702F78F651 error: peer is unavailable
2017-10-12 14:12:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"iHEkKvGTbb67iPDZjK7aiQUiuNgZ86Cl","error":"Peer is unavailable","portNumber":null}'
2017-10-12 14:12:45 - D,EBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'iHEkKvGTbb67iPDZjK7aiQUiuNgZ86Cl', error: 'Peer is unavailable', listeningPort: '%s''
,2017-10-12 14:12:45 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-10-12 14:12:45 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F773DE60-18A4-400C-8204-9798A9B73E46 (syncValue: UpmtBNqeUqSfQx53zDsot8G,SjXsAkpkL)'
2017-10-12 14:12:45 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F773DE60-18A4-400C-8204-9798A9B73E46", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F773DE60-18A4-400C-8204-9798A9B73E46", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F773DE60-18A4-400C-8204-9798A,9B73E46:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5A8ACC72-CBD4-4A4C-ACF7-A8702F78F651:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:F773DE60-18A4-400C-8204-9798A9B73E46:0 state: notConnected -> connecting
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:35C81906-6548-4B44-8317-0C0DE5CB1B6B
[ThaliCore] Advertiser: session connected Peer(uuid: "ABD6CB4A-6271-425B-A46F-AF3661BD6BDF", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:35C81906-6548-4B44-8317-0C0DE5CB1B6B state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F773DE60-18A4-400C-8204-9798A9B73E46:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:F773DE60-18A4-400C-8204-9798A9B73E46:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "F773DE60-18A4-400C-8204-9798A9B73E46", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52807
2017-10-12 14:12:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"UpmtBNqeUqSfQx53zDsot8GSjXsAkpkL",,"error":null,"portNumber":52807}'
2017-10-12 14:12:48 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'UpmtBNqeUqSfQx53zDsot8GSjXsAkpkL', error: 'null', listeningPort: '52807''
,2017-10-12 14:12:48 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F773DE60-18A4-400C-8204-9798A9B73E46:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F773DE60-18A4-400C-8204-9798A9B73E46:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [3, 12, 15]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:15
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:116 count:1 vsID:15
,[ThaliCore] VirtualSocket.writePendingData() to write:116 written:116 count:0 vsID:15
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:15
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 93 vsID:15
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:179 count:1 vsID:15
[ThaliCore] VirtualSocket.writePendingData() to write:179 written:179 count:0 vsID:15
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:15
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 266 vsID:15
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:117 count:1 vsID:15
[ThaliCore] VirtualSocket.writePendingData() to write:117 written:117 count:0 vsID:15
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:15
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 261 vsID:15
,2017-10-12 14:12:48 - DEBUG testUtils: 'Got response data'
2017-10-12 14:12:48 - DEBUG testUtils: 'Got end'
ok 281 response body should match testData
ok 282 must be started
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:35C81906-6548-4B44-8317-0C0DE5CB1B6B
,[ThaliCore] Session.session(_:peer:didChange:) peer:35C81906-6548-4B44-8317-0C0DE5CB1B6B state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:35C81906-6548-4B44-8317-0C0DE5CB1B6B
[ThaliCore] Session.startOutputStream(with:) peer:35C81906-6548-4B44-8317-0C0DE5CB1B6B
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [3, 12, 15, 16]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 116 vsID:16
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:16
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:93 count:1 vsID:16
[ThaliCore] VirtualSocket.writePendingData() to write:93 written:93 count:0 vsID:16
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:16
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 179 vsID:16
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:266 count:1 vsID:16
[ThaliCore] VirtualSocket.writePendingData() to write:266 written:266 count:0 vsID:16
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:16
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 117 vsID:16
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:261 count:1 vsID:16
,[ThaliCore] VirtualSocket.writePendingData() to write:261 written:261 count:0 vsID:16
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:16
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:ABD6CB4A-6271-425B-A46F-AF3661BD6BDF
2017-10-12 14:12:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-10-12 14:12:57 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:12:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
2017-10-12 14:12:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:57 - INFO thaliMobile: 'Filtered out discoveryAdvertis,ingStateUpdate (was in stopped state).'
2017-10-12 14:12:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 283 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:12:57 - DEBUG thaliMobileNativeWrap,per: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising,()
2017-10-12 14:12:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:12:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped s,t,ate).'
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCo,re] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:16
[ThaliCore] VirtualSocket.closeStreams() vsID:16
[ThaliCore] BrowserManager.disconnect peer:,F773DE60-18A4-400C-8204-9798A9B73E46
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:52807
[ThaliCore] VirtualSocket.closeStreams() vsID:15
[ThaliCore] TCPListener.soc,ketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didS,ocketDisconnectHandler
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:16
[ThaliCore] VirtualSocket.deinit vsID:16 [3, 12, 15]
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] VirtualSocket exited RunLoop vsID:15
[ThaliCore] Session.disconnect() peer:F773DE60-18A4-400C-8204-9798A9B73E46:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:15
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:15 [3, 12]
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:F773DE60-18A4-400C-8204-9798A9B73E46:0
[ThaliCore] BrowserRelay.deinit
,2017-10-12 14:12:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:12:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:12:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:35C81906-6548-4B44-8317-0C0DE5CB1B6B state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "ABD6CB4A-6271-425B-A46F-AF3661BD6BDF", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
,[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:35C81906-6548-4B44-8317-0C0DE5CB1B6B
,2017-10-12 14:12:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:12:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-10-12 14:12:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-10-12 14:12:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-10-12 14:12:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:35C81906-6548-4B44-8317-0C0DE5CB1B6B
,# can still do HTTP requests between peers with coordinator
,2017-10-12 14:12:58 - DEBUG thaliMobileNativeWrapper: 'listening 52810'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E3E6800D-080B-4126-8D61-32FBECFAD95D
[ThaliCore] Browser.st,artListening
2017-10-12 14:12:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-10-12 14:12:58 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:12:58 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F4118EDF-60F4-42F0-BF43-5EB5C47044EE", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,F4118EDF-60F4-42F0-BF43-5EB5C47044EE
2017-10-12 14:12:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-10-12 14:12:58 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:12:58 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:81780A6B-66B6-4FF1-8B15-F2911B9E5A76:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "81780A6B-66B6-4FF1-8B15-F2911B9E5A76", generation: 0)
2017-10-12 14:12:59 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"81780A6B-66B6-4FF1-8B15-F2911B9E5A76","generation":0}]'
2017-10-12 14:12:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"81780A6B-66B6-4FF1-8B15-F2911B9E5A76","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F773DE60-18A4-400C-8204-9798A9B73E46:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F773DE60-18A4-400C-8204-9798A9B73E46", generation: 0)
2017-10-12 14:12:59 - DEBUG t,haliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"81780A6B-66B6-4FF1-8B15-F2911B9E5A76","peerAvailable":true,"generation":0,"portNumber":null}'
2017-10-12 14:12:59 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"pe,erIdentifier":"81780A6B-66B6-4FF1-8B15-F2911B9E5A76","peerAvailable":true,"generation":0,"portNumber":null}'
2017-10-12 14:12:59 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 81780A6B-66B6-4FF1-8B15-F2911B9E5A76 (syncValue: gEJPPIcv01JsVa7,pnEgXeSOUUNuOehj0)'
2017-10-12 14:12:59 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "81780A6B-66B6-4FF1-8B15-F2911B9E5A76", generation: 0) crea,t,ing a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "81780A6B-66B6-4FF1-8B15-F2911B9E5A76", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:81780A6B-66B6-4FF1-8B,15-F2911B9E5A76:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-10-12 14:12:59 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChang,ed event from native layer [{"peerAvailable":true,"peerIdentifier":"F773DE60-18A4-400C-8204-9798A9B73E46","generation":0}]'
2017-10-12 14:12:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIde,ntifier":"F773DE60-18A4-400C-8204-9798A9B73E46","generation":0}'
,2017-10-12 14:12:59 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"F773DE60-18A4-400C-8204-9798A9B73E46","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-10-12 14:12:59 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"F773DE60-18A4-400C-8204-9798A9B73E46","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D7CAB270-9BC0-4CDF-BD73-40FA14990958:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D7CAB270-9BC0-4CDF-BD73-40FA14990958", generation: 0)
,2017-10-12 14:12:59 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"D7CAB270-9BC0-4CDF-BD73-40FA14990958","generation":0}]'
,2017-10-12 14:12:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"D7CAB270-9BC0-4CDF-BD73-40FA14990958","generation":0}'
,2017-10-12 14:12:59 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"D7CAB270-9BC0-4CDF-BD73-40FA14990958","peerAvailable":true,"generation":0,"portNumber":null}'
2017-10-12 14:12:59 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"D7CAB270-9BC0-4CDF-BD73-40FA14990958","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-10-12 14:12:59 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"D7CAB270-9BC0-4CDF-BD73-40FA14990958","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F4118EDF-60F4-42F0-BF43-5EB5C47044EE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F4118EDF-60F4-42F0-BF43-5EB5C47044EE", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:410E7270-6EDA-4ECB-8986-F94E54BD9FA2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "410E7270-6EDA-4ECB-8986-F94E54BD9FA2", generation: 0)
2017-10-12 14:13:00 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"410E7270-6EDA-4ECB-8986-F94E54BD9FA2","generation":0}]'
2017-10-12 14:13:00 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"410E7270-6EDA-4ECB-8986-F94E54BD9FA2","generation":0}'
,2017-10-12 14:13:00 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"410E7270-6EDA-4ECB-8986-F94E54BD9FA2","peerAvailable":true,"generation":0,"portNumber":null}'
2017-10-12 14:13:00 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"410E7270-6EDA-4ECB-8986-F94E54BD9FA2","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-10-12 14:13:00 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"410E7270-6EDA-4ECB-8986-F94E54BD9FA2","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:81780A6B-66B6-4FF1-8B15-F2911B9E5A76:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:81,780A6B-66B6-4FF1-8B15-F2911B9E5A76:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "81780A6B-66B6-4FF1-8B15-F2911B9E5A76", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,1780A6B-66B6-4FF1-8B15-F2911B9E5A76", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "81780A6B-66B6-4FF1-8B15-F2911B9E5A76", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:81780A6B-66B6-4FF1-8B15-F2911B9E5A76:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:81780A6B-66B6-4FF1-8B15-F2911B9E5A76:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:81780A6B-66B6-4FF1-8B15-F2911B9E5A76:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:81,780A6B-66B6-4FF1-8B15-F2911B9E5A76:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "81780A6B-66B6-4FF1-8B15-F2911B9E5A76", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,1780A6B-66B6-4FF1-8B15-F2911B9E5A76", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "81780A6B-66B6-4FF1-8B15-F2911B9E5A76", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:81780A6B-66B6-4FF1-8B15-F2911B9E5A76:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:81780A6B-66B6-4FF1-8B15-F2911B9E5A76:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:81780A6B-66B6-4FF1-8B15-F2911B9E5A76:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:81,780A6B-66B6-4FF1-8B15-F2911B9E5A76:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "81780A6B-66B6-4FF1-8B15-F2911B9E5A76", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,1780A6B-66B6-4FF1-8B15-F2911B9E5A76", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "81780A6B-66B6-4FF1-8B15-F2911B9E5A76", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:81780A6B-66B6-4FF1-8B15-F2911B9E5A76:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:81780A6B-66B6-4FF1-8B15-F2911B9E5A76:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:81780A6B-66B6-4FF1-8B15-F2911B9E5A76:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "81780A6B-66B6-4FF1-8B15-F2911B9E5A76", generation: 0)
2017-10-12 14:13:08 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"81780A6B-66B6-4FF1-8B15-F2911B9E5A76","generation":0}]'
2017-10-12 14:13:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"81780A6B-66B6-4FF1-8B15-F2911B9E5A76","generation":0}'
,2017-10-12 14:13:08 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"81780A6B-66B6-4FF1-8B15-F2911B9E5A76","peerAvailable":false,"generation":null,"portNumber":null}'
2017-10-12 14:13:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"81780A6B-66B6-4FF1-8B15-F2911B9E5A76","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:81780A6B-66B6-4FF1-8B15-F2911B9E5A76:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:81,780A6B-66B6-4FF1-8B15-F2911B9E5A76:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "81780A6B-66B6-4FF1-8B15-F2911B9E5A76", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:81780A6B,-66B6-4FF1-8B15-F2911B9E5A76 error: max retries exceeded
2017-10-12 14:13:10 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"gEJPPIcv01JsVa7pnEgXeSOUUNuOehj0","error":"Connection could not be established","portNumber":null}'
2017-1,0-12 14:13:10 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'gEJPPIcv01JsVa7pnEgXeSOUUNuOehj0', error: 'Connection could not be established', listeningPort: '%s''
,2017-10-12 14:13:10 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-10-12 14:13:10 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F773DE60-18A4-400C-8204-9798A9B73E46 (syncValue: e78F9Rb,WKRiZguPdRD31BDuuiZKTB5KF)'
2017-10-12 14:13:10 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F773DE60-18A4-400C-8204-9798A9B73E46", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F773DE60-18A4-400C-8204-9798A9B73E46", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F773DE60-18A4,-400C-8204-9798A9B73E46:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:81780A6B-66B6-4FF1-8B15-F2911B9E5A76:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:F773DE60-18A4-400C-8204-9798A9B73E46:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F7,73DE60-18A4-400C-8204-9798A9B73E46:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "F773DE60-18A4-400C-8204-9798A9B73E46", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,773DE60-18A4-400C-8204-9798A9B73E46", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F773DE60-18A4-400C-8204-9798A9B73E46", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:F773DE60-18A4-400C-8204-9798A9B73E46:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:F773DE60-18A4-400C-8204-9798A9B73E46:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:F773DE60-18A4-400C-8204-9798A9B73E46:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F7,73DE60-18A4-400C-8204-9798A9B73E46:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "F773DE60-18A4-400C-8204-9798A9B73E46", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,773DE60-18A4-400C-8204-9798A9B73E46", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F773DE60-18A4-400C-8204-9798A9B73E46", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:F773DE60-18A4-400C-8204-9798A9B73E46:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:F773DE60-18A4-400C-8204-9798A9B73E46:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:37518B26-8BF7-469C-B92D-28C8738C7E6A
[ThaliCore] Advertiser: session connected Peer(uuid: "F4118EDF-60F4-42F0-BF43-5EB5C47044EE", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:37518B26-8BF7-469C-B92D-28C8738C7E6A state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:F773DE60-18A4-400C-8204-9798A9B73E46:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "F773DE60-18A4-400C-8204-9798A9B73E46", generation: 0)
2017-10-12 14:13:16 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"F773DE60-18A4-400C-8204-9798A9B73E46","generation":0}]'
2017-10-12 14:13:16 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"F773DE60-18A4-400C-8204-9798A9B73E46","generation":0}'
,2017-10-12 14:13:16 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"F773DE60-18A4-400C-8204-9798A9B73E46","peerAvailable":false,"generation":null,"portNumber":null}'
2017-10-12 14:13:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"F773DE60-18A4-400C-8204-9798A9B73E46","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:F773DE60-18A4-400C-8204-9798A9B73E46:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F7,73DE60-18A4-400C-8204-9798A9B73E46:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "F773DE60-18A4-400C-8204-9798A9B73E46", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,773DE60-18A4-400C-8204-9798A9B73E46", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F773DE60-18A4-400C-8204-9798A9B73E46", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-10-12 14:13:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"e78F9RbWKRiZguPdRD31BDuuiZKTB5KF","error":"Peer is unavailable",,"portNumber":null}'
2017-10-12 14:13:18 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'e78F9RbWKRiZguPdRD31BDuuiZKTB5KF', error: 'Peer is unavailable', listeningPort: '%s''
,2017-10-12 14:13:18 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-10-12 14:13:18 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D7CAB270-9BC0-4CDF-BD73-40FA14990958 (syncValue: r9OgYIsGK4lEFptR7phN8D9,Yzf2qlNLk)'
2017-10-12 14:13:18 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D7CAB270-9BC0-4CDF-BD73-40FA14990958", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D7CAB270-9BC0-4CDF-BD73-40FA14990958", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D7CAB270-9BC0-4CDF-BD73-40FA1,4990958:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:37518B26-8BF7-469C-B92D-28C8738C7E6A
,[ThaliCore] Session.deinit peer:F773DE60-18A4-400C-8204-9798A9B73E46:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:37518B26-8BF7-469C-B92D-28C8738C7E6A state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:37518B26-8BF7-469C-B92D-28C8738C7E6A
[ThaliCore] Session.startOutputStream(with:) peer:37518B26-8BF7-469C-B92D-28C8738C7E6A
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [3, 12, 17]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:17
,[ThaliCore] Session.session(_:peer:didChange:) peer:D7CAB270-9BC0-4CDF-BD73-40FA14990958:0 state: notConnected -> connecting
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 116 vsID:17
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:93 count:1 vsID:17
[ThaliCore] VirtualSocket.writePendingData() to write:93 written:93 count:0 vsID:17
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:17
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 179 vsID:17
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:266 count:1 vsID:17
[ThaliCore] VirtualSocket.writePendingData() to write:266 written:266 count:0 vsID:17
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:17
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 117 vsID:17
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:261 count:1 vsID:17
[ThaliCore] VirtualSocket.writePendingData() to write:261 written:261 count:0 vsID:17
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:17
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D7CAB270-9BC0-4CDF-BD73-40FA14990958:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D7CAB270-9BC0-4CDF-BD73-40FA14990958:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "D7CAB270-9BC0-4CDF-BD73-40FA14990958", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52830
2017-10-12 14:13:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"r9OgYIsGK4lEFptR7phN8D9Yzf2qlNLk",,"error":null,"portNumber":52830}'
2017-10-12 14:13:21 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'r9OgYIsGK4lEFptR7phN8D9Yzf2qlNLk', error: 'null', listeningPort: '52830''
,2017-10-12 14:13:21 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) pee,r:D7CAB270-9BC0-4CDF-BD73-40FA14990958:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D7CAB270-9BC0-4CDF-BD73-40FA14990958:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:18 [3, 12, 17, 18]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:18
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:116 count:1 vsID:18
,[ThaliCore] VirtualSocket.writePendingData() to write:116 written:116 count:0 vsID:18
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:18
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 93 vsID:18
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:179 count:1 vsID:18
[ThaliCore] VirtualSocket.writePendingData() to write:179 written:179 count:0 vsID:18
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:18
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 266 vsID:18
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:117 count:1 vsID:18
[ThaliCore] VirtualSocket.writePendingData() to write:117 written:117 count:0 vsID:18
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:18
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 261 vsID:18
,2017-10-12 14:13:21 - DEBUG testUtils: 'Got response data'
,2017-10-12 14:13:21 - DEBUG testUtils: 'Got end'
,ok 284 response body should match testData
,ok 285 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:F4118EDF-60F4-42F0-BF43-5EB5C47044EE
2017-10-12 14:13:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-10-12 14:13:22 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:13:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-10-12 14:13:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:13:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
2017-10-12 14:13:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 286 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-12 14:13:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:13:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:13:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:13:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:17
[ThaliCore] VirtualSocket.closeStreams() vsID:17
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:17
,[ThaliCore] VirtualSocket.deinit vsID:17 [3, 12, 18]
,[ThaliCore] BrowserManager.disconnect peer:D7CAB270-9BC0-4CDF-BD73-40FA14990958
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:52830
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] VirtualSocket.closeStreams() vsID:18
,[ThaliCore] VirtualSocket exited RunLoop vsID:18
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] VirtualSocket.deinit vsID:18 [3, 12]
,[ThaliCore] Session.disconnect() peer:D7CAB270-9BC0-4CDF-BD73-40FA14990958:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D7CAB270-9BC0-4CDF-BD73-40FA14990958:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "D7CAB270-9BC0-4CDF-BD73-40FA14990958", generation: 0)
,2017-10-12 14:13:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:13:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:13:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:13:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:13:22 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:13:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:13:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:13:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-10-12 14:13:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"r9OgYIsGK4lEFptR7phN8D9Yzf2qlNLk","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:37518B26-8BF7-469C-B92D-28C8738C7E6A state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "F4118EDF-60F4-42F0-BF43-5EB5C47044EE", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:37518B26-8BF7-469C-B92D-28C8738C7E6A
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:D7CAB270-9BC0-4CDF-BD73-40FA14990958:0
[ThaliCore] BrowserRelay.deinit
,# calls correct starts when network changes
,2017-10-12 14:13:23 - DEBUG CoordinatedClient: 'test was skipped, name: 'calls correct starts when network changes''
,# teardown
,ok 287 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:13:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:13:23 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:13:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-10-12 14:13:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:13:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-12 14:13:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-12 14:13:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:13:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:13:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:13:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:13:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:13:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:37518B26-8BF7-469C-B92D-28C8738C7E6A
,# test to coordinate connection cut
,# teardown
,ok 288 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-12 14:13:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-12 14:13:23 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-12 14:13:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-10-12 14:13:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-12 14:13:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-12 14:13:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-12 14:13:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-12 14:13:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-12 14:13:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-12 14:13:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-12 14:13:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-12 14:13:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests after connections are cut
,2017-10-12 14:13:24 - DEBUG thaliMobileNativeWrapper: 'listening 52832'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:ECD60A6A-D6F6-46A7-875A-934594B43C95
[ThaliCore] Browser.st,artListening
,2017-10-12 14:13:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-10-12 14:13:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:13:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F7B780B3-E5D5-4724-94CC-B034C67019CD", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:F7B780B3-E5D5-,4724-94CC-B034C67019CD
2017-10-12 14:13:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-10-12 14:13:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"adv,e,rtisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-12 14:13:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D7CAB270-9BC0-4CDF-BD73-40FA14990958:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D7CAB270-9BC0-4CDF-BD73-40FA14990958", generation: 0)
,2017-10-12 14:13:24 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"D7CAB270-9BC0-4CDF-BD73-40FA14990958","generation":0}]'
2017-10-12 14:13:24 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"D7CAB270-9BC0-4CDF-BD73-40FA14990958","generation":0}'
,2017-10-12 14:13:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"D7CAB270-9BC0-4CDF-BD73-40FA14990958","peerAvailable":true,"generation":0,"portNumber":null}'
[ThaliCore] Browser.browser(_:foundPeer:withDi,scoveryInfo:) found peer:410E7270-6EDA-4ECB-8986-F94E54BD9FA2:0
2017-10-12 14:13:24 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"D7CAB270-9BC0-4CDF-BD73-40FA14990958","peerAvailable":true,"generation":0,"portNumber":null}'
[Thali,Core] BrowserManager.foundPeerHandler peer:Peer(uuid: "410E7270-6EDA-4ECB-8986-F94E54BD9FA2", generation: 0)
,2017-10-12 14:13:24 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D7CAB270-9BC0-4CDF-BD73-40FA14990958 (syncValue: XFax21hxEary4JNPDsWk5B7ooOci3Owj)'
2017-10-12 14:13:24 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[T,haliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D7CAB270-9BC0-4CDF-BD73-40FA14990958", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D7CA,B270-9BC0-4CDF-BD73-40FA14990958", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D7CAB270-9BC0-4CDF-BD73-40FA14990958:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] ,TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-10-12 14:13:24 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"410E7270-6EDA-4ECB-8986-F94E54BD9FA2","generation":0}]'
,2017-10-12 14:13:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"410E7270-6EDA-4ECB-8986-F94E54BD9FA2","generation":0}'
,2017-10-12 14:13:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"410E7270-6EDA-4ECB-8986-F94E54BD9FA2","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-10-12 14:13:24 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"410E7270-6EDA-4ECB-8986-F94E54BD9FA2","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-10-12 14:13:24 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FB421661-2DB1-4A56-B4CE-BFB2D97775BD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FB421661-2DB1-4A56-B4CE-BFB2D97775BD", generation: 0)
2017-10-12 14:13:25 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"FB421661-2DB1-4A56-B4CE-BFB2D97775BD","generation":0}]'
2017-10-12 14:13:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"FB421661-2DB1-4A56-B4CE-BFB2D97775BD","generation":0}'
2017-10-12 14:13:25 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"FB421661-2DB1-4A56-,B4CE-BFB2D97775BD","peerAvailable":true,"generation":0,"portNumber":null}'
2017-10-12 14:13:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"FB421661-2DB1-4A56-B4CE-BFB2D97775BD","connectionType":"MPCF","peerAv,a[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D5C8287F-80CD-4EE0-B744-DD990FEE672B:0
ilable":true,"generation":0,"newAddressPort":false}'
2017-10-12 14:13:25 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":",FB421661-2DB1-4A56-B4CE-BFB2D97775BD","peerAvailable":true,"generation":0,"portNumber":null}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D5C8287F-80CD-4EE0-B744-DD990FEE672B", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withD,iscoveryInfo:) found peer:F7B780B3-E5D5-4724-94CC-B034C67019CD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F7B780B3-E5D5-4724-94CC-B034C67019CD", generation: 0)
,2017-10-12 14:13:25 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"D5C8287F-80CD-4EE0-B744-DD990FEE672B","generation":0}]'
,2017-10-12 14:13:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"D5C8287F-80CD-4EE0-B744-DD990FEE672B","generation":0}'
,2017-10-12 14:13:25 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"D5C8287F-80CD-4EE0-B744-DD990FEE672B","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-10-12 14:13:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"D5C8287F-80CD-4EE0-B744-DD990FEE672B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-10-12 14:13:25 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"D5C8287F-80CD-4EE0-B744-DD990FEE672B","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:D7CAB270-9BC0-4CDF-BD73-40FA14990958:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D7,CAB270-9BC0-4CDF-BD73-40FA14990958:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "D7CAB270-9BC0-4CDF-BD73-40FA14990958", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,7CAB270-9BC0-4CDF-BD73-40FA14990958", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D7CAB270-9BC0-4CDF-BD73-40FA14990958", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:D7CAB270-9BC0-4CDF-BD73-40FA14990958:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:D7CAB270-9BC0-4CDF-BD73-40FA14990958:0
[ThaliCore] BrowserRelay.deinit
,2017-10-12 14:13:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:13:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:D7CAB270-9BC0-4CDF-BD73-40FA14990958:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "D7CAB270-9BC0-4CDF-BD73-40FA14990958", generation: 0)
2017-10-12 14:13:27 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"D7CAB270-9BC0-4CDF-BD73-40FA14990958","generation":0}]'
2017-10-12 14:13:27 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"D7CAB270-9BC0-4CDF-BD73-40FA14990958","generation":0}'
,2017-10-12 14:13:27 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"D7CAB270-9BC0-4CDF-BD73-40FA14990958","peerAvailable":false,"generation":null,"portNumber":null}'
2017-10-12 14:13:27 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"D7CAB270-9BC0-4CDF-BD73-40FA14990958","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:D7CAB270-9BC0-4CDF-BD73-40FA14990958:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D7,CAB270-9BC0-4CDF-BD73-40FA14990958:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "D7CAB270-9BC0-4CDF-BD73-40FA14990958", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,7CAB270-9BC0-4CDF-BD73-40FA14990958", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D7CAB270-9BC0-4CDF-BD73-40FA14990958", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-10-12 14:13:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"XFax21hxEary4JNPDsWk5B7ooOci3Owj","error":"Peer is unavailable","portNumber":null}'
2017-10-12 14:13:29 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'XFax21hxEary4JNPDsWk5B7ooOci3Owj', error: 'Peer is unavailable', listeningPort: '%s''
,2017-10-12 14:13:29 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-10-12 14:13:29 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 410E7270-6EDA-4ECB-8986-F94E54BD9FA2 (syncValue: NU1KEEqI6JmJHxhi0LtIWWU,br2Lyh4h7)'
2017-10-12 14:13:29 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "410E7270-6EDA-4ECB-8986-F94E54BD9FA2", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "410E7270-6EDA-4ECB-8986-F94E54BD9FA2", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:410E7270-6EDA-4ECB-8986-F94E5,4BD9FA2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:D7CAB270-9BC0-4CDF-BD73-40FA14990958:0
[ThaliCore] BrowserRelay.deinit
,2017-10-12 14:13:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:13:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,[ThaliCore] Session.session(_:peer:didChange:) peer:410E7270-6EDA-4ECB-8986-F94E54BD9FA2:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:41,0E7270-6EDA-4ECB-8986-F94E54BD9FA2:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "410E7270-6EDA-4ECB-8986-F94E54BD9FA2", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,10E7270-6EDA-4ECB-8986-F94E54BD9FA2", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "410E7270-6EDA-4ECB-8986-F94E54BD9FA2", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:410E7270-6EDA-4ECB-8986-F94E54BD9FA2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:410E7270-6EDA-4ECB-8986-F94E54BD9FA2:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:410E7270-6EDA-4ECB-8986-F94E54BD9FA2:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:41,0E7270-6EDA-4ECB-8986-F94E54BD9FA2:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "410E7270-6EDA-4ECB-8986-F94E54BD9FA2", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,10E7270-6EDA-4ECB-8986-F94E54BD9FA2", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "410E7270-6EDA-4ECB-8986-F94E54BD9FA2", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:410E7270-6EDA-4ECB-8986-F94E54BD9FA2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:410E7270-6EDA-4ECB-8986-F94E54BD9FA2:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:410E7270-6EDA-4ECB-8986-F94E54BD9FA2:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "410E7270-6EDA-4ECB-8986-F94E54BD9FA2", generation: 0)
2017-10-12 14:13:36 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"410E7270-6EDA-4ECB-8986-F94E54BD9FA2","generation":0}]'
2017-10-12 14:13:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"410E7270-6EDA-4ECB-8986-F94E54BD9FA2","generation":0}'
,2017-10-12 14:13:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"410E7270-6EDA-4ECB-8986-F94E54BD9FA2","peerAvailable":false,"generation":null,"portNumber":null}'
2017-10-12 14:13:36 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"410E7270-6EDA-4ECB-8986-F94E54BD9FA2","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:410E7270-6EDA-4ECB-8986-F94E54BD9FA2:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:41,0E7270-6EDA-4ECB-8986-F94E54BD9FA2:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "410E7270-6EDA-4ECB-8986-F94E54BD9FA2", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,10E7270-6EDA-4ECB-8986-F94E54BD9FA2", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "410E7270-6EDA-4ECB-8986-F94E54BD9FA2", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-10-12 14:13:37 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"NU1KEEqI6JmJHxhi0LtIWWUbr2Lyh4h7","error":"Peer is unavailable",,"portNumber":null}'
2017-10-12 14:13:37 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'NU1KEEqI6JmJHxhi0LtIWWUbr2Lyh4h7', error: 'Peer is unavailable', listeningPort: '%s''
,2017-10-12 14:13:37 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-10-12 14:13:37 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for FB421661-2DB1-4A56-B4CE-BFB2D97775BD (syncValue: yylMJEnNEKOa7L5RRRlBDl6,VtuImgzDB)'
2017-10-12 14:13:37 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FB421661-2DB1-4A56-B4CE-BFB2D97775BD", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FB421661-2DB1-4A56-B4CE-BFB2D97775BD", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FB421661-2DB1-4A56-B4CE-BFB2D,97775BD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:410E7270-6EDA-4ECB-8986-F94E54BD9FA2:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:FB421661-2DB1-4A56-B4CE-BFB2D97775BD:0 state: notConnected -> connecting
,2017-10-12 14:13:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:13:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FB421661-2DB1-4A56-B4CE-BFB2D97775BD:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:FB421661-2DB1-4A56-B4CE-BFB2D97775BD:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "FB421661-2DB1-4A56-B4CE-BFB2D97775BD", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52852
2017-10-12 14:13:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"yylMJEnNEKOa7L5RRRlBDl6VtuImgzDB",,"error":null,"portNumber":52852}'
2017-10-12 14:13:41 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'yylMJEnNEKOa7L5RRRlBDl6VtuImgzDB', error: 'null', listeningPort: '52852''
,2017-10-12 14:13:41 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FB421661-2DB1-4A56-B4CE-BFB2D97775BD:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FB421661-2DB1-4A56-B4CE-BFB2D97775BD:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [3, 12, 19]
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:19
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:116 count:1 vsID:19
,[ThaliCore] VirtualSocket.writePendingData() to write:116 written:116 count:0 vsID:19
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:19
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 93 vsID:19
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:179 count:1 vsID:19
,[ThaliCore] VirtualSocket.writePendingData() to write:179 written:179 count:0 vsID:19
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:19
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 266 vsID:19
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:117 count:1 vsID:19
[ThaliCore] VirtualSocket.writePendingData() to write:117 written:117 count:0 vsID:19
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:19
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 261 vsID:19
,2017-10-12 14:13:41 - DEBUG testUtils: 'Got response data'
,2017-10-12 14:13:41 - DEBUG testUtils: 'Got end'
,ok 289 response body should match testData
,ok 290 must be started
,# teardown
,2017-10-12 14:13:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:13:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:13:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:13:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:14:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:14:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:14:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:14:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:14:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:14:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:14:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:14:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
2017-10-12 14:14:41 - INFO, CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server ,that is not listening yet witheatNotRunning set to true'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOG,GER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoin,ts plugin delay interval'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue, and run in order'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
2017-10-12 14:,14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
2017-10-12 14:14:41 - INFO CoordinatedCl,ient: '***TEST_LOGGER result: passed - another'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
2017-10-12 14:14:41 - INF,O CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: pa,ssed - test sinon sansbox stub override'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore aft,er test end'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
2017-10-12 14:14:41 - INFO Coordinat,edClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result:, passed - peerAvailabilityChange is called'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
2017-,10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
2017-10-12 14:14:41 - INFO Coordina,tedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
20,17-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying ,to double connect to a peer on Android'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
2017-10-12 14:14:41 - INFO Coordinate,dClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListe,ning - destroying the local connection kills the connection to the remote peer'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiConnect properly fails on legal but non-existent peerID'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with invalid syncValue'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call disconnect with invalid peer id'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - disconnect doesn't fail on plausible but bogus peer ID'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Get same port when trying to connect mult,iple times on iOS'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - initial peer discovery'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 1'
2017-10-12 14:14:41 - INF,O CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 2'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - check latest peer discovery'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER res,ult: skipped - Set up for no peer discovery test'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - no peer discovery'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling createNativeListen,er directly rejects'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits incomingConnectionState'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server connections all up'
2017-10-12 14:14:41 - INFO C,oordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - clo,sing the whole server cleans everything up'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
2017-10-12 14:14:41 - IN,FO CoordinatedClient: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can create servers manag,er'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling stop without start causes error'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can start/stop servers manager'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connect,ion'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single local http request'
2017-10-12 14:14:41 - INFO Co,ordinatedClient: '***TEST_LOGGER result: passed - Single coordinated request ios native'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple local http requests'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_L,OGGER result: passed - Multiple coordinated request ios native'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
2017-10-12 14:14:41 - INFO CoordinatedClient:, '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startL,isteningForAdvertisements many times'
,2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #st,opAdvertisingAndListening many times'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status before starting'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - error returned, with bad router'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are started when we call start'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP Servers Manager should be nul,l when we call start on iOS'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are stopped when we call stop'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateCon,nection is properly hooked up'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateConnection is return error if we get called on iOS'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: ski,pped - make sure terminateListener is properly hooked up'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateListener is return error if we get called on iOS'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure we actually call kill connections properly'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received'
2017-10-,12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire ,failedNativeConnection event when we get failedConnection from multiConnectConnection'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER ,result: skipped - make sure bad PSK connections fail'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer changes handled from a queue'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - relay,ing discoveryAdvertisingStateUpdateNonTCP'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received'
2017-10-12 14:14:41 - INFO CoordinatedCl,ient: '***TEST_LOGGER result: passed - we successfully receive and replay discoveryAdvertisingStateUpdate'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber, on iOS'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests between peers'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can still do HTTP requests between peers with coord,inator'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - calls correct starts when network changes'
2017-10-12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test to coordinate connection cut'
2017-10-,12 14:14:41 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - can do HTTP requests after connections are cut, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369,C0043/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/ti,mers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1
''
2017-10-12 14:14:41 - ERROR Coord,inatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-10-12 14:14:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:14:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:14:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:14:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:15:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:15:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:15:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:15:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:15:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:15:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:15:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:15:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:15:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:15:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4,980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:16:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:16:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:16:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:16:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:16:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:16:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:16:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:16:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:16:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:16:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:16:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:16:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:17:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:17:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:17:01 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:350:16
$9@timers.js:120:1
''
,2017-10-12 14:17:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:17:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:17:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:17:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:17:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:17:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:17:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:17:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:17:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:17:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:18:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:18:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:18:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:18:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:18:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:18:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:18:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:18:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:18:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:18:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:18:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:18:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:19:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:19:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:19:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:19:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:19:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:19:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:19:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:19:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:19:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:19:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4,980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:19:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:19:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:20:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:20:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:20:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:20:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:20:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:20:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:20:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:20:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:20:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:20:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4,980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:20:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:20:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:21:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:21:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:21:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:21:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:21:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:21:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:21:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:21:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:21:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:21:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:21:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:21:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:22:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:22:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:22:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:22:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:22:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:22:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:22:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:22:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:22:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:22:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:22:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:22:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:23:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:23:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:23:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:23:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:23:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:23:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:23:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:23:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:23:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:23:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:23:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:23:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:24:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:24:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:24:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:24:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:24:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:24:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:24:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:24:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:24:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:24:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:24:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:24:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:25:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:25:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:25:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:25:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:25:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:25:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:25:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:25:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:25:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:25:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:25:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:25:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:26:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:26:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:26:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:26:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:26:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:26:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:26:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:26:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:26:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:26:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:26:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:26:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:27:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:27:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:27:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:27:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:27:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:27:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:27:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:27:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:27:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:27:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-12 14:27:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-498,0-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-12 14:27:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/36AC1659-0B1F-4980-851A-EBC5369C0043/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''

```
